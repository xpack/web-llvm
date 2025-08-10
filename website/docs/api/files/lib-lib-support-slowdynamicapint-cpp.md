---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/slowdynamicapint-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `SlowDynamicAPInt.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">llvm/ADT/SlowDynamicAPInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">llvm/ADT/Hashing.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86cb80d1cfe9f340e28760d24cfef373">getMaxWidth</a> (const APInt &amp;A, const APInt &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a260fae637de414fe27ae28483df4f379">runOpWithExpandOnOverflow</a> (const APInt &amp;A, const APInt &amp;B, function_ref&lt; APInt(const APInt &amp;, const APInt &amp;, bool &amp;Overflow)&gt; Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bring a and b to have the same width and then call <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op(a, b, overflow)</a>. <a href="#a260fae637de414fe27ae28483df4f379">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getMaxWidth() {#a86cb80d1cfe9f340e28760d24cfef373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getMaxWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; B)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a4f198a2d2b22d598b78a504e397cee1a">llvm::detail::ceilDiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a88f3af76e71063ffac341ed1ac69929d">llvm::detail::floorDiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a77acb98b86953c95e4bc46b380e89b09">llvm::detail::gcd</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a73d90fea50ec5a75c894d67fbe2d3b17">llvm::detail::SlowDynamicAPInt::operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#ad6b9ab408d61ca138628e070cd6bd93a">llvm::detail::SlowDynamicAPInt::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a44e9d3a334499824e1ff938254e597bf">llvm::detail::SlowDynamicAPInt::operator&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a7d50644f90a55900013be55fcb257f42">llvm::detail::SlowDynamicAPInt::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a7c66825db234e73dedb2c3799bfa3f12">llvm::detail::SlowDynamicAPInt::operator&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#aed7171fdf762b090dd88be0697e652be">llvm::detail::SlowDynamicAPInt::operator&gt;=</a> and <a href="#a260fae637de414fe27ae28483df4f379">runOpWithExpandOnOverflow</a>.</p>

</div>
</div>

### runOpWithExpandOnOverflow() {#a260fae637de414fe27ae28483df4f379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt runOpWithExpandOnOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;, bool &amp;Overflow)&gt; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bring a and b to have the same width and then call <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op(a, b, overflow)</a>.</p>


<hr/>



### Arithmetic operators {#autotoc_md108}


<p>If the overflow bit becomes set, resize a and b to double the width and call <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op(a, b, overflow)</a>, returning its result. The operation with double widths should not also overflow.</p>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a86cb80d1cfe9f340e28760d24cfef373">getMaxWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a0fc607373675fde318c740e7bc810ff9">llvm::detail::SlowDynamicAPInt::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#afbe3b990798e79cc464f39472699112b">llvm::detail::SlowDynamicAPInt::operator+</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a0a7d474fe2bca892a50861086e90cf07">llvm::detail::SlowDynamicAPInt::operator-</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a9284a4735992c0b86c3827ecbd0d0861">llvm::detail::SlowDynamicAPInt::operator/</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
