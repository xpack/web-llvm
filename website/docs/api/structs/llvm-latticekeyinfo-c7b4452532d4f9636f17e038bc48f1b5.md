---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/latticekeyinfo-c7b4452532d4f9636f17e038bc48f1b5
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LatticeKeyInfo` Struct Template Reference

<p>A specialization of <a href="/web-llvm/docs/api/structs/llvm/latticekeyinfo">LatticeKeyInfo</a> for CVPLatticeKeys. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LatticeKeyInfo&lt;CVPLatticeKey&gt; { ... }
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4633a2b8a3baf978de113248f0396ee4">getValueFromLatticeKey</a> (CVPLatticeKey Key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static CVPLatticeKey</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04bb932f1650040d14559e18d189ae8c">getLatticeKeyFromValue</a> (Value *V)</td>
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

<p>A specialization of <a href="/web-llvm/docs/api/structs/llvm/latticekeyinfo">LatticeKeyInfo</a> for CVPLatticeKeys.</p>


<p>The generic solver must translate between LatticeKeys and LLVM Values when adding Values to its work list and inspecting the state of control-flow related values.</p>


<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getLatticeKeyFromValue() {#a04bb932f1650040d14559e18d189ae8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVPLatticeKey llvm::LatticeKeyInfo&lt; CVPLatticeKey &gt;::getLatticeKeyFromValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#a5f10072974ec01bdf70a2f2215f44b23a0ba7583639a274c434bbe6ef797115a4">anonymous{CalledValuePropagation.cpp}::Register</a>.</p>

</div>
</div>

### getValueFromLatticeKey() {#a4633a2b8a3baf978de113248f0396ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::LatticeKeyInfo&lt; CVPLatticeKey &gt;::getValueFromLatticeKey (CVPLatticeKey Key)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
