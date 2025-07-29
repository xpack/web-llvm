---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/format-provider-0f8c4dae2a93fb42cc485d5a034bb90a
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `format_provider` Struct Template

<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for floating point types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::format_provider&lt;T, std::enable_if_t&lt; support::detail::use_double_formatter&lt; T &gt;::value &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">llvm/Support/FormatProviders.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/support/detail/helperfunctions">HelperFunctions</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac09ed44245ea28d1512add257d986716">format</a> (const T &amp;V, llvm::raw_ostream &amp;Stream, StringRef Style)</td>
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

<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for floating point types.</p>


<p>The options string of a floating point type has the format:</p>


<p>float_options :: [style][precision] style ::  precision :: &lt;non-negative integer&gt; 0-99</p>


<hr/>



### | style | Meaning | Example | {#autotoc_md51}


## | | | Input | Output | {#autotoc_md52}


<p>| P / p | Percentage | 0.05 | 5.00% | | F / f | Fixed point | 1.0 | 1.00 | | E | Exponential with E | 100000 | 1.0E+05 | | e | Exponential with e | 100000 | 1.0e+05 |</p>


## | (empty) | Same as F / f | | | {#autotoc_md53}


<p>The default precision is 6 for exponential (E / e) and 2 for everything else.</p>


<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### format() {#ac09ed44245ea28d1512add257d986716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_double_formatter&lt; T &gt;::value &gt; &gt;::format (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; V, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Style)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faf5ccb8d51ca38e2f3329955fc0149cd4">llvm::Exponent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faa54499f98c54ce5bba679091629d0b4a">llvm::ExponentUpper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8fa4457d440870ad6d42bab9082d9bf9b61">llvm::Fixed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bae39f96702d05005822dca771333ae">llvm::getDefaultPrecision</a>, <a href="/web-llvm/docs/api/classes/llvm/support/detail/helperfunctions/#a8d13ee7422a183c8996a9e39940bbde8">llvm::support::detail::HelperFunctions::parseNumericPrecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faadaaee4b22041c27198d410c68d952c9">llvm::Percent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abadfa6a189135012fde92b57982b2ce2">llvm::write_double</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
