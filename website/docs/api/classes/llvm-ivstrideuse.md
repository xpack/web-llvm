---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ivstrideuse
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IVStrideUse` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> - Keep track of one use of a strided induction variable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::IVStrideUse { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">llvm/Analysis/IVUsers.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle with callbacks on RAUW and destruction. <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a097019ab19ab2e17ee9a4218fac9aa89">IVUsers</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2140ae8507867b97114724c6a6dbbba">IVStrideUse</a> (IVUsers *P, Instruction *U, Value *O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc04591d1d6420a7fdbc15a4c5f0e31">getUser</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getUser - Return the user instruction for this use. <a href="#a1bc04591d1d6420a7fdbc15a4c5f0e31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb8718e691dfd2e5d5a3e0d876e35cc9">setUser</a> (Instruction *NewUser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setUser - Assign a new user instruction for this use. <a href="#acb8718e691dfd2e5d5a3e0d876e35cc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850ce8990175a8dc4e5a641df3db14aa">getOperandValToReplace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOperandValToReplace - Return the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of the operand in the user instruction that this <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> is representing. <a href="#a850ce8990175a8dc4e5a641df3db14aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f03f777c4395d140e90f7a5278ee03">setOperandValToReplace</a> (Value *Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setOperandValToReplace - Assign a new <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> as the operand value to replace. <a href="#a59f03f777c4395d140e90f7a5278ee03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ac765465998d0f34ed6123631bda54fab">PostIncLoopSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6475dcea1bb00ad07700b96492896c59">getPostIncLoops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPostIncLoops - Return the set of loops for which the expression has been adjusted to use post-inc mode. <a href="#a6475dcea1bb00ad07700b96492896c59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8433a09d9b66df4f5c8a4d1414dc8ec9">transformToPostInc</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>transformToPostInc - Transform the expression to post-inc form for the given loop. <a href="#a8433a09d9b66df4f5c8a4d1414dc8ec9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e128fe9b12150cf9b6415b61c45e73">deleted</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deleted - Implementation of <a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a> virtual function to receive notification when the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> is deleted. <a href="#a18e128fe9b12150cf9b6415b61c45e73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a455a12a32108201983bc6e46df732fca">Parent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parent - a pointer to the <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> that owns this <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a>. <a href="#a455a12a32108201983bc6e46df732fca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a75c804b182e0f69862bfcf702eb3ee">OperandValToReplace</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OperandValToReplace - The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of the operand in the user instruction that this <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> is representing. <a href="#a6a75c804b182e0f69862bfcf702eb3ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ac765465998d0f34ed6123631bda54fab">PostIncLoopSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee1642fffe12b44f924ae3307de2746">PostIncLoops</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PostIncLoops - The set of loops for which Expr has been adjusted to use post-inc mode. <a href="#a8ee1642fffe12b44f924ae3307de2746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> - Keep track of one use of a strided induction variable.</p>


<p>The Expr member keeps track of the expression, <a href="/web-llvm/docs/api/classes/llvm/user">User</a> is the actual user instruction of the operand, and 'OperandValToReplace' is the operand of the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> that is the use.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<div class="doxySectionDef">

## Friends

### IVUsers {#a097019ab19ab2e17ee9a4218fac9aa89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>Reference <a href="#a097019ab19ab2e17ee9a4218fac9aa89">IVUsers</a>.</p>


<p>Referenced by <a href="#ac2140ae8507867b97114724c6a6dbbba">IVStrideUse</a> and <a href="#a097019ab19ab2e17ee9a4218fac9aa89">IVUsers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IVStrideUse() {#ac2140ae8507867b97114724c6a6dbbba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IVStrideUse::IVStrideUse (<a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> * P, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * U, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * O)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a7e87f4bd72a4d8b7f092b2a2ee69ba1d">llvm::CallbackVH::CallbackVH</a>, <a href="#a097019ab19ab2e17ee9a4218fac9aa89">IVUsers</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getOperandValToReplace() {#a850ce8990175a8dc4e5a641df3db14aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::IVStrideUse::getOperandValToReplace ()</td>
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

<p>getOperandValToReplace - Return the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of the operand in the user instruction that this <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> is representing.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ivusers/#a729d7a4c47511beaaec595f1b85f7889">llvm::IVUsers::getReplacementExpr</a>.</p>

</div>
</div>

### getPostIncLoops() {#a6475dcea1bb00ad07700b96492896c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PostIncLoopSet &amp; llvm::IVStrideUse::getPostIncLoops ()</td>
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

<p>getPostIncLoops - Return the set of loops for which the expression has been adjusted to use post-inc mode.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ivusers/#af19a630344b862c4b06bca0e51d978cc">llvm::IVUsers::getExpr</a>.</p>

</div>
</div>

### getUser() {#a1bc04591d1d6420a7fdbc15a4c5f0e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::IVStrideUse::getUser ()</td>
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

<p>getUser - Return the user instruction for this use.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">llvm::ValueHandleBase::getValPtr</a>.</p>

</div>
</div>

### setOperandValToReplace() {#a59f03f777c4395d140e90f7a5278ee03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IVStrideUse::setOperandValToReplace (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op)</td>
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

<p>setOperandValToReplace - Assign a new <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> as the operand value to replace.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### setUser() {#acb8718e691dfd2e5d5a3e0d876e35cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IVStrideUse::setUser (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * NewUser)</td>
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

<p>setUser - Assign a new user instruction for this use.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#ab3a25e82043f8a99ad6ed61fb9c9483c">llvm::CallbackVH::setValPtr</a>.</p>

</div>
</div>

### transformToPostInc() {#a8433a09d9b66df4f5c8a4d1414dc8ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IVStrideUse::transformToPostInc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>transformToPostInc - Transform the expression to post-inc form for the given loop.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### deleted() {#a18e128fe9b12150cf9b6415b61c45e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IVStrideUse::deleted ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deleted - Implementation of <a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a> virtual function to receive notification when the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> is deleted.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OperandValToReplace {#a6a75c804b182e0f69862bfcf702eb3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeakTrackingVH llvm::IVStrideUse::OperandValToReplace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OperandValToReplace - The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of the operand in the user instruction that this <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> is representing.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### Parent {#a455a12a32108201983bc6e46df732fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IVUsers* llvm::IVStrideUse::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parent - a pointer to the <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> that owns this <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a>.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### PostIncLoops {#a8ee1642fffe12b44f924ae3307de2746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostIncLoopSet llvm::IVStrideUse::PostIncLoops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PostIncLoops - The set of loops for which Expr has been adjusted to use post-inc mode.</p>


<p>This corresponds with <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a>'s post-inc concept.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
