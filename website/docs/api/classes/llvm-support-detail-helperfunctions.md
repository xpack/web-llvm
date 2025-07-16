---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/support/detail/helperfunctions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HelperFunctions` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::support::detail::HelperFunctions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">llvm/Support/FormatProviders.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/format-provider-0f8c4dae2a93fb42cc485d5a034bb90a">format_provider&lt;T, std::enable_if_t&lt; support::detail::use_double_formatter&lt; T &gt;::value &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for floating point types. <a href="/web-llvm/docs/api/structs/llvm/format-provider-0f8c4dae2a93fb42cc485d5a034bb90a/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/format-provider-bb2727522f9037c807f0f90a70a7b85d">format_provider&lt;T, std::enable_if_t&lt; support::detail::use_integral_formatter&lt; T &gt;::value &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for integral arithmetic types. <a href="/web-llvm/docs/api/structs/llvm/format-provider-bb2727522f9037c807f0f90a70a7b85d/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/format-provider-15a9d9c43fc1c54a3bb168a7dc27cbd1">format_provider&lt;T, std::enable_if_t&lt; support::detail::use_pointer_formatter&lt; T &gt;::value &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for integral pointer types. <a href="/web-llvm/docs/api/structs/llvm/format-provider-15a9d9c43fc1c54a3bb168a7dc27cbd1/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d13ee7422a183c8996a9e39940bbde8">parseNumericPrecision</a> (StringRef Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0">HexPrintStyle</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb0f57f306baea34b019415c36bd794">consumeHexStyle</a> (StringRef &amp;Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7820283c9bbf6077dccc08dcb649e788">consumeNumHexDigits</a> (StringRef &amp;Str, HexPrintStyle Style, size_t Default)</td>
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


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<div class="doxySectionDef">

## Protected Static Functions

### consumeHexStyle() {#aefb0f57f306baea34b019415c36bd794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; HexPrintStyle &gt; llvm::support::detail::HelperFunctions::consumeHexStyle (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Str)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0aff4b514f126214ab6ab5ab9ecd249cd6">llvm::PrefixLower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a3cc854288a88eeb0ef88c4fc91ee69c6">llvm::PrefixUpper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/format-provider-bb2727522f9037c807f0f90a70a7b85d/#a34e92357abe1820d6466c4cd488b9ecb">llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_integral_formatter&lt; T &gt;::value &gt; &gt;::format</a> and <a href="/web-llvm/docs/api/structs/llvm/format-provider-15a9d9c43fc1c54a3bb168a7dc27cbd1/#a70cb2abdcca0ddaa703b3bb889405a87">llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_pointer_formatter&lt; T &gt;::value &gt; &gt;::format</a>.</p>

</div>
</div>

### consumeNumHexDigits() {#a7820283c9bbf6077dccc08dcb649e788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::support::detail::HelperFunctions::consumeNumHexDigits (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Str, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0">HexPrintStyle</a> Style, size_t Default)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae87bff309f80c39cdc11a573d25f8dd6">llvm::isPrefixedHexStyle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/format-provider-bb2727522f9037c807f0f90a70a7b85d/#a34e92357abe1820d6466c4cd488b9ecb">llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_integral_formatter&lt; T &gt;::value &gt; &gt;::format</a> and <a href="/web-llvm/docs/api/structs/llvm/format-provider-15a9d9c43fc1c54a3bb168a7dc27cbd1/#a70cb2abdcca0ddaa703b3bb889405a87">llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_pointer_formatter&lt; T &gt;::value &gt; &gt;::format</a>.</p>

</div>
</div>

### parseNumericPrecision() {#a8d13ee7422a183c8996a9e39940bbde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; size_t &gt; llvm::support::detail::HelperFunctions::parseNumericPrecision (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/format-provider-0f8c4dae2a93fb42cc485d5a034bb90a/#ac09ed44245ea28d1512add257d986716">llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_double_formatter&lt; T &gt;::value &gt; &gt;::format</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
