---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/mtbufformat
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `MTBUFFormat` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::MTBUFFormat { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DataFormat : int64_t { <a href="#a1639288a4e781b242be214c44eb42c4c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">NumFormat : int64_t { <a href="#a5d70ded8d54418ba62fd42d38c15ad5f">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">MergedFormat : int64_t { <a href="#aaf9125002211d7393035edc3d1e206ee">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">UnifiedFormatCommon : int64_t { <a href="#ad3114b80fe75fc1d13fb0d768704c8a5">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace425756e45dc13fdd4ee49616cbe202">getDfmt</a> (const StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8578e709d958ea749140a3b350137805">getDfmtName</a> (unsigned Id)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cebbe727625d409e207067ec351cc94">getNfmtLookupTable</a> (const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4ceeee60ddf9662daddba7a110cd607">getNfmt</a> (const StringRef Name, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadbb33a5e7684bfcb11a794b6baca824">getNfmtName</a> (unsigned Id, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74cb545dd808a8d80b3cddf27234fe5c">isValidDfmtNfmt</a> (unsigned Id, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ee42390df5ca4d0d3997dec2087c787">isValidNfmt</a> (unsigned Id, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88658310897a5ba8565bf1366213a307">encodeDfmtNfmt</a> (unsigned Dfmt, unsigned Nfmt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9954d5857cbb4abc0e38c222b5ef43d">decodeDfmtNfmt</a> (unsigned Format, unsigned &amp;Dfmt, unsigned &amp;Nfmt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa145eb4bbc534a2bae0b03059fad51b7">getUnifiedFormat</a> (const StringRef Name, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d81fc5bb6d434e310f66ff2abbfc5bc">getUnifiedFormatName</a> (unsigned Id, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f353aad546880174de1b50609b0d18">isValidUnifiedFormat</a> (unsigned Id, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81576381721fb9bbda2d0dbf37866dd6">convertDfmtNfmt2Ufmt</a> (unsigned Dfmt, unsigned Nfmt, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa71ec16c7a2bb6aaeb19ca20d7cb7442">isValidFormatEncoding</a> (unsigned Val, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2521888c0029b6776056a5b8d18ec449">getDefaultFormatEncoding</a> (const MCSubtargetInfo &amp;STI)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418b03b9f5c5591964bc1fa703b7334b">DfmtSymbolic</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c3f1e747dddef88bd0f7d989695e84c">NfmtSymbolicGFX10</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5b6eed2c392be5e4d5bc3c230ba8372">NfmtSymbolicSICI</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab36464ce766421e7bad5e73cc8804360">NfmtSymbolicVI</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed62db6f0ed22dd90cb75cdd5ab51d65">UfmtSymbolicGFX10</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4892a22b4e826782b7ff57addab9ae">DfmtNfmt2UFmtGFX10</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dadca5e0872bce302f8a6ffc7e7b9b2">UfmtSymbolicGFX11</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab297f6499eff6e71d9391aa2f902ab4f">DfmtNfmt2UFmtGFX11</a>[]</td>
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


<div class="doxySectionDef">

## Enumerations

### DataFormat {#a1639288a4e781b242be214c44eb42c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::MTBUFFormat::DataFormat : int64_t</td>
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
<td class="doxyEnumItemName">DFMT_INVALID<a id="a1639288a4e781b242be214c44eb42c4ca6a63f8d666f7cf73eaea8ff0c805c191"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_8<a id="a1639288a4e781b242be214c44eb42c4ca2c93f1a7b6b4d80081af38baaf4f8cac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_16<a id="a1639288a4e781b242be214c44eb42c4cad0ada97e6d313df407f6179bf0a1793b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_8_8<a id="a1639288a4e781b242be214c44eb42c4ca9d342b3b9f73e764c4668a34b3bfa6dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_32<a id="a1639288a4e781b242be214c44eb42c4cadc732698f7e8e73d57d495dd7b0bfbfc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_16_16<a id="a1639288a4e781b242be214c44eb42c4ca611637c7cf7723d539ee2c930f3058e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_10_11_11<a id="a1639288a4e781b242be214c44eb42c4ca43657e8dd963d5f30fdb705f514cd487"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_11_11_10<a id="a1639288a4e781b242be214c44eb42c4cad74b1bf41ff5fc41a73e4d338959adfa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_10_10_10_2<a id="a1639288a4e781b242be214c44eb42c4caa61a1d80aeea2d0d4ffaaba81f679a85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_2_10_10_10<a id="a1639288a4e781b242be214c44eb42c4ca9d8f16d03faf4de33a7b1468e8375de6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_8_8_8_8<a id="a1639288a4e781b242be214c44eb42c4cab800b47a0d3aae2117fbb23d6a085004"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_32_32<a id="a1639288a4e781b242be214c44eb42c4cae7e6636e67b31430cfc632c693c8b8bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_16_16_16_16<a id="a1639288a4e781b242be214c44eb42c4ca499dd9f42f5f67dc29483764a2743fa7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_32_32_32<a id="a1639288a4e781b242be214c44eb42c4ca93aedce07f8987d18e44d461c71c95f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_32_32_32_32<a id="a1639288a4e781b242be214c44eb42c4ca15ddbecbfce45b82fd44a821c1e03a76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_RESERVED_15<a id="a1639288a4e781b242be214c44eb42c4cab1c446e1a9af0c11d9110b9012d40f42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_MIN<a id="a1639288a4e781b242be214c44eb42c4ca474d0c2c4819611b684c81005262bf8c"></a></td>
<td class="doxyEnumItemDescription"> (= DFMT_INVALID)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_MAX<a id="a1639288a4e781b242be214c44eb42c4cac45aafc770d4681d282f7beb40d4ad03"></a></td>
<td class="doxyEnumItemDescription"> (= DFMT_RESERVED_15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_UNDEF<a id="a1639288a4e781b242be214c44eb42c4ca6523540e869e65331060df57c9add409"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_DEFAULT<a id="a1639288a4e781b242be214c44eb42c4ca8b7ccf769433236212a15d3076881aa7"></a></td>
<td class="doxyEnumItemDescription"> (= DFMT_8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_SHIFT<a id="a1639288a4e781b242be214c44eb42c4caecc9c6131a21ff4ca83e2a99ba39e45e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_MASK<a id="a1639288a4e781b242be214c44eb42c4cab0f0bf3cb3cf2aac66c9d2574bbb38d0"></a></td>
<td class="doxyEnumItemDescription"> (= 0xF)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### MergedFormat {#aaf9125002211d7393035edc3d1e206ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::MTBUFFormat::MergedFormat : int64_t</td>
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
<td class="doxyEnumItemName">DFMT_NFMT_UNDEF<a id="aaf9125002211d7393035edc3d1e206eea90b9b77db8bea1154fca6cb0b4e80f26"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_NFMT_DEFAULT<a id="aaf9125002211d7393035edc3d1e206eea3b0b4a9c3db2e3d1f4c63833a4050b87"></a></td>
<td class="doxyEnumItemDescription">
 (= ((DFMT_DEFAULT &amp; DFMT_MASK) &lt;&lt; DFMT_SHIFT) |
                      ((NFMT_DEFAULT &amp; NFMT_MASK) &lt;&lt; NFMT_SHIFT))
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_NFMT_MASK<a id="aaf9125002211d7393035edc3d1e206eea0b6462bb0ded7560486337c847642aab"></a></td>
<td class="doxyEnumItemDescription"> (= (DFMT_MASK &lt;&lt; DFMT_SHIFT) | (NFMT_MASK &lt;&lt; NFMT_SHIFT))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFMT_NFMT_MAX<a id="aaf9125002211d7393035edc3d1e206eeaa94afe5df355c40e0044cd4269e8ea11"></a></td>
<td class="doxyEnumItemDescription"> (= DFMT_NFMT_MASK)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### NumFormat {#a5d70ded8d54418ba62fd42d38c15ad5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::MTBUFFormat::NumFormat : int64_t</td>
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
<td class="doxyEnumItemName">NFMT_UNORM<a id="a5d70ded8d54418ba62fd42d38c15ad5fa9a0be502f1820e758740cda3993bfb08"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_SNORM<a id="a5d70ded8d54418ba62fd42d38c15ad5fac63fe3cdbe36fc1f21fae68d356d79d0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_USCALED<a id="a5d70ded8d54418ba62fd42d38c15ad5fab944396f6d9c8c2cfb4f27fd768a41b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_SSCALED<a id="a5d70ded8d54418ba62fd42d38c15ad5fae1ebd5e6ed969249e914e5ae5a9e0163"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_UINT<a id="a5d70ded8d54418ba62fd42d38c15ad5fa14e9b7fa6f0a86d741fc33a9ec1a603c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_SINT<a id="a5d70ded8d54418ba62fd42d38c15ad5fa3d4865fafef04edd34bc57f99909c804"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_RESERVED_6<a id="a5d70ded8d54418ba62fd42d38c15ad5fa3401385fbc3b8ee2105fec11e8bbaf20"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_SNORM_OGL<a id="a5d70ded8d54418ba62fd42d38c15ad5fa70ec4f71b717c397e8c9097668ab11b1"></a></td>
<td class="doxyEnumItemDescription"> (= NFMT_RESERVED_6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_FLOAT<a id="a5d70ded8d54418ba62fd42d38c15ad5fadcf9578e9419f4694555752b038dc9a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_MIN<a id="a5d70ded8d54418ba62fd42d38c15ad5fab708868c6257f96763180aff334c9cae"></a></td>
<td class="doxyEnumItemDescription"> (= NFMT_UNORM)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_MAX<a id="a5d70ded8d54418ba62fd42d38c15ad5fa666d8c0c7a439fa8b46a5b6f43214466"></a></td>
<td class="doxyEnumItemDescription"> (= NFMT_FLOAT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_UNDEF<a id="a5d70ded8d54418ba62fd42d38c15ad5fa236bdeff44903627faf337bd91ca344e"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_DEFAULT<a id="a5d70ded8d54418ba62fd42d38c15ad5fa3861fe2916797a81c4ed930d3b12653a"></a></td>
<td class="doxyEnumItemDescription"> (= NFMT_UNORM)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_SHIFT<a id="a5d70ded8d54418ba62fd42d38c15ad5fa40fc04b2a83e6656691a189c85e95ca7"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NFMT_MASK<a id="a5d70ded8d54418ba62fd42d38c15ad5fa65e1d2bd51e7a5d4e9be81ba0c9c32bf"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### UnifiedFormatCommon {#ad3114b80fe75fc1d13fb0d768704c8a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::MTBUFFormat::UnifiedFormatCommon : int64_t</td>
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
<td class="doxyEnumItemName">UFMT_MAX<a id="ad3114b80fe75fc1d13fb0d768704c8a5ab3a1cd28cc7e61cd410a53a20af20625"></a></td>
<td class="doxyEnumItemDescription"> (= 127)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UFMT_UNDEF<a id="ad3114b80fe75fc1d13fb0d768704c8a5a0dd1e270e143e4f1f45ee074260863d4"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UFMT_DEFAULT<a id="ad3114b80fe75fc1d13fb0d768704c8a5a553b6d26e6df5d1dc67fc7c027048228"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### convertDfmtNfmt2Ufmt() {#a81576381721fb9bbda2d0dbf37866dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AMDGPU::MTBUFFormat::convertDfmtNfmt2Ufmt (unsigned Dfmt, unsigned Nfmt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a2e4892a22b4e826782b7ff57addab9ae">DfmtNfmt2UFmtGFX10</a>, <a href="#ab297f6499eff6e71d9391aa2f902ab4f">DfmtNfmt2UFmtGFX11</a>, <a href="#a88658310897a5ba8565bf1366213a307">encodeDfmtNfmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx10/#a9f4b9c2257280532185aa363f023fbf5ae94eac08f0faacbe0eca769bccac6f22">llvm::AMDGPU::UfmtGFX10::UFMT_FIRST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx11/#a5cb0b88974a1601339c538367073d209a649cf362018d9f7ab9c27a4e790a65c7">llvm::AMDGPU::UfmtGFX11::UFMT_FIRST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx10/#a9f4b9c2257280532185aa363f023fbf5a9b82ab88423d8bad150a65304e811c88">llvm::AMDGPU::UfmtGFX10::UFMT_LAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx11/#a5cb0b88974a1601339c538367073d209a70c2438cff9f12a18b31c6069702d0f0">llvm::AMDGPU::UfmtGFX11::UFMT_LAST</a> and <a href="#ad3114b80fe75fc1d13fb0d768704c8a5a0dd1e270e143e4f1f45ee074260863d4">UFMT_UNDEF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ad0ddd35516c856b2c41317d0c1febdea">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicSplitFormat</a>.</p>

</div>
</div>

### decodeDfmtNfmt() {#af9954d5857cbb4abc0e38c222b5ef43d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPU::MTBUFFormat::decodeDfmtNfmt (unsigned Format, unsigned &amp; Dfmt, unsigned &amp; Nfmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a1639288a4e781b242be214c44eb42c4cab0f0bf3cb3cf2aac66c9d2574bbb38d0">DFMT_MASK</a>, <a href="#a1639288a4e781b242be214c44eb42c4caecc9c6131a21ff4ca83e2a99ba39e45e">DFMT_SHIFT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>, <a href="#a5d70ded8d54418ba62fd42d38c15ad5fa65e1d2bd51e7a5d4e9be81ba0c9c32bf">NFMT_MASK</a> and <a href="#a5d70ded8d54418ba62fd42d38c15ad5fa40fc04b2a83e6656691a189c85e95ca7">NFMT_SHIFT</a>.</p>


<p>Referenced by <a href="#a74cb545dd808a8d80b3cddf27234fe5c">isValidDfmtNfmt</a>.</p>

</div>
</div>

### encodeDfmtNfmt() {#a88658310897a5ba8565bf1366213a307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READNONE int64_t llvm::AMDGPU::MTBUFFormat::encodeDfmtNfmt (unsigned Dfmt, unsigned Nfmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1875 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a1639288a4e781b242be214c44eb42c4caecc9c6131a21ff4ca83e2a99ba39e45e">DFMT_SHIFT</a> and <a href="#a5d70ded8d54418ba62fd42d38c15ad5fa40fc04b2a83e6656691a189c85e95ca7">NFMT_SHIFT</a>.</p>


<p>Referenced by <a href="#a81576381721fb9bbda2d0dbf37866dd6">convertDfmtNfmt2Ufmt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a157290e9f9aa7ff61c53d131b090e50a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDfmtNfmt</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ad0ddd35516c856b2c41317d0c1febdea">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicSplitFormat</a>.</p>

</div>
</div>

### getDefaultFormatEncoding() {#a2521888c0029b6776056a5b8d18ec449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::MTBUFFormat::getDefaultFormatEncoding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1930 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#aaf9125002211d7393035edc3d1e206eea3b0b4a9c3db2e3d1f4c63833a4050b87">DFMT_NFMT_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a> and <a href="#ad3114b80fe75fc1d13fb0d768704c8a5a553b6d26e6df5d1dc67fc7c027048228">UFMT_DEFAULT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aae18974f031b21f7dd37b072a1cbe24d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseFORMAT</a>.</p>

</div>
</div>

### getDfmt() {#ace425756e45dc13fdd4ee49616cbe202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AMDGPU::MTBUFFormat::getDfmt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a1639288a4e781b242be214c44eb42c4cac45aafc770d4681d282f7beb40d4ad03">DFMT_MAX</a>, <a href="#a1639288a4e781b242be214c44eb42c4ca474d0c2c4819611b684c81005262bf8c">DFMT_MIN</a>, <a href="#a1639288a4e781b242be214c44eb42c4ca6523540e869e65331060df57c9add409">DFMT_UNDEF</a> and <a href="#a418b03b9f5c5591964bc1fa703b7334b">DfmtSymbolic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aea4cc2cee6a095dbbd1f35f80ad3c3e1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::matchDfmtNfmt</a>.</p>

</div>
</div>

### getDfmtName() {#a8578e709d958ea749140a3b350137805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AMDGPU::MTBUFFormat::getDfmtName (unsigned Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1639288a4e781b242be214c44eb42c4cac45aafc770d4681d282f7beb40d4ad03">DFMT_MAX</a> and <a href="#a418b03b9f5c5591964bc1fa703b7334b">DfmtSymbolic</a>.</p>

</div>
</div>

### getNfmt() {#ac4ceeee60ddf9662daddba7a110cd607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AMDGPU::MTBUFFormat::getNfmt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#a5cebbe727625d409e207067ec351cc94">getNfmtLookupTable</a>, <a href="#a5d70ded8d54418ba62fd42d38c15ad5fa666d8c0c7a439fa8b46a5b6f43214466">NFMT_MAX</a>, <a href="#a5d70ded8d54418ba62fd42d38c15ad5fab708868c6257f96763180aff334c9cae">NFMT_MIN</a> and <a href="#a5d70ded8d54418ba62fd42d38c15ad5fa236bdeff44903627faf337bd91ca344e">NFMT_UNDEF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aea4cc2cee6a095dbbd1f35f80ad3c3e1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::matchDfmtNfmt</a>.</p>

</div>
</div>

### getNfmtLookupTable() {#a5cebbe727625d409e207067ec351cc94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral const  * llvm::AMDGPU::MTBUFFormat::getNfmtLookupTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 1842 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ade135e9169df98a7457505a0ea5b6179">llvm::AMDGPU::isCI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a626413fe751b97e13812bb7b635e6dd5">llvm::AMDGPU::isGFX9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a58f60f9ac04e27846a67a951d920837e">llvm::AMDGPU::isSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad198ccff657f64471c12cc36d9aa1969">llvm::AMDGPU::isVI</a>, <a href="#a6c3f1e747dddef88bd0f7d989695e84c">NfmtSymbolicGFX10</a>, <a href="#ab5b6eed2c392be5e4d5bc3c230ba8372">NfmtSymbolicSICI</a> and <a href="#ab36464ce766421e7bad5e73cc8804360">NfmtSymbolicVI</a>.</p>


<p>Referenced by <a href="#ac4ceeee60ddf9662daddba7a110cd607">getNfmt</a> and <a href="#aadbb33a5e7684bfcb11a794b6baca824">getNfmtName</a>.</p>

</div>
</div>

### getNfmtName() {#aadbb33a5e7684bfcb11a794b6baca824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AMDGPU::MTBUFFormat::getNfmtName (unsigned Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5cebbe727625d409e207067ec351cc94">getNfmtLookupTable</a> and <a href="#a5d70ded8d54418ba62fd42d38c15ad5fa666d8c0c7a439fa8b46a5b6f43214466">NFMT_MAX</a>.</p>


<p>Referenced by <a href="#a5ee42390df5ca4d0d3997dec2087c787">isValidNfmt</a>.</p>

</div>
</div>

### getUnifiedFormat() {#aa145eb4bbc534a2bae0b03059fad51b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AMDGPU::MTBUFFormat::getUnifiedFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1884 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx10/#a9f4b9c2257280532185aa363f023fbf5ae94eac08f0faacbe0eca769bccac6f22">llvm::AMDGPU::UfmtGFX10::UFMT_FIRST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx11/#a5cb0b88974a1601339c538367073d209a649cf362018d9f7ab9c27a4e790a65c7">llvm::AMDGPU::UfmtGFX11::UFMT_FIRST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx10/#a9f4b9c2257280532185aa363f023fbf5a9b82ab88423d8bad150a65304e811c88">llvm::AMDGPU::UfmtGFX10::UFMT_LAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx11/#a5cb0b88974a1601339c538367073d209a70c2438cff9f12a18b31c6069702d0f0">llvm::AMDGPU::UfmtGFX11::UFMT_LAST</a>, <a href="#ad3114b80fe75fc1d13fb0d768704c8a5a0dd1e270e143e4f1f45ee074260863d4">UFMT_UNDEF</a>, <a href="#aed62db6f0ed22dd90cb75cdd5ab51d65">UfmtSymbolicGFX10</a> and <a href="#a0dadca5e0872bce302f8a6ffc7e7b9b2">UfmtSymbolicGFX11</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a9cba0b00a0bcffcb413914db33553071">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicUnifiedFormat</a>.</p>

</div>
</div>

### getUnifiedFormatName() {#a2d81fc5bb6d434e310f66ff2abbfc5bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AMDGPU::MTBUFFormat::getUnifiedFormatName (unsigned Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1899 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27e5626ce22d0cd09916837dc88b7efe">llvm::AMDGPU::isGFX10</a>, <a href="#a21f353aad546880174de1b50609b0d18">isValidUnifiedFormat</a>, <a href="#aed62db6f0ed22dd90cb75cdd5ab51d65">UfmtSymbolicGFX10</a> and <a href="#a0dadca5e0872bce302f8a6ffc7e7b9b2">UfmtSymbolicGFX11</a>.</p>

</div>
</div>

### isValidDfmtNfmt() {#a74cb545dd808a8d80b3cddf27234fe5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::MTBUFFormat::isValidDfmtNfmt (unsigned Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1864 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#af9954d5857cbb4abc0e38c222b5ef43d">decodeDfmtNfmt</a> and <a href="#a5ee42390df5ca4d0d3997dec2087c787">isValidNfmt</a>.</p>

</div>
</div>

### isValidFormatEncoding() {#aa71ec16c7a2bb6aaeb19ca20d7cb7442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::MTBUFFormat::isValidFormatEncoding (unsigned Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1926 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#aaf9125002211d7393035edc3d1e206eeaa94afe5df355c40e0044cd4269e8ea11">DFMT_NFMT_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a> and <a href="#ad3114b80fe75fc1d13fb0d768704c8a5ab3a1cd28cc7e61cd410a53a20af20625">UFMT_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ae93e542fa2b3eac118a87c97a47bc681">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseNumericFormat</a>.</p>

</div>
</div>

### isValidNfmt() {#a5ee42390df5ca4d0d3997dec2087c787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::MTBUFFormat::isValidNfmt (unsigned Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1871 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#aadbb33a5e7684bfcb11a794b6baca824">getNfmtName</a>.</p>


<p>Referenced by <a href="#a74cb545dd808a8d80b3cddf27234fe5c">isValidDfmtNfmt</a>.</p>

</div>
</div>

### isValidUnifiedFormat() {#a21f353aad546880174de1b50609b0d18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::MTBUFFormat::isValidUnifiedFormat (unsigned Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1905 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27e5626ce22d0cd09916837dc88b7efe">llvm::AMDGPU::isGFX10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx10/#a9f4b9c2257280532185aa363f023fbf5a9b82ab88423d8bad150a65304e811c88">llvm::AMDGPU::UfmtGFX10::UFMT_LAST</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ufmtgfx11/#a5cb0b88974a1601339c538367073d209a70c2438cff9f12a18b31c6069702d0f0">llvm::AMDGPU::UfmtGFX11::UFMT_LAST</a>.</p>


<p>Referenced by <a href="#a2d81fc5bb6d434e310f66ff2abbfc5bc">getUnifiedFormatName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DfmtNfmt2UFmtGFX10 {#a2e4892a22b4e826782b7ff57addab9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned const llvm::AMDGPU::MTBUFFormat::DfmtNfmt2UFmtGFX10</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a81576381721fb9bbda2d0dbf37866dd6">convertDfmtNfmt2Ufmt</a>.</p>

</div>
</div>

### DfmtNfmt2UFmtGFX11 {#ab297f6499eff6e71d9391aa2f902ab4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned const llvm::AMDGPU::MTBUFFormat::DfmtNfmt2UFmtGFX11</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a81576381721fb9bbda2d0dbf37866dd6">convertDfmtNfmt2Ufmt</a>.</p>

</div>
</div>

### DfmtSymbolic {#a418b03b9f5c5591964bc1fa703b7334b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral const llvm::AMDGPU::MTBUFFormat::DfmtSymbolic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "BUF_DATA_FORMAT_INVALID",
  "BUF_DATA_FORMAT_8",
  "BUF_DATA_FORMAT_16",
  "BUF_DATA_FORMAT_8_8",
  "BUF_DATA_FORMAT_32",
  "BUF_DATA_FORMAT_16_16",
  "BUF_DATA_FORMAT_10_11_11",
  "BUF_DATA_FORMAT_11_11_10",
  "BUF_DATA_FORMAT_10_10_10_2",
  "BUF_DATA_FORMAT_2_10_10_10",
  "BUF_DATA_FORMAT_8_8_8_8",
  "BUF_DATA_FORMAT_32_32",
  "BUF_DATA_FORMAT_16_16_16_16",
  "BUF_DATA_FORMAT_32_32_32",
  "BUF_DATA_FORMAT_32_32_32_32",
  "BUF_DATA_FORMAT_RESERVED_15"
}
</div>
</dd>
</dl>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#ace425756e45dc13fdd4ee49616cbe202">getDfmt</a> and <a href="#a8578e709d958ea749140a3b350137805">getDfmtName</a>.</p>

</div>
</div>

### NfmtSymbolicGFX10 {#a6c3f1e747dddef88bd0f7d989695e84c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral const llvm::AMDGPU::MTBUFFormat::NfmtSymbolicGFX10</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "BUF_NUM_FORMAT_UNORM",
  "BUF_NUM_FORMAT_SNORM",
  "BUF_NUM_FORMAT_USCALED",
  "BUF_NUM_FORMAT_SSCALED",
  "BUF_NUM_FORMAT_UINT",
  "BUF_NUM_FORMAT_SINT",
  "",
  "BUF_NUM_FORMAT_FLOAT"
}
</div>
</dd>
</dl>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a5cebbe727625d409e207067ec351cc94">getNfmtLookupTable</a>.</p>

</div>
</div>

### NfmtSymbolicSICI {#ab5b6eed2c392be5e4d5bc3c230ba8372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral const llvm::AMDGPU::MTBUFFormat::NfmtSymbolicSICI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "BUF_NUM_FORMAT_UNORM",
  "BUF_NUM_FORMAT_SNORM",
  "BUF_NUM_FORMAT_USCALED",
  "BUF_NUM_FORMAT_SSCALED",
  "BUF_NUM_FORMAT_UINT",
  "BUF_NUM_FORMAT_SINT",
  "BUF_NUM_FORMAT_SNORM_OGL",
  "BUF_NUM_FORMAT_FLOAT"
}
</div>
</dd>
</dl>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a5cebbe727625d409e207067ec351cc94">getNfmtLookupTable</a>.</p>

</div>
</div>

### NfmtSymbolicVI {#ab36464ce766421e7bad5e73cc8804360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral const llvm::AMDGPU::MTBUFFormat::NfmtSymbolicVI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {    
  "BUF_NUM_FORMAT_UNORM",
  "BUF_NUM_FORMAT_SNORM",
  "BUF_NUM_FORMAT_USCALED",
  "BUF_NUM_FORMAT_SSCALED",
  "BUF_NUM_FORMAT_UINT",
  "BUF_NUM_FORMAT_SINT",
  "BUF_NUM_FORMAT_RESERVED_6",
  "BUF_NUM_FORMAT_FLOAT"
}
</div>
</dd>
</dl>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a5cebbe727625d409e207067ec351cc94">getNfmtLookupTable</a>.</p>

</div>
</div>

### UfmtSymbolicGFX10 {#aed62db6f0ed22dd90cb75cdd5ab51d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral const llvm::AMDGPU::MTBUFFormat::UfmtSymbolicGFX10</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#aa145eb4bbc534a2bae0b03059fad51b7">getUnifiedFormat</a> and <a href="#a2d81fc5bb6d434e310f66ff2abbfc5bc">getUnifiedFormatName</a>.</p>

</div>
</div>

### UfmtSymbolicGFX11 {#a0dadca5e0872bce302f8a6ffc7e7b9b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral const llvm::AMDGPU::MTBUFFormat::UfmtSymbolicGFX11</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#aa145eb4bbc534a2bae0b03059fad51b7">getUnifiedFormat</a> and <a href="#a2d81fc5bb6d434e310f66ff2abbfc5bc">getUnifiedFormatName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
