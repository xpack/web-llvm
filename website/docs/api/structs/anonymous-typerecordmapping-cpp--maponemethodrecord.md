---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MapOneMethodRecord` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb050f70c6d0ca7a40b10fa475d7f77">MapOneMethodRecord</a> (bool IsFromOverloadList)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8512de7a16f0f4a4b44a94bd615e1c31">operator()</a> (CodeViewRecordIO &amp;IO, OneMethodRecord &amp;Method) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a71dda4e992ce2561bd3dcd48f8fa28">IsFromOverloadList</a></td>
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


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp">TypeRecordMapping.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MapOneMethodRecord() {#a6eb050f70c6d0ca7a40b10fa475d7f77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::MapOneMethodRecord (bool IsFromOverloadList)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp">TypeRecordMapping.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a8512de7a16f0f4a4b44a94bd615e1c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator() (<a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio">CodeViewRecordIO</a> &amp; IO, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord">OneMethodRecord</a> &amp; Method)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp">TypeRecordMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/codeview/memberattributes/#a432bbd871c0fd2f7d1ded474054e346f">llvm::codeview::MemberAttributes::Attrs</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#ae64e42551b20dd850923628e968c61b2">llvm::codeview::OneMethodRecord::Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#a99cb8d9d0bb2afa112ef8d4239eb2f1e">llvm::codeview::OneMethodRecord::getAccess</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-typerecordmapping-cpp-/#a6e24199be7ad39f6ae05ce0b9ee14f31">anonymous{TypeRecordMapping.cpp}::getMemberAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#ac5995cb258a5e2e48cbd88eb9d55c248">llvm::codeview::OneMethodRecord::getMethodKind</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#ac4912ea70026c956728a2d2730bda6e9">llvm::codeview::OneMethodRecord::getOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#a66952c25fab42f836c97333715a36239">llvm::codeview::OneMethodRecord::isIntroducingVirtual</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#af503b7ac929de6f504809a3b42f3f49c">llvm::codeview::CodeViewRecordIO::isReading</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a5d36269fb288350b629675233d6bdf16">llvm::codeview::CodeViewRecordIO::mapInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#aa488397718059fddf9d4e699e2de4678">llvm::codeview::CodeViewRecordIO::mapStringZ</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#a442a2d9e12e944cb483f3a6435b84cb0">llvm::codeview::OneMethodRecord::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#a353d4483ddd2413bb0278ab13823f40b">llvm::codeview::OneMethodRecord::Type</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#ad90a90b166c420395bedf48b1ad24cea">llvm::codeview::OneMethodRecord::VFTableOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsFromOverloadList {#a6a71dda4e992ce2561bd3dcd48f8fa28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::IsFromOverloadList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp">TypeRecordMapping.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp">TypeRecordMapping.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
