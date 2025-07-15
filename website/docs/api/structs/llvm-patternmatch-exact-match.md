---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/exact-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Exact_match` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename SubPattern_t&gt;
struct llvm::PatternMatch::Exact_match&lt;SubPattern_t&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubPattern_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a51fade9b2387f37c247437ddc8c4fb12">Exact_match</a> (const SubPattern_t &amp;SP)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OpTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6dd3eee29f79dbc95cad210b652097b8">match</a> (OpTy *V)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubPattern_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SubPattern_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a70fdf703852279fbd1f5da334daf1192">SubPattern</a></td>
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


<p>Definition at line 1568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Exact\_match() {#a51fade9b2387f37c247437ddc8c4fb12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubPattern_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::Exact_match&lt; SubPattern_t &gt;::Exact_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SubPattern_t &amp; SP)</td>
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



<p>Definition at line 1571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Reference <a href="#a70fdf703852279fbd1f5da334daf1192">llvm::PatternMatch::Exact_match&lt; SubPattern_t &gt;::SubPattern</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a6dd3eee29f79dbc95cad210b652097b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatternMatch::Exact_match&lt; SubPattern_t &gt;::match (OpTy * V)</td>
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



<p>Definition at line 1573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a70fdf703852279fbd1f5da334daf1192">llvm::PatternMatch::Exact_match&lt; SubPattern_t &gt;::SubPattern</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### SubPattern {#a70fdf703852279fbd1f5da334daf1192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubPattern_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubPattern_t llvm::PatternMatch::Exact_match&lt; SubPattern_t &gt;::SubPattern</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a51fade9b2387f37c247437ddc8c4fb12">llvm::PatternMatch::Exact_match&lt; SubPattern_t &gt;::Exact_match</a> and <a href="#a6dd3eee29f79dbc95cad210b652097b8">llvm::PatternMatch::Exact_match&lt; SubPattern_t &gt;::match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
