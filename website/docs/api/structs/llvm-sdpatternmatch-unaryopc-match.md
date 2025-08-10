---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sdpatternmatch/unaryopc-match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `UnaryOpc_match` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename Opnd_P, bool ExcludeChain = false&gt;
struct llvm::SDPatternMatch::UnaryOpc_match&lt;Opnd_P, ExcludeChain&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">llvm/CodeGen/SDPatternMatch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Opnd_P, bool ExcludeChain = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5e6023b48725f897ca6efbf861b53ecc">UnaryOpc_match</a> (unsigned Opc, const Opnd_P &amp;Op, std::optional&lt; SDNodeFlags &gt; Flgs=std::nullopt)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MatchContext&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa82cb4ad7ffa228901bd32582599254b">match</a> (const MatchContext &amp;Ctx, SDValue N)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Opnd_P, bool ExcludeChain = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27166a5afcd1ff08057bf0105aa19a8a">Opcode</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Opnd_P, bool ExcludeChain = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Opnd_P</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf8c40cc10bf645bd8bbbf7896e5f8e5">Opnd</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Opnd_P, bool ExcludeChain = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1352844eeefe080b167e9dedc08b1c65">Flags</a></td>
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


<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UnaryOpc\_match() {#a5e6023b48725f897ca6efbf861b53ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Opnd_P, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::UnaryOpc_match (unsigned Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Opnd_P &amp; Op, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> &gt; Flgs=std::nullopt)</td>
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



<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="#a1352844eeefe080b167e9dedc08b1c65">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::Flags</a>, <a href="#a27166a5afcd1ff08057bf0105aa19a8a">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::Opcode</a> and <a href="#aaf8c40cc10bf645bd8bbbf7896e5f8e5">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::Opnd</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#aa82cb4ad7ffa228901bd32582599254b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MatchContext&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::match (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MatchContext &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands/#a006f515fed3d399b72bd8868c4e66a9d">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::FirstIndex</a>, <a href="#a1352844eeefe080b167e9dedc08b1c65">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::Flags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#a04ca771721b0090c8fbe9586a2d444f3">llvm::SDPatternMatch::m_Opc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a27166a5afcd1ff08057bf0105aa19a8a">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::Opcode</a>, <a href="#aaf8c40cc10bf645bd8bbbf7896e5f8e5">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::Opnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#af8425e06dcc0a862a898887c9baca083">llvm::SDPatternMatch::sd_context_match</a> and <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands/#a51dd9986ea8bee28540b1df8a63b3248">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Flags {#a1352844eeefe080b167e9dedc08b1c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Opnd_P, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;SDNodeFlags&gt; llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#aa82cb4ad7ffa228901bd32582599254b">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::match</a> and <a href="#a5e6023b48725f897ca6efbf861b53ecc">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::UnaryOpc_match</a>.</p>

</div>
</div>

### Opcode {#a27166a5afcd1ff08057bf0105aa19a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Opnd_P, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#aa82cb4ad7ffa228901bd32582599254b">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::match</a> and <a href="#a5e6023b48725f897ca6efbf861b53ecc">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::UnaryOpc_match</a>.</p>

</div>
</div>

### Opnd {#aaf8c40cc10bf645bd8bbbf7896e5f8e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Opnd_P, bool ExcludeChain = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Opnd_P llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::Opnd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a>.</p>


<p>Referenced by <a href="#aa82cb4ad7ffa228901bd32582599254b">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::match</a> and <a href="#a5e6023b48725f897ca6efbf861b53ecc">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::UnaryOpc_match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/sdpatternmatch-h">SDPatternMatch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
