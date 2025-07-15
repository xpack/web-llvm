---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppcgenregisterbankinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PPCGenRegisterBankInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::PPCGenRegisterBankInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcregisterbankinfo-h">Target/PowerPC/GISel/PPCRegisterBankInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds all the information related to register banks. <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo">PPCRegisterBankInfo</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PartialMappingIdx { <a href="#a79e3b30e8cd36fdc4e42996a9a3bb767">...</a> }</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace53ff5aeaa5e6fc30696d67a6e483bd">getValueMapping</a> (PartialMappingIdx RBIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the pointer to the <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> representing the <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> at <span class="doxyComputerOutput">RBIdx</span>. <a href="#ace53ff5aeaa5e6fc30696d67a6e483bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a417eb0f48d7b970297c97228ba4c12e5">getCopyMapping</a> (unsigned DstBankID, unsigned SrcBankID, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the pointer to the <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> of the operands of a copy instruction from the <span class="doxyComputerOutput">SrcBankID</span> register bank to the <span class="doxyComputerOutput">DstBankID</span> register bank with a size of <span class="doxyComputerOutput">Size</span>. <a href="#a417eb0f48d7b970297c97228ba4c12e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">RegisterBankInfo::PartialMapping</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74da2aa3dca76bde115df107d97fccb1">PartMappings</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ccac6e887d61e78d4bdd0b8eb72bdaf">ValMappings</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a79e3b30e8cd36fdc4e42996a9a3bb767">PartialMappingIdx</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64fd96e6fe4e2eb1c6046fa7239bf75a">BankIDToCopyMapIdx</a>[]</td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcregisterbankinfo-h">PPCRegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### PartialMappingIdx {#a79e3b30e8cd36fdc4e42996a9a3bb767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPCGenRegisterBankInfo::PartialMappingIdx </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
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
<td class="doxyEnumItemName">PMI_None<a id="a79e3b30e8cd36fdc4e42996a9a3bb767a2ee23870f2fd48da4bd5da6a4b7fdf52"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_GPR32<a id="a79e3b30e8cd36fdc4e42996a9a3bb767abc0dd26ab279f12128dd8201db365bdb"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_GPR64<a id="a79e3b30e8cd36fdc4e42996a9a3bb767a9fbfbb69fa262e0ebfb3cdb198a910c3"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FPR32<a id="a79e3b30e8cd36fdc4e42996a9a3bb767af5d01deba7ccc0d5cbeaa267053678f5"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FPR64<a id="a79e3b30e8cd36fdc4e42996a9a3bb767ab9388c733da9c7190d24873ee8cd8a5a"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_VEC128<a id="a79e3b30e8cd36fdc4e42996a9a3bb767a75476602555c7e122b1693a1fa386050"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_CR<a id="a79e3b30e8cd36fdc4e42996a9a3bb767ae54a65ab84c65f7910d7822f9ad4928a"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_Min<a id="a79e3b30e8cd36fdc4e42996a9a3bb767a542bcdd9bd9aeba56a1434af96b39b77"></a></td>
<td class="doxyEnumItemDescription"> (= PMI_GPR32)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcregisterbankinfo-h">PPCRegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### getCopyMapping() {#a417eb0f48d7b970297c97228ba4c12e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping * llvm::PPCGenRegisterBankInfo::getCopyMapping (unsigned DstBankID, unsigned SrcBankID, unsigned Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the pointer to the <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> of the operands of a copy instruction from the <span class="doxyComputerOutput">SrcBankID</span> register bank to the <span class="doxyComputerOutput">DstBankID</span> register bank with a size of <span class="doxyComputerOutput">Size</span>.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcregisterbankinfo-h">PPCRegisterBankInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

### getValueMapping() {#ace53ff5aeaa5e6fc30696d67a6e483bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping * llvm::PPCGenRegisterBankInfo::getValueMapping (<a href="#a79e3b30e8cd36fdc4e42996a9a3bb767">PartialMappingIdx</a> RBIdx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the pointer to the <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> representing the <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> at <span class="doxyComputerOutput">RBIdx</span>.</p>


<p>The returned mapping works for instructions with the same kind of operands for up to 3 operands.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">RBIdx</span> != PartialMappingIdx::None</p></dd>
</dl>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcregisterbankinfo-h">PPCRegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### BankIDToCopyMapIdx {#a64fd96e6fe4e2eb1c6046fa7239bf75a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PartialMappingIdx llvm::PPCGenRegisterBankInfo::BankIDToCopyMapIdx[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcregisterbankinfo-h">PPCRegisterBankInfo.h</a>.</p>

</div>
</div>

### PartMappings {#a74da2aa3dca76bde115df107d97fccb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::PartialMapping llvm::PPCGenRegisterBankInfo::PartMappings[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcregisterbankinfo-h">PPCRegisterBankInfo.h</a>.</p>

</div>
</div>

### ValMappings {#a0ccac6e887d61e78d4bdd0b8eb72bdaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping llvm::PPCGenRegisterBankInfo::ValMappings[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcregisterbankinfo-h">PPCRegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcregisterbankinfo-h">PPCRegisterBankInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
