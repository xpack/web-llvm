---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-capturetracking-cpp-/capturesbefore
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CapturesBefore` Struct Reference

<p>Only find pointer captures which happen before the given instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{CaptureTracking.cpp}::CapturesBefore { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/capturetracker">CaptureTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is used in conjunction with PointerMayBeCaptured. <a href="/web-llvm/docs/api/structs/llvm/capturetracker/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc18d9ec07613adc873eec5878a2edf0">CapturesBefore</a> (bool ReturnCaptures, const Instruction *I, const DominatorTree *DT, bool IncludeI, const LoopInfo *LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab81680d41e08ed51e46429695b9ed780">tooManyUses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tooManyUses - The depth of traversal has breached a limit. <a href="#ab81680d41e08ed51e46429695b9ed780">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8f2592f5bdd6544ed498a6d1809cbd">isSafeToPrune</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cff3d7972218ba6932358aff66905fe">captured</a> (const Use *U) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>captured - Information about the pointer was captured by the user of use U. <a href="#a3cff3d7972218ba6932358aff66905fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae003916c5543317ab2ec8373b89a3931">BeforeHere</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc89ffa851c82cbd44db16d789e2ccd">DT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8aa8f0489a4225239f2e9a6f2af51be">ReturnCaptures</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac890c6f0443c5b5e8bd52c26baa257e0">IncludeI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36ff229daca0e1b4d318df1e87af6ec1">Captured</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27aa2cbf31c09e0e9e6ef4749c7a03f">LI</a></td>
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

<p>Only find pointer captures which happen before the given instruction.</p>


<p>Uses the dominator tree to determine whether one instruction is before another. Only support the case where the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is defined in the same basic block as the given instruction and the use.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CapturesBefore() {#adc18d9ec07613adc873eec5878a2edf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CaptureTracking.cpp}::CapturesBefore::CapturesBefore (bool ReturnCaptures, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, bool IncludeI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>References <a href="#ae003916c5543317ab2ec8373b89a3931">BeforeHere</a>, <a href="#a0fc89ffa851c82cbd44db16d789e2ccd">DT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac890c6f0443c5b5e8bd52c26baa257e0">IncludeI</a>, <a href="#ab27aa2cbf31c09e0e9e6ef4749c7a03f">LI</a> and <a href="#ab8aa8f0489a4225239f2e9a6f2af51be">ReturnCaptures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### captured() {#a3cff3d7972218ba6932358aff66905fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::CapturesBefore::captured (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>captured - Information about the pointer was captured by the user of use U.</p>


<p>Return true to stop the traversal or false to continue looking for more capturing instructions.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>References <a href="#a36ff229daca0e1b4d318df1e87af6ec1">Captured</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a3c8f2592f5bdd6544ed498a6d1809cbd">isSafeToPrune</a> and <a href="#ab8aa8f0489a4225239f2e9a6f2af51be">ReturnCaptures</a>.</p>

</div>
</div>

### isSafeToPrune() {#a3c8f2592f5bdd6544ed498a6d1809cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::CapturesBefore::isSafeToPrune (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>References <a href="#ae003916c5543317ab2ec8373b89a3931">BeforeHere</a>, <a href="#a0fc89ffa851c82cbd44db16d789e2ccd">DT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac890c6f0443c5b5e8bd52c26baa257e0">IncludeI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affedc93ead6b25c57a7196d32ff11e89">llvm::isPotentiallyReachable</a> and <a href="#ab27aa2cbf31c09e0e9e6ef4749c7a03f">LI</a>.</p>


<p>Referenced by <a href="#a3cff3d7972218ba6932358aff66905fe">captured</a>.</p>

</div>
</div>

### tooManyUses() {#ab81680d41e08ed51e46429695b9ed780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CaptureTracking.cpp}::CapturesBefore::tooManyUses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>tooManyUses - The depth of traversal has breached a limit.</p>


<p>There may be capturing instructions that will not be passed into <a href="#a3cff3d7972218ba6932358aff66905fe">captured()</a>.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Reference <a href="#a36ff229daca0e1b4d318df1e87af6ec1">Captured</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BeforeHere {#ae003916c5543317ab2ec8373b89a3931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction* anonymous{CaptureTracking.cpp}::CapturesBefore::BeforeHere</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#adc18d9ec07613adc873eec5878a2edf0">CapturesBefore</a> and <a href="#a3c8f2592f5bdd6544ed498a6d1809cbd">isSafeToPrune</a>.</p>

</div>
</div>

### Captured {#a36ff229daca0e1b4d318df1e87af6ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::CapturesBefore::Captured = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#a3cff3d7972218ba6932358aff66905fe">captured</a> and <a href="#ab81680d41e08ed51e46429695b9ed780">tooManyUses</a>.</p>

</div>
</div>

### DT {#a0fc89ffa851c82cbd44db16d789e2ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DominatorTree* anonymous{CaptureTracking.cpp}::CapturesBefore::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#adc18d9ec07613adc873eec5878a2edf0">CapturesBefore</a> and <a href="#a3c8f2592f5bdd6544ed498a6d1809cbd">isSafeToPrune</a>.</p>

</div>
</div>

### IncludeI {#ac890c6f0443c5b5e8bd52c26baa257e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::CapturesBefore::IncludeI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#adc18d9ec07613adc873eec5878a2edf0">CapturesBefore</a> and <a href="#a3c8f2592f5bdd6544ed498a6d1809cbd">isSafeToPrune</a>.</p>

</div>
</div>

### LI {#ab27aa2cbf31c09e0e9e6ef4749c7a03f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopInfo* anonymous{CaptureTracking.cpp}::CapturesBefore::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#adc18d9ec07613adc873eec5878a2edf0">CapturesBefore</a> and <a href="#a3c8f2592f5bdd6544ed498a6d1809cbd">isSafeToPrune</a>.</p>

</div>
</div>

### ReturnCaptures {#ab8aa8f0489a4225239f2e9a6f2af51be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::CapturesBefore::ReturnCaptures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#a3cff3d7972218ba6932358aff66905fe">captured</a> and <a href="#adc18d9ec07613adc873eec5878a2edf0">CapturesBefore</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
