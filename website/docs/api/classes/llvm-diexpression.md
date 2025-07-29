---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diexpression
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DIExpression` Class

<p>DWARF expression. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DIExpression { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> node. <a href="/web-llvm/docs/api/classes/llvm/mdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df6a04b4d600de0d93ed69c8122eb2e">element_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt;::iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a09e6caba71ab15519f9e55ceb4d10d">FragmentInfo</a> = <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo">DbgVariableFragmentInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19950785bfc91a61d088fc2423dcf788">ExtOps</a> = std::array&lt; uint64_t, 6 &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SignedOrUnsignedConstant { <a href="#a5307ea3a541fa8d6d713f305541c0782">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PrependOps : uint8_t { <a href="#a6472489551b8960cc115a93d95eef9f6">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used for <a href="#ab804b15bb92ff685d7c1464b2816d608">DIExpression::prepend</a>. <a href="#a6472489551b8960cc115a93d95eef9f6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e9b9373a267d77e3be3090a7173ff5">DIExpression</a> (LLVMContext &amp;C, StorageType Storage, ArrayRef&lt; uint64_t &gt; Elements)</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae399c69b260865525739b646b3362ee1">~DIExpression</a> ()=default</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression/expr-op-iterator">expr_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2385d3ed339f953fa0d9ff2bed10483d">expr_op_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit the elements via <a href="/web-llvm/docs/api/classes/llvm/diexpression/exproperand">ExprOperand</a> wrappers. <a href="#a2385d3ed339f953fa0d9ff2bed10483d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression/expr-op-iterator">expr_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fa5abf71eb1019c5a31a969ef43bac2">expr_op_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/expr-op-iterator">expr_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42258a251b06bafacc8a2c21f1537500">DEFINE_MDNODE_GET</a> (DIExpression,(ArrayRef&lt; uint64_t &gt; Elements),(Elements)) TempDIExpression clone() const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7e344136f26c673bbd64e6cb88178a">getElements</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b59c8fe81267b338774bf6c542f90ee">getNumElements</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa07b8d87479ec84346886b96ef5912a">getElement</a> (unsigned I) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a5307ea3a541fa8d6d713f305541c0782">SignedOrUnsignedConstant</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acabd4da8227159965c0baf81f9643d39">isConstant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this represents a constant value, if so. <a href="#acabd4da8227159965c0baf81f9643d39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aef6cbb464a57070a26cf422b979df9">getNumLocationOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of unique location operands referred to (via DW_OP_LLVM_arg) in this expression; this is not necessarily the number of instances of DW_OP_LLVM_arg within the expression. <a href="#a9aef6cbb464a57070a26cf422b979df9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1df6a04b4d600de0d93ed69c8122eb2e">element_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54244237156023415444d12acb4f2829">elements_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1df6a04b4d600de0d93ed69c8122eb2e">element_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c248324c8be329a7f619041c4d19ea">elements_end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad63287a310a4434048a6ee1abeea261e">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c6397a9b21812183d69e90c3dac17f9">startsWithDeref</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the first element a DW_OP_deref. <a href="#a3c6397a9b21812183d69e90c3dac17f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8facdaa3e5cf886085dbc81082bc8d41">isDeref</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether there is exactly one operator and it is a DW_OP_deref;. <a href="#a8facdaa3e5cf886085dbc81082bc8d41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa436f5a29352b2ea04248061b0ed8a4d">getActiveBits</a> (DIVariable *Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bits that have an active value, i.e. <a href="#aa436f5a29352b2ea04248061b0ed8a4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a2a09e6caba71ab15519f9e55ceb4d10d">FragmentInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57923a1622a946ed07ac664898571b99">getFragmentInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the details of this fragment expression. <a href="#a57923a1622a946ed07ac664898571b99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09cb593dee41c8fc24828091be9f992f">isFragment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether this is a piece of an aggregate variable. <a href="#a09cb593dee41c8fc24828091be9f992f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40cd3c3332ecc579f7a92924714d6d5c">isImplicit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether this is an implicit location description. <a href="#a40cd3c3332ecc579f7a92924714d6d5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7926734793677673e68d8cff410552ec">isComplex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the location is computed on the expression stack, meaning it cannot be a simple register location. <a href="#a7926734793677673e68d8cff410552ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a4fe1aa8e698aa8cd6a24751a80d91">isSingleLocationExpression</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the evaluated expression makes use of a single location at the start of the expression, i.e. <a href="#ac9a4fe1aa8e698aa8cd6a24751a80d91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the elements contained in this expression, skipping past the leading <span class="doxyComputerOutput">DW_OP_LLVM_arg, 0</span> if one is present. <a href="#ac93b77f1f537436cbb281bbc34b3bd96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ddc726fd7cdca07f747a5394c7c492">extractIfOffset</a> (int64_t &amp;Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a constant offset, extract it. <a href="#a25ddc726fd7cdca07f747a5394c7c492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8478c6263c444e06a6c80f0b3df98c">extractLeadingOffset</a> (int64_t &amp;OffsetInBytes, SmallVectorImpl&lt; uint64_t &gt; &amp;RemainingOps) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assuming that the expression operates on an address, extract a constant offset and the successive ops. <a href="#aca8478c6263c444e06a6c80f0b3df98c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55331359f9d74f5969a5b1ac700cbccd">hasAllLocationOps</a> (unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff this <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> contains at least one instance of <span class="doxyComputerOutput">DW_OP_LLVM_arg, n</span> for all n in [0, N). <a href="#a55331359f9d74f5969a5b1ac700cbccd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db6c0b1668b619833216566c16a9728">fragmentCmp</a> (const DIExpression *Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the relative position of the fragments described by this <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> and <span class="doxyComputerOutput">Other</span>. <a href="#a2db6c0b1668b619833216566c16a9728">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79a5cb53dbe209aae83af6b05a90de04">fragmentsOverlap</a> (const DIExpression *Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if fragments overlap between this <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> and <span class="doxyComputerOutput">Other</span>. <a href="#a79a5cb53dbe209aae83af6b05a90de04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a012168d44e49d5120cf8919cd096fd3b">isEntryValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the expression consists of exactly one entry value operand. <a href="#a012168d44e49d5120cf8919cd096fd3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e4ee2a70091fe36640fda28c69580c6">constantFold</a> (const ConstantInt *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to shorten an expression with an initial constant operand. <a href="#a8e4ee2a70091fe36640fda28c69580c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a804421879fbddb541d8393ec3c3730ee">foldConstantMath</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to shorten an expression with constant math operations that can be evaluated at compile time. <a href="#a804421879fbddb541d8393ec3c3730ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TempDIExpression</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047c3d37fa300286048e2e036b5c138a">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0609c1b8c1c7c655a022dea381b5e3df">Elements</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9178f86e040a88869d74de58943905">classof</a> (const Metadata *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="#a2a09e6caba71ab15519f9e55ceb4d10d">FragmentInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc5f1632a4c520497898439c17dc026">getFragmentInfo</a> (expr_op_iterator Start, expr_op_iterator End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the details of this fragment expression. <a href="#a7cc5f1632a4c520497898439c17dc026">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab420b672954fd0fc80a22da36dd9cc52">convertToUndefExpression</a> (const DIExpression *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes all elements from <span class="doxyComputerOutput">Expr</span> that do not apply to an undef debug value, which includes every operator that computes the value/location on the DWARF stack, including any DW_OP_LLVM_arg elements (making the result of this function always a single-location expression) while leaving everything that defines what the computed value applies to, i.e. <a href="#ab420b672954fd0fc80a22da36dd9cc52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99560dec7123cee3a3e6bbc0d70befdd">convertToVariadicExpression</a> (const DIExpression *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">Expr</span> is a non-variadic expression (i.e. <a href="#a99560dec7123cee3a3e6bbc0d70befdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854dc7a14b5443f6244301690474c7a0">convertToNonVariadicExpression</a> (const DIExpression *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">Expr</span> is a valid single-location expression, i.e. <a href="#a854dc7a14b5443f6244301690474c7a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa68d326a8239d9ee5ae5196e81b68582">canonicalizeExpressionOps</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Ops, const DIExpression *Expr, bool IsIndirect)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts the elements of <span class="doxyComputerOutput">Expr</span> into <span class="doxyComputerOutput">Ops</span> modified to a canonical form, which uses DW_OP_LLVM_arg (i.e. <a href="#aa68d326a8239d9ee5ae5196e81b68582">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2210b0af48ac382a4986510d1406bc">isEqualExpression</a> (const DIExpression *FirstExpr, bool FirstIndirect, const DIExpression *SecondExpr, bool SecondIndirect)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines whether two debug values should produce equivalent DWARF expressions, using their DIExpressions and directness, ignoring the differences between otherwise identical expressions in variadic and non-variadic form and not considering the debug operands. <a href="#a3e2210b0af48ac382a4986510d1406bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272fe723d8c234f2137d34621a5cef78">appendOffset</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Ops, int64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append <span class="doxyComputerOutput">Ops</span> with operations to apply the <span class="doxyComputerOutput">Offset</span>. <a href="#a272fe723d8c234f2137d34621a5cef78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0a91f5f2e148fabfcc21454c7768b40">extractAddressClass</a> (const DIExpression *Expr, unsigned &amp;AddrClass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the last 4 elements of the expression are DW_OP_constu &lt;DWARF
Address Space&gt; DW_OP_swap DW_OP_xderef and extracts the &lt;DWARF Address
Space&gt;. <a href="#af0a91f5f2e148fabfcc21454c7768b40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab804b15bb92ff685d7c1464b2816d608">prepend</a> (const DIExpression *Expr, uint8_t Flags, int64_t Offset=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepend <span class="doxyComputerOutput">DIExpr</span> with a deref and offset operation and optionally turn it into a stack value or/and an entry value. <a href="#ab804b15bb92ff685d7c1464b2816d608">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a48df3735933cf1621760019e5fd8c">prependOpcodes</a> (const DIExpression *Expr, SmallVectorImpl&lt; uint64_t &gt; &amp;Ops, bool StackValue=false, bool EntryValue=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepend <span class="doxyComputerOutput">DIExpr</span> with the given opcodes and optionally turn it into a stack value. <a href="#af3a48df3735933cf1621760019e5fd8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15f4de7989cc83855e8f65792ae94bc4">append</a> (const DIExpression *Expr, ArrayRef&lt; uint64_t &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the opcodes <span class="doxyComputerOutput">Ops</span> to <span class="doxyComputerOutput">DIExpr</span>. <a href="#a15f4de7989cc83855e8f65792ae94bc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac255b2b7ff59963227ea39e1d176f63a">appendToStack</a> (const DIExpression *Expr, ArrayRef&lt; uint64_t &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert <span class="doxyComputerOutput">DIExpr</span> into a stack value if it isn't one already by appending DW_OP_deref if needed, and appending <span class="doxyComputerOutput">Ops</span> to the resulting expression. <a href="#ac255b2b7ff59963227ea39e1d176f63a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f48305fa7d23161515c94bca7c2beb6">appendOpsToArg</a> (const DIExpression *Expr, ArrayRef&lt; uint64_t &gt; Ops, unsigned ArgNo, bool StackValue=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a copy of <span class="doxyComputerOutput">Expr</span> by appending the given list of <span class="doxyComputerOutput">Ops</span> to each instance of the operand <span class="doxyComputerOutput">DW_OP_LLVM_arg, \p ArgNo</span>. <a href="#a5f48305fa7d23161515c94bca7c2beb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c14a49c489d623a8174f48b368cd3e8">replaceArg</a> (const DIExpression *Expr, uint64_t OldArg, uint64_t NewArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a copy of <span class="doxyComputerOutput">Expr</span> with each instance of <span class="doxyComputerOutput">DW_OP_LLVM_arg, \p OldArg</span> replaced with <span class="doxyComputerOutput">DW_OP_LLVM_arg, \p NewArg</span>, and each instance of <span class="doxyComputerOutput">DW_OP_LLVM_arg, Arg</span> with <span class="doxyComputerOutput">DW_OP_LLVM_arg, Arg - 1</span> for all Arg &gt; <span class="doxyComputerOutput">OldArg</span>. <a href="#a9c14a49c489d623a8174f48b368cd3e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2fc167f75191e1d22e12e8e382605bb">createFragmentExpression</a> (const DIExpression *Expr, unsigned OffsetInBits, unsigned SizeInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> to describe one part of an aggregate variable that is fragmented across multiple Values. <a href="#ab2fc167f75191e1d22e12e8e382605bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd5915f3d0282066e03560c56ea075e">fragmentCmp</a> (const FragmentInfo &amp;A, const FragmentInfo &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the relative position of the fragments passed in. <a href="#a6dd5915f3d0282066e03560c56ea075e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea8623be899e029827af260965c860d">calculateFragmentIntersect</a> (const DataLayout &amp;DL, const Value *SliceStart, uint64_t SliceOffsetInBits, uint64_t SliceSizeInBits, const Value *DbgPtr, int64_t DbgPtrOffsetInBits, int64_t DbgExtractOffsetInBits, DIExpression::FragmentInfo VarFrag, std::optional&lt; DIExpression::FragmentInfo &gt; &amp;Result, int64_t &amp;OffsetFromLocationInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes a fragment, bit-extract operation if needed, and new constant offset to describe a part of a variable covered by some memory. <a href="#a4ea8623be899e029827af260965c860d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a19950785bfc91a61d088fc2423dcf788">ExtOps</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21411e047f9e3a5a7557b7b14982a04b">getExtOps</a> (unsigned FromSize, unsigned ToSize, bool Signed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the ops for a zero- or sign-extension in a <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a>. <a href="#a21411e047f9e3a5a7557b7b14982a04b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac687b806c1ee6f3e560b206de208a7e3">appendExt</a> (const DIExpression *Expr, unsigned FromSize, unsigned ToSize, bool Signed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append a zero- or sign-extension to <span class="doxyComputerOutput">Expr</span>. <a href="#ac687b806c1ee6f3e560b206de208a7e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d29699ee79b3a3d7359278f6bab01c">fragmentsOverlap</a> (const FragmentInfo &amp;A, const FragmentInfo &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if fragments overlap between a pair of FragmentInfos. <a href="#a46d29699ee79b3a3d7359278f6bab01c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79cd7d68470466d0b4fa1882d56dad3">getImpl</a> (LLVMContext &amp;Context, ArrayRef&lt; uint64_t &gt; Elements, StorageType Storage, bool ShouldCreate=true)</td>
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

<p>DWARF expression.</p>


<p>This is (almost) a DWARF expression that modifies the location of a variable, or the location of a single piece of a variable, or (when using DW_OP_stack_value) is the constant variable value.</p>


<p>TODO: Co-allocate the expression elements. TODO: Separate from <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a>, or otherwise drop Distinct and Temporary storage types.</p>


<p>Definition at line 2763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### element\_iterator {#a1df6a04b4d600de0d93ed69c8122eb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DIExpression::element_iterator =  ArrayRef&lt;uint64_t&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### ExtOps {#a19950785bfc91a61d088fc2423dcf788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DIExpression::ExtOps =  std::array&lt;uint64_t, 6&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### FragmentInfo {#a2a09e6caba71ab15519f9e55ceb4d10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DIExpression::FragmentInfo =  DbgVariableFragmentInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2927 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### PrependOps {#a6472489551b8960cc115a93d95eef9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DIExpression::PrependOps : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used for <a href="#ab804b15bb92ff685d7c1464b2816d608">DIExpression::prepend</a>.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ApplyOffset<a id="a6472489551b8960cc115a93d95eef9f6a4ce0a0358c0de36a6ea4413d7abcbca8"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DerefBefore<a id="a6472489551b8960cc115a93d95eef9f6a18f3c7099f5b8bfe10361a97ee34a5c9"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DerefAfter<a id="a6472489551b8960cc115a93d95eef9f6a9778207fdbedcd56192301c38b5ffe4c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StackValue<a id="a6472489551b8960cc115a93d95eef9f6ac12819115837830defd8e5b9e5d1fb36"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EntryValue<a id="a6472489551b8960cc115a93d95eef9f6a732b32a9387e1f0a0b49cd59b96905ae"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 3043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SignedOrUnsignedConstant {#a5307ea3a541fa8d6d713f305541c0782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::DIExpression::SignedOrUnsignedConstant </td>
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
<td class="doxyEnumItemName">SignedConstant<a id="a5307ea3a541fa8d6d713f305541c0782a8a57732b81b5f0593b28e007f88acd95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnsignedConstant<a id="a5307ea3a541fa8d6d713f305541c0782a96e79d1e0a81cdd5e68865fbe9132f2e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LLVMContextImpl {#aa81f87de855d80e4275071841a7e0c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl">LLVMContextImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 2764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>


<p>Referenced by <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>

</div>
</div>

### MDNode {#acf51c34793180f67be514c1d6e4167f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 2765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/metadata/#a8265bf29997e9e49d47a38a762d4bb0f">llvm::Metadata::Storage</a>.</p>


<p>Referenced by <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DIExpression() {#a38e9b9373a267d77e3be3090a7173ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIExpression::DIExpression (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Elements)</td>
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



<p>Definition at line 2769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~DIExpression() {#ae399c69b260865525739b646b3362ee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIExpression::~DIExpression ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### expr\_op\_begin() {#a2385d3ed339f953fa0d9ff2bed10483d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">expr_op_iterator llvm::DIExpression::expr_op_begin ()</td>
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

<p>Visit the elements via <a href="/web-llvm/docs/api/classes/llvm/diexpression/exproperand">ExprOperand</a> wrappers.</p>


<p>These range iterators visit elements through <em><a href="/web-llvm/docs/api/classes/llvm/diexpression/exproperand">ExprOperand</a></em> wrappers. This is not guaranteed to be a valid range unless <em><a href="#ad63287a310a4434048a6ee1abeea261e">isValid()</a></em> gives <span class="doxyComputerOutput">true</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><em><a href="#ad63287a310a4434048a6ee1abeea261e">isValid()</a></em> gives <span class="doxyComputerOutput">true</span>.</p></dd>
</dl>


<p>Definition at line 2904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#a54244237156023415444d12acb4f2829">elements_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a20a446c2f1ffd55e5e8c6499bc1795e9">llvm::DIExpressionCursor::DIExpressionCursor</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/structs/llvm/dbgvariablelocation/#aba45f582b07732ab64d6d518d4b45b12">llvm::DbgVariableLocation::extractFromMachineInstruction</a>, <a href="#a57923a1622a946ed07ac664898571b99">getFragmentInfo</a> and <a href="#ad63287a310a4434048a6ee1abeea261e">isValid</a>.</p>

</div>
</div>

### expr\_op\_end() {#a3fa5abf71eb1019c5a31a969ef43bac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">expr_op_iterator llvm::DIExpression::expr_op_end ()</td>
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



<p>Definition at line 2907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#a00c248324c8be329a7f619041c4d19ea">elements_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a20a446c2f1ffd55e5e8c6499bc1795e9">llvm::DIExpressionCursor::DIExpressionCursor</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/structs/llvm/dbgvariablelocation/#aba45f582b07732ab64d6d518d4b45b12">llvm::DbgVariableLocation::extractFromMachineInstruction</a>, <a href="#a57923a1622a946ed07ac664898571b99">getFragmentInfo</a> and <a href="#ad63287a310a4434048a6ee1abeea261e">isValid</a>.</p>

</div>
</div>

### expr\_ops() {#a040fc6238a02edb543766c9d9644d35f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; expr_op_iterator &gt; llvm::DIExpression::expr_ops ()</td>
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



<p>Definition at line 2910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#a2385d3ed339f953fa0d9ff2bed10483d">expr_op_begin</a> and <a href="#a3fa5abf71eb1019c5a31a969ef43bac2">expr_op_end</a>.</p>


<p>Referenced by <a href="#a15f4de7989cc83855e8f65792ae94bc4">append</a>, <a href="#a5f48305fa7d23161515c94bca7c2beb6">appendOpsToArg</a>, <a href="#aa68d326a8239d9ee5ae5196e81b68582">canonicalizeExpressionOps</a>, <a href="#a8e4ee2a70091fe36640fda28c69580c6">constantFold</a>, <a href="#a99560dec7123cee3a3e6bbc0d70befdd">convertToVariadicExpression</a>, <a href="#ab2fc167f75191e1d22e12e8e382605bb">createFragmentExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a4c75a6c6ed9dedc2ff52927972587023">createOrReplaceFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="#aa436f5a29352b2ea04248061b0ed8a4d">getActiveBits</a>, <a href="#a9aef6cbb464a57070a26cf422b979df9">getNumLocationOperands</a>, <a href="#a55331359f9d74f5969a5b1ac700cbccd">hasAllLocationOps</a>, <a href="#a7926734793677673e68d8cff410552ec">isComplex</a>, <a href="#a40cd3c3332ecc579f7a92924714d6d5c">isImplicit</a>, <a href="#ac9a4fe1aa8e698aa8cd6a24751a80d91">isSingleLocationExpression</a>, <a href="#af3a48df3735933cf1621760019e5fd8c">prependOpcodes</a> and <a href="#a9c14a49c489d623a8174f48b368cd3e8">replaceArg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### constantFold() {#a8e4ee2a70091fe36640fda28c69580c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIExpression *, const ConstantInt * &gt; DIExpression::constantFold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to shorten an expression with an initial constant operand.</p>


<p>Returns a new expression and constant on success, or the original expression and constant on failure.</p>


<p>Declaration at line 3199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 2168 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0caee0952c3cd8bf8106bbfa0a323c1ca82">llvm::dwarf::DW_OP_LLVM_convert</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a9b5fc98b47d44d1150d3610bdfab1430">llvm::APInt::sextOrTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7eb536540d37a55860c52b81778b013e">llvm::FastISel::lowerDbgValue</a>.</p>

</div>
</div>

### DEFINE\_MDNODE\_GET() {#a42258a251b06bafacc8a2c21f1537500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIExpression::DEFINE_MDNODE_GET (<a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a>, (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Elements), (Elements))</td>
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



<p>Definition at line 2783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### elements\_begin() {#a54244237156023415444d12acb4f2829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">element_iterator llvm::DIExpression::elements_begin ()</td>
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



<p>Definition at line 2813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a> and <a href="#a9b7e344136f26c673bbd64e6cb88178a">getElements</a>.</p>


<p>Referenced by <a href="#aa68d326a8239d9ee5ae5196e81b68582">canonicalizeExpressionOps</a>, <a href="#a99560dec7123cee3a3e6bbc0d70befdd">convertToVariadicExpression</a> and <a href="#a2385d3ed339f953fa0d9ff2bed10483d">expr_op_begin</a>.</p>

</div>
</div>

### elements\_end() {#a00c248324c8be329a7f619041c4d19ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">element_iterator llvm::DIExpression::elements_end ()</td>
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



<p>Definition at line 2814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a> and <a href="#a9b7e344136f26c673bbd64e6cb88178a">getElements</a>.</p>


<p>Referenced by <a href="#aa68d326a8239d9ee5ae5196e81b68582">canonicalizeExpressionOps</a>, <a href="#a99560dec7123cee3a3e6bbc0d70befdd">convertToVariadicExpression</a> and <a href="#a3fa5abf71eb1019c5a31a969ef43bac2">expr_op_end</a>.</p>

</div>
</div>

### extractIfOffset() {#a25ddc726fd7cdca07f747a5394c7c492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::extractIfOffset (int64_t &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a constant offset, extract it.</p>


<p>If there is no expression, return true with an offset of zero.</p>


<p>Declaration at line 3020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1736 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a6989fb54b0ff045520a716621e13067d">transferSRADebugInfo</a>.</p>

</div>
</div>

### extractLeadingOffset() {#aca8478c6263c444e06a6c80f0b3df98c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::extractLeadingOffset (int64_t &amp; OffsetInBytes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; RemainingOps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assuming that the expression operates on an address, extract a constant offset and the successive ops.</p>


<p>Return false if the expression contains any incompatible ops (including non-zero DW_OP_LLVM_args - only a single address operand to the expression is permitted).</p>


<p>We don't try very hard to interpret the expression because we assume that foldConstantMath has canonicalized the expression.</p>


<p>Declaration at line 3029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1767 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cafa8715d4f64791c3f0b479ececa39d34">llvm::dwarf::DW_OP_LLVM_extract_bits_sext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca3d02f9a2d8b9066b6c6ef1a39018de7f">llvm::dwarf::DW_OP_LLVM_extract_bits_zext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a> and <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a>.</p>

</div>
</div>

### foldConstantMath() {#a804421879fbddb541d8393ec3c3730ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIExpression::foldConstantMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to shorten an expression with constant math operations that can be evaluated at compile time.</p>


<p>Returns a new expression on success, or the old expression if there is nothing to be reduced.</p>


<p>Declaration at line 3204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#ade8a5e3b6a082e4cb8bb4202ae7f652a">canonicalizeDwarfOperations</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#abf31f517c8657e44b85f80ba0d5f41a6">consumeOneOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#ac0d81675f096becfb4ab791f569f951b">isConstantVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#a8949a90af3c69d31f132d6933c4d5914">optimizeDwarfOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a76ebfb1bca92ec8cf347deae857a2b35">llvm::DIExpressionCursor::peek</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a01f4fc152711818825bc2fd1d279063d">llvm::DIExpressionCursor::peekNext</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a5936f4188ab3407a34414892d9305324">llvm::DIExpressionCursor::peekNextN</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#a789d043cecadfc51338fee7f9683324a">tryFoldCommutativeMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#aa3f0516b6857ed87b9547d6f65dd6897">tryFoldCommutativeMathWithArgInBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#aaa2373cd29671119d8d4c12077c4f9da">tryFoldConstants</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#a067186aa899ad496af6a360ce9515eee">tryFoldNoOpMath</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#afe18f2bacebf9cbf307a33cf86b81e4e">salvageDbgAssignAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a245a901981dbba45d423697bb3351b1b">llvm::salvageDebugInfoForDbgValues</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a>.</p>

</div>
</div>

### fragmentCmp() {#a2db6c0b1668b619833216566c16a9728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::DIExpression::fragmentCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Other)</td>
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

<p>Determine the relative position of the fragments described by this <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> and <span class="doxyComputerOutput">Other</span>.</p>


<p>Calls static fragmentCmp implementation.</p>


<p>Definition at line 3178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#a6dd5915f3d0282066e03560c56ea075e">fragmentCmp</a>, <a href="#a57923a1622a946ed07ac664898571b99">getFragmentInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### fragmentsOverlap() {#a79a5cb53dbe209aae83af6b05a90de04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIExpression::fragmentsOverlap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Other)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if fragments overlap between this <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> and <span class="doxyComputerOutput">Other</span>.</p>

<p>Definition at line 3185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#a6dd5915f3d0282066e03560c56ea075e">fragmentCmp</a>, <a href="#a09cb593dee41c8fc24828091be9f992f">isFragment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### getActiveBits() {#aa436f5a29352b2ea04248061b0ed8a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DIExpression::getActiveBits (<a href="/web-llvm/docs/api/classes/llvm/divariable">DIVariable</a> * Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of bits that have an active value, i.e.</p>


<p>those that aren't known to be zero/sign (depending on the type of Var) and which are within the size of this fragment (if it is one). If we can't deduce anything from the expression this will return the size of Var.</p>


<p>Declaration at line 2933 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1686 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cafa8715d4f64791c3f0b479ececa39d34">llvm::dwarf::DW_OP_LLVM_extract_bits_sext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca3d02f9a2d8b9066b6c6ef1a39018de7f">llvm::dwarf::DW_OP_LLVM_extract_bits_zext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a07db644f289c0f86fcf989f17d2b6572">llvm::DIVariable::getSignedness</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a6b5977deeb9f99e156685e190de78403">llvm::DIVariable::getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/dibasictype/#a60f94cc0e71193b01ca24ef37de9845aa71fed0c3428bf1a2e19af257c4bac379">llvm::DIBasicType::Signed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0bdd0669ab7b82ba709bfedcb751dcc3">valueCoversEntireFragment</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a05d7d91d31a8121c140a4da8645c6474">valueCoversEntireFragment</a>.</p>

</div>
</div>

### getElement() {#aaa07b8d87479ec84346886b96ef5912a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DIExpression::getElement (unsigned I)</td>
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



<p>Definition at line 2791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="#acabd4da8227159965c0baf81f9643d39">isConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#acf65ce696212774397a4c1a3afc44275">updateOneDbgValueForAlloca</a>.</p>

</div>
</div>

### getElements() {#a9b7e344136f26c673bbd64e6cb88178a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint64_t &gt; llvm::DIExpression::getElements ()</td>
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



<p>Definition at line 2787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#ac255b2b7ff59963227ea39e1d176f63a">appendToStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aca4868511b7a594d12cd9581b9777e9f">combineDIExpressions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a5ae41c589bd3c54f2a968e8336f3aa98">dropInitialDeref</a>, <a href="#a54244237156023415444d12acb4f2829">elements_begin</a>, <a href="#a00c248324c8be329a7f619041c4d19ea">elements_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad86cc3ddbd30cefe005d825b5587321f">getDerefOffsetInBytes</a> and <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a>.</p>

</div>
</div>

### getFragmentInfo() {#a57923a1622a946ed07ac664898571b99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; FragmentInfo &gt; llvm::DIExpression::getFragmentInfo ()</td>
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

<p>Retrieve the details of this fragment expression.</p>

<p>Definition at line 2940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#a2385d3ed339f953fa0d9ff2bed10483d">expr_op_begin</a>, <a href="#a3fa5abf71eb1019c5a31a969ef43bac2">expr_op_end</a> and <a href="#a57923a1622a946ed07ac664898571b99">getFragmentInfo</a>.</p>


<p>Referenced by <a href="#a2db6c0b1668b619833216566c16a9728">fragmentCmp</a>, <a href="#a57923a1622a946ed07ac664898571b99">getFragmentInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a0aad1c5c3b32063a952fce1c03f31b98">llvm::DIExpressionCursor::getFragmentInfo</a> and <a href="#a09cb593dee41c8fc24828091be9f992f">isFragment</a>.</p>

</div>
</div>

### getNumElements() {#a1b59c8fe81267b338774bf6c542f90ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIExpression::getNumElements ()</td>
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



<p>Definition at line 2789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#ac255b2b7ff59963227ea39e1d176f63a">appendToStack</a>, <a href="#a99560dec7123cee3a3e6bbc0d70befdd">convertToVariadicExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a12d9c2c86e33faf07858a46c4bad9544">finishCallSiteParams</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad86cc3ddbd30cefe005d825b5587321f">getDerefOffsetInBytes</a>, <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a>, <a href="#a7926734793677673e68d8cff410552ec">isComplex</a>, <a href="#acabd4da8227159965c0baf81f9643d39">isConstant</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#a930c119c5ebcb496e7665a4521f42b94">TransferTracker::isEntryValueVariable</a>, <a href="#a40cd3c3332ecc579f7a92924714d6d5c">isImplicit</a>, <a href="#ac9a4fe1aa8e698aa8cd6a24751a80d91">isSingleLocationExpression</a>, <a href="#ad63287a310a4434048a6ee1abeea261e">isValid</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a9db16f6b49d380b76183877d54b42c5c">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a245a901981dbba45d423697bb3351b1b">llvm::salvageDebugInfoForDbgValues</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#acf65ce696212774397a4c1a3afc44275">updateOneDbgValueForAlloca</a>.</p>

</div>
</div>

### getNumLocationOperands() {#a9aef6cbb464a57070a26cf422b979df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DIExpression::getNumLocationOperands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of unique location operands referred to (via DW_OP_LLVM_arg) in this expression; this is not necessarily the number of instances of DW_OP_LLVM_arg within the expression.</p>


<p>For example, for the expression: (DW_OP_LLVM_arg 0, DW_OP_LLVM_arg 1, DW_OP_plus, DW_OP_LLVM_arg 0, DW_OP_mul) This function would return 2, as there are two unique location operands (0 and 1).</p>


<p>Declaration at line 2809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 2206 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a> and <a href="#a55331359f9d74f5969a5b1ac700cbccd">hasAllLocationOps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a245a901981dbba45d423697bb3351b1b">llvm::salvageDebugInfoForDbgValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8cf671ed90e3e80717aaa6318b24794c">llvm::SelectionDAGBuilder::salvageUnresolvedDbgValue</a>.</p>

</div>
</div>

### getSingleLocationExpressionElements() {#ac93b77f1f537436cbb281bbc34b3bd96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ArrayRef&lt; uint64_t &gt; &gt; DIExpression::getSingleLocationExpressionElements ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a reference to the elements contained in this expression, skipping past the leading <span class="doxyComputerOutput">DW_OP_LLVM_arg, 0</span> if one is present.</p>


<p>Similar to <span class="doxyComputerOutput">convertToNonVariadicExpression</span>, but faster and cheaper - it does not check whether the expression is a single-location expression, and it returns elements rather than creating a new <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a>.</p>


<p>Declaration at line 2964 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1584 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="#a9b7e344136f26c673bbd64e6cb88178a">getElements</a>, <a href="#a1b59c8fe81267b338774bf6c542f90ee">getNumElements</a> and <a href="#ac9a4fe1aa8e698aa8cd6a24751a80d91">isSingleLocationExpression</a>.</p>


<p>Referenced by <a href="#a854dc7a14b5443f6244301690474c7a0">convertToNonVariadicExpression</a>, <a href="#af0a91f5f2e148fabfcc21454c7768b40">extractAddressClass</a>, <a href="#a25ddc726fd7cdca07f747a5394c7c492">extractIfOffset</a>, <a href="#aca8478c6263c444e06a6c80f0b3df98c">extractLeadingOffset</a>, <a href="#a8facdaa3e5cf886085dbc81082bc8d41">isDeref</a>, <a href="#a012168d44e49d5120cf8919cd096fd3b">isEntryValue</a> and <a href="#a3c6397a9b21812183d69e90c3dac17f9">startsWithDeref</a>.</p>

</div>
</div>

### hasAllLocationOps() {#a55331359f9d74f5969a5b1ac700cbccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::hasAllLocationOps (unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true iff this <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> contains at least one instance of <span class="doxyComputerOutput">DW_OP_LLVM_arg, n</span> for all n in [0, N).</p>

<p>Declaration at line 3034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1806 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a9aef6cbb464a57070a26cf422b979df9">getNumLocationOperands</a>.</p>

</div>
</div>

### isComplex() {#a7926734793677673e68d8cff410552ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::isComplex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the location is computed on the expression stack, meaning it cannot be a simple register location.</p>

<p>Declaration at line 2952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1540 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca989f426170b8ef321ffeb4838b4c590f">llvm::dwarf::DW_OP_LLVM_tag_offset</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="#a1b59c8fe81267b338774bf6c542f90ee">getNumElements</a> and <a href="#ad63287a310a4434048a6ee1abeea261e">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a88fd52c520cef6a03af97c37c308ae78">LiveDebugValues::MLocTracker::emitLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a49495d1f6880c856ab33832442a9e000">llvm::DbgVariableRecord::isKillLocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ab8a7ab37beb2d225c6cb1e9c6c20d0d0">UpdateDbgValueInst</a>.</p>

</div>
</div>

### isConstant() {#acabd4da8227159965c0baf81f9643d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DIExpression::SignedOrUnsignedConstant &gt; DIExpression::isConstant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether this represents a constant value, if so.</p>

<p>Declaration at line 2799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 2217 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="#aaa07b8d87479ec84346886b96ef5912a">getElement</a>, <a href="#a1b59c8fe81267b338774bf6c542f90ee">getNumElements</a>, <a href="#a5307ea3a541fa8d6d713f305541c0782a8a57732b81b5f0593b28e007f88acd95">SignedConstant</a> and <a href="#a5307ea3a541fa8d6d713f305541c0782a96e79d1e0a81cdd5e68865fbe9132f2e">UnsignedConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>.</p>

</div>
</div>

### isDeref() {#a8facdaa3e5cf886085dbc81082bc8d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::isDeref ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether there is exactly one operator and it is a DW_OP_deref;.</p>

<p>Declaration at line 2925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1388 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>Reference <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/transfertracker/#a930c119c5ebcb496e7665a4521f42b94">TransferTracker::isEntryValueVariable</a>.</p>

</div>
</div>

### isEntryValue() {#a012168d44e49d5120cf8919cd096fd3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::isEntryValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the expression consists of exactly one entry value operand.</p>


<p>(This is the only configuration of entry values that is supported.)</p>


<p>Declaration at line 3193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1375 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca0c7ecbb9cc8d5fb23652e00de7b288a0">llvm::dwarf::DW_OP_LLVM_entry_value</a> and <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a12d9c2c86e33faf07858a46c4bad9544">finishCallSiteParams</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ae45a9559b6fd1578fb4d12f341cbed57">llvm::MachineInstr::isDebugEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc/#af3a1ee026c3f78840848dd5fa9d071ee">llvm::DbgValueLoc::isEntryVal</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7eb536540d37a55860c52b81778b013e">llvm::FastISel::lowerDbgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a80eff7852e73a149806fca03c7df37b0">processIfEntryValueDbgDeclare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a082b9984a203d2a2ba3dd4b5986d4706">llvm::DwarfExpression::setLocation</a>.</p>

</div>
</div>

### isFragment() {#a09cb593dee41c8fc24828091be9f992f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIExpression::isFragment ()</td>
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

<p>Return whether this is a piece of an aggregate variable.</p>

<p>Definition at line 2945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#a57923a1622a946ed07ac664898571b99">getFragmentInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2fdab5e48a4c62a742df876d4e55940f">llvm::DwarfExpression::addFragmentOffset</a>, <a href="#a79a5cb53dbe209aae83af6b05a90de04">fragmentsOverlap</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc/#ad27639d6dc295ea60a4f792cac90b1df">llvm::DbgValueLoc::isFragment</a>.</p>

</div>
</div>

### isImplicit() {#a40cd3c3332ecc579f7a92924714d6d5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::isImplicit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether this is an implicit location description.</p>

<p>Declaration at line 2948 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="#a1b59c8fe81267b338774bf6c542f90ee">getNumElements</a> and <a href="#ad63287a310a4434048a6ee1abeea261e">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aca4868511b7a594d12cd9581b9777e9f">combineDIExpressions</a>, <a href="#ab2fc167f75191e1d22e12e8e382605bb">createFragmentExpression</a> and <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a88fd52c520cef6a03af97c37c308ae78">LiveDebugValues::MLocTracker::emitLoc</a>.</p>

</div>
</div>

### isSingleLocationExpression() {#ac9a4fe1aa8e698aa8cd6a24751a80d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::isSingleLocationExpression ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the evaluated expression makes use of a single location at the start of the expression, i.e.</p>


<p>if it contains only a single DW_OP_LLVM_arg op as its first operand, or if it contains none.</p>


<p>Declaration at line 2957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1563 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="#a1b59c8fe81267b338774bf6c542f90ee">getNumElements</a> and <a href="#ad63287a310a4434048a6ee1abeea261e">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a88fd52c520cef6a03af97c37c308ae78">LiveDebugValues::MLocTracker::emitLoc</a>, <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a>.</p>

</div>
</div>

### isValid() {#ad63287a310a4434048a6ee1abeea261e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::isValid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2915 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1429 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0caee0952c3cd8bf8106bbfa0a323c1ca82">llvm::dwarf::DW_OP_LLVM_convert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca0c7ecbb9cc8d5fb23652e00de7b288a0">llvm::dwarf::DW_OP_LLVM_entry_value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cafa8715d4f64791c3f0b479ececa39d34">llvm::dwarf::DW_OP_LLVM_extract_bits_sext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca3d02f9a2d8b9066b6c6ef1a39018de7f">llvm::dwarf::DW_OP_LLVM_extract_bits_zext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca1d4cd3c9f41c395601558b0bec435888">llvm::dwarf::DW_OP_LLVM_implicit_pointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca989f426170b8ef321ffeb4838b4c590f">llvm::dwarf::DW_OP_LLVM_tag_offset</a>, <a href="#a2385d3ed339f953fa0d9ff2bed10483d">expr_op_begin</a>, <a href="#a3fa5abf71eb1019c5a31a969ef43bac2">expr_op_end</a>, <a href="#a1b59c8fe81267b338774bf6c542f90ee">getNumElements</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc/#a0b4a6d1648810ee79adb140ecfcd313c">llvm::DbgValueLoc::DbgValueLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc/#a08070666eb69541a696eb1212b19ddc5">llvm::DbgValueLoc::DbgValueLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a12d9c2c86e33faf07858a46c4bad9544">finishCallSiteParams</a>, <a href="#a7926734793677673e68d8cff410552ec">isComplex</a>, <a href="#a40cd3c3332ecc579f7a92924714d6d5c">isImplicit</a> and <a href="#ac9a4fe1aa8e698aa8cd6a24751a80d91">isSingleLocationExpression</a>.</p>

</div>
</div>

### startsWithDeref() {#a3c6397a9b21812183d69e90c3dac17f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::startsWithDeref ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the first element a DW_OP_deref.</p>

<p>Declaration at line 2922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1382 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>Reference <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a9db16f6b49d380b76183877d54b42c5c">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneImpl() {#a047c3d37fa300286048e2e036b5c138a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempDIExpression llvm::DIExpression::cloneImpl ()</td>
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



<p>Definition at line 2778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Elements {#a0609c1b8c1c7c655a022dea381b5e3df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; llvm::DIExpression::Elements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### append() {#a15f4de7989cc83855e8f65792ae94bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIExpression::append (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Ops)</td>
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

<p>Append the opcodes <span class="doxyComputerOutput">Ops</span> to <span class="doxyComputerOutput">DIExpr</span>.</p>


<p>Unlike <a href="#ac255b2b7ff59963227ea39e1d176f63a">appendToStack</a>, the returned expression is a stack value only if <span class="doxyComputerOutput">DIExpr</span> is a stack value. If <span class="doxyComputerOutput">DIExpr</span> describes a fragment, the returned expression will describe the same fragment.</p>


<p>Declaration at line 3067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1948 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>.</p>


<p>Referenced by <a href="#ac255b2b7ff59963227ea39e1d176f63a">appendToStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aca4868511b7a594d12cd9581b9777e9f">combineDIExpressions</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7994fd7ca0d8f8fcf2a9d18d151d0988">llvm::LowerDbgDeclare</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a80eff7852e73a149806fca03c7df37b0">processIfEntryValueDbgDeclare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ab8a7ab37beb2d225c6cb1e9c6c20d0d0">UpdateDbgValueInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#adaf155c02ba4c5b8ec6d8d72b50e0f91">upgradeDbgIntrinsicToDbgRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a0b1eb53b30ddeb8ebdccc60c0837300f">walkToAllocaAndPrependOffsetDeref</a>.</p>

</div>
</div>

### appendExt() {#ac687b806c1ee6f3e560b206de208a7e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIExpression::appendExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, unsigned FromSize, unsigned ToSize, bool Signed)</td>
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

<p>Append a zero- or sign-extension to <span class="doxyComputerOutput">Expr</span>.</p>


<p>Converts the expression to a stack value if it isn't one already.</p>


<p>Declaration at line 3168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 2251 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="#ac255b2b7ff59963227ea39e1d176f63a">appendToStack</a>, <a href="#a21411e047f9e3a5a7557b7b14982a04b">getExtOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>.</p>

</div>
</div>

### appendOffset() {#a272fe723d8c234f2137d34621a5cef78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIExpression::appendOffset (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Ops, int64_t Offset)</td>
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

<p>Append <span class="doxyComputerOutput">Ops</span> with operations to apply the <span class="doxyComputerOutput">Offset</span>.</p>

<p>Declaration at line 3016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a86078042131d19e2f2316d66815279cd">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::createOffsetExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a1e101bcf68a4448908d194d220029861">llvm::SystemZRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa93abb15d7ccdae4c8dc69cef75a202a">llvm::AArch64RegisterInfo::getOffsetOpcodes</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a575bd978cab5f3910b4882f7f0c58217">llvm::RISCVRegisterInfo::getOffsetOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#af2460aaecee28b4a96ea41286e8aa406">llvm::TargetRegisterInfo::getOffsetOpcodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a55a8ce252bfbfa1af642af05f2c31e10">getSalvageOpsForBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7144f12bd93229efcf87a052ab80d5e6">getSalvageOpsForGEP</a>, <a href="#ab804b15bb92ff685d7c1464b2816d608">prepend</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a582354e8d5806847614742270d2ece1d">llvm::SelectionDAG::salvageDebugInfo</a>.</p>

</div>
</div>

### appendOpsToArg() {#a5f48305fa7d23161515c94bca7c2beb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIExpression::appendOpsToArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Ops, unsigned ArgNo, bool StackValue=false)</td>
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

<p>Create a copy of <span class="doxyComputerOutput">Expr</span> by appending the given list of <span class="doxyComputerOutput">Ops</span> to each instance of the operand <span class="doxyComputerOutput">DW_OP_LLVM_arg, \p ArgNo</span>.</p>


<p>This is used to modify a specific location used by <span class="doxyComputerOutput">Expr</span>, such as when salvaging that location.</p>


<p>Declaration at line 3080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1858 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="#af3a48df3735933cf1621760019e5fd8c">prependOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a6472489551b8960cc115a93d95eef9f6ac12819115837830defd8e5b9e5d1fb36">StackValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#abdc52e9e6f499ad37b933391860177aa">llvm::memtag::annotateDebugRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a31dbab7857704fe8018197bf23abba19">computeExprForSpill</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a1e101bcf68a4448908d194d220029861">llvm::SystemZRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a88fd52c520cef6a03af97c37c308ae78">LiveDebugValues::MLocTracker::emitLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxprologepilogpass-cpp-/nvptxprologepilogpass/#a58c45f00a8ce8f9282ad2bbcfbd08cde">anonymous{NVPTXPrologEpilogPass.cpp}::NVPTXPrologEpilogPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#afe18f2bacebf9cbf307a33cf86b81e4e">salvageDbgAssignAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a582354e8d5806847614742270d2ece1d">llvm::SelectionDAG::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a245a901981dbba45d423697bb3351b1b">llvm::salvageDebugInfoForDbgValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8cf671ed90e3e80717aaa6318b24794c">llvm::SelectionDAGBuilder::salvageUnresolvedDbgValue</a>.</p>

</div>
</div>

### appendToStack() {#ac255b2b7ff59963227ea39e1d176f63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIExpression::appendToStack (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Ops)</td>
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

<p>Convert <span class="doxyComputerOutput">DIExpr</span> into a stack value if it isn't one already by appending DW_OP_deref if needed, and appending <span class="doxyComputerOutput">Ops</span> to the resulting expression.</p>


<p>If <span class="doxyComputerOutput">DIExpr</span> describes a fragment, the returned expression will describe the same fragment.</p>


<p>Declaration at line 3073 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1972 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a15f4de7989cc83855e8f65792ae94bc4">append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aa713e2599e000adc01ced998c05502a7">llvm::ArrayRef&lt; T &gt;::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#a9b7e344136f26c673bbd64e6cb88178a">getElements</a>, <a href="#a7cc5f1632a4c520497898439c17dc026">getFragmentInfo</a>, <a href="#a1b59c8fe81267b338774bf6c542f90ee">getNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ac687b806c1ee6f3e560b206de208a7e3">appendExt</a>.</p>

</div>
</div>

### calculateFragmentIntersect() {#a4ea8623be899e029827af260965c860d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::calculateFragmentIntersect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SliceStart, uint64_t SliceOffsetInBits, uint64_t SliceSizeInBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DbgPtr, int64_t DbgPtrOffsetInBits, int64_t DbgExtractOffsetInBits, <a href="#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> VarFrag, std::optional&lt; <a href="#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> &gt; &amp; Result, int64_t &amp; OffsetFromLocationInBits)</td>
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

<p>Computes a fragment, bit-extract operation if needed, and new constant offset to describe a part of a variable covered by some memory.</p>


<p>See declaration for more info.</p>


<p>The memory region starts at: <span class="doxyComputerOutput">SliceStart</span> + <span class="doxyComputerOutput">SliceOffsetInBits</span> And is size: <span class="doxyComputerOutput">SliceSizeInBits</span></p>


<p>The location of the existing variable fragment <span class="doxyComputerOutput">VarFrag</span> is: <span class="doxyComputerOutput">DbgPtr</span> + <span class="doxyComputerOutput">DbgPtrOffsetInBits</span> + <span class="doxyComputerOutput">DbgExtractOffsetInBits</span>.</p>


<p>It is intended that these arguments are derived from a debug record:</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">DbgPtr</span> is the (single) <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> operand.</li>
<li><span class="doxyComputerOutput">DbgPtrOffsetInBits</span> is the constant offset applied to <span class="doxyComputerOutput">DbgPtr</span>.</li>
<li><span class="doxyComputerOutput">DbgExtractOffsetInBits</span> is the offset from a DW_OP_LLVM_bit_extract_[sz]ext operation.</li>
</ul>

<p>Results and return value:</p>


<ul class="doxyList ">
<li>Return false if the result can't be calculated for any reason.</li>
<li><span class="doxyComputerOutput">Result</span> is set to nullopt if the intersect equals <span class="doxyComputerOutput">VarFarg</span>.</li>
<li><span class="doxyComputerOutput">Result</span> contains a zero-sized fragment if there's no intersect.</li>
<li><span class="doxyComputerOutput">OffsetFromLocationInBits</span> is set to the difference between the first bit of the variable location and the first bit of the slice. The magnitude of a negative value therefore indicates the number of bits into the variable fragment that the memory region begins.</li>
</ul>

<p>We don't pass in a debug record directly to get the constituent parts and offsets because different debug records store the information in different places (dbg_assign has two DIExpressions - one contains the fragment info for the entire intrinsic).</p>


<p>Declaration at line 3154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 2099 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ac5e4e131889dc27ebec32f382c835971">llvm::Value::getPointerOffsetFrom</a>, <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo/#aa86c07e6c797389355badf65a44276f8">llvm::DbgVariableFragmentInfo::intersect</a>, <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo/#aa448040bf5ec2ebafc3dbe0eb15b6d55">llvm::DbgVariableFragmentInfo::OffsetInBits</a> and <a href="/web-llvm/docs/api/structs/llvm/dbgvariablefragmentinfo/#af581a7bb056b2b642d6705cc4af65fa2">llvm::DbgVariableFragmentInfo::SizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a619cfadc608f78f1b1ac61c885ea2bbc">calculateFragmentIntersectImpl</a>.</p>

</div>
</div>

### canonicalizeExpressionOps() {#aa68d326a8239d9ee5ae5196e81b68582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIExpression::canonicalizeExpressionOps (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Ops, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, bool IsIndirect)</td>
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

<p>Inserts the elements of <span class="doxyComputerOutput">Expr</span> into <span class="doxyComputerOutput">Ops</span> modified to a canonical form, which uses DW_OP_LLVM_arg (i.e.</p>


<p>is a variadic expression) and folds the implied derefence from the <span class="doxyComputerOutput">IsIndirect</span> flag into the expression. This allows us to check equivalence between expressions with differing directness or variadicness.</p>


<p>Declaration at line 2995 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1634 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="#a54244237156023415444d12acb4f2829">elements_begin</a>, <a href="#a00c248324c8be329a7f619041c4d19ea">elements_end</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>.</p>


<p>Referenced by <a href="#a3e2210b0af48ac382a4986510d1406bc">isEqualExpression</a>.</p>

</div>
</div>

### classof() {#a9c9178f86e040a88869d74de58943905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIExpression::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Definition at line 2917 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

### convertToNonVariadicExpression() {#a854dc7a14b5443f6244301690474c7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; const DIExpression * &gt; DIExpression::convertToNonVariadicExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr)</td>
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

<p>If <span class="doxyComputerOutput">Expr</span> is a valid single-location expression, i.e.</p>


<p>it refers to only a single debug operand at the start of the expression, then return that expression in a non-variadic form by removing DW_OP_LLVM_arg from the expression if it is present; otherwise returns std::nullopt. See also <span class="doxyComputerOutput">getSingleLocationExpressionElements</span> above, which skips checking <span class="doxyComputerOutput">isSingleLocationExpression</span> and returns a list of elements rather than a <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a>.</p>


<p>Declaration at line 2988 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1624 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a> and <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loc/entryvalue/#a01c50402331616f6b2606c9f7b1680da">llvm::Loc::EntryValue::addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aff31f82e78047b9ec0867b80a925d6df">getDebugLocValue</a> and <a href="/web-llvm/docs/api/classes/transfertracker/#ac441348b2e73e12e1d8657de17b76568">TransferTracker::recoverAsEntryValue</a>.</p>

</div>
</div>

### convertToUndefExpression() {#ab420b672954fd0fc80a22da36dd9cc52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIExpression * DIExpression::convertToUndefExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr)</td>
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

<p>Removes all elements from <span class="doxyComputerOutput">Expr</span> that do not apply to an undef debug value, which includes every operator that computes the value/location on the DWARF stack, including any DW_OP_LLVM_arg elements (making the result of this function always a single-location expression) while leaving everything that defines what the computed value applies to, i.e.</p>


<p>the fragment information.</p>


<p>Declaration at line 2972 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1601 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a> and <a href="#a7cc5f1632a4c520497898439c17dc026">getFragmentInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a63e197923d820bd6b000a5344adc92ea">llvm::InstrEmitter::EmitDbgNoLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac42eef26cc4185a8932bc59a94dc5d16">llvm::SelectionDAGBuilder::handleKillDebugValue</a>.</p>

</div>
</div>

### convertToVariadicExpression() {#a99560dec7123cee3a3e6bbc0d70befdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIExpression * DIExpression::convertToVariadicExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr)</td>
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

<p>If <span class="doxyComputerOutput">Expr</span> is a non-variadic expression (i.e.</p>


<p>one that does not contain DW_OP_LLVM_arg), returns <span class="doxyComputerOutput">Expr</span> converted to variadic form by adding a leading [DW_OP_LLVM_arg, 0] to the expression; otherwise returns <span class="doxyComputerOutput">Expr</span>.</p>


<p>Declaration at line 2978 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1611 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="#a54244237156023415444d12acb4f2829">elements_begin</a>, <a href="#a00c248324c8be329a7f619041c4d19ea">elements_end</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="#a1b59c8fe81267b338774bf6c542f90ee">getNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a582354e8d5806847614742270d2ece1d">llvm::SelectionDAG::salvageDebugInfo</a>.</p>

</div>
</div>

### createFragmentExpression() {#ab2fc167f75191e1d22e12e8e382605bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DIExpression * &gt; DIExpression::createFragmentExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, unsigned OffsetInBits, unsigned SizeInBits)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> to describe one part of an aggregate variable that is fragmented across multiple Values.</p>


<p>The DW_OP_LLVM_fragment operation will be appended to the elements of <span class="doxyComputerOutput">Expr</span>. If <span class="doxyComputerOutput">Expr</span> already contains a <span class="doxyComputerOutput">DW_OP_LLVM_fragment</span> <span class="doxyComputerOutput">OffsetInBits</span> is interpreted as an offset into the existing fragment.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Offset of the piece in bits.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Size of the piece in bits.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Creating a fragment expression may fail if <span class="doxyComputerOutput">Expr</span> contains arithmetic operations that would be truncated.</p></dd>
</dl>


<p>Declaration at line 3105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 2006 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cafa8715d4f64791c3f0b479ececa39d34">llvm::dwarf::DW_OP_LLVM_extract_bits_sext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca3d02f9a2d8b9066b6c6ef1a39018de7f">llvm::dwarf::DW_OP_LLVM_extract_bits_zext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a> and <a href="#a40cd3c3332ecc579f7a92924714d6d5c">isImplicit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#a3e5ffea0fa3c8e006a9bb56d22a0aa12">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::DbgVariableValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a9b051a25ba281897b4dc62df58312b7e">emitDbgAssign</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a81d863ec17163a5dcedc09cb1a48aadf">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a0346c3f86c714b9ae84f5566a95e90ac">migrateDebugInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/memlocfragmentfill/#a8c0e38f8e7530ce5863d73acc50d25ff">anonymous{AssignmentTrackingAnalysis.cpp}::MemLocFragmentFill::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a1321465508b2b54862b90ca404386e06">shortenAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afce558f34a90609d76e4c2f45ab5650c">llvm::SelectionDAG::transferDbgValues</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a6989fb54b0ff045520a716621e13067d">transferSRADebugInfo</a>.</p>

</div>
</div>

### extractAddressClass() {#af0a91f5f2e148fabfcc21454c7768b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIExpression * DIExpression::extractAddressClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, unsigned &amp; AddrClass)</td>
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

<p>Checks if the last 4 elements of the expression are DW_OP_constu &lt;DWARF
Address Space&gt; DW_OP_swap DW_OP_xderef and extracts the &lt;DWARF Address
Space&gt;.</p>

<p>Declaration at line 3039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1817 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a> and <a href="#ac93b77f1f537436cbb281bbc34b3bd96">getSingleLocationExpressionElements</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>.</p>

</div>
</div>

### fragmentCmp() {#a6dd5915f3d0282066e03560c56ea075e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::DIExpression::fragmentCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2a09e6caba71ab15519f9e55ceb4d10d">FragmentInfo</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2a09e6caba71ab15519f9e55ceb4d10d">FragmentInfo</a> &amp; B)</td>
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

<p>Determine the relative position of the fragments passed in.</p>


<p>Returns -1 if this is entirely before Other, 0 if this and Other overlap, 1 if this is entirely after Other.</p>


<p>Definition at line 3111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sha1-cpp/#abdad3565c5705ead34a0d0ff9eed5628">r1</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/sha1-cpp/#a723eaa5ada5620f3ec382e24ab5f0da5">r2</a>.</p>


<p>Referenced by <a href="#a2db6c0b1668b619833216566c16a9728">fragmentCmp</a>, <a href="#a79a5cb53dbe209aae83af6b05a90de04">fragmentsOverlap</a> and <a href="#a46d29699ee79b3a3d7359278f6bab01c">fragmentsOverlap</a>.</p>

</div>
</div>

### fragmentsOverlap() {#a46d29699ee79b3a3d7359278f6bab01c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIExpression::fragmentsOverlap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2a09e6caba71ab15519f9e55ceb4d10d">FragmentInfo</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2a09e6caba71ab15519f9e55ceb4d10d">FragmentInfo</a> &amp; B)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if fragments overlap between a pair of FragmentInfos.</p>

<p>Definition at line 3172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a6dd5915f3d0282066e03560c56ea075e">fragmentCmp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac08d1b312ae9756038394d6b9568f383">llvm::SelectionDAGBuilder::dropDanglingDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a9ee24d91499bcb94c513e7db61664312">handleNewDebugValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#ad435005d9876513f43056c258958554a">stashEntryDbgValues</a>.</p>

</div>
</div>

### getExtOps() {#a21411e047f9e3a5a7557b7b14982a04b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression::ExtOps DIExpression::getExtOps (unsigned FromSize, unsigned ToSize, bool Signed)</td>
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

<p>Returns the ops for a zero- or sign-extension in a <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a>.</p>

<p>Declaration at line 3164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 2243 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0caee0952c3cd8bf8106bbfa0a323c1ca82">llvm::dwarf::DW_OP_LLVM_convert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>


<p>Referenced by <a href="#ac687b806c1ee6f3e560b206de208a7e3">appendExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp/#a894fb383cc3e3a326646b5f3366881d2">getSalvageOpsForTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a582354e8d5806847614742270d2ece1d">llvm::SelectionDAG::salvageDebugInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>.</p>

</div>
</div>

### getFragmentInfo() {#a7cc5f1632a4c520497898439c17dc026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DIExpression::FragmentInfo &gt; DIExpression::getFragmentInfo (<a href="/web-llvm/docs/api/classes/llvm/diexpression/expr-op-iterator">expr_op_iterator</a> Start, <a href="/web-llvm/docs/api/classes/llvm/diexpression/expr-op-iterator">expr_op_iterator</a> End)</td>
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

<p>Retrieve the details of this fragment expression.</p>

<p>Declaration at line 2936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1677 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2fdab5e48a4c62a742df876d4e55940f">llvm::DwarfExpression::addFragmentOffset</a>, <a href="#ac255b2b7ff59963227ea39e1d176f63a">appendToStack</a>, <a href="#ab420b672954fd0fc80a22da36dd9cc52">convertToUndefExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#a3e5ffea0fa3c8e006a9bb56d22a0aa12">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::DbgVariableValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a81d863ec17163a5dcedc09cb1a48aadf">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a642f20d33151f41a46e601f14910989c">llvm::DbgVariableIntrinsic::getFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae446f360cb65e72ea25e919c540e7388">llvm::DbgVariableRecord::getFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a4c82990aaa735486cf25766512679d77">getFragmentOffsetInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#afe18f2bacebf9cbf307a33cf86b81e4e">salvageDbgAssignAddress</a>.</p>

</div>
</div>

### isEqualExpression() {#a3e2210b0af48ac382a4986510d1406bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DIExpression::isEqualExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * FirstExpr, bool FirstIndirect, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * SecondExpr, bool SecondIndirect)</td>
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

<p>Determines whether two debug values should produce equivalent DWARF expressions, using their DIExpressions and directness, ignoring the differences between otherwise identical expressions in variadic and non-variadic form and not considering the debug operands.</p>


<p><span class="doxyComputerOutput">FirstExpr</span> is the <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> for the first debug value. <span class="doxyComputerOutput">FirstIndirect</span> should be true if the first debug value is indirect; in IR this should be true for dbg.declare intrinsics and false for dbg.values, and in MIR this should be true only for DBG_VALUE instructions whose second operand is an immediate value. <span class="doxyComputerOutput">SecondExpr</span> and <span class="doxyComputerOutput">SecondIndirect</span> have the same meaning as the prior arguments, but apply to the second debug value.</p>


<p>Declaration at line 3010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1664 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>Reference <a href="#aa68d326a8239d9ee5ae5196e81b68582">canonicalizeExpressionOps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc/#aed9e2c87c90de2626b7e97f055a36067">llvm::DbgValueLoc::isEquivalent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8d4914ca78a5bd34e64807479fc057cf">llvm::MachineInstr::isEquivalentDbgInstr</a> and <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#aa487b5a6fe6c9f4fac7f809c488f3029">LiveDebugValues::DbgValueProperties::isJoinable</a>.</p>

</div>
</div>

### prepend() {#ab804b15bb92ff685d7c1464b2816d608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIExpression::prepend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, uint8_t Flags, int64_t Offset=0)</td>
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

<p>Prepend <span class="doxyComputerOutput">DIExpr</span> with a deref and offset operation and optionally turn it into a stack value or/and an entry value.</p>

<p>Declaration at line 3053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1842 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a272fe723d8c234f2137d34621a5cef78">appendOffset</a>, <a href="#a6472489551b8960cc115a93d95eef9f6a9778207fdbedcd56192301c38b5ffe4c">DerefAfter</a>, <a href="#a6472489551b8960cc115a93d95eef9f6a18f3c7099f5b8bfe10361a97ee34a5c9">DerefBefore</a>, <a href="#a6472489551b8960cc115a93d95eef9f6a732b32a9387e1f0a0b49cd59b96905ae">EntryValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#af3a48df3735933cf1621760019e5fd8c">prependOpcodes</a> and <a href="#a6472489551b8960cc115a93d95eef9f6ac12819115837830defd8e5b9e5d1fb36">StackValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a31dbab7857704fe8018197bf23abba19">computeExprForSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#ac9fa612919367a702574336b92a242d2">llvm::MipsInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#ad8e6a4fdd6c500cf5a2a6f253cd05e65">processDbgDeclare</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#ac441348b2e73e12e1d8657de17b76568">TransferTracker::recoverAsEntryValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afae608ddbbaa668b04aac083a6683245">llvm::replaceDbgDeclare</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/memlocfragmentfill/#a8c0e38f8e7530ce5863d73acc50d25ff">anonymous{AssignmentTrackingAnalysis.cpp}::MemLocFragmentFill::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#acf65ce696212774397a4c1a3afc44275">updateOneDbgValueForAlloca</a>.</p>

</div>
</div>

### prependOpcodes() {#af3a48df3735933cf1621760019e5fd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIExpression::prependOpcodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Ops, bool StackValue=false, bool EntryValue=false)</td>
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

<p>Prepend <span class="doxyComputerOutput">DIExpr</span> with the given opcodes and optionally turn it into a stack value.</p>

<p>Declaration at line 3058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1915 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca0c7ecbb9cc8d5fb23652e00de7b288a0">llvm::dwarf::DW_OP_LLVM_entry_value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="#a6472489551b8960cc115a93d95eef9f6a732b32a9387e1f0a0b49cd59b96905ae">EntryValue</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a> and <a href="#a6472489551b8960cc115a93d95eef9f6ac12819115837830defd8e5b9e5d1fb36">StackValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#abdc52e9e6f499ad37b933391860177aa">llvm::memtag::annotateDebugRecords</a>, <a href="#a5f48305fa7d23161515c94bca7c2beb6">appendOpsToArg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a352ccfab7392a21f5253bca1791022d5">llvm::FastISel::lowerDbgDeclare</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7eb536540d37a55860c52b81778b013e">llvm::FastISel::lowerDbgValue</a>, <a href="#ab804b15bb92ff685d7c1464b2816d608">prepend</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ac6859ef2a1c57ce668658e21fe90bfad">llvm::TargetRegisterInfo::prependOffsetExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a0b1eb53b30ddeb8ebdccc60c0837300f">walkToAllocaAndPrependOffsetDeref</a>.</p>

</div>
</div>

### replaceArg() {#a9c14a49c489d623a8174f48b368cd3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIExpression::replaceArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, uint64_t OldArg, uint64_t NewArg)</td>
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

<p>Create a copy of <span class="doxyComputerOutput">Expr</span> with each instance of <span class="doxyComputerOutput">DW_OP_LLVM_arg, \p OldArg</span> replaced with <span class="doxyComputerOutput">DW_OP_LLVM_arg, \p NewArg</span>, and each instance of <span class="doxyComputerOutput">DW_OP_LLVM_arg, Arg</span> with <span class="doxyComputerOutput">DW_OP_LLVM_arg, Arg - 1</span> for all Arg &gt; <span class="doxyComputerOutput">OldArg</span>.</p>


<p>This is used when replacing one of the operands of a debug value list with another operand in the same list and deleting the old operand.</p>


<p>Declaration at line 3090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1893 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="#a040fc6238a02edb543766c9d9644d35f">expr_ops</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#a3e5ffea0fa3c8e006a9bb56d22a0aa12">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::DbgVariableValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getImpl() {#af79cd7d68470466d0b4fa1882d56dad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * DIExpression::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Elements, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 2774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1369 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
