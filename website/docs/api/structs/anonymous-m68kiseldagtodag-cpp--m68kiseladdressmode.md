---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `M68kISelAddressMode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AddrType { <a href="#a5e9e0e3b0a0b531710a8e2a051628689">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Base { <a href="#a46832c7411abf3b50e7e2bd40062822d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a> (AddrType AT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56ea14b21ac540044695df370c5c7b3">hasSymbolicDisplacement</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7c9f7ef7708b3acb7366ca839f18692">hasBase</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07654fca498c35c61c05548864c02c60">hasFrameIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135ef521eb222263bd3737241f96833f">hasBaseReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af576c2ef3c0564ac151e250d7bb7278a">hasIndexReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386b44ca8fc5dfccb63c07481db2524d">isDispAddrType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if address mode type supports displacement. <a href="#a386b44ca8fc5dfccb63c07481db2524d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f340fdabbc82a71ef85e03b3f1dce0c">getDispSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f7711666903b4d53215521ef8f8c1b">hasDisp</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed17df504ffbd84b83d70b4197816b5d">isDisp8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a1addcc73b7e893977bd97659f6d65">isDisp16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22476867010bd7cf2ab2a7128d655e4c">isDisp32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f8c14f9f67ad3f335f6e7c9c760681">isPCRelative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this addressing mode is already PC-relative. <a href="#aa5f8c14f9f67ad3f335f6e7c9c760681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283c8af77b20674deb6df24f7fafb347">setBaseReg</a> (SDValue Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca9f5bb50cfc8ea5f55971ef36310e0">setIndexReg</a> (SDValue Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4c1e0a3ac33cb22a5eafffea1428607">dump</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5e9e0e3b0a0b531710a8e2a051628689">AddrType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab09373c3bf7cd36b8616eb9300f65e43">AM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a46832c7411abf3b50e7e2bd40062822d">Base</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87de11a1ed5994728311f322cea460f9">BaseType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a713ace664d7086a01098608505e38">Disp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9dd546ffbe61e1c49b482bbd603082f">BaseReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae92f7227ae0a66d7f87b3c4588917644">BaseFrameIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab672b5bc6a883d5bd4de354367953ed4">IndexReg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d857852763ad228adbe56c6e7c314f">Scale</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaff8ef5091bc7ab308691291c55aeefd">GV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066238ee75137639f8719f4b7cef127b">CP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa648f067fefe9157201c962b4efb9b6e">BlockAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0fcdce86a780f52c2b2ca9f25a9ef1">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5bacef4465a8d2c64e78eacb2af9f36">MCSym</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b3aeda2dbea611c7db1bb83d9d4c45">JT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac6867e20a1231adab9d495e529a6c33">Alignment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8be5fb0c0bef16eda24255c02d74a83">SymbolFlags</a></td>
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


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AddrType {#a5e9e0e3b0a0b531710a8e2a051628689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::AddrType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
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
<td class="doxyEnumItemName">ARI<a id="a5e9e0e3b0a0b531710a8e2a051628689aeab1547140d5b7d0e20cd6b9cc0ed629"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARIPI<a id="a5e9e0e3b0a0b531710a8e2a051628689a3d4586d59ab12469a3b6fadf172f63c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARIPD<a id="a5e9e0e3b0a0b531710a8e2a051628689ac4005f5aadcdd35298cd89687ee975c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARID<a id="a5e9e0e3b0a0b531710a8e2a051628689acb2b7bbb0e2f3f76538306e5fa548770"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARII<a id="a5e9e0e3b0a0b531710a8e2a051628689aeb997c63fcccc002599c61bab9b0c1cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCD<a id="a5e9e0e3b0a0b531710a8e2a051628689a64bd82be2f900e31c0c58b47fb919c28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCI<a id="a5e9e0e3b0a0b531710a8e2a051628689ac89b74e7544d782dd33c25fdaae40b8f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AL<a id="a5e9e0e3b0a0b531710a8e2a051628689ae892e780304dc3ef15e69b9f3fed3669"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### Base {#a46832c7411abf3b50e7e2bd40062822d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::Base </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
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
<td class="doxyEnumItemName">RegBase<a id="a46832c7411abf3b50e7e2bd40062822da77389e3a1193d2101c7ebd5bfa1853d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrameIndexBase<a id="a46832c7411abf3b50e7e2bd40062822dad1498855f473542b2722d7fddf92c2f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### M68kISelAddressMode() {#a5ca5283bb94f9ac5de4bc46092aa07e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::M68kISelAddressMode (<a href="#a5e9e0e3b0a0b531710a8e2a051628689">AddrType</a> AT)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#aac6867e20a1231adab9d495e529a6c33">Alignment</a>, <a href="#ab09373c3bf7cd36b8616eb9300f65e43">AM</a>, <a href="#ae92f7227ae0a66d7f87b3c4588917644">BaseFrameIndex</a>, <a href="#a87de11a1ed5994728311f322cea460f9">BaseType</a>, <a href="#aa648f067fefe9157201c962b4efb9b6e">BlockAddr</a>, <a href="#a066238ee75137639f8719f4b7cef127b">CP</a>, <a href="#ad0a713ace664d7086a01098608505e38">Disp</a>, <a href="#adc0fcdce86a780f52c2b2ca9f25a9ef1">ES</a>, <a href="#aaff8ef5091bc7ab308691291c55aeefd">GV</a>, <a href="#ab672b5bc6a883d5bd4de354367953ed4">IndexReg</a>, <a href="#aa7b3aeda2dbea611c7db1bb83d9d4c45">JT</a>, <a href="#aa5bacef4465a8d2c64e78eacb2af9f36">MCSym</a>, <a href="#a46832c7411abf3b50e7e2bd40062822da77389e3a1193d2101c7ebd5bfa1853d4">RegBase</a>, <a href="#a74d857852763ad228adbe56c6e7c314f">Scale</a> and <a href="#ab8be5fb0c0bef16eda24255c02d74a83">SymbolFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ac4c1e0a3ac33cb22a5eafffea1428607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::dump ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#ae92f7227ae0a66d7f87b3c4588917644">BaseFrameIndex</a>, <a href="#ab9dd546ffbe61e1c49b482bbd603082f">BaseReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ad0a713ace664d7086a01098608505e38">Disp</a>, <a href="#ab672b5bc6a883d5bd4de354367953ed4">IndexReg</a> and <a href="#a74d857852763ad228adbe56c6e7c314f">Scale</a>.</p>

</div>
</div>

### getDispSize() {#a9f340fdabbc82a71ef85e03b3f1dce0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::getDispSize ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a5e9e0e3b0a0b531710a8e2a051628689ae892e780304dc3ef15e69b9f3fed3669">AL</a>, <a href="#ab09373c3bf7cd36b8616eb9300f65e43">AM</a>, <a href="#a5e9e0e3b0a0b531710a8e2a051628689acb2b7bbb0e2f3f76538306e5fa548770">ARID</a>, <a href="#a5e9e0e3b0a0b531710a8e2a051628689aeb997c63fcccc002599c61bab9b0c1cc">ARII</a>, <a href="#a5e9e0e3b0a0b531710a8e2a051628689a64bd82be2f900e31c0c58b47fb919c28">PCD</a> and <a href="#a5e9e0e3b0a0b531710a8e2a051628689ac89b74e7544d782dd33c25fdaae40b8f">PCI</a>.</p>


<p>Referenced by <a href="#a29f7711666903b4d53215521ef8f8c1b">hasDisp</a>, <a href="#a06a1addcc73b7e893977bd97659f6d65">isDisp16</a>, <a href="#a22476867010bd7cf2ab2a7128d655e4c">isDisp32</a> and <a href="#aed17df504ffbd84b83d70b4197816b5d">isDisp8</a>.</p>

</div>
</div>

### hasBase() {#ae7c9f7ef7708b3acb7366ca839f18692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::hasBase ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#ab9dd546ffbe61e1c49b482bbd603082f">BaseReg</a>, <a href="#a87de11a1ed5994728311f322cea460f9">BaseType</a> and <a href="#a46832c7411abf3b50e7e2bd40062822dad1498855f473542b2722d7fddf92c2f7">FrameIndexBase</a>.</p>

</div>
</div>

### hasBaseReg() {#a135ef521eb222263bd3737241f96833f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::hasBaseReg ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#ab9dd546ffbe61e1c49b482bbd603082f">BaseReg</a>, <a href="#a87de11a1ed5994728311f322cea460f9">BaseType</a> and <a href="#a46832c7411abf3b50e7e2bd40062822da77389e3a1193d2101c7ebd5bfa1853d4">RegBase</a>.</p>

</div>
</div>

### hasDisp() {#a29f7711666903b4d53215521ef8f8c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::hasDisp ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="#a9f340fdabbc82a71ef85e03b3f1dce0c">getDispSize</a>.</p>

</div>
</div>

### hasFrameIndex() {#a07654fca498c35c61c05548864c02c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::hasFrameIndex ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a87de11a1ed5994728311f322cea460f9">BaseType</a> and <a href="#a46832c7411abf3b50e7e2bd40062822dad1498855f473542b2722d7fddf92c2f7">FrameIndexBase</a>.</p>

</div>
</div>

### hasIndexReg() {#af576c2ef3c0564ac151e250d7bb7278a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::hasIndexReg ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a87de11a1ed5994728311f322cea460f9">BaseType</a>, <a href="#ab672b5bc6a883d5bd4de354367953ed4">IndexReg</a> and <a href="#a46832c7411abf3b50e7e2bd40062822da77389e3a1193d2101c7ebd5bfa1853d4">RegBase</a>.</p>

</div>
</div>

### hasSymbolicDisplacement() {#ae56ea14b21ac540044695df370c5c7b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::hasSymbolicDisplacement ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#aa648f067fefe9157201c962b4efb9b6e">BlockAddr</a>, <a href="#a066238ee75137639f8719f4b7cef127b">CP</a>, <a href="#adc0fcdce86a780f52c2b2ca9f25a9ef1">ES</a>, <a href="#aaff8ef5091bc7ab308691291c55aeefd">GV</a>, <a href="#aa7b3aeda2dbea611c7db1bb83d9d4c45">JT</a> and <a href="#aa5bacef4465a8d2c64e78eacb2af9f36">MCSym</a>.</p>

</div>
</div>

### isDisp16() {#a06a1addcc73b7e893977bd97659f6d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::isDisp16 ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="#a9f340fdabbc82a71ef85e03b3f1dce0c">getDispSize</a>.</p>

</div>
</div>

### isDisp32() {#a22476867010bd7cf2ab2a7128d655e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::isDisp32 ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="#a9f340fdabbc82a71ef85e03b3f1dce0c">getDispSize</a>.</p>

</div>
</div>

### isDisp8() {#aed17df504ffbd84b83d70b4197816b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::isDisp8 ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="#a9f340fdabbc82a71ef85e03b3f1dce0c">getDispSize</a>.</p>

</div>
</div>

### isDispAddrType() {#a386b44ca8fc5dfccb63c07481db2524d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::isDispAddrType ()</td>
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

<p>True if address mode type supports displacement.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a5e9e0e3b0a0b531710a8e2a051628689ae892e780304dc3ef15e69b9f3fed3669">AL</a>, <a href="#ab09373c3bf7cd36b8616eb9300f65e43">AM</a>, <a href="#a5e9e0e3b0a0b531710a8e2a051628689acb2b7bbb0e2f3f76538306e5fa548770">ARID</a>, <a href="#a5e9e0e3b0a0b531710a8e2a051628689aeb997c63fcccc002599c61bab9b0c1cc">ARII</a>, <a href="#a5e9e0e3b0a0b531710a8e2a051628689a64bd82be2f900e31c0c58b47fb919c28">PCD</a> and <a href="#a5e9e0e3b0a0b531710a8e2a051628689ac89b74e7544d782dd33c25fdaae40b8f">PCI</a>.</p>

</div>
</div>

### isPCRelative() {#aa5f8c14f9f67ad3f335f6e7c9c760681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::isPCRelative ()</td>
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

<p>Return true if this addressing mode is already PC-relative.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#ab9dd546ffbe61e1c49b482bbd603082f">BaseReg</a>, <a href="#a87de11a1ed5994728311f322cea460f9">BaseType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a46832c7411abf3b50e7e2bd40062822da77389e3a1193d2101c7ebd5bfa1853d4">RegBase</a>.</p>

</div>
</div>

### setBaseReg() {#a283c8af77b20674deb6df24f7fafb347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::setBaseReg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Reg)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#ab9dd546ffbe61e1c49b482bbd603082f">BaseReg</a>, <a href="#a87de11a1ed5994728311f322cea460f9">BaseType</a> and <a href="#a46832c7411abf3b50e7e2bd40062822da77389e3a1193d2101c7ebd5bfa1853d4">RegBase</a>.</p>

</div>
</div>

### setIndexReg() {#aeca9f5bb50cfc8ea5f55971ef36310e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::setIndexReg (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Reg)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="#ab672b5bc6a883d5bd4de354367953ed4">IndexReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Alignment {#aac6867e20a1231adab9d495e529a6c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::Alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### AM {#ab09373c3bf7cd36b8616eb9300f65e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrType anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::AM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a9f340fdabbc82a71ef85e03b3f1dce0c">getDispSize</a>, <a href="#a386b44ca8fc5dfccb63c07481db2524d">isDispAddrType</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### BaseFrameIndex {#ae92f7227ae0a66d7f87b3c4588917644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::BaseFrameIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ac4c1e0a3ac33cb22a5eafffea1428607">dump</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### BaseReg {#ab9dd546ffbe61e1c49b482bbd603082f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::BaseReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ac4c1e0a3ac33cb22a5eafffea1428607">dump</a>, <a href="#ae7c9f7ef7708b3acb7366ca839f18692">hasBase</a>, <a href="#a135ef521eb222263bd3737241f96833f">hasBaseReg</a>, <a href="#aa5f8c14f9f67ad3f335f6e7c9c760681">isPCRelative</a> and <a href="#a283c8af77b20674deb6df24f7fafb347">setBaseReg</a>.</p>

</div>
</div>

### BaseType {#a87de11a1ed5994728311f322cea460f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Base anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::BaseType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ae7c9f7ef7708b3acb7366ca839f18692">hasBase</a>, <a href="#a135ef521eb222263bd3737241f96833f">hasBaseReg</a>, <a href="#a07654fca498c35c61c05548864c02c60">hasFrameIndex</a>, <a href="#af576c2ef3c0564ac151e250d7bb7278a">hasIndexReg</a>, <a href="#aa5f8c14f9f67ad3f335f6e7c9c760681">isPCRelative</a>, <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a> and <a href="#a283c8af77b20674deb6df24f7fafb347">setBaseReg</a>.</p>

</div>
</div>

### BlockAddr {#aa648f067fefe9157201c962b4efb9b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockAddress* anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::BlockAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ae56ea14b21ac540044695df370c5c7b3">hasSymbolicDisplacement</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### CP {#a066238ee75137639f8719f4b7cef127b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Constant* anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::CP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ae56ea14b21ac540044695df370c5c7b3">hasSymbolicDisplacement</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### Disp {#ad0a713ace664d7086a01098608505e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::Disp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ac4c1e0a3ac33cb22a5eafffea1428607">dump</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### ES {#adc0fcdce86a780f52c2b2ca9f25a9ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ae56ea14b21ac540044695df370c5c7b3">hasSymbolicDisplacement</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### GV {#aaff8ef5091bc7ab308691291c55aeefd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue* anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::GV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ae56ea14b21ac540044695df370c5c7b3">hasSymbolicDisplacement</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### IndexReg {#ab672b5bc6a883d5bd4de354367953ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::IndexReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ac4c1e0a3ac33cb22a5eafffea1428607">dump</a>, <a href="#af576c2ef3c0564ac151e250d7bb7278a">hasIndexReg</a>, <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a> and <a href="#aeca9f5bb50cfc8ea5f55971ef36310e0">setIndexReg</a>.</p>

</div>
</div>

### JT {#aa7b3aeda2dbea611c7db1bb83d9d4c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::JT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ae56ea14b21ac540044695df370c5c7b3">hasSymbolicDisplacement</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### MCSym {#aa5bacef4465a8d2c64e78eacb2af9f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::MCSym</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ae56ea14b21ac540044695df370c5c7b3">hasSymbolicDisplacement</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### Scale {#a74d857852763ad228adbe56c6e7c314f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::Scale</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ac4c1e0a3ac33cb22a5eafffea1428607">dump</a> and <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

### SymbolFlags {#ab8be5fb0c0bef16eda24255c02d74a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char anonymous{M68kISelDAGToDAG.cpp}::M68kISelAddressMode::SymbolFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a5ca5283bb94f9ac5de4bc46092aa07e8">M68kISelAddressMode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
