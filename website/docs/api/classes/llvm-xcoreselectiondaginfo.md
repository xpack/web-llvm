---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xcoreselectiondaginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XCoreSelectionDAGInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::XCoreSelectionDAGInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreselectiondaginfo-h">Target/XCore/XCoreSelectionDAGInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can subclass this to parameterize the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> lowering and instruction selection process. <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af87dbf9e0c8190963043ea6154532c25">EmitTargetCodeForMemcpy</a> (SelectionDAG &amp;DAG, const SDLoc &amp;dl, SDValue Chain, SDValue Op1, SDValue Op2, SDValue Op3, Align Alignment, bool isVolatile, bool AlwaysInline, MachinePointerInfo DstPtrInfo, MachinePointerInfo SrcPtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memcpy. <a href="#af87dbf9e0c8190963043ea6154532c25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreselectiondaginfo-h">XCoreSelectionDAGInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### EmitTargetCodeForMemcpy() {#af87dbf9e0c8190963043ea6154532c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue XCoreSelectionDAGInfo::EmitTargetCodeForMemcpy (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op3, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool isVolatile, bool AlwaysInline, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> DstPtrInfo, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> SrcPtrInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit target-specific code that performs a memcpy.</p>


<p>This can be used by targets to provide code sequences for cases that don't fit the target's parameters for simple loads/stores and can be more efficient than using a library call. This function can return a null <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if the target declines to use custom code and a different lowering strategy should be used.</p>


<p>If AlwaysInline is true, the size is constant and the target should not emit any calls and is strongly encouraged to attempt to emit inline code even if it is beyond the usual threshold because this intrinsic is being expanded in a place where calls are not feasible (e.g. within the prologue for another call). If the target chooses to decline an AlwaysInline request here, legalize will resort to using simple loads and stores.</p>


<p>Declaration at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreselectiondaginfo-h">XCoreSelectionDAGInfo.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreselectiondaginfo-cpp">XCoreSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa8f1c26a4e070ead6c67b4e9a5d93124">llvm::SelectionDAG::getExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a7a2619d0e489a4ba9c19a0d86a041d59">llvm::DataLayout::getIntPtrType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a165e3da23cb77e612919b366f1978af2">llvm::TargetLoweringBase::getLibcallCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a150a6b1d332e8d13b77970bd05a235ca">llvm::SelectionDAG::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aabd42a6eddc3daec9153679b54f79300">llvm::TargetLowering::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad5386f4196a9eab5701c451469f2e20e">llvm::SelectionDAG::MaskedValueIsZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#ae8c9a19c4e49854df72efd6a33299ca6">llvm::TargetLowering::CallLoweringInfo::setChain</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#aa05efb86ccf079a618d7ccc2d0984510">llvm::TargetLowering::CallLoweringInfo::setDebugLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a92da69e2625a91ae468da5ed229a3a93">llvm::TargetLowering::CallLoweringInfo::setDiscardResult</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a3273e8eefbe635bf0be621b276e22add">llvm::TargetLowering::CallLoweringInfo::setLibCallee</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreselectiondaginfo-cpp">XCoreSelectionDAGInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreselectiondaginfo-h">XCoreSelectionDAGInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
