---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/rewritebuffer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RewriteBuffer` Class

<p><a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a> - As code is rewritten, SourceBuffer's from the original input with modifications get a new <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a> associated with them. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RewriteBuffer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">llvm/ADT/RewriteBuffer.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab672c063a54889c173d84d3ef5e40942">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/rewriterope/#aae0632a23e919ec6285c0cd7e7839ce5">RewriteRope::const_iterator</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6858b60c9b365d29f2cea3e024bf8e62">clang::Rewriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab672c063a54889c173d84d3ef5e40942">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a856895feec13424f426516cba22ec8df">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab672c063a54889c173d84d3ef5e40942">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f93f5b96aae17e8e801734dd13f3ea6">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b6a74c2bda71f4a5184e57239c3bda4">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad911b0b688a9a92ea8ef85f80cfa9c1">Initialize</a> (const char *BufStart, const char *BufEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize - Start this rewrite buffer out with a copy of the unmodified input buffer. <a href="#aad911b0b688a9a92ea8ef85f80cfa9c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1e891f99ade3d225acd7c67cb41522">Initialize</a> (StringRef Input)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b72d3db59db1731c63217c291929ced">write</a> (raw_ostream &amp;Stream) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write to <span class="doxyComputerOutput">Stream</span> the result of applying all changes to the original buffer. <a href="#a0b72d3db59db1731c63217c291929ced">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08eea0e9e695bc7d1e025b211aebeae9">RemoveText</a> (unsigned OrigOffset, unsigned Size, bool removeLineIfEmpty=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RemoveText - Remove the specified text. <a href="#a08eea0e9e695bc7d1e025b211aebeae9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b5f8de8f5f0ee46177d2cf2281ea475">InsertText</a> (unsigned OrigOffset, StringRef Str, bool InsertAfter=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InsertText - Insert some text at the specified point, where the offset in the buffer is specified relative to the original SourceBuffer. <a href="#a3b5f8de8f5f0ee46177d2cf2281ea475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c5e6f816e760c0e7299045e9143c072">InsertTextBefore</a> (unsigned OrigOffset, StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InsertTextBefore - Insert some text before the specified point, where the offset in the buffer is specified relative to the original SourceBuffer. <a href="#a4c5e6f816e760c0e7299045e9143c072">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5c73017f12ea37edde955b7ddc07ba">InsertTextAfter</a> (unsigned OrigOffset, StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InsertTextAfter - Insert some text at the specified point, where the offset in the buffer is specified relative to the original SourceBuffer. <a href="#afd5c73017f12ea37edde955b7ddc07ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4da15ad7c70b2c9ac934adf213819f7">ReplaceText</a> (unsigned OrigOffset, unsigned OrigLength, StringRef NewStr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReplaceText - This method replaces a range of characters in the input buffer with a new string. <a href="#af4da15ad7c70b2c9ac934adf213819f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac435e5367bbd5c22f840544b24d45d">getMappedOffset</a> (unsigned OrigOffset, bool AfterInserts=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMappedOffset - Given an offset into the original SourceBuffer that this <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a> is based on, map it into the offset space of the <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a>. <a href="#a2ac435e5367bbd5c22f840544b24d45d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf8b6d875840a0fecc696f5912cb6f32">AddInsertDelta</a> (unsigned OrigOffset, int Change)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddInsertDelta - When an insertion is made at a position, this method is used to record that information. <a href="#adf8b6d875840a0fecc696f5912cb6f32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2230f1f81e47afde2a09347d9eba47ab">AddReplaceDelta</a> (unsigned OrigOffset, int Change)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddReplaceDelta - When a replacement/deletion is made at a position, this method is used to record that information. <a href="#a2230f1f81e47afde2a09347d9eba47ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a393d3821d8cf8f206ad8bd114c2491b8">Deltas</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deltas - Keep track of all the deltas in the source code due to insertions and deletions. <a href="#a393d3821d8cf8f206ad8bd114c2491b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rewriterope">RewriteRope</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c10b38c93e216d7a34529edd3d4ec47">Buffer</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a> - As code is rewritten, SourceBuffer's from the original input with modifications get a new <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a> associated with them.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a> captures the modified text itself as well as information used to map between SourceLocation's in the original input and offsets in the <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a>. For example, if text is inserted into the buffer, any locations after the insertion point have to be mapped.</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#ab672c063a54889c173d84d3ef5e40942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RewriteBuffer::iterator =  RewriteRope::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### clang::Rewriter {#a6858b60c9b365d29f2cea3e024bf8e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class clang::Rewriter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>


<p>Reference <a href="#a6858b60c9b365d29f2cea3e024bf8e62">clang::Rewriter</a>.</p>


<p>Referenced by <a href="#a6858b60c9b365d29f2cea3e024bf8e62">clang::Rewriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a856895feec13424f426516cba22ec8df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::RewriteBuffer::begin ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>


<p>Referenced by <a href="#a08eea0e9e695bc7d1e025b211aebeae9">RemoveText</a> and <a href="#a0b72d3db59db1731c63217c291929ced">write</a>.</p>

</div>
</div>

### end() {#a0f93f5b96aae17e8e801734dd13f3ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::RewriteBuffer::end ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>


<p>Referenced by <a href="#a08eea0e9e695bc7d1e025b211aebeae9">RemoveText</a> and <a href="#a0b72d3db59db1731c63217c291929ced">write</a>.</p>

</div>
</div>

### Initialize() {#aad911b0b688a9a92ea8ef85f80cfa9c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RewriteBuffer::Initialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BufStart, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BufEnd)</td>
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

<p>Initialize - Start this rewrite buffer out with a copy of the unmodified input buffer.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>

</div>
</div>

### Initialize() {#acc1e891f99ade3d225acd7c67cb41522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RewriteBuffer::Initialize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Input)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>


<p>Reference <a href="#acc1e891f99ade3d225acd7c67cb41522">Initialize</a>.</p>


<p>Referenced by <a href="#acc1e891f99ade3d225acd7c67cb41522">Initialize</a>.</p>

</div>
</div>

### InsertText() {#a3b5f8de8f5f0ee46177d2cf2281ea475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RewriteBuffer::InsertText (unsigned OrigOffset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, bool InsertAfter=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>InsertText - Insert some text at the specified point, where the offset in the buffer is specified relative to the original SourceBuffer.</p>


<p>The text is inserted after the specified location.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewritebuffer-cpp">RewriteBuffer.cpp</a>.</p>


<p>Referenced by <a href="#afd5c73017f12ea37edde955b7ddc07ba">InsertTextAfter</a> and <a href="#a4c5e6f816e760c0e7299045e9143c072">InsertTextBefore</a>.</p>

</div>
</div>

### InsertTextAfter() {#afd5c73017f12ea37edde955b7ddc07ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RewriteBuffer::InsertTextAfter (unsigned OrigOffset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>InsertTextAfter - Insert some text at the specified point, where the offset in the buffer is specified relative to the original SourceBuffer.</p>


<p>The text is inserted after the specified location.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>


<p>Reference <a href="#a3b5f8de8f5f0ee46177d2cf2281ea475">InsertText</a>.</p>

</div>
</div>

### InsertTextBefore() {#a4c5e6f816e760c0e7299045e9143c072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RewriteBuffer::InsertTextBefore (unsigned OrigOffset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>InsertTextBefore - Insert some text before the specified point, where the offset in the buffer is specified relative to the original SourceBuffer.</p>


<p>The text is inserted before the specified location. This is method is the same as InsertText with "InsertAfter == false".</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>


<p>Reference <a href="#a3b5f8de8f5f0ee46177d2cf2281ea475">InsertText</a>.</p>

</div>
</div>

### RemoveText() {#a08eea0e9e695bc7d1e025b211aebeae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RewriteBuffer::RemoveText (unsigned OrigOffset, unsigned Size, bool removeLineIfEmpty=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RemoveText - Remove the specified text.</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewritebuffer-cpp">RewriteBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a856895feec13424f426516cba22ec8df">begin</a>, <a href="#a0f93f5b96aae17e8e801734dd13f3ea6">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/rewritebuffer-cpp/#a9b7312ca538e0925db1cd79f0a47ef06">isWhitespaceExceptNL</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### ReplaceText() {#af4da15ad7c70b2c9ac934adf213819f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RewriteBuffer::ReplaceText (unsigned OrigOffset, unsigned OrigLength, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NewStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReplaceText - This method replaces a range of characters in the input buffer with a new string.</p>


<p>This is effectively a combined "remove/insert" operation.</p>


<p>This is effectively a combined "remove+insert" operation.</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewritebuffer-cpp">RewriteBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### size() {#a4b6a74c2bda71f4a5184e57239c3bda4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RewriteBuffer::size ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>

</div>
</div>

### write() {#a0b72d3db59db1731c63217c291929ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; RewriteBuffer::write (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write to <span class="doxyComputerOutput">Stream</span> the result of applying all changes to the original buffer.</p>


<p>Note that it isn't safe to use this function to overwrite memory mapped files in-place (PR17960). Consider using a higher-level utility such as Rewriter::overwriteChangedFiles() instead.</p>


<p>The original buffer is not actually changed.</p>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewritebuffer-cpp">RewriteBuffer.cpp</a>.</p>


<p>References <a href="#a856895feec13424f426516cba22ec8df">begin</a>, <a href="#a0f93f5b96aae17e8e801734dd13f3ea6">end</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AddInsertDelta() {#adf8b6d875840a0fecc696f5912cb6f32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RewriteBuffer::AddInsertDelta (unsigned OrigOffset, int Change)</td>
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

<p>AddInsertDelta - When an insertion is made at a position, this method is used to record that information.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>

</div>
</div>

### AddReplaceDelta() {#a2230f1f81e47afde2a09347d9eba47ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RewriteBuffer::AddReplaceDelta (unsigned OrigOffset, int Change)</td>
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

<p>AddReplaceDelta - When a replacement/deletion is made at a position, this method is used to record that information.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>

</div>
</div>

### getMappedOffset() {#a2ac435e5367bbd5c22f840544b24d45d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RewriteBuffer::getMappedOffset (unsigned OrigOffset, bool AfterInserts=false)</td>
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

<p>getMappedOffset - Given an offset into the original SourceBuffer that this <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a> is based on, map it into the offset space of the <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer">RewriteBuffer</a>.</p>


<p>If AfterInserts is true and if the OrigOffset indicates a position where text is inserted, the location returned will be after any inserted text at the position.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buffer {#a3c10b38c93e216d7a34529edd3d4ec47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RewriteRope llvm::RewriteBuffer::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>

</div>
</div>

### Deltas {#a393d3821d8cf8f206ad8bd114c2491b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaTree llvm::RewriteBuffer::Deltas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deltas - Keep track of all the deltas in the source code due to insertions and deletions.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewritebuffer-h">RewriteBuffer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/rewritebuffer-cpp">RewriteBuffer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
