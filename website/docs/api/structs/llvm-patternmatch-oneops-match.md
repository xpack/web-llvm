---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/patternmatch/oneops-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OneOps_match` Struct Template Reference

<p>Matches instructions with Opcode and three operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T0, unsigned Opcode&gt;
struct llvm::PatternMatch::OneOps_match&lt;T0, Opcode&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T0, unsigned Opcode&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad3fa7d9beb014eb1cfa20cb01d2d04da">OneOps_match</a> (const T0 &amp;Op1)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2efcccf5da1164cd22f5fa206886ec5e">match</a> (OpTy *V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T0, unsigned Opcode&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T0</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaac90ea1390e8a5eac7ce03bf9498417">Op1</a></td>
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

<p>Matches instructions with Opcode and three operands.</p>

<p>Definition at line 1711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OneOps\_match() {#ad3fa7d9beb014eb1cfa20cb01d2d04da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0, unsigned Opcode&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PatternMatch::OneOps_match&lt; T0, Opcode &gt;::OneOps_match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T0 &amp; Op1)</td>
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



<p>Definition at line 1714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Reference <a href="#aaac90ea1390e8a5eac7ce03bf9498417">llvm::PatternMatch::OneOps_match&lt; T0, Opcode &gt;::Op1</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a2efcccf5da1164cd22f5fa206886ec5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename OpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatternMatch::OneOps_match&lt; T0, Opcode &gt;::match (OpTy * V)</td>
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



<p>Definition at line 1716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aaac90ea1390e8a5eac7ce03bf9498417">llvm::PatternMatch::OneOps_match&lt; T0, Opcode &gt;::Op1</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Op1 {#aaac90ea1390e8a5eac7ce03bf9498417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0, unsigned Opcode&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T0 llvm::PatternMatch::OneOps_match&lt; T0, Opcode &gt;::Op1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a>.</p>


<p>Referenced by <a href="#a2efcccf5da1164cd22f5fa206886ec5e">llvm::PatternMatch::OneOps_match&lt; T0, Opcode &gt;::match</a> and <a href="#ad3fa7d9beb014eb1cfa20cb01d2d04da">llvm::PatternMatch::OneOps_match&lt; T0, Opcode &gt;::OneOps_match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">PatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
