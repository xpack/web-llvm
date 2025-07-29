---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcstatepointinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCStatepointInst` Class

<p>Represents a gc.statepoint intrinsic call. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GCStatepointInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">llvm/IR/Statepoint.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for all callable instructions (<a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> and <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>) Holds everything related to calling a function. <a href="/web-llvm/docs/api/classes/llvm/callbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a603a5bfcd809283f948cbf101851c173">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b449fea7580fc19a0ec4c5d662062a">GCStatepointInst</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d27f1fae49733cb126558899fca9797">GCStatepointInst</a> (const GCStatepointInst &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst">GCStatepointInst</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3eea106faeac766e09f4bbb88f2488">operator=</a> (const GCStatepointInst &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f370e414666fd92c2ec6fdfc70eaafd">getID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> associated with this statepoint. <a href="#a4f370e414666fd92c2ec6fdfc70eaafd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f7597de18eb49e3c6b9f1a15980a46f">getNumPatchBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of patchable bytes associated with this statepoint. <a href="#a0f7597de18eb49e3c6b9f1a15980a46f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e0ebfdcf1d9e384aeb9c597d0d11b7c">getNumCallArgs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of arguments to be passed to the actual callee. <a href="#a2e0ebfdcf1d9e384aeb9c597d0d11b7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e0495e0f7d0b948c7b38f862035acbe">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af196b6ea9e0a63c97336480d7fe60c27">getActualCalledOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value actually being called or invoked. <a href="#af196b6ea9e0a63c97336480d7fe60c27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965d5982305df45893de57d0a800fdad">getActualCalledFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the function called if this is a wrapping a direct call, and null otherwise. <a href="#a965d5982305df45893de57d0a800fdad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf5e64879884d57feb90917960dc288">getActualReturnType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type of the value returned by the call underlying the statepoint. <a href="#addf5e64879884d57feb90917960dc288">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe8d2e8e5d0ceb4a4ab76533faeb0c1">actual_arg_size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of arguments to the underlying call. <a href="#a2fe8d2e8e5d0ceb4a4ab76533faeb0c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dba7d21d7bbdd6652c6f596d253bb24">actual_arg_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator to the begining of the arguments to the underlying call. <a href="#a8dba7d21d7bbdd6652c6f596d253bb24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9affda98a42fa9eeca661518ef2f4034">actual_arg_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an end iterator of the arguments to the underlying call. <a href="#a9affda98a42fa9eeca661518ef2f4034">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3141911846aa98c98c4cfaa3b611b5c2">actual_args</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>range adapter for actual call arguments <a href="#a3141911846aa98c98c4cfaa3b611b5c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36080372317ba912639416f07a561506">gc_transition_args_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af422fe78a5f773d1d6948224670d7498">gc_transition_args_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab87cd6fb82c75cc81ca7729b240a465c">gc_transition_args</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>range adapter for GC transition arguments <a href="#ab87cd6fb82c75cc81ca7729b240a465c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23b0fbe869cf4baef885aaab613ffe56">deopt_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df806263f1e5d5cfbd39ada183f6fd2">deopt_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc53246a24c4d0c685efff73d9b4815">deopt_operands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>range adapter for vm state arguments <a href="#a3dc53246a24c4d0c685efff73d9b4815">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a748b2e4d7bb43011fcc43c38945c7a86">gc_live_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator to the begining of the argument range describing gc live values for the statepoint. <a href="#a748b2e4d7bb43011fcc43c38945c7a86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe5a441ccb5494ac458909dd7b28ecdc">gc_live_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an end iterator for the gc live range. <a href="#abe5a441ccb5494ac458909dd7b28ecdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab918f369f09ca202d5b7f42e01fd0013">gc_live</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>range adapter for gc live arguments <a href="#ab918f369f09ca202d5b7f42e01fd0013">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst">GCRelocateInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af997f3314625f4b7fcac2d24b5d9539e">getGCRelocates</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get list of all gc reloactes linked to this statepoint May contain several relocations for the same base/derived pair. <a href="#af997f3314625f4b7fcac2d24b5d9539e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade4b57265c96820be0f356f6062155ee">classof</a> (const CallBase *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb75408c1e8576c19f5a3249175534b1">classof</a> (const Value *V)</td>
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

<p>Represents a gc.statepoint intrinsic call.</p>


<p>This extends directly from <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> as the <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> only supports calls and gc.statepoint is invokable.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a603a5bfcd809283f948cbf101851c173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IDPos<a id="a603a5bfcd809283f948cbf101851c173afe97bee20d7f65f4d9425024d6e1731e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumPatchBytesPos<a id="a603a5bfcd809283f948cbf101851c173a98ac92e7271dede6726ee0afd667182b"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CalledFunctionPos<a id="a603a5bfcd809283f948cbf101851c173a0d232e12419f54293cf8da7122c0672c"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumCallArgsPos<a id="a603a5bfcd809283f948cbf101851c173abbc8efa614b1719004dc7633cbd1623f"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlagsPos<a id="a603a5bfcd809283f948cbf101851c173abfd75640ecd5cbd351571d66f9876d5f"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallArgsBeginPos<a id="a603a5bfcd809283f948cbf101851c173a4bd61c6f1d2d253230fb6a6cca78d8aa"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCStatepointInst() {#a07b449fea7580fc19a0ec4c5d662062a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCStatepointInst::GCStatepointInst ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>Referenced by <a href="#a4d27f1fae49733cb126558899fca9797">GCStatepointInst</a> and <a href="#aea3eea106faeac766e09f4bbb88f2488">operator=</a>.</p>

</div>
</div>

### GCStatepointInst() {#a4d27f1fae49733cb126558899fca9797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCStatepointInst::GCStatepointInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst">GCStatepointInst</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>Reference <a href="#a07b449fea7580fc19a0ec4c5d662062a">GCStatepointInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aea3eea106faeac766e09f4bbb88f2488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCStatepointInst &amp; llvm::GCStatepointInst::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst">GCStatepointInst</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>Reference <a href="#a07b449fea7580fc19a0ec4c5d662062a">GCStatepointInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### actual\_arg\_begin() {#a8dba7d21d7bbdd6652c6f596d253bb24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GCStatepointInst::actual_arg_begin ()</td>
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

<p>Return an iterator to the begining of the arguments to the underlying call.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4fb513d744ca72275932b2c7003f16f6">llvm::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a603a5bfcd809283f948cbf101851c173a4bd61c6f1d2d253230fb6a6cca78d8aa">CallArgsBeginPos</a>.</p>


<p>Referenced by <a href="#a9affda98a42fa9eeca661518ef2f4034">actual_arg_end</a> and <a href="#a3141911846aa98c98c4cfaa3b611b5c2">actual_args</a>.</p>

</div>
</div>

### actual\_arg\_end() {#a9affda98a42fa9eeca661518ef2f4034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GCStatepointInst::actual_arg_end ()</td>
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

<p>Return an end iterator of the arguments to the underlying call.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="#a8dba7d21d7bbdd6652c6f596d253bb24">actual_arg_begin</a>, <a href="#a2fe8d2e8e5d0ceb4a4ab76533faeb0c1">actual_arg_size</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a3141911846aa98c98c4cfaa3b611b5c2">actual_args</a>.</p>

</div>
</div>

### actual\_arg\_size() {#a2fe8d2e8e5d0ceb4a4ab76533faeb0c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::GCStatepointInst::actual_arg_size ()</td>
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

<p>Return the number of arguments to the underlying call.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>Reference <a href="#a2e0ebfdcf1d9e384aeb9c597d0d11b7c">getNumCallArgs</a>.</p>


<p>Referenced by <a href="#a9affda98a42fa9eeca661518ef2f4034">actual_arg_end</a>.</p>

</div>
</div>

### actual\_args() {#a3141911846aa98c98c4cfaa3b611b5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_op_iterator &gt; llvm::GCStatepointInst::actual_args ()</td>
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

<p>range adapter for actual call arguments</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="#a8dba7d21d7bbdd6652c6f596d253bb24">actual_arg_begin</a>, <a href="#a9affda98a42fa9eeca661518ef2f4034">actual_arg_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### deopt\_begin() {#a23b0fbe869cf4baef885aaab613ffe56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GCStatepointInst::deopt_begin ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca3f6df86c6efab701ade7abbc3134c25a">llvm::LLVMContext::OB_deopt</a>.</p>


<p>Referenced by <a href="#a3dc53246a24c4d0c685efff73d9b4815">deopt_operands</a>.</p>

</div>
</div>

### deopt\_end() {#a2df806263f1e5d5cfbd39ada183f6fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GCStatepointInst::deopt_end ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca3f6df86c6efab701ade7abbc3134c25a">llvm::LLVMContext::OB_deopt</a>.</p>


<p>Referenced by <a href="#a3dc53246a24c4d0c685efff73d9b4815">deopt_operands</a>.</p>

</div>
</div>

### deopt\_operands() {#a3dc53246a24c4d0c685efff73d9b4815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_op_iterator &gt; llvm::GCStatepointInst::deopt_operands ()</td>
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

<p>range adapter for vm state arguments</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="#a23b0fbe869cf4baef885aaab613ffe56">deopt_begin</a>, <a href="#a2df806263f1e5d5cfbd39ada183f6fd2">deopt_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### gc\_live() {#ab918f369f09ca202d5b7f42e01fd0013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_op_iterator &gt; llvm::GCStatepointInst::gc_live ()</td>
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

<p>range adapter for gc live arguments</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="#a748b2e4d7bb43011fcc43c38945c7a86">gc_live_begin</a>, <a href="#abe5a441ccb5494ac458909dd7b28ecdc">gc_live_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### gc\_live\_begin() {#a748b2e4d7bb43011fcc43c38945c7a86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GCStatepointInst::gc_live_begin ()</td>
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

<p>Returns an iterator to the begining of the argument range describing gc live values for the statepoint.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9caf85bb6bcf02a05fdd35f660e57d82534">llvm::LLVMContext::OB_gc_live</a>.</p>


<p>Referenced by <a href="#ab918f369f09ca202d5b7f42e01fd0013">gc_live</a>.</p>

</div>
</div>

### gc\_live\_end() {#abe5a441ccb5494ac458909dd7b28ecdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GCStatepointInst::gc_live_end ()</td>
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

<p>Return an end iterator for the gc live range.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9caf85bb6bcf02a05fdd35f660e57d82534">llvm::LLVMContext::OB_gc_live</a>.</p>


<p>Referenced by <a href="#ab918f369f09ca202d5b7f42e01fd0013">gc_live</a>.</p>

</div>
</div>

### gc\_transition\_args() {#ab87cd6fb82c75cc81ca7729b240a465c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_op_iterator &gt; llvm::GCStatepointInst::gc_transition_args ()</td>
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

<p>range adapter for GC transition arguments</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="#a36080372317ba912639416f07a561506">gc_transition_args_begin</a>, <a href="#af422fe78a5f773d1d6948224670d7498">gc_transition_args_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### gc\_transition\_args\_begin() {#a36080372317ba912639416f07a561506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GCStatepointInst::gc_transition_args_begin ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca3adfd6f3291adf59a7977597741211c6">llvm::LLVMContext::OB_gc_transition</a>.</p>


<p>Referenced by <a href="#ab87cd6fb82c75cc81ca7729b240a465c">gc_transition_args</a>.</p>

</div>
</div>

### gc\_transition\_args\_end() {#af422fe78a5f773d1d6948224670d7498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GCStatepointInst::gc_transition_args_end ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca3adfd6f3291adf59a7977597741211c6">llvm::LLVMContext::OB_gc_transition</a>.</p>


<p>Referenced by <a href="#ab87cd6fb82c75cc81ca7729b240a465c">gc_transition_args</a>.</p>

</div>
</div>

### getActualCalledFunction() {#a965d5982305df45893de57d0a800fdad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::GCStatepointInst::getActualCalledFunction ()</td>
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

<p>Returns the function called if this is a wrapping a direct call, and null otherwise.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#af196b6ea9e0a63c97336480d7fe60c27">getActualCalledOperand</a>.</p>

</div>
</div>

### getActualCalledOperand() {#af196b6ea9e0a63c97336480d7fe60c27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::GCStatepointInst::getActualCalledOperand ()</td>
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

<p>Return the value actually being called or invoked.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="#a603a5bfcd809283f948cbf101851c173a0d232e12419f54293cf8da7122c0672c">CalledFunctionPos</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>


<p>Referenced by <a href="#a965d5982305df45893de57d0a800fdad">getActualCalledFunction</a>.</p>

</div>
</div>

### getActualReturnType() {#addf5e64879884d57feb90917960dc288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::GCStatepointInst::getActualReturnType ()</td>
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

<p>Return the type of the value returned by the call underlying the statepoint.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="#a603a5bfcd809283f948cbf101851c173a0d232e12419f54293cf8da7122c0672c">CalledFunctionPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aa9d39950dcbd9e1e6dac2b66db4324d4">llvm::CallBase::getParamElementType</a>.</p>

</div>
</div>

### getFlags() {#a7e0495e0f7d0b948c7b38f862035acbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::GCStatepointInst::getFlags ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a603a5bfcd809283f948cbf101851c173abfd75640ecd5cbd351571d66f9876d5f">FlagsPos</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>

</div>
</div>

### getGCRelocates() {#af997f3314625f4b7fcac2d24b5d9539e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; const GCRelocateInst * &gt; llvm::GCStatepointInst::getGCRelocates ()</td>
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

<p>Get list of all gc reloactes linked to this statepoint May contain several relocations for the same base/derived pair.</p>


<p>For example this could happen due to relocations on unwinding path of invoke.</p>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#ac2f338c3f467b3d09613e190d73044a5">users</a>.</p>

</div>
</div>

### getID() {#a4f370e414666fd92c2ec6fdfc70eaafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::GCStatepointInst::getID ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> associated with this statepoint.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a> and <a href="#a603a5bfcd809283f948cbf101851c173afe97bee20d7f65f4d9425024d6e1731e">IDPos</a>.</p>

</div>
</div>

### getNumCallArgs() {#a2e0ebfdcf1d9e384aeb9c597d0d11b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::GCStatepointInst::getNumCallArgs ()</td>
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

<p>Number of arguments to be passed to the actual callee.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a> and <a href="#a603a5bfcd809283f948cbf101851c173abbc8efa614b1719004dc7633cbd1623f">NumCallArgsPos</a>.</p>


<p>Referenced by <a href="#a2fe8d2e8e5d0ceb4a4ab76533faeb0c1">actual_arg_size</a>.</p>

</div>
</div>

### getNumPatchBytes() {#a0f7597de18eb49e3c6b9f1a15980a46f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCStatepointInst::getNumPatchBytes ()</td>
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

<p>Return the number of patchable bytes associated with this statepoint.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="#a603a5bfcd809283f948cbf101851c173a98ac92e7271dede6726ee0afd667182b">NumPatchBytesPos</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ade4b57265c96820be0f356f6062155ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStatepointInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * I)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8a6c9c1339e7a196e0ae69031426c083">llvm::CallBase::CallBase</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aeb75408c1e8576c19f5a3249175534b1">classof</a>.</p>

</div>
</div>

### classof() {#aeb75408c1e8576c19f5a3249175534b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCStatepointInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ade4b57265c96820be0f356f6062155ee">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">Statepoint.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
