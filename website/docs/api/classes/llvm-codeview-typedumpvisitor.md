---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/typedumpvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TypeDumpVisitor` Class

<p>Dumper for CodeView type streams found in <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> object files and PDB files. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::codeview::TypeDumpVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">llvm/DebugInfo/CodeView/TypeDumpVisitor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typevisitorcallbacks">TypeVisitorCallbacks</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f36bbc238bba20f2abd0da3b49f9275">TypeDumpVisitor</a> (TypeCollection &amp;TpiTypes, ScopedPrinter *W, bool PrintRecordBytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed3cbd5a284d43852203231c865d301">setIpiTypes</a> (TypeCollection &amp;Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When dumping types from an IPI stream in a PDB, a type index may refer to a type or an item <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#aeed3cbd5a284d43852203231c865d301">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e7948ed7eb93e7b89c76a850a9c32a3">printTypeIndex</a> (StringRef FieldName, TypeIndex TI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae29dde96431d4331ee7eb6006b77d843">printItemIndex</a> (StringRef FieldName, TypeIndex TI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c74870b34ef151a36efc97cddfaa03">visitUnknownType</a> (CVType &amp;Record) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Action to take on unknown types. By default, they are ignored. <a href="#a67c74870b34ef151a36efc97cddfaa03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a573db82ee8c5c16c37d3a3b0293920ea">visitUnknownMember</a> (CVMemberRecord &amp;Record) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1609c4919cf4b671bdbabe8b5b91ab3">visitTypeBegin</a> (CVType &amp;Record) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Paired begin/end actions for all types. <a href="#af1609c4919cf4b671bdbabe8b5b91ab3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418b79f4288d791e538fa1cf1c4a6960">visitTypeBegin</a> (CVType &amp;Record, TypeIndex Index) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a390a4a6e3ed8fd6c7a8092c748bfc040">visitTypeEnd</a> (CVType &amp;Record) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa470e9dab06e163ce2b08a65ad83fc2">visitMemberBegin</a> (CVMemberRecord &amp;Record) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67448cf4a26f3f4eda72cd2bacdec169">visitMemberEnd</a> (CVMemberRecord &amp;Record) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a5428087c4d166e1da2abb1f250b0e">printMemberAttributes</a> (MemberAttributes Attrs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c98ee2f143b3d4408dee9e15f926302">printMemberAttributes</a> (MemberAccess Access, MethodKind Kind, MethodOptions Options)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35984e88bf24c63efa0bab3801b6fdd5">getSourceTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the database of indices for the stream that we are dumping. <a href="#a35984e88bf24c63efa0bab3801b6fdd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fa27afe01ef06cffb2347f27e78f8f">W</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6555da2867c9048175fa4b7587ace7e4">PrintRecordBytes</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c229246d84ae9e225374e8e7b3b0af7">TpiTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5692306edcec942dcddfd3219efc46e6">IpiTypes</a> = nullptr</td>
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

<p>Dumper for CodeView type streams found in <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> object files and PDB files.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TypeDumpVisitor() {#a7f36bbc238bba20f2abd0da3b49f9275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::TypeDumpVisitor::TypeDumpVisitor (<a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a> &amp; TpiTypes, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> * W, bool PrintRecordBytes)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printItemIndex() {#ae29dde96431d4331ee7eb6006b77d843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeDumpVisitor::printItemIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aff82033771977413104f16ed617d2b4f">llvm::codeview::printTypeIndex</a>.</p>

</div>
</div>

### printTypeIndex() {#a3e7948ed7eb93e7b89c76a850a9c32a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeDumpVisitor::printTypeIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aff82033771977413104f16ed617d2b4f">llvm::codeview::printTypeIndex</a>.</p>

</div>
</div>

### setIpiTypes() {#aeed3cbd5a284d43852203231c865d301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::codeview::TypeDumpVisitor::setIpiTypes (<a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a> &amp; Types)</td>
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

<p>When dumping types from an IPI stream in a PDB, a type index may refer to a type or an item <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>The dumper will lookup the "name" of the index in the item database if appropriate. If ItemDB is null, it will use TypeDB, which is correct when dumping types from an object file (/Z7).</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>.</p>

</div>
</div>

### visitMemberBegin() {#afa470e9dab06e163ce2b08a65ad83fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeDumpVisitor::visitMemberBegin (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp/#a80b7c4ad3b2bd0c43c8f004ab549476d">getLeafTypeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp/#ad635b4c1cbff12fbcc5bd82bccc5e4f3">LeafTypeNames</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitMemberEnd() {#a67448cf4a26f3f4eda72cd2bacdec169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeDumpVisitor::visitMemberEnd (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a746052f3a8d6068791b8fc33a2dd0c64">llvm::codeview::getBytesAsCharacters</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitTypeBegin() {#af1609c4919cf4b671bdbabe8b5b91ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeDumpVisitor::visitTypeBegin (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Paired begin/end actions for all types.</p>


<p>Receives all record data, including the fixed-length record prefix.</p>


<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a07d13e00998a0b341376f2fbd3a0ed54">llvm::codeview::TypeIndex::fromArrayIndex</a> and <a href="#af1609c4919cf4b671bdbabe8b5b91ab3">visitTypeBegin</a>.</p>


<p>Referenced by <a href="#af1609c4919cf4b671bdbabe8b5b91ab3">visitTypeBegin</a>.</p>

</div>
</div>

### visitTypeBegin() {#a418b79f4288d791e538fa1cf1c4a6960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeDumpVisitor::visitTypeBegin (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp/#a80b7c4ad3b2bd0c43c8f004ab549476d">getLeafTypeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp/#ad635b4c1cbff12fbcc5bd82bccc5e4f3">LeafTypeNames</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitTypeEnd() {#a390a4a6e3ed8fd6c7a8092c748bfc040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeDumpVisitor::visitTypeEnd (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a746052f3a8d6068791b8fc33a2dd0c64">llvm::codeview::getBytesAsCharacters</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitUnknownMember() {#a573db82ee8c5c16c37d3a3b0293920ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeDumpVisitor::visitUnknownMember (<a href="/web-llvm/docs/api/structs/llvm/codeview/cvmemberrecord">CVMemberRecord</a> &amp; Record)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitUnknownType() {#a67c74870b34ef151a36efc97cddfaa03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeDumpVisitor::visitUnknownType (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Record)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Action to take on unknown types. By default, they are ignored.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp/#ad635b4c1cbff12fbcc5bd82bccc5e4f3">LeafTypeNames</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getSourceTypes() {#a35984e88bf24c63efa0bab3801b6fdd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeCollection &amp; llvm::codeview::TypeDumpVisitor::getSourceTypes ()</td>
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

<p>Get the database of indices for the stream that we are dumping.</p>


<p>If ItemDB is set, then we must be dumping an item (IPI) stream. This will also always get the appropriate DB for printing item names.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>.</p>

</div>
</div>

### printMemberAttributes() {#ac4a5428087c4d166e1da2abb1f250b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeDumpVisitor::printMemberAttributes (<a href="/web-llvm/docs/api/structs/llvm/codeview/memberattributes">MemberAttributes</a> Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

### printMemberAttributes() {#a0c98ee2f143b3d4408dee9e15f926302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeDumpVisitor::printMemberAttributes (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a86888a0082bafa16b982170695ebb881">MemberAccess</a> Access, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a> Kind, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626f">MethodOptions</a> Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>, definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IpiTypes {#a5692306edcec942dcddfd3219efc46e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeCollection* llvm::codeview::TypeDumpVisitor::IpiTypes = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>.</p>

</div>
</div>

### PrintRecordBytes {#a6555da2867c9048175fa4b7587ace7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::TypeDumpVisitor::PrintRecordBytes = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>.</p>

</div>
</div>

### TpiTypes {#a6c229246d84ae9e225374e8e7b3b0af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeCollection&amp; llvm::codeview::TypeDumpVisitor::TpiTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>.</p>

</div>
</div>

### W {#ae1fa27afe01ef06cffb2347f27e78f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedPrinter* llvm::codeview::TypeDumpVisitor::W</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedumpvisitor-h">TypeDumpVisitor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typedumpvisitor-cpp">TypeDumpVisitor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
