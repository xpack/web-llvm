---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-aarch64postlegalizerlowering-cpp-/shufflevectorpseudo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ShuffleVectorPseudo` Struct Reference

<p>Represents a pseudo instruction which replaces a G_SHUFFLE_VECTOR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{AArch64PostLegalizerLowering.cpp}::ShuffleVectorPseudo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc18e773fdd4a1c87b86e88045bf673">ShuffleVectorPseudo</a> (unsigned Opc, Register Dst, std::initializer_list&lt; SrcOp &gt; SrcOps)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d9148780c72da3c2a7b5bfa0954615">ShuffleVectorPseudo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e8e4a2a5e8a93ab861aa885e0ce1ee">Opc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opcode for the instruction. (E.g. G_ZIP1) <a href="#a87e8e4a2a5e8a93ab861aa885e0ce1ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d139a37610d566987401c615398a3b3">Dst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destination register. <a href="#a2d139a37610d566987401c615398a3b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb5dd89cc73c6ba82243116bab56e479">SrcOps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source registers. <a href="#afb5dd89cc73c6ba82243116bab56e479">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents a pseudo instruction which replaces a G_SHUFFLE_VECTOR.</p>


<p>Used for matching target-supported shuffles before codegen.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ShuffleVectorPseudo() {#a8fc18e773fdd4a1c87b86e88045bf673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64PostLegalizerLowering.cpp}::ShuffleVectorPseudo::ShuffleVectorPseudo (unsigned Opc, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &gt; SrcOps)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<p>References <a href="#a2d139a37610d566987401c615398a3b3">Dst</a>, <a href="#a87e8e4a2a5e8a93ab861aa885e0ce1ee">Opc</a> and <a href="#afb5dd89cc73c6ba82243116bab56e479">SrcOps</a>.</p>

</div>
</div>

### ShuffleVectorPseudo() {#a60d9148780c72da3c2a7b5bfa0954615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64PostLegalizerLowering.cpp}::ShuffleVectorPseudo::ShuffleVectorPseudo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#aab8df7d7e3ce751342641af96a441226">anonymous{AArch64PostLegalizerLowering.cpp}::matchDupFromBuildVector</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a9b2765617a7f219018411ea15d1b2357">anonymous{AArch64PostLegalizerLowering.cpp}::matchDupFromInsertVectorElt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a0e7fcc80fba58e49993976fe1ca63bb6">anonymous{AArch64PostLegalizerLowering.cpp}::matchEXT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a5f2ddad973979c1e22c12df4eb61d289">anonymous{AArch64PostLegalizerLowering.cpp}::matchREV</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#abe0132c19c2bd5fa7901bdcbf8e2791e">anonymous{AArch64PostLegalizerLowering.cpp}::matchTRN</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a9107f70b16e7f301b6bb8d8f8a9c3d11">anonymous{AArch64PostLegalizerLowering.cpp}::matchUZP</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a360fc2ad0865f80a9d354eb41b791e0b">anonymous{AArch64PostLegalizerLowering.cpp}::matchZip</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Dst {#a2d139a37610d566987401c615398a3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{AArch64PostLegalizerLowering.cpp}::ShuffleVectorPseudo::Dst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destination register.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ab5aa406f974e74967376237df439846a">anonymous{AArch64PostLegalizerLowering.cpp}::applyEXT</a> and <a href="#a8fc18e773fdd4a1c87b86e88045bf673">ShuffleVectorPseudo</a>.</p>

</div>
</div>

### Opc {#a87e8e4a2a5e8a93ab861aa885e0ce1ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64PostLegalizerLowering.cpp}::ShuffleVectorPseudo::Opc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Opcode for the instruction. (E.g. G_ZIP1)</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ab5aa406f974e74967376237df439846a">anonymous{AArch64PostLegalizerLowering.cpp}::applyEXT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ad32e02ce8096aee6a5378ec754bf5034">anonymous{AArch64PostLegalizerLowering.cpp}::applyShuffleVectorPseudo</a> and <a href="#a8fc18e773fdd4a1c87b86e88045bf673">ShuffleVectorPseudo</a>.</p>

</div>
</div>

### SrcOps {#afb5dd89cc73c6ba82243116bab56e479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SrcOp, 2&gt; anonymous{AArch64PostLegalizerLowering.cpp}::ShuffleVectorPseudo::SrcOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source registers.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ab5aa406f974e74967376237df439846a">anonymous{AArch64PostLegalizerLowering.cpp}::applyEXT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ad32e02ce8096aee6a5378ec754bf5034">anonymous{AArch64PostLegalizerLowering.cpp}::applyShuffleVectorPseudo</a> and <a href="#a8fc18e773fdd4a1c87b86e88045bf673">ShuffleVectorPseudo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
