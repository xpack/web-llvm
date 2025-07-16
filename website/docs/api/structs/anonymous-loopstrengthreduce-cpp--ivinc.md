---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-loopstrengthreduce-cpp-/ivinc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IVInc` Struct Reference

<p>An individual increment in a Chain of IV increments. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{LoopStrengthReduce.cpp}::IVInc { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a00efb2c77fbadba8355cf70a0c46da">IVInc</a> (Instruction *U, Value *O, const SCEV *E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24dd72fbb252cd525690013aae6688db">UserInst</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89eb1b3a3d8c73618179b2ca0ac8bfd6">IVOperand</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad35bcf540910bcaecb50636e153c55c">IncExpr</a></td>
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

<p>An individual increment in a Chain of IV increments.</p>


<p>Relate an IV user to an expression that computes the IV it uses from the IV used by the previous link in the Chain.</p>


<p>For the head of a chain, IncExpr holds the absolute <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for the original IVOperand. The head of the chain's IVOperand is only valid during chain collection, before LSR replaces IV users. During chain generation, IncExpr can be used to find the new IVOperand that computes the same expression.</p>


<p>Definition at line 2082 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IVInc() {#a4a00efb2c77fbadba8355cf70a0c46da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopStrengthReduce.cpp}::IVInc::IVInc (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * U, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * E)</td>
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



<p>Definition at line 2087 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#aad35bcf540910bcaecb50636e153c55c">IncExpr</a>, <a href="#a89eb1b3a3d8c73618179b2ca0ac8bfd6">IVOperand</a> and <a href="#a24dd72fbb252cd525690013aae6688db">UserInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IncExpr {#aad35bcf540910bcaecb50636e153c55c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* anonymous{LoopStrengthReduce.cpp}::IVInc::IncExpr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2085 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a4a00efb2c77fbadba8355cf70a0c46da">IVInc</a>.</p>

</div>
</div>

### IVOperand {#a89eb1b3a3d8c73618179b2ca0ac8bfd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{LoopStrengthReduce.cpp}::IVInc::IVOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2084 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a4a00efb2c77fbadba8355cf70a0c46da">IVInc</a>.</p>

</div>
</div>

### UserInst {#a24dd72fbb252cd525690013aae6688db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{LoopStrengthReduce.cpp}::IVInc::UserInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2083 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a4a00efb2c77fbadba8355cf70a0c46da">IVInc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
