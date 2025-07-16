---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/formatv-object-base
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `formatv_object_base` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::formatv_object_base { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/formatv-object">formatv_object&lt;Tuple&gt;</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ecf8eb658bde7495b1e140fc67668d4">formatv_object_base</a> (StringRef Fmt, ArrayRef&lt; support::detail::format_adapter * &gt; Adapters, bool Validate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c21ad581f8118b36c74491bb6e6e55">formatv_object_base</a> (formatv_object_base const &amp;rhs)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fbeebe4e188bdddf6cfec3f89f7c6fd">formatv_object_base</a> (formatv_object_base &amp;&amp;rhs)=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a049f9b544d4b25131f1315ade59ae85c">operator SmallString&lt; N &gt;</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55fca63540d9b9771aab2e2ef22102cd">operator std::string</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1909dc6f7823cf0b4c30885197406471">format</a> (raw_ostream &amp;S) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf577b5205c929de4042770a32a9517">str</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac64f67e3ce4b19a97cf56329d93808f7">sstr</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt;</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454b6b825ab87db9fd04519ef66825dd">Fmt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/support/detail/format-adapter">support::detail::format_adapter</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c3d07d59e6f327f85e31c78a38db685">Adapters</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e52ddd60b2a1047b17ad0c5c5122dc">Validate</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/replacementitem">ReplacementItem</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3daaa42a47524368df5608cccd1f6b66">parseFormatString</a> (StringRef Fmt, size_t NumArgs, bool Validate)</td>
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


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### formatv\_object\_base() {#a5ecf8eb658bde7495b1e140fc67668d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatv_object_base::formatv_object_base (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Fmt, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/support/detail/format-adapter">support::detail::format_adapter</a> * &gt; Adapters, bool Validate)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>References <a href="#a9c3d07d59e6f327f85e31c78a38db685">Adapters</a>, <a href="#a454b6b825ab87db9fd04519ef66825dd">Fmt</a> and <a href="#a03e52ddd60b2a1047b17ad0c5c5122dc">Validate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/formatv-object/#a3b24fb21aee12344fdaba1a14e3d7459">llvm::formatv_object&lt; Tuple &gt;::formatv_object</a>, <a href="/web-llvm/docs/api/classes/llvm/formatv-object/#a974591deeb830e3934264cf6b34fefbe">llvm::formatv_object&lt; Tuple &gt;::formatv_object</a>, <a href="#a1fbeebe4e188bdddf6cfec3f89f7c6fd">formatv_object_base</a> and <a href="#aa5c21ad581f8118b36c74491bb6e6e55">formatv_object_base</a>.</p>

</div>
</div>

### formatv\_object\_base() {#aa5c21ad581f8118b36c74491bb6e6e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatv_object_base::formatv_object_base (<a href="/web-llvm/docs/api/classes/llvm/formatv-object-base">formatv_object_base</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; rhs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Reference <a href="#a5ecf8eb658bde7495b1e140fc67668d4">formatv_object_base</a>.</p>

</div>
</div>

### formatv\_object\_base() {#a1fbeebe4e188bdddf6cfec3f89f7c6fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatv_object_base::formatv_object_base (<a href="/web-llvm/docs/api/classes/llvm/formatv-object-base">formatv_object_base</a> &amp;&amp; rhs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Reference <a href="#a5ecf8eb658bde7495b1e140fc67668d4">formatv_object_base</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator SmallString&lt; N &gt;() {#a049f9b544d4b25131f1315ade59ae85c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatv_object_base::operator SmallString&lt; N &gt; ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Reference <a href="#ac64f67e3ce4b19a97cf56329d93808f7">sstr</a>.</p>

</div>
</div>

### operator std::string() {#a55fca63540d9b9771aab2e2ef22102cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatv_object_base::operator std::string ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Reference <a href="#aaaf577b5205c929de4042770a32a9517">str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### format() {#a1909dc6f7823cf0b4c30885197406471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::formatv_object_base::format (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; S)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>References <a href="#a9c3d07d59e6f327f85e31c78a38db685">Adapters</a>, <a href="#a454b6b825ab87db9fd04519ef66825dd">Fmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3ad7da1b76e5799f53a399b7a96ba67437">llvm::Literal</a>, <a href="#a3daaa42a47524368df5608cccd1f6b66">parseFormatString</a> and <a href="#a03e52ddd60b2a1047b17ad0c5c5122dc">Validate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ac5283ab203049acfffb2dd233f816402">llvm::raw_ostream::operator&lt;&lt;</a>.</p>

</div>
</div>

### sstr() {#ac64f67e3ce4b19a97cf56329d93808f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt; N &gt; llvm::formatv_object_base::sstr ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Referenced by <a href="#a049f9b544d4b25131f1315ade59ae85c">operator SmallString&lt; N &gt;</a>.</p>

</div>
</div>

### str() {#aaaf577b5205c929de4042770a32a9517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::formatv_object_base::str ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>.</p>


<p>Referenced by <a href="#a55fca63540d9b9771aab2e2ef22102cd">operator std::string</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Adapters {#a9c3d07d59e6f327f85e31c78a38db685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;support::detail::format_adapter *&gt; llvm::formatv_object_base::Adapters</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Referenced by <a href="#a1909dc6f7823cf0b4c30885197406471">format</a>, <a href="/web-llvm/docs/api/classes/llvm/formatv-object/#a3b24fb21aee12344fdaba1a14e3d7459">llvm::formatv_object&lt; Tuple &gt;::formatv_object</a> and <a href="#a5ecf8eb658bde7495b1e140fc67668d4">formatv_object_base</a>.</p>

</div>
</div>

### Fmt {#a454b6b825ab87db9fd04519ef66825dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::formatv_object_base::Fmt</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Referenced by <a href="#a1909dc6f7823cf0b4c30885197406471">format</a>, <a href="/web-llvm/docs/api/classes/llvm/formatv-object/#a974591deeb830e3934264cf6b34fefbe">llvm::formatv_object&lt; Tuple &gt;::formatv_object</a>, <a href="#a5ecf8eb658bde7495b1e140fc67668d4">formatv_object_base</a> and <a href="#a3daaa42a47524368df5608cccd1f6b66">parseFormatString</a>.</p>

</div>
</div>

### Validate {#a03e52ddd60b2a1047b17ad0c5c5122dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::formatv_object_base::Validate</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Referenced by <a href="#a1909dc6f7823cf0b4c30885197406471">format</a>, <a href="/web-llvm/docs/api/classes/llvm/formatv-object/#a974591deeb830e3934264cf6b34fefbe">llvm::formatv_object&lt; Tuple &gt;::formatv_object</a>, <a href="#a5ecf8eb658bde7495b1e140fc67668d4">formatv_object_base</a> and <a href="#a3daaa42a47524368df5608cccd1f6b66">parseFormatString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### parseFormatString() {#a3daaa42a47524368df5608cccd1f6b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; ReplacementItem, 2 &gt; formatv_object_base::parseFormatString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Fmt, size_t NumArgs, bool Validate)</td>
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



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp">FormatVariadic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a454b6b825ab87db9fd04519ef66825dd">Fmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a> and <a href="#a03e52ddd60b2a1047b17ad0c5c5122dc">Validate</a>.</p>


<p>Referenced by <a href="#a1909dc6f7823cf0b4c30885197406471">format</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp">FormatVariadic.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
