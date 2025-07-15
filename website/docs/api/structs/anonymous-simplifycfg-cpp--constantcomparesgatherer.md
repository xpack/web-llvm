---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-simplifycfg-cpp-/constantcomparesgatherer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ConstantComparesGatherer` Struct Reference

<p>Given a chain of or (||) or and (&amp;&amp;) comparison of a value against a constant, this will try to recover the information required for a switch structure. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4d63c7f5734e71bb5bcf6fd36d6888">ConstantComparesGatherer</a> (Instruction *Cond, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct and compute the result for the comparison instruction Cond. <a href="#a2d4d63c7f5734e71bb5bcf6fd36d6888">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d8c53a3fad18a7b6aa8c97f749d182">ConstantComparesGatherer</a> (const ConstantComparesGatherer &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/constantcomparesgatherer">ConstantComparesGatherer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f989d1a296fca1993e32bf1d99de2fa">operator=</a> (const ConstantComparesGatherer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81897563f4dce451574d95bdea116d29">setValueOnce</a> (Value *NewVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to set the current value used for the comparison, it succeeds only if it wasn't set before or if the new value is the same as the old one. <a href="#a81897563f4dce451574d95bdea116d29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6cd6b4b2d4085f76bd53164258bbce7">matchInstruction</a> (Instruction *I, bool isEQ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to match <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> "I" as a comparison against a constant and populates the array Vals with the set of values that match (or do not match depending on isEQ). <a href="#aa6cd6b4b2d4085f76bd53164258bbce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a818c4a5d0578dbb075460d6a5e9b9a0c">gather</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a potentially 'or'd or 'and'd together collection of icmp eq/ne/lt/gt instructions that compare a value against a constant, extract the value being compared, and stick the list constants into the Vals vector. <a href="#a818c4a5d0578dbb075460d6a5e9b9a0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab91c0864780d3ac43fdeb39b7034bdaf">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0672c6aca6021dfa9e5b6823a760db78">CompValue</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> found for the switch comparison. <a href="#a0672c6aca6021dfa9e5b6823a760db78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31bb30d8d4ac7d1f8c1a431e1cd86ba3">Extra</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extra clause to be checked before the switch. <a href="#a31bb30d8d4ac7d1f8c1a431e1cd86ba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3a44fdc0389349f3026138888096e44">Vals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of integers to match in switch. <a href="#ab3a44fdc0389349f3026138888096e44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3100c0f9b21e01920825332cfb7a30">UsedICmps</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of comparisons matched in the and/or chain. <a href="#a3b3100c0f9b21e01920825332cfb7a30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Given a chain of or (||) or and (&amp;&amp;) comparison of a value against a constant, this will try to recover the information required for a switch structure.</p>


<p>It will depth-first traverse the chain of comparison, seeking for patterns like a == 12 or a &lt; 4 and combine them to produce a set of integer representing the different cases for the switch. Note that if the chain is composed of '||' it will build the set of elements that matches the comparisons (i.e. any of this value validate the chain) while for a chain of '&amp;&amp;' it will build the set elements that make the test fail.</p>


<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConstantComparesGatherer() {#a2d4d63c7f5734e71bb5bcf6fd36d6888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::ConstantComparesGatherer (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Construct and compute the result for the comparison instruction Cond.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a> and <a href="#ab91c0864780d3ac43fdeb39b7034bdaf">DL</a>.</p>


<p>Referenced by <a href="#ad5d8c53a3fad18a7b6aa8c97f749d182">ConstantComparesGatherer</a> and <a href="#a9f989d1a296fca1993e32bf1d99de2fa">operator=</a>.</p>

</div>
</div>

### ConstantComparesGatherer() {#ad5d8c53a3fad18a7b6aa8c97f749d182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::ConstantComparesGatherer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/constantcomparesgatherer">ConstantComparesGatherer</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>Reference <a href="#a2d4d63c7f5734e71bb5bcf6fd36d6888">ConstantComparesGatherer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9f989d1a296fca1993e32bf1d99de2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantComparesGatherer &amp; anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/constantcomparesgatherer">ConstantComparesGatherer</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>References <a href="#a0672c6aca6021dfa9e5b6823a760db78">CompValue</a> and <a href="#a2d4d63c7f5734e71bb5bcf6fd36d6888">ConstantComparesGatherer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### gather() {#a818c4a5d0578dbb075460d6a5e9b9a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::gather (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Given a potentially 'or'd or 'and'd together collection of icmp eq/ne/lt/gt instructions that compare a value against a constant, extract the value being compared, and stick the list constants into the Vals vector.</p>


<p>One "Extra" case is allowed to differ from the other.</p>


<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>

</div>
</div>

### matchInstruction() {#aa6cd6b4b2d4085f76bd53164258bbce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::matchInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, bool isEQ)</td>
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

<p>Try to match <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> "I" as a comparison against a constant and populates the array Vals with the set of values that match (or do not match depending on isEQ).</p>


<p>Return false on failure. On success, the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> the comparison matched against is placed in CompValue. If CompValue is already set, the function is expected to fail if a match is found but the value compared to is different.</p>


<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>

</div>
</div>

### setValueOnce() {#a81897563f4dce451574d95bdea116d29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::setValueOnce (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewVal)</td>
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

<p>Try to set the current value used for the comparison, it succeeds only if it wasn't set before or if the new value is the same as the old one.</p>

<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CompValue {#a0672c6aca6021dfa9e5b6823a760db78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::CompValue = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> found for the switch comparison.</p>

<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>Referenced by <a href="#a9f989d1a296fca1993e32bf1d99de2fa">operator=</a>.</p>

</div>
</div>

### DL {#ab91c0864780d3ac43fdeb39b7034bdaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>Referenced by <a href="#a2d4d63c7f5734e71bb5bcf6fd36d6888">ConstantComparesGatherer</a>.</p>

</div>
</div>

### Extra {#a31bb30d8d4ac7d1f8c1a431e1cd86ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::Extra = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extra clause to be checked before the switch.</p>

<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>

</div>
</div>

### UsedICmps {#a3b3100c0f9b21e01920825332cfb7a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::UsedICmps = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of comparisons matched in the and/or chain.</p>

<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>

</div>
</div>

### Vals {#ab3a44fdc0389349f3026138888096e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ConstantInt *, 8&gt; anonymous{SimplifyCFG.cpp}::ConstantComparesGatherer::Vals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of integers to match in switch.</p>

<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
