---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/dependencygraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DependencyGraph` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::DependencyGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">llvm/Transforms/Vectorize/SandboxVectorizer/DependencyGraph.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DependencyType { <a href="#af4c4ae4efd379d5909425bcde3a895c0">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad6892c718b879bc0698bf964c26082">DependencyGraph</a> (AAResults &amp;AA, Context &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor also registers callbacks. <a href="#a7ad6892c718b879bc0698bf964c26082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3c9c7bbc1c42116b170288ca439786">~DependencyGraph</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d01fa2445dc8a828884a106979acc1">getNode</a> (Instruction *I) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b46d781baee65722d04c13cf46d68ee">getNodeOrNull</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Like <a href="#a53d01fa2445dc8a828884a106979acc1">getNode()</a> but returns nullptr if <span class="doxyComputerOutput">I</span> is nullptr. <a href="#a9b46d781baee65722d04c13cf46d68ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab738214b8747fd2e0d9429149718b286">getOrCreateNode</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab89419b289ce60676c9dcca14e365b7b">extend</a> (ArrayRef&lt; Instruction * &gt; Instrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build/extend the dependency graph such that it includes <span class="doxyComputerOutput">Instrs</span>. <a href="#ab89419b289ce60676c9dcca14e365b7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1209a84e8b6d155d6450bf793d098066">getInterval</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the range of instructions included in the DAG. <a href="#a1209a84e8b6d155d6450bf793d098066">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0878831867afeb41543432d50679ae00">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6263e5ae80d0e8dffd164c1587af04">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if the DAG's state is clear. Used in assertions. <a href="#a1e6263e5ae80d0e8dffd164c1587af04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8602ab3d40d78dfbf826e154ac3fb8d">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c5d61503c625e40ca3f67bbbbad8916">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a77d064e2679f3142f452af12c06288">alias</a> (Instruction *SrcI, Instruction *DstI, DependencyType DepType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if there is a memory/other dependency <span class="doxyComputerOutput">SrcI-&gt;DstI</span>. <a href="#a3a77d064e2679f3142f452af12c06288">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304780f82b784f09b5c378f2e87e28bb">hasDep</a> (sandboxir::Instruction *SrcI, sandboxir::Instruction *DstI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f8f716c5275436025caf11548385f0">scanAndAddDeps</a> (MemDGNode &amp;DstN, const Interval&lt; MemDGNode &gt; &amp;SrcScanRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go through all mem nodes in <span class="doxyComputerOutput">SrcScanRange</span> and try to add dependencies to <span class="doxyComputerOutput">DstN</span>. <a href="#a35f8f716c5275436025caf11548385f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3dba7792bad1a55453a9522089feb7">setDefUseUnscheduledSuccs</a> (const Interval&lt; Instruction &gt; &amp;NewInterval)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the UnscheduledSuccs of all DGNodes in <span class="doxyComputerOutput">NewInterval</span> based on def-use edges. <a href="#a1e3dba7792bad1a55453a9522089feb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f3034b2ff231a27994a8629e06c8ed9">createNewNodes</a> (const Interval&lt; Instruction &gt; &amp;NewInterval)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create DAG nodes for instrs in <span class="doxyComputerOutput">NewInterval</span> and update the MemNode chain. <a href="#a1f3034b2ff231a27994a8629e06c8ed9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af452576e49e4fd9d67a27106fc3c015a">getMemDGNodeBefore</a> (DGNode *N, bool IncludingN, MemDGNode *SkipN=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for <span class="doxyComputerOutput">notify*Instr()</span>. <a href="#af452576e49e4fd9d67a27106fc3c015a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af89a71b006efc89877cd19adea60a766">getMemDGNodeAfter</a> (DGNode *N, bool IncludingN, MemDGNode *SkipN=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for <span class="doxyComputerOutput">notifyMoveInstr()</span>. <a href="#af89a71b006efc89877cd19adea60a766">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad847a5eff7d0078304b5e148de8224a1">notifyCreateInstr</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by the callbacks when a new instruction <span class="doxyComputerOutput">I</span> has been created. <a href="#ad847a5eff7d0078304b5e148de8224a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9434a0c9c866151369e7715b8a50f40">notifyEraseInstr</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by the callbacks when instruction <span class="doxyComputerOutput">I</span> is about to get deleted. <a href="#ae9434a0c9c866151369e7715b8a50f40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a2f48b8a602b9b291ecf24d0c94cd7">notifyMoveInstr</a> (Instruction *I, const BBIterator &amp;To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by the callbacks when instruction <span class="doxyComputerOutput">I</span> is about to be moved to <span class="doxyComputerOutput">To</span>. <a href="#ad5a2f48b8a602b9b291ecf24d0c94cd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c384a470e8b404bb95b100784f54712">InstrToNodeMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f9a55cf0e7d2748b1be3aee5eb22e2">DAGInterval</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DAG spans across all instructions in this interval. <a href="#a10f9a55cf0e7d2748b1be3aee5eb22e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2fab80e8b258b648a4c174153bb4d6f">Ctx</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">Context::CallbackID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fc01d94541248aed73cd7876a5577a8">CreateInstrCB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">Context::CallbackID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e65a1c6f6a36cec2f44e2a2615ab403">EraseInstrCB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/callbackid">Context::CallbackID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0952a6ce706f3c15ce9fe0b59bec806f">MoveInstrCB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a45e8aa0e1c4634669e1306aba3825">BatchAA</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static DependencyType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9755e843016dd6cfeeecdd4740ffcea9">getRoughDepType</a> (Instruction *FromI, Instruction *ToI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the dependency type depending on whether instructions may read/write memory or whether they are some specific opcode-related restrictions. <a href="#a9755e843016dd6cfeeecdd4740ffcea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### DependencyType {#af4c4ae4efd379d5909425bcde3a895c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::sandboxir::DependencyGraph::DependencyType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ReadAfterWrite<a id="af4c4ae4efd379d5909425bcde3a895c0af7ffd3bf370060bf4f8b165a240ab04d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WriteAfterWrite<a id="af4c4ae4efd379d5909425bcde3a895c0aa08b0599f006ea7bb1feadd3fc50527f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WriteAfterRead<a id="af4c4ae4efd379d5909425bcde3a895c0a7a15f80f73d5a9a70d3fabe6907dcb3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Control<a id="af4c4ae4efd379d5909425bcde3a895c0aa1595abbb4c3a326636dd178757cd6c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Other<a id="af4c4ae4efd379d5909425bcde3a895c0a6311ae17c1ee52b36e68aaf4ad066387"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="af4c4ae4efd379d5909425bcde3a895c0a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DependencyGraph() {#a7ad6892c718b879bc0698bf964c26082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::DependencyGraph::DependencyGraph (<a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AA, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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

<p>This constructor also registers callbacks.</p>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DependencyGraph() {#a8b3c9c7bbc1c42116b170288ca439786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::DependencyGraph::~DependencyGraph ()</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a0878831867afeb41543432d50679ae00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DependencyGraph::clear ()</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### dump() {#a4c5d61503c625e40ca3f67bbbbad8916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DependencyGraph::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#aa8602ab3d40d78dfbf826e154ac3fb8d">print</a>.</p>

</div>
</div>

### empty() {#a1e6263e5ae80d0e8dffd164c1587af04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DependencyGraph::empty ()</td>
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

<p>\Returns true if the DAG's state is clear. Used in assertions.</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### extend() {#ab89419b289ce60676c9dcca14e365b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Interval&lt; Instruction &gt; llvm::sandboxir::DependencyGraph::extend (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * &gt; Instrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build/extend the dependency graph such that it includes <span class="doxyComputerOutput">Instrs</span>.</p>


<p>Returns the range of instructions added to the DAG.</p>


<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnodeintervalbuilder/#af0cf2e45248094d2e024dc4ce6917fdc">llvm::sandboxir::MemDGNodeIntervalBuilder::make</a>.</p>

</div>
</div>

### getInterval() {#a1209a84e8b6d155d6450bf793d098066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Interval&lt; Instruction &gt; llvm::sandboxir::DependencyGraph::getInterval ()</td>
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

<p>\Returns the range of instructions included in the DAG.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### getNode() {#a53d01fa2445dc8a828884a106979acc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DGNode * llvm::sandboxir::DependencyGraph::getNode (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnodeintervalbuilder/#a5a0f15c37075c267f196cf8b7924e972">llvm::sandboxir::MemDGNodeIntervalBuilder::getBotMemDGNode</a>, <a href="#a9b46d781baee65722d04c13cf46d68ee">getNodeOrNull</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnodeintervalbuilder/#a99dd801df4d1697edd4ddd637666c084">llvm::sandboxir::MemDGNodeIntervalBuilder::getTopMemDGNode</a>.</p>

</div>
</div>

### getNodeOrNull() {#a9b46d781baee65722d04c13cf46d68ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DGNode * llvm::sandboxir::DependencyGraph::getNodeOrNull (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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

<p>Like <a href="#a53d01fa2445dc8a828884a106979acc1">getNode()</a> but returns nullptr if <span class="doxyComputerOutput">I</span> is nullptr.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a53d01fa2445dc8a828884a106979acc1">getNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getOrCreateNode() {#ab738214b8747fd2e0d9429149718b286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DGNode * llvm::sandboxir::DependencyGraph::getOrCreateNode (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#ac1b89d7c178eb196de3d1f05cc205642">llvm::sandboxir::DGNode::isMemDepNodeCandidate</a>.</p>

</div>
</div>

### print() {#aa8602ab3d40d78dfbf826e154ac3fb8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DependencyGraph::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ad1664de8206ba30fc8d13a01850f42db">llvm::sandboxir::Instruction::comesBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#ad6adf15fe451a7d857cea3f8a1905f81">llvm::sandboxir::DGNode::getInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a4c5d61503c625e40ca3f67bbbbad8916">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### alias() {#a3a77d064e2679f3142f452af12c06288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DependencyGraph::alias (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * SrcI, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * DstI, DependencyType DepType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns true if there is a memory/other dependency <span class="doxyComputerOutput">SrcI-&gt;DstI</span>.</p>

<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

### createNewNodes() {#a1f3034b2ff231a27994a8629e06c8ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DependencyGraph::createNewNodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> &gt; &amp; NewInterval)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create DAG nodes for instrs in <span class="doxyComputerOutput">NewInterval</span> and update the MemNode chain.</p>

<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

### getMemDGNodeAfter() {#af89a71b006efc89877cd19adea60a766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDGNode * llvm::sandboxir::DependencyGraph::getMemDGNodeAfter (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> * N, bool IncludingN, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> * SkipN=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for <span class="doxyComputerOutput">notifyMoveInstr()</span>.</p>


<p>\Returns the first <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> that comes after <span class="doxyComputerOutput">N</span>, skipping <span class="doxyComputerOutput">SkipN</span>, including or excluding <span class="doxyComputerOutput">N</span> based on <span class="doxyComputerOutput">IncludingN</span>, or nullptr if not found.</p>


<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

### getMemDGNodeBefore() {#af452576e49e4fd9d67a27106fc3c015a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDGNode * llvm::sandboxir::DependencyGraph::getMemDGNodeBefore (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> * N, bool IncludingN, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> * SkipN=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for <span class="doxyComputerOutput">notify*Instr()</span>.</p>


<p>\Returns the first <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> that comes before <span class="doxyComputerOutput">N</span>, skipping <span class="doxyComputerOutput">SkipN</span>, including or excluding <span class="doxyComputerOutput">N</span> based on <span class="doxyComputerOutput">IncludingN</span>, or nullptr if not found.</p>


<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

### hasDep() {#a304780f82b784f09b5c378f2e87e28bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DependencyGraph::hasDep (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">sandboxir::Instruction</a> * SrcI, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">sandboxir::Instruction</a> * DstI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

### notifyCreateInstr() {#ad847a5eff7d0078304b5e148de8224a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DependencyGraph::notifyCreateInstr (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called by the callbacks when a new instruction <span class="doxyComputerOutput">I</span> has been created.</p>

<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

### notifyEraseInstr() {#ae9434a0c9c866151369e7715b8a50f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DependencyGraph::notifyEraseInstr (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called by the callbacks when instruction <span class="doxyComputerOutput">I</span> is about to get deleted.</p>

<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

### notifyMoveInstr() {#ad5a2f48b8a602b9b291ecf24d0c94cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DependencyGraph::notifyMoveInstr (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBIterator &amp; To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called by the callbacks when instruction <span class="doxyComputerOutput">I</span> is about to be moved to <span class="doxyComputerOutput">To</span>.</p>

<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

### scanAndAddDeps() {#a35f8f716c5275436025caf11548385f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DependencyGraph::scanAndAddDeps (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> &amp; DstN, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> &gt; &amp; SrcScanRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Go through all mem nodes in <span class="doxyComputerOutput">SrcScanRange</span> and try to add dependencies to <span class="doxyComputerOutput">DstN</span>.</p>

<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

### setDefUseUnscheduledSuccs() {#a1e3dba7792bad1a55453a9522089feb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DependencyGraph::setDefUseUnscheduledSuccs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> &gt; &amp; NewInterval)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the UnscheduledSuccs of all DGNodes in <span class="doxyComputerOutput">NewInterval</span> based on def-use edges.</p>

<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BatchAA {#a20a45e8aa0e1c4634669e1306aba3825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BatchAAResults&gt; llvm::sandboxir::DependencyGraph::BatchAA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### CreateInstrCB {#a6fc01d94541248aed73cd7876a5577a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Context::CallbackID&gt; llvm::sandboxir::DependencyGraph::CreateInstrCB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### Ctx {#ad2fab80e8b258b648a4c174153bb4d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context* llvm::sandboxir::DependencyGraph::Ctx = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### DAGInterval {#a10f9a55cf0e7d2748b1be3aee5eb22e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Interval&lt;Instruction&gt; llvm::sandboxir::DependencyGraph::DAGInterval</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The DAG spans across all instructions in this interval.</p>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### EraseInstrCB {#a7e65a1c6f6a36cec2f44e2a2615ab403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Context::CallbackID&gt; llvm::sandboxir::DependencyGraph::EraseInstrCB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### InstrToNodeMap {#a7c384a470e8b404bb95b100784f54712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Instruction *, std::unique_ptr&lt;DGNode&gt; &gt; llvm::sandboxir::DependencyGraph::InstrToNodeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### MoveInstrCB {#a0952a6ce706f3c15ce9fe0b59bec806f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Context::CallbackID&gt; llvm::sandboxir::DependencyGraph::MoveInstrCB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getRoughDepType() {#a9755e843016dd6cfeeecdd4740ffcea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DependencyGraph::DependencyType llvm::sandboxir::DependencyGraph::getRoughDepType (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * FromI, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * ToI)</td>
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

<p>\Returns the dependency type depending on whether instructions may read/write memory or whether they are some specific opcode-related restrictions.</p>


<p>Note: It does not check whether a memory dependency is actually correct, as it won't call <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a>. Therefore it returns the worst-case dep type.</p>


<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
