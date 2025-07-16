---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/constantfprange-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ConstantFPRange.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfprange-h">llvm/IR/ConstantFPRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static APFloat::cmpResult</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a095c6a1883dc33dfe9e5ffba9613a3ec">strictCompare</a> (const APFloat &amp;LHS, const APFloat &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5f56c6dbd79483472793e618ad64f8a">isNonCanonicalEmptySet</a> (const APFloat &amp;Lower, const APFloat &amp;Upper)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e7cbf32894b4feb398e5ff39919ca1">canonicalizeRange</a> (APFloat &amp;Lower, APFloat &amp;Upper)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad23e1346d5dc008131b5a683270263">fcmpPredExcludesEqual</a> (FCmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true for ULT/UGT/OLT/OGT. <a href="#a1ad23e1346d5dc008131b5a683270263">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6196262129213645adfe2c1f4bfc562">makeLessThan</a> (APFloat V, FCmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return [-inf, V) or [-inf, V]. <a href="#aa6196262129213645adfe2c1f4bfc562">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac402a26d55b042a1350ed55c9fa2f36">makeGreaterThan</a> (APFloat V, FCmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return (V, +inf] or [V, +inf]. <a href="#aac402a26d55b042a1350ed55c9fa2f36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e9cfe70f7f772a846b632fd67a1b578">extendZeroIfEqual</a> (const ConstantFPRange &amp;CR, FCmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make sure that +0/-0 are both included in the range. <a href="#a0e9cfe70f7f772a846b632fd67a1b578">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe0a2d80588accff7111123a015df68">setNaNField</a> (const ConstantFPRange &amp;CR, FCmpInst::Predicate Pred)</td>
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


<div class="doxySectionDef">

## Functions

### canonicalizeRange() {#aa6e7cbf32894b4feb398e5ff39919ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void canonicalizeRange (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Lower, <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Upper)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a>, <a href="#ae5f56c6dbd79483472793e618ad64f8a">isNonCanonicalEmptySet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a980922d17596d03dcc175b9fa44c44ad">llvm::ConstantFPRange::intersectWith</a>.</p>

</div>
</div>

### extendZeroIfEqual() {#a0e9cfe70f7f772a846b632fd67a1b578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange extendZeroIfEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; CR, FCmpInst::Predicate Pred)</td>
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

<p>Make sure that +0/-0 are both included in the range.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a1280f3ee32c39f4732e88d94f62ba72d">llvm::ConstantFPRange::containsQNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a3c822545e0122b707c5953be7c06fef3">llvm::ConstantFPRange::containsSNaN</a>, <a href="#a1ad23e1346d5dc008131b5a683270263">fcmpPredExcludesEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#aecf00eeae75d39bfd560934ea6657ce3">llvm::ConstantFPRange::getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#aeb1ef69f315dc2f8249e020780192e3d">llvm::ConstantFPRange::getUpper</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a84ec432d02febd1b518e9453b1a0eba9">llvm::ConstantFPRange::makeAllowedFCmpRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">llvm::ConstantFPRange::makeSatisfyingFCmpRegion</a>.</p>

</div>
</div>

### fcmpPredExcludesEqual() {#a1ad23e1346d5dc008131b5a683270263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool fcmpPredExcludesEqual (FCmpInst::Predicate Pred)</td>
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

<p>Return true for ULT/UGT/OLT/OGT.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>.</p>


<p>Referenced by <a href="#a0e9cfe70f7f772a846b632fd67a1b578">extendZeroIfEqual</a>, <a href="#aac402a26d55b042a1350ed55c9fa2f36">makeGreaterThan</a> and <a href="#aa6196262129213645adfe2c1f4bfc562">makeLessThan</a>.</p>

</div>
</div>

### isNonCanonicalEmptySet() {#ae5f56c6dbd79483472793e618ad64f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNonCanonicalEmptySet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Lower, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Upper)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca9f45fb1a56fb0564ec5ede93dad96cc4">llvm::APFloatBase::cmpGreaterThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="#a095c6a1883dc33dfe9e5ffba9613a3ec">strictCompare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="#aa6e7cbf32894b4feb398e5ff39919ca1">canonicalizeRange</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a0b7b8a013caf003e5249f15aeff08d02">llvm::ConstantFPRange::ConstantFPRange</a>.</p>

</div>
</div>

### makeGreaterThan() {#aac402a26d55b042a1350ed55c9fa2f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange makeGreaterThan (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> V, FCmpInst::Predicate Pred)</td>
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

<p>Return (V, +inf] or [V, +inf].</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="#a1ad23e1346d5dc008131b5a683270263">fcmpPredExcludesEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a340071757f3e0c6524e70a873212adee">llvm::ConstantFPRange::getNonNaN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a84ec432d02febd1b518e9453b1a0eba9">llvm::ConstantFPRange::makeAllowedFCmpRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">llvm::ConstantFPRange::makeSatisfyingFCmpRegion</a>.</p>

</div>
</div>

### makeLessThan() {#aa6196262129213645adfe2c1f4bfc562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange makeLessThan (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> V, FCmpInst::Predicate Pred)</td>
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

<p>Return [-inf, V) or [-inf, V].</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="#a1ad23e1346d5dc008131b5a683270263">fcmpPredExcludesEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a340071757f3e0c6524e70a873212adee">llvm::ConstantFPRange::getNonNaN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a84ec432d02febd1b518e9453b1a0eba9">llvm::ConstantFPRange::makeAllowedFCmpRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">llvm::ConstantFPRange::makeSatisfyingFCmpRegion</a>.</p>

</div>
</div>

### setNaNField() {#affe0a2d80588accff7111123a015df68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantFPRange setNaNField (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfprange">ConstantFPRange</a> &amp; CR, FCmpInst::Predicate Pred)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#aecf00eeae75d39bfd560934ea6657ce3">llvm::ConstantFPRange::getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#aeb1ef69f315dc2f8249e020780192e3d">llvm::ConstantFPRange::getUpper</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aae55ea42185b7528c0c149625b998968">llvm::CmpInst::isUnordered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a84ec432d02febd1b518e9453b1a0eba9">llvm::ConstantFPRange::makeAllowedFCmpRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">llvm::ConstantFPRange::makeSatisfyingFCmpRegion</a>.</p>

</div>
</div>

### strictCompare() {#a095c6a1883dc33dfe9e5ffba9613a3ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::cmpResult strictCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp">ConstantFPRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca95e6b9c1e27b4949da4c40f5afb842a6">llvm::APFloatBase::cmpEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca9f45fb1a56fb0564ec5ede93dad96cc4">llvm::APFloatBase::cmpGreaterThan</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca6bd5099a8de38cdb7b0a65bf451c4fa7">llvm::APFloatBase::cmpLessThan</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#adc453b2dc648e45c35ae756cbe300cb8">llvm::ConstantFPRange::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a28af69a643d5ba066a7492b98e71c6bb">llvm::ConstantFPRange::contains</a> and <a href="#ae5f56c6dbd79483472793e618ad64f8a">isNonCanonicalEmptySet</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
