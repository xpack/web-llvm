---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/symbolize/markupparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MarkupParser` Class

<p>Parses a log containing symbolizer markup into a sequence of nodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::symbolize::MarkupParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">llvm/DebugInfo/Symbolize/Markup.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a77ded267a2d238bf5f1e9c3a78dc96">MarkupParser</a> (StringSet&lt;&gt; MultilineTags={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af65477d093fd230a78c34132fd3a6546">parseLine</a> (StringRef Line)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses an individual <span class="doxyComputerOutput">Line</span> of input. <a href="#af65477d093fd230a78c34132fd3a6546">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb494b6794b875a17f4b0ddb5f858af">flush</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform the parser of that the input stream has ended. <a href="#a2cb494b6794b875a17f4b0ddb5f858af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/symbolize/markupnode">MarkupNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eaa76c1f1e142ff478fe1ac0196cab9">nextNode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next node in the input sequence. <a href="#a1eaa76c1f1e142ff478fe1ac0196cab9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a48c7806aabb3e20030a142f2f05f5">isSGR</a> (const MarkupNode &amp;Node) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/symbolize/markupnode">MarkupNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2fc8db8e13477f93eb5ba2481b41dc7">parseElement</a> (StringRef Line)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf5b9e9b1ac86afff6d9ec2246bb8bc8">parseTextOutsideMarkup</a> (StringRef Text)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3568072a1bfdd10a785dc5c3fb71d1a1">parseMultiLineBegin</a> (StringRef Line)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f110c67c15bb1a9964bae59c8b2a881">parseMultiLineEnd</a> (StringRef Line)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae644913f6b3349b944942f8813ca0a50">MultilineTags</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f1d490325431d509f0b9b4de2646fa">FinishedMultiline</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f0f46e2866fd4fe0f2e116a2509b0e">InProgressMultiline</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f88ebe04331eac0eefc823edfeb122">Line</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/symbolize/markupnode">MarkupNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7e55458c3652f7744e0e852d5d9718a">Buffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a179a91cb2c6053ef9b734389e1f662da">NextIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a43a6d94e963b9465eb439c439a0b05">SGRSyntax</a></td>
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

<p>Parses a log containing symbolizer markup into a sequence of nodes.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MarkupParser() {#a6a77ded267a2d238bf5f1e9c3a78dc96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::symbolize::MarkupParser::MarkupParser (<a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a>&lt;&gt; MultilineTags={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/markup-cpp">Markup.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#adc30de2535cb8772ec117f12fbc4714d">llvm::symbolize::SGRSyntaxStr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### flush() {#a2cb494b6794b875a17f4b0ddb5f858af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::symbolize::MarkupParser::flush ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inform the parser of that the input stream has ended.</p>


<p>This allows the parser to finish any deferred processing (e.g., an in-progress multi-line element) and may cause <a href="#a1eaa76c1f1e142ff478fe1ac0196cab9">nextNode()</a> to return additional nodes.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/markup-cpp">Markup.cpp</a>.</p>

</div>
</div>

### isSGR() {#a31a48c7806aabb3e20030a142f2f05f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::symbolize::MarkupParser::isSGR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/symbolize/markupnode">MarkupNode</a> &amp; Node)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>.</p>

</div>
</div>

### nextNode() {#a1eaa76c1f1e142ff478fe1ac0196cab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MarkupNode &gt; llvm::symbolize::MarkupParser::nextNode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the next node in the input sequence.</p>


<p>Calling <a href="#a1eaa76c1f1e142ff478fe1ac0196cab9">nextNode()</a> may invalidate the contents of the node returned by the previous call.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the next markup node or std::nullopt if none remain.</p></dd>
</dl>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/markup-cpp">Markup.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a4d5dd7fe2a8b87fc57e6a7c7af7291c7">llvm::symbolize::advanceTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1eaa76c1f1e142ff478fe1ac0196cab9">nextNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#affc5c86ebe7a9a58c623b38370b90762">llvm::symbolize::takeTo</a>.</p>


<p>Referenced by <a href="#a1eaa76c1f1e142ff478fe1ac0196cab9">nextNode</a>.</p>

</div>
</div>

### parseLine() {#af65477d093fd230a78c34132fd3a6546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::symbolize::MarkupParser::parseLine (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses an individual <span class="doxyComputerOutput">Line</span> of input.</p>


<p>Nodes from the previous <a href="#af65477d093fd230a78c34132fd3a6546">parseLine()</a> call that haven't yet been extracted by <a href="#a1eaa76c1f1e142ff478fe1ac0196cab9">nextNode()</a> are discarded. The nodes returned by <a href="#a1eaa76c1f1e142ff478fe1ac0196cab9">nextNode()</a> may reference the input string, so it must be retained by the caller until the last use.</p>


<p>Note that some elements may span multiple lines. If a line ends with the start of one of these elements, then no nodes will be produced until the either the end or something that cannot be part of an element is encountered. This may only occur after multiple calls to <a href="#af65477d093fd230a78c34132fd3a6546">parseLine()</a>, corresponding to the lines of the multi-line element.</p>


<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/markup-cpp">Markup.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### parseElement() {#af2fc8db8e13477f93eb5ba2481b41dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MarkupNode &gt; llvm::symbolize::MarkupParser::parseElement (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/markup-cpp">Markup.cpp</a>.</p>

</div>
</div>

### parseMultiLineBegin() {#a3568072a1bfdd10a785dc5c3fb71d1a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; llvm::symbolize::MarkupParser::parseMultiLineBegin (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/markup-cpp">Markup.cpp</a>.</p>

</div>
</div>

### parseMultiLineEnd() {#a0f110c67c15bb1a9964bae59c8b2a881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; llvm::symbolize::MarkupParser::parseMultiLineEnd (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/markup-cpp">Markup.cpp</a>.</p>

</div>
</div>

### parseTextOutsideMarkup() {#acf5b9e9b1ac86afff6d9ec2246bb8bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::symbolize::MarkupParser::parseTextOutsideMarkup (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/markup-cpp">Markup.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buffer {#af7e55458c3652f7744e0e852d5d9718a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MarkupNode&gt; llvm::symbolize::MarkupParser::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>.</p>

</div>
</div>

### FinishedMultiline {#a53f1d490325431d509f0b9b4de2646fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::symbolize::MarkupParser::FinishedMultiline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>.</p>

</div>
</div>

### InProgressMultiline {#ab5f0f46e2866fd4fe0f2e116a2509b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::symbolize::MarkupParser::InProgressMultiline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>.</p>

</div>
</div>

### Line {#ab9f88ebe04331eac0eefc823edfeb122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::symbolize::MarkupParser::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>.</p>

</div>
</div>

### MultilineTags {#ae644913f6b3349b944942f8813ca0a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringSet llvm::symbolize::MarkupParser::MultilineTags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>.</p>

</div>
</div>

### NextIdx {#a179a91cb2c6053ef9b734389e1f662da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::symbolize::MarkupParser::NextIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>.</p>

</div>
</div>

### SGRSyntax {#a0a43a6d94e963b9465eb439c439a0b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Regex llvm::symbolize::MarkupParser::SGRSyntax</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/symbolize/markup-h">Markup.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/markup-cpp">Markup.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
