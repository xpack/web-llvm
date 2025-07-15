---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/selectpatternresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SelectPatternResult` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::SelectPatternResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a6bf471c1030973649c2e426afc212097">SelectPatternFlavor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ca9c2098248eac9051008d6eb9f321d">Flavor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ab1ec0705ee0a9265c1533bad94aae26f">SelectPatternNaNBehavior</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0258a1ec39b9906e918a1a60fdfbc51">NaNBehavior</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af27f528f038a2334dd80b7c77246fe">Ordered</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only applicable if Flavor is SPF_FMINNUM or SPF_FMAXNUM. <a href="#a6af27f528f038a2334dd80b7c77246fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c732c9e96c40976f0509fe0233fe7b">isMinOrMax</a> (SelectPatternFlavor SPF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When implementing this min/max pattern as fcmp; select, does the fcmp have to be ordered? <a href="#a94c732c9e96c40976f0509fe0233fe7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Flavor {#a3ca9c2098248eac9051008d6eb9f321d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectPatternFlavor llvm::SelectPatternResult::Flavor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a323137971325611ddc1b899b00b8aaa0">llvm::canConvertToMinOrMaxIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae83866ca1a903e74fd6b66c1fec0d528">llvm::ARMTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6a2d7b6d01962d7dff4c6e3e87f4575e">isSignedMinMaxClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a0deafca5c66f3b900139bcf024085e8f">isSSATMinMaxPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab2e632f73c35674249cdee998f104cc0">matchMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>.</p>

</div>
</div>

### NaNBehavior {#ab0258a1ec39b9906e918a1a60fdfbc51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectPatternNaNBehavior llvm::SelectPatternResult::NaNBehavior</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>

</div>
</div>

### Ordered {#a6af27f528f038a2334dd80b7c77246fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SelectPatternResult::Ordered</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Only applicable if Flavor is SPF_FMINNUM or SPF_FMAXNUM.</p>

<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isMinOrMax() {#a94c732c9e96c40976f0509fe0233fe7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SelectPatternResult::isMinOrMax (<a href="/web-llvm/docs/api/namespaces/llvm/#a6bf471c1030973649c2e426afc212097">SelectPatternFlavor</a> SPF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When implementing this min/max pattern as fcmp; select, does the fcmp have to be ordered?</p>


<p>Return true if <span class="doxyComputerOutput">SPF</span> is a min or a max pattern.</p>


<p>Definition at line 1145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6bf471c1030973649c2e426afc212097a07d293fd946951d9655259c5e9b93356">llvm::SPF_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6bf471c1030973649c2e426afc212097a08658871fecea100ad724bd8b1c3ae56">llvm::SPF_NABS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6bf471c1030973649c2e426afc212097aee3dafa9fac8f6fa1e1110ef463cc452">llvm::SPF_UNKNOWN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a323137971325611ddc1b899b00b8aaa0">llvm::canConvertToMinOrMaxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a6415fb68bc55f3a316aa414a5c2c0ab2">llvm::RecurrenceDescriptor::getReductionOpChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a77bc4c2ac5bdfea178b15627e282cc8c">matchMinMaxOfMinMax</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afa1ff3254ee225171cb55d46b0eab145">simplifySelectWithICmpCond</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
