---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/giselchangeobserver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GISelChangeObserver` Class Reference

<p>Abstract class that contains various methods for clients to notify about changes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GISelChangeObserver { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">llvm/CodeGen/GlobalISel/GISelChangeObserver.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/combiner/worklistmaintainer">WorkListMaintainer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class acts as the glue that joins the <a href="/web-llvm/docs/api/classes/llvm/combinerhelper">CombinerHelper</a> to the overall Combine algorithm. <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/instructionselect/miiteratormaintainer">MIIteratorMaintainer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class observes instruction insertions/removals. <a href="/web-llvm/docs/api/classes/instructionselect/miiteratormaintainer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuregisterbankinfo-cpp-/applyregbankmapping">ApplyRegBankMapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-irtranslator-cpp-/dilocationverifier">DILocationVerifier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that every instruction created has the same <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> as the instruction being translated. <a href="/web-llvm/docs/api/classes/anonymous-irtranslator-cpp-/dilocationverifier/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-legalizer-cpp-/legalizerworklistmanager">LegalizerWorkListManager</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipsregisterbankinfo-cpp-/instmanager">InstManager</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The CSE Analysis object. <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper">GISelObserverWrapper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple wrapper observer that takes several observers, and calls each one for each event. <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a></td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abba070d74d4a70cc63a5f402242dd2fc">~GISelChangeObserver</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbcc821688d1687f0b5faf9ba83bd902">erasingInstr</a> (MachineInstr &amp;MI)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction is about to be erased. <a href="#adbcc821688d1687f0b5faf9ba83bd902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53bec73a7e61679a0aed216280a0fc7">createdInstr</a> (MachineInstr &amp;MI)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction has been created and inserted into the function. <a href="#ac53bec73a7e61679a0aed216280a0fc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f637715070a99aa4140444e12697f9a">changingInstr</a> (MachineInstr &amp;MI)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction is about to be mutated in some way. <a href="#a1f637715070a99aa4140444e12697f9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45a05a932f80f51023592ff5131d56a5">changedInstr</a> (MachineInstr &amp;MI)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction was mutated in some way. <a href="#a45a05a932f80f51023592ff5131d56a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae260ef07f27a4b7f76496d9929bbb317">changingAllUsesOfReg</a> (const MachineRegisterInfo &amp;MRI, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All the instructions using the given register are being changed. <a href="#ae260ef07f27a4b7f76496d9929bbb317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274ff6e49f7c082a254920495943be57">finishedChangingAllUsesOfReg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All instructions reported as changing by <a href="#ae260ef07f27a4b7f76496d9929bbb317">changingAllUsesOfReg()</a> have finished being changed. <a href="#a274ff6e49f7c082a254920495943be57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a120b3d5cbe11c2ed005930483e3073e1">ChangingAllUsesOfReg</a></td>
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

## Description {#details}

<p>Abstract class that contains various methods for clients to notify about changes.</p>


<p>This should be the preferred way for APIs to notify changes. Typically calling erasingInstr/createdInstr multiple times should not affect the result. The observer would likely need to check if it was already notified earlier (consider using <a href="/web-llvm/docs/api/classes/llvm/giselworklist">GISelWorkList</a>).</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~GISelChangeObserver() {#abba070d74d4a70cc63a5f402242dd2fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::GISelChangeObserver::~GISelChangeObserver ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changedInstr() {#a45a05a932f80f51023592ff5131d56a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::GISelChangeObserver::changedInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This instruction was mutated in some way.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a50bbcbf690dd0de0a3f4abe2dd51fb55">anonymous{AArch64PostLegalizerLowering.cpp}::applyAdjustICmpImmAndPred</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a89a1d7d6a7cd7ea75a68ff3719372321">anonymous{AArch64PreLegalizerCombiner.cpp}::applyFoldGlobalOffset</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#aed33fa18d1d840b90fc467e1286ae39a">anonymous{AArch64PostLegalizerCombiner.cpp}::applyFoldMergeToZext</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#aaf7cc2c49ca5083e87a6ea579cc61831">anonymous{AArch64PostLegalizerLowering.cpp}::applyFormTruncstore</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a9bddeb3377e91345c52d28658dad61a3">anonymous{AArch64PreLegalizerCombiner.cpp}::applyICmpRedundantTrunc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#afe3d90eeb6011641d6a0263c17fc34c1">anonymous{AArch64PostLegalizerCombiner.cpp}::applyMutateAnyExtToZExt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a682303631f076977e40a54643727e8a4">anonymous{AArch64PostLegalizerLowering.cpp}::applySwapICmpOperands</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a14b95cfe536a811b87f134aa5e91c0f9">anonymous{AArch64PostLegalizerLowering.cpp}::applyUnmergeExtToUnmerge</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="#a274ff6e49f7c082a254920495943be57">finishedChangingAllUsesOfReg</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a51ac04efbaa3282a12478341fa0a7b9a">llvm::AMDGPULegalizerInfo::legalizeSBufferPrefetch</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5fb58d2b96b0e7a4a021fbe21869aaa8">llvm::AMDGPULegalizerInfo::legalizeStore</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a99f0584edf9a13120df821e7f77d9731">llvm::LegalizationArtifactCombiner::replaceRegOrBuildCopy</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#a90cc54876f57e2f6ee698215c7550ba7">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineUnmergeDefs</a>.</p>

</div>
</div>

### changingAllUsesOfReg() {#ae260ef07f27a4b7f76496d9929bbb317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GISelChangeObserver::changingAllUsesOfReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All the instructions using the given register are being changed.</p>


<p>For convenience, <a href="#a274ff6e49f7c082a254920495943be57">finishedChangingAllUsesOfReg()</a> will report the completion of the changes. The use list may change between this call and <a href="#a274ff6e49f7c082a254920495943be57">finishedChangingAllUsesOfReg()</a>.</p>


<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselchangeobserver-cpp">GISelChangeObserver.cpp</a>.</p>


<p>References <a href="#a1f637715070a99aa4140444e12697f9a">changingInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>.</p>

</div>
</div>

### changingInstr() {#a1f637715070a99aa4140444e12697f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::GISelChangeObserver::changingInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This instruction is about to be mutated in some way.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a50bbcbf690dd0de0a3f4abe2dd51fb55">anonymous{AArch64PostLegalizerLowering.cpp}::applyAdjustICmpImmAndPred</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a89a1d7d6a7cd7ea75a68ff3719372321">anonymous{AArch64PreLegalizerCombiner.cpp}::applyFoldGlobalOffset</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#aed33fa18d1d840b90fc467e1286ae39a">anonymous{AArch64PostLegalizerCombiner.cpp}::applyFoldMergeToZext</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#aaf7cc2c49ca5083e87a6ea579cc61831">anonymous{AArch64PostLegalizerLowering.cpp}::applyFormTruncstore</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a9bddeb3377e91345c52d28658dad61a3">anonymous{AArch64PreLegalizerCombiner.cpp}::applyICmpRedundantTrunc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#afe3d90eeb6011641d6a0263c17fc34c1">anonymous{AArch64PostLegalizerCombiner.cpp}::applyMutateAnyExtToZExt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a14b95cfe536a811b87f134aa5e91c0f9">anonymous{AArch64PostLegalizerLowering.cpp}::applyUnmergeExtToUnmerge</a>, <a href="#ae260ef07f27a4b7f76496d9929bbb317">changingAllUsesOfReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a51ac04efbaa3282a12478341fa0a7b9a">llvm::AMDGPULegalizerInfo::legalizeSBufferPrefetch</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5fb58d2b96b0e7a4a021fbe21869aaa8">llvm::AMDGPULegalizerInfo::legalizeStore</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a99f0584edf9a13120df821e7f77d9731">llvm::LegalizationArtifactCombiner::replaceRegOrBuildCopy</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#a90cc54876f57e2f6ee698215c7550ba7">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineUnmergeDefs</a>.</p>

</div>
</div>

### createdInstr() {#ac53bec73a7e61679a0aed216280a0fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::GISelChangeObserver::createdInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An instruction has been created and inserted into the function.</p>


<p>Note that the instruction might not be a fully fledged instruction at this point and won't be if the <a href="/web-llvm/docs/api/classes/llvm/machinefunction/delegate">MachineFunction::Delegate</a> is calling it. This is because the delegate only sees the construction of the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> before operands have been added.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### erasingInstr() {#adbcc821688d1687f0b5faf9ba83bd902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::GISelChangeObserver::erasingInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An instruction is about to be erased.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>.</p>

</div>
</div>

### finishedChangingAllUsesOfReg() {#a274ff6e49f7c082a254920495943be57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GISelChangeObserver::finishedChangingAllUsesOfReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All instructions reported as changing by <a href="#ae260ef07f27a4b7f76496d9929bbb317">changingAllUsesOfReg()</a> have finished being changed.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselchangeobserver-cpp">GISelChangeObserver.cpp</a>.</p>


<p>Reference <a href="#a45a05a932f80f51023592ff5131d56a5">changedInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ChangingAllUsesOfReg {#a120b3d5cbe11c2ed005930483e3073e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr *, 4&gt; llvm::GISelChangeObserver::ChangingAllUsesOfReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">GISelChangeObserver.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselchangeobserver-cpp">GISelChangeObserver.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
