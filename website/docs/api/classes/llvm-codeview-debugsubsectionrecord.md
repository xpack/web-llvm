---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/debugsubsectionrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DebugSubsectionRecord` Class



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::DebugSubsectionRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">llvm/DebugInfo/CodeView/DebugSubsectionRecord.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fef9071bdf5369431216a15ec9295bd">DebugSubsectionRecord</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa01ef0eaae7c71613c2b61c94a613b91">DebugSubsectionRecord</a> (DebugSubsectionKind Kind, BinaryStreamRef Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1aa453be1d81657eb8ac13c221a7f3d">getRecordLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2af">DebugSubsectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f80f60a7c507c599778b2c6ca5c53f">kind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f78bcad5e129ca65ab47f018116c28">getRecordData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2af">DebugSubsectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5282898f6ddba2d9966ca911875aec74">Kind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa6adf97f83acf6453d4a6a4b1070f3754">DebugSubsectionKind::None</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be48d00b18bb3e25990a759944cc753">Data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d6b180a6430d3f25c49ab5777d63d59">initialize</a> (BinaryStreamRef Stream, DebugSubsectionRecord &amp;Info)</td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebugSubsectionRecord() {#a6fef9071bdf5369431216a15ec9295bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugSubsectionRecord::DebugSubsectionRecord ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a>.</p>


<p>References <a href="#a6fef9071bdf5369431216a15ec9295bd">DebugSubsectionRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>.</p>


<p>Referenced by <a href="#a6fef9071bdf5369431216a15ec9295bd">DebugSubsectionRecord</a> and <a href="#a2d6b180a6430d3f25c49ab5777d63d59">initialize</a>.</p>

</div>
</div>

### DebugSubsectionRecord() {#aa01ef0eaae7c71613c2b61c94a613b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugSubsectionRecord::DebugSubsectionRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2af">DebugSubsectionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugsubsectionrecord-cpp">DebugSubsectionRecord.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRecordData() {#a14f78bcad5e129ca65ab47f018116c28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef DebugSubsectionRecord::getRecordData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugsubsectionrecord-cpp">DebugSubsectionRecord.cpp</a>.</p>

</div>
</div>

### getRecordLength() {#aa1aa453be1d81657eb8ac13c221a7f3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DebugSubsectionRecord::getRecordLength ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugsubsectionrecord-cpp">DebugSubsectionRecord.cpp</a>.</p>

</div>
</div>

### kind() {#a29f80f60a7c507c599778b2c6ca5c53f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugSubsectionKind DebugSubsectionRecord::kind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugsubsectionrecord-cpp">DebugSubsectionRecord.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Data {#a5be48d00b18bb3e25990a759944cc753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryStreamRef llvm::codeview::DebugSubsectionRecord::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a>.</p>

</div>
</div>

### Kind {#a5282898f6ddba2d9966ca911875aec74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugSubsectionKind llvm::codeview::DebugSubsectionRecord::Kind = <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa6adf97f83acf6453d4a6a4b1070f3754">DebugSubsectionKind::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### initialize() {#a2d6b180a6430d3f25c49ab5777d63d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DebugSubsectionRecord::initialize (<a href="/web-llvm/docs/api/classes/llvm/binarystreamref">BinaryStreamRef</a> Stream, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecord">DebugSubsectionRecord</a> &amp; Info)</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugsubsectionrecord-cpp">DebugSubsectionRecord.cpp</a>.</p>


<p>References <a href="#a6fef9071bdf5369431216a15ec9295bd">DebugSubsectionRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a07e25e055f92f545f94821c4a3cbded8">llvm::BinaryStreamReader::readObject</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a03bf40efbeb72552b33026fa1608280b">llvm::BinaryStreamReader::readStreamRef</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor-aa4cf4a73737d16d115dea80ff681a08/#a5245c9fad1a0cc1f3e4e9b1106fe9dc1">llvm::VarStreamArrayExtractor&lt; codeview::DebugSubsectionRecord &gt;::operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">DebugSubsectionRecord.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/debugsubsectionrecord-cpp">DebugSubsectionRecord.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
