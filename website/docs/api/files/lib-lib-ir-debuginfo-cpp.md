---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/debuginfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DebugInfo.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">llvm-c/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">llvm/IR/DIBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">llvm/IR/DebugProgramInstruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gvmaterializer-h">llvm/IR/GVMaterializer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
#include "llvm/BinaryFormat/Dwarf.def"
#include "llvm/IR/Metadata.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-debuginfo-cpp-">anonymous{DebugInfo.cpp}</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-debuginfo-cpp-/debugtypeinforemoval">DebugTypeInfoRemoval</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class to downgrade -g metadata to -gline-tables-only metadata. <a href="/web-llvm/docs/api/classes/anonymous-debuginfo-cpp-/debugtypeinforemoval/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntrinsicT, bool DbgAssignAndValuesOnly&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac43142f662a5dd59c09abd92322a9821">findDbgIntrinsics</a> (SmallVectorImpl&lt; IntrinsicT * &gt; &amp;Result, Value *V, SmallVectorImpl&lt; DbgVariableRecord * &gt; *DbgVariableRecords)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a60230fc7fed1d9eca1f2a89098364">updateLoopMetadataDebugLocationsImpl</a> (MDNode *OrigLoopID, function_ref&lt; Metadata *(Metadata *)&gt; Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ce3a67baafe11cb1484e0a1fc2b451">isDILocationReachable</a> (SmallPtrSetImpl&lt; Metadata * &gt; &amp;Visited, SmallPtrSetImpl&lt; Metadata * &gt; &amp;Reachable, Metadata *MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a node is a <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> or if a <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> is indirectly referenced by one of the node's children. <a href="#af9ce3a67baafe11cb1484e0a1fc2b451">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc4df7597bb478e068d19916b187ef65">isAllDILocation</a> (SmallPtrSetImpl&lt; Metadata * &gt; &amp;Visited, SmallPtrSetImpl&lt; Metadata * &gt; &amp;AllDILocation, const SmallPtrSetImpl&lt; Metadata * &gt; &amp;DIReachable, Metadata *MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a063e0f7f97a2cf494f8fff2e566bde">stripLoopMDLoc</a> (const SmallPtrSetImpl&lt; Metadata * &gt; &amp;AllDILocation, const SmallPtrSetImpl&lt; Metadata * &gt; &amp;DIReachable, Metadata *MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a417bd37b1f7e5061fd57036f3160b288">stripDebugLocFromLoopID</a> (MDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fb21c837dc04c6def8040f838b51f2e">map_from_llvmDWARFsourcelanguage</a> (LLVMDWARFSourceLanguage lang)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DIT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> (LLVMMetadataRef Ref)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a> (LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3f6763a7cdf20068a5eaae7373e91f7">map_to_llvmDIFlags</a> (DINode::DIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#aee46b4d49ad15932fe2706f1d308d4e9">DISubprogram::DISPFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11192367cc63da8f6cd8415d7d93b56a">pack_into_DISPFlags</a> (bool IsLocalToUnit, bool IsDefinition, bool IsOptimized)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a619cfadc608f78f1b1ac61c885ea2bbc">calculateFragmentIntersectImpl</a> (const DataLayout &amp;DL, const Value *Dest, uint64_t SliceOffsetInBits, uint64_t SliceSizeInBits, const T *AssignRecord, std::optional&lt; DIExpression::FragmentInfo &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FIXME: Remove this wrapper function and call <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a4ea8623be899e029827af260965c860d">DIExpression::calculateFragmentIntersect</a> directly. <a href="#a619cfadc608f78f1b1ac61c885ea2bbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/at/assignmentinfo">AssignmentInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb6a2b1b5242599e12b7fe897140eda3">getAssignmentInfoImpl</a> (const DataLayout &amp;DL, const Value *StoreDest, TypeSize SizeInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect constant properies (base, size, offset) of <span class="doxyComputerOutput">StoreDest</span>. <a href="#afb6a2b1b5242599e12b7fe897140eda3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b051a25ba281897b4dc62df58312b7e">emitDbgAssign</a> (AssignmentInfo Info, Value *Val, Value *Dest, Instruction &amp;StoreLikeInst, const VarRecord &amp;VarRec, DIBuilder &amp;DIB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns nullptr if the assignment shouldn't be attributed to this variable. <a href="#a9b051a25ba281897b4dc62df58312b7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07dca79c487ad44ed9f03cfde69c7747">setAssignmentTrackingModuleFlag</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9239698ab535528bfcba30502b5c1d1">getAssignmentTrackingModuleFlag</a> (const Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga731cad87060764d2639a9b661b88f3d4">LLVMDebugMetadataVersion</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current debug metadata version number. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga731cad87060764d2639a9b661b88f3d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3e4ab5c187c85469fa148ba496ad785c">LLVMCreateDIBuilderDisallowUnresolved</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a builder for a module, and do not allow for unresolved nodes attached to the module. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3e4ab5c187c85469fa148ba496ad785c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga47bd8cf5e928bfd6e2dbbc41bef906e8">LLVMCreateDIBuilder</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a builder for a module and collect unresolved nodes attached to the module in order to resolve cycles during a call to <span class="doxyComputerOutput">LLVMDIBuilderFinalize</span>. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga47bd8cf5e928bfd6e2dbbc41bef906e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga75216df9fb21497235b8dc0da3f77cd2">LLVMGetModuleDebugMetadataVersion</a> (LLVMModuleRef Module)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The version of debug metadata that's present in the provided <span class="doxyComputerOutput">Module</span>. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga75216df9fb21497235b8dc0da3f77cd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac86aed2f5553740f151cb1905d4718ee">LLVMStripModuleDebugInfo</a> (LLVMModuleRef Module)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Strip debug info in the module if it exists. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac86aed2f5553740f151cb1905d4718ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf36ccab6f24f7aa2fab88270756bf952">LLVMDisposeDIBuilder</a> (LLVMDIBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocates the <span class="doxyComputerOutput">DIBuilder</span> and everything it owns. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf36ccab6f24f7aa2fab88270756bf952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2137b1dffc60225e2d26756f299a2223">LLVMDIBuilderFinalize</a> (LLVMDIBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct any deferred debug info descriptors. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2137b1dffc60225e2d26756f299a2223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabc75effdb1e1cc44b4393c7716e7f5d2">LLVMDIBuilderFinalizeSubprogram</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Subprogram)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize a specific subprogram. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabc75effdb1e1cc44b4393c7716e7f5d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac80c97dafb7ed1815c40df3e29ac574d">LLVMDIBuilderCreateCompileUnit</a> (LLVMDIBuilderRef Builder, LLVMDWARFSourceLanguage Lang, LLVMMetadataRef FileRef, const char *Producer, size_t ProducerLen, LLVMBool isOptimized, const char *Flags, size_t FlagsLen, unsigned RuntimeVer, const char *SplitName, size_t SplitNameLen, LLVMDWARFEmissionKind Kind, unsigned DWOId, LLVMBool SplitDebugInlining, LLVMBool DebugInfoForProfiling, const char *SysRoot, size_t SysRootLen, const char *SDK, size_t SDKLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CompileUnit provides an anchor for all debugging information generated during this instance of compilation. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac80c97dafb7ed1815c40df3e29ac574d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaee236259f740de70edbb17b7a274aa3f">LLVMDIBuilderCreateFile</a> (LLVMDIBuilderRef Builder, const char *Filename, size_t FilenameLen, const char *Directory, size_t DirectoryLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a file descriptor to hold debugging information for a file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaee236259f740de70edbb17b7a274aa3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a47cdee54f0b80f9ba952d766582f97">LLVMDIBuilderCreateModule</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentScope, const char *Name, size_t NameLen, const char *ConfigMacros, size_t ConfigMacrosLen, const char *IncludePath, size_t IncludePathLen, const char *APINotesFile, size_t APINotesFileLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new descriptor for a module with the specified parent scope. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a47cdee54f0b80f9ba952d766582f97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga28cb215b1180c262f2a29d811fef274f">LLVMDIBuilderCreateNameSpace</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentScope, const char *Name, size_t NameLen, LLVMBool ExportSymbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new descriptor for a namespace with the specified parent scope. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga28cb215b1180c262f2a29d811fef274f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga16e177b130697369b80b40e2a6e4b4bd">LLVMDIBuilderCreateFunction</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, const char *LinkageName, size_t LinkageNameLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool IsLocalToUnit, LLVMBool IsDefinition, unsigned ScopeLine, LLVMDIFlags Flags, LLVMBool IsOptimized)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified subprogram. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga16e177b130697369b80b40e2a6e4b4bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad66fcc89d7abf993d470cc20459ac6c3">LLVMDIBuilderCreateLexicalBlock</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Line, unsigned Column)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a lexical block with the specified parent context. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad66fcc89d7abf993d470cc20459ac6c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233939d145977e24bad18c7a27718fba">LLVMDIBuilderCreateLexicalBlockFile</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Discriminator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a lexical block with a new file attached. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233939d145977e24bad18c7a27718fba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4bd7b93a5adab9a1c2e0115d6fd27aaa">LLVMDIBuilderCreateImportedModuleFromNamespace</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef NS, LLVMMetadataRef File, unsigned Line)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported namespace. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4bd7b93a5adab9a1c2e0115d6fd27aaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga79b2014998173c73f1643a12d125f57d">LLVMDIBuilderCreateImportedModuleFromAlias</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef ImportedEntity, LLVMMetadataRef File, unsigned Line, LLVMMetadataRef *Elements, unsigned NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported module that aliases another imported entity descriptor. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga79b2014998173c73f1643a12d125f57d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0fb25118742415266bc77ba402c0be3e">LLVMDIBuilderCreateImportedModuleFromModule</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef M, LLVMMetadataRef File, unsigned Line, LLVMMetadataRef *Elements, unsigned NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported module. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0fb25118742415266bc77ba402c0be3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaecac3bea8780aabc755043bf56ccde16">LLVMDIBuilderCreateImportedDeclaration</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef Decl, LLVMMetadataRef File, unsigned Line, const char *Name, size_t NameLen, LLVMMetadataRef *Elements, unsigned NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported function, type, or variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaecac3bea8780aabc755043bf56ccde16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga297455fb958aa499228de05966751977">LLVMDIBuilderCreateDebugLocation</a> (LLVMContextRef Ctx, unsigned Line, unsigned Column, LLVMMetadataRef Scope, LLVMMetadataRef InlinedAt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new DebugLocation that describes a source location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga297455fb958aa499228de05966751977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac367fff632214b9cb6a7c72a560c6375">LLVMDILocationGetLine</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the line number of this debug location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac367fff632214b9cb6a7c72a560c6375">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5d3f8954443857acd2f3e63e924af5bb">LLVMDILocationGetColumn</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the column number of this debug location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5d3f8954443857acd2f3e63e924af5bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4b79e6d86d287cbd5a2bad9d890d0cf6">LLVMDILocationGetScope</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the local scope associated with this debug location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4b79e6d86d287cbd5a2bad9d890d0cf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga02154723977a1df274e6dd6cab1b3c12">LLVMDILocationGetInlinedAt</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the "inline at" location associated with this debug location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga02154723977a1df274e6dd6cab1b3c12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabb1ada7b7f03079b1a3fc26d45a872c8">LLVMDIScopeGetFile</a> (LLVMMetadataRef Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the file associated with a given scope. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabb1ada7b7f03079b1a3fc26d45a872c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6d217da95423a5058437b10d48eb299c">LLVMDIFileGetDirectory</a> (LLVMMetadataRef File, unsigned *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the directory of a given file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6d217da95423a5058437b10d48eb299c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7080e9914e8708451283d10b69cc8edc">LLVMDIFileGetFilename</a> (LLVMMetadataRef File, unsigned *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of a given file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7080e9914e8708451283d10b69cc8edc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae0a790e33f02c87d24b428da4d2b34ce">LLVMDIFileGetSource</a> (LLVMMetadataRef File, unsigned *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source of a given file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae0a790e33f02c87d24b428da4d2b34ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9ea606817ce85b9915297eb2de2a653d">LLVMDIBuilderCreateMacro</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentMacroFile, unsigned Line, LLVMDWARFMacinfoRecordType RecordType, const char *Name, size_t NameLen, const char *Value, size_t ValueLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a macro. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9ea606817ce85b9915297eb2de2a653d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4f1086f983fe945bf4377c392ed87f4a">LLVMDIBuilderCreateTempMacroFile</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentMacroFile, unsigned Line, LLVMMetadataRef File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information temporary entry for a macro file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4f1086f983fe945bf4377c392ed87f4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga52949afcc1bb31880de9208e6a488329">LLVMDIBuilderCreateEnumerator</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, int64_t Value, LLVMBool IsUnsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an enumerator. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga52949afcc1bb31880de9208e6a488329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0f63a87fe95c032988248173c40836e4">LLVMDIBuilderCreateEnumerationType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, LLVMMetadataRef *Elements, unsigned NumElements, LLVMMetadataRef ClassTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an enumeration. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0f63a87fe95c032988248173c40836e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga90500ff94794b86be3dd73f6d6f3a8a5">LLVMDIBuilderCreateUnionType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags, LLVMMetadataRef *Elements, unsigned NumElements, unsigned RunTimeLang, const char *UniqueId, size_t UniqueIdLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a union. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga90500ff94794b86be3dd73f6d6f3a8a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab3c5243ec4c41efdde6efd665f31c2a9">LLVMDIBuilderCreateArrayType</a> (LLVMDIBuilderRef Builder, uint64_t Size, uint32_t AlignInBits, LLVMMetadataRef Ty, LLVMMetadataRef *Subscripts, unsigned NumSubscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an array. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab3c5243ec4c41efdde6efd665f31c2a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5a3fc221b7877d1efe4e10fe6d586a37">LLVMDIBuilderCreateVectorType</a> (LLVMDIBuilderRef Builder, uint64_t Size, uint32_t AlignInBits, LLVMMetadataRef Ty, LLVMMetadataRef *Subscripts, unsigned NumSubscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a vector type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5a3fc221b7877d1efe4e10fe6d586a37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gacec115e56690a95e2bbf90143b39b3a7">LLVMDIBuilderCreateBasicType</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, uint64_t SizeInBits, LLVMDWARFTypeEncoding Encoding, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a basic type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gacec115e56690a95e2bbf90143b39b3a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafa96c20ff0708be1cabd2c06c9ce03ca">LLVMDIBuilderCreatePointerType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef PointeeTy, uint64_t SizeInBits, uint32_t AlignInBits, unsigned AddressSpace, const char *Name, size_t NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a pointer. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafa96c20ff0708be1cabd2c06c9ce03ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf293a26d4fd886befce34f6ce2a3bdf1">LLVMDIBuilderCreateStructType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags, LLVMMetadataRef DerivedFrom, LLVMMetadataRef *Elements, unsigned NumElements, unsigned RunTimeLang, LLVMMetadataRef VTableHolder, const char *UniqueId, size_t UniqueIdLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a struct. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf293a26d4fd886befce34f6ce2a3bdf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabe5507b0346c326bcbd875dec7dfca91">LLVMDIBuilderCreateMemberType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a member. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabe5507b0346c326bcbd875dec7dfca91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga280cc8b0ba12ddba27a70640961d5aae">LLVMDIBuilderCreateUnspecifiedType</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a DWARF unspecified type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga280cc8b0ba12ddba27a70640961d5aae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7c8d150bba12a1d9874e3d692fd804f6">LLVMDIBuilderCreateStaticMemberType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, LLVMMetadataRef Type, LLVMDIFlags Flags, LLVMValueRef ConstantVal, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a C++ static data member. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7c8d150bba12a1d9874e3d692fd804f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga00f6a1630b3771db5c911f99a4f8dca6">LLVMDIBuilderCreateObjCIVar</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef Ty, LLVMMetadataRef PropertyNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Objective-C instance variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga00f6a1630b3771db5c911f99a4f8dca6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9cbf85a105f1c34719076b29b0830a83">LLVMDIBuilderCreateObjCProperty</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, const char *GetterName, size_t GetterNameLen, const char *SetterName, size_t SetterNameLen, unsigned PropertyAttributes, LLVMMetadataRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Objective-C property. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9cbf85a105f1c34719076b29b0830a83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga20ed80a8dd7b49ba6fcdd9d3d2ac20e5">LLVMDIBuilderCreateObjectPointerType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Type, LLVMBool Implicit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a uniqued DIType* clone with FlagObjectPointer. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga20ed80a8dd7b49ba6fcdd9d3d2ac20e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf237e3bbfe69ee176ae2bf8db9079346">LLVMDIBuilderCreateTypedef</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Type, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Scope, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a typedef. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf237e3bbfe69ee176ae2bf8db9079346">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac57bc2d6025d4be99b2e1b11c91a8904">LLVMDIBuilderCreateInheritance</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Ty, LLVMMetadataRef BaseTy, uint64_t BaseOffset, uint32_t VBPtrOffset, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry to establish inheritance relationship between two types. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac57bc2d6025d4be99b2e1b11c91a8904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga93103e684ef975e27c124279b530f4a4">LLVMDIBuilderCreateForwardDecl</a> (LLVMDIBuilderRef Builder, unsigned Tag, const char *Name, size_t NameLen, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, const char *UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a permanent forward-declared type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga93103e684ef975e27c124279b530f4a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadcfce4b4d1ca9e120e479b56f24378d2">LLVMDIBuilderCreateReplaceableCompositeType</a> (LLVMDIBuilderRef Builder, unsigned Tag, const char *Name, size_t NameLen, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags, const char *UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a temporary forward-declared type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadcfce4b4d1ca9e120e479b56f24378d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga8780f2c20339b37b01f8878401f27d00">LLVMDIBuilderCreateQualifiedType</a> (LLVMDIBuilderRef Builder, unsigned Tag, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a qualified type, e.g. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga8780f2c20339b37b01f8878401f27d00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a2899f83e586e884e2c75811d911742">LLVMDIBuilderCreateReferenceType</a> (LLVMDIBuilderRef Builder, unsigned Tag, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a c++ style reference or rvalue reference type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a2899f83e586e884e2c75811d911742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac54583c434a27a5a1cc2f1a64f1abd6e">LLVMDIBuilderCreateNullPtrType</a> (LLVMDIBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create C++11 nullptr type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac54583c434a27a5a1cc2f1a64f1abd6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5abafa3c43023b3169fae1f22c678049">LLVMDIBuilderCreateMemberPointerType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef PointeeType, LLVMMetadataRef ClassType, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a pointer to member. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5abafa3c43023b3169fae1f22c678049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b2ece29856cc374fa69d6945066f332">LLVMDIBuilderCreateBitFieldMemberType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint64_t OffsetInBits, uint64_t StorageOffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a bit field member. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b2ece29856cc374fa69d6945066f332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabdc3694c6c196a2d7181860b40fb9ac3">LLVMDIBuilderCreateClassType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef DerivedFrom, LLVMMetadataRef *Elements, unsigned NumElements, LLVMMetadataRef VTableHolder, LLVMMetadataRef TemplateParamsNode, const char *UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a class. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabdc3694c6c196a2d7181860b40fb9ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga208f89cfe45c5cfe3fa2c77c9227964f">LLVMDIBuilderCreateArtificialType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a uniqued DIType* clone with FlagArtificial set. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga208f89cfe45c5cfe3fa2c77c9227964f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga829c0e0a5fec733d28b736c072bec4eb">LLVMGetDINodeTag</a> (LLVMMetadataRef MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the dwarf::Tag of a DINode. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga829c0e0a5fec733d28b736c072bec4eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaef39844bc3df500ee733588158eae292">LLVMDITypeGetName</a> (LLVMMetadataRef DType, size_t *Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of this DIType. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaef39844bc3df500ee733588158eae292">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga12af60f959285ba5ff8d568d27dda9a9">LLVMDITypeGetSizeInBits</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of this DIType in bits. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga12af60f959285ba5ff8d568d27dda9a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae9747065099a9912fec575bd7edb7857">LLVMDITypeGetOffsetInBits</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the offset of this DIType in bits. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae9747065099a9912fec575bd7edb7857">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2c1ae3a9365c49a64025df8a64086c2c">LLVMDITypeGetAlignInBits</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the alignment of this DIType in bits. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2c1ae3a9365c49a64025df8a64086c2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga780f4dfcebe39a69b115ae4f0d2b300f">LLVMDITypeGetLine</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source line where this DIType is declared. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga780f4dfcebe39a69b115ae4f0d2b300f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6bcea905cd35ad99a0d535721d8fe4ff">LLVMDITypeGetFlags</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the flags associated with this DIType. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6bcea905cd35ad99a0d535721d8fe4ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadbd363bcd72a98cc8225b11a0ea0f6fa">LLVMDIBuilderGetOrCreateTypeArray</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef *Data, size_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a type array. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadbd363bcd72a98cc8225b11a0ea0f6fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga96266a67a61ce67e77498296bbae2551">LLVMDIBuilderCreateSubroutineType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef File, LLVMMetadataRef *ParameterTypes, unsigned NumParameterTypes, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create subroutine type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga96266a67a61ce67e77498296bbae2551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5821133c41a6cdaea77af97a71ce2ab1">LLVMDIBuilderCreateExpression</a> (LLVMDIBuilderRef Builder, uint64_t *Addr, size_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable which has a complex address expression for its address. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5821133c41a6cdaea77af97a71ce2ab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabd9e7761d1632466c41620b609381644">LLVMDIBuilderCreateConstantValueExpression</a> (LLVMDIBuilderRef Builder, uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable that does not have an address, but does have a constant value. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabd9e7761d1632466c41620b609381644">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga83af94c8ebc30248947274cd3c6b2b18">LLVMDIBuilderCreateGlobalVariableExpression</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, const char *Linkage, size_t LinkLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool LocalToUnit, LLVMMetadataRef Expr, LLVMMetadataRef Decl, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga83af94c8ebc30248947274cd3c6b2b18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b9b6964e6643fc8cd61ea5b7a447ac3">LLVMDIGlobalVariableExpressionGetVariable</a> (LLVMMetadataRef GVE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the <span class="doxyComputerOutput">DIVariable</span> associated with this global variable expression. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b9b6964e6643fc8cd61ea5b7a447ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2d889441ac9541119cc05b65b178bcfe">LLVMDIGlobalVariableExpressionGetExpression</a> (LLVMMetadataRef GVE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the <span class="doxyComputerOutput">DIExpression</span> associated with this global variable expression. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2d889441ac9541119cc05b65b178bcfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7929e8886d3a6c8c121f17dcb2af1dd6">LLVMDIVariableGetFile</a> (LLVMMetadataRef Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the file associated with a given variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7929e8886d3a6c8c121f17dcb2af1dd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2ed3e2ec3f48e55ed167177139d5b14b">LLVMDIVariableGetScope</a> (LLVMMetadataRef Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the scope associated with a given variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2ed3e2ec3f48e55ed167177139d5b14b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad19c6732705efa0c40e2bc0010632303">LLVMDIVariableGetLine</a> (LLVMMetadataRef Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source line where this <span class="doxyComputerOutput">DIVariable</span> is declared. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad19c6732705efa0c40e2bc0010632303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga68d0a34a31a878cc0452697bebf63e1f">LLVMTemporaryMDNode</a> (LLVMContextRef Ctx, LLVMMetadataRef *Data, size_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new temporary <span class="doxyComputerOutput">MDNode</span>. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga68d0a34a31a878cc0452697bebf63e1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga488dddd6a44fa6154d5520c2a76cab41">LLVMDisposeTemporaryMDNode</a> (LLVMMetadataRef TempNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate a temporary node. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga488dddd6a44fa6154d5520c2a76cab41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga704c67d1afa02bfe39cd02b4830c8f3f">LLVMMetadataReplaceAllUsesWith</a> (LLVMMetadataRef TempTargetMetadata, LLVMMetadataRef Replacement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all uses of temporary metadata. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga704c67d1afa02bfe39cd02b4830c8f3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga862c55fb3e10df7538c7883a948df025">LLVMDIBuilderCreateTempGlobalVariableFwdDecl</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, const char *Linkage, size_t LnkLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool LocalToUnit, LLVMMetadataRef Decl, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified global variable that is temporary and meant to be RAUWed. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga862c55fb3e10df7538c7883a948df025">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gacac753a410ba2c99ab8de5a5bb6275aa">LLVMDIBuilderInsertDeclareRecordBefore</a> (LLVMDIBuilderRef Builder, LLVMValueRef Storage, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMValueRef Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gacac753a410ba2c99ab8de5a5bb6275aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga17213bad234b832c6447b97ce0a1cdfa">LLVMDIBuilderInsertDeclareRecordAtEnd</a> (LLVMDIBuilderRef Builder, LLVMValueRef Storage, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMBasicBlockRef Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga17213bad234b832c6447b97ce0a1cdfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad502913d5fbb1891c256136560488409">LLVMDIBuilderInsertDbgValueRecordBefore</a> (LLVMDIBuilderRef Builder, LLVMValueRef Val, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMValueRef Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad502913d5fbb1891c256136560488409">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab976691ac79d65d9ff429b3c5a8f587a">LLVMDIBuilderInsertDbgValueRecordAtEnd</a> (LLVMDIBuilderRef Builder, LLVMValueRef Val, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMBasicBlockRef Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab976691ac79d65d9ff429b3c5a8f587a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga677811d786d2d985b961135a8b0a555b">LLVMDIBuilderCreateAutoVariable</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool AlwaysPreserve, LLVMDIFlags Flags, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a local auto variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga677811d786d2d985b961135a8b0a555b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9390bbfb5a8ea9b429b6086a6fcf957a">LLVMDIBuilderCreateParameterVariable</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, unsigned ArgNo, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool AlwaysPreserve, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a function parameter variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9390bbfb5a8ea9b429b6086a6fcf957a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga45454a88af46c21af848f5f95db5795c">LLVMDIBuilderGetOrCreateSubrange</a> (LLVMDIBuilderRef Builder, int64_t LowerBound, int64_t Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a value range. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga45454a88af46c21af848f5f95db5795c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga07712e5d4d664c623674c09e03c9c011">LLVMDIBuilderGetOrCreateArray</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef *Data, size_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an array of DI Nodes. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga07712e5d4d664c623674c09e03c9c011">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafddfbdaa9a85beba597ca456f2085251">LLVMGetSubprogram</a> (LLVMValueRef Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the subprogram attached to a function. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafddfbdaa9a85beba597ca456f2085251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3fb4cb7331aa97b2bdd91044b5c33fad">LLVMSetSubprogram</a> (LLVMValueRef Func, LLVMMetadataRef SP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the subprogram attached to a function. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3fb4cb7331aa97b2bdd91044b5c33fad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233c8c86bdfa0ceaad5ddbbb5d50fa1d">LLVMDISubprogramGetLine</a> (LLVMMetadataRef Subprogram)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the line associated with a given subprogram. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233c8c86bdfa0ceaad5ddbbb5d50fa1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2f2db17683a598ccfcfe8b0ad33f3040">LLVMInstructionGetDebugLoc</a> (LLVMValueRef Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the debug location for the given instruction. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2f2db17683a598ccfcfe8b0ad33f3040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga50b4ca3bd1b86721e92ac6b411af63c8">LLVMInstructionSetDebugLoc</a> (LLVMValueRef Inst, LLVMMetadataRef Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the debug location for the given instruction. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga50b4ca3bd1b86721e92ac6b411af63c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga71d2155ac54703ed0f1e3e230ef36065">LLVMDIBuilderCreateLabel</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Context, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, LLVMBool AlwaysPreserve)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a label. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga71d2155ac54703ed0f1e3e230ef36065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gace19cbd43c471a934793ba8f66ec16ce">LLVMDIBuilderInsertLabelBefore</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef LabelInfo, LLVMMetadataRef Location, LLVMValueRef InsertBefore)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.label intrinsic call. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gace19cbd43c471a934793ba8f66ec16ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab176ba6b04ac20f7363e3f2315dd7545">LLVMDIBuilderInsertLabelAtEnd</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef LabelInfo, LLVMMetadataRef Location, LLVMBasicBlockRef InsertAtEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.label intrinsic call. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab176ba6b04ac20f7363e3f2315dd7545">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf09a2cd6396ded40b1260ca98a72e434">LLVMMetadataKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga8794c88979fc63df9256714ddad96268">LLVMGetMetadataKind</a> (LLVMMetadataRef Metadata)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the enumerated type of a Metadata instance. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga8794c88979fc63df9256714ddad96268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fbb2cd3e7ca729057610b989666df42">AssignmentTrackingModuleFlag</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70cb3c0d314e41944b65f1bfdaa6457">HANDLE_DW_LANG</a>(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59a8031b78f28120baafcfc27852d8bb">HANDLE_METADATA_LEAF</a>(CLASS)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"assignment-tracking"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### calculateFragmentIntersectImpl() {#a619cfadc608f78f1b1ac61c885ea2bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool calculateFragmentIntersectImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Dest, uint64_t SliceOffsetInBits, uint64_t SliceSizeInBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * AssignRecord, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FIXME: Remove this wrapper function and call <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a4ea8623be899e029827af260965c860d">DIExpression::calculateFragmentIntersect</a> directly.</p>

<p>Definition at line 1938 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a4ea8623be899e029827af260965c860d">llvm::DIExpression::calculateFragmentIntersect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/at/#ad7b73b4fea9ae261dfe1d0141e34d55c">llvm::at::calculateFragmentIntersect</a> and <a href="/web-llvm/docs/api/namespaces/llvm/at/#aee2965aa3f042ce827de5849929bae91">llvm::at::calculateFragmentIntersect</a>.</p>

</div>
</div>

### emitDbgAssign() {#a9b051a25ba281897b4dc62df58312b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitDbgAssign (<a href="/web-llvm/docs/api/structs/llvm/at/assignmentinfo">AssignmentInfo</a> Info, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Dest, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; StoreLikeInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/at/varrecord">VarRecord</a> &amp; VarRec, <a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp; DIB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns nullptr if the assignment shouldn't be attributed to this variable.</p>

<p>Definition at line 2062 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab2fc167f75191e1d22e12e8e382605bb">llvm::DIExpression::createFragmentExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae465cfd07a3ac2e84847e670d92ae8ad">llvm::DbgVariableRecord::createLinkedDVRAssign</a>, <a href="/web-llvm/docs/api/structs/llvm/at/varrecord/#aef07c6fc4c9df3199800ba5decf9c8e0">llvm::at::VarRecord::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a6b5977deeb9f99e156685e190de78403">llvm::DIVariable::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5a6937fcd639ac78a93b48ab6624e957">llvm::DIBuilder::insertDbgAssign</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/at/varrecord/#afa37ef81e1522bc8d78d702c59ad62b1">llvm::at::VarRecord::Var</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/at/#a5c4090098e3eaedb61973431af4898b1">llvm::at::trackAssignments</a>.</p>

</div>
</div>

### findDbgIntrinsics() {#ac43142f662a5dd59c09abd92322a9821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IntrinsicT, bool DbgAssignAndValuesOnly&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void findDbgIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; IntrinsicT * &gt; &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * &gt; * DbgVariableRecords)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#ab3e08d91bdd3730f8658ea55d61e69b1">llvm::DIArgList::getAllDbgVariableRecordUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/localasmetadata/#ab3824551809fd3b92409d32854adff80">llvm::LocalAsMetadata::getIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a43da96a342731ffba21f83523a9c787a">llvm::MetadataAsValue::getIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a26bad0f6e5435a5a4dc50850c5b8f628">llvm::findDbgUsers</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d7448a42ae4db532d3ba40e250ec825">llvm::findDbgValues</a>.</p>

</div>
</div>

### getAssignmentInfoImpl() {#afb6a2b1b5242599e12b7fe897140eda3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AssignmentInfo &gt; getAssignmentInfoImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StoreDest, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> SizeInBits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect constant properies (base, size, offset) of <span class="doxyComputerOutput">StoreDest</span>.</p>


<p>Return std::nullopt if any properties are not constants or the offset from the base pointer is negative.</p>


<p>Definition at line 2017 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab01d8694a759a934e01f1c558c3ce862">llvm::APInt::getLimitedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a23c582e2452eeb2b2cf6e0c43eca617e">llvm::Value::stripAndAccumulateConstantOffsets</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/at/#ae56d26e266b1d9f9e3e8abef9cd76d2a">llvm::at::getAssignmentInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#acba9ed42400327fd80c5ec86803ca1f0">llvm::at::getAssignmentInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/at/#a2d0eb3e7683f09ea28cc50f670b2d0e8">llvm::at::getAssignmentInfo</a>.</p>

</div>
</div>

### getAssignmentTrackingModuleFlag() {#ac9239698ab535528bfcba30502b5c1d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getAssignmentTrackingModuleFlag (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2303 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="#a6fbb2cd3e7ca729057610b989666df42">AssignmentTrackingModuleFlag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa9ef2dbd1b7ce921093f7d4a7bd4cc5c">llvm::isAssignmentTrackingEnabled</a>.</p>

</div>
</div>

### isAllDILocation() {#adc4df7597bb478e068d19916b187ef65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAllDILocation (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; AllDILocation, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; DIReachable, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#adc4df7597bb478e068d19916b187ef65">isAllDILocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#adc4df7597bb478e068d19916b187ef65">isAllDILocation</a>.</p>

</div>
</div>

### isDILocationReachable() {#af9ce3a67baafe11cb1484e0a1fc2b451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDILocationReachable (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; Reachable, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a node is a <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> or if a <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> is indirectly referenced by one of the node's children.</p>

<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#af9ce3a67baafe11cb1484e0a1fc2b451">isDILocationReachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#af9ce3a67baafe11cb1484e0a1fc2b451">isDILocationReachable</a>.</p>

</div>
</div>

### map\_from\_llvmDIFlags() {#a801c923f0e508c12c7c76544bd5b790c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DINode::DIFlags map_from_llvmDIFlags (<a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1040 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga677811d786d2d985b961135a8b0a555b">LLVMDIBuilderCreateAutoVariable</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gacec115e56690a95e2bbf90143b39b3a7">LLVMDIBuilderCreateBasicType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b2ece29856cc374fa69d6945066f332">LLVMDIBuilderCreateBitFieldMemberType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabdc3694c6c196a2d7181860b40fb9ac3">LLVMDIBuilderCreateClassType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga16e177b130697369b80b40e2a6e4b4bd">LLVMDIBuilderCreateFunction</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac57bc2d6025d4be99b2e1b11c91a8904">LLVMDIBuilderCreateInheritance</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5abafa3c43023b3169fae1f22c678049">LLVMDIBuilderCreateMemberPointerType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabe5507b0346c326bcbd875dec7dfca91">LLVMDIBuilderCreateMemberType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga00f6a1630b3771db5c911f99a4f8dca6">LLVMDIBuilderCreateObjCIVar</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9390bbfb5a8ea9b429b6086a6fcf957a">LLVMDIBuilderCreateParameterVariable</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadcfce4b4d1ca9e120e479b56f24378d2">LLVMDIBuilderCreateReplaceableCompositeType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7c8d150bba12a1d9874e3d692fd804f6">LLVMDIBuilderCreateStaticMemberType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf293a26d4fd886befce34f6ce2a3bdf1">LLVMDIBuilderCreateStructType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga96266a67a61ce67e77498296bbae2551">LLVMDIBuilderCreateSubroutineType</a> and <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga90500ff94794b86be3dd73f6d6f3a8a5">LLVMDIBuilderCreateUnionType</a>.</p>

</div>
</div>

### map\_from\_llvmDWARFsourcelanguage() {#a8fb21c837dc04c6def8040f838b51f2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned map_from_llvmDWARFsourcelanguage (<a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4436852644d626940ee2edc2ffb65880">LLVMDWARFSourceLanguage</a> lang)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac80c97dafb7ed1815c40df3e29ac574d">LLVMDIBuilderCreateCompileUnit</a>.</p>

</div>
</div>

### map\_to\_llvmDIFlags() {#ac3f6763a7cdf20068a5eaae7373e91f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDIFlags map_to_llvmDIFlags (<a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6bcea905cd35ad99a0d535721d8fe4ff">LLVMDITypeGetFlags</a>.</p>

</div>
</div>

### pack\_into\_DISPFlags() {#a11192367cc63da8f6cd8415d7d93b56a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram::DISPFlags pack_into_DISPFlags (bool IsLocalToUnit, bool IsDefinition, bool IsOptimized)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#a7854a45d655a2b9979b3c429b8fef3fd">llvm::DISubprogram::toSPFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga16e177b130697369b80b40e2a6e4b4bd">LLVMDIBuilderCreateFunction</a>.</p>

</div>
</div>

### setAssignmentTrackingModuleFlag() {#a07dca79c487ad44ed9f03cfde69c7747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setAssignmentTrackingModuleFlag (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2297 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="#a6fbb2cd3e7ca729057610b989666df42">AssignmentTrackingModuleFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a> and <a href="/web-llvm/docs/api/classes/llvm/module/#a0a5c55e12c97b80021330fe82b642293a89821032d3b24b6a135f1d5acfbcd2c8">llvm::Module::Max</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackingpass/#a56ff79a9fa9dba1d34f2e7d55319b6cb">llvm::AssignmentTrackingPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackingpass/#a809e420808034e2e213e44b485fed902">llvm::AssignmentTrackingPass::run</a>.</p>

</div>
</div>

### stripDebugLocFromLoopID() {#a417bd37b1f7e5061fd57036f3160b288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * stripDebugLocFromLoopID (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a1a063e0f7f97a2cf494f8fff2e566bde">stripLoopMDLoc</a> and <a href="#a35a60230fc7fed1d9eca1f2a89098364">updateLoopMetadataDebugLocationsImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a21fc2a53fec95633917f4135b7ab645e">llvm::stripDebugInfo</a>.</p>

</div>
</div>

### stripLoopMDLoc() {#a1a063e0f7f97a2cf494f8fff2e566bde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * stripLoopMDLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; AllDILocation, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; &amp; DIReachable, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a> and <a href="#a1a063e0f7f97a2cf494f8fff2e566bde">stripLoopMDLoc</a>.</p>


<p>Referenced by <a href="#a417bd37b1f7e5061fd57036f3160b288">stripDebugLocFromLoopID</a> and <a href="#a1a063e0f7f97a2cf494f8fff2e566bde">stripLoopMDLoc</a>.</p>

</div>
</div>

### unwrapDI() {#afa38484f37bc017c52d69457d3e6d2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIT * unwrapDI (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab3c5243ec4c41efdde6efd665f31c2a9">LLVMDIBuilderCreateArrayType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga208f89cfe45c5cfe3fa2c77c9227964f">LLVMDIBuilderCreateArtificialType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b2ece29856cc374fa69d6945066f332">LLVMDIBuilderCreateBitFieldMemberType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabdc3694c6c196a2d7181860b40fb9ac3">LLVMDIBuilderCreateClassType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac80c97dafb7ed1815c40df3e29ac574d">LLVMDIBuilderCreateCompileUnit</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0f63a87fe95c032988248173c40836e4">LLVMDIBuilderCreateEnumerationType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga93103e684ef975e27c124279b530f4a4">LLVMDIBuilderCreateForwardDecl</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga16e177b130697369b80b40e2a6e4b4bd">LLVMDIBuilderCreateFunction</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga83af94c8ebc30248947274cd3c6b2b18">LLVMDIBuilderCreateGlobalVariableExpression</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaecac3bea8780aabc755043bf56ccde16">LLVMDIBuilderCreateImportedDeclaration</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga79b2014998173c73f1643a12d125f57d">LLVMDIBuilderCreateImportedModuleFromAlias</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0fb25118742415266bc77ba402c0be3e">LLVMDIBuilderCreateImportedModuleFromModule</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4bd7b93a5adab9a1c2e0115d6fd27aaa">LLVMDIBuilderCreateImportedModuleFromNamespace</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac57bc2d6025d4be99b2e1b11c91a8904">LLVMDIBuilderCreateInheritance</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga71d2155ac54703ed0f1e3e230ef36065">LLVMDIBuilderCreateLabel</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad66fcc89d7abf993d470cc20459ac6c3">LLVMDIBuilderCreateLexicalBlock</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233939d145977e24bad18c7a27718fba">LLVMDIBuilderCreateLexicalBlockFile</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9ea606817ce85b9915297eb2de2a653d">LLVMDIBuilderCreateMacro</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5abafa3c43023b3169fae1f22c678049">LLVMDIBuilderCreateMemberPointerType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabe5507b0346c326bcbd875dec7dfca91">LLVMDIBuilderCreateMemberType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a47cdee54f0b80f9ba952d766582f97">LLVMDIBuilderCreateModule</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga28cb215b1180c262f2a29d811fef274f">LLVMDIBuilderCreateNameSpace</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga00f6a1630b3771db5c911f99a4f8dca6">LLVMDIBuilderCreateObjCIVar</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9cbf85a105f1c34719076b29b0830a83">LLVMDIBuilderCreateObjCProperty</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga20ed80a8dd7b49ba6fcdd9d3d2ac20e5">LLVMDIBuilderCreateObjectPointerType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafa96c20ff0708be1cabd2c06c9ce03ca">LLVMDIBuilderCreatePointerType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga8780f2c20339b37b01f8878401f27d00">LLVMDIBuilderCreateQualifiedType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a2899f83e586e884e2c75811d911742">LLVMDIBuilderCreateReferenceType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadcfce4b4d1ca9e120e479b56f24378d2">LLVMDIBuilderCreateReplaceableCompositeType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7c8d150bba12a1d9874e3d692fd804f6">LLVMDIBuilderCreateStaticMemberType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf293a26d4fd886befce34f6ce2a3bdf1">LLVMDIBuilderCreateStructType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga862c55fb3e10df7538c7883a948df025">LLVMDIBuilderCreateTempGlobalVariableFwdDecl</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4f1086f983fe945bf4377c392ed87f4a">LLVMDIBuilderCreateTempMacroFile</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf237e3bbfe69ee176ae2bf8db9079346">LLVMDIBuilderCreateTypedef</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga90500ff94794b86be3dd73f6d6f3a8a5">LLVMDIBuilderCreateUnionType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5a3fc221b7877d1efe4e10fe6d586a37">LLVMDIBuilderCreateVectorType</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabc75effdb1e1cc44b4393c7716e7f5d2">LLVMDIBuilderFinalizeSubprogram</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab176ba6b04ac20f7363e3f2315dd7545">LLVMDIBuilderInsertLabelAtEnd</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gace19cbd43c471a934793ba8f66ec16ce">LLVMDIBuilderInsertLabelBefore</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6d217da95423a5058437b10d48eb299c">LLVMDIFileGetDirectory</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7080e9914e8708451283d10b69cc8edc">LLVMDIFileGetFilename</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae0a790e33f02c87d24b428da4d2b34ce">LLVMDIFileGetSource</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2d889441ac9541119cc05b65b178bcfe">LLVMDIGlobalVariableExpressionGetExpression</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b9b6964e6643fc8cd61ea5b7a447ac3">LLVMDIGlobalVariableExpressionGetVariable</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5d3f8954443857acd2f3e63e924af5bb">LLVMDILocationGetColumn</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga02154723977a1df274e6dd6cab1b3c12">LLVMDILocationGetInlinedAt</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac367fff632214b9cb6a7c72a560c6375">LLVMDILocationGetLine</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4b79e6d86d287cbd5a2bad9d890d0cf6">LLVMDILocationGetScope</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabb1ada7b7f03079b1a3fc26d45a872c8">LLVMDIScopeGetFile</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga488dddd6a44fa6154d5520c2a76cab41">LLVMDisposeTemporaryMDNode</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233c8c86bdfa0ceaad5ddbbb5d50fa1d">LLVMDISubprogramGetLine</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2c1ae3a9365c49a64025df8a64086c2c">LLVMDITypeGetAlignInBits</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6bcea905cd35ad99a0d535721d8fe4ff">LLVMDITypeGetFlags</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga780f4dfcebe39a69b115ae4f0d2b300f">LLVMDITypeGetLine</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaef39844bc3df500ee733588158eae292">LLVMDITypeGetName</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae9747065099a9912fec575bd7edb7857">LLVMDITypeGetOffsetInBits</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga12af60f959285ba5ff8d568d27dda9a9">LLVMDITypeGetSizeInBits</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7929e8886d3a6c8c121f17dcb2af1dd6">LLVMDIVariableGetFile</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad19c6732705efa0c40e2bc0010632303">LLVMDIVariableGetLine</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2ed3e2ec3f48e55ed167177139d5b14b">LLVMDIVariableGetScope</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga829c0e0a5fec733d28b736c072bec4eb">LLVMGetDINodeTag</a> and <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga704c67d1afa02bfe39cd02b4830c8f3f">LLVMMetadataReplaceAllUsesWith</a>.</p>

</div>
</div>

### updateLoopMetadataDebugLocationsImpl() {#a35a60230fc7fed1d9eca1f2a89098364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * updateLoopMetadataDebugLocationsImpl (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * OrigLoopID, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *(<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *)&gt; Updater)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mdoperand/#ac5d52549f5e52702a331fbc4bd7eb512">llvm::MDOperand::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>


<p>Referenced by <a href="#a417bd37b1f7e5061fd57036f3160b288">stripDebugLocFromLoopID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aecd4ed57fa6a20d048310d43f5c96da9">llvm::updateLoopMetadataDebugLocations</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AssignmentTrackingModuleFlag {#a6fbb2cd3e7ca729057610b989666df42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* AssignmentTrackingModuleFlag</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "debug-<a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>-assignment-tracking"
</div>
</dd>
</dl>

<p>Definition at line 2294 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac9239698ab535528bfcba30502b5c1d1">getAssignmentTrackingModuleFlag</a> and <a href="#a07dca79c487ad44ed9f03cfde69c7747">setAssignmentTrackingModuleFlag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"assignment-tracking"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2120 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_LANG {#aa70cb3c0d314e41944b65f1bfdaa6457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LANG(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4436852644d626940ee2edc2ffb65880">LLVMDWARFSourceLanguage</a>##NAME:                                          \
    return ID;
</div>
</dd>
</dl>

<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

### HANDLE\_METADATA\_LEAF {#a59a8031b78f28120baafcfc27852d8bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_METADATA_LEAF(CLASS)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Metadata::CLASS##Kind: \
    return (<a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf09a2cd6396ded40b1260ca98a72e434">LLVMMetadataKind</a>)LLVM##CLASS##MetadataKind;
</div>
</dd>
</dl>

<p>Definition at line 1855 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
