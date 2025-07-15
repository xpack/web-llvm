---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/brc-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `brc_match` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename Cond_t, typename TrueBlock_t, typename FalseBlock_t&gt;
struct llvm::PatternMatch::brc_match&lt;Cond_t, TrueBlock_t, FalseBlock_t&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Cond_t, typename TrueBlock_t, typename FalseBlock_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a71adf9b35a8c5f82c93efd9f18ee1bb0">brc_match</a> (const Cond_t &amp;C, const TrueBlock_t &amp;t, const FalseBlock_t &amp;f)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8bba42ed67a84b48aac06d1a39444355">match</a> (OpTy *V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Cond_t, typename TrueBlock_t, typename FalseBlock_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Cond_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a460b9a02463455a54fd3c58b7242e4e3">Cond</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Cond_t, typename TrueBlock_t, typename FalseBlock_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">TrueBlock_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75e56a111679e73e8fc43324a08f096f">T</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Cond_t, typename TrueBlock_t, typename FalseBlock_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">FalseBlock_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a05f8249d52885c66e04e9b06f998987e">F</a></td>
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


<p>Definition at line 2202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### brc\_match() {#a71adf9b35a8c5f82c93efd9f18ee1bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Cond_t, typename TrueBlock_t, typename FalseBlock_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::brc_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Cond_t &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TrueBlock_t &amp; t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FalseBlock_t &amp; f)</td>
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



<p>Definition at line 2207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a460b9a02463455a54fd3c58b7242e4e3">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::Cond</a>, <a href="#a05f8249d52885c66e04e9b06f998987e">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::F</a> and <a href="#a75e56a111679e73e8fc43324a08f096f">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a8bba42ed67a84b48aac06d1a39444355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::match (OpTy * V)</td>
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



<p>Definition at line 2210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="#a460b9a02463455a54fd3c58b7242e4e3">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a05f8249d52885c66e04e9b06f998987e">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::F</a> and <a href="#a75e56a111679e73e8fc43324a08f096f">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Cond {#a460b9a02463455a54fd3c58b7242e4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Cond_t, typename TrueBlock_t, typename FalseBlock_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cond_t llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::Cond</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a71adf9b35a8c5f82c93efd9f18ee1bb0">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::brc_match</a> and <a href="#a8bba42ed67a84b48aac06d1a39444355">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::match</a>.</p>

</div>
</div>

### F {#a05f8249d52885c66e04e9b06f998987e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Cond_t, typename TrueBlock_t, typename FalseBlock_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FalseBlock_t llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a71adf9b35a8c5f82c93efd9f18ee1bb0">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::brc_match</a> and <a href="#a8bba42ed67a84b48aac06d1a39444355">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::match</a>.</p>

</div>
</div>

### T {#a75e56a111679e73e8fc43324a08f096f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Cond_t, typename TrueBlock_t, typename FalseBlock_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrueBlock_t llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a71adf9b35a8c5f82c93efd9f18ee1bb0">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::brc_match</a> and <a href="#a8bba42ed67a84b48aac06d1a39444355">llvm::PatternMatch::brc_match&lt; Cond_t, TrueBlock_t, FalseBlock_t &gt;::match</a>.</p>

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
