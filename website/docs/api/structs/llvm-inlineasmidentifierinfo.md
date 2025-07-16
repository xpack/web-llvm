---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/inlineasmidentifierinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InlineAsmIdentifierInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::InlineAsmIdentifierInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">llvm/MC/MCParser/MCAsmParser.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IdKind { <a href="#a04889d7b2cc61d9a2bd7841c9d536b21">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe55f03726f7572e8f634f641f23f8e">InlineAsmIdentifierInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a01da0b2db675cdbdb09d618836cb44">isKind</a> (IdKind kind) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6eb96f6f80512d1109bcd2d9806372d">setEnum</a> (int64_t enumVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bbcf1e72836591c303695e7d01f2b83">setLabel</a> (void *decl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529b4a51ca5a97a5d9773f27e93a8e9c">setVar</a> (void *decl, bool isGlobalLV, unsigned size, unsigned type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/inlineasmidentifierinfo/enumidentifier">EnumIdentifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4817b89e743b5e19b1b4d680884f4bc5">Enum</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/inlineasmidentifierinfo/labelidentifier">LabelIdentifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81ddf5547f936de62e391c7ef40b86f">Label</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/inlineasmidentifierinfo/variableidentifier">VariableIdentifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cfdb7a6308cd66fdc1659cc5c6b9588">Var</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/inlineasmidentifierinfo">llvm::InlineAsmIdentifierInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9525fd190291bbd9cb10971cdccda259"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a04889d7b2cc61d9a2bd7841c9d536b21">IdKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4408945479cf4438f0e71ab00da564d5">Kind</a> = <a href="#a04889d7b2cc61d9a2bd7841c9d536b21a044c43878f4e8874c76d38351729de4e">IK_Invalid</a></td>
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


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### IdKind {#a04889d7b2cc61d9a2bd7841c9d536b21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InlineAsmIdentifierInfo::IdKind </td>
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
<td class="doxyEnumItemName">IK_Invalid<a id="a04889d7b2cc61d9a2bd7841c9d536b21a044c43878f4e8874c76d38351729de4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_Label<a id="a04889d7b2cc61d9a2bd7841c9d536b21a6917178e396791b6f56defcc817c7dec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_EnumVal<a id="a04889d7b2cc61d9a2bd7841c9d536b21a704007697830db898bcf02cd0eb6c704"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_Var<a id="a04889d7b2cc61d9a2bd7841c9d536b21ab7b8a36ea4c5f45a99971e9fd207aa0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InlineAsmIdentifierInfo() {#abfe55f03726f7572e8f634f641f23f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsmIdentifierInfo::InlineAsmIdentifierInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Reference <a href="#a04889d7b2cc61d9a2bd7841c9d536b21a044c43878f4e8874c76d38351729de4e">IK_Invalid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isKind() {#a8a01da0b2db675cdbdb09d618836cb44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsmIdentifierInfo::isKind (<a href="#a04889d7b2cc61d9a2bd7841c9d536b21">IdKind</a> kind)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="#aa6eb96f6f80512d1109bcd2d9806372d">setEnum</a>, <a href="#a7bbcf1e72836591c303695e7d01f2b83">setLabel</a> and <a href="#a529b4a51ca5a97a5d9773f27e93a8e9c">setVar</a>.</p>

</div>
</div>

### setEnum() {#aa6eb96f6f80512d1109bcd2d9806372d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAsmIdentifierInfo::setEnum (int64_t enumVal)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4817b89e743b5e19b1b4d680884f4bc5">Enum</a>, <a href="#a04889d7b2cc61d9a2bd7841c9d536b21a704007697830db898bcf02cd0eb6c704">IK_EnumVal</a>, <a href="#a04889d7b2cc61d9a2bd7841c9d536b21a044c43878f4e8874c76d38351729de4e">IK_Invalid</a> and <a href="#a8a01da0b2db675cdbdb09d618836cb44">isKind</a>.</p>

</div>
</div>

### setLabel() {#a7bbcf1e72836591c303695e7d01f2b83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAsmIdentifierInfo::setLabel (void * decl)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a04889d7b2cc61d9a2bd7841c9d536b21a044c43878f4e8874c76d38351729de4e">IK_Invalid</a>, <a href="#a04889d7b2cc61d9a2bd7841c9d536b21a6917178e396791b6f56defcc817c7dec">IK_Label</a>, <a href="#a8a01da0b2db675cdbdb09d618836cb44">isKind</a> and <a href="#ad81ddf5547f936de62e391c7ef40b86f">Label</a>.</p>

</div>
</div>

### setVar() {#a529b4a51ca5a97a5d9773f27e93a8e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAsmIdentifierInfo::setVar (void * decl, bool isGlobalLV, unsigned size, unsigned type)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a04889d7b2cc61d9a2bd7841c9d536b21a044c43878f4e8874c76d38351729de4e">IK_Invalid</a>, <a href="#a04889d7b2cc61d9a2bd7841c9d536b21ab7b8a36ea4c5f45a99971e9fd207aa0f">IK_Var</a>, <a href="#a8a01da0b2db675cdbdb09d618836cb44">isKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a> and <a href="#a5cfdb7a6308cd66fdc1659cc5c6b9588">Var</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a9525fd190291bbd9cb10971cdccda259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::InlineAsmIdentifierInfo llvm::InlineAsmIdentifierInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

### Enum {#a4817b89e743b5e19b1b4d680884f4bc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EnumIdentifier llvm::InlineAsmIdentifierInfo::Enum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="#aa6eb96f6f80512d1109bcd2d9806372d">setEnum</a>.</p>

</div>
</div>

### Label {#ad81ddf5547f936de62e391c7ef40b86f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LabelIdentifier llvm::InlineAsmIdentifierInfo::Label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="#a7bbcf1e72836591c303695e7d01f2b83">setLabel</a>.</p>

</div>
</div>

### Var {#a5cfdb7a6308cd66fdc1659cc5c6b9588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariableIdentifier llvm::InlineAsmIdentifierInfo::Var</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>


<p>Referenced by <a href="#a529b4a51ca5a97a5d9773f27e93a8e9c">setVar</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a4408945479cf4438f0e71ab00da564d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdKind llvm::InlineAsmIdentifierInfo::Kind = <a href="#a04889d7b2cc61d9a2bd7841c9d536b21a044c43878f4e8874c76d38351729de4e">IK_Invalid</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mcasmparser-h">MCAsmParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
