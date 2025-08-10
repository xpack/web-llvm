---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dbgvariableintrinsic
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DbgVariableIntrinsic` Class

<p>This is the common base class for debug info intrinsics for variables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DbgVariableIntrinsic { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbginfointrinsic">DbgInfoIntrinsic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the common base class for debug info intrinsics. <a href="/web-llvm/docs/api/classes/llvm/dbginfointrinsic/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgdeclareinst">DbgDeclareInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents the llvm.dbg.declare instruction. <a href="/web-llvm/docs/api/classes/llvm/dbgdeclareinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst">DbgValueInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents the llvm.dbg.value instruction. <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/location-op-iterator">location_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aee0a03668ffd951c891317d8a0c30e">location_ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the locations corresponding to the variable referenced by the debug info intrinsic. <a href="#a1aee0a03668ffd951c891317d8a0c30e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5702a1d09ac6ee86196a38b3f682a570">getVariableLocationOp</a> (unsigned OpIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d995a069d73ebebbd6a4aace342ef76">replaceVariableLocationOp</a> (Value *OldValue, Value *NewValue, bool AllowEmpty=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f66dfca05bfb9a4f5bddbad1ad043e6">replaceVariableLocationOp</a> (unsigned OpIdx, Value *NewValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fb252b26b548e2ed904e02782013abd">addVariableLocationOps</a> (ArrayRef&lt; Value * &gt; NewValues, DIExpression *NewExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adding a new location operand will always result in this intrinsic using an ArgList, and must always be accompanied by a new expression that uses the new operand. <a href="#a1fb252b26b548e2ed904e02782013abd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180601bf52af11126dcf05266de02500">setVariable</a> (DILocalVariable *NewVar)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71808acf992f787300ec18d5700f09cc">setExpression</a> (DIExpression *NewExpr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8976759fe7e2d0329628f86b42957704">getNumVariableLocationOps</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfa0ffc95fedffcb2ac3cca51872af7a">hasArgList</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c005ab74340f04df81ce12b8511a27a">isAddressOfVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this describe the address of a local variable. <a href="#a8c005ab74340f04df81ce12b8511a27a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26dfaa3ce6f23365ff2ce9a105514ac7">isValueOfVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this describes the value of a local variable. <a href="#a26dfaa3ce6f23365ff2ce9a105514ac7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2539583fcfa83b3ecdfc1fea52cff6">setKillLocation</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7f3b3d318132753954ca4da891245d8">isKillLocation</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854857be09a21f27fb21ba872fe6f639">getVariable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1707c1c1ab1f3278424f265893c87fb">getExpression</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753c375d2c90d5f7e04af2ea99648ac3">getRawLocation</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper">RawLocationWrapper</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af28b06f97e6a2341656475dbbd4a5e79">getWrappedLocation</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1e5c61ab8cebb2b9a4c7b9e20d87783">getRawVariable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8046dbd496e42d7fc3079474e62cb02">getRawExpression</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2faebe0374c9b44fdb9bd71cafdef798">setRawLocation</a> (Metadata *Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> of this should generally be avoided; instead, replaceVariableLocationOp and addVariableLocationOps should be used where possible to avoid creating invalid state. <a href="#a2faebe0374c9b44fdb9bd71cafdef798">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad00657bed806e5e3e4f3a55e48c97023">getFragmentSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size (in bits) of the variable, or fragment of the variable that is described. <a href="#ad00657bed806e5e3e4f3a55e48c97023">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642f20d33151f41a46e601f14910989c">getFragment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the FragmentInfo for the variable. <a href="#a642f20d33151f41a46e601f14910989c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16b5a4db7225864cc5615c683d946f87">getFragmentOrEntireVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the FragmentInfo for the variable if it exists, otherwise return a FragmentInfo that covers the entire variable if the variable size is known, otherwise return a zero-sized fragment. <a href="#a16b5a4db7225864cc5615c683d946f87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae723478bb89b56b7c11d9184e627c9c5">setArgOperand</a> (unsigned i, Value *v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6ec69f4fdb9928d76326e4db900317">setOperand</a> (unsigned i, Value *v)</td>
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

## Casting methods Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f67ba2a41221c586f0af8b1cdf71d4">classof</a> (const IntrinsicInst *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a8e1943fe4042c62f1de477c609d0c">classof</a> (const Value *V)</td>
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

<p>This is the common base class for debug info intrinsics for variables.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addVariableLocationOps() {#a1fb252b26b548e2ed904e02782013abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgVariableIntrinsic::addVariableLocationOps (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; NewValues, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * NewExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adding a new location operand will always result in this intrinsic using an ArgList, and must always be accompanied by a new expression that uses the new operand.</p>

<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a51072a9980c37f5cce2a30e9dc4b3057">llvm::DIArgList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67e80dcdf6a5358a9d3defbe0e8f6c34">llvm::getAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a8976759fe7e2d0329628f86b42957704">getNumVariableLocationOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a1aee0a03668ffd951c891317d8a0c30e">location_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ae723478bb89b56b7c11d9184e627c9c5">setArgOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### getExpression() {#ad1707c1c1ab1f3278424f265893c87fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * llvm::DbgVariableIntrinsic::getExpression ()</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#ae8046dbd496e42d7fc3079474e62cb02">getRawExpression</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab77dd880f8a4804500c2fd5c4df979ee">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79e6c0c958b2de133d4b9d0e2c62f1e4">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8946e172b10c0ef5eaebb28ebb7662ad">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="#a642f20d33151f41a46e601f14910989c">getFragment</a>, <a href="#a16b5a4db7225864cc5615c683d946f87">getFragmentOrEntireVariable</a>, <a href="#ad00657bed806e5e3e4f3a55e48c97023">getFragmentSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36d31b1eb92d4a290df06be8709c39be">llvm::InsertDebugValueAtStoreLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a5a020f0ab461a1f6e3b87aff314bd040">insertNewDbgInst</a>, <a href="#af7f3b3d318132753954ca4da891245d8">isKillLocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a58217c3769fe3ee4ac0d221b836849f0">llvm::FastISel::selectIntrinsicCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0bdd0669ab7b82ba709bfedcb751dcc3">valueCoversEntireFragment</a>.</p>

</div>
</div>

### getFragment() {#a642f20d33151f41a46e601f14910989c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DIExpression::FragmentInfo &gt; llvm::DbgVariableIntrinsic::getFragment ()</td>
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

<p>Get the FragmentInfo for the variable.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="#ad1707c1c1ab1f3278424f265893c87fb">getExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a7cc5f1632a4c520497898439c17dc026">llvm::DIExpression::getFragmentInfo</a>.</p>

</div>
</div>

### getFragmentOrEntireVariable() {#a16b5a4db7225864cc5615c683d946f87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression::FragmentInfo llvm::DbgVariableIntrinsic::getFragmentOrEntireVariable ()</td>
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

<p>Get the FragmentInfo for the variable if it exists, otherwise return a FragmentInfo that covers the entire variable if the variable size is known, otherwise return a zero-sized fragment.</p>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="#ad1707c1c1ab1f3278424f265893c87fb">getExpression</a>, <a href="#ad00657bed806e5e3e4f3a55e48c97023">getFragmentSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo/#aa448040bf5ec2ebafc3dbe0eb15b6d55">llvm::DbgVariableFragmentInfo::OffsetInBits</a> and <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo/#af581a7bb056b2b642d6705cc4af65fa2">llvm::DbgVariableFragmentInfo::SizeInBits</a>.</p>

</div>
</div>

### getFragmentSizeInBits() {#ad00657bed806e5e3e4f3a55e48c97023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DbgVariableIntrinsic::getFragmentSizeInBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the size (in bits) of the variable, or fragment of the variable that is described.</p>

<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="#ad1707c1c1ab1f3278424f265893c87fb">getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a6b5977deeb9f99e156685e190de78403">llvm::DIVariable::getSizeInBits</a> and <a href="#a854857be09a21f27fb21ba872fe6f639">getVariable</a>.</p>


<p>Referenced by <a href="#a16b5a4db7225864cc5615c683d946f87">getFragmentOrEntireVariable</a>.</p>

</div>
</div>

### getNumVariableLocationOps() {#a8976759fe7e2d0329628f86b42957704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DbgVariableIntrinsic::getNumVariableLocationOps ()</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper/#ade5d82896273c4f2c2fa0c72070fc023">llvm::RawLocationWrapper::getNumVariableLocationOps</a> and <a href="#af28b06f97e6a2341656475dbbd4a5e79">getWrappedLocation</a>.</p>


<p>Referenced by <a href="#a1fb252b26b548e2ed904e02782013abd">addVariableLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgdeclareinst/#a3dd0197b425429468709af927dd71f08">llvm::DbgDeclareInst::getAddress</a>, <a href="#a9f66dfca05bfb9a4f5bddbad1ad043e6">replaceVariableLocationOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0bdd0669ab7b82ba709bfedcb751dcc3">valueCoversEntireFragment</a>.</p>

</div>
</div>

### getRawExpression() {#ae8046dbd496e42d7fc3079474e62cb02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DbgVariableIntrinsic::getRawExpression ()</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>


<p>Referenced by <a href="#ad1707c1c1ab1f3278424f265893c87fb">getExpression</a>.</p>

</div>
</div>

### getRawLocation() {#a753c375d2c90d5f7e04af2ea99648ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DbgVariableIntrinsic::getRawLocation ()</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a0d93b962edf730134f28184361570932">llvm::DbgVariableRecord::DbgVariableRecord</a> and <a href="#af28b06f97e6a2341656475dbbd4a5e79">getWrappedLocation</a>.</p>

</div>
</div>

### getRawVariable() {#ac1e5c61ab8cebb2b9a4c7b9e20d87783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DbgVariableIntrinsic::getRawVariable ()</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>


<p>Referenced by <a href="#a854857be09a21f27fb21ba872fe6f639">getVariable</a>.</p>

</div>
</div>

### getVariable() {#a854857be09a21f27fb21ba872fe6f639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalVariable * llvm::DbgVariableIntrinsic::getVariable ()</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#ac1e5c61ab8cebb2b9a4c7b9e20d87783">getRawVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab77dd880f8a4804500c2fd5c4df979ee">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79e6c0c958b2de133d4b9d0e2c62f1e4">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8946e172b10c0ef5eaebb28ebb7662ad">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4514f516df040b468e552a28163b3747">getAggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a30791b6c651e6313b0aab3f01da9d57b">getAggregateVariable</a>, <a href="#ad00657bed806e5e3e4f3a55e48c97023">getFragmentSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36d31b1eb92d4a290df06be8709c39be">llvm::InsertDebugValueAtStoreLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a5a020f0ab461a1f6e3b87aff314bd040">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab994e75dc5cae892a87ae9a86d4b767a">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a58217c3769fe3ee4ac0d221b836849f0">llvm::FastISel::selectIntrinsicCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0bdd0669ab7b82ba709bfedcb751dcc3">valueCoversEntireFragment</a>.</p>

</div>
</div>

### getVariableLocationOp() {#a5702a1d09ac6ee86196a38b3f682a570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * DbgVariableIntrinsic::getVariableLocationOp (unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper/#a5b9c652a5b3b050be7f6363d136d15d6">llvm::RawLocationWrapper::getVariableLocationOp</a> and <a href="#af28b06f97e6a2341656475dbbd4a5e79">getWrappedLocation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgdeclareinst/#a3dd0197b425429468709af927dd71f08">llvm::DbgDeclareInst::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst/#a82f5c63aa1e00276f988174976c57903">llvm::DbgValueInst::getValue</a>, <a href="#a9f66dfca05bfb9a4f5bddbad1ad043e6">replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0bdd0669ab7b82ba709bfedcb751dcc3">valueCoversEntireFragment</a>.</p>

</div>
</div>

### getWrappedLocation() {#af28b06f97e6a2341656475dbbd4a5e79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RawLocationWrapper llvm::DbgVariableIntrinsic::getWrappedLocation ()</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="#a753c375d2c90d5f7e04af2ea99648ac3">getRawLocation</a>.</p>


<p>Referenced by <a href="#a8976759fe7e2d0329628f86b42957704">getNumVariableLocationOps</a>, <a href="#a5702a1d09ac6ee86196a38b3f682a570">getVariableLocationOp</a>, <a href="#acfa0ffc95fedffcb2ac3cca51872af7a">hasArgList</a>, <a href="#af7f3b3d318132753954ca4da891245d8">isKillLocation</a> and <a href="#a1aee0a03668ffd951c891317d8a0c30e">location_ops</a>.</p>

</div>
</div>

### hasArgList() {#acfa0ffc95fedffcb2ac3cca51872af7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableIntrinsic::hasArgList ()</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="#af28b06f97e6a2341656475dbbd4a5e79">getWrappedLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper/#acaf135b0c3da7778910e043864bcf1ac">llvm::RawLocationWrapper::hasArgList</a>.</p>


<p>Referenced by <a href="#a9f66dfca05bfb9a4f5bddbad1ad043e6">replaceVariableLocationOp</a>, <a href="#a3d995a069d73ebebbd6a4aace342ef76">replaceVariableLocationOp</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a58217c3769fe3ee4ac0d221b836849f0">llvm::FastISel::selectIntrinsicCall</a>.</p>

</div>
</div>

### isAddressOfVariable() {#a8c005ab74340f04df81ce12b8511a27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableIntrinsic::isAddressOfVariable ()</td>
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

<p>Does this describe the address of a local variable.</p>


<p>True for dbg.declare, but not dbg.value, which describes its value, or dbg.assign, which describes a combination of the variable's value and address.</p>


<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8946e172b10c0ef5eaebb28ebb7662ad">llvm::ConvertDebugDeclareToDebugValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0bdd0669ab7b82ba709bfedcb751dcc3">valueCoversEntireFragment</a>.</p>

</div>
</div>

### isKillLocation() {#af7f3b3d318132753954ca4da891245d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableIntrinsic::isKillLocation ()</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="#ad1707c1c1ab1f3278424f265893c87fb">getExpression</a>, <a href="#af28b06f97e6a2341656475dbbd4a5e79">getWrappedLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper/#ac8ed1622d5056cac8ace0c5d46f1e66e">llvm::RawLocationWrapper::isKillLocation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a579e878e02e34bf9699e3d82da2bc070">removeUndefDbgAssignsFromEntryBlock</a>.</p>

</div>
</div>

### isValueOfVariable() {#a26dfaa3ce6f23365ff2ce9a105514ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableIntrinsic::isValueOfVariable ()</td>
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

<p>Determine if this describes the value of a local variable.</p>


<p>It is true for dbg.value, but false for dbg.declare, which describes its address, and false for dbg.assign, which describes a combination of the variable's value and address.</p>


<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>.</p>

</div>
</div>

### location\_ops() {#a1aee0a03668ffd951c891317d8a0c30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; location_op_iterator &gt; DbgVariableIntrinsic::location_ops ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the locations corresponding to the variable referenced by the debug info intrinsic.</p>


<p>Depending on the intrinsic, this could be the variable's value or its address.</p>


<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="#af28b06f97e6a2341656475dbbd4a5e79">getWrappedLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper/#a58600c67115e2e8118e00ca77d73172d">llvm::RawLocationWrapper::location_ops</a>.</p>


<p>Referenced by <a href="#a1fb252b26b548e2ed904e02782013abd">addVariableLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst/#a1469e03438be312e275d87c194fbd384">llvm::DbgValueInst::getValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4dfea19770364b880a77c3f0c1c0f67c">llvm::insertDebugValuesForPHIs</a>, <a href="#a3d995a069d73ebebbd6a4aace342ef76">replaceVariableLocationOp</a> and <a href="#aaf2539583fcfa83b3ecdfc1fea52cff6">setKillLocation</a>.</p>

</div>
</div>

### replaceVariableLocationOp() {#a3d995a069d73ebebbd6a4aace342ef76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgVariableIntrinsic::replaceVariableLocationOp (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OldValue, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewValue, bool AllowEmpty=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a51072a9980c37f5cce2a30e9dc4b3057">llvm::DIArgList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67e80dcdf6a5358a9d3defbe0e8f6c34">llvm::getAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#acfa0ffc95fedffcb2ac3cca51872af7a">hasArgList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a1aee0a03668ffd951c891317d8a0c30e">location_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#ae723478bb89b56b7c11d9184e627c9c5">setArgOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4dfea19770364b880a77c3f0c1c0f67c">llvm::insertDebugValuesForPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a>, <a href="#aaf2539583fcfa83b3ecdfc1fea52cff6">setKillLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#acf65ce696212774397a4c1a3afc44275">updateOneDbgValueForAlloca</a>.</p>

</div>
</div>

### replaceVariableLocationOp() {#a9f66dfca05bfb9a4f5bddbad1ad043e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgVariableIntrinsic::replaceVariableLocationOp (unsigned OpIdx, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a51072a9980c37f5cce2a30e9dc4b3057">llvm::DIArgList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67e80dcdf6a5358a9d3defbe0e8f6c34">llvm::getAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a8976759fe7e2d0329628f86b42957704">getNumVariableLocationOps</a>, <a href="#a5702a1d09ac6ee86196a38b3f682a570">getVariableLocationOp</a>, <a href="#acfa0ffc95fedffcb2ac3cca51872af7a">hasArgList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#ae723478bb89b56b7c11d9184e627c9c5">setArgOperand</a>.</p>

</div>
</div>

### setExpression() {#a71808acf992f787300ec18d5700f09cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableIntrinsic::setExpression (<a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * NewExpr)</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a> and <a href="#ae723478bb89b56b7c11d9184e627c9c5">setArgOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#acf65ce696212774397a4c1a3afc44275">updateOneDbgValueForAlloca</a>.</p>

</div>
</div>

### setKillLocation() {#aaf2539583fcfa83b3ecdfc1fea52cff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableIntrinsic::setKillLocation ()</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a1aee0a03668ffd951c891317d8a0c30e">location_ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a434449d5a0f4b334aca9163b13b6286ba02b848adda8d7d33a2b25d87dbef1d75">Poison</a> and <a href="#a3d995a069d73ebebbd6a4aace342ef76">replaceVariableLocationOp</a>.</p>

</div>
</div>

### setRawLocation() {#a2faebe0374c9b44fdb9bd71cafdef798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableIntrinsic::setRawLocation (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Location)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> of this should generally be avoided; instead, replaceVariableLocationOp and addVariableLocationOps should be used where possible to avoid creating invalid state.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a> and <a href="#ae723478bb89b56b7c11d9184e627c9c5">setArgOperand</a>.</p>

</div>
</div>

### setVariable() {#a180601bf52af11126dcf05266de02500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableIntrinsic::setVariable (<a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * NewVar)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a> and <a href="#ae723478bb89b56b7c11d9184e627c9c5">setArgOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### setArgOperand() {#ae723478bb89b56b7c11d9184e627c9c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableIntrinsic::setArgOperand (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/callbase/#abc10b887caad109288ffceb230493a85">llvm::CallBase::setArgOperand</a>.</p>


<p>Referenced by <a href="#a1fb252b26b548e2ed904e02782013abd">addVariableLocationOps</a>, <a href="#a9f66dfca05bfb9a4f5bddbad1ad043e6">replaceVariableLocationOp</a>, <a href="#a3d995a069d73ebebbd6a4aace342ef76">replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#af50410033f7fa1450e7030aa25eae45e">llvm::DbgAssignIntrinsic::setAddressExpression</a>, <a href="#a71808acf992f787300ec18d5700f09cc">setExpression</a>, <a href="#a2faebe0374c9b44fdb9bd71cafdef798">setRawLocation</a> and <a href="#a180601bf52af11126dcf05266de02500">setVariable</a>.</p>

</div>
</div>

### setOperand() {#aae6ec69f4fdb9928d76326e4db900317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgVariableIntrinsic::setOperand (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#aef2660c212a6794faf7ec16cae82248a">llvm::DbgAssignIntrinsic::setAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#a4c46f4f09337677b638261fc6487aade">llvm::DbgAssignIntrinsic::setAssignId</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#a06c7810ad5d205218bce57bff448b2e3">llvm::DbgAssignIntrinsic::setValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Casting methods

### classof {#ac6f67ba2a41221c586f0af8b1cdf71d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableIntrinsic::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * I)</td>
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



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a64a8e1943fe4042c62f1de477c609d0c">classof</a>.</p>

</div>
</div>

### classof {#a64a8e1943fe4042c62f1de477c609d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgVariableIntrinsic::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac6f67ba2a41221c586f0af8b1cdf71d4">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp">IntrinsicInst.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
