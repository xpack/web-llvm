---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-lvcompare-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{LVCompare.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{LVCompare.cpp} { ... }
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a595743901bd638327dbf6ea9b4c8ae44">LVCompareEntry</a> = std::tuple&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, unsigned, unsigned, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace1c2edb0f5af6f16205ca7dc0da2faa">LVCompareInfo</a> = std::map&lt; <a href="#a07e3fb63275d7219abf3c1a04e9d5926">LVCompareItem</a>, <a href="#a595743901bd638327dbf6ea9b4c8ae44">LVCompareEntry</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LVCompareItem { <a href="#a07e3fb63275d7219abf3c1a04e9d5926">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">LVCompareIndex { <a href="#a1ad6686ca7dcf67bc791fff07fdf7818">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb495e1cd7f5df61f02dcf8f5160d62">getHeader</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ab3681f0b25a9b917e52be360e6edf">getExpected</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa262e6ce443153c925eb99cf4ba0218b">getMissing</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af86a3a7ed19589a8116be7bcf56864ba">getAdded</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed756d65544fed8683dd6c9eebab6db">zeroResults</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LVCompareInfo::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc452df2b7fe014c59301b929ad6b72">getResultsEntry</a> (LVElement *Element)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ef14fbb440e09041aab8e8b54e697b">updateExpected</a> (LVElement *Element)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff30765db1c6fa27e15c0be798c3af4c">updateMissingOrAdded</a> (LVElement *Element, LVComparePass Pass)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ace1c2edb0f5af6f16205ca7dc0da2faa">LVCompareInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb4fe267293e2793367be0f3c3049d9">Results</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static LVCompareInfo::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1471fb6e7ddd176956e119ee51615d">IterTotal</a> = Results.end()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcompare">LVCompare</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1045f3cf3aeb081b39521caa2a0cee">CurrentComparator</a> = nullptr</td>
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

## Typedefs

### LVCompareEntry {#a595743901bd638327dbf6ea9b4c8ae44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LVCompare.cpp}::LVCompareEntry =  std::tuple&lt;const char *, unsigned, unsigned, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>

</div>
</div>

### LVCompareInfo {#ace1c2edb0f5af6f16205ca7dc0da2faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LVCompare.cpp}::LVCompareInfo =  std::map&lt;LVCompareItem, LVCompareEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LVCompareIndex {#a1ad6686ca7dcf67bc791fff07fdf7818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{LVCompare.cpp}::LVCompareIndex </td>
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
<td class="doxyEnumItemName">Header<a id="a1ad6686ca7dcf67bc791fff07fdf7818abf50d5e661106d0abe925af3c2e6f7e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Expected<a id="a1ad6686ca7dcf67bc791fff07fdf7818ac87076fc9901bb23fee8eda95971b5a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Missing<a id="a1ad6686ca7dcf67bc791fff07fdf7818a2aee0be2678ee90fd327cc186826438e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Added<a id="a1ad6686ca7dcf67bc791fff07fdf7818af29ddbfb905eb2593fdcdfb243f9af85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>

</div>
</div>

### LVCompareItem {#a07e3fb63275d7219abf3c1a04e9d5926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{LVCompare.cpp}::LVCompareItem </td>
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
<td class="doxyEnumItemName">Scope<a id="a07e3fb63275d7219abf3c1a04e9d5926a5d113f2038d289f391614c39043629e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Symbol<a id="a07e3fb63275d7219abf3c1a04e9d5926a02c86eb2792f3262c21d030a87e19793"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Type<a id="a07e3fb63275d7219abf3c1a04e9d5926aa1fa27779242b4902f7ae3bdd5c6d508"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Line<a id="a07e3fb63275d7219abf3c1a04e9d5926a4803e6b9e63dabf04de980788d6a13c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Total<a id="a07e3fb63275d7219abf3c1a04e9d5926a96b0141273eabab320119c467cdcaf17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getAdded() {#af86a3a7ed19589a8116be7bcf56864ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LVCompare.cpp}::getAdded ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>Reference <a href="#a1ad6686ca7dcf67bc791fff07fdf7818af29ddbfb905eb2593fdcdfb243f9af85">Added</a>.</p>

</div>
</div>

### getExpected() {#ad8ab3681f0b25a9b917e52be360e6edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LVCompare.cpp}::getExpected ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>Reference <a href="#a1ad6686ca7dcf67bc791fff07fdf7818ac87076fc9901bb23fee8eda95971b5a5">Expected</a>.</p>

</div>
</div>

### getHeader() {#a9cb495e1cd7f5df61f02dcf8f5160d62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LVCompare.cpp}::getHeader ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>Reference <a href="#a1ad6686ca7dcf67bc791fff07fdf7818abf50d5e661106d0abe925af3c2e6f7e7">Header</a>.</p>

</div>
</div>

### getMissing() {#aa262e6ce443153c925eb99cf4ba0218b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LVCompare.cpp}::getMissing ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>Reference <a href="#a1ad6686ca7dcf67bc791fff07fdf7818a2aee0be2678ee90fd327cc186826438e">Missing</a>.</p>

</div>
</div>

### getResultsEntry() {#accc452df2b7fe014c59301b929ad6b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVCompareInfo::iterator anonymous{LVCompare.cpp}::getResultsEntry (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a07e3fb63275d7219abf3c1a04e9d5926a4803e6b9e63dabf04de980788d6a13c4">Line</a>, <a href="#afdb4fe267293e2793367be0f3c3049d9">Results</a>, <a href="#a07e3fb63275d7219abf3c1a04e9d5926a5d113f2038d289f391614c39043629e8">Scope</a>, <a href="#a07e3fb63275d7219abf3c1a04e9d5926a02c86eb2792f3262c21d030a87e19793">Symbol</a> and <a href="#a07e3fb63275d7219abf3c1a04e9d5926aa1fa27779242b4902f7ae3bdd5c6d508">Type</a>.</p>


<p>Referenced by <a href="#a08ef14fbb440e09041aab8e8b54e697b">updateExpected</a> and <a href="#aff30765db1c6fa27e15c0be798c3af4c">updateMissingOrAdded</a>.</p>

</div>
</div>

### updateExpected() {#a08ef14fbb440e09041aab8e8b54e697b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LVCompare.cpp}::updateExpected (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>References <a href="#accc452df2b7fe014c59301b929ad6b72">getResultsEntry</a> and <a href="#aef1471fb6e7ddd176956e119ee51615d">IterTotal</a>.</p>

</div>
</div>

### updateMissingOrAdded() {#aff30765db1c6fa27e15c0be798c3af4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LVCompare.cpp}::updateMissingOrAdded (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a2f63e339cd88f5a8e97a8150ea9129d2">LVComparePass</a> Pass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>References <a href="#accc452df2b7fe014c59301b929ad6b72">getResultsEntry</a>, <a href="#aef1471fb6e7ddd176956e119ee51615d">IterTotal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a2f63e339cd88f5a8e97a8150ea9129d2a2aee0be2678ee90fd327cc186826438e">llvm::logicalview::Missing</a>.</p>

</div>
</div>

### zeroResults() {#a9ed756d65544fed8683dd6c9eebab6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LVCompare.cpp}::zeroResults ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aef1471fb6e7ddd176956e119ee51615d">IterTotal</a>, <a href="#afdb4fe267293e2793367be0f3c3049d9">Results</a> and <a href="#a07e3fb63275d7219abf3c1a04e9d5926a96b0141273eabab320119c467cdcaf17">Total</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CurrentComparator {#a5c1045f3cf3aeb081b39521caa2a0cee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVCompare* anonymous{LVCompare.cpp}::CurrentComparator = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>

</div>
</div>

### IterTotal {#aef1471fb6e7ddd176956e119ee51615d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVCompareInfo::iterator anonymous{LVCompare.cpp}::IterTotal = Results.end()</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>Referenced by <a href="#a08ef14fbb440e09041aab8e8b54e697b">updateExpected</a>, <a href="#aff30765db1c6fa27e15c0be798c3af4c">updateMissingOrAdded</a> and <a href="#a9ed756d65544fed8683dd6c9eebab6db">zeroResults</a>.</p>

</div>
</div>

### Results {#afdb4fe267293e2793367be0f3c3049d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVCompareInfo anonymous{LVCompare.cpp}::Results</td>
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
    {<a href="#a07e3fb63275d7219abf3c1a04e9d5926a4803e6b9e63dabf04de980788d6a13c4">LVCompareItem::Line</a>, <a href="#a595743901bd638327dbf6ea9b4c8ae44">LVCompareEntry</a>("Lines", 0, 0, 0)},
    {<a href="#a07e3fb63275d7219abf3c1a04e9d5926a5d113f2038d289f391614c39043629e8">LVCompareItem::Scope</a>, <a href="#a595743901bd638327dbf6ea9b4c8ae44">LVCompareEntry</a>("Scopes", 0, 0, 0)},
    {<a href="#a07e3fb63275d7219abf3c1a04e9d5926a02c86eb2792f3262c21d030a87e19793">LVCompareItem::Symbol</a>, <a href="#a595743901bd638327dbf6ea9b4c8ae44">LVCompareEntry</a>("Symbols", 0, 0, 0)},
    {<a href="#a07e3fb63275d7219abf3c1a04e9d5926aa1fa27779242b4902f7ae3bdd5c6d508">LVCompareItem::Type</a>, <a href="#a595743901bd638327dbf6ea9b4c8ae44">LVCompareEntry</a>("Types", 0, 0, 0)},
    {<a href="#a07e3fb63275d7219abf3c1a04e9d5926a96b0141273eabab320119c467cdcaf17">LVCompareItem::Total</a>, <a href="#a595743901bd638327dbf6ea9b4c8ae44">LVCompareEntry</a>("Total", 0, 0, 0)}}
</div>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a>.</p>


<p>Referenced by <a href="#accc452df2b7fe014c59301b929ad6b72">getResultsEntry</a> and <a href="#a9ed756d65544fed8683dd6c9eebab6db">zeroResults</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvcompare-cpp">LVCompare.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
