---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/format-provider-15a9d9c43fc1c54a3bb168a7dc27cbd1
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `format_provider` Struct Template

<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for integral pointer types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::format_provider&lt;T, std::enable_if_t&lt; support::detail::use_pointer_formatter&lt; T &gt;::value &gt;&gt; { ... }
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a70cb2abdcca0ddaa703b3bb889405a87">format</a> (const T &amp;V, llvm::raw_ostream &amp;Stream, StringRef Style)</td>
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

<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for integral pointer types.</p>


<p>The options string of a pointer type has the grammar:</p>


<p>pointer_options :: [style][precision] style ::  digits :: &lt;non-negative integer&gt; 0-sizeof(void*)</p>


<hr/>



### | S | Meaning | Example | {#autotoc_md44}


## | | | Input | Output | {#autotoc_md45}


<p>| x- | Hex no prefix, lower | 0xDEADBEEF | deadbeef | | X- | Hex no prefix, upper | 0xDEADBEEF | DEADBEEF | | x+ / x | Hex + prefix, lower | 0xDEADBEEF | 0xdeadbeef | | X+ / X | Hex + prefix, upper | 0xDEADBEEF | 0xDEADBEEF |</p>


## | (empty) | Same as X+ / X | | | {#autotoc_md46}


<p>The default precision is the number of nibbles in a machine word, and in all cases indicates the minimum number of nibbles to print.</p>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### format() {#a70cb2abdcca0ddaa703b3bb889405a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_pointer_formatter&lt; T &gt;::value &gt; &gt;::format (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; V, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Style)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/support/detail/helperfunctions/#aefb0f57f306baea34b019415c36bd794">llvm::support::detail::HelperFunctions::consumeHexStyle</a>, <a href="/web-llvm/docs/api/classes/llvm/support/detail/helperfunctions/#a7820283c9bbf6077dccc08dcb649e788">llvm::support::detail::HelperFunctions::consumeNumHexDigits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a3cc854288a88eeb0ef88c4fc91ee69c6">llvm::PrefixUpper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab1aedb7c876c118bfb3b40eb756db6f9">llvm::write_hex</a>.</p>

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
