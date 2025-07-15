---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ilist-node-with-parent
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ilist_node_with_parent` Class Template Reference

<p>An ilist node that can access its parent list. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename NodeTy, typename ParentTy, class... Options&gt;
class llvm::ilist_node_with_parent&lt;NodeTy, ParentTy, Options&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">llvm/ADT/ilist_node.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af7bbc12015222bdafcbffb722485be04">ilist_node_with_parent</a> ()=default</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ParentTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a31a823b492711c44518361f865cf8061">getNodeParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forward to NodeTy::getParent(). <a href="#a31a823b492711c44518361f865cf8061">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Adjacent Node Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1dfdcf6998ec28bfd2f8d2cdebc984a9">getPrevNode</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a292f8fd7937af71bfea9a9d8fcb0a4f9">getPrevNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the previous node, or <span class="doxyComputerOutput">nullptr</span> for the list head. <a href="#a292f8fd7937af71bfea9a9d8fcb0a4f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a62ee7ece4986606d41363bc1f70d5ab2">getNextNode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next node, or <span class="doxyComputerOutput">nullptr</span> for the list tail. <a href="#a62ee7ece4986606d41363bc1f70d5ab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad292c541aef6c435f7d6bc73f7e94189">getNextNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next node, or <span class="doxyComputerOutput">nullptr</span> for the list tail. <a href="#ad292c541aef6c435f7d6bc73f7e94189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An ilist node that can access its parent list.</p>


<p>Requires <span class="doxyComputerOutput">NodeTy</span> to have <em><a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">getParent()</a></em> to find the parent node, and the <span class="doxyComputerOutput">ParentTy</span> to have <em>getSublistAccess()</em> to get a reference to the list.</p>


<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### ilist\_node\_with\_parent() {#af7bbc12015222bdafcbffb722485be04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::ilist_node_with_parent ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; ilist_node_impl&lt; ilist_detail::compute_node_options&lt; NodeTy, Options... &gt;::type &gt;, ilist_detail::compute_node_options&lt; NodeTy, Options... &gt;::type::parent_ty &gt;::getParent</a>.</p>


<p>Referenced by <a href="#ad292c541aef6c435f7d6bc73f7e94189">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a> and <a href="#a292f8fd7937af71bfea9a9d8fcb0a4f9">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getPrevNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNodeParent() {#a31a823b492711c44518361f865cf8061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ParentTy * llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNodeParent ()</td>
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

<p>Forward to NodeTy::getParent().</p>


<p>Note: do not use the name "getParent()". We want a compile error (instead of recursion) when the subclass fails to implement <em><a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">getParent()</a></em>.</p>


<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Adjacent Node Accessors



<p>Get the previous node, or <span class="doxyComputerOutput">nullptr</span> for the list head.</p>


### getNextNode {#a62ee7ece4986606d41363bc1f70d5ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeTy * llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode ()</td>
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

<p>Get the next node, or <span class="doxyComputerOutput">nullptr</span> for the list tail.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a08610118e213de1b759470f0eafb9b18">llvm::OpenMPIRBuilder::collapseLoops</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#acf9b16e74216c278e3362f8e84c16ab0">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::copyArgsPassedByValToAllocas</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae0287686a5ffe03bc264972c862726ea">llvm::OpenMPIRBuilder::createCanonicalLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a819a79471317d350cbad8cfe9ad1c98e">llvm::getMachineInstrType</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a1bcb8bb92d8385a81a07659c6e1ec6fc">llvm::MustBeExecutedContextExplorer::getMustBeExecutedNextInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#a4801e594c6226fb9020a07ca36641c5b">getNextMachineInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a9c681660f7ed1f72a0a5ff822d4f5e8e">getNextNode</a>, <a href="#ad292c541aef6c435f7d6bc73f7e94189">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a0cb597b1f0cffe907fa834e9a95fe719">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3e3071be46334a57263e70548609d657">insertRelocationStores</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#aa6f399598404d630b1091693ed0a6f88">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a9364799319bac519aa565ec882986e6d">simplifyRelocatesOffABase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e4870aac193f722693ae7e24aa5a2be">llvm::sortBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85ee70791795fa2ddb07694182f783b2">llvm::splitBB</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a8369ab820502d8565628a7691353538a">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicCompareExchange</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a7c97c0b1f7463c3f6d909f1e95263e58">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicLoad</a>.</p>

</div>
</div>

### getNextNode {#ad292c541aef6c435f7d6bc73f7e94189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeTy * llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode ()</td>
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

<p>Get the next node, or <span class="doxyComputerOutput">nullptr</span> for the list tail.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>


<p>References <a href="#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a> and <a href="#af7bbc12015222bdafcbffb722485be04">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::ilist_node_with_parent</a>.</p>

</div>
</div>

### getPrevNode {#a1dfdcf6998ec28bfd2f8d2cdebc984a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeTy * llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getPrevNode ()</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#ab273671903c0baabbbf098a0a4581101">llvm::ARMBlockPlacement::fixBackwardsWLS</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysis/#aa20d83f600303548f2e24aa2fc98e377">llvm::CtxProfAnalysis::getCallsiteInstrumentation</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#aa990506f9bd98f9c5d4f82fdfe633116">llvm::MustBeExecutedContextExplorer::getMustBeExecutedPrevInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#aaf95913e52851622a35765cc28adf643">getOrCreateDebugLoc</a>, <a href="#a292f8fd7937af71bfea9a9d8fcb0a4f9">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getPrevNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunction/#abc9a654b8a69fecf6acc17555b12b8b2">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunction::getReplacementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysis/#a411b52f3710d28d5927341e36853f03b">llvm::CtxProfAnalysis::getSelectInstrumentation</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aaa8ee7d6ed01d35fd4b92fa9acc0eb1d">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::isAssumedDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-spirvstructurizer-cpp-/#a55f5674c6ed1c3e224388d258b79fcc5">llvm::anonymous{SPIRVStructurizer.cpp}::replaceIfBranchTargets</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/lockstepreverseiterator/#a681ac4eccb12ef854bb38bb656c1f1f5">anonymous{SimplifyCFG.cpp}::LockstepReverseIterator::reset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a9f3928b341e4412b8b66b794896014f0">simplifySuspendPoint</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#ae9b9f0a9eabb6c31d895d9b3e575fd51">anonymous{HotColdSplitting.cpp}::unlikelyExecuted</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#ac4d437dc2fa86f5a19219d3e8aa0d20b">updateKillStatus</a>.</p>

</div>
</div>

### getPrevNode {#a292f8fd7937af71bfea9a9d8fcb0a4f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeTy, typename ParentTy, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeTy * llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getPrevNode ()</td>
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

<p>Get the previous node, or <span class="doxyComputerOutput">nullptr</span> for the list head.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>


<p>References <a href="#a1dfdcf6998ec28bfd2f8d2cdebc984a9">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getPrevNode</a> and <a href="#af7bbc12015222bdafcbffb722485be04">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::ilist_node_with_parent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
