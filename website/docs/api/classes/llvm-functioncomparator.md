---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/functioncomparator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FunctionComparator` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/functioncomparator">FunctionComparator</a> - Compares two functions to determine whether or not they will generate machine code with the same behaviour. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FunctionComparator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">llvm/Transforms/Utils/FunctionComparator.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d0bc707a7410d5e1225c5e29a6f0c0c">FunctionComparator</a> (const Function *F1, const Function *F2, GlobalNumberState *GN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca10cc5976994ee1c01be4b019c1ee6">compare</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the two functions have equivalent behaviour. <a href="#a4ca10cc5976994ee1c01be4b019c1ee6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6d7e8c1ae29b2989d915a96866408ad">beginCompare</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start the comparison. <a href="#ac6d7e8c1ae29b2989d915a96866408ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a404aec2d456394b3b9ace0364045cfa2">compareSignature</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compares the signature and other general attributes of the two functions. <a href="#a404aec2d456394b3b9ace0364045cfa2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21408b47716ef75ac95ded9097918f0a">cmpBasicBlocks</a> (const BasicBlock *BBL, const BasicBlock *BBR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether two basic blocks have equivalent behaviour. <a href="#a21408b47716ef75ac95ded9097918f0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a> (const Constant *L, const Constant *R) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constants comparison. <a href="#aecc5ef45f49070634ddd53a04ed5548e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad251347b1feac30dc71e64f61b2ea195">cmpGlobalValues</a> (GlobalValue *L, GlobalValue *R) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compares two global values by number. <a href="#ad251347b1feac30dc71e64f61b2ea195">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a> (const Value *L, const Value *R) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign or look up previously assigned numbers for the two values, and return whether the numbers are equal. <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa359aa2850f74fbc9dbdb4650c13f4cf">cmpOperations</a> (const Instruction *L, const Instruction *R, bool &amp;needToCmpOperands) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two Instructions for equivalence, similar to <a href="/web-llvm/docs/api/classes/llvm/instruction/#a25175390eaee0646bcb8b30990ab723b">Instruction::isSameOperationAs</a>. <a href="#aa359aa2850f74fbc9dbdb4650c13f4cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96167048c547bb562d69720cee2a48a6">cmpTypes</a> (Type *TyL, Type *TyR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>cmpType - compares two types, defines total ordering among the types set. <a href="#a96167048c547bb562d69720cee2a48a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a> (uint64_t L, uint64_t R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec80b03038382f41e2f3217db10d729">cmpAligns</a> (Align L, Align R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf58b007a386724dbc14ca472df8980">cmpAPInts</a> (const APInt &amp;L, const APInt &amp;R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3090ffa7bd5437bfa54660bc5983834a">cmpConstantRanges</a> (const ConstantRange &amp;L, const ConstantRange &amp;R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a31319ba96ba0a68b6c30fed08f3dd2">cmpAPFloats</a> (const APFloat &amp;L, const APFloat &amp;R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a494a3d5038b4704ce9d4220394e18c84">cmpMem</a> (StringRef L, StringRef R) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b05aa2bd58caf3af6f88825f34e5776">cmpOrderings</a> (AtomicOrdering L, AtomicOrdering R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9268807201ab47ed85e878a8f08fc66c">cmpInlineAsm</a> (const InlineAsm *L, const InlineAsm *R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d2f05de66ff22cab55aa260fd0417a">cmpAttrs</a> (const AttributeList L, const AttributeList R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ff1222f9638bfb1c8c6302fdca0883">cmpMDNode</a> (const MDNode *L, const MDNode *R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee43772169f3d279ded2656a3fe63a58">cmpMetadata</a> (const Metadata *L, const Metadata *R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64a3ae7604cec072650dc8612391133">cmpInstMetadata</a> (Instruction const *L, Instruction const *R) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6046e72387de962e5e1b160ed627defb">cmpOperandBundlesSchema</a> (const CallBase &amp;LCS, const CallBase &amp;RCS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af111b976ea3558ddc40db053b53fd58d">cmpGEPs</a> (const GEPOperator *GEPL, const GEPOperator *GEPR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two GEPs for equivalent pointer arithmetic. <a href="#af111b976ea3558ddc40db053b53fd58d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b827b6ddd7075cf4c670b7229b9827">cmpGEPs</a> (const GetElementPtrInst *GEPL, const GetElementPtrInst *GEPR) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab58e4d2fb258a0d2c839fbfdae9024">FnL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fec2baea95adaabe3bec634298422db">FnR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77ad785d8141826893648381c2af01d1">sn_mapL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign serial numbers to values from left function, and values from right function. <a href="#a77ad785d8141826893648381c2af01d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ff9c9c67aa148ddc34ff5f8aac1150d">sn_mapR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalnumberstate">GlobalNumberState</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8d9e79148bc71611a20406b85c991b">GlobalNumbers</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/functioncomparator">FunctionComparator</a> - Compares two functions to determine whether or not they will generate machine code with the same behaviour.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> is used if available. The comparator always fails conservatively (erring on the side of claiming that two functions are different).</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionComparator() {#a0d0bc707a7410d5e1225c5e29a6f0c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FunctionComparator::FunctionComparator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F2, <a href="/web-llvm/docs/api/classes/llvm/globalnumberstate">GlobalNumberState</a> * GN)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>.</p>


<p>References <a href="#a6ab58e4d2fb258a0d2c839fbfdae9024">FnL</a> and <a href="#a2fec2baea95adaabe3bec634298422db">FnR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compare() {#a4ca10cc5976994ee1c01be4b019c1ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::compare ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the two functions have equivalent behaviour.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 1007 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac6d7e8c1ae29b2989d915a96866408ad">beginCompare</a>, <a href="#a21408b47716ef75ac95ded9097918f0a">cmpBasicBlocks</a>, <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a>, <a href="#a404aec2d456394b3b9ace0364045cfa2">compareSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a6ab58e4d2fb258a0d2c839fbfdae9024">FnL</a>, <a href="#a2fec2baea95adaabe3bec634298422db">FnR</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6e5d2e18c81baaeec7dadc81a0dea993">llvm::Instruction::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### beginCompare() {#ac6d7e8c1ae29b2989d915a96866408ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionComparator::beginCompare ()</td>
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

<p>Start the comparison.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>.</p>


<p>Referenced by <a href="#a4ca10cc5976994ee1c01be4b019c1ee6">compare</a>.</p>

</div>
</div>

### cmpAligns() {#abec80b03038382f41e2f3217db10d729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpAligns (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> L, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>Referenced by <a href="#aa359aa2850f74fbc9dbdb4650c13f4cf">cmpOperations</a>.</p>

</div>
</div>

### cmpAPFloats() {#a5a31319ba96ba0a68b6c30fed08f3dd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpAPFloats (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>References <a href="#aedf58b007a386724dbc14ca472df8980">cmpAPInts</a>, <a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a5a1d760444efbbc033928adb6f41f1f3">llvm::APFloatBase::semanticsMaxExponent</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1cf388064ffacaf16fafb77dd41942d9">llvm::APFloatBase::semanticsMinExponent</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6530cd829b7e8d4df2c29d950039961e">llvm::APFloatBase::semanticsPrecision</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a27161c9f62ab8ae2d6ddaf10b8ccb937">llvm::APFloatBase::semanticsSizeInBits</a>.</p>


<p>Referenced by <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>.</p>

</div>
</div>

### cmpAPInts() {#aedf58b007a386724dbc14ca472df8980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpAPInts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>Reference <a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a>.</p>


<p>Referenced by <a href="#a5a31319ba96ba0a68b6c30fed08f3dd2">cmpAPFloats</a>, <a href="#a3090ffa7bd5437bfa54660bc5983834a">cmpConstantRanges</a> and <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>.</p>

</div>
</div>

### cmpBasicBlocks() {#a21408b47716ef75ac95ded9097918f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpBasicBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BBL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BBR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether two basic blocks have equivalent behaviour.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#aa359aa2850f74fbc9dbdb4650c13f4cf">cmpOperations</a>, <a href="#a96167048c547bb562d69720cee2a48a6">cmpTypes</a>, <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#a4ca10cc5976994ee1c01be4b019c1ee6">compare</a>.</p>

</div>
</div>

### cmpConstantRanges() {#a3090ffa7bd5437bfa54660bc5983834a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpConstantRanges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>Reference <a href="#aedf58b007a386724dbc14ca472df8980">cmpAPInts</a>.</p>


<p>Referenced by <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>.</p>

</div>
</div>

### cmpConstants() {#aecc5ef45f49070634ddd53a04ed5548e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpConstants (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constants comparison.</p>


<p>Constants comparison:</p>


<p>Its analog to lexicographical comparison between hypothetical numbers of next format: &lt;bitcastability-trait&gt;&lt;raw-bit-contents&gt;</p>


<ol class="doxyList" type="1">
<li>Bitcastability. <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether L's type could be losslessly bitcasted to R's type. On this stage method, in case when lossless bitcast is not possible method returns -1 or 1, thus also defining which type is greater in context of bitcastability. Stage 0: If types are equal in terms of cmpTypes, then we can go straight to the contents comparison. If types differ, remember types comparison result and check whether we still can bitcast types. Stage 1: Types that satisfies isFirstClassType conditions are always greater then others. Stage 2: Vector is greater then non-vector. If both types are vectors, then vector with greater bitwidth is greater. If both types are vectors with the same bitwidth, then types are bitcastable, and we can skip other stages, and go to contents comparison. Stage 3: Pointer types are greater than non-pointers. If both types are pointers of the same address space - go to contents comparison. Different address spaces: pointer with greater address space is greater. Stage 4: Types are neither vectors, nor pointers. And they differ. We don't know how to bitcast them. So, we better don't do it, and return types comparison result (so it determines the relationship among constants we don't know how to bitcast).</li>
</ol>

<p>Just for clearance, let's see how the set of constants could look on single dimension axis:</p>


<p>[NFCT], [FCT, "others"], [FCT, pointers], [FCT, vectors] Where: NFCT - Not a FirstClassType FCT - FirstClassTyp:</p>


<ol class="doxyList" type="1">
<li>Compare raw contents. It ignores types on this stage and only compares bits from L and R. Returns 0, if L and R has equivalent contents. -1 or 1 if values are different. Pretty trivial: 2.1. If contents are numbers, compare numbers. Ints with greater bitwidth are greater. Ints with same bitwidths compared by their contents. 2.2. "And so on". Just to avoid discrepancies with comments perhaps it would be better to read the implementation itself.</li>
<li>And again about overall picture. Let's look back at how the ordered set of constants will look like: [NFCT], [FCT, "others"], [FCT, pointers], [FCT, vectors]</li>
</ol>

<p>Now look, what could be inside [FCT, "others"], for example: [FCT, "others"] = [ [double 0.1], [double 1.23], [i32 1], [i32 2], { double 1.0 }, ; StructTyID, NumElements = 1 { i32 1 }, ; StructTyID, NumElements = 1 { double 1, i32 1 }, ; StructTyID, NumElements = 2 { i32 1, double 1 } ; StructTyID, NumElements = 2 ]</p>


<p>Let's explain the order. Float numbers will be less than integers, just because of cmpType terms: FloatTyID &lt; IntegerTyID. Floats (with same <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a>) are sorted according to their value. Then you can see integers, and they are, like a floats, could be easy sorted among each others. The structures. Structures are grouped at the tail, again because of their <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a80cca3528193bd0d53e43a6d030f0ea0">TypeID</a>: StructTyID &gt; IntegerTyID &gt; FloatTyID. Structures with greater number of elements are greater. Structures with greater elements going first are greater. The same logic with vectors, arrays and other possible complex types.</p>


<p>Bitcastable constants. Let's assume, that some constant, belongs to some group of "so-called-equal" values with different types, and at the same time belongs to another group of constants with equal types and "really" equal values.</p>


<p>Now, prove that this is impossible:</p>


<p>If constant A with type TyA is bitcastable to B with type TyB, then:</p>


<ol class="doxyList" type="1">
<li>All constants with equal types to TyA, are bitcastable to B. Since those should be vectors (if TyA is vector), pointers (if TyA is pointer), or else (if TyA equal to TyB), those types should be equal to TyB.</li>
<li>All constants with non-equal, but bitcastable types to TyA, are bitcastable to B. Once again, just because we allow it to vectors and pointers only. This statement could be expanded as below: 2.1. All vectors with equal bitwidth to vector A, has equal bitwidth to vector B, and thus bitcastable to B as well. 2.2. All pointers of the same address space, no matter what they point to, bitcastable. So if C is pointer, it could be bitcasted to A and to B. So any constant equal or bitcastable to A is equal or bitcastable to B. QED.</li>
</ol>

<p>In another words, for pointers and vectors, we ignore top-level type and look at their particular properties (bit-width for vectors, and address space for pointers). If these properties are equal - compare their contents.</p>


<ol class="doxyList" type="1">
<li><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether type of L constant could be losslessly bitcasted to R type.</li>
<li>Compare constant contents. For more details see declaration comments.</li>
</ol>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5a31319ba96ba0a68b6c30fed08f3dd2">cmpAPFloats</a>, <a href="#aedf58b007a386724dbc14ca472df8980">cmpAPInts</a>, <a href="#a3090ffa7bd5437bfa54660bc5983834a">cmpConstantRanges</a>, <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>, <a href="#ad251347b1feac30dc71e64f61b2ea195">cmpGlobalValues</a>, <a href="#a494a3d5038b4704ce9d4220394e18c84">cmpMem</a>, <a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a>, <a href="#a96167048c547bb562d69720cee2a48a6">cmpTypes</a>, <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a6ab58e4d2fb258a0d2c839fbfdae9024">FnL</a>, <a href="#a2fec2baea95adaabe3bec634298422db">FnR</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#abcbecd821a6c5590f25efdf76406a3e8">llvm::BlockAddress::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#abb524f716e3a2a50acacf3e3df344662">llvm::BlockAddress::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ad7c657cd513c76f7d328ffdf0fc46f2b">llvm::ConstantExpr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a82a7e98c00f5bb12e2c5481fe0ab3f1a">llvm::Type::isFirstClassType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a2228fd86a118c059a40aa7906b7b9f75">OBOL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>


<p>Referenced by <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a> and <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a>.</p>

</div>
</div>

### cmpGlobalValues() {#ad251347b1feac30dc71e64f61b2ea195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpGlobalValues (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * L, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compares two global values by number.</p>


<p>Uses the GlobalNumbersState to identify the same gobals across function calls.</p>


<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>Reference <a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a>.</p>


<p>Referenced by <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>.</p>

</div>
</div>

### cmpMem() {#a494a3d5038b4704ce9d4220394e18c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpMem (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> L, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>Reference <a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a>.</p>


<p>Referenced by <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a> and <a href="#a404aec2d456394b3b9ace0364045cfa2">compareSignature</a>.</p>

</div>
</div>

### cmpNumbers() {#ab0590a1bcd08f75a7580a66c7a2023f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpNumbers (uint64_t L, uint64_t R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>Referenced by <a href="#a5a31319ba96ba0a68b6c30fed08f3dd2">cmpAPFloats</a>, <a href="#aedf58b007a386724dbc14ca472df8980">cmpAPInts</a>, <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>, <a href="#ad251347b1feac30dc71e64f61b2ea195">cmpGlobalValues</a>, <a href="#a494a3d5038b4704ce9d4220394e18c84">cmpMem</a>, <a href="#aa359aa2850f74fbc9dbdb4650c13f4cf">cmpOperations</a>, <a href="#a96167048c547bb562d69720cee2a48a6">cmpTypes</a>, <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a> and <a href="#a404aec2d456394b3b9ace0364045cfa2">compareSignature</a>.</p>

</div>
</div>

### cmpOperations() {#aa359aa2850f74fbc9dbdb4650c13f4cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpOperations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * R, bool &amp; needToCmpOperands)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare two Instructions for equivalence, similar to <a href="/web-llvm/docs/api/classes/llvm/instruction/#a25175390eaee0646bcb8b30990ab723b">Instruction::isSameOperationAs</a>.</p>


<p>Stages are listed in "most significant stage first" order: On each stage below, we do comparison between some left and right operation parts. If parts are non-equal, we assign parts comparison result to the operation comparison result and exit from method. Otherwise we proceed to the next stage. Stages:</p>


<ol class="doxyList" type="1">
<li>Operations opcodes. Compared as numbers.</li>
<li>Number of operands.</li>
<li>Operation types. Compared with cmpType method.</li>
<li>Compare operation subclass optional data as stream of bytes: just convert it to integers and call cmpNumbers.</li>
<li>Compare in operation operand types with cmpType in most significant operand first order.</li>
<li>Last stage. <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> operations for some specific attributes. For example, for Load it would be: 6.1.Load: volatile (as boolean flag) 6.2.Load: alignment (as integer numbers) 6.3.Load: ordering (as underlying enum class value) 6.4.Load: synch-scope (as integer numbers) 6.5.Load: range metadata (as integer ranges) On this stage its better to see the code, since its not more than 10-15 strings for particular instruction, and could change sometimes.</li>
</ol>

<p>Sets <span class="doxyComputerOutput">needToCmpOperands</span> to true if the operands of the instructions still must be compared afterwards. In this case it's already guaranteed that both instructions have the same number of operands.</p>


<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#abec80b03038382f41e2f3217db10d729">cmpAligns</a>, <a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a>, <a href="#a96167048c547bb562d69720cee2a48a6">cmpTypes</a>, <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a0621d26039722d96ad6da863edbf60f9">llvm::GetElementPtrInst::getPointerOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a21408b47716ef75ac95ded9097918f0a">cmpBasicBlocks</a>.</p>

</div>
</div>

### cmpTypes() {#a96167048c547bb562d69720cee2a48a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpTypes (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * TyL, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * TyR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>cmpType - compares two types, defines total ordering among the types set.</p>


<p>Return values: 0 if types are equal, -1 if Left is less than Right, +1 if Left is greater than Right.</p>


<p>Description: Comparison is broken onto stages. Like in lexicographical comparison stage coming first has higher priority. On each explanation stage keep in mind total ordering properties.</p>


<ol class="doxyList" type="1">
<li>Before comparison we coerce pointer types of 0 address space to integer. We also don't bother with same type at left and right, so just return 0 in this case.</li>
<li>If types are of different kind (different type IDs). Return result of type IDs comparison, treating them as numbers.</li>
<li>If types are integers, check that they have the same width. If they are vectors, check that they have the same count and subtype.</li>
<li>Types have the same <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, so check whether they are one of:</li>
</ol>

<ul class="doxyList ">
<li>Void</li>
<li>Float</li>
<li>Double</li>
<li>X86_FP80</li>
<li>FP128</li>
<li>PPC_FP128</li>
<li>Label</li>
<li><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> We can treat these types as equal whenever their IDs are same.</li>
</ul>

<ol class="doxyList" type="1">
<li>If Left and Right are pointers, return result of address space comparison (numbers comparison). We can treat pointer types of same address space as equal.</li>
<li>If types are complex. Then both Left and Right are to be expanded and their element types will be checked with the same way. If we get Res != 0 on some stage, return it. Otherwise return 0.</li>
<li>For all other cases put llvm_unreachable.</li>
</ol>

<p>See method declaration comments for more details.</p>


<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">llvm::Type::ArrayTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a>, <a href="#a96167048c547bb562d69720cee2a48a6">cmpTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="#a6ab58e4d2fb258a0d2c839fbfdae9024">FnL</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc">llvm::Type::FP128TyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa0ec130d9ce9883b3e9c6071ee19a4b16">llvm::Type::FunctionTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aee3c78d73273cb8449cd10cc15edcb83">llvm::StructType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a858efd7b61654c0de28c56f9adafa13d">llvm::StructType::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a84b61ef997688651dd4e06cb7567cfed">llvm::StructType::isPacked</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa66db5616b8f6b2cfe991861905747783">llvm::Type::LabelTyID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaad3b3756c598c8acc2d002f5f9a2c1d04">llvm::Type::MetadataTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48">llvm::Type::PPC_FP128TyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">llvm::Type::StructTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae01900ccd0d696ce7ede9d710415f162">llvm::Type::TokenTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa567ac2c7944f770cfb2c2cffc94b3520">llvm::Type::VoidTyID</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">llvm::Type::X86_FP80TyID</a>.</p>


<p>Referenced by <a href="#a21408b47716ef75ac95ded9097918f0a">cmpBasicBlocks</a>, <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>, <a href="#aa359aa2850f74fbc9dbdb4650c13f4cf">cmpOperations</a>, <a href="#a96167048c547bb562d69720cee2a48a6">cmpTypes</a> and <a href="#a404aec2d456394b3b9ace0364045cfa2">compareSignature</a>.</p>

</div>
</div>

### cmpValues() {#ac7b438ce165bdc9f0bff4c55f8c0f499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign or look up previously assigned numbers for the two values, and return whether the numbers are equal.</p>


<p>Compare two values used by the two functions under pair-wise comparison.</p>


<p>Numbers are assigned in the order visited. Comparison order: Stage 0: <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that is function itself is always greater then others. If left and right values are references to their functions, then they are equal. Stage 1: Constants are greater than non-constants. If both left and right are constants, then the result of cmpConstants is used as cmpValues result. Stage 2: <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> instances are greater than others. If both left and right are <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> instances, InlineAsm* pointers casted to integers and compared as numbers. Stage 3: For all other cases we compare order we meet these values in their functions. If right value was met first during scanning, then left value is greater. In another words, we compare serial numbers, for more details see comments for sn_mapL and sn_mapR.</p>


<p>If this is the first time the values are seen, they're added to the mapping so that we will detect mismatches on next use. See comments in declaration for more details.</p>


<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>References <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>, <a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a6ab58e4d2fb258a0d2c839fbfdae9024">FnL</a>, <a href="#a2fec2baea95adaabe3bec634298422db">FnR</a> and <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#ac524678278da9691379135d01953a8e9">llvm::MetadataAsValue::getMetadata</a>.</p>


<p>Referenced by <a href="#a21408b47716ef75ac95ded9097918f0a">cmpBasicBlocks</a>, <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>, <a href="#aa359aa2850f74fbc9dbdb4650c13f4cf">cmpOperations</a>, <a href="#a4ca10cc5976994ee1c01be4b019c1ee6">compare</a> and <a href="#a404aec2d456394b3b9ace0364045cfa2">compareSignature</a>.</p>

</div>
</div>

### compareSignature() {#a404aec2d456394b3b9ace0364045cfa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::compareSignature ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compares the signature and other general attributes of the two functions.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a494a3d5038b4704ce9d4220394e18c84">cmpMem</a>, <a href="#ab0590a1bcd08f75a7580a66c7a2023f0">cmpNumbers</a>, <a href="#a96167048c547bb562d69720cee2a48a6">cmpTypes</a>, <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a>, <a href="#a6ab58e4d2fb258a0d2c839fbfdae9024">FnL</a>, <a href="#a2fec2baea95adaabe3bec634298422db">FnR</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a4ca10cc5976994ee1c01be4b019c1ee6">compare</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cmpAttrs() {#a15d2f05de66ff22cab55aa260fd0417a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>

</div>
</div>

### cmpGEPs() {#af111b976ea3558ddc40db053b53fd58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpGEPs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gepoperator">GEPOperator</a> * GEPL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gepoperator">GEPOperator</a> * GEPR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare two GEPs for equivalent pointer arithmetic.</p>


<p>Parts to be compared for each comparison stage, most significant stage first:</p>


<ol class="doxyList" type="1">
<li>Address space. As numbers.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> offset, (using <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a5c00e7e76ef5e98c6ffec8d31f63970a">GEPOperator::accumulateConstantOffset</a> method).</li>
<li>Pointer operand type (using cmpType method).</li>
<li>Number of operands.</li>
<li>Compare operands, using cmpValues method.</li>
</ol>

<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>

</div>
</div>

### cmpGEPs() {#a72b827b6ddd7075cf4c670b7229b9827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::FunctionComparator::cmpGEPs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEPL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEPR)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>.</p>

</div>
</div>

### cmpInlineAsm() {#a9268807201ab47ed85e878a8f08fc66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpInlineAsm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> * R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>

</div>
</div>

### cmpInstMetadata() {#aa64a3ae7604cec072650dc8612391133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpInstMetadata (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * L, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>

</div>
</div>

### cmpMDNode() {#a55ff1222f9638bfb1c8c6302fdca0883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpMDNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>

</div>
</div>

### cmpMetadata() {#aee43772169f3d279ded2656a3fe63a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>

</div>
</div>

### cmpOperandBundlesSchema() {#a6046e72387de962e5e1b160ed627defb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpOperandBundlesSchema (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; LCS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; RCS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>

</div>
</div>

### cmpOrderings() {#a5b05aa2bd58caf3af6f88825f34e5776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionComparator::cmpOrderings (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> L, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### FnL {#a6ab58e4d2fb258a0d2c839fbfdae9024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::FunctionComparator::FnL</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>.</p>


<p>Referenced by <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>, <a href="#a96167048c547bb562d69720cee2a48a6">cmpTypes</a>, <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a>, <a href="#a4ca10cc5976994ee1c01be4b019c1ee6">compare</a>, <a href="#a404aec2d456394b3b9ace0364045cfa2">compareSignature</a> and <a href="#a0d0bc707a7410d5e1225c5e29a6f0c0c">FunctionComparator</a>.</p>

</div>
</div>

### FnR {#a2fec2baea95adaabe3bec634298422db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * llvm::FunctionComparator::FnR</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>.</p>


<p>Referenced by <a href="#aecc5ef45f49070634ddd53a04ed5548e">cmpConstants</a>, <a href="#ac7b438ce165bdc9f0bff4c55f8c0f499">cmpValues</a>, <a href="#a4ca10cc5976994ee1c01be4b019c1ee6">compare</a>, <a href="#a404aec2d456394b3b9ace0364045cfa2">compareSignature</a> and <a href="#a0d0bc707a7410d5e1225c5e29a6f0c0c">FunctionComparator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GlobalNumbers {#aac8d9e79148bc71611a20406b85c991b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalNumberState* llvm::FunctionComparator::GlobalNumbers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>.</p>

</div>
</div>

### sn\_mapL {#a77ad785d8141826893648381c2af01d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value*, int&gt; llvm::FunctionComparator::sn_mapL</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign serial numbers to values from left function, and values from right function.</p>


<p>Explanation: Being comparing functions we need to compare values we meet at left and right sides. Its easy to sort things out for external values. It just should be the same value at left and right. But for local values (those were introduced inside function body) we have to ensure they were introduced at exactly the same place, and plays the same role. Let's assign serial number to each value when we meet it first time. Values that were met at same place will be with same serial numbers. In this case it would be good to explain few points about values assigned to BBs and other ways of implementation (see below).</p>


<ol class="doxyList" type="1">
<li>Safety of BB reordering. It's safe to change the order of BasicBlocks in function. Relationship with other functions and serial numbering will not be changed in this case. As follows from <a href="#a4ca10cc5976994ee1c01be4b019c1ee6">FunctionComparator::compare()</a>, we do CFG walk: we start from the entry, and then take each terminator. So it doesn't matter how in fact BBs are ordered in function. And since cmpValues are called during this walk, the numbering depends only on how BBs located inside the CFG. So the answer is - yes. We will get the same numbering.</li>
<li>Impossibility to use dominance properties of values. If we compare two instruction operands: first is usage of local variable AL from function FL, and second is usage of local variable AR from FR, we could compare their origins and check whether they are defined at the same place. But, we are still not able to compare operands of PHI nodes, since those could be operands from further BBs we didn't scan yet. So it's impossible to use dominance properties in general.</li>
</ol>

<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>.</p>

</div>
</div>

### sn\_mapR {#a5ff9c9c67aa148ddc34ff5f8aac1150d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value*, int&gt; llvm::FunctionComparator::sn_mapR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functioncomparator-h">FunctionComparator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functioncomparator-cpp">FunctionComparator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
