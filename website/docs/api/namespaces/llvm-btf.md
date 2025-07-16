---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/btf
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `BTF` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::BTF { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/header">Header</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The .<a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> section header definition. <a href="/web-llvm/docs/api/structs/llvm/btf/header/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/commontype">CommonType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> common type definition. <a href="/web-llvm/docs/api/structs/llvm/btf/commontype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/btfenum">BTFEnum</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BTF_KIND_ENUM is followed by multiple "struct BTFEnum". <a href="/web-llvm/docs/api/structs/llvm/btf/btfenum/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/btfenum64">BTFEnum64</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BTF_KIND_ENUM64 is followed by multiple "struct BTFEnum64". <a href="/web-llvm/docs/api/structs/llvm/btf/btfenum64/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/btfarray">BTFArray</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BTF_KIND_ARRAY is followed by one "struct BTFArray". <a href="/web-llvm/docs/api/structs/llvm/btf/btfarray/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/btfmember">BTFMember</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BTF_KIND_STRUCT and BTF_KIND_UNION are followed by multiple "struct BTFMember". <a href="/web-llvm/docs/api/structs/llvm/btf/btfmember/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/btfparam">BTFParam</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BTF_KIND_FUNC_PROTO are followed by multiple "struct BTFParam". <a href="/web-llvm/docs/api/structs/llvm/btf/btfparam/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/btfdatasec">BTFDataSec</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BTF_KIND_DATASEC are followed by multiple "struct BTFDataSecVar". <a href="/web-llvm/docs/api/structs/llvm/btf/btfdatasec/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/extheader">ExtHeader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The .BTF.ext section header definition. <a href="/web-llvm/docs/api/structs/llvm/btf/extheader/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/bpffuncinfo">BPFFuncInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifying one function info. <a href="/web-llvm/docs/api/structs/llvm/btf/bpffuncinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/secfuncinfo">SecFuncInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifying function info's in one section. <a href="/web-llvm/docs/api/structs/llvm/btf/secfuncinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/bpflineinfo">BPFLineInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifying one line info. <a href="/web-llvm/docs/api/structs/llvm/btf/bpflineinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/seclineinfo">SecLineInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifying line info's in one section. <a href="/web-llvm/docs/api/structs/llvm/btf/seclineinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/bpffieldreloc">BPFFieldReloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifying one offset relocation. <a href="/web-llvm/docs/api/structs/llvm/btf/bpffieldreloc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/secfieldreloc">SecFieldReloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifying offset relocation's in one section. <a href="/web-llvm/docs/api/structs/llvm/btf/secfieldreloc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/arraytype">ArrayType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/structtype">StructType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/enumtype">EnumType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/btf/enum64type">Enum64Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint32_t { <a href="#a6ec8ee3421ecf83a99f08254c75bb619">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#ac469d636ea54a1eb9da4c1f633a4496c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sizes in bytes of various things in the <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> format. <a href="#ac469d636ea54a1eb9da4c1f633a4496c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint32_t { <a href="#aca6cc69f0f884702fe99132c1768fc69">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">TypeKinds : uint8_t { <a href="#a0af1f8573a112c12b0da96e71f0c2980">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint8_t { <a href="#a362eaa8f9116455c5f7c094184392199">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attributes stored in the INT_ENCODING. <a href="#a362eaa8f9116455c5f7c094184392199">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint8_t { <a href="#af1a9d2e61645fcb9c7f99ba6575a0e4c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BTF_KIND_FUNC can be global, static or extern. <a href="#af1a9d2e61645fcb9c7f99ba6575a0e4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint8_t { <a href="#a62e2e79c8ada2f06799e39e1bceac88b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Variable scoping information. <a href="#a62e2e79c8ada2f06799e39e1bceac88b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PatchableRelocKind : uint32_t { <a href="#af0e0ebe9cc5df71a99c113f92f148799">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CO-RE relocation kind codes used in .BTF.ext section. <a href="#af0e0ebe9cc5df71a99c113f92f148799">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad378f719619db33a1230ea7c54e89942">FWD_UNION_FLAG</a> = 1u &lt;&lt; 31</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4efb94e5d02bd8a665a4d969c41c393a">ENUM_SIGNED_FLAG</a> = 1u &lt;&lt; 31</td>
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

### anonymous enum  {#a6ec8ee3421ecf83a99f08254c75bb619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint32_t</td>
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
<td class="doxyEnumItemName">MAGIC<a id="a6ec8ee3421ecf83a99f08254c75bb619a7ce2fb333004db6fba00cb0e9d5643a2"></a></td>
<td class="doxyEnumItemDescription"> (= 0xeB9F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VERSION<a id="a6ec8ee3421ecf83a99f08254c75bb619a74ca018665ed4283ea62fa16b3959ba5"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>

</div>
</div>

### anonymous enum  {#ac469d636ea54a1eb9da4c1f633a4496c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sizes in bytes of various things in the <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> format.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HeaderSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca4af5f992bdc47a779c499ffc6fdcaf43"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtHeaderSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca4fd79d51eeb922263326f1b63b5ed0c2"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CommonTypeSize<a id="ac469d636ea54a1eb9da4c1f633a4496cac7b762881751a4050258403c56a474c8"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTFArraySize<a id="ac469d636ea54a1eb9da4c1f633a4496ca145e88869737d1e5d66f69560ebc3b76"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTFEnumSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca40e10ede382977180a24aff1d47a56fc"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTFEnum64Size<a id="ac469d636ea54a1eb9da4c1f633a4496ca0c9f8e5e4ae813fac59083717851ce07"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTFMemberSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca3663f67af63c0c12b250f0a116272dea"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTFParamSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca841b25a4c08266f90f2eab0c069812e0"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTFDataSecVarSize<a id="ac469d636ea54a1eb9da4c1f633a4496cacab2d7bfdf05721a0926f1720349c48c"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SecFuncInfoSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca805bbdf1bf4cd3255a65adb366fc7d3e"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SecLineInfoSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca5285c08177d64988cd500216aa3dd72c"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SecFieldRelocSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca57880654dbca3044c69bb9093dc558c0"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPFFuncInfoSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca33efb06f47c2ccb444930e6cb0d728fa"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPFLineInfoSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca6ae6030bf84fe96956874eabb935a50e"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPFFieldRelocSize<a id="ac469d636ea54a1eb9da4c1f633a4496ca95c9283601ae79feccbe7919be819da3"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>

</div>
</div>

### anonymous enum  {#aca6cc69f0f884702fe99132c1768fc69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint32_t</td>
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
<td class="doxyEnumItemName">MAX_VLEN<a id="aca6cc69f0f884702fe99132c1768fc69a0b74663a3318d0a8c56cf85058b833ce"></a></td>
<td class="doxyEnumItemDescription">Max # of struct/union/enum members or func args (= 0xffff)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>

</div>
</div>

### anonymous enum  {#a362eaa8f9116455c5f7c094184392199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attributes stored in the INT_ENCODING.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INT_SIGNED<a id="a362eaa8f9116455c5f7c094184392199a7112153d77d8e8504dea93f5cdbe87e2"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INT_CHAR<a id="a362eaa8f9116455c5f7c094184392199a3c1b830bf0a0512d4d15518141309e24"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INT_BOOL<a id="a362eaa8f9116455c5f7c094184392199af11755cf94b2dbee7c1c0bc26e6a06f5"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 2))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>

</div>
</div>

### anonymous enum  {#af1a9d2e61645fcb9c7f99ba6575a0e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BTF_KIND_FUNC can be global, static or extern.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_STATIC<a id="af1a9d2e61645fcb9c7f99ba6575a0e4ca16d923c98d9f71d27f5cb1576fdab1c6"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_GLOBAL<a id="af1a9d2e61645fcb9c7f99ba6575a0e4cad5f32670b77599a0fd74dd349fb8d1e2"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FUNC_EXTERN<a id="af1a9d2e61645fcb9c7f99ba6575a0e4ca5013ca928d6276c4491b13a132a8eb2d"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>

</div>
</div>

### anonymous enum  {#a62e2e79c8ada2f06799e39e1bceac88b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Variable scoping information.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VAR_STATIC<a id="a62e2e79c8ada2f06799e39e1bceac88ba94c71e5a252df524a5cffd450c48d465"></a></td>
<td class="doxyEnumItemDescription">Linkage: InternalLinkage (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VAR_GLOBAL_ALLOCATED<a id="a62e2e79c8ada2f06799e39e1bceac88ba3c8bcddcaf91e52c922c2e67f6b0fad9"></a></td>
<td class="doxyEnumItemDescription">Linkage: ExternalLinkage (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VAR_GLOBAL_EXTERNAL<a id="a62e2e79c8ada2f06799e39e1bceac88badf47534843830ba58742b53faa5afcf9"></a></td>
<td class="doxyEnumItemDescription">Linkage: ExternalLinkage (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>

</div>
</div>

### PatchableRelocKind {#af0e0ebe9cc5df71a99c113f92f148799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::BTF::PatchableRelocKind : uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CO-RE relocation kind codes used in .BTF.ext section.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIELD_BYTE_OFFSET<a id="af0e0ebe9cc5df71a99c113f92f148799a65537ca629fc55c1cb58287b73d352b5"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIELD_BYTE_SIZE<a id="af0e0ebe9cc5df71a99c113f92f148799aa7ed9c11a74d7d89fd613edd59aa09a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIELD_EXISTENCE<a id="af0e0ebe9cc5df71a99c113f92f148799af20ac25cf46638e7e25a14ec2df08ef6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIELD_SIGNEDNESS<a id="af0e0ebe9cc5df71a99c113f92f148799a371ef25f16d59edde27ea1418bbd5425"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIELD_LSHIFT_U64<a id="af0e0ebe9cc5df71a99c113f92f148799adebd77ac95d260fd74b6b7d5af076808"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIELD_RSHIFT_U64<a id="af0e0ebe9cc5df71a99c113f92f148799a0ba30ef232f9881a53f6f66295926e2f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTF_TYPE_ID_LOCAL<a id="af0e0ebe9cc5df71a99c113f92f148799ad68d76b71372e215deecb4c8ed3270c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTF_TYPE_ID_REMOTE<a id="af0e0ebe9cc5df71a99c113f92f148799acbb290538d39cb27fb3cc388297b226b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_EXISTENCE<a id="af0e0ebe9cc5df71a99c113f92f148799ad5e3f2784be9365b4b1e4ea9f7ed7577"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_SIZE<a id="af0e0ebe9cc5df71a99c113f92f148799aeb14048b6ba0696f38cf4a87744413d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENUM_VALUE_EXISTENCE<a id="af0e0ebe9cc5df71a99c113f92f148799ab96e1ec4defd44b7cf6d64d2154eeb8a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENUM_VALUE<a id="af0e0ebe9cc5df71a99c113f92f148799a371669db5e8b461d1cfa6c3c4a58ac60"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_MATCH<a id="af0e0ebe9cc5df71a99c113f92f148799ae1b7461f572b33b7261159c8546dd7ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAX_FIELD_RELOC_KIND<a id="af0e0ebe9cc5df71a99c113f92f148799abbedb736c5e8d73c224d26c81d150594"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>

</div>
</div>

### TypeKinds {#a0af1f8573a112c12b0da96e71f0c2980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::BTF::TypeKinds : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ENUM\_SIGNED\_FLAG {#a4efb94e5d02bd8a665a4d969c41c393a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTF::ENUM_SIGNED_FLAG = 1u &lt;&lt; 31</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>.</p>

</div>
</div>

### FWD\_UNION\_FLAG {#ad378f719619db33a1230ea7c54e89942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTF::FWD_UNION_FLAG = 1u &lt;&lt; 31</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/btf/btf-h">BTF.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
