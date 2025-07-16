---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sdpatternmatch/switchcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SwitchContext` Struct Template Reference

<p>Switch to a different MatchContext for subsequent patterns. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename NewMatchContext, typename Pattern&gt;
struct llvm::SDPatternMatch::SwitchContext&lt;NewMatchContext, Pattern&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">llvm/CodeGen/SDPatternMatch.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename OrigMatchContext&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add6c67bd91e3b57463153096015a65d7">match</a> (const OrigMatchContext &amp;, SDValue N)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NewMatchContext, typename Pattern&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NewMatchContext &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2653c132c860f2591e0582e868d1874a">Ctx</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NewMatchContext, typename Pattern&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ba4ad1598969f877f8a6533dfecdd53">P</a></td>
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

<p>Switch to a different MatchContext for subsequent patterns.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### match() {#add6c67bd91e3b57463153096015a65d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OrigMatchContext&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDPatternMatch::SwitchContext&lt; NewMatchContext, Pattern &gt;::match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> OrigMatchContext &amp;, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="#a2653c132c860f2591e0582e868d1874a">llvm::SDPatternMatch::SwitchContext&lt; NewMatchContext, Pattern &gt;::Ctx</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a3ba4ad1598969f877f8a6533dfecdd53">llvm::SDPatternMatch::SwitchContext&lt; NewMatchContext, Pattern &gt;::P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Ctx {#a2653c132c860f2591e0582e868d1874a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NewMatchContext, typename Pattern&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NewMatchContext&amp; llvm::SDPatternMatch::SwitchContext&lt; NewMatchContext, Pattern &gt;::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#add6c67bd91e3b57463153096015a65d7">llvm::SDPatternMatch::SwitchContext&lt; NewMatchContext, Pattern &gt;::match</a>.</p>

</div>
</div>

### P {#a3ba4ad1598969f877f8a6533dfecdd53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NewMatchContext, typename Pattern&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pattern llvm::SDPatternMatch::SwitchContext&lt; NewMatchContext, Pattern &gt;::P</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#add6c67bd91e3b57463153096015a65d7">llvm::SDPatternMatch::SwitchContext&lt; NewMatchContext, Pattern &gt;::match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
