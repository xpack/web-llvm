---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instrprofsummarybuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstrProfSummaryBuilder` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::InstrProfSummaryBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">llvm/ProfileData/ProfileCommon.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder">ProfileSummaryBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8747e71b83f766bb1c7105a0e89bf07">InstrProfSummaryBuilder</a> (std::vector&lt; uint32_t &gt; Cutoffs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad877eb5253ae859efe7aef03e4c54e55">addEntryCount</a> (uint64_t Count)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2002e9c0d71251ac2410f38173a383ca">addInternalCount</a> (uint64_t Count)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99a638f9bdb5ab1005ba66d099cbd44">addRecord</a> (const InstrProfRecord &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/profilesummary">ProfileSummary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d13ddc46d3f3bb1f92b191513008e5a">getSummary</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57acb857039fcffc938cbfb204ad3eeb">MaxInternalBlockCount</a> = 0</td>
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


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrProfSummaryBuilder() {#ae8747e71b83f766bb1c7105a0e89bf07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfSummaryBuilder::InstrProfSummaryBuilder (std::vector&lt; uint32_t &gt; Cutoffs)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ab24fb220148ef06233b2609976f3da9e">llvm::ProfileSummaryBuilder::ProfileSummaryBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEntryCount() {#ad877eb5253ae859efe7aef03e4c54e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfSummaryBuilder::addEntryCount (uint64_t Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a28089a7d5a36c764dfe33f9f44b47d87">llvm::ProfileSummaryBuilder::addCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5751c9ba595d25bf69ea8b197ce8dd78">llvm::getInstrMaxCountValue</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a72a11c11194d7fa532931fa9421c7021">llvm::ProfileSummaryBuilder::MaxFunctionCount</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ac145bd9c0722766b91ad79062cb1028f">llvm::ProfileSummaryBuilder::NumFunctions</a>.</p>


<p>Referenced by <a href="#aa99a638f9bdb5ab1005ba66d099cbd44">addRecord</a>.</p>

</div>
</div>

### addInternalCount() {#a2002e9c0d71251ac2410f38173a383ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfSummaryBuilder::addInternalCount (uint64_t Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a28089a7d5a36c764dfe33f9f44b47d87">llvm::ProfileSummaryBuilder::addCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5751c9ba595d25bf69ea8b197ce8dd78">llvm::getInstrMaxCountValue</a>.</p>


<p>Referenced by <a href="#aa99a638f9bdb5ab1005ba66d099cbd44">addRecord</a>.</p>

</div>
</div>

### addRecord() {#aa99a638f9bdb5ab1005ba66d099cbd44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrProfSummaryBuilder::addRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord">InstrProfRecord</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="#ad877eb5253ae859efe7aef03e4c54e55">addEntryCount</a>, <a href="#a2002e9c0d71251ac2410f38173a383ca">addInternalCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a69bdbaedb4ae6b233e5eccac5ebc2d77ac46600297a1a6f13ed709e33fcc7ae4e">llvm::InstrProfRecord::NotPseudo</a>.</p>

</div>
</div>

### getSummary() {#a3d13ddc46d3f3bb1f92b191513008e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ProfileSummary &gt; InstrProfSummaryBuilder::getSummary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a0cf99f7dc09e330137cb10a3a42c12b3">llvm::ProfileSummaryBuilder::computeDetailedSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ad028b48e4b5b572a4d192042c467ac80">llvm::ProfileSummaryBuilder::DetailedSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a1680e5f0b03a6e19ab4b9043a2db4c56">llvm::ProfileSummaryBuilder::MaxCount</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a72a11c11194d7fa532931fa9421c7021">llvm::ProfileSummaryBuilder::MaxFunctionCount</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#adf42bc6121e00b01b160019b4761c546">llvm::ProfileSummaryBuilder::NumCounts</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ac145bd9c0722766b91ad79062cb1028f">llvm::ProfileSummaryBuilder::NumFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#aa5aa682b3904e88749fa973b3da370c2a8c847a58db35295f26d16ccbfcac6e0c">llvm::ProfileSummary::PSK_Instr</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a9f4b516c5122d851880c9e1f2cf59520">llvm::ProfileSummaryBuilder::TotalCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MaxInternalBlockCount {#a57acb857039fcffc938cbfb204ad3eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstrProfSummaryBuilder::MaxInternalBlockCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
