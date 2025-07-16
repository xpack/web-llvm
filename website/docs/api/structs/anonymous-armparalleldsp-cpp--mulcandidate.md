---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-armparalleldsp-cpp-/mulcandidate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MulCandidate` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{ARMParallelDSP.cpp}::MulCandidate { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13891759f5d1e5cc058cdb8079286eb">MulCandidate</a> (Instruction *I, Value *lhs, Value *rhs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc65c17215b140e618ea55052f172440">HasTwoLoadInputs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae532cd521dec2112c03f3bcc3f0765df">getBaseLoad</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3579457c0ec0bb5e59f5e902da6034c">Root</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a600f5b1b0501d58f3c2eb4485bcf954b">LHS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6afac03a0820ced441c209f270a468d4">RHS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515a4fd469e9f71db959022a73045b41">Exchange</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511d678a00adf3d0aff731991a4f38ba">Paired</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2a1608b8cc6af01a88416793fd2ab9f">VecLd</a></td>
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


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MulCandidate() {#ad13891759f5d1e5cc058cdb8079286eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMParallelDSP.cpp}::MulCandidate::MulCandidate (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * lhs, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * rhs)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a600f5b1b0501d58f3c2eb4485bcf954b">LHS</a>, <a href="#a6afac03a0820ced441c209f270a468d4">RHS</a> and <a href="#ab3579457c0ec0bb5e59f5e902da6034c">Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBaseLoad() {#ae532cd521dec2112c03f3bcc3f0765df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst * anonymous{ARMParallelDSP.cpp}::MulCandidate::getBaseLoad ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Reference <a href="#af2a1608b8cc6af01a88416793fd2ab9f">VecLd</a>.</p>

</div>
</div>

### HasTwoLoadInputs() {#acc65c17215b140e618ea55052f172440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMParallelDSP.cpp}::MulCandidate::HasTwoLoadInputs ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a600f5b1b0501d58f3c2eb4485bcf954b">LHS</a> and <a href="#a6afac03a0820ced441c209f270a468d4">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Exchange {#a515a4fd469e9f71db959022a73045b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMParallelDSP.cpp}::MulCandidate::Exchange = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/reduction/#a181a6bac261671ae24b57cf17edc2675">anonymous{ARMParallelDSP.cpp}::Reduction::AddMulPair</a>.</p>

</div>
</div>

### LHS {#a600f5b1b0501d58f3c2eb4485bcf954b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{ARMParallelDSP.cpp}::MulCandidate::LHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Referenced by <a href="#acc65c17215b140e618ea55052f172440">HasTwoLoadInputs</a> and <a href="#ad13891759f5d1e5cc058cdb8079286eb">MulCandidate</a>.</p>

</div>
</div>

### Paired {#a511d678a00adf3d0aff731991a4f38ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMParallelDSP.cpp}::MulCandidate::Paired = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/reduction/#a181a6bac261671ae24b57cf17edc2675">anonymous{ARMParallelDSP.cpp}::Reduction::AddMulPair</a>.</p>

</div>
</div>

### RHS {#a6afac03a0820ced441c209f270a468d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{ARMParallelDSP.cpp}::MulCandidate::RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Referenced by <a href="#acc65c17215b140e618ea55052f172440">HasTwoLoadInputs</a> and <a href="#ad13891759f5d1e5cc058cdb8079286eb">MulCandidate</a>.</p>

</div>
</div>

### Root {#ab3579457c0ec0bb5e59f5e902da6034c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{ARMParallelDSP.cpp}::MulCandidate::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/reduction/#a181a6bac261671ae24b57cf17edc2675">anonymous{ARMParallelDSP.cpp}::Reduction::AddMulPair</a> and <a href="#ad13891759f5d1e5cc058cdb8079286eb">MulCandidate</a>.</p>

</div>
</div>

### VecLd {#af2a1608b8cc6af01a88416793fd2ab9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LoadInst*, 2&gt; anonymous{ARMParallelDSP.cpp}::MulCandidate::VecLd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Referenced by <a href="#ae532cd521dec2112c03f3bcc3f0765df">getBaseLoad</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
