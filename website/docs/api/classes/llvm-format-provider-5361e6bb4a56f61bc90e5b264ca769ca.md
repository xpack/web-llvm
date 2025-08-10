---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/format-provider-5361e6bb4a56f61bc90e5b264ca769ca
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `format_provider` Class Template

<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for ranges. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IterT&gt;
class llvm::format_provider&lt;llvm::iterator_range&lt; IterT &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">llvm/Support/FormatProviders.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76e415cb6d316a05937ef06697be818e">value</a> = typename std::iterator_traits&lt; IterT &gt;::value_type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abbf6dcd12697c330a44aa62117b7f6da">format</a> (const llvm::iterator_range&lt; IterT &gt; &amp;V, llvm::raw_ostream &amp;Stream, StringRef Style)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c69bec2571fc4b49b84a87f58b0a99c">consumeOneOption</a> (StringRef &amp;Style, char Indicator, StringRef Default)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a231623eea0700ef7310804dc2c34a715">parseOptions</a> (StringRef Style) -&gt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
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

<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for ranges.</p>


<p>This will print an arbitrary range as a delimited sequence of items.</p>


<p>The options string of a range type has the grammar:</p>


<p>range_style ::= [separator] [element_style] separator ::= "$" delimeted_expr element_style ::= "@" delimeted_expr delimeted_expr ::= "[" expr "]" | "(" expr ")" | "&lt;" expr "&gt;" expr ::= &lt;any string not containing delimeter&gt;</p>


<p>where the separator expression is the string to insert between consecutive items in the range and the argument expression is the Style specification to be used when formatting the underlying type. The default separator if unspecified is ' ' (space). The syntax of the argument expression follows whatever grammar is dictated by the format provider or format adapter used to format the value type.</p>


<p>Note that attempting to format an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt;T&gt;</span> where no format provider can be found for T will result in a compile error.</p>


<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### value {#a76e415cb6d316a05937ef06697be818e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::format_provider&lt; llvm::iterator_range&lt; IterT &gt; &gt;::value =  typename std::iterator_traits&lt;IterT&gt;::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### format() {#abbf6dcd12697c330a44aa62117b7f6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::format_provider&lt; llvm::iterator_range&lt; IterT &gt; &gt;::format (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/iterator-range">llvm::iterator_range</a>&lt; IterT &gt; &amp; V, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Style)</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/support/detail/#a7b7c745d9aa9e637371b87e5905f3fdc">llvm::support::detail::build_format_adapter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### consumeOneOption() {#a1c69bec2571fc4b49b84a87f58b0a99c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::format_provider&lt; llvm::iterator_range&lt; IterT &gt; &gt;::consumeOneOption (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Style, char Indicator, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Default)</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>

</div>
</div>

### parseOptions() {#a231623eea0700ef7310804dc2c34a715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; StringRef, StringRef &gt; llvm::format_provider&lt; llvm::iterator_range&lt; IterT &gt; &gt;::parseOptions (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Style)</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
