---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/writeref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WriteRef` Class

<p>A reference to a register write. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::WriteRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">llvm/MCA/HardwareUnits/RegisterFile.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833e1a55959fe53db661f37d7cb7d939">WriteRef</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa5e13f96a99e15a475430906b5bf77">WriteRef</a> (unsigned SourceIndex, WriteState *WS)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9398f61c22f4c1024aa4b2c46a5ae3d7">operator==</a> (const WriteRef &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20af3b12bfc186241f64184daf799a31">getSourceIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21d536ceb2443d93a98c50e5d0d1153">getWriteBackCycle</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/writestate">WriteState</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3fa6f3913b02ca785582b43e06c7401">getWriteState</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/writestate">WriteState</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f66561a90f87925c227a448526edfd">getWriteState</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2322850429b4482184841861b5fe8279">getWriteResourceID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba38aec982153accf474bfe396d833bb">getRegisterID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0829d9a1b982b240442bf94b38857b">commit</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293ffb54d80a7b162bcc0dda787106c8">notifyExecuted</a> (unsigned Cycle)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4045c36ca1b3e8a6408d3eca7feab7a">hasKnownWriteBackCycle</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e682e1f07caa8665b2b72dada628493">isWriteZero</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd257701b8ad45e56d9954237782d9f4">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17ce90d8183bb4c68696c25b7b2fd637">isAvailable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this register write has been executed, and the new register value is therefore available to users. <a href="#a17ce90d8183bb4c68696c25b7b2fd637">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3087249ea30e15b4ab04765242d51bd">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed6c208a4040239993e92656d43abc7">IID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b028b4039868ad8048ef7e5c551ff1">WriteBackCycle</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86b0733c162b7131038819944f290968">WriteResID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c186e5f00ec05ae513501bcce52cac3">RegisterID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/writestate">WriteState</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8178f6696f22408ed76d43cdde572ec3">Write</a></td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3390b68ab1f339449653c1e97ef2b021">INVALID_IID</a> = std::numeric_limits&lt;unsigned&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
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

<p>A reference to a register write.</p>


<p>This class is mainly used by the register file to describe register mappings. It correlates a register write to the source index of the defining instruction.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WriteRef() {#a833e1a55959fe53db661f37d7cb7d939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::WriteRef::WriteRef ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>


<p>Referenced by <a href="#a9398f61c22f4c1024aa4b2c46a5ae3d7">operator==</a>.</p>

</div>
</div>

### WriteRef() {#a0aa5e13f96a99e15a475430906b5bf77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::WriteRef::WriteRef (unsigned SourceIndex, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate">WriteState</a> * WS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a9398f61c22f4c1024aa4b2c46a5ae3d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::WriteRef::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/writeref">WriteRef</a> &amp; Other)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a833e1a55959fe53db661f37d7cb7d939">WriteRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### commit() {#a7b0829d9a1b982b240442bf94b38857b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::WriteRef::commit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a7a65825cbd0e2859b88d170184507982">llvm::mca::RegisterFile::removeRegisterWrite</a>.</p>

</div>
</div>

### dump() {#aa3087249ea30e15b4ab04765242d51bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::WriteRef::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#a543498eab55ee4dd759f3a0afb4a085f">llvm::mca::WriteState::dump</a>, <a href="#a20af3b12bfc186241f64184daf799a31">getSourceIndex</a>, <a href="#ab3fa6f3913b02ca785582b43e06c7401">getWriteState</a> and <a href="#abd257701b8ad45e56d9954237782d9f4">isValid</a>.</p>

</div>
</div>

### getRegisterID() {#aba38aec982153accf474bfe396d833bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCPhysReg llvm::mca::WriteRef::getRegisterID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>

</div>
</div>

### getSourceIndex() {#a20af3b12bfc186241f64184daf799a31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::WriteRef::getSourceIndex ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a25dd8effff24d6d3273181f469154ee5">llvm::mca::RegisterFile::addRegisterWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>, <a href="#aa3087249ea30e15b4ab04765242d51bd">dump</a> and <a href="#abd257701b8ad45e56d9954237782d9f4">isValid</a>.</p>

</div>
</div>

### getWriteBackCycle() {#af21d536ceb2443d93a98c50e5d0d1153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::WriteRef::getWriteBackCycle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af4045c36ca1b3e8a6408d3eca7feab7a">hasKnownWriteBackCycle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a1466f7d3691522202889297ef461b3c5">llvm::mca::RegisterFile::getElapsedCyclesFromWriteBack</a>.</p>

</div>
</div>

### getWriteResourceID() {#a2322850429b4482184841861b5fe8279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::WriteRef::getWriteResourceID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>.</p>

</div>
</div>

### getWriteState() {#ab3fa6f3913b02ca785582b43e06c7401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WriteState * llvm::mca::WriteRef::getWriteState ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a25dd8effff24d6d3273181f469154ee5">llvm::mca::RegisterFile::addRegisterWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>, <a href="#aa3087249ea30e15b4ab04765242d51bd">dump</a>, <a href="#a2e682e1f07caa8665b2b72dada628493">isWriteZero</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#aff33426f5edf9f386718b122bae39f7b">llvm::mca::RegisterFile::onInstructionExecuted</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a7a65825cbd0e2859b88d170184507982">llvm::mca::RegisterFile::removeRegisterWrite</a>.</p>

</div>
</div>

### getWriteState() {#ac2f66561a90f87925c227a448526edfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WriteState * llvm::mca::WriteRef::getWriteState ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### hasKnownWriteBackCycle() {#af4045c36ca1b3e8a6408d3eca7feab7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::WriteRef::hasKnownWriteBackCycle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>Reference <a href="#abd257701b8ad45e56d9954237782d9f4">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a1466f7d3691522202889297ef461b3c5">llvm::mca::RegisterFile::getElapsedCyclesFromWriteBack</a>, <a href="#af21d536ceb2443d93a98c50e5d0d1153">getWriteBackCycle</a> and <a href="#a17ce90d8183bb4c68696c25b7b2fd637">isAvailable</a>.</p>

</div>
</div>

### isAvailable() {#a17ce90d8183bb4c68696c25b7b2fd637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::WriteRef::isAvailable ()</td>
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

<p>Returns true if this register write has been executed, and the new register value is therefore available to users.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>


<p>Reference <a href="#af4045c36ca1b3e8a6408d3eca7feab7a">hasKnownWriteBackCycle</a>.</p>

</div>
</div>

### isValid() {#abd257701b8ad45e56d9954237782d9f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::WriteRef::isValid ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>


<p>Reference <a href="#a20af3b12bfc186241f64184daf799a31">getSourceIndex</a>.</p>


<p>Referenced by <a href="#aa3087249ea30e15b4ab04765242d51bd">dump</a>, <a href="#af4045c36ca1b3e8a6408d3eca7feab7a">hasKnownWriteBackCycle</a> and <a href="#a2e682e1f07caa8665b2b72dada628493">isWriteZero</a>.</p>

</div>
</div>

### isWriteZero() {#a2e682e1f07caa8665b2b72dada628493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::WriteRef::isWriteZero ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab3fa6f3913b02ca785582b43e06c7401">getWriteState</a>, <a href="#abd257701b8ad45e56d9954237782d9f4">isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/writestate/#ade56a94cb586991cf9605301d237cdbe">llvm::mca::WriteState::isWriteZero</a>.</p>

</div>
</div>

### notifyExecuted() {#a293ffb54d80a7b162bcc0dda787106c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::WriteRef::notifyExecuted (unsigned Cycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#aff33426f5edf9f386718b122bae39f7b">llvm::mca::RegisterFile::onInstructionExecuted</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IID {#a1ed6c208a4040239993e92656d43abc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::WriteRef::IID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### RegisterID {#a3c186e5f00ec05ae513501bcce52cac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCPhysReg llvm::mca::WriteRef::RegisterID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### Write {#a8178f6696f22408ed76d43cdde572ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WriteState* llvm::mca::WriteRef::Write</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### WriteBackCycle {#a20b028b4039868ad8048ef7e5c551ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::WriteRef::WriteBackCycle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

### WriteResID {#a86b0733c162b7131038819944f290968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::WriteRef::WriteResID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### INVALID\_IID {#a3390b68ab1f339449653c1e97ef2b021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::mca::WriteRef::INVALID_IID = std::numeric_limits&lt;unsigned&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/registerfile-h">RegisterFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/registerfile-cpp">RegisterFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
