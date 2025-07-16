---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/format-provider-bf689c9ff674024f18c58d50fd076614
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `format_provider` Struct Template Reference

<p>Format provider for <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">TimePoint&lt;&gt;</a> <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::format_provider&lt;sys::TimePoint&lt;&gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/chrono-h">llvm/Support/Chrono.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe54668061dd2e64bf01c720689becbc">format</a> (const sys::TimePoint&lt;&gt; &amp;TP, llvm::raw_ostream &amp;OS, StringRef Style)</td>
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

<p>Format provider for <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">TimePoint&lt;&gt;</a></p>


<p>The options string is a strftime format string, with extensions:</p>


<ul class="doxyList ">
<li>L is millis: 000-999</li>
<li>f is micros: 000000-999999</li>
<li>N is nanos: 000000000 - 999999999</li>
</ul>

<p>If no options are given, the default format is "%Y-%m-%d %H:%M:%S.%N".</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/chrono-h">Chrono.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### format() {#abe54668061dd2e64bf01c720689becbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::format_provider&lt; sys::TimePoint&lt;&gt; &gt;::format (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">sys::TimePoint</a>&lt;&gt; &amp; TP, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Style)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/chrono-h">Chrono.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/chrono-h">Chrono.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
