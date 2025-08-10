---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/stringtable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `StringTable` Struct

<p>The string table used for serializing remarks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::StringTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">llvm/Remarks/RemarkStringTable.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b672d576b8ec8aba6a7c374f98f0b77">StringTable</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbfbea2198f28e8d9ce1319c57e3b3d6">StringTable</a> (const StringTable &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable copy. <a href="#adbfbea2198f28e8d9ce1319c57e3b3d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4ff68facfd497bc8d98da0fc7b178b">StringTable</a> (StringTable &amp;&amp;)=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should be movable. <a href="#a7f4ff68facfd497bc8d98da0fc7b178b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f6807755537a42e7b93e84af1c2ba60">StringTable</a> (const ParsedStringTable &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a string table from a <a href="/web-llvm/docs/api/structs/llvm/remarks/parsedstringtable">ParsedStringTable</a>. <a href="#a6f6807755537a42e7b93e84af1c2ba60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f82b10bdbd6641190831bf7d84f714e">operator=</a> (const StringTable &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2afb4a816099f8ce44ae6ff1361516ef">operator=</a> (StringTable &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2e87ab6e6926b438f4d10e5ed1f33d6">add</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a string to the table. It returns an unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the string. <a href="#ae2e87ab6e6926b438f4d10e5ed1f33d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f58ed47dc2581869528b5478cd04ded">internalize</a> (Remark &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modify <span class="doxyComputerOutput">R</span> to use strings from this string table. <a href="#a3f58ed47dc2581869528b5478cd04ded">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e58ea3fcbfd1e8b4a5921c850507a0">serialize</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the string table to a stream. <a href="#a78e58ea3fcbfd1e8b4a5921c850507a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b58d23a2b774b24b57b6207440887af">serialize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the string table to a vector. <a href="#a2b58d23a2b774b24b57b6207440887af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b9ea0ddb6059ba10219d79eee49ea4a">StrTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string table containing all the unique strings used in the output. <a href="#a6b9ea0ddb6059ba10219d79eee49ea4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f051e00af51868a0ff39edc68c8023c">SerializedSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total size of the string table when serialized. <a href="#a2f051e00af51868a0ff39edc68c8023c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The string table used for serializing remarks.</p>


<p>This table can be for example serialized in a section to be consumed after the compilation.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StringTable() {#a1b672d576b8ec8aba6a7c374f98f0b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::StringTable::StringTable ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>.</p>


<p>Referenced by <a href="#a9f82b10bdbd6641190831bf7d84f714e">operator=</a>, <a href="#a2afb4a816099f8ce44ae6ff1361516ef">operator=</a>, <a href="#adbfbea2198f28e8d9ce1319c57e3b3d6">StringTable</a> and <a href="#a7f4ff68facfd497bc8d98da0fc7b178b">StringTable</a>.</p>

</div>
</div>

### StringTable() {#adbfbea2198f28e8d9ce1319c57e3b3d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::StringTable::StringTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disable copy.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>.</p>


<p>Reference <a href="#a1b672d576b8ec8aba6a7c374f98f0b77">StringTable</a>.</p>

</div>
</div>

### StringTable() {#a7f4ff68facfd497bc8d98da0fc7b178b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::StringTable::StringTable (<a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp;&amp;)</td>
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

<p>Should be movable.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>.</p>


<p>Reference <a href="#a1b672d576b8ec8aba6a7c374f98f0b77">StringTable</a>.</p>

</div>
</div>

### StringTable() {#a6f6807755537a42e7b93e84af1c2ba60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTable::StringTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/parsedstringtable">ParsedStringTable</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a string table from a <a href="/web-llvm/docs/api/structs/llvm/remarks/parsedstringtable">ParsedStringTable</a>.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstringtable-cpp">RemarkStringTable.cpp</a>.</p>


<p>References <a href="#ae2e87ab6e6926b438f4d10e5ed1f33d6">add</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9f82b10bdbd6641190831bf7d84f714e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTable &amp; llvm::remarks::StringTable::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>.</p>


<p>Reference <a href="#a1b672d576b8ec8aba6a7c374f98f0b77">StringTable</a>.</p>

</div>
</div>

### operator=() {#a2afb4a816099f8ce44ae6ff1361516ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTable &amp; llvm::remarks::StringTable::operator= (<a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a> &amp;&amp;)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a1b672d576b8ec8aba6a7c374f98f0b77">StringTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ae2e87ab6e6926b438f4d10e5ed1f33d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, StringRef &gt; StringTable::add (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a string to the table. It returns an unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the string.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstringtable-cpp">RemarkStringTable.cpp</a>.</p>


<p>References <a href="#a2f051e00af51868a0ff39edc68c8023c">SerializedSize</a> and <a href="#a6b9ea0ddb6059ba10219d79eee49ea4a">StrTab</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="#a3f58ed47dc2581869528b5478cd04ded">internalize</a> and <a href="#a6f6807755537a42e7b93e84af1c2ba60">StringTable</a>.</p>

</div>
</div>

### internalize() {#a3f58ed47dc2581869528b5478cd04ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringTable::internalize (<a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modify <span class="doxyComputerOutput">R</span> to use strings from this string table.</p>


<p>If the string table does not contain the strings, it adds them.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstringtable-cpp">RemarkStringTable.cpp</a>.</p>


<p>References <a href="#ae2e87ab6e6926b438f4d10e5ed1f33d6">add</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/argument/#a1659ff309b2d229a210b52d897680ecd">llvm::remarks::Argument::Key</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/argument/#a47da97597ff2702cbce42d0ba7322349">llvm::remarks::Argument::Loc</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/argument/#a43436771a3f98d9984cbd0428bc1b9a3">llvm::remarks::Argument::Val</a>.</p>

</div>
</div>

### serialize() {#a78e58ea3fcbfd1e8b4a5921c850507a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringTable::serialize (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Serialize the string table to a stream.</p>


<p>It is serialized as a little endian uint64 (the size of the table in bytes) followed by a sequence of NULL-terminated strings, where the N-th string is the string with the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> N in the StrTab map.</p>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstringtable-cpp">RemarkStringTable.cpp</a>.</p>


<p>References <a href="#a78e58ea3fcbfd1e8b4a5921c850507a0">serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad436403de744b37b7517d0a7efd891e3">llvm::remarks::BitstreamRemarkSerializerHelper::emitMetaStrTab</a> and <a href="#a78e58ea3fcbfd1e8b4a5921c850507a0">serialize</a>.</p>

</div>
</div>

### serialize() {#a2b58d23a2b774b24b57b6207440887af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; StringRef &gt; StringTable::serialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Serialize the string table to a vector.</p>


<p>This allows users to do the actual writing to file/memory/other. The string with the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> == N should be the N-th element in the vector.</p>


<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstringtable-cpp">RemarkStringTable.cpp</a>.</p>


<p>Reference <a href="#a6b9ea0ddb6059ba10219d79eee49ea4a">StrTab</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### SerializedSize {#a2f051e00af51868a0ff39edc68c8023c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::remarks::StringTable::SerializedSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Total size of the string table when serialized.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>.</p>


<p>Referenced by <a href="#ae2e87ab6e6926b438f4d10e5ed1f33d6">add</a>.</p>

</div>
</div>

### StrTab {#a6b9ea0ddb6059ba10219d79eee49ea4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned, BumpPtrAllocator&gt; llvm::remarks::StringTable::StrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string table containing all the unique strings used in the output.</p>


<p>It maps a string to an unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a>.</p>


<p>Referenced by <a href="#ae2e87ab6e6926b438f4d10e5ed1f33d6">add</a> and <a href="#a2b58d23a2b774b24b57b6207440887af">serialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkstringtable-h">RemarkStringTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkstringtable-cpp">RemarkStringTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
