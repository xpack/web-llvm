---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memdepresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemDepResult` Class

<p>A memory dependence query can return one of three different answers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemDepResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">llvm/Analysis/MemoryDependenceAnalysis.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626ce759bbdafd97b9a1f4ebbb5ce92a">ValueTy</a> = <a href="/web-llvm/docs/api/classes/llvm/pointersumtype">PointerSumType</a>&lt; DepType, <a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; Invalid, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;, <a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; Clobber, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;, <a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; Def, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;, <a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; Other, <a href="/web-llvm/docs/api/classes/llvm/pointerembeddedint">PointerEmbeddedInt</a>&lt; OtherType, 3 &gt; &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DepType { <a href="#ab9298a0662bef8856087aae491e84790">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">OtherType { <a href="#ae5e9de11544c9532c492be1bcff8b2d7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If DepType is "Other", the upper part of the sum type is an encoding of the following more detailed type information. <a href="#ae5e9de11544c9532c492be1bcff8b2d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a532bf6813cfad427c793ef4678216b9d">MemoryDependenceResults</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a2ee4897b77650c8af536a9b0c02a8">MemDepResult</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe0f4a827f2a5236ca96c9d6e0e004d">MemDepResult</a> (ValueTy V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d5331fe3f7e2bc481057a5c7560b8a">operator==</a> (const MemDepResult &amp;M) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f76f839925005473d8bafecc0edd69d">operator!=</a> (const MemDepResult &amp;M) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6f43b4f03c10a544c5de9ddf4f2a31">operator&lt;</a> (const MemDepResult &amp;M) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60fe973bfe754cec02dff33319d81888">operator&gt;</a> (const MemDepResult &amp;M) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01bfb86ab31d9f9a92f926aba4a463dc">isClobber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query that is an instruction clobber dependency. <a href="#a01bfb86ab31d9f9a92f926aba4a463dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70bfd297fb0ed3a5fa0ef09b5a47b496">isDef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query that is an instruction definition dependency. <a href="#a70bfd297fb0ed3a5fa0ef09b5a47b496">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9284c7b4e7cfa1baabc14bf877b29f8">isLocal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a valid local query (Clobber/Def). <a href="#aa9284c7b4e7cfa1baabc14bf877b29f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6159ef05223f67e8dd0a178377f06b">isNonLocal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query that is transparent to the start of the block, but where a non-local hasn't been done. <a href="#a2b6159ef05223f67e8dd0a178377f06b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47504af508f66b8f52d3f100d32326fc">isNonFuncLocal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query that is transparent to the start of the function. <a href="#a47504af508f66b8f52d3f100d32326fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad752ec517a6efc823355c1e2fc21abb">isUnknown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query which cannot and/or will not be computed. <a href="#aad752ec517a6efc823355c1e2fc21abb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae824fe970b941b6bafc9b41d65cb4799">getInst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a normal dependency, returns the instruction that is depended on. <a href="#ae824fe970b941b6bafc9b41d65cb4799">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94413fe1c3ef468e891d75e02aed00f8">isDirty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this is a <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> in its dirty/invalid. state. <a href="#a94413fe1c3ef468e891d75e02aed00f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointersumtype">ValueTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a152e00edeb4b8c1595754ebe864307f7">Value</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4760893fa2bd86ce4460d3171fb9a82">getDef</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>get methods: These are static ctor methods for creating various <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> kinds. <a href="#ae4760893fa2bd86ce4460d3171fb9a82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acfd94bce56e2812f8e5d7626dd9b8f">getClobber</a> (Instruction *Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a465c166d520399ff2b114c8aac5e7f3d">getNonLocal</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfd696331e43abcbcf5060bf0cd506e4">getNonFuncLocal</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87800772e5bbce0b8e0cb23b54e47f58">getUnknown</a> ()</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf1e438f2ec9e65b143bd4c5a0821cd">getDirty</a> (Instruction *Inst)</td>
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

<p>A memory dependence query can return one of three different answers.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ValueTy {#a626ce759bbdafd97b9a1f4ebbb5ce92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemDepResult::ValueTy =  PointerSumType&lt;
      DepType, PointerSumTypeMember&lt;Invalid, Instruction *&gt;,
      PointerSumTypeMember&lt;Clobber, Instruction *&gt;,
      PointerSumTypeMember&lt;Def, Instruction *&gt;,
      PointerSumTypeMember&lt;Other, PointerEmbeddedInt&lt;OtherType, 3&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DepType {#ab9298a0662bef8856087aae491e84790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MemDepResult::DepType </td>
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
<td class="doxyEnumItemName">Invalid<a id="ab9298a0662bef8856087aae491e84790a7cb2cbf4079b61ed98784f9fe153c9aa"></a></td>
<td class="doxyEnumItemDescription">Clients of MemDep never see this (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Clobber<a id="ab9298a0662bef8856087aae491e84790a22789038753868da92742bca54389f13"></a></td>
<td class="doxyEnumItemDescription">This is a dependence on the specified instruction which clobbers the desired value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Def<a id="ab9298a0662bef8856087aae491e84790a1761e14f49db6d6f5c342ad4d0117b37"></a></td>
<td class="doxyEnumItemDescription">This is a dependence on the specified instruction which defines or produces the desired memory location</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Other<a id="ab9298a0662bef8856087aae491e84790aaa9b5488803947feba51dd5f638d9727"></a></td>
<td class="doxyEnumItemDescription">This marker indicates that the query has no known dependency in the specified block</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### OtherType {#ae5e9de11544c9532c492be1bcff8b2d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MemDepResult::OtherType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If DepType is "Other", the upper part of the sum type is an encoding of the following more detailed type information.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NonLocal<a id="ae5e9de11544c9532c492be1bcff8b2d7a65afdebdf3f85d40f7d820a0053ad5f2"></a></td>
<td class="doxyEnumItemDescription">This marker indicates that the query has no dependency in the specified block (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NonFuncLocal<a id="ae5e9de11544c9532c492be1bcff8b2d7ab477dfce95da90a912d1d60cedf4f03b"></a></td>
<td class="doxyEnumItemDescription">This marker indicates that the query has no dependency in the specified function</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="ae5e9de11544c9532c492be1bcff8b2d7a85de94931b71d99e58399555e1e9e729"></a></td>
<td class="doxyEnumItemDescription">This marker indicates that the query dependency is unknown</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### MemoryDependenceResults {#a532bf6813cfad427c793ef4678216b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults">MemoryDependenceResults</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>Reference <a href="#a532bf6813cfad427c793ef4678216b9d">MemoryDependenceResults</a>.</p>


<p>Referenced by <a href="#a532bf6813cfad427c793ef4678216b9d">MemoryDependenceResults</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemDepResult() {#aa7a2ee4897b77650c8af536a9b0c02a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemDepResult::MemDepResult ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#a6acfd94bce56e2812f8e5d7626dd9b8f">getClobber</a>, <a href="#ae4760893fa2bd86ce4460d3171fb9a82">getDef</a>, <a href="#adfd696331e43abcbcf5060bf0cd506e4">getNonFuncLocal</a>, <a href="#a465c166d520399ff2b114c8aac5e7f3d">getNonLocal</a> and <a href="#a87800772e5bbce0b8e0cb23b54e47f58">getUnknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MemDepResult() {#a8fe0f4a827f2a5236ca96c9d6e0e004d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemDepResult::MemDepResult (<a href="/web-llvm/docs/api/classes/llvm/pointersumtype">ValueTy</a> V)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a1f76f839925005473d8bafecc0edd69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> &amp; M)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### operator&lt;() {#a9e6f43b4f03c10a544c5de9ddf4f2a31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> &amp; M)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### operator==() {#a86d5331fe3f7e2bc481057a5c7560b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> &amp; M)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### operator&gt;() {#a60fe973bfe754cec02dff33319d81888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::operator&gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> &amp; M)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInst() {#ae824fe970b941b6bafc9b41d65cb4799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::MemDepResult::getInst ()</td>
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

<p>If this is a normal dependency, returns the instruction that is depended on.</p>


<p>Otherwise, returns null.</p>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a4082748189dc3460ea7130cd8d7790b5">llvm::MemoryDependenceResults::removeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a160dacda9f89b4c190ff303c6f4ed15e">reportMayClobberedLoad</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>.</p>

</div>
</div>

### isClobber() {#a01bfb86ab31d9f9a92f926aba4a463dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::isClobber ()</td>
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

<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query that is an instruction clobber dependency.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="#aa9284c7b4e7cfa1baabc14bf877b29f8">isLocal</a>.</p>

</div>
</div>

### isDef() {#a70bfd297fb0ed3a5fa0ef09b5a47b496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::isDef ()</td>
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

<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query that is an instruction definition dependency.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a3928622cecd7b474f1c959b50897fae4">llvm::MemoryDependenceResults::getPointerDependencyFrom</a>, <a href="#aa9284c7b4e7cfa1baabc14bf877b29f8">isLocal</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>.</p>

</div>
</div>

### isLocal() {#aa9284c7b4e7cfa1baabc14bf877b29f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::isLocal ()</td>
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

<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a valid local query (Clobber/Def).</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>References <a href="#a01bfb86ab31d9f9a92f926aba4a463dc">isClobber</a> and <a href="#a70bfd297fb0ed3a5fa0ef09b5a47b496">isDef</a>.</p>

</div>
</div>

### isNonFuncLocal() {#a47504af508f66b8f52d3f100d32326fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::isNonFuncLocal ()</td>
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

<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query that is transparent to the start of the function.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

### isNonLocal() {#a2b6159ef05223f67e8dd0a178377f06b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::isNonLocal ()</td>
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

<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query that is transparent to the start of the block, but where a non-local hasn't been done.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a3928622cecd7b474f1c959b50897fae4">llvm::MemoryDependenceResults::getPointerDependencyFrom</a>.</p>

</div>
</div>

### isUnknown() {#aad752ec517a6efc823355c1e2fc21abb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::isUnknown ()</td>
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

<p>Tests if this <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> represents a query which cannot and/or will not be computed.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a3928622cecd7b474f1c959b50897fae4">llvm::MemoryDependenceResults::getPointerDependencyFrom</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isDirty() {#a94413fe1c3ef468e891d75e02aed00f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemDepResult::isDirty ()</td>
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

<p>Tests if this is a <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> in its dirty/invalid. state.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Value {#a152e00edeb4b8c1595754ebe864307f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTy llvm::MemDepResult::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getClobber() {#a6acfd94bce56e2812f8e5d7626dd9b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult llvm::MemDepResult::getClobber (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pointersumtype/#a822f3a6433ac1dbaaead6a3143675fd0">llvm::PointerSumType&lt; DepType, PointerSumTypeMember&lt; Invalid, Instruction * &gt;, PointerSumTypeMember&lt; Clobber, Instruction * &gt;, PointerSumTypeMember&lt; Def, Instruction * &gt;, PointerSumTypeMember&lt; Other, PointerEmbeddedInt&lt; OtherType, 3 &gt; &gt; &gt;::create</a> and <a href="#aa7a2ee4897b77650c8af536a9b0c02a8">MemDepResult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### getDef() {#ae4760893fa2bd86ce4460d3171fb9a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult llvm::MemDepResult::getDef (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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

<p>get methods: These are static ctor methods for creating various <a href="/web-llvm/docs/api/classes/llvm/memdepresult">MemDepResult</a> kinds.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pointersumtype/#a822f3a6433ac1dbaaead6a3143675fd0">llvm::PointerSumType&lt; DepType, PointerSumTypeMember&lt; Invalid, Instruction * &gt;, PointerSumTypeMember&lt; Clobber, Instruction * &gt;, PointerSumTypeMember&lt; Def, Instruction * &gt;, PointerSumTypeMember&lt; Other, PointerEmbeddedInt&lt; OtherType, 3 &gt; &gt; &gt;::create</a> and <a href="#aa7a2ee4897b77650c8af536a9b0c02a8">MemDepResult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a81ed5939e93e21552b452f5f82a73a38">llvm::MemoryDependenceResults::getInvariantGroupPointerDependency</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### getNonFuncLocal() {#adfd696331e43abcbcf5060bf0cd506e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult llvm::MemDepResult::getNonFuncLocal ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pointersumtype/#a822f3a6433ac1dbaaead6a3143675fd0">llvm::PointerSumType&lt; DepType, PointerSumTypeMember&lt; Invalid, Instruction * &gt;, PointerSumTypeMember&lt; Clobber, Instruction * &gt;, PointerSumTypeMember&lt; Def, Instruction * &gt;, PointerSumTypeMember&lt; Other, PointerEmbeddedInt&lt; OtherType, 3 &gt; &gt; &gt;::create</a> and <a href="#aa7a2ee4897b77650c8af536a9b0c02a8">MemDepResult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### getNonLocal() {#a465c166d520399ff2b114c8aac5e7f3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult llvm::MemDepResult::getNonLocal ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pointersumtype/#a822f3a6433ac1dbaaead6a3143675fd0">llvm::PointerSumType&lt; DepType, PointerSumTypeMember&lt; Invalid, Instruction * &gt;, PointerSumTypeMember&lt; Clobber, Instruction * &gt;, PointerSumTypeMember&lt; Def, Instruction * &gt;, PointerSumTypeMember&lt; Other, PointerEmbeddedInt&lt; OtherType, 3 &gt; &gt; &gt;::create</a> and <a href="#aa7a2ee4897b77650c8af536a9b0c02a8">MemDepResult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a81ed5939e93e21552b452f5f82a73a38">llvm::MemoryDependenceResults::getInvariantGroupPointerDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### getUnknown() {#a87800772e5bbce0b8e0cb23b54e47f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult llvm::MemDepResult::getUnknown ()</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pointersumtype/#a822f3a6433ac1dbaaead6a3143675fd0">llvm::PointerSumType&lt; DepType, PointerSumTypeMember&lt; Invalid, Instruction * &gt;, PointerSumTypeMember&lt; Clobber, Instruction * &gt;, PointerSumTypeMember&lt; Def, Instruction * &gt;, PointerSumTypeMember&lt; Other, PointerEmbeddedInt&lt; OtherType, 3 &gt; &gt; &gt;::create</a> and <a href="#aa7a2ee4897b77650c8af536a9b0c02a8">MemDepResult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a81ed5939e93e21552b452f5f82a73a38">llvm::MemoryDependenceResults::getInvariantGroupPointerDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#ab46fb372d99dc0562d09cfdcd041d5ab">llvm::MemoryDependenceResults::getNonLocalPointerDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a3928622cecd7b474f1c959b50897fae4">llvm::MemoryDependenceResults::getPointerDependencyFrom</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getDirty() {#a7cf1e438f2ec9e65b143bd4c5a0821cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDepResult llvm::MemDepResult::getDirty (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorydependenceanalysis-h">MemoryDependenceAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
