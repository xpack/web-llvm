---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/switchsuccwrapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SwitchSuccWrapper` Struct

<p>Checking whether two cases of <a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a> are equal depends on the contents of the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> and the incoming values of their successor PHINodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct SwitchSuccWrapper { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0765647c64190b61909606646061c314">Dest</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 8 &gt; &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d0092e0f010e6f8831d0b4797f1a8d3">PhiPredIVs</a></td>
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

<p>Checking whether two cases of <a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a> are equal depends on the contents of the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> and the incoming values of their successor PHINodes.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">PHINode::getIncomingValueForBlock</a> is O(|Preds|), so we'd like to avoid calling this function on each <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> every time isEqual is called, especially since the same <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> may be passed as an argument multiple times. To do this, we can precompute a map of <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> -&gt; Pred <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> -&gt; IncomingValue and add it in the Wrapper so isEqual can do O(1) checking of the incoming values.</p>


<p>Definition at line 7500 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Dest {#a0765647c64190b61909606646061c314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* SwitchSuccWrapper::Dest</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7501 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>.</p>

</div>
</div>

### PhiPredIVs {#a0d0092e0f010e6f8831d0b4797f1a8d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PHINode *, SmallDenseMap&lt;BasicBlock *, Value *, 8&gt; &gt;* SwitchSuccWrapper::PhiPredIVs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
