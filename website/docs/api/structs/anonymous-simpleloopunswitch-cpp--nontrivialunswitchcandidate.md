---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-simpleloopunswitch-cpp-/nontrivialunswitchcandidate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `NonTrivialUnswitchCandidate` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a428fcbe432c0149594a5fe987bafd318">NonTrivialUnswitchCandidate</a> (Instruction *TI, ArrayRef&lt; Value * &gt; Invariants, std::optional&lt; InstructionCost &gt; Cost=std::nullopt, std::optional&lt; InjectedInvariant &gt; PendingInjection=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae121300fe93703e0c8825f724025f2a2">hasPendingInjection</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695f3bf5e2bba01665de74141bfb6655">TI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tinyptrvector">TinyPtrVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ce4b1dbb1250c62fca0e4b6a580a14">Invariants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f60bd27f2a0a661d2af174a13bb257c">Cost</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/injectedinvariant">InjectedInvariant</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929ea50c0f49f2b80e471c99d108c2cf">PendingInjection</a></td>
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


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NonTrivialUnswitchCandidate() {#a428fcbe432c0149594a5fe987bafd318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate::NonTrivialUnswitchCandidate (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * TI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Invariants, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &gt; Cost=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-simpleloopunswitch-cpp-/injectedinvariant">InjectedInvariant</a> &gt; PendingInjection=std::nullopt)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="#a1f60bd27f2a0a661d2af174a13bb257c">Cost</a>, <a href="#a12ce4b1dbb1250c62fca0e4b6a580a14">Invariants</a>, <a href="#a929ea50c0f49f2b80e471c99d108c2cf">PendingInjection</a> and <a href="#a695f3bf5e2bba01665de74141bfb6655">TI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasPendingInjection() {#ae121300fe93703e0c8825f724025f2a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate::hasPendingInjection ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Reference <a href="#a929ea50c0f49f2b80e471c99d108c2cf">PendingInjection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Cost {#a1f60bd27f2a0a661d2af174a13bb257c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;InstructionCost&gt; anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate::Cost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a428fcbe432c0149594a5fe987bafd318">NonTrivialUnswitchCandidate</a>.</p>

</div>
</div>

### Invariants {#a12ce4b1dbb1250c62fca0e4b6a580a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TinyPtrVector&lt;Value *&gt; anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate::Invariants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a428fcbe432c0149594a5fe987bafd318">NonTrivialUnswitchCandidate</a>.</p>

</div>
</div>

### PendingInjection {#a929ea50c0f49f2b80e471c99d108c2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;InjectedInvariant&gt; anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate::PendingInjection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#ae121300fe93703e0c8825f724025f2a2">hasPendingInjection</a> and <a href="#a428fcbe432c0149594a5fe987bafd318">NonTrivialUnswitchCandidate</a>.</p>

</div>
</div>

### TI {#a695f3bf5e2bba01665de74141bfb6655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{SimpleLoopUnswitch.cpp}::NonTrivialUnswitchCandidate::TI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Referenced by <a href="#a428fcbe432c0149594a5fe987bafd318">NonTrivialUnswitchCandidate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
