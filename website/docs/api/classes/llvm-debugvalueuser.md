---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/debugvalueuser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DebugValueUser` Class

<p>Base class for tracking ValueAsMetadata/DIArgLists with user lookups and Owner callbacks outside of <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DebugValueUser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> of a variable value-assignment, aka a non instruction representation of the dbg.value intrinsic. <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9ba175b0a06b0c9f3f2b7c59de4a5c">DebugValueUser</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a9e4cf14d62c1049ac3a84a093fffa0">DebugValueUser</a> (std::array&lt; Metadata *, 3 &gt; DebugValues)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af26353d977ff3af25598d77e68dbf2c3">DebugValueUser</a> (DebugValueUser &amp;&amp;X)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f98d48dac31a29891f3ea44f002f13">DebugValueUser</a> (const DebugValueUser &amp;X)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1b9d2cdb6a3926dff38a1d67d2db98">~DebugValueUser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4652d2380b00f276f3873f3e413a33c8">operator=</a> (DebugValueUser &amp;&amp;X)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabcaed6e7760a000b5dc3658dd63b746">operator=</a> (const DebugValueUser &amp;X)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6822d6e7acfee6f7aa9d49c0cef3c78e">operator==</a> (const DebugValueUser &amp;X) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a544e4cfb9dfe43772f639d5a556e2248">operator!=</a> (const DebugValueUser &amp;X) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae048cddef21682604d7ecb4d659ead91">getUser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d30c78026a2fe19fdb527932bcafba5">getUser</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51231385e9897d93b6ff7af9c96d1036">handleChangedValue</a> (void *Old, Metadata *NewDebugValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To be called by <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a2b9c0ec6595f7f4b7d737415a8cb0aaf">ReplaceableMetadataImpl::replaceAllUsesWith</a>, where <span class="doxyComputerOutput">Old</span> is a pointer to one of the pointers in <span class="doxyComputerOutput">DebugValues</span> (so should be type Metadata**), and <span class="doxyComputerOutput">NewDebugValue</span> is the new Metadata* that is replacing *Old. <a href="#a51231385e9897d93b6ff7af9c96d1036">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687f1a4e631d1ac4f5f36c370ba13268">resetDebugValues</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac437300794c7752e14a5cbca8d436c4c">resetDebugValue</a> (size_t Idx, Metadata *DebugValue)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96eda2bc83d3c713448ae292d4ef398f">getDebugValues</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a4ea9772ba5dbb75b6b3c2408a6cc2">trackDebugValue</a> (size_t Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab036646201a0f1f9efb11d13cb0ad586">trackDebugValues</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad50127adaab85decf96996e5b69e2081">untrackDebugValue</a> (size_t Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2fdb5f3220b37d6850010383ae15916">untrackDebugValues</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61037b3d421233a252b240f0c25da8a0">retrackDebugValues</a> (DebugValueUser &amp;X)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a></td>
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

<p>Base class for tracking ValueAsMetadata/DIArgLists with user lookups and Owner callbacks outside of <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a>.</p>


<p>Currently only inherited by <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a>; if other classes need to use it, then a SubclassID will need to be added (either as a new field or by making DebugValue into a PointerIntUnion) to discriminate between the subclasses in lookup and callback handling.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebugValueUser() {#a4b9ba175b0a06b0c9f3f2b7c59de4a5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebugValueUser::DebugValueUser ()</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="#a10f98d48dac31a29891f3ea44f002f13">DebugValueUser</a>, <a href="#af26353d977ff3af25598d77e68dbf2c3">DebugValueUser</a>, <a href="#a544e4cfb9dfe43772f639d5a556e2248">operator!=</a>, <a href="#aabcaed6e7760a000b5dc3658dd63b746">operator=</a>, <a href="#a4652d2380b00f276f3873f3e413a33c8">operator=</a> and <a href="#a6822d6e7acfee6f7aa9d49c0cef3c78e">operator==</a>.</p>

</div>
</div>

### DebugValueUser() {#a5a9e4cf14d62c1049ac3a84a093fffa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebugValueUser::DebugValueUser (std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, 3 &gt; DebugValues)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>.</p>

</div>
</div>

### DebugValueUser() {#af26353d977ff3af25598d77e68dbf2c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebugValueUser::DebugValueUser (<a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp;&amp; X)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>, <a href="#a4b9ba175b0a06b0c9f3f2b7c59de4a5c">DebugValueUser</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### DebugValueUser() {#a10f98d48dac31a29891f3ea44f002f13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebugValueUser::DebugValueUser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp; X)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>, <a href="#a4b9ba175b0a06b0c9f3f2b7c59de4a5c">DebugValueUser</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DebugValueUser() {#afd1b9d2cdb6a3926dff38a1d67d2db98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebugValueUser::~DebugValueUser ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a544e4cfb9dfe43772f639d5a556e2248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugValueUser::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp; X)</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>, <a href="#a4b9ba175b0a06b0c9f3f2b7c59de4a5c">DebugValueUser</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator=() {#a4652d2380b00f276f3873f3e413a33c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugValueUser &amp; llvm::DebugValueUser::operator= (<a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp;&amp; X)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>, <a href="#a4b9ba175b0a06b0c9f3f2b7c59de4a5c">DebugValueUser</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator=() {#aabcaed6e7760a000b5dc3658dd63b746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugValueUser &amp; llvm::DebugValueUser::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp; X)</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>, <a href="#a4b9ba175b0a06b0c9f3f2b7c59de4a5c">DebugValueUser</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator==() {#a6822d6e7acfee6f7aa9d49c0cef3c78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DebugValueUser::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp; X)</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>, <a href="#a4b9ba175b0a06b0c9f3f2b7c59de4a5c">DebugValueUser</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getUser() {#ae048cddef21682604d7ecb4d659ead91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgVariableRecord * DebugValueUser::getUser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### getUser() {#a9d30c78026a2fe19fdb527932bcafba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DbgVariableRecord * DebugValueUser::getUser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### handleChangedValue() {#a51231385e9897d93b6ff7af9c96d1036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugValueUser::handleChangedValue (void * Old, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * NewDebugValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>To be called by <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a2b9c0ec6595f7f4b7d737415a8cb0aaf">ReplaceableMetadataImpl::replaceAllUsesWith</a>, where <span class="doxyComputerOutput">Old</span> is a pointer to one of the pointers in <span class="doxyComputerOutput">DebugValues</span> (so should be type Metadata**), and <span class="doxyComputerOutput">NewDebugValue</span> is the new Metadata* that is replacing *Old.</p>


<p>For manually replacing elements of DebugValues, <span class="doxyComputerOutput">resetDebugValue(Idx, NewDebugValue)</span> should be used instead.</p>


<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#ac437300794c7752e14a5cbca8d436c4c">resetDebugValue</a>.</p>

</div>
</div>

### resetDebugValue() {#ac437300794c7752e14a5cbca8d436c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DebugValueUser::resetDebugValue (size_t Idx, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * DebugValue)</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>.</p>


<p>Referenced by <a href="#a51231385e9897d93b6ff7af9c96d1036">handleChangedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#acae02d7d014e32fd2151b92bf57aeb12">llvm::DbgVariableRecord::setAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ac8518bc959468abc1fcd62fadb427f45">llvm::DbgVariableRecord::setAssignId</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a9b641aa0b6a8f401fff5ba3675467835">llvm::DbgVariableRecord::setKillAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a826d85216c59be98085f0d03882b9c83">llvm::DbgVariableRecord::setRawLocation</a>.</p>

</div>
</div>

### resetDebugValues() {#a687f1a4e631d1ac4f5f36c370ba13268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DebugValueUser::resetDebugValues ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getDebugValues() {#a96eda2bc83d3c713448ae292d4ef398f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Metadata * &gt; llvm::DebugValueUser::getDebugValues ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#ab9d0079a3383c1716114943006e2d0f3">DebugValues</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### retrackDebugValues() {#a61037b3d421233a252b240f0c25da8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugValueUser::retrackDebugValues (<a href="/web-llvm/docs/api/classes/llvm/debugvalueuser">DebugValueUser</a> &amp; X)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### trackDebugValue() {#ad8a4ea9772ba5dbb75b6b3c2408a6cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugValueUser::trackDebugValue (size_t Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### trackDebugValues() {#ab036646201a0f1f9efb11d13cb0ad586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugValueUser::trackDebugValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### untrackDebugValue() {#ad50127adaab85decf96996e5b69e2081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugValueUser::untrackDebugValue (size_t Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### untrackDebugValues() {#af2fdb5f3220b37d6850010383ae15916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugValueUser::untrackDebugValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DebugValues {#ab9d0079a3383c1716114943006e2d0f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;Metadata *, 3&gt; llvm::DebugValueUser::DebugValues</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad5a6c4942fc21c7c6c614a78b35747d1">llvm::DbgVariableRecord::DbgVariableRecord</a>, <a href="#a10f98d48dac31a29891f3ea44f002f13">DebugValueUser</a>, <a href="#af26353d977ff3af25598d77e68dbf2c3">DebugValueUser</a>, <a href="#a5a9e4cf14d62c1049ac3a84a093fffa0">DebugValueUser</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a4df534a195fe4df5fc7c2eaf2a96bd97">llvm::DbgVariableRecord::getAssignID</a>, <a href="#a96eda2bc83d3c713448ae292d4ef398f">getDebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad76c901f38759f560144bafef2c598be">llvm::DbgVariableRecord::getRawAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a92bf6b19c53c3ebfa6045aaeacf6e24b">llvm::DbgVariableRecord::getRawAssignID</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ab9edb568c54e87f08484a5f46e399bee">llvm::DbgVariableRecord::getRawLocation</a>, <a href="#a51231385e9897d93b6ff7af9c96d1036">handleChangedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae53d93dd6b3f1e5cc24506d2f4119625">llvm::DbgVariableRecord::isIdenticalToWhenDefined</a>, <a href="#a544e4cfb9dfe43772f639d5a556e2248">operator!=</a>, <a href="#aabcaed6e7760a000b5dc3658dd63b746">operator=</a>, <a href="#a4652d2380b00f276f3873f3e413a33c8">operator=</a>, <a href="#a6822d6e7acfee6f7aa9d49c0cef3c78e">operator==</a>, <a href="#ac437300794c7752e14a5cbca8d436c4c">resetDebugValue</a> and <a href="#a687f1a4e631d1ac4f5f36c370ba13268">resetDebugValues</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
