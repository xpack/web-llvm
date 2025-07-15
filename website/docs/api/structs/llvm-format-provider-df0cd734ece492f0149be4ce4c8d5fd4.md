---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/format-provider-df0cd734ece492f0149be4ce4c8d5fd4
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `format_provider` Struct Template Reference

<p>Allow printing <a href="/web-llvm/docs/api/classes/llvm/json/value">json::Value</a> with <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">formatv()</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::format_provider&lt;llvm::json::Value&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">llvm/Support/JSON.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190aff78bb7ee7618b561151f06dd5cd">format</a> (const llvm::json::Value &amp;, raw_ostream &amp;, StringRef)</td>
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

<p>Allow printing <a href="/web-llvm/docs/api/classes/llvm/json/value">json::Value</a> with <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">formatv()</a>.</p>


<p>The default style is basic/compact formatting, like operator&lt;&lt;. A format string like formatv("{0:2}", <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>) pretty-prints with indent 2.</p>


<p>Definition at line 1098 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### format() {#a190aff78bb7ee7618b561151f06dd5cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::format_provider&lt; llvm::json::Value &gt;::format (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/value">llvm::json::Value</a> &amp; E, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Options)</td>
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



<p>Declaration at line 1099 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#ad132dccf457f071b5854a8c94135e7c2">llvm::json::OStream::value</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
