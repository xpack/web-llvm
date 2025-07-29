---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/livedebugvalues/dbgvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DbgValue` Class

<p>Class recording the (high level) <em>value</em> of a variable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class LiveDebugValues::DbgValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">CodeGen/LiveDebugValues/InstrRefBasedImpl.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">KindT { <a href="#ac144ecd93e2625852097b3cab8a9d9bb">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a> (ArrayRef&lt; DbgOpID &gt; DbgOps, const DbgValueProperties &amp;Prop)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6277b4733d5286e2d8255d7eba3f08f">DbgValue</a> (unsigned BlockNo, const DbgValueProperties &amp;Prop, KindT Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1fd62363786d818dc9eafa3ea7b6d1b">DbgValue</a> (const DbgValueProperties &amp;Prop, KindT Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2de6fb82488ae81a7764d202b4b4344">operator==</a> (const DbgValue &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc30ac8e755afea628cc7db7736b54b8">operator!=</a> (const DbgValue &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9959e337a4d3e325e795686118700112">dump</a> (const MLocTracker *MTrack=nullptr, const DbgOpIDMap *OpStore=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12c429bd06d73df15134959325cd6022">getDbgOpIDs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70e8b6292c37300a3ea50fce69b2cdd">getDbgOpID</a> (unsigned Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7230438e78079233a5d7b3bc1d4f14b2">setDbgOpIDs</a> (ArrayRef&lt; DbgOpID &gt; NewIDs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add403fcd8074cf38d737756d931a013f">getLocationOpCount</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7231ce82c508c6311c527adacd942e97">hasJoinableLocOps</a> (const DbgValue &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa11be25d68038f30cb3e3cbe1e28839b">isUnjoinedPHI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6662bccd0cfb394a7fff423ee4fb40b">hasIdenticalValidLocOps</a> (const DbgValue &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0867a91c94f59efa8118215449f8b1d6">BlockNo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a NoVal or VPHI <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a>, which block it was generated in. <a href="#a0867a91c94f59efa8118215449f8b1d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a127bb33bfa67d26975c12bf33568af48">Properties</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a> for the <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> above. <a href="#a127bb33bfa67d26975c12bf33568af48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac144ecd93e2625852097b3cab8a9d9bb">KindT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5057e38ab74080fe88552c870519a84">Kind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Discriminator for whether this is a constant or an in-program value. <a href="#ad5057e38ab74080fe88552c870519a84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a327df730cc2c759ecf79b91b275aa2c0">DbgOps</a>[MAX_DBG_OPS]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If Kind is Def or VPHI, the set of IDs corresponding to the DbgOps that are used. <a href="#a327df730cc2c759ecf79b91b275aa2c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e4770056e609e87617c78b0a0bd5ed">OpCount</a></td>
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

<p>Class recording the (high level) <em>value</em> of a variable.</p>


<p>Identifies the value of the variable as a list of ValueIDNums and constant MachineOperands, or as an empty list for undef debug values or VPHI values which we have not found valid locations for. This class also stores meta-information about how the value is qualified. Used to reason about variable values when performing the second (<a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> specific) dataflow analysis.</p>


<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### KindT {#ac144ecd93e2625852097b3cab8a9d9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LiveDebugValues::DbgValue::KindT </td>
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
<td class="doxyEnumItemName">Undef<a id="ac144ecd93e2625852097b3cab8a9d9bba7c46001b3585fc4e42328dbe7123b5d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Def<a id="ac144ecd93e2625852097b3cab8a9d9bba953f120c5617d3f2b42df3fd424222ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPHI<a id="ac144ecd93e2625852097b3cab8a9d9bba520dc455d7fa69d828e881474255e2ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoVal<a id="ac144ecd93e2625852097b3cab8a9d9bbaf26793ed3fb3ea880eb66562c90d1826"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DbgValue() {#aa4c75a83b060403787c1fa416b0da31f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::DbgValue::DbgValue (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a> &gt; DbgOps, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Prop)</td>
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



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0867a91c94f59efa8118215449f8b1d6">BlockNo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a>, <a href="#ac144ecd93e2625852097b3cab8a9d9bba953f120c5617d3f2b42df3fd424222ad">Def</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#ae1a6cd7bbbd214de5c1990def99b1c57">LiveDebugValues::DbgValueProperties::getLocationOpCount</a>, <a href="#ad5057e38ab74080fe88552c870519a84">Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h/#af667677cb792c9287ab6aedd72d45193">MAX_DBG_OPS</a>, <a href="#a127bb33bfa67d26975c12bf33568af48">Properties</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a> and <a href="#ac144ecd93e2625852097b3cab8a9d9bba7c46001b3585fc4e42328dbe7123b5d4">Undef</a>.</p>


<p>Referenced by <a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a>, <a href="#af6662bccd0cfb394a7fff423ee4fb40b">hasIdenticalValidLocOps</a>, <a href="#a7231ce82c508c6311c527adacd942e97">hasJoinableLocOps</a>, <a href="#abc30ac8e755afea628cc7db7736b54b8">operator!=</a> and <a href="#af2de6fb82488ae81a7764d202b4b4344">operator==</a>.</p>

</div>
</div>

### DbgValue() {#ab6277b4733d5286e2d8255d7eba3f08f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::DbgValue::DbgValue (unsigned BlockNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Prop, <a href="#ac144ecd93e2625852097b3cab8a9d9bb">KindT</a> Kind)</td>
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



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0867a91c94f59efa8118215449f8b1d6">BlockNo</a>, <a href="#ad5057e38ab74080fe88552c870519a84">Kind</a>, <a href="#ac144ecd93e2625852097b3cab8a9d9bbaf26793ed3fb3ea880eb66562c90d1826">NoVal</a>, <a href="#a127bb33bfa67d26975c12bf33568af48">Properties</a> and <a href="#ac144ecd93e2625852097b3cab8a9d9bba520dc455d7fa69d828e881474255e2ed">VPHI</a>.</p>

</div>
</div>

### DbgValue() {#ad1fd62363786d818dc9eafa3ea7b6d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::DbgValue::DbgValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Prop, <a href="#ac144ecd93e2625852097b3cab8a9d9bb">KindT</a> Kind)</td>
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



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0867a91c94f59efa8118215449f8b1d6">BlockNo</a>, <a href="#ad5057e38ab74080fe88552c870519a84">Kind</a>, <a href="#a127bb33bfa67d26975c12bf33568af48">Properties</a> and <a href="#ac144ecd93e2625852097b3cab8a9d9bba7c46001b3585fc4e42328dbe7123b5d4">Undef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#abc30ac8e755afea628cc7db7736b54b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgValue::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> &amp; Other)</td>
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



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#af2de6fb82488ae81a7764d202b4b4344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgValue::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> &amp; Other)</td>
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



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a0867a91c94f59efa8118215449f8b1d6">BlockNo</a>, <a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a>, <a href="#ac144ecd93e2625852097b3cab8a9d9bba953f120c5617d3f2b42df3fd424222ad">Def</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae04157f1cd3b64e93ebd44f8f65e395c">llvm::equal</a>, <a href="#a12c429bd06d73df15134959325cd6022">getDbgOpIDs</a>, <a href="#ad5057e38ab74080fe88552c870519a84">Kind</a>, <a href="#ac144ecd93e2625852097b3cab8a9d9bbaf26793ed3fb3ea880eb66562c90d1826">NoVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a127bb33bfa67d26975c12bf33568af48">Properties</a> and <a href="#ac144ecd93e2625852097b3cab8a9d9bba520dc455d7fa69d828e881474255e2ed">VPHI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a9959e337a4d3e325e795686118700112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgValue::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> * MTrack=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap">DbgOpIDMap</a> * OpStore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a0867a91c94f59efa8118215449f8b1d6">BlockNo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac144ecd93e2625852097b3cab8a9d9bba953f120c5617d3f2b42df3fd424222ad">Def</a>, <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid/#a743561a2288ede30c2992d98e1866505">LiveDebugValues::DbgOpID::dump</a>, <a href="#aa70e8b6292c37300a3ea50fce69b2cdd">getDbgOpID</a>, <a href="#a12c429bd06d73df15134959325cd6022">getDbgOpIDs</a>, <a href="#ad5057e38ab74080fe88552c870519a84">Kind</a>, <a href="#ac144ecd93e2625852097b3cab8a9d9bbaf26793ed3fb3ea880eb66562c90d1826">NoVal</a>, <a href="#a127bb33bfa67d26975c12bf33568af48">Properties</a> and <a href="#ac144ecd93e2625852097b3cab8a9d9bba520dc455d7fa69d828e881474255e2ed">VPHI</a>.</p>

</div>
</div>

### getDbgOpID() {#aa70e8b6292c37300a3ea50fce69b2cdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgOpID LiveDebugValues::DbgValue::getDbgOpID (unsigned Index)</td>
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



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid/#a91064aebe93d3d6b7776a90451f2a854">LiveDebugValues::DbgOpID::UndefID</a>.</p>


<p>Referenced by <a href="#a9959e337a4d3e325e795686118700112">dump</a> and <a href="#a7231ce82c508c6311c527adacd942e97">hasJoinableLocOps</a>.</p>

</div>
</div>

### getDbgOpIDs() {#a12c429bd06d73df15134959325cd6022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; DbgOpID &gt; LiveDebugValues::DbgValue::getDbgOpIDs ()</td>
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



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a9959e337a4d3e325e795686118700112">dump</a>, <a href="#af6662bccd0cfb394a7fff423ee4fb40b">hasIdenticalValidLocOps</a> and <a href="#af2de6fb82488ae81a7764d202b4b4344">operator==</a>.</p>

</div>
</div>

### getLocationOpCount() {#add403fcd8074cf38d737756d931a013f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::DbgValue::getLocationOpCount ()</td>
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



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#a127bb33bfa67d26975c12bf33568af48">Properties</a>.</p>


<p>Referenced by <a href="#a7231ce82c508c6311c527adacd942e97">hasJoinableLocOps</a> and <a href="#a7230438e78079233a5d7b3bc1d4f14b2">setDbgOpIDs</a>.</p>

</div>
</div>

### hasIdenticalValidLocOps() {#af6662bccd0cfb394a7fff423ee4fb40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgValue::hasIdenticalValidLocOps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> &amp; Other)</td>
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



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae04157f1cd3b64e93ebd44f8f65e395c">llvm::equal</a>, <a href="#a12c429bd06d73df15134959325cd6022">getDbgOpIDs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### hasJoinableLocOps() {#a7231ce82c508c6311c527adacd942e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgValue::hasJoinableLocOps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> &amp; Other)</td>
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



<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a>, <a href="#aa70e8b6292c37300a3ea50fce69b2cdd">getDbgOpID</a>, <a href="#add403fcd8074cf38d737756d931a013f">getLocationOpCount</a>, <a href="#aa11be25d68038f30cb3e3cbe1e28839b">isUnjoinedPHI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### isUnjoinedPHI() {#aa11be25d68038f30cb3e3cbe1e28839b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgValue::isUnjoinedPHI ()</td>
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



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#ad5057e38ab74080fe88552c870519a84">Kind</a> and <a href="#ac144ecd93e2625852097b3cab8a9d9bba520dc455d7fa69d828e881474255e2ed">VPHI</a>.</p>


<p>Referenced by <a href="#a7231ce82c508c6311c527adacd942e97">hasJoinableLocOps</a>.</p>

</div>
</div>

### setDbgOpIDs() {#a7230438e78079233a5d7b3bc1d4f14b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::DbgValue::setDbgOpIDs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a> &gt; NewIDs)</td>
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



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#add403fcd8074cf38d737756d931a013f">getLocationOpCount</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BlockNo {#a0867a91c94f59efa8118215449f8b1d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LiveDebugValues::DbgValue::BlockNo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For a NoVal or VPHI <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a>, which block it was generated in.</p>

<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a>, <a href="#ad1fd62363786d818dc9eafa3ea7b6d1b">DbgValue</a>, <a href="#ab6277b4733d5286e2d8255d7eba3f08f">DbgValue</a>, <a href="#a9959e337a4d3e325e795686118700112">dump</a> and <a href="#af2de6fb82488ae81a7764d202b4b4344">operator==</a>.</p>

</div>
</div>

### Kind {#ad5057e38ab74080fe88552c870519a84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KindT LiveDebugValues::DbgValue::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Discriminator for whether this is a constant or an in-program value.</p>

<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a>, <a href="#ad1fd62363786d818dc9eafa3ea7b6d1b">DbgValue</a>, <a href="#ab6277b4733d5286e2d8255d7eba3f08f">DbgValue</a>, <a href="#a9959e337a4d3e325e795686118700112">dump</a>, <a href="#aa11be25d68038f30cb3e3cbe1e28839b">isUnjoinedPHI</a> and <a href="#af2de6fb82488ae81a7764d202b4b4344">operator==</a>.</p>

</div>
</div>

### Properties {#a127bb33bfa67d26975c12bf33568af48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgValueProperties LiveDebugValues::DbgValue::Properties</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a> for the <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> above.</p>

<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#aa4c75a83b060403787c1fa416b0da31f">DbgValue</a>, <a href="#ad1fd62363786d818dc9eafa3ea7b6d1b">DbgValue</a>, <a href="#ab6277b4733d5286e2d8255d7eba3f08f">DbgValue</a>, <a href="#a9959e337a4d3e325e795686118700112">dump</a>, <a href="#add403fcd8074cf38d737756d931a013f">getLocationOpCount</a> and <a href="#af2de6fb82488ae81a7764d202b4b4344">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DbgOps {#a327df730cc2c759ecf79b91b275aa2c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgOpID LiveDebugValues::DbgValue::DbgOps[MAX_DBG_OPS]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If Kind is Def or VPHI, the set of IDs corresponding to the DbgOps that are used.</p>


<p>VPHIs set every <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to EmptyID when we have not found a valid machine-value for every operand, and sets them to the corresponding machine-values when we have found all of them.</p>


<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### OpCount {#a13e4770056e609e87617c78b0a0bd5ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::DbgValue::OpCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
