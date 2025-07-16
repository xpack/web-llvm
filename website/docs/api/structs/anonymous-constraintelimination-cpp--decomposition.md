---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-constraintelimination-cpp-/decomposition
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Decomposition` Struct Reference

<p>Represents an Offset + Coefficient1 * Variable1 + ... decomposition. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ConstraintElimination.cpp}::Decomposition { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe183d480c55ba96b3716679525c787">Decomposition</a> (int64_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f108f2a6164e643c6418cbc08d6d8b">Decomposition</a> (Value *V, bool IsKnownNonNegative=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee82235ec3d0b0cbaccd29acf693f81">Decomposition</a> (int64_t Offset, ArrayRef&lt; DecompEntry &gt; Vars)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867981842db9718c108f713b68062a91">add</a> (int64_t OtherOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1504aabaab250ca935a1f7088bfd42c0">add</a> (const Decomposition &amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ff89f0cb757a75341706ebbf4ed7ee">sub</a> (const Decomposition &amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b061500c5bb05b05a9a0c0bb6205e1e">mul</a> (int64_t Factor)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab009842111612da481ca69462b52a12f">Offset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/decompentry">DecompEntry</a>, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae879aaf293c9c094d820ffc9284f5b7c">Vars</a></td>
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

<p>Represents an Offset + Coefficient1 * Variable1 + ... decomposition.</p>

<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Decomposition() {#acbe183d480c55ba96b3716679525c787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ConstraintElimination.cpp}::Decomposition::Decomposition (int64_t Offset)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Reference <a href="#ab009842111612da481ca69462b52a12f">Offset</a>.</p>


<p>Referenced by <a href="#a1504aabaab250ca935a1f7088bfd42c0">add</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a3a288d8153f8bd74315b59636438d6e2">decomposeGEP</a> and <a href="#aa3ff89f0cb757a75341706ebbf4ed7ee">sub</a>.</p>

</div>
</div>

### Decomposition() {#ad3f108f2a6164e643c6418cbc08d6d8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ConstraintElimination.cpp}::Decomposition::Decomposition (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool IsKnownNonNegative=false)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Reference <a href="#ae879aaf293c9c094d820ffc9284f5b7c">Vars</a>.</p>

</div>
</div>

### Decomposition() {#a1ee82235ec3d0b0cbaccd29acf693f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ConstraintElimination.cpp}::Decomposition::Decomposition (int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/decompentry">DecompEntry</a> &gt; Vars)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#ab009842111612da481ca69462b52a12f">Offset</a> and <a href="#ae879aaf293c9c094d820ffc9284f5b7c">Vars</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a867981842db9718c108f713b68062a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ConstraintElimination.cpp}::Decomposition::add (int64_t OtherOffset)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a21d115d23f25fa3a2eabb1acaac67444">addWithOverflow</a> and <a href="#ab009842111612da481ca69462b52a12f">Offset</a>.</p>


<p>Referenced by <a href="#a1504aabaab250ca935a1f7088bfd42c0">add</a> and <a href="#aa3ff89f0cb757a75341706ebbf4ed7ee">sub</a>.</p>

</div>
</div>

### add() {#a1504aabaab250ca935a1f7088bfd42c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ConstraintElimination.cpp}::Decomposition::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/decomposition">Decomposition</a> &amp; Other)</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#a867981842db9718c108f713b68062a91">add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="#acbe183d480c55ba96b3716679525c787">Decomposition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae879aaf293c9c094d820ffc9284f5b7c">Vars</a>.</p>

</div>
</div>

### mul() {#a7b061500c5bb05b05a9a0c0bb6205e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ConstraintElimination.cpp}::Decomposition::mul (int64_t Factor)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a3f9fcd2e20a682694cfa512d34dcc2b5">multiplyWithOverflow</a>, <a href="#ab009842111612da481ca69462b52a12f">Offset</a> and <a href="#ae879aaf293c9c094d820ffc9284f5b7c">Vars</a>.</p>


<p>Referenced by <a href="#aa3ff89f0cb757a75341706ebbf4ed7ee">sub</a>.</p>

</div>
</div>

### sub() {#aa3ff89f0cb757a75341706ebbf4ed7ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ConstraintElimination.cpp}::Decomposition::sub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/decomposition">Decomposition</a> &amp; Other)</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#a867981842db9718c108f713b68062a91">add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="#acbe183d480c55ba96b3716679525c787">Decomposition</a>, <a href="#a7b061500c5bb05b05a9a0c0bb6205e1e">mul</a>, <a href="#ab009842111612da481ca69462b52a12f">Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ae879aaf293c9c094d820ffc9284f5b7c">Vars</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Offset {#ab009842111612da481ca69462b52a12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{ConstraintElimination.cpp}::Decomposition::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#a867981842db9718c108f713b68062a91">add</a>, <a href="#acbe183d480c55ba96b3716679525c787">Decomposition</a>, <a href="#a1ee82235ec3d0b0cbaccd29acf693f81">Decomposition</a>, <a href="#a7b061500c5bb05b05a9a0c0bb6205e1e">mul</a> and <a href="#aa3ff89f0cb757a75341706ebbf4ed7ee">sub</a>.</p>

</div>
</div>

### Vars {#ae879aaf293c9c094d820ffc9284f5b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DecompEntry, 3&gt; anonymous{ConstraintElimination.cpp}::Decomposition::Vars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#a1504aabaab250ca935a1f7088bfd42c0">add</a>, <a href="#a1ee82235ec3d0b0cbaccd29acf693f81">Decomposition</a>, <a href="#ad3f108f2a6164e643c6418cbc08d6d8b">Decomposition</a>, <a href="#a7b061500c5bb05b05a9a0c0bb6205e1e">mul</a> and <a href="#aa3ff89f0cb757a75341706ebbf4ed7ee">sub</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
