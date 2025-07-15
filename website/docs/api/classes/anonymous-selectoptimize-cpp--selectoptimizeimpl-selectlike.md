---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SelectLike` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike">SelectLike</a> is an abstraction over <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> and other operations that can act like selects. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648e2bbb8bcd79026c72e7ef07515846">SelectLike</a> (Instruction *I, bool Inverted=false, unsigned CondIdx=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a262cc55e52583b7a30afb7bf04fad7d3">getI</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea24291ce3601f0823b47f196bfd0de">getI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12cc212f8876eee8d0ff6683e1b6579e">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee80c7bc7828d0fc244636ade75c641">getConditionOpIndex</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f084cd73f3a03dfea46ce6ede486c8c">getTrueValue</a> (bool HonorInverts=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the true value for the <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike">SelectLike</a> instruction. <a href="#a4f084cd73f3a03dfea46ce6ede486c8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6782369911061765c5975ac4d777f38">getFalseValue</a> (bool HonorInverts=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the false value for the <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike">SelectLike</a> instruction. <a href="#ad6782369911061765c5975ac4d777f38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/#a7e50b359af6e42ca84e7152e049da6e5">Scaled64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad811cf3b50296c6f065133a96294e28">getOpCostOnBranch</a> (bool IsTrue, const DenseMap&lt; const Instruction *, CostInfo &gt; &amp;InstCostMap, const TargetTransformInfo *TTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the NonPredCost cost of the op on <span class="doxyComputerOutput">isTrue</span> branch, given the costs in <span class="doxyComputerOutput">InstCostMap</span>. <a href="#aad811cf3b50296c6f065133a96294e28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9582d717d8218768a25fc37fa654934">I</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The select (/or) instruction. <a href="#aa9582d717d8218768a25fc37fa654934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a921ac60f0ce1b2859645ad4c85dbc6f6">Inverted</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this select is inverted, "not(cond), FalseVal, TrueVal", as opposed to the original condition. <a href="#a921ac60f0ce1b2859645ad4c85dbc6f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a8214fe0c6b69b981aa64c8c715a8a">CondIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the operand that depends on condition. <a href="#ab9a8214fe0c6b69b981aa64c8c715a8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike">SelectLike</a> is an abstraction over <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> and other operations that can act like selects.</p>


<p>For example <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">Or(Zext(icmp), X)</a> can be treated like select(icmp, X|1, X).</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SelectLike() {#a648e2bbb8bcd79026c72e7ef07515846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::SelectLike (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, bool Inverted=false, unsigned CondIdx=0)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getConditionOpIndex() {#a6ee80c7bc7828d0fc244636ade75c641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getConditionOpIndex ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>

</div>
</div>

### getFalseValue() {#ad6782369911061765c5975ac4d777f38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getFalseValue (bool HonorInverts=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Return the false value for the <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike">SelectLike</a> instruction.</p>


<p>For example the getFalseValue of a select or <span class="doxyComputerOutput">x</span> in <span class="doxyComputerOutput">or(zext(c), x)</span> (which is <span class="doxyComputerOutput">select(c, x|1, x)</span>)</p>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a4f084cd73f3a03dfea46ce6ede486c8c">getTrueValue</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#aad811cf3b50296c6f065133a96294e28">getOpCostOnBranch</a> and <a href="#a4f084cd73f3a03dfea46ce6ede486c8c">getTrueValue</a>.</p>

</div>
</div>

### getI() {#a262cc55e52583b7a30afb7bf04fad7d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getI ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>


<p>Referenced by <a href="#aad811cf3b50296c6f065133a96294e28">getOpCostOnBranch</a>.</p>

</div>
</div>

### getI() {#aeea24291ce3601f0823b47f196bfd0de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getI ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>

</div>
</div>

### getOpCostOnBranch() {#aad811cf3b50296c6f065133a96294e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scaled64 anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getOpCostOnBranch (bool IsTrue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/structs/anonymous-selectoptimize-cpp-/selectoptimizeimpl/costinfo">CostInfo</a> &gt; &amp; InstCostMap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI)</td>
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

<p>Return the NonPredCost cost of the op on <span class="doxyComputerOutput">isTrue</span> branch, given the costs in <span class="doxyComputerOutput">InstCostMap</span>.</p>


<p>This may need to be generated for select-like instructions.</p>


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a643e49ec18ba075b047b4bbc026f4774">llvm::ScaledNumber&lt; uint64_t &gt;::get</a>, <a href="#ad6782369911061765c5975ac4d777f38">getFalseValue</a>, <a href="#a262cc55e52583b7a30afb7bf04fad7d3">getI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>, <a href="#a4f084cd73f3a03dfea46ce6ede486c8c">getTrueValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a69da904ff7dd16157dfda88b1c050db0">llvm::ScaledNumber&lt; uint64_t &gt;::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba81b2c6f1f1e13e4a575e6d1c8b29b6e1">llvm::TargetTransformInfo::TCK_Latency</a>.</p>

</div>
</div>

### getTrueValue() {#a4f084cd73f3a03dfea46ce6ede486c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getTrueValue (bool HonorInverts=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Return the true value for the <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike">SelectLike</a> instruction.</p>


<p>Note this may not exist for all <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike">SelectLike</a> instructions. For example, for <span class="doxyComputerOutput">or(zext(c), x)</span> the true value would be <span class="doxyComputerOutput">or(x,1)</span>. As this value does not exist, nullptr is returned.</p>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad6782369911061765c5975ac4d777f38">getFalseValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ad6782369911061765c5975ac4d777f38">getFalseValue</a> and <a href="#aad811cf3b50296c6f065133a96294e28">getOpCostOnBranch</a>.</p>

</div>
</div>

### getType() {#a12cc212f8876eee8d0ff6683e1b6579e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getType ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CondIdx {#ab9a8214fe0c6b69b981aa64c8c715a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::CondIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the operand that depends on condition.</p>


<p>Only for select-like instruction such as Or/Add.</p>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>

</div>
</div>

### I {#aa9582d717d8218768a25fc37fa654934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::I</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The select (/or) instruction.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>

</div>
</div>

### Inverted {#a921ac60f0ce1b2859645ad4c85dbc6f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::Inverted = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this select is inverted, "not(cond), FalseVal, TrueVal", as opposed to the original condition.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
