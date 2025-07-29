---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/symbolrewriter/rewritemapparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RewriteMapParser` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SymbolRewriter::RewriteMapParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">llvm/Transforms/Utils/SymbolRewriter.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f3ae9cac7a4557bd5c1e311548cd26">parse</a> (const std::string &amp;MapFile, RewriteDescriptorList *Descriptors)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf013395b09d00197cf14353753e3a38">parse</a> (std::unique_ptr&lt; MemoryBuffer &gt; &amp;MapFile, RewriteDescriptorList *DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ddbd1312493ea13a8b1d171e674e525">parseEntry</a> (yaml::Stream &amp;Stream, yaml::KeyValueNode &amp;Entry, RewriteDescriptorList *DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a421455b3f9ade32f885305dcda8e40dd">parseRewriteFunctionDescriptor</a> (yaml::Stream &amp;Stream, yaml::ScalarNode *Key, yaml::MappingNode *Value, RewriteDescriptorList *DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4ef413190bcf499e2af533b7fe13515">parseRewriteGlobalVariableDescriptor</a> (yaml::Stream &amp;Stream, yaml::ScalarNode *Key, yaml::MappingNode *Value, RewriteDescriptorList *DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e2e63a10ea164fc553794cd81b1fa0f">parseRewriteGlobalAliasDescriptor</a> (yaml::Stream &amp;YS, yaml::ScalarNode *K, yaml::MappingNode *V, RewriteDescriptorList *DL)</td>
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


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### parse() {#a73f3ae9cac7a4557bd5c1e311548cd26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RewriteMapParser::parse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; MapFile, <a href="/web-llvm/docs/api/namespaces/llvm/symbolrewriter/#a0595c7fd39f8a8f9819d30602e4335f7">RewriteDescriptorList</a> * Descriptors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="#a73f3ae9cac7a4557bd5c1e311548cd26">parse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a73f3ae9cac7a4557bd5c1e311548cd26">parse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### parse() {#abf013395b09d00197cf14353753e3a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RewriteMapParser::parse (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &amp; MapFile, <a href="/web-llvm/docs/api/namespaces/llvm/symbolrewriter/#a0595c7fd39f8a8f9819d30602e4335f7">RewriteDescriptorList</a> * DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

### parseEntry() {#a8ddbd1312493ea13a8b1d171e674e525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RewriteMapParser::parseEntry (<a href="/web-llvm/docs/api/classes/llvm/yaml/stream">yaml::Stream</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode">yaml::KeyValueNode</a> &amp; Entry, <a href="/web-llvm/docs/api/namespaces/llvm/symbolrewriter/#a0595c7fd39f8a8f9819d30602e4335f7">RewriteDescriptorList</a> * DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

### parseRewriteFunctionDescriptor() {#a421455b3f9ade32f885305dcda8e40dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RewriteMapParser::parseRewriteFunctionDescriptor (<a href="/web-llvm/docs/api/classes/llvm/yaml/stream">yaml::Stream</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode">yaml::ScalarNode</a> * Key, <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode">yaml::MappingNode</a> * Value, <a href="/web-llvm/docs/api/namespaces/llvm/symbolrewriter/#a0595c7fd39f8a8f9819d30602e4335f7">RewriteDescriptorList</a> * DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

### parseRewriteGlobalAliasDescriptor() {#a8e2e63a10ea164fc553794cd81b1fa0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RewriteMapParser::parseRewriteGlobalAliasDescriptor (<a href="/web-llvm/docs/api/classes/llvm/yaml/stream">yaml::Stream</a> &amp; YS, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode">yaml::ScalarNode</a> * K, <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode">yaml::MappingNode</a> * V, <a href="/web-llvm/docs/api/namespaces/llvm/symbolrewriter/#a0595c7fd39f8a8f9819d30602e4335f7">RewriteDescriptorList</a> * DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

### parseRewriteGlobalVariableDescriptor() {#ad4ef413190bcf499e2af533b7fe13515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RewriteMapParser::parseRewriteGlobalVariableDescriptor (<a href="/web-llvm/docs/api/classes/llvm/yaml/stream">yaml::Stream</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode">yaml::ScalarNode</a> * Key, <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode">yaml::MappingNode</a> * Value, <a href="/web-llvm/docs/api/namespaces/llvm/symbolrewriter/#a0595c7fd39f8a8f9819d30602e4335f7">RewriteDescriptorList</a> * DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/symbolrewriter-h">SymbolRewriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/symbolrewriter-cpp">SymbolRewriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
