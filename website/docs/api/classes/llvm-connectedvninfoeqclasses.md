---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/connectedvninfoeqclasses
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConnectedVNInfoEqClasses` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses">ConnectedVNInfoEqClasses</a> - Helper class that can divide VNInfos in a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> into equivalence clases of connected components. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConnectedVNInfoEqClasses { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">llvm/CodeGen/LiveInterval.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a266d2e02cf60caf2503f30d4c7ec15d6">ConnectedVNInfoEqClasses</a> (LiveIntervals &amp;lis)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab075ccec6878e16419fca5e423c7ddad">Classify</a> (const LiveRange &amp;LR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classify the values in <span class="doxyComputerOutput">LR</span> into connected components. <a href="#ab075ccec6878e16419fca5e423c7ddad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72973e4a97d936d5d4805a89a3cc2ec">getEqClass</a> (const VNInfo *VNI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEqClass - Classify creates equivalence classes numbered 0..N. <a href="#ae72973e4a97d936d5d4805a89a3cc2ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d79e4d110e15056182588d168ac6b2f">Distribute</a> (LiveInterval &amp;LI, LiveInterval *LIV[], MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Distribute values in <span class="doxyComputerOutput">LI</span> into a separate <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> for each connected component. <a href="#a5d79e4d110e15056182588d168ac6b2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4e24c61bc9112c7598bedfac4467f8">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inteqclasses">IntEqClasses</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e461049b5db639130c8f2165e7f7353">EqClass</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses">ConnectedVNInfoEqClasses</a> - Helper class that can divide VNInfos in a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> into equivalence clases of connected components.</p>


<p>A <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> that has multiple connected components can be broken into multiple <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>.</p>


<p>Given a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> that may have multiple connected components, run:</p>


<p>unsigned numComps = ConEQ.Classify(LI); if (numComps &gt; 1) { // allocate numComps-1 new <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> into LIS[1..] ConEQ.Distribute(LIS); }</p>


<p>Definition at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConnectedVNInfoEqClasses() {#a266d2e02cf60caf2503f30d4c7ec15d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConnectedVNInfoEqClasses::ConnectedVNInfoEqClasses (<a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; lis)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Classify() {#ab075ccec6878e16419fca5e423c7ddad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ConnectedVNInfoEqClasses::Classify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classify the values in <span class="doxyComputerOutput">LR</span> into connected components.</p>


<p>Returns the number of connected components.</p>


<p>Declaration at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a93450063916ca1ab1f11bf3304a6ad03">llvm::LiveRange::getNumValNums</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a7e1ec6260b229b2f5913405b758bc146">llvm::LiveRange::getVNInfoBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9eb4aa155c41e60dff42f4e741a0dcf0">llvm::LiveRange::valnos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aeffc1bb4ebe64a8ad3478e1253683847">llvm::LiveIntervals::splitSeparateComponents</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a787f3f4287374d61c5f0657dd83acbb4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveInterval</a>.</p>

</div>
</div>

### Distribute() {#a5d79e4d110e15056182588d168ac6b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConnectedVNInfoEqClasses::Distribute (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LIV=[], <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Distribute values in <span class="doxyComputerOutput">LI</span> into a separate <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> for each connected component.</p>


<p>LIV must have an empty <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> for each additional connected component. The first connected component is left in <span class="doxyComputerOutput">LI</span>.</p>


<p>Declaration at line 1026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1371 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#af6fb03322f7b38d6e815343732497798">llvm::LiveInterval::createSubRange</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78118d64746879fbc29e499228182853">llvm::DistributeRange</a>, <a href="#ae72973e4a97d936d5d4805a89a3cc2ec">getEqClass</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0aac3ef1eadaa206a70b767730ef3c5b">llvm::LiveInterval::removeEmptySubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#aaae33cfd0a31e453deec40b2d5274e70">llvm::LiveQueryResult::valueDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a> and <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a8c9627b7e8bbfa4fbd02f6644907147f">llvm::LiveQueryResult::valueOut</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aeffc1bb4ebe64a8ad3478e1253683847">llvm::LiveIntervals::splitSeparateComponents</a>.</p>

</div>
</div>

### getEqClass() {#ae72973e4a97d936d5d4805a89a3cc2ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ConnectedVNInfoEqClasses::getEqClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI)</td>
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

<p>getEqClass - Classify creates equivalence classes numbered 0..N.</p>


<p>Return the equivalence class assigned the VNI.</p>


<p>Definition at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>.</p>


<p>Referenced by <a href="#a5d79e4d110e15056182588d168ac6b2f">Distribute</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a787f3f4287374d61c5f0657dd83acbb4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveInterval</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EqClass {#a0e461049b5db639130c8f2165e7f7353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntEqClasses llvm::ConnectedVNInfoEqClasses::EqClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### LIS {#a3f4e24c61bc9112c7598bedfac4467f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals&amp; llvm::ConnectedVNInfoEqClasses::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
