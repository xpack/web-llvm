---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sddbgvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SDDbgValue` Class

<p>Holds the information from a dbg_value node through SDISel. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SDDbgValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">CodeGen/SelectionDAG/SDNodeDbgValue.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bbfc66d078e240930409cc562753881">SDDbgValue</a> (BumpPtrAllocator &amp;Alloc, DIVariable *Var, DIExpression *Expr, ArrayRef&lt; SDDbgOperand &gt; L, ArrayRef&lt; SDNode * &gt; Dependencies, bool IsIndirect, DebugLoc DL, unsigned O, bool IsVariadic)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6ad5db42934af6834a14350071c3c1">SDDbgValue</a> (const SDDbgValue &amp;Other)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2396d02645163f863c7af63667ab2817">~SDDbgValue</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056c1f55334c4e6040148501812f2da1">operator=</a> (const SDDbgValue &amp;Other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b54645b0192a0ed2af213eb528b2f80">getVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> pointer for the variable. <a href="#a3b54645b0192a0ed2af213eb528b2f80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08d83b680a533ba07f644648545ab9c">getExpression</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> pointer for the expression. <a href="#ac08d83b680a533ba07f644648545ab9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6c31464e5393b719458fcb337369bdb">getLocationOps</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34733a72bb7de3bab7dade0ac71d2bfe">copyLocationOps</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaff1dd6fbb54c4d291b0f77343d60a92">getSDNodes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3ca299174d1092d2ab922bcb2811707">getAdditionalDependencies</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae238ef844b7d208238cd654383931699">isIndirect</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether this is an indirect value. <a href="#ae238ef844b7d208238cd654383931699">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af439591059d973f85e23d248f63f3529">isVariadic</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d23f6c5a21c459b913fa6e63cf75dc9">getDebugLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>. <a href="#a1d23f6c5a21c459b913fa6e63cf75dc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64971a85d1a0b74058957f9f1fed5b19">getOrder</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the SDNodeOrder. <a href="#a64971a85d1a0b74058957f9f1fed5b19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a456b1fecfa3d25a0b2a4822332cdd044">setIsInvalidated</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setIsInvalidated / isInvalidated - Setter / getter of the "Invalidated" property. <a href="#a456b1fecfa3d25a0b2a4822332cdd044">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa041c9375782c6ab2d0b6c24fd986630">isInvalidated</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77e165206b5171c2e43a90014006669">setIsEmitted</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setIsEmitted / isEmitted - Getter/Setter for flag indicating that this <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> has been emitted to an MBB. <a href="#ae77e165206b5171c2e43a90014006669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a164e0d03251f0dcfe0e9c358ae749308">isEmitted</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87e353e86ada8e84a92f195299ad868">clearIsEmitted</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearIsEmitted - Reset Emitted flag, for certain special cases where <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> is emitted twice. <a href="#aa87e353e86ada8e84a92f195299ad868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6abb9875bd75a74af631f2017c2f4264">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b15905b247b2552feb7d41ff01742db">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9728f96e219758bf37a1e61a2f7ae3ba">NumLocationOps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa76cb5d12c97c38d46b895f64691148">LocationOps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284f6565ebd3cb8792ab67ae97742ec4">NumAdditionalDependencies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9b142b746262120f02c375fa2aa76c">AdditionalDependencies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba6a01568e0977f16bd70edf22f63b46">Var</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac386656ecf25b9152d8e0e11c04ad5">Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767790bbe5ead8699a31da9e6f26b464">DL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105faecfa16418448a4fd184ed821d03">Order</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b38f058a3e77aefcddf017cb3f0a46">IsIndirect</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad69d19d6a25fc752cd0696e325f543b0">IsVariadic</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae905337c1a49540f321826f2e41d7bb">Invalid</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a145ba64e2714e5b9d6a27cfe23b76ca3">Emitted</a> = false</td>
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

<p>Holds the information from a dbg_value node through SDISel.</p>


<p>We do not use <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> here to avoid including its header.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SDDbgValue() {#a9bbfc66d078e240930409cc562753881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDDbgValue::SDDbgValue (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc, <a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> * Var, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a> &gt; L, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; Dependencies, bool IsIndirect, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, unsigned O, bool IsVariadic)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="#a056c1f55334c4e6040148501812f2da1">operator=</a> and <a href="#a1e6ad5db42934af6834a14350071c3c1">SDDbgValue</a>.</p>

</div>
</div>

### SDDbgValue() {#a1e6ad5db42934af6834a14350071c3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDDbgValue::SDDbgValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> &amp; Other)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a9bbfc66d078e240930409cc562753881">SDDbgValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SDDbgValue() {#a2396d02645163f863c7af63667ab2817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDDbgValue::~SDDbgValue ()</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a056c1f55334c4e6040148501812f2da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDDbgValue &amp; llvm::SDDbgValue::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> &amp; Other)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a9bbfc66d078e240930409cc562753881">SDDbgValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearIsEmitted() {#aa87e353e86ada8e84a92f195299ad868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDDbgValue::clearIsEmitted ()</td>
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

<p>clearIsEmitted - Reset Emitted flag, for certain special cases where <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> is emitted twice.</p>


<p>DBG_INSTR_REF depends on this behaviour.</p>


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### copyLocationOps() {#a34733a72bb7de3bab7dade0ac71d2bfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; SDDbgOperand &gt; llvm::SDDbgValue::copyLocationOps ()</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8fc529c79977cdd01e187986f960a07f">llvm::SmallVector</a>.</p>

</div>
</div>

### dump() {#a6abb9875bd75a74af631f2017c2f4264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDDbgValue::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>, definition at line 1005 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa041c9375782c6ab2d0b6c24fd986630">isInvalidated</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a1b15905b247b2552feb7d41ff01742db">print</a>.</p>

</div>
</div>

### getAdditionalDependencies() {#ac3ca299174d1092d2ab922bcb2811707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SDNode * &gt; llvm::SDDbgValue::getAdditionalDependencies ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>


<p>Referenced by <a href="#aaff1dd6fbb54c4d291b0f77343d60a92">getSDNodes</a>.</p>

</div>
</div>

### getDebugLoc() {#a1d23f6c5a21c459b913fa6e63cf75dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; llvm::SDDbgValue::getDebugLoc ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a63e197923d820bd6b000a5344adc92ea">llvm::InstrEmitter::EmitDbgNoLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a10bb6b0cc9a25c709e0009358b859d69">llvm::InstrEmitter::EmitDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a> and <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a71936ccaaca62faa835ddf1887cb2626">llvm::InstrEmitter::EmitDbgValueList</a>.</p>

</div>
</div>

### getExpression() {#ac08d83b680a533ba07f644648545ab9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * llvm::SDDbgValue::getExpression ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> pointer for the expression.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a63e197923d820bd6b000a5344adc92ea">llvm::InstrEmitter::EmitDbgNoLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a> and <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a71936ccaaca62faa835ddf1887cb2626">llvm::InstrEmitter::EmitDbgValueList</a>.</p>

</div>
</div>

### getLocationOps() {#aa6c31464e5393b719458fcb337369bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SDDbgOperand &gt; llvm::SDDbgValue::getLocationOps ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a10bb6b0cc9a25c709e0009358b859d69">llvm::InstrEmitter::EmitDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a71936ccaaca62faa835ddf1887cb2626">llvm::InstrEmitter::EmitDbgValueList</a>, <a href="#aaff1dd6fbb54c4d291b0f77343d60a92">getSDNodes</a> and <a href="#a1b15905b247b2552feb7d41ff01742db">print</a>.</p>

</div>
</div>

### getOrder() {#a64971a85d1a0b74058957f9f1fed5b19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDDbgValue::getOrder ()</td>
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

<p>Returns the SDNodeOrder.</p>


<p>This is the order of the preceding node in the input.</p>


<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="#a1b15905b247b2552feb7d41ff01742db">print</a>.</p>

</div>
</div>

### getSDNodes() {#aaff1dd6fbb54c4d291b0f77343d60a92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; SDNode * &gt; llvm::SDDbgValue::getSDNodes ()</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>References <a href="#ac3ca299174d1092d2ab922bcb2811707">getAdditionalDependencies</a>, <a href="#aa6c31464e5393b719458fcb337369bdb">getLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709aa35847085c9bc57f525640fa8ae5a15c">llvm::SDDbgOperand::SDNODE</a>.</p>

</div>
</div>

### getVariable() {#a3b54645b0192a0ed2af213eb528b2f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIVariable * llvm::SDDbgValue::getVariable ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> pointer for the variable.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a63e197923d820bd6b000a5344adc92ea">llvm::InstrEmitter::EmitDbgNoLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a10bb6b0cc9a25c709e0009358b859d69">llvm::InstrEmitter::EmitDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a> and <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a71936ccaaca62faa835ddf1887cb2626">llvm::InstrEmitter::EmitDbgValueList</a>.</p>

</div>
</div>

### isEmitted() {#a164e0d03251f0dcfe0e9c358ae749308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgValue::isEmitted ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="#a1b15905b247b2552feb7d41ff01742db">print</a>.</p>

</div>
</div>

### isIndirect() {#ae238ef844b7d208238cd654383931699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgValue::isIndirect ()</td>
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

<p>Returns whether this is an indirect value.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a> and <a href="#a1b15905b247b2552feb7d41ff01742db">print</a>.</p>

</div>
</div>

### isInvalidated() {#aa041c9375782c6ab2d0b6c24fd986630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgValue::isInvalidated ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="#a6abb9875bd75a74af631f2017c2f4264">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a10bb6b0cc9a25c709e0009358b859d69">llvm::InstrEmitter::EmitDbgValue</a> and <a href="#a1b15905b247b2552feb7d41ff01742db">print</a>.</p>

</div>
</div>

### isVariadic() {#af439591059d973f85e23d248f63f3529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgValue::isVariadic ()</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a10bb6b0cc9a25c709e0009358b859d69">llvm::InstrEmitter::EmitDbgValue</a> and <a href="#a1b15905b247b2552feb7d41ff01742db">print</a>.</p>

</div>
</div>

### print() {#a1b15905b247b2552feb7d41ff01742db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDDbgValue::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>, definition at line 963 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709aae386012326afbc26eeecc3701f36134">llvm::SDDbgOperand::CONST</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709a8c6e740c1259b720ed9f87a05baf593b">llvm::SDDbgOperand::FRAMEIX</a>, <a href="#aa6c31464e5393b719458fcb337369bdb">getLocationOps</a>, <a href="#a64971a85d1a0b74058957f9f1fed5b19">getOrder</a>, <a href="#a164e0d03251f0dcfe0e9c358ae749308">isEmitted</a>, <a href="#ae238ef844b7d208238cd654383931699">isIndirect</a>, <a href="#aa041c9375782c6ab2d0b6c24fd986630">isInvalidated</a>, <a href="#af439591059d973f85e23d248f63f3529">isVariadic</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#a001f788db44eec30b041b21b571523d7">PrintNodeId</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709aa35847085c9bc57f525640fa8ae5a15c">llvm::SDDbgOperand::SDNODE</a> and <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709a18402f81e9528c3cc41c781786e533b8">llvm::SDDbgOperand::VREG</a>.</p>


<p>Referenced by <a href="#a6abb9875bd75a74af631f2017c2f4264">dump</a>.</p>

</div>
</div>

### setIsEmitted() {#ae77e165206b5171c2e43a90014006669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDDbgValue::setIsEmitted ()</td>
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

<p>setIsEmitted / isEmitted - Getter/Setter for flag indicating that this <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> has been emitted to an MBB.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a10bb6b0cc9a25c709e0009358b859d69">llvm::InstrEmitter::EmitDbgValue</a>.</p>

</div>
</div>

### setIsInvalidated() {#a456b1fecfa3d25a0b2a4822332cdd044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDDbgValue::setIsInvalidated ()</td>
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

<p>setIsInvalidated / isInvalidated - Setter / getter of the "Invalidated" property.</p>


<p>A <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> is invalid if the <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> that produces the value is deleted.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AdditionalDependencies {#ace9b142b746262120f02c375fa2aa76c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode** llvm::SDDbgValue::AdditionalDependencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### DL {#a767790bbe5ead8699a31da9e6f26b464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::SDDbgValue::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### Emitted {#a145ba64e2714e5b9d6a27cfe23b76ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgValue::Emitted = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### Expr {#aeac386656ecf25b9152d8e0e11c04ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression* llvm::SDDbgValue::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### Invalid {#aae905337c1a49540f321826f2e41d7bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgValue::Invalid = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### IsIndirect {#a44b38f058a3e77aefcddf017cb3f0a46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgValue::IsIndirect</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### IsVariadic {#ad69d19d6a25fc752cd0696e325f543b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDDbgValue::IsVariadic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### LocationOps {#aaa76cb5d12c97c38d46b895f64691148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDDbgOperand* llvm::SDDbgValue::LocationOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### NumAdditionalDependencies {#a284f6565ebd3cb8792ab67ae97742ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SDDbgValue::NumAdditionalDependencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### NumLocationOps {#a9728f96e219758bf37a1e61a2f7ae3ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SDDbgValue::NumLocationOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### Order {#a105faecfa16418448a4fd184ed821d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDDbgValue::Order</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

### Var {#aba6a01568e0977f16bd70edf22f63b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIVariable* llvm::SDDbgValue::Var</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/sdnodedbgvalue-h">SDNodeDbgValue.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
