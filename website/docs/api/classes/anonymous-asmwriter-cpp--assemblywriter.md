---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-asmwriter-cpp-/assemblywriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AssemblyWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AsmWriter.cpp}::AssemblyWriter { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3de6826079ac5f3ca5f7ef28dd3d9fb">AssemblyWriter</a> (formatted_raw_ostream &amp;o, SlotTracker &amp;Mac, const Module *M, AssemblyAnnotationWriter *AAW, bool IsForDebug, bool ShouldPreserveUseListOrder=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter">AssemblyWriter</a> with an external <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a>. <a href="#ab3de6826079ac5f3ca5f7ef28dd3d9fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38bba199ff23a3f2720107463054f9c2">AssemblyWriter</a> (formatted_raw_ostream &amp;o, SlotTracker &amp;Mac, const ModuleSummaryIndex *Index, bool IsForDebug)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/asmwritercontext">AsmWriterContext</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c668efa4b03efd334831e35da09378">getContext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac99997dcb417b8486233aed7f162cb0e">printMDNodeBody</a> (const MDNode *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac514ffc60e99e3e3d07b1b11973e2547">printNamedMDNode</a> (const NamedMDNode *NMD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43739573951954b013ba47125af51af2">printModule</a> (const Module *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a7c36cb1f1a299406e3cfa95b7404e">writeOperand</a> (const Value *Op, bool PrintType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc27aa83649282c846c35b22413ebf83">writeParamOperand</a> (const Value *Operand, AttributeSet Attrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a404d6605bd1587cb6b67b8b1f575022e">writeOperandBundles</a> (const CallBase *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753ecf6e16982f73f95dbfa7149b1c9e">writeSyncScope</a> (const LLVMContext &amp;Context, SyncScope::ID SSID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d634efc6c53e0f564e01aef25aaa0a">writeAtomic</a> (const LLVMContext &amp;Context, AtomicOrdering Ordering, SyncScope::ID SSID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53364013a2915f73f0c81f0a7974aba9">writeAtomicCmpXchg</a> (const LLVMContext &amp;Context, AtomicOrdering SuccessOrdering, AtomicOrdering FailureOrdering, SyncScope::ID SSID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a536ea5f0471772d2cbeb45138b34bb46">writeAllMDNodes</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21520233869b871c5cb13f8658a8bed0">writeMDNode</a> (unsigned Slot, const MDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2835a14441938516c2ae9e545d330a">writeAttribute</a> (const Attribute &amp;Attr, bool InAttrGroup=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab85047a4b52debd8bb9dc6556bf5113">writeAttributeSet</a> (const AttributeSet &amp;AttrSet, bool InAttrGroup=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a989cea32f0cf3729efcbf95b0f83a395">writeAllAttributeGroups</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a399312b003f10b95ad890372a70e0bf8">printTypeIdentities</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5529011752e50f62b1108a018df5e751">printGlobal</a> (const GlobalVariable *GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9005670841925a061ef19fe62955bce">printAlias</a> (const GlobalAlias *GA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89d2a6c720f05584135f01f20cc3c9ee">printIFunc</a> (const GlobalIFunc *GI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b1b0fe2304c977973331a277cfbd46">printComdat</a> (const Comdat *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace495e41b614e9f54d0ae8c8ea318fcd">printFunction</a> (const Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printFunction - Print all aspects of a function. <a href="#ace495e41b614e9f54d0ae8c8ea318fcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad57efe4558f8566bb06e708cd818578d">printArgument</a> (const Argument *FA, AttributeSet Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printArgument - This member is called for every argument that is passed into the function. <a href="#ad57efe4558f8566bb06e708cd818578d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f875a89b00cf04b3d413c954e9fe915">printBasicBlock</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printBasicBlock - This member is called for each basic block in a method. <a href="#a6f875a89b00cf04b3d413c954e9fe915">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932779da6f4872e86e4a98eb4ad22677">printInstructionLine</a> (const Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printInstructionLine - Print an instruction and a newline character. <a href="#a932779da6f4872e86e4a98eb4ad22677">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27130c5f74c2f20dd183f5ab83f54e6c">printInstruction</a> (const Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ec90e40a57f00c972a2e26352bf658">printDbgMarker</a> (const DbgMarker &amp;DPI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c33f7bfe854f12e21290f2a03a10a18">printDbgVariableRecord</a> (const DbgVariableRecord &amp;DVR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0550e356effa7d9246d22a6cf35a852b">printDbgLabelRecord</a> (const DbgLabelRecord &amp;DLR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d1f11be10f3c1d2b1776d84b0fbf5f">printDbgRecord</a> (const DbgRecord &amp;DR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a68db6125988ae5a8ff8e3bdfffcb32">printDbgRecordLine</a> (const DbgRecord &amp;DR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printDbgRecordLine - Print a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> with indentation and a newline character. <a href="#a4a68db6125988ae5a8ff8e3bdfffcb32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acccf84e16de1e75d80dde03014d98473">printUseListOrder</a> (const Value *V, const std::vector&lt; unsigned &gt; &amp;Shuffle)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c9b9c61a57546141a09c717cc9203dd">printUseLists</a> (const Function *F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51eeec9ea4e0b01342c3c5ded09d9d44">printModuleSummaryIndex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6daecba2f410ca680f7c789de806dc9d">printSummaryInfo</a> (unsigned Slot, const ValueInfo &amp;VI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d0df1adc907ec1c35df6ab26770f5b">printSummary</a> (const GlobalValueSummary &amp;Summary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab129b1dd5cbd57c3b50c3676e2ea67d0">printAliasSummary</a> (const AliasSummary *AS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8481c88ad7b96975060bd5df75554b3e">printGlobalVarSummary</a> (const GlobalVarSummary *GS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c2888afae81bca2dcd4347db1e014e">printFunctionSummary</a> (const FunctionSummary *FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ccea8ba8bd9770a7999071a79f9a1c2">printTypeIdSummary</a> (const TypeIdSummary &amp;TIS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e8059a18f443b6bb46cf3ca15b0acb">printTypeIdCompatibleVtableSummary</a> (const TypeIdCompatibleVtableInfo &amp;TI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0673433b10a762c449d89d6255ee9f4b">printTypeTestResolution</a> (const TypeTestResolution &amp;TTRes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1270952dd74af412e65c54315e51fd60">printArgs</a> (const std::vector&lt; uint64_t &gt; &amp;Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83d9a3fded69b1a33d8f581f75efe4f3">printWPDRes</a> (const WholeProgramDevirtResolution &amp;WPDRes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae452e35369a6552e0059f13304193c49">printTypeIdInfo</a> (const FunctionSummary::TypeIdInfo &amp;TIDInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3b4023531c17b577909a4bfecc6cd9">printVFuncId</a> (const FunctionSummary::VFuncId VFId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7ca2941d1e6bf79c4c703be8fddede">printNonConstVCalls</a> (const std::vector&lt; FunctionSummary::VFuncId &gt; &amp;VCallList, const char *Tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066ddf77ed428bcf1f7a98b4c08cfc88">printConstVCalls</a> (const std::vector&lt; FunctionSummary::ConstVCall &gt; &amp;VCallList, const char *Tag)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae63579096c29c3db1be63a3dbbf32309">printMetadataAttachments</a> (const SmallVectorImpl&lt; std::pair&lt; unsigned, MDNode * &gt; &gt; &amp;MDs, StringRef Separator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print out metadata attachments. <a href="#ae63579096c29c3db1be63a3dbbf32309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8caf78fafae4d68fc7c716a1b7d33ede">printInfoComment</a> (const Value &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printInfoComment - Print a little comment after the instruction indicating which slot it occupies. <a href="#a8caf78fafae4d68fc7c716a1b7d33ede">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8885f1c7fc7719f28bffe5c6c596cc67">printGCRelocateComment</a> (const GCRelocateInst &amp;Relocate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printGCRelocateComment - print comment after call to the gc.relocate intrinsic indicating base and derived pointer names. <a href="#a8885f1c7fc7719f28bffe5c6c596cc67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5502abf1b4e8247c9c00b9431b479e25">Out</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9730aab6b5a2298136edefa82982b5ed">TheModule</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4b5d6513e09376795f23a01beb9a68">TheIndex</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3756ea3cb34f27897450ff34a769b856">SlotTrackerStorage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a71e6fa47b4fc15a5c698a67745c2fa">Machine</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting">TypePrinting</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a034e5b40e5795972ca6e44105e1e5">TypePrinter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabecea4d188a004896b615ee8cd58ac3">AnnotationWriter</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca98b14b0bdd41c877ba8ca972c6eef">Comdats</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce5e40960ef2dce52188c0e277af7fa">IsForDebug</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad720b16486272ca93f5c08ca02266b60">ShouldPreserveUseListOrder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a9dba8485af0d57fec37ee7bd17cafcc5">UseListOrderMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2c464d319bea37115b71f21b8f1e34a">UseListOrders</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d3fbbab1a05cde02918b8d7074b3fec">MDNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ea6ade4e681eb4d37cb8cde28a99b9">SSNs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Synchronization scope names registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#a02ea6ade4e681eb4d37cb8cde28a99b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631b923ac4917dcc2b1cbaa7e87a006b">SummaryToGUIDMap</a></td>
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


<p>Definition at line 2730 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AssemblyWriter() {#ab3de6826079ac5f3ca5f7ef28dd3d9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssemblyWriter::AssemblyWriter (<a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; o, <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> &amp; Mac, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a> * AAW, bool IsForDebug, bool ShouldPreserveUseListOrder=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter">AssemblyWriter</a> with an external <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a>.</p>

<p>Definition at line 2749 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a98140bed34afff96a44ab31ef977f5ec">llvm::GlobalObject::getComdat</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>.</p>

</div>
</div>

### AssemblyWriter() {#a38bba199ff23a3f2720107463054f9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssemblyWriter::AssemblyWriter (<a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; o, <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> &amp; Mac, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * Index, bool IsForDebug)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2753 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getContext() {#ac0c668efa4b03efd334831e35da09378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmWriterContext anonymous{AsmWriter.cpp}::AssemblyWriter::getContext ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2756 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Referenced by <a href="#a0550e356effa7d9246d22a6cf35a852b">printDbgLabelRecord</a>, <a href="#a7c33f7bfe854f12e21290f2a03a10a18">printDbgVariableRecord</a>, <a href="#ac99997dcb417b8486233aed7f162cb0e">printMDNodeBody</a>, <a href="#ac7a7c36cb1f1a299406e3cfa95b7404e">writeOperand</a>, <a href="#a404d6605bd1587cb6b67b8b1f575022e">writeOperandBundles</a> and <a href="#adc27aa83649282c846c35b22413ebf83">writeParamOperand</a>.</p>

</div>
</div>

### printAlias() {#ae9005670841925a061ef19fe62955bce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printAlias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * GA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2786 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a7666cc7bd9294c7ae9992c41c591e08b">llvm::GlobalAlias::getAliasee</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af09a662b4e302d0683d0fe9dc2a9335f">llvm::GlobalValue::getDLLStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a34ed5c00494852d2cc92e00f1e692490">getLinkageNameWithSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a72237a63b5edcf78a32453822139f1d5">llvm::GlobalValue::getPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a52126ae2091b18cecfd5ad0f0012839a">llvm::GlobalValue::getThreadLocalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac2417a3c6edd0db7a9ad84b82c4054b7">llvm::GlobalValue::getUnnamedAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a4ab494dbedb6de02c4dc9f5b12f95100">getUnnamedAddrEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a28b9561d9ef3d237ef894023187fa26c">llvm::GlobalValue::getVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a0bf930687efa9a6cdc47d318dbd2e6d4">llvm::GlobalValue::hasPartition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac010bf63f00b00f321a141448942a697">llvm::GlobalValue::isMaterializable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a81a19bb50ce0a6457bf0366b196c9a96">PrintDLLStorageClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae205407d61d26187ae589c4a4f78320e">PrintDSOLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3c542b04650c506ccb8c7adb8984b137">PrintThreadLocalModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac92ccaae13428fbf8fcb741c69863c70">PrintVisibility</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> and <a href="#ac7a7c36cb1f1a299406e3cfa95b7404e">writeOperand</a>.</p>


<p>Referenced by <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### printAliasSummary() {#ab129b1dd5cbd57c3b50c3676e2ea67d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printAliasSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aliassummary">AliasSummary</a> * AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2806 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aliassummary/#a3cf8470cbd684199dd060dc117e84a5d">llvm::AliasSummary::getAliasee</a> and <a href="/web-llvm/docs/api/classes/llvm/aliassummary/#aa5a7f7d6f4739990d4f9a5e388a0be22">llvm::AliasSummary::hasAliasee</a>.</p>


<p>Referenced by <a href="#a75d0df1adc907ec1c35df6ab26770f5b">printSummary</a>.</p>

</div>
</div>

### printArgs() {#a1270952dd74af412e65c54315e51fd60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printArgs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; uint64_t &gt; &amp; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2812 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Referenced by <a href="#a066ddf77ed428bcf1f7a98b4c08cfc88">printConstVCalls</a> and <a href="#a83d9a3fded69b1a33d8f581f75efe4f3">printWPDRes</a>.</p>

</div>
</div>

### printArgument() {#ad57efe4558f8566bb06e708cd818578d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printArgument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * Arg, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>printArgument - This member is called for every argument that is passed into the function.</p>


<p>Simply print it out</p>


<p>Definition at line 2790 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3d6e60a917bf5f4052dbb2673f11e087">PrintLLVMName</a> and <a href="#aab85047a4b52debd8bb9dc6556bf5113">writeAttributeSet</a>.</p>


<p>Referenced by <a href="#ace495e41b614e9f54d0ae8c8ea318fcd">printFunction</a>.</p>

</div>
</div>

### printBasicBlock() {#a6f875a89b00cf04b3d413c954e9fe915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>printBasicBlock - This member is called for each basic block in a method.</p>

<p>Definition at line 2791 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4ec05121d4b54b3691ad6203e78ff54e">llvm::BasicBlock::isEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aec73ab739d6b324c9753c7071afd6c2fa1c1c0a2fa257d4c584150dbc04ec2509">LabelPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3e549d97549636a7f08779d5cd98540">llvm::pred_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2103c335fa6ab933312c3871c82b0106">llvm::pred_end</a>, <a href="#a4a68db6125988ae5a8ff8e3bdfffcb32">printDbgRecordLine</a>, <a href="#a932779da6f4872e86e4a98eb4ad22677">printInstructionLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3d6e60a917bf5f4052dbb2673f11e087">PrintLLVMName</a> and <a href="#ac7a7c36cb1f1a299406e3cfa95b7404e">writeOperand</a>.</p>


<p>Referenced by <a href="#ace495e41b614e9f54d0ae8c8ea318fcd">printFunction</a>.</p>

</div>
</div>

### printComdat() {#a93b1b0fe2304c977973331a277cfbd46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printComdat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2788 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### printConstVCalls() {#a066ddf77ed428bcf1f7a98b4c08cfc88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printConstVCalls (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a> &gt; &amp; VCallList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2820 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a1270952dd74af412e65c54315e51fd60">printArgs</a> and <a href="#a9e3b4023531c17b577909a4bfecc6cd9">printVFuncId</a>.</p>


<p>Referenced by <a href="#ae452e35369a6552e0059f13304193c49">printTypeIdInfo</a>.</p>

</div>
</div>

### printDbgLabelRecord() {#a0550e356effa7d9246d22a6cf35a852b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printDbgLabelRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord">DbgLabelRecord</a> &amp; DLR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2796 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#ac0c668efa4b03efd334831e35da09378">getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>


<p>Referenced by <a href="#af0d1f11be10f3c1d2b1776d84b0fbf5f">printDbgRecord</a>.</p>

</div>
</div>

### printDbgMarker() {#a16ec90e40a57f00c972a2e26352bf658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printDbgMarker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> &amp; DPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2794 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a36e5e8e39d6d654db719920186533fac">llvm::DbgMarker::MarkedInstr</a>, <a href="#af0d1f11be10f3c1d2b1776d84b0fbf5f">printDbgRecord</a>, <a href="#a27130c5f74c2f20dd183f5ab83f54e6c">printInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#acf93a5910e8b1adcdca71705495e5d92">llvm::DbgMarker::StoredDbgRecords</a>.</p>

</div>
</div>

### printDbgRecord() {#af0d1f11be10f3c1d2b1776d84b0fbf5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printDbgRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &amp; DR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2797 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a0550e356effa7d9246d22a6cf35a852b">printDbgLabelRecord</a> and <a href="#a7c33f7bfe854f12e21290f2a03a10a18">printDbgVariableRecord</a>.</p>


<p>Referenced by <a href="#a16ec90e40a57f00c972a2e26352bf658">printDbgMarker</a> and <a href="#a4a68db6125988ae5a8ff8e3bdfffcb32">printDbgRecordLine</a>.</p>

</div>
</div>

### printDbgRecordLine() {#a4a68db6125988ae5a8ff8e3bdfffcb32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printDbgRecordLine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &amp; DR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>printDbgRecordLine - Print a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> with indentation and a newline character.</p>

<p>Definition at line 2798 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="#af0d1f11be10f3c1d2b1776d84b0fbf5f">printDbgRecord</a>.</p>


<p>Referenced by <a href="#a6f875a89b00cf04b3d413c954e9fe915">printBasicBlock</a>.</p>

</div>
</div>

### printDbgVariableRecord() {#a7c33f7bfe854f12e21290f2a03a10a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printDbgVariableRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp; DVR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2795 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca185b7133db22230701a857c059360cc2">llvm::DbgVariableRecord::Assign</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">llvm::DbgVariableRecord::Declare</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a942ba74e5c32ec1b9471e80c2c826b5d">llvm::DebugLoc::getAsMDNode</a>, <a href="#ac0c668efa4b03efd334831e35da09378">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3a0f4e00c3f6345c52c6acd178b3fca3">llvm::DbgRecord::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad76c901f38759f560144bafef2c598be">llvm::DbgVariableRecord::getRawAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a56ed176f3945639483c3ff12214f3ce3">llvm::DbgVariableRecord::getRawAddressExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a92bf6b19c53c3ebfa6045aaeacf6e24b">llvm::DbgVariableRecord::getRawAssignID</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a3e0fc51827c21c4dd8f590d7cc4000db">llvm::DbgVariableRecord::getRawExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ab9edb568c54e87f08484a5f46e399bee">llvm::DbgVariableRecord::getRawLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a9f421ee6c8aa855c30816913e794a4c7">llvm::DbgVariableRecord::getRawVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a1adb590f8f0ceed777898888ed5db7ac">llvm::DbgVariableRecord::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a8e44c4d5de5d1134497e3ca3b922c535">llvm::DbgVariableRecord::isDbgAssign</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca689202409e48743b914713f96d93947c">llvm::DbgVariableRecord::Value</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>


<p>Referenced by <a href="#af0d1f11be10f3c1d2b1776d84b0fbf5f">printDbgRecord</a>.</p>

</div>
</div>

### printFunction() {#ace495e41b614e9f54d0ae8c8ea318fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>printFunction - Print all aspects of a function.</p>

<p>Definition at line 2789 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a34ed5c00494852d2cc92e00f1e692490">getLinkageNameWithSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a4ab494dbedb6de02c4dc9f5b12f95100">getUnnamedAddrEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a03e88ecc68b413d829593f385d84dca6">llvm::AttributeSet::hasAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aed6d706def80ab7bcb8b35112a9f94be">maybePrintComdat</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="#ad57efe4558f8566bb06e708cd818578d">printArgument</a>, <a href="#a6f875a89b00cf04b3d413c954e9fe915">printBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a13e35bdf0ecd9533b463d3c902d3659c">PrintCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a81a19bb50ce0a6457bf0366b196c9a96">PrintDLLStorageClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae205407d61d26187ae589c4a4f78320e">PrintDSOLocation</a>, <a href="#a7c9b9c61a57546141a09c717cc9203dd">printUseLists</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac92ccaae13428fbf8fcb741c69863c70">PrintVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">llvm::AttributeList::ReturnIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>, <a href="#aab85047a4b52debd8bb9dc6556bf5113">writeAttributeSet</a> and <a href="#ac7a7c36cb1f1a299406e3cfa95b7404e">writeOperand</a>.</p>


<p>Referenced by <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### printFunctionSummary() {#a37c2888afae81bca2dcd4347db1e014e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printFunctionSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2808 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a1a3c2e99e572ec71d3820d0363d90742">llvm::Cold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21f2a6af0e8fcffa3bf64eaf6b345861">llvm::getHotnessName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a4194726ee334e1085d93e002837b73f0">llvm::Hot</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27ad814aa38fbac7f6d03b30741366aae56">llvm::NotCold</a>, <a href="#ae452e35369a6552e0059f13304193c49">printTypeIdInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::CalleeInfo::Unknown</a>.</p>


<p>Referenced by <a href="#a75d0df1adc907ec1c35df6ab26770f5b">printSummary</a>.</p>

</div>
</div>

### printGlobal() {#a5529011752e50f62b1108a018df5e751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2785 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a115ac0121663aa8365e095d095d0c633">llvm::GlobalObject::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a3d200b1568f70b28ae0eb9bec58d6690">llvm::GlobalObject::getAllMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a2e5805d3565801dc32ec696d17624c6e">llvm::GlobalVariable::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a339c8e24dbf600ae50b1aac2be2c1dbf">llvm::GlobalVariable::getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af09a662b4e302d0683d0fe9dc2a9335f">llvm::GlobalValue::getDLLStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0698d5bcabbfbca4f56a9d7a81cecb25">llvm::GlobalVariable::getInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a34ed5c00494852d2cc92e00f1e692490">getLinkageNameWithSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a72237a63b5edcf78a32453822139f1d5">llvm::GlobalValue::getPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a10dbf1e2be9c60af49efb9bfded99225">llvm::GlobalValue::getSanitizerMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a0b2e3fb45c4435c29abebf7768a77cd6">llvm::GlobalObject::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a52126ae2091b18cecfd5ad0f0012839a">llvm::GlobalValue::getThreadLocalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac2417a3c6edd0db7a9ad84b82c4054b7">llvm::GlobalValue::getUnnamedAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a4ab494dbedb6de02c4dc9f5b12f95100">getUnnamedAddrEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a28b9561d9ef3d237ef894023187fa26c">llvm::GlobalValue::getVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a1847e956a0087fefdb49e2a9583c7d18">llvm::GlobalValue::hasExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a1c66d4eff947253e7610a66379974d63">llvm::GlobalVariable::hasInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a0bf930687efa9a6cdc47d318dbd2e6d4">llvm::GlobalValue::hasPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6d863ff0d778248ac9b693db3494565c">llvm::GlobalValue::hasSanitizerMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ade7dc7510e950cd1c1181138b390f965">llvm::GlobalObject::hasSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#aa859e108741fa64681b63f0c0c672512">llvm::GlobalVariable::isConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#ac1da5875b7fe84a87d30ef1a90524c1c">llvm::GlobalValue::SanitizerMetadata::IsDynInit</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0f6dab3350ff78735031a6a62f344f18">llvm::GlobalVariable::isExternallyInitialized</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac010bf63f00b00f321a141448942a697">llvm::GlobalValue::isMaterializable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa6a2e45ae404e3f797d2d7e9f3a48949">llvm::CodeModel::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aed6d706def80ab7bcb8b35112a9f94be">maybePrintComdat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#a06dd653fcfff7260ea2ab89cc39029cb">llvm::GlobalValue::SanitizerMetadata::Memtag</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#af14cbae5c1ca7ff03eaa9c66d41e0940">llvm::GlobalValue::SanitizerMetadata::NoAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata/#a3c6f90fc4359e4c8cc2ad7333254f3c7">llvm::GlobalValue::SanitizerMetadata::NoHWAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a81a19bb50ce0a6457bf0366b196c9a96">PrintDLLStorageClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae205407d61d26187ae589c4a4f78320e">PrintDSOLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3c542b04650c506ccb8c7adb8984b137">PrintThreadLocalModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac92ccaae13428fbf8fcb741c69863c70">PrintVisibility</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa686bcdfaefdfe3f49acbfe6f680bc22d">llvm::CodeModel::Tiny</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> and <a href="#ac7a7c36cb1f1a299406e3cfa95b7404e">writeOperand</a>.</p>


<p>Referenced by <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### printGlobalVarSummary() {#a8481c88ad7b96975060bd5df75554b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printGlobalVarSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvarsummary">GlobalVarSummary</a> * GS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2807 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a75d0df1adc907ec1c35df6ab26770f5b">printSummary</a>.</p>

</div>
</div>

### printIFunc() {#a89d2a6c720f05584135f01f20cc3c9ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printIFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> * GI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2787 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a34ed5c00494852d2cc92e00f1e692490">getLinkageNameWithSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a72237a63b5edcf78a32453822139f1d5">llvm::GlobalValue::getPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#afaea927bc35e1609245901d8cb61366f">llvm::GlobalIFunc::getResolver</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a28b9561d9ef3d237ef894023187fa26c">llvm::GlobalValue::getVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a0bf930687efa9a6cdc47d318dbd2e6d4">llvm::GlobalValue::hasPartition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac010bf63f00b00f321a141448942a697">llvm::GlobalValue::isMaterializable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae205407d61d26187ae589c4a4f78320e">PrintDSOLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac92ccaae13428fbf8fcb741c69863c70">PrintVisibility</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> and <a href="#ac7a7c36cb1f1a299406e3cfa95b7404e">writeOperand</a>.</p>


<p>Referenced by <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### printInstruction() {#a27130c5f74c2f20dd183f5ab83f54e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2793 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a917739f8f62442b8fea20bbe72cab891">llvm::AttributeList::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ac8d6f220fcf8f327c6c739813df8c4c9">llvm::AttributeList::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a1cf553641e8527095ae4c8ec88a2cd92">llvm::AttributeList::getFnAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#ae8a61b9349a5ea2fb1b3d856bd4e9ab2">llvm::AtomicRMWInst::getOperationName</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ada7a173c40ca7ac048a4b7099ceb71c0">llvm::AttributeList::getParamAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ad78e7e25df5981be38867dd67df81f92">llvm::AttributeList::hasFnAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ac58b17d02803ec68e3dbfc82a8f45d5e">llvm::AttributeList::hasRetAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac46926a2483bd793432d5ca0f7879de3">maybePrintCallAddrSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a13e35bdf0ecd9533b463d3c902d3659c">PrintCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3d6e60a917bf5f4052dbb2673f11e087">PrintLLVMName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a515ea398a2f882f4d1ea69c71ea8d39c">PrintShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">llvm::AttributeList::ReturnIndex</a>, <a href="#aa6d634efc6c53e0f564e01aef25aaa0a">writeAtomic</a>, <a href="#a53364013a2915f73f0c81f0a7974aba9">writeAtomicCmpXchg</a>, <a href="#ac7a7c36cb1f1a299406e3cfa95b7404e">writeOperand</a>, <a href="#a404d6605bd1587cb6b67b8b1f575022e">writeOperandBundles</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a2ced856c3217b5902cfc6e22ade76eaa">WriteOptimizationInfo</a> and <a href="#adc27aa83649282c846c35b22413ebf83">writeParamOperand</a>.</p>


<p>Referenced by <a href="#a16ec90e40a57f00c972a2e26352bf658">printDbgMarker</a> and <a href="#a932779da6f4872e86e4a98eb4ad22677">printInstructionLine</a>.</p>

</div>
</div>

### printInstructionLine() {#a932779da6f4872e86e4a98eb4ad22677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printInstructionLine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>printInstructionLine - Print an instruction and a newline character.</p>

<p>Definition at line 2792 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a27130c5f74c2f20dd183f5ab83f54e6c">printInstruction</a>.</p>


<p>Referenced by <a href="#a6f875a89b00cf04b3d413c954e9fe915">printBasicBlock</a>.</p>

</div>
</div>

### printMDNodeBody() {#ac99997dcb417b8486233aed7f162cb0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printMDNodeBody (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2760 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#ac0c668efa4b03efd334831e35da09378">getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a6dd54a7261fabfe58a4c7c66ff7846d0">WriteMDNodeBodyInternal</a>.</p>


<p>Referenced by <a href="#a21520233869b871c5cb13f8658a8bed0">writeMDNode</a>.</p>

</div>
</div>

### printModule() {#a43739573951954b013ba47125af51af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2763 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/valueenumerator-cpp/#a9e9ff0c61346a6511c2f5eef7704c99e">predictUseListOrder</a>, <a href="#ae9005670841925a061ef19fe62955bce">printAlias</a>, <a href="#a93b1b0fe2304c977973331a277cfbd46">printComdat</a>, <a href="#ace495e41b614e9f54d0ae8c8ea318fcd">printFunction</a>, <a href="#a5529011752e50f62b1108a018df5e751">printGlobal</a>, <a href="#a89d2a6c720f05584135f01f20cc3c9ee">printIFunc</a>, <a href="#ac514ffc60e99e3e3d07b1b11973e2547">printNamedMDNode</a>, <a href="#a399312b003f10b95ad890372a70e0bf8">printTypeIdentities</a>, <a href="#a7c9b9c61a57546141a09c717cc9203dd">printUseLists</a>, <a href="#a989cea32f0cf3729efcbf95b0f83a395">writeAllAttributeGroups</a> and <a href="#a536ea5f0471772d2cbeb45138b34bb46">writeAllMDNodes</a>.</p>

</div>
</div>

### printModuleSummaryIndex() {#a51eeec9ea4e0b01342c3c5ded09d9d44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printModuleSummaryIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2803 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a71ee7e63264e4997a3340a781d44832e">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a67b09ea4ea9bc853c7893d7c5e61cec5">llvm::ModuleSummaryIndex::getRegularLTOModuleName</a>, <a href="#a6daecba2f410ca680f7c789de806dc9d">printSummaryInfo</a>, <a href="#a16e8059a18f443b6bb46cf3ca15b0acb">printTypeIdCompatibleVtableSummary</a> and <a href="#a7ccea8ba8bd9770a7999071a79f9a1c2">printTypeIdSummary</a>.</p>

</div>
</div>

### printNamedMDNode() {#ac514ffc60e99e3e3d07b1b11973e2547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printNamedMDNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> * NMD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2761 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/asmwritercontext/#a94062353410e68b3b153cc88b829d36c">anonymous{AsmWriter.cpp}::AsmWriterContext::getEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#a5e90645e97cbfe08194f0db4d0bdec88">llvm::NamedMDNode::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#acde8007e0e69969423e2de52343b702f">llvm::NamedMDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#aa24b566603d206b0e74bf63daf521078">llvm::NamedMDNode::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a73529d591c6cc76d12ac7099bbd7e440">printMetadataIdentifier</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae17ea3efcdbb81ab64b4b54031176d88">writeDIExpression</a>.</p>


<p>Referenced by <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### printNonConstVCalls() {#a6c7ca2941d1e6bf79c4c703be8fddede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printNonConstVCalls (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a> &gt; &amp; VCallList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2817 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="#a9e3b4023531c17b577909a4bfecc6cd9">printVFuncId</a>.</p>


<p>Referenced by <a href="#ae452e35369a6552e0059f13304193c49">printTypeIdInfo</a>.</p>

</div>
</div>

### printSummary() {#a75d0df1adc907ec1c35df6ab26770f5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> &amp; Summary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2805 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a0c8dfea65f1f5dfba143b1fc9768614ca9472a9af94b2b12a3e8530336f32685d">llvm::GlobalValueSummary::AliasKind</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags/#a68afba1d01d2c8a930fae79199d8e280">llvm::GlobalValueSummary::GVFlags::CanAutoHide</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags/#a3bb8213497b192925ad7a95078631469">llvm::GlobalValueSummary::GVFlags::DSOLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a0c8dfea65f1f5dfba143b1fc9768614ca5034481e0a0691fa0f4b4321c33ecb5b">llvm::GlobalValueSummary::FunctionKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#abb125dbd101f28ac21fec3eb0611dfa4">getImportTypeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aacd93da4be9b01ed5c96cbfa881aeb71">getLinkageName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a84ad952468a5f8d7ffb8650ec9282cf8">getSummaryKindName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a8c65115110985b60bf4d0f71a5ecd550">getVisibilityName</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags/#a999b0f705022f5577410741705b51399">llvm::GlobalValueSummary::GVFlags::ImportType</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags/#ab3e4711ebf79a15a08499843071da146">llvm::GlobalValueSummary::GVFlags::Linkage</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags/#adf60e51668a91b9a24f41451806eb7e8">llvm::GlobalValueSummary::GVFlags::Live</a>, <a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags/#aa7df9cb43125220f4198f90440164ba2">llvm::GlobalValueSummary::GVFlags::NotEligibleToImport</a>, <a href="#ab129b1dd5cbd57c3b50c3676e2ea67d0">printAliasSummary</a>, <a href="#a37c2888afae81bca2dcd4347db1e014e">printFunctionSummary</a>, <a href="#a8481c88ad7b96975060bd5df75554b3e">printGlobalVarSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags/#ac7914ffd4eb71a53515d73ea6abc74a7">llvm::GlobalValueSummary::GVFlags::Visibility</a>.</p>


<p>Referenced by <a href="#a6daecba2f410ca680f7c789de806dc9d">printSummaryInfo</a>.</p>

</div>
</div>

### printSummaryInfo() {#a6daecba2f410ca680f7c789de806dc9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printSummaryInfo (unsigned Slot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &amp; VI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2804 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="#a75d0df1adc907ec1c35df6ab26770f5b">printSummary</a>.</p>


<p>Referenced by <a href="#a51eeec9ea4e0b01342c3c5ded09d9d44">printModuleSummaryIndex</a>.</p>

</div>
</div>

### printTypeIdCompatibleVtableSummary() {#a16e8059a18f443b6bb46cf3ca15b0acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printTypeIdCompatibleVtableSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ada2485ca228b028f8639ad86ce41d6ec">TypeIdCompatibleVtableInfo</a> &amp; TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2810 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a51eeec9ea4e0b01342c3c5ded09d9d44">printModuleSummaryIndex</a>.</p>

</div>
</div>

### printTypeIdentities() {#a399312b003f10b95ad890372a70e0bf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printTypeIdentities ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2784 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aec73ab739d6b324c9753c7071afd6c2fa5dd3523630566b2c032744029b66efbd">LocalPrefix</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3d6e60a917bf5f4052dbb2673f11e087">PrintLLVMName</a>.</p>


<p>Referenced by <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### printTypeIdInfo() {#ae452e35369a6552e0059f13304193c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printTypeIdInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/functionsummary/typeidinfo">FunctionSummary::TypeIdInfo</a> &amp; TIDInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2814 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a066ddf77ed428bcf1f7a98b4c08cfc88">printConstVCalls</a>, <a href="#a6c7ca2941d1e6bf79c4c703be8fddede">printNonConstVCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/functionsummary/typeidinfo/#a5fd68c70ca503931dfedb66add9ddaf1">llvm::FunctionSummary::TypeIdInfo::TypeCheckedLoadConstVCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/functionsummary/typeidinfo/#a9173f15dad28f7e5e05a4b133fc54021">llvm::FunctionSummary::TypeIdInfo::TypeCheckedLoadVCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/functionsummary/typeidinfo/#ab0f29b48b080b735fa7f1a579d2a8936">llvm::FunctionSummary::TypeIdInfo::TypeTestAssumeConstVCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/functionsummary/typeidinfo/#ab6b8eea40d56e793d1c5cd4d1b921147">llvm::FunctionSummary::TypeIdInfo::TypeTestAssumeVCalls</a> and <a href="/web-llvm/docs/api/structs/llvm/functionsummary/typeidinfo/#ab3aad34dbb3cc1fb6daa0a79dbcf5166">llvm::FunctionSummary::TypeIdInfo::TypeTests</a>.</p>


<p>Referenced by <a href="#a37c2888afae81bca2dcd4347db1e014e">printFunctionSummary</a>.</p>

</div>
</div>

### printTypeIdSummary() {#a7ccea8ba8bd9770a7999071a79f9a1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printTypeIdSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/typeidsummary">TypeIdSummary</a> &amp; TIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2809 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a0673433b10a762c449d89d6255ee9f4b">printTypeTestResolution</a>, <a href="#a83d9a3fded69b1a33d8f581f75efe4f3">printWPDRes</a>, <a href="/web-llvm/docs/api/structs/llvm/typeidsummary/#a80bc0b8f2041f3a3839f393f1a6aae33">llvm::TypeIdSummary::TTRes</a> and <a href="/web-llvm/docs/api/structs/llvm/typeidsummary/#a01d5759cee861fcfca3b26ff5927e83c">llvm::TypeIdSummary::WPDRes</a>.</p>


<p>Referenced by <a href="#a51eeec9ea4e0b01342c3c5ded09d9d44">printModuleSummaryIndex</a>.</p>

</div>
</div>

### printTypeTestResolution() {#a0673433b10a762c449d89d6255ee9f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printTypeTestResolution (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/typetestresolution">TypeTestResolution</a> &amp; TTRes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2811 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#ad43ecb12669b6fda67694c153847ebdd">llvm::TypeTestResolution::AlignLog2</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a742493488e02c32e595b0052a4c247d5">llvm::TypeTestResolution::BitMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ab84b1a4040d0e23018b9bfe7ccfbacc5">getTTResKindName</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#ad940f79d8b859f1b9bdbc4df5b9bda75">llvm::TypeTestResolution::InlineBits</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a4f7d657b28994fc8695b080cb20b1c97">llvm::TypeTestResolution::SizeM1</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a453599f2782c97d48d8bcedf6f75122d">llvm::TypeTestResolution::SizeM1BitWidth</a> and <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a66ff82a2443a6f422cd95843084564f6">llvm::TypeTestResolution::TheKind</a>.</p>


<p>Referenced by <a href="#a7ccea8ba8bd9770a7999071a79f9a1c2">printTypeIdSummary</a>.</p>

</div>
</div>

### printUseListOrder() {#acccf84e16de1e75d80dde03014d98473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printUseListOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; unsigned &gt; &amp; Shuffle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2800 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ac7a7c36cb1f1a299406e3cfa95b7404e">writeOperand</a>.</p>


<p>Referenced by <a href="#a7c9b9c61a57546141a09c717cc9203dd">printUseLists</a>.</p>

</div>
</div>

### printUseLists() {#a7c9b9c61a57546141a09c717cc9203dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printUseLists (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2801 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#acccf84e16de1e75d80dde03014d98473">printUseListOrder</a>.</p>


<p>Referenced by <a href="#ace495e41b614e9f54d0ae8c8ea318fcd">printFunction</a> and <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### printVFuncId() {#a9e3b4023531c17b577909a4bfecc6cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printVFuncId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a> VFId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2815 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid/#ab1eb65bd04804dbc2530022ac5f2ad3a">llvm::FunctionSummary::VFuncId::GUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid/#abdfc19655480c368bb77b87f4b272cde">llvm::FunctionSummary::VFuncId::Offset</a>.</p>


<p>Referenced by <a href="#a066ddf77ed428bcf1f7a98b4c08cfc88">printConstVCalls</a> and <a href="#a6c7ca2941d1e6bf79c4c703be8fddede">printNonConstVCalls</a>.</p>

</div>
</div>

### printWPDRes() {#a83d9a3fded69b1a33d8f581f75efe4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printWPDRes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> &amp; WPDRes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2813 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a4e8c5d9850cd1e4bcbade2cfc82e56c7">getWholeProgDevirtResByArgKindName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a227d0a32d5eaba74f96b14060c31ae26">getWholeProgDevirtResKindName</a>, <a href="#a1270952dd74af412e65c54315e51fd60">printArgs</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a1c0a0ec1654585583572f16e799176dc">llvm::WholeProgramDevirtResolution::ResByArg</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208a05ee7e7ff849410d68ccfd73e177387f">llvm::WholeProgramDevirtResolution::SingleImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ab97c12959c5cc7b46b115da7e1ac5047">llvm::WholeProgramDevirtResolution::SingleImplName</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a11bddbadb47e3bd7803ded5d4f4248fc">llvm::WholeProgramDevirtResolution::TheKind</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea635d252c06de8cd5c96ebcf3d8989ccf">llvm::WholeProgramDevirtResolution::ByArg::UniformRetVal</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea8bf72562c0a17a25f9e07863e68543b3">llvm::WholeProgramDevirtResolution::ByArg::UniqueRetVal</a>.</p>


<p>Referenced by <a href="#a7ccea8ba8bd9770a7999071a79f9a1c2">printTypeIdSummary</a>.</p>

</div>
</div>

### writeAllAttributeGroups() {#a989cea32f0cf3729efcbf95b0f83a395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeAllAttributeGroups ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2782 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### writeAllMDNodes() {#a536ea5f0471772d2cbeb45138b34bb46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeAllMDNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2778 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a21520233869b871c5cb13f8658a8bed0">writeMDNode</a>.</p>


<p>Referenced by <a href="#a43739573951954b013ba47125af51af2">printModule</a>.</p>

</div>
</div>

### writeAtomic() {#aa6d634efc6c53e0f564e01aef25aaa0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeAtomic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2770 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a473a7928f2af5c01022800db638773">llvm::toIRString</a> and <a href="#a753ecf6e16982f73f95dbfa7149b1c9e">writeSyncScope</a>.</p>


<p>Referenced by <a href="#a27130c5f74c2f20dd183f5ab83f54e6c">printInstruction</a>.</p>

</div>
</div>

### writeAtomicCmpXchg() {#a53364013a2915f73f0c81f0a7974aba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeAtomicCmpXchg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> SuccessOrdering, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> FailureOrdering, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2773 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a473a7928f2af5c01022800db638773">llvm::toIRString</a> and <a href="#a753ecf6e16982f73f95dbfa7149b1c9e">writeSyncScope</a>.</p>


<p>Referenced by <a href="#a27130c5f74c2f20dd183f5ab83f54e6c">printInstruction</a>.</p>

</div>
</div>

### writeAttribute() {#a2a2835a14441938516c2ae9e545d330a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeAttribute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &amp; Attr, bool InAttrGroup=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2780 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a6fea074fd9120ff82abd8f9e0036a12a">llvm::Attribute::getKindAsEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a9f1de7d65958c48ef95760927081625c">llvm::Attribute::getNameFromAttrKind</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aff1705f60feb6936d4e9cf126347c5e7">llvm::Attribute::getValueAsType</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#ab6fc71def3a243f7c93d39db21344240">llvm::Attribute::isTypeAttribute</a>.</p>


<p>Referenced by <a href="#aab85047a4b52debd8bb9dc6556bf5113">writeAttributeSet</a>.</p>

</div>
</div>

### writeAttributeSet() {#aab85047a4b52debd8bb9dc6556bf5113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeAttributeSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> &amp; AttrSet, bool InAttrGroup=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2781 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="#a2a2835a14441938516c2ae9e545d330a">writeAttribute</a>.</p>


<p>Referenced by <a href="#ad57efe4558f8566bb06e708cd818578d">printArgument</a>, <a href="#ace495e41b614e9f54d0ae8c8ea318fcd">printFunction</a> and <a href="#adc27aa83649282c846c35b22413ebf83">writeParamOperand</a>.</p>

</div>
</div>

### writeMDNode() {#a21520233869b871c5cb13f8658a8bed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeMDNode (unsigned Slot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2779 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="#ac99997dcb417b8486233aed7f162cb0e">printMDNodeBody</a>.</p>


<p>Referenced by <a href="#a536ea5f0471772d2cbeb45138b34bb46">writeAllMDNodes</a>.</p>

</div>
</div>

### writeOperand() {#ac7a7c36cb1f1a299406e3cfa95b7404e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, bool PrintType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2765 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#ac0c668efa4b03efd334831e35da09378">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>


<p>Referenced by <a href="#ae9005670841925a061ef19fe62955bce">printAlias</a>, <a href="#a6f875a89b00cf04b3d413c954e9fe915">printBasicBlock</a>, <a href="#ace495e41b614e9f54d0ae8c8ea318fcd">printFunction</a>, <a href="#a5529011752e50f62b1108a018df5e751">printGlobal</a>, <a href="#a89d2a6c720f05584135f01f20cc3c9ee">printIFunc</a>, <a href="#a27130c5f74c2f20dd183f5ab83f54e6c">printInstruction</a> and <a href="#acccf84e16de1e75d80dde03014d98473">printUseListOrder</a>.</p>

</div>
</div>

### writeOperandBundles() {#a404d6605bd1587cb6b67b8b1f575022e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeOperandBundles (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2767 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#ac0c668efa4b03efd334831e35da09378">getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/operandbundleuse/#a18c31f8bc506304f4a6c1e4047f1e2bb">llvm::OperandBundleUse::getTagName</a>, <a href="/web-llvm/docs/api/structs/llvm/operandbundleuse/#a6d68cbafa7572a5216785c899dc621fa">llvm::OperandBundleUse::Inputs</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>


<p>Referenced by <a href="#a27130c5f74c2f20dd183f5ab83f54e6c">printInstruction</a>.</p>

</div>
</div>

### writeParamOperand() {#adc27aa83649282c846c35b22413ebf83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeParamOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Operand, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2766 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#ac0c668efa4b03efd334831e35da09378">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> and <a href="#aab85047a4b52debd8bb9dc6556bf5113">writeAttributeSet</a>.</p>


<p>Referenced by <a href="#a27130c5f74c2f20dd183f5ab83f54e6c">printInstruction</a>.</p>

</div>
</div>

### writeSyncScope() {#a753ecf6e16982f73f95dbfa7149b1c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::writeSyncScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2768 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">llvm::SyncScope::System</a>.</p>


<p>Referenced by <a href="#aa6d634efc6c53e0f564e01aef25aaa0a">writeAtomic</a> and <a href="#a53364013a2915f73f0c81f0a7974aba9">writeAtomicCmpXchg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### printGCRelocateComment() {#a8885f1c7fc7719f28bffe5c6c596cc67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printGCRelocateComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst">GCRelocateInst</a> &amp; Relocate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>printGCRelocateComment - print comment after call to the gc.relocate intrinsic indicating base and derived pointer names.</p>

<p>Definition at line 2835 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### printInfoComment() {#a8caf78fafae4d68fc7c716a1b7d33ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printInfoComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>printInfoComment - Print a little comment after the instruction indicating which slot it occupies.</p>

<p>Definition at line 2831 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### printMetadataAttachments() {#ae63579096c29c3db1be63a3dbbf32309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssemblyWriter::printMetadataAttachments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &gt; &amp; MDs, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Separator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print out metadata attachments.</p>

<p>Definition at line 2825 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AnnotationWriter {#aabecea4d188a004896b615ee8cd58ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssemblyAnnotationWriter* anonymous{AsmWriter.cpp}::AssemblyWriter::AnnotationWriter = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2737 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### Comdats {#a4ca98b14b0bdd41c877ba8ca972c6eef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;const Comdat *&gt; anonymous{AsmWriter.cpp}::AssemblyWriter::Comdats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2738 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### IsForDebug {#a8ce5e40960ef2dce52188c0e277af7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmWriter.cpp}::AssemblyWriter::IsForDebug</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2739 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### Machine {#a5a71e6fa47b4fc15a5c698a67745c2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotTracker&amp; anonymous{AsmWriter.cpp}::AssemblyWriter::Machine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2735 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### MDNames {#a3d3fbbab1a05cde02918b8d7074b3fec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StringRef, 8&gt; anonymous{AsmWriter.cpp}::AssemblyWriter::MDNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2742 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### Out {#a5502abf1b4e8247c9c00b9431b479e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">formatted_raw_ostream&amp; anonymous{AsmWriter.cpp}::AssemblyWriter::Out</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2731 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### ShouldPreserveUseListOrder {#ad720b16486272ca93f5c08ca02266b60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AsmWriter.cpp}::AssemblyWriter::ShouldPreserveUseListOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2740 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### SlotTrackerStorage {#a3756ea3cb34f27897450ff34a769b856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SlotTracker&gt; anonymous{AsmWriter.cpp}::AssemblyWriter::SlotTrackerStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2734 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### SSNs {#a02ea6ade4e681eb4d37cb8cde28a99b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StringRef, 8&gt; anonymous{AsmWriter.cpp}::AssemblyWriter::SSNs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Synchronization scope names registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>

<p>Definition at line 2744 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### SummaryToGUIDMap {#a631b923ac4917dcc2b1cbaa7e87a006b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const GlobalValueSummary *, GlobalValue::GUID&gt; anonymous{AsmWriter.cpp}::AssemblyWriter::SummaryToGUIDMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2745 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### TheIndex {#a9e4b5d6513e09376795f23a01beb9a68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleSummaryIndex* anonymous{AsmWriter.cpp}::AssemblyWriter::TheIndex = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2733 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### TheModule {#a9730aab6b5a2298136edefa82982b5ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module* anonymous{AsmWriter.cpp}::AssemblyWriter::TheModule = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2732 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### TypePrinter {#ae3a034e5b40e5795972ca6e44105e1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypePrinting anonymous{AsmWriter.cpp}::AssemblyWriter::TypePrinter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2736 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### UseListOrders {#aa2c464d319bea37115b71f21b8f1e34a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UseListOrderMap anonymous{AsmWriter.cpp}::AssemblyWriter::UseListOrders</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2741 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
