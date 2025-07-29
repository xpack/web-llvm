---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ccvalassign
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CCValAssign` Class

<p><a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> - Represent assignment of one arg/retval to a location. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CCValAssign { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">llvm/CodeGen/CallingConvLower.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LocInfo { <a href="#a2b78fd53da0b5df7bc4eacf7df556a45">...</a> }</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a188e532798c13cfbb236db81f321b0c8">CCValAssign</a> (LocInfo HTP, unsigned ValNo, MVT ValVT, MVT LocVT, bool IsCustom)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a17634afdbaf2ee268be6118014845">convertToReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75b916fb8d50addf965f757f9089e17">convertToMem</a> (int64_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6f82d490b016e27d3a4cd7ab7efdf6">getValNo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5972ab02a98f9b5ce46e7f55fd711982">getValVT</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07dddcff2886a2b840f993f7ce17dd28">isRegLoc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb903a1b21cafe8f73ce95ed629882e">isMemLoc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a193a46550761f868004d800dd2a535d8">isPendingLoc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5378385666bd865565fcf8407fcc36f9">needsCustom</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17dbc2feaea84ef8d353095d6e618f29">getLocReg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa531ef30c8af299cbbd1a6660b3cf225">getLocMemOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8a3ce07066eca99fd4585de802748a">getExtraInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c2e47e51795ce2f60500846109d5a7">getLocVT</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2b78fd53da0b5df7bc4eacf7df556a45">LocInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2897ab064cc53e41f2b6ae3d69902abc">getLocInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00f5c6b7e90595b7eaa2776a51e1c38">isExtInLoc</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a337d96d4ea6bf079abd145d3c4e2cdec">isUpperBitsInLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::variant&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, int64_t, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a591c8c0b7bc2047746d1deefbd7e0c5c">Data</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f7884cb1bc607a222d86ff2057aba62">ValNo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValNo - This is the value number being assigned (e.g. an argument number). <a href="#a5f7884cb1bc607a222d86ff2057aba62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40753249331379f858d0f5f0224b6ce">isCustom</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isCustom - True if this arg/retval requires special handling. <a href="#ad40753249331379f858d0f5f0224b6ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2b78fd53da0b5df7bc4eacf7df556a45">LocInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0fd25111229a6e277a6b3c39fa3b0a">HTP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information about how the value is assigned. <a href="#a1c0fd25111229a6e277a6b3c39fa3b0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e3c9088096f6665d4f445c72ada869">ValVT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValVT - The type of the value being assigned. <a href="#a22e3c9088096f6665d4f445c72ada869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3122ed4728d0d91840bec3c30cf42d">LocVT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LocVT - The type of the location being assigned to. <a href="#aef3122ed4728d0d91840bec3c30cf42d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29708e79e029f1029d46d65e7631b778">getReg</a> (unsigned ValNo, MVT ValVT, MCRegister Reg, MVT LocVT, LocInfo HTP, bool IsCustom=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3213a94802bb4f87a3e388af6cdd9d7f">getCustomReg</a> (unsigned ValNo, MVT ValVT, MCRegister Reg, MVT LocVT, LocInfo HTP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d9dd26dea75ebba5b55516b52e0752">getMem</a> (unsigned ValNo, MVT ValVT, int64_t Offset, MVT LocVT, LocInfo HTP, bool IsCustom=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ca02e9c44d57c994cc5351c24f6223">getCustomMem</a> (unsigned ValNo, MVT ValVT, int64_t Offset, MVT LocVT, LocInfo HTP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1022d05ab2d1337a97addf0ea4678fed">getPending</a> (unsigned ValNo, MVT ValVT, MVT LocVT, LocInfo HTP, unsigned ExtraInfo=0)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> - Represent assignment of one arg/retval to a location.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### LocInfo {#a2b78fd53da0b5df7bc4eacf7df556a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::CCValAssign::LocInfo </td>
</tr>
</table>
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
<td class="doxyEnumItemName">Full<a id="a2b78fd53da0b5df7bc4eacf7df556a45a8b73d77b9e54663c2e80a48d0917dce1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SExt<a id="a2b78fd53da0b5df7bc4eacf7df556a45a7fd25972cdb14499949c7726499e0cb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZExt<a id="a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AExt<a id="a2b78fd53da0b5df7bc4eacf7df556a45acc07b91f72979f3e9b12c2e0c355db46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SExtUpper<a id="a2b78fd53da0b5df7bc4eacf7df556a45aec09697a16bc3cc461d29f0f551e63c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZExtUpper<a id="a2b78fd53da0b5df7bc4eacf7df556a45a17dad9007e52963b27d90b46bfab8cb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AExtUpper<a id="a2b78fd53da0b5df7bc4eacf7df556a45aeada2602a598f9b877f1b75ed7dd9e4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BCvt<a id="a2b78fd53da0b5df7bc4eacf7df556a45a0f94adbbe71c94edaa533a25973bbffc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Trunc<a id="a2b78fd53da0b5df7bc4eacf7df556a45a467b8d92c7df0dbb83e53cf2694920c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VExt<a id="a2b78fd53da0b5df7bc4eacf7df556a45aac6bf1a4743f81c8ee1cb10ef85ce063"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPExt<a id="a2b78fd53da0b5df7bc4eacf7df556a45ac52f457c429c17250b13662a5ddd0c4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Indirect<a id="a2b78fd53da0b5df7bc4eacf7df556a45aacf7e7d80f766b55b2bbdaf3d354c39e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### CCValAssign() {#a188e532798c13cfbb236db81f321b0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CCValAssign::CCValAssign (<a href="#a2b78fd53da0b5df7bc4eacf7df556a45">LocInfo</a> HTP, unsigned ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, bool IsCustom)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertToMem() {#af75b916fb8d50addf965f757f9089e17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CCValAssign::convertToMem (int64_t Offset)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### convertToReg() {#a08a17634afdbaf2ee268be6118014845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CCValAssign::convertToReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### getExtraInfo() {#a9a8a3ce07066eca99fd4585de802748a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CCValAssign::getExtraInfo ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>

</div>
</div>

### getLocInfo() {#a2897ab064cc53e41f2b6ae3d69902abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocInfo llvm::CCValAssign::getLocInfo ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a1cdf9ea1d249387f26e37569d6cdb088">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a475797835e85ab2eee4c3364cfc79a2f">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#aa0e53803ef9c1e4cee4e195ced9c0841">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a84f5d960aa6e996db2572c7d5c7b163e">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#a64309ae031097cf3cde8199ea5e0249a">llvm::CallLowering::IncomingValueHandler::buildExtensionHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a5e731292c2474865560219c29069c6de">canUseSiblingCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a80524f39942329cc334f7748283b556e">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a79833f5d23f7d199579738f2dc85ab60">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a79833f5d23f7d199579738f2dc85ab60">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2bc16e1191a3e8a096aae2f90f9b6677">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a1e734d495716fdccb9fd1497d802de2b">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a654343d6b7c4aa6aa1329f9ed421b225">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a654343d6b7c4aa6aa1329f9ed421b225">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59c8bc2723e6744d5618db1f430fc94a">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a9b9867c23ea2c20125ffe635160cb9bb">llvm::CallLowering::ValueHandler::extendRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9696c62f9eeb556df764837c92b560df">llvm::SITargetLowering::LowerCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4e7be374a3346400a32967d91108c3e">llvm::LoongArchTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a33edc5c19a9e674e389ecc1320464e23">llvm::HexagonTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4ce28f633cfe7a89369965cd9792e8fb">llvm::SITargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a73a391aef4505ecba196737cabb18ca0">llvm::VETargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#aa76596666bd4af3c0104b7a8fd514db0">llvm::SparcTargetLowering::LowerReturn_64</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a26c8cba96e72f333e829e607938ce893">llvm::CCState::resultsCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#ae809b55a75992a119dd6441aaeabd49b">UnpackFromArgumentSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a448318fedd7b77f12f1163c8d5a5b10a">unpackFromRegLoc</a>.</p>

</div>
</div>

### getLocMemOffset() {#aa531ef30c8af299cbbd1a6660b3cf225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::CCValAssign::getLocMemOffset ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a4017f4bbfa6740ad4927245ad4dba2c4">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#af1779518d5baec53b2ce17673169282f">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#aa0dc943f955ef5657bcc9eb702f611fd">lowerCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#af36f0d9675dc67d62c6cbf827ee7b745">llvm::R600TargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a479378216af352a6202281eb9b5b202a">llvm::CallLowering::resultsCompatible</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a26c8cba96e72f333e829e607938ce893">llvm::CCState::resultsCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a4fe763745add3c357f272b8f41264d6a">unpack64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae3c73a05257120f8a564e40826d20ace">unpackF64OnRV32DSoftABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>.</p>

</div>
</div>

### getLocReg() {#a17dbc2feaea84ef8d353095d6e618f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::CCValAssign::getLocReg ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a2d9bff6057c95e354dbc28e4604517c0">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#ac2990fcd086ddeb552b46fe5d49c77de">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#aa35ca40243a91b75afd51c04ee241788">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a8037cdaaf593bc895700f71a95ee9bcc">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a5e731292c2474865560219c29069c6de">canUseSiblingCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a49816805ae1abf4f4a01546d06c413a5">getv64i1Argument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9696c62f9eeb556df764837c92b560df">llvm::SITargetLowering::LowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#aa0dc943f955ef5657bcc9eb702f611fd">lowerCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#af36f0d9675dc67d62c6cbf827ee7b745">llvm::R600TargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a33edc5c19a9e674e389ecc1320464e23">llvm::HexagonTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#aece826681b1fdc9ec7c82f4a9152000f">llvm::LoongArchTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4ce28f633cfe7a89369965cd9792e8fb">llvm::SITargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a3a9a464956d7d22291e5a6a29d4266e5">llvm::SystemZTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a73a391aef4505ecba196737cabb18ca0">llvm::VETargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ae491d50e304bf7057a2f4dfbf1650e56">llvm::XtensaTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a97357df4054a9551eb9a07b609cea109">llvm::SparcTargetLowering::LowerReturn_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#aa76596666bd4af3c0104b7a8fd514db0">llvm::SparcTargetLowering::LowerReturn_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a44432ec9756a3ffcf9fcc04ad9dce2e9">Passv64i1ArgInRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a479378216af352a6202281eb9b5b202a">llvm::CallLowering::resultsCompatible</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a26c8cba96e72f333e829e607938ce893">llvm::CCState::resultsCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a4fe763745add3c357f272b8f41264d6a">unpack64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae3c73a05257120f8a564e40826d20ace">unpackF64OnRV32DSoftABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#af586c31be6208a365b50ac3a892be6d7">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad96e48f13961854d2242e9462a920394">unpackFromRegLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a448318fedd7b77f12f1163c8d5a5b10a">unpackFromRegLoc</a>.</p>

</div>
</div>

### getLocVT() {#ab7c2e47e51795ce2f60500846109d5a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::CCValAssign::getLocVT ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a1cdf9ea1d249387f26e37569d6cdb088">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a475797835e85ab2eee4c3364cfc79a2f">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuincomingarghandler/#a3769dc3bae28271b452cf69cf3494761">anonymous{AMDGPUCallLowering.cpp}::AMDGPUIncomingArgHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#aa35ca40243a91b75afd51c04ee241788">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a8037cdaaf593bc895700f71a95ee9bcc">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#a2d2d74818c4f4ba5fb41e8a4f2c9d152">llvm::CallLowering::IncomingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a90abcb97861455132a9ca451c19405f0">CC_LoongArchAssign2GRLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvcallingconv-cpp/#a10b000ebfe8f8018565e8180e73d3a7d">CC_RISCVAssign2XLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a80524f39942329cc334f7748283b556e">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a79833f5d23f7d199579738f2dc85ab60">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2bc16e1191a3e8a096aae2f90f9b6677">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a1e734d495716fdccb9fd1497d802de2b">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a654343d6b7c4aa6aa1329f9ed421b225">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a654343d6b7c4aa6aa1329f9ed421b225">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59c8bc2723e6744d5618db1f430fc94a">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a9b9867c23ea2c20125ffe635160cb9bb">llvm::CallLowering::ValueHandler::extendRegister</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucalllowering-cpp-/#af49a6097a8071a69f37f57febd91c05c">anonymous{AMDGPUCallLowering.cpp}::extendRegisterMin32</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a77c170f4c52ebc0ecaeaae4a2b660916">getStackValueStoreTypeHack</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9696c62f9eeb556df764837c92b560df">llvm::SITargetLowering::LowerCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#af36f0d9675dc67d62c6cbf827ee7b745">llvm::R600TargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a33edc5c19a9e674e389ecc1320464e23">llvm::HexagonTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#aece826681b1fdc9ec7c82f4a9152000f">llvm::LoongArchTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4ce28f633cfe7a89369965cd9792e8fb">llvm::SITargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a3a9a464956d7d22291e5a6a29d4266e5">llvm::SystemZTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a73a391aef4505ecba196737cabb18ca0">llvm::VETargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ae491d50e304bf7057a2f4dfbf1650e56">llvm::XtensaTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a97357df4054a9551eb9a07b609cea109">llvm::SparcTargetLowering::LowerReturn_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#aa76596666bd4af3c0104b7a8fd514db0">llvm::SparcTargetLowering::LowerReturn_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#ab268a162e6da94b8012d8366563ae9f7">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a313bdf934f1f8454b6800d8d997801d2">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a4fe763745add3c357f272b8f41264d6a">unpack64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae3c73a05257120f8a564e40826d20ace">unpackF64OnRV32DSoftABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#ae809b55a75992a119dd6441aaeabd49b">UnpackFromArgumentSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#af586c31be6208a365b50ac3a892be6d7">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad96e48f13961854d2242e9462a920394">unpackFromRegLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a448318fedd7b77f12f1163c8d5a5b10a">unpackFromRegLoc</a>.</p>

</div>
</div>

### getValNo() {#aad6f82d490b016e27d3a4cd7ab7efdf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CCValAssign::getValNo ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a2d9bff6057c95e354dbc28e4604517c0">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#ac2990fcd086ddeb552b46fe5d49c77de">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a90abcb97861455132a9ca451c19405f0">CC_LoongArchAssign2GRLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvcallingconv-cpp/#a10b000ebfe8f8018565e8180e73d3a7d">CC_RISCVAssign2XLen</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>.</p>

</div>
</div>

### getValVT() {#a5972ab02a98f9b5ce46e7f55fd711982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::CCValAssign::getValVT ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a2d9bff6057c95e354dbc28e4604517c0">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#ac2990fcd086ddeb552b46fe5d49c77de">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a1cdf9ea1d249387f26e37569d6cdb088">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a475797835e85ab2eee4c3364cfc79a2f">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#aa35ca40243a91b75afd51c04ee241788">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a8037cdaaf593bc895700f71a95ee9bcc">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a90abcb97861455132a9ca451c19405f0">CC_LoongArchAssign2GRLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvcallingconv-cpp/#a10b000ebfe8f8018565e8180e73d3a7d">CC_RISCVAssign2XLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a80524f39942329cc334f7748283b556e">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a79833f5d23f7d199579738f2dc85ab60">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a79833f5d23f7d199579738f2dc85ab60">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2bc16e1191a3e8a096aae2f90f9b6677">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a1e734d495716fdccb9fd1497d802de2b">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a654343d6b7c4aa6aa1329f9ed421b225">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59c8bc2723e6744d5618db1f430fc94a">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a9b9867c23ea2c20125ffe635160cb9bb">llvm::CallLowering::ValueHandler::extendRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a5176666164b27a32c0b6093b921cde29">llvm::CallLowering::ValueHandler::getStackValueStoreType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a77c170f4c52ebc0ecaeaae4a2b660916">getStackValueStoreTypeHack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a49816805ae1abf4f4a01546d06c413a5">getv64i1Argument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9696c62f9eeb556df764837c92b560df">llvm::SITargetLowering::LowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#aa0dc943f955ef5657bcc9eb702f611fd">lowerCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4e7be374a3346400a32967d91108c3e">llvm::LoongArchTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a73a391aef4505ecba196737cabb18ca0">llvm::VETargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#aa76596666bd4af3c0104b7a8fd514db0">llvm::SparcTargetLowering::LowerReturn_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a4fe763745add3c357f272b8f41264d6a">unpack64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae3c73a05257120f8a564e40826d20ace">unpackF64OnRV32DSoftABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#ae809b55a75992a119dd6441aaeabd49b">UnpackFromArgumentSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>.</p>

</div>
</div>

### isExtInLoc() {#aa00f5c6b7e90595b7eaa2776a51e1c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CCValAssign::isExtInLoc ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>References <a href="#a2b78fd53da0b5df7bc4eacf7df556a45acc07b91f72979f3e9b12c2e0c355db46">AExt</a>, <a href="#a2b78fd53da0b5df7bc4eacf7df556a45a7fd25972cdb14499949c7726499e0cb6">SExt</a> and <a href="#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">ZExt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a80524f39942329cc334f7748283b556e">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>.</p>

</div>
</div>

### isMemLoc() {#a5bb903a1b21cafe8f73ce95ed629882e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CCValAssign::isMemLoc ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9696c62f9eeb556df764837c92b560df">llvm::SITargetLowering::LowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#aa0dc943f955ef5657bcc9eb702f611fd">lowerCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a26c8cba96e72f333e829e607938ce893">llvm::CCState::resultsCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a4fe763745add3c357f272b8f41264d6a">unpack64</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae3c73a05257120f8a564e40826d20ace">unpackF64OnRV32DSoftABI</a>.</p>

</div>
</div>

### isPendingLoc() {#a193a46550761f868004d800dd2a535d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CCValAssign::isPendingLoc ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a26c8cba96e72f333e829e607938ce893">llvm::CCState::resultsCompatible</a>.</p>

</div>
</div>

### isRegLoc() {#a07dddcff2886a2b840f993f7ce17dd28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CCValAssign::isRegLoc ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a2d9bff6057c95e354dbc28e4604517c0">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#ac2990fcd086ddeb552b46fe5d49c77de">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#aa35ca40243a91b75afd51c04ee241788">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a8037cdaaf593bc895700f71a95ee9bcc">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a5e731292c2474865560219c29069c6de">canUseSiblingCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a49816805ae1abf4f4a01546d06c413a5">getv64i1Argument</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9696c62f9eeb556df764837c92b560df">llvm::SITargetLowering::LowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#aa0dc943f955ef5657bcc9eb702f611fd">lowerCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4e7be374a3346400a32967d91108c3e">llvm::LoongArchTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#aece826681b1fdc9ec7c82f4a9152000f">llvm::LoongArchTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4ce28f633cfe7a89369965cd9792e8fb">llvm::SITargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a3a9a464956d7d22291e5a6a29d4266e5">llvm::SystemZTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a73a391aef4505ecba196737cabb18ca0">llvm::VETargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ae491d50e304bf7057a2f4dfbf1650e56">llvm::XtensaTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a97357df4054a9551eb9a07b609cea109">llvm::SparcTargetLowering::LowerReturn_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#aa76596666bd4af3c0104b7a8fd514db0">llvm::SparcTargetLowering::LowerReturn_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a44432ec9756a3ffcf9fcc04ad9dce2e9">Passv64i1ArgInRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a479378216af352a6202281eb9b5b202a">llvm::CallLowering::resultsCompatible</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a26c8cba96e72f333e829e607938ce893">llvm::CCState::resultsCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a4fe763745add3c357f272b8f41264d6a">unpack64</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae3c73a05257120f8a564e40826d20ace">unpackF64OnRV32DSoftABI</a>.</p>

</div>
</div>

### isUpperBitsInLoc() {#a337d96d4ea6bf079abd145d3c4e2cdec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CCValAssign::isUpperBitsInLoc ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>References <a href="#a2b78fd53da0b5df7bc4eacf7df556a45aeada2602a598f9b877f1b75ed7dd9e4a">AExtUpper</a>, <a href="#a2b78fd53da0b5df7bc4eacf7df556a45aec09697a16bc3cc461d29f0f551e63c0">SExtUpper</a> and <a href="#a2b78fd53da0b5df7bc4eacf7df556a45a17dad9007e52963b27d90b46bfab8cb5">ZExtUpper</a>.</p>

</div>
</div>

### needsCustom() {#a5378385666bd865565fcf8407fcc36f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CCValAssign::needsCustom ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a2d9bff6057c95e354dbc28e4604517c0">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#ac2990fcd086ddeb552b46fe5d49c77de">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2bc16e1191a3e8a096aae2f90f9b6677">convertLocVTToValVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59c8bc2723e6744d5618db1f430fc94a">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a73a391aef4505ecba196737cabb18ca0">llvm::VETargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a97357df4054a9551eb9a07b609cea109">llvm::SparcTargetLowering::LowerReturn_32</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#aa76596666bd4af3c0104b7a8fd514db0">llvm::SparcTargetLowering::LowerReturn_64</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Data {#a591c8c0b7bc2047746d1deefbd7e0c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::variant&lt;Register, int64_t, unsigned&gt; llvm::CCValAssign::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>

</div>
</div>

### HTP {#a1c0fd25111229a6e277a6b3c39fa3b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocInfo llvm::CCValAssign::HTP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Information about how the value is assigned.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>

</div>
</div>

### isCustom {#ad40753249331379f858d0f5f0224b6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CCValAssign::isCustom</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isCustom - True if this arg/retval requires special handling.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>

</div>
</div>

### LocVT {#aef3122ed4728d0d91840bec3c30cf42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::CCValAssign::LocVT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LocVT - The type of the location being assigned to.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>

</div>
</div>

### ValNo {#a5f7884cb1bc607a222d86ff2057aba62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CCValAssign::ValNo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ValNo - This is the value number being assigned (e.g. an argument number).</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>

</div>
</div>

### ValVT {#a22e3c9088096f6665d4f445c72ada869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::CCValAssign::ValVT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ValVT - The type of the value being assigned.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getCustomMem() {#ab3ca02e9c44d57c994cc5351c24f6223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCValAssign llvm::CCValAssign::getCustomMem (unsigned ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="#a2b78fd53da0b5df7bc4eacf7df556a45">LocInfo</a> HTP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>References <a href="#a36d9dd26dea75ebba5b55516b52e0752">getMem</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a0818113ef1e2baa976b60a563c589126">CC_Sparc_Assign_Split_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aef49509c46de9de5e5af60e6f24f913a">CC_Sparc_Assign_SRet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a53416f63e4299aa1c62d190b2b6cf663">llvm::CC_XPLINK64_Allocate128BitVararg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a68b101df4798d06a20096c78748efeb2">f64AssignAAPCS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#ac0bff44982ab88d486466e16c975d0b0">f64AssignAPCS</a>.</p>

</div>
</div>

### getCustomReg() {#a3213a94802bb4f87a3e388af6cdd9d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCValAssign llvm::CCValAssign::getCustomReg (unsigned ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="#a2b78fd53da0b5df7bc4eacf7df556a45">LocInfo</a> HTP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>References <a href="#a29708e79e029f1029d46d65e7631b778">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aefa9d9e14f365171f98e0a86d34c3c08">Analyze_CC_Sparc64_Half</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a169d373fe5dc70c88b2a47ff825e3203">CC_MipsO32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp/#aa881d2e727e6a14013435af6691a598e">CC_PPC32_SPE_CustomSplitFP64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp/#a7a5fa20ecc7b5d7b962f4591ed563c17">CC_PPC32_SPE_RetF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8276b8e4ba01bd306af7ad5f001e2806">llvm::CC_RISCV_FastCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a02b9ad5a7bd4edc9897926a8d1967db7">CC_Sparc_Assign_Ret_Split_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a0818113ef1e2baa976b60a563c589126">CC_Sparc_Assign_Split_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a4634e79ad97015aa93f2379f619cc6ae">CC_X86_32_RegCall_Assign2Regs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#aec2fa7c07d3f8428a21ab34269b90456">CustomAssignInRegList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a68b101df4798d06a20096c78748efeb2">f64AssignAAPCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#ac0bff44982ab88d486466e16c975d0b0">f64AssignAPCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a1fac48a8f131620a4eca64a2811befe9">f64RetAssign</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a4046c9ff3e500fb323f37cf298adc970">fixupVariableFloatArgs</a>.</p>

</div>
</div>

### getMem() {#a36d9dd26dea75ebba5b55516b52e0752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCValAssign llvm::CCValAssign::getMem (unsigned ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="#a2b78fd53da0b5df7bc4eacf7df556a45">LocInfo</a> HTP, bool IsCustom=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afe2ba453aa8039b2d52c9474d9f14bc0">Analyze_CC_Sparc64_Full</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aefa9d9e14f365171f98e0a86d34c3c08">Analyze_CC_Sparc64_Half</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8423e53bcc9782e23a4e48e8ef88d150">llvm::analyzeArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae9fdb22bd3bd49303fbaf324c924f73c">llvm::CC_CSKY_ABIV2_SOFT_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiisellowering-cpp/#a75b985b7df04630b9f9184354b1b24bf">CC_Lanai32_VarArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a90abcb97861455132a9ca451c19405f0">CC_LoongArchAssign2GRLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a169d373fe5dc70c88b2a47ff825e3203">CC_MipsO32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8276b8e4ba01bd306af7ad5f001e2806">llvm::CC_RISCV_FastCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvcallingconv-cpp/#a10b000ebfe8f8018565e8180e73d3a7d">CC_RISCVAssign2XLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a7ee234a7eddb790513041e995ed66158">CC_X86_Intr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaisellowering-cpp/#a0da36c55dd342a918e3fdb66b919ebf4">CC_Xtensa_Custom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a4046c9ff3e500fb323f37cf298adc970">fixupVariableFloatArgs</a>, <a href="#ab3ca02e9c44d57c994cc5351c24f6223">getCustomMem</a> and <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a095917a8626bb95e378e4ccb653aac75">llvm::CCState::HandleByVal</a>.</p>

</div>
</div>

### getPending() {#a1022d05ab2d1337a97addf0ea4678fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCValAssign llvm::CCValAssign::getPending (unsigned ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="#a2b78fd53da0b5df7bc4eacf7df556a45">LocInfo</a> HTP, unsigned ExtraInfo=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#af3f5f44efd30903d2316ec3e8f20cda3">CC_AArch64_Custom_Stack_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3624679803f9a11d8362aca440f744a6">llvm::CC_SystemZ_I128Indirect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a41dd5c8db0f0898d613b138097515474">CC_X86_32_MCUInReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a61009b749b466b57d30ec5134bf613bb">CC_X86_64_I128</a>.</p>

</div>
</div>

### getReg() {#a29708e79e029f1029d46d65e7631b778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCValAssign llvm::CCValAssign::getReg (unsigned ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="#a2b78fd53da0b5df7bc4eacf7df556a45">LocInfo</a> HTP, bool IsCustom=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afe2ba453aa8039b2d52c9474d9f14bc0">Analyze_CC_Sparc64_Full</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aefa9d9e14f365171f98e0a86d34c3c08">Analyze_CC_Sparc64_Half</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430isellowering-cpp/#ad996415c84f27a48afd2fd7dc653efea">AnalyzeArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8423e53bcc9782e23a4e48e8ef88d150">llvm::analyzeArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08acbbba5edd5a9d4090220358bc9305">llvm::analyzeReturnValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae9fdb22bd3bd49303fbaf324c924f73c">llvm::CC_CSKY_ABIV2_SOFT_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7c58eb7c6cf6b55da864fe749fea62ad">CC_LoongArch_GHC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a90abcb97861455132a9ca451c19405f0">CC_LoongArchAssign2GRLen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab15d7687532864492d61498a0f24f98d">llvm::CC_M68k_Any_AssignToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a169d373fe5dc70c88b2a47ff825e3203">CC_MipsO32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8276b8e4ba01bd306af7ad5f001e2806">llvm::CC_RISCV_FastCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a04866da4b47769738d66f9d25fcf7304">llvm::CC_RISCV_GHC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvcallingconv-cpp/#a10b000ebfe8f8018565e8180e73d3a7d">CC_RISCVAssign2XLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a41dd5c8db0f0898d613b138097515474">CC_X86_32_MCUInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#af8687e6a4188d6843aebb24bf2944804">CC_X86_32_VectorCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#aaa1494436b6de4729389856e59276c98">CC_X86_64_VectorCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a14a88401fe6f00ed3b943fa7f0132d46">CC_X86_VectorCallAssignRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a53416f63e4299aa1c62d190b2b6cf663">llvm::CC_XPLINK64_Allocate128BitVararg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaisellowering-cpp/#a0da36c55dd342a918e3fdb66b919ebf4">CC_Xtensa_Custom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a4046c9ff3e500fb323f37cf298adc970">fixupVariableFloatArgs</a>, <a href="#a3213a94802bb4f87a3e388af6cdd9d7f">getCustomReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a25c7ccd93e74006df24fd1392e07014f">llvm::Ret_CSKY_ABIV2_SOFT_64</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">CallingConvLower.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
