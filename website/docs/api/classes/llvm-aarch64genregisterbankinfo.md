---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64genregisterbankinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64GenRegisterBankInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AArch64GenRegisterBankInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">Target/AArch64/GISel/AArch64RegisterBankInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo">AArch64RegisterBankInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class provides the information for the target register banks. <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">PartialMappingIdx { <a href="#a0ce0a1e8370bfd2d2f95eec99db57bd9">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ValueMappingIdx { <a href="#a5bc25a8a7793e62e97276637b1f5bfca">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0544412676b94227fa1cbd691372dab">checkPartialMap</a> (unsigned Idx, unsigned ValStartIdx, unsigned ValLength, const RegisterBank &amp;RB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac204e7094869818cf50f235726a351a">checkValueMapImpl</a> (unsigned Idx, unsigned FirstInBank, unsigned Size, unsigned Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5815052cc039d0e029b6aebf81614419">checkPartialMappingIdx</a> (PartialMappingIdx FirstAlias, PartialMappingIdx LastAlias, ArrayRef&lt; PartialMappingIdx &gt; Order)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce9fd2addf2bda8320f018848e938fa">getRegBankBaseIdxOffset</a> (unsigned RBIdx, TypeSize Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6c7f8d7dc748c8c3e5e4d3e230c71c">getValueMapping</a> (PartialMappingIdx RBIdx, TypeSize Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the pointer to the <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> representing the <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> at <span class="doxyComputerOutput">RBIdx</span> with a size of <span class="doxyComputerOutput">Size</span>. <a href="#ace6c7f8d7dc748c8c3e5e4d3e230c71c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52505890f7e825cd589db0e54395e9e5">getCopyMapping</a> (unsigned DstBankID, unsigned SrcBankID, TypeSize Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the pointer to the <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> of the operands of a copy instruction from the <span class="doxyComputerOutput">SrcBankID</span> register bank to the <span class="doxyComputerOutput">DstBankID</span> register bank with a size of <span class="doxyComputerOutput">Size</span>. <a href="#a52505890f7e825cd589db0e54395e9e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2c869b663eb82158eb929290dd29f67">getFPExtMapping</a> (unsigned DstSize, unsigned SrcSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the instruction mapping for G_FPEXT. <a href="#aa2c869b663eb82158eb929290dd29f67">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bccd695609f957457acb1eaa984045c">PartMappings</a>[]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ba357b7ffb47400eba332bcc7a3653">ValMappings</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0ce0a1e8370bfd2d2f95eec99db57bd9">PartialMappingIdx</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3aec3ca7a88b8d7f64d310d12444ac8">BankIDToCopyMapIdx</a>[]</td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### PartialMappingIdx {#a0ce0a1e8370bfd2d2f95eec99db57bd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64GenRegisterBankInfo::PartialMappingIdx </td>
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
<td class="doxyEnumItemName">PMI_None<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9ada6aa4fc496e081101afcb7ca2c8a373"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FPR16<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a7d0f4c1015d1380e8813dd5b6a07d5be"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FPR32<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a57ade2e8c7009c5b3daa35e6373c2dea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FPR64<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a0b8bca96f9b583cbfaf7448edc60ef89"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FPR128<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a74b3fe0416b1909c5f09e250e80e4443"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FPR256<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a9a036a733dc1c145a8f3607b799b87d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FPR512<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9aebf52e13aa4d38c631d9e5376578b4b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_GPR32<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a3affacb0ea6b477fc5b6a5331ae1a0dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_GPR64<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a15443bb0e40040577432ba71db504125"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_GPR128<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a5046c1b33042e6e139dfe42d4c2a836d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FirstGPR<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a6f05aa805febfc871072ccfaeab73947"></a></td>
<td class="doxyEnumItemDescription"> (= PMI_GPR32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_LastGPR<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9abd8d169cb7433122c1b4bfbbbe835b9a"></a></td>
<td class="doxyEnumItemDescription"> (= PMI_GPR128)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_FirstFPR<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9a5204b837734b0428ff3bc7d07c5620ad"></a></td>
<td class="doxyEnumItemDescription"> (= PMI_FPR16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_LastFPR<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9af741e39026b897179f21ab69f6fd83ea"></a></td>
<td class="doxyEnumItemDescription"> (= PMI_FPR512)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PMI_Min<a id="a0ce0a1e8370bfd2d2f95eec99db57bd9ab2879f12d4bf51793e9c64d53a977f81"></a></td>
<td class="doxyEnumItemDescription"> (= PMI_FirstFPR)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>

</div>
</div>

### ValueMappingIdx {#a5bc25a8a7793e62e97276637b1f5bfca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64GenRegisterBankInfo::ValueMappingIdx </td>
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
<td class="doxyEnumItemName">InvalidIdx<a id="a5bc25a8a7793e62e97276637b1f5bfcaa730a5843a9f6efa5bd572374a57001cc"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">First3OpsIdx<a id="a5bc25a8a7793e62e97276637b1f5bfcaa8dc019b27373bae43af2ea9402f70486"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Last3OpsIdx<a id="a5bc25a8a7793e62e97276637b1f5bfcaac5a293b56b4e91c760d23bd621e2cb9d"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DistanceBetweenRegBanks<a id="a5bc25a8a7793e62e97276637b1f5bfcaa85dded0bdbea67517ba33cda7c543cae"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstCrossRegCpyIdx<a id="a5bc25a8a7793e62e97276637b1f5bfcaa1e6d3663df1f326b330a5bf5ad63a640"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastCrossRegCpyIdx<a id="a5bc25a8a7793e62e97276637b1f5bfcaa9e6eb3f047f47123c78aa2da9829c107"></a></td>
<td class="doxyEnumItemDescription"> (= 42)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DistanceBetweenCrossRegCpy<a id="a5bc25a8a7793e62e97276637b1f5bfcaa4c2ea860c72e3eb2037d12b654f6e301"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPExt16To32Idx<a id="a5bc25a8a7793e62e97276637b1f5bfcaa1e2ee27e61922a5f8d4586b97788c4a3"></a></td>
<td class="doxyEnumItemDescription"> (= 44)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPExt16To64Idx<a id="a5bc25a8a7793e62e97276637b1f5bfcaa29ec7d849b5818663330722608967570"></a></td>
<td class="doxyEnumItemDescription"> (= 46)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPExt32To64Idx<a id="a5bc25a8a7793e62e97276637b1f5bfcaa66634e722b92b1635f9c14aa89003e57"></a></td>
<td class="doxyEnumItemDescription"> (= 48)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPExt64To128Idx<a id="a5bc25a8a7793e62e97276637b1f5bfcaa9b4ebe30fd1f79ea25dc4309a2cae068"></a></td>
<td class="doxyEnumItemDescription"> (= 50)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Shift64Imm<a id="a5bc25a8a7793e62e97276637b1f5bfcaaa633b88dcc41c33fb9989f39237c1b8a"></a></td>
<td class="doxyEnumItemDescription"> (= 52)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### checkPartialMap() {#ae0544412676b94227fa1cbd691372dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64GenRegisterBankInfo::checkPartialMap (unsigned Idx, unsigned ValStartIdx, unsigned ValLength, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; RB)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>

</div>
</div>

### checkPartialMappingIdx() {#a5815052cc039d0e029b6aebf81614419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64GenRegisterBankInfo::checkPartialMappingIdx (<a href="#a0ce0a1e8370bfd2d2f95eec99db57bd9">PartialMappingIdx</a> FirstAlias, <a href="#a0ce0a1e8370bfd2d2f95eec99db57bd9">PartialMappingIdx</a> LastAlias, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#a0ce0a1e8370bfd2d2f95eec99db57bd9">PartialMappingIdx</a> &gt; Order)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a8c46e5a35a9df5b131a85976d8d70af0">llvm::AArch64RegisterBankInfo::AArch64RegisterBankInfo</a>.</p>

</div>
</div>

### checkValueMapImpl() {#aac204e7094869818cf50f235726a351a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64GenRegisterBankInfo::checkValueMapImpl (unsigned Idx, unsigned FirstInBank, unsigned Size, unsigned Offset)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getCopyMapping() {#a52505890f7e825cd589db0e54395e9e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping * llvm::AArch64GenRegisterBankInfo::getCopyMapping (unsigned DstBankID, unsigned SrcBankID, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Size)</td>
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

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a3f4bf9736903f31820c978bdb1b6810f">llvm::AArch64RegisterBankInfo::getInstrAlternativeMappings</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

### getFPExtMapping() {#aa2c869b663eb82158eb929290dd29f67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping * llvm::AArch64GenRegisterBankInfo::getFPExtMapping (unsigned DstSize, unsigned SrcSize)</td>
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

<p>Get the instruction mapping for G_FPEXT.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>(DstSize, SrcSize) pair is one of the following: (32, 16), (64, 16), (64, 32), (128, 64)</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> with statically allocated OperandsMapping.</p></dd>
</dl>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

### getRegBankBaseIdxOffset() {#a0ce9fd2addf2bda8320f018848e938fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64GenRegisterBankInfo::getRegBankBaseIdxOffset (unsigned RBIdx, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Size)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getValueMapping() {#ace6c7f8d7dc748c8c3e5e4d3e230c71c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping * llvm::AArch64GenRegisterBankInfo::getValueMapping (<a href="#a0ce0a1e8370bfd2d2f95eec99db57bd9">PartialMappingIdx</a> RBIdx, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Size)</td>
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

<p>Get the pointer to the <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> representing the <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> at <span class="doxyComputerOutput">RBIdx</span> with a size of <span class="doxyComputerOutput">Size</span>.</p>


<p>The returned mapping works for instructions with the same kind of operands for up to 3 operands.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">RBIdx</span> != PartialMappingIdx::None</p></dd>
</dl>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a3f4bf9736903f31820c978bdb1b6810f">llvm::AArch64RegisterBankInfo::getInstrAlternativeMappings</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### BankIDToCopyMapIdx {#ac3aec3ca7a88b8d7f64d310d12444ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PartialMappingIdx llvm::AArch64GenRegisterBankInfo::BankIDToCopyMapIdx[]</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>

</div>
</div>

### PartMappings {#a7bccd695609f957457acb1eaa984045c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::PartialMapping llvm::AArch64GenRegisterBankInfo::PartMappings[]</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

### ValMappings {#ad8ba357b7ffb47400eba332bcc7a3653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping llvm::AArch64GenRegisterBankInfo::ValMappings[]</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">AArch64RegisterBankInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
