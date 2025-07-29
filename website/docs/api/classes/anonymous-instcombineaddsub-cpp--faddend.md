---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-instcombineaddsub-cpp-/faddend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FAddend` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddend">FAddend</a> is used to represent floating-point addend. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{InstCombineAddSub.cpp}::FAddend { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a8d19d3b1ddbc0930fbbd5c0c37c4c">FAddend</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae94d140ff4c9270f0ff3b8a55e2ebf2e">operator+=</a> (const FAddend &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b2d97e9f1fba00b45d3bcfce5346f6">getSymVal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddendcoef">FAddendCoef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda7965183ccf4ac9cf926434edc22f2">getCoef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e850e43be36bc719bde694c5ded9813">isConstant</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2d84e95adb6e78840c14e552e34e88">isZero</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b3e4c25084e471d7f921305e3f88829">set</a> (short Coefficient, Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e2ae5f1e613a0cb5ee51b29f7dcfb1">set</a> (const APFloat &amp;Coefficient, Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5149736940024f2facf99959547b8e44">set</a> (const ConstantFP *Coefficient, Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c0cc15117f0497c8ec309549be6e88">negate</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48a27ff66f7f36744592735b09bcd8d4">drillAddendDownOneStep</a> (FAddend &amp;Addend0, FAddend &amp;Addend1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to FAddend::drillDownOneStep() except that the value being splitted is the addend itself. <a href="#a48a27ff66f7f36744592735b09bcd8d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fdc0ab9144600dfa3ca7a7a53435ae">Scale</a> (const FAddendCoef &amp;ScaleAmt)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8022daf2d82fe18c01cedc9603638285">Val</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddendcoef">FAddendCoef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf5414cc07254b11711481c2694a89b">Coeff</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b3d6406d7e75f89f75afce4b23cc012">drillValueDownOneStep</a> (Value *V, FAddend &amp;A0, FAddend &amp;A1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drill down the U-D chain one step to find the definition of V, and try to break the definition into one or two addends. <a href="#a2b3d6406d7e75f89f75afce4b23cc012">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddend">FAddend</a> is used to represent floating-point addend.</p>


<p>An addend is represented as &lt;C, V&gt;, where the V is a symbolic value, and C is a constant coefficient. A constant addend is represented as &lt;C, 0&gt;.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FAddend() {#a98a8d19d3b1ddbc0930fbbd5c0c37c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InstCombineAddSub.cpp}::FAddend::FAddend ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>Referenced by <a href="#a48a27ff66f7f36744592735b09bcd8d4">drillAddendDownOneStep</a>, <a href="#a2b3d6406d7e75f89f75afce4b23cc012">drillValueDownOneStep</a> and <a href="#ae94d140ff4c9270f0ff3b8a55e2ebf2e">operator+=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator+=() {#ae94d140ff4c9270f0ff3b8a55e2ebf2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InstCombineAddSub.cpp}::FAddend::operator+= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddend">FAddend</a> &amp; T)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a98a8d19d3b1ddbc0930fbbd5c0c37c4c">FAddend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### drillAddendDownOneStep() {#a48a27ff66f7f36744592735b09bcd8d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FAddend::drillAddendDownOneStep (<a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddend">FAddend</a> &amp; Addend0, <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddend">FAddend</a> &amp; Addend1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to FAddend::drillDownOneStep() except that the value being splitted is the addend itself.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>References <a href="#a2b3d6406d7e75f89f75afce4b23cc012">drillValueDownOneStep</a>, <a href="#a98a8d19d3b1ddbc0930fbbd5c0c37c4c">FAddend</a> and <a href="#a6e850e43be36bc719bde694c5ded9813">isConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddcombine/#a47fa84ad65315d095fa4153566cbd0b6">anonymous{InstCombineAddSub.cpp}::FAddCombine::simplify</a>.</p>

</div>
</div>

### getCoef() {#afda7965183ccf4ac9cf926434edc22f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FAddendCoef &amp; anonymous{InstCombineAddSub.cpp}::FAddend::getCoef ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddcombine/#a47fa84ad65315d095fa4153566cbd0b6">anonymous{InstCombineAddSub.cpp}::FAddCombine::simplify</a>.</p>

</div>
</div>

### getSymVal() {#a40b2d97e9f1fba00b45d3bcfce5346f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{InstCombineAddSub.cpp}::FAddend::getSymVal ()</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddcombine/#a47fa84ad65315d095fa4153566cbd0b6">anonymous{InstCombineAddSub.cpp}::FAddCombine::simplify</a>.</p>

</div>
</div>

### isConstant() {#a6e850e43be36bc719bde694c5ded9813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InstCombineAddSub.cpp}::FAddend::isConstant ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>Referenced by <a href="#a48a27ff66f7f36744592735b09bcd8d4">drillAddendDownOneStep</a> and <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddcombine/#a47fa84ad65315d095fa4153566cbd0b6">anonymous{InstCombineAddSub.cpp}::FAddCombine::simplify</a>.</p>

</div>
</div>

### isZero() {#aed2d84e95adb6e78840c14e552e34e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InstCombineAddSub.cpp}::FAddend::isZero ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>

</div>
</div>

### negate() {#a51c0cc15117f0497c8ec309549be6e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InstCombineAddSub.cpp}::FAddend::negate ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>Referenced by <a href="#a2b3d6406d7e75f89f75afce4b23cc012">drillValueDownOneStep</a>.</p>

</div>
</div>

### set() {#a5b3e4c25084e471d7f921305e3f88829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InstCombineAddSub.cpp}::FAddend::set (short Coefficient, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>Referenced by <a href="#a2b3d6406d7e75f89f75afce4b23cc012">drillValueDownOneStep</a>.</p>

</div>
</div>

### set() {#ad8e2ae5f1e613a0cb5ee51b29f7dcfb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InstCombineAddSub.cpp}::FAddend::set (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Coefficient, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>

</div>
</div>

### set() {#a5149736940024f2facf99959547b8e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InstCombineAddSub.cpp}::FAddend::set (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * Coefficient, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### Scale() {#ac3fdc0ab9144600dfa3ca7a7a53435ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InstCombineAddSub.cpp}::FAddend::Scale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddendcoef">FAddendCoef</a> &amp; ScaleAmt)</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Coeff {#acdf5414cc07254b11711481c2694a89b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FAddendCoef anonymous{InstCombineAddSub.cpp}::FAddend::Coeff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>

</div>
</div>

### Val {#a8022daf2d82fe18c01cedc9603638285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{InstCombineAddSub.cpp}::FAddend::Val = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### drillValueDownOneStep() {#a2b3d6406d7e75f89f75afce4b23cc012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FAddend::drillValueDownOneStep (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddend">FAddend</a> &amp; A0, <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddend">FAddend</a> &amp; A1)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drill down the U-D chain one step to find the definition of V, and try to break the definition into one or two addends.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a98a8d19d3b1ddbc0930fbbd5c0c37c4c">FAddend</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ae46c23ed39de6de6cf9ec6e57755e4c5">llvm::ConstantFP::isZero</a>, <a href="#a51c0cc15117f0497c8ec309549be6e88">negate</a> and <a href="#a5b3e4c25084e471d7f921305e3f88829">set</a>.</p>


<p>Referenced by <a href="#a48a27ff66f7f36744592735b09bcd8d4">drillAddendDownOneStep</a> and <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddcombine/#a47fa84ad65315d095fa4153566cbd0b6">anonymous{InstCombineAddSub.cpp}::FAddCombine::simplify</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp">InstCombineAddSub.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
