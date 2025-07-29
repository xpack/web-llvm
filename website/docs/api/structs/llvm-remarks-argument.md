---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/argument
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Argument` Struct

<p>A key-value pair with a debug location that is used to display the remarks at the right place in the source. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::Argument { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">llvm/Remarks/Remark.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3300ef5ccea26f8c499d0ff60b8d3396">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/structs/llvm/remarks/argument">Argument</a>. <a href="#a3300ef5ccea26f8c499d0ff60b8d3396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46136a8edb24437ca3ef84c207b8b392">getValAsInt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value of argument as int. <a href="#a46136a8edb24437ca3ef84c207b8b392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afad099ef48df69d598545ad3c1cd5ab1">isValInt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the argument value can be parsed as int. <a href="#afad099ef48df69d598545ad3c1cd5ab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1659ff309b2d229a210b52d897680ecd">Key</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43436771a3f98d9984cbd0428bc1b9a3">Val</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklocation">RemarkLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47da97597ff2702cbce42d0ba7322349">Loc</a></td>
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

<p>A key-value pair with a debug location that is used to display the remarks at the right place in the source.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getValAsInt() {#a46136a8edb24437ca3ef84c207b8b392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int &gt; Argument::getValAsInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the value of argument as int.</p>


<p>Returns the value of a specified key parsed from <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a> and <a href="#a43436771a3f98d9984cbd0428bc1b9a3">Val</a>.</p>


<p>Referenced by <a href="#afad099ef48df69d598545ad3c1cd5ab1">isValInt</a>.</p>

</div>
</div>

### isValInt() {#afad099ef48df69d598545ad3c1cd5ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::isValInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the argument value can be parsed as int.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>Reference <a href="#a46136a8edb24437ca3ef84c207b8b392">getValAsInt</a>.</p>

</div>
</div>

### print() {#a3300ef5ccea26f8c499d0ff60b8d3396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Argument::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/structs/llvm/remarks/argument">Argument</a>.</p>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="#a1659ff309b2d229a210b52d897680ecd">Key</a> and <a href="#a43436771a3f98d9984cbd0428bc1b9a3">Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#af47a876cb79c9f9130c77ec1845aba7a">llvm::remarks::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Key {#a1659ff309b2d229a210b52d897680ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::remarks::Argument::Key</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable/#a3f58ed47dc2581869528b5478cd04ded">llvm::remarks::StringTable::internalize</a> and <a href="#a3300ef5ccea26f8c499d0ff60b8d3396">print</a>.</p>

</div>
</div>

### Loc {#a47da97597ff2702cbce42d0ba7322349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;RemarkLocation&gt; llvm::remarks::Argument::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable/#a3f58ed47dc2581869528b5478cd04ded">llvm::remarks::StringTable::internalize</a>.</p>

</div>
</div>

### Val {#a43436771a3f98d9984cbd0428bc1b9a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::remarks::Argument::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad385e18cefeea744d80d4ab608dfd09d">llvm::remarks::BitstreamRemarkSerializerHelper::emitRemarkBlock</a>, <a href="#a46136a8edb24437ca3ef84c207b8b392">getValAsInt</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable/#a3f58ed47dc2581869528b5478cd04ded">llvm::remarks::StringTable::internalize</a> and <a href="#a3300ef5ccea26f8c499d0ff60b8d3396">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
