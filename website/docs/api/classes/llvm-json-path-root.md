---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/json/path/root
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Root` Class

<p>The root is the trivial <a href="/web-llvm/docs/api/classes/llvm/json/path">Path</a> to the root value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::json::Path::Root { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">llvm/Support/JSON.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f1992d3ed371fddb365bf13ed962aa6">Path::report</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acee898545ed238ee925d9cd23787fde6">Root</a> (llvm::StringRef Name="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af78bfa2d5bb88f88410223755bcd20c9">Root</a> (Root &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7857709c798bd7d5e7983f647bab1104">Root</a> (const Root &amp;)=delete</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/json/path/root">Root</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac89989a09764c1e89fe33de340086d43">operator=</a> (Root &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/json/path/root">Root</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31bf7cacb46f1f2684523d6c8065d1a9">operator=</a> (const Root &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c80beebd4079b6f29718231592ef00">getError</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the last error reported, or else a generic error. <a href="#a67c80beebd4079b6f29718231592ef00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a064c6a4f075f7dbdbdc16e791de1168a">printErrorContext</a> (const Value &amp;, llvm::raw_ostream &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the root value with the error shown inline as a comment. <a href="#a064c6a4f075f7dbdbdc16e791de1168a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c19ca8129c3ae08ae2324e2222e7446">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">llvm::StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa82066fc9eb9117af4793e4a391f6516">ErrorMessage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; Path::Segment &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa02a6e98e0001ae6a9c8af1a7694b77">ErrorPath</a></td>
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

<p>The root is the trivial <a href="/web-llvm/docs/api/classes/llvm/json/path">Path</a> to the root value.</p>


<p>It also stores the latest reported error and the path where it occurred.</p>


<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Path::report {#a1f1992d3ed371fddb365bf13ed962aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/classes/llvm/stringliteral">llvm::StringLiteral</a> Message</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Root() {#acee898545ed238ee925d9cd23787fde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::json::Path::Root::Root (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name="")</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Referenced by <a href="#a31bf7cacb46f1f2684523d6c8065d1a9">operator=</a>, <a href="#ac89989a09764c1e89fe33de340086d43">operator=</a>, <a href="#a7857709c798bd7d5e7983f647bab1104">Root</a> and <a href="#af78bfa2d5bb88f88410223755bcd20c9">Root</a>.</p>

</div>
</div>

### Root() {#af78bfa2d5bb88f88410223755bcd20c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::json::Path::Root::Root (<a href="/web-llvm/docs/api/classes/llvm/json/path/root">Root</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Reference <a href="#acee898545ed238ee925d9cd23787fde6">Root</a>.</p>

</div>
</div>

### Root() {#a7857709c798bd7d5e7983f647bab1104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::json::Path::Root::Root (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/path/root">Root</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Reference <a href="#acee898545ed238ee925d9cd23787fde6">Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ac89989a09764c1e89fe33de340086d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Root &amp; llvm::json::Path::Root::operator= (<a href="/web-llvm/docs/api/classes/llvm/json/path/root">Root</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Reference <a href="#acee898545ed238ee925d9cd23787fde6">Root</a>.</p>

</div>
</div>

### operator=() {#a31bf7cacb46f1f2684523d6c8065d1a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Root &amp; llvm::json::Path::Root::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/path/root">Root</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Reference <a href="#acee898545ed238ee925d9cd23787fde6">Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getError() {#a67c80beebd4079b6f29718231592ef00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::json::Path::Root::getError ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the last error reported, or else a generic error.</p>

<p>Declaration at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

### printErrorContext() {#a064c6a4f075f7dbdbdc16e791de1168a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::Path::Root::printErrorContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/value">Value</a> &amp; R, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the root value with the error shown inline as a comment.</p>


<p>Unrelated parts of the value are elided for brevity, e.g. { "id": 42, "name": /* expected string *‍/ null, "properties": { ... } }</p>


<p>Declaration at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a3251137d4e13982c711221d45fff9a09">llvm::json::abbreviate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a0cff3f49083a4dfc91368979f818f297">llvm::json::abbreviateChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a91056cd37dda55d4b00d69b6361641e4">llvm::json::OStream::array</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a39613bf6aa1a8059a4dd25d57c7fd1e5">llvm::json::OStream::attributeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#aacce5798acdb34154adce0318fdfdaf8">llvm::json::OStream::attributeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a8d6140131d6891e8ca8c134b889b8ec8">llvm::json::OStream::comment</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a06d556674c46c15e5906f2f645f4fbe5">llvm::json::OStream::object</a>, <a href="/web-llvm/docs/api/classes/llvm/json/path/#ae545989dfe88e1df8ea16fb3454952c8">llvm::json::Path::Path</a> and <a href="/web-llvm/docs/api/namespaces/llvm/json/#a4821bec148e6c1fb582ae15d760d116c">llvm::json::sortedElements</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ErrorMessage {#aa82066fc9eb9117af4793e4a391f6516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringLiteral llvm::json::Path::Root::ErrorMessage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### ErrorPath {#aaa02a6e98e0001ae6a9c8af1a7694b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Path::Segment&gt; llvm::json::Path::Root::ErrorPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### Name {#a7c19ca8129c3ae08ae2324e2222e7446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef llvm::json::Path::Root::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
