---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/shufflevectorinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ShuffleVectorInst` Class Reference

<p>This instruction constructs a fixed permutation of two input vectors. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ShuffleVectorInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87273cb892a8182f137567e6b631695e">Instruction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46141ae6646785e46d48cae9f1011511">ShuffleVectorInst</a> (Value *V1, Value *Mask, const Twine &amp;NameStr="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ef22019a6b173a2b6699d5bfccd19d3">ShuffleVectorInst</a> (Value *V1, ArrayRef&lt; int &gt; Mask, const Twine &amp;NameStr="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9550ae3e26eaa39468d80a6940709b5c">ShuffleVectorInst</a> (Value *V1, Value *V2, Value *Mask, const Twine &amp;NameStr="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ca93f9d04de6b4256cdfdb677611ed">ShuffleVectorInst</a> (Value *V1, Value *V2, ArrayRef&lt; int &gt; Mask, const Twine &amp;NameStr="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d8d34447ef4ce6cb316c55d6ce8ef5">operator new</a> (size_t S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af07ba6cf6b7fc44d6ecb0b886f715fdf">operator delete</a> (void *Ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa94c68d274d913e05b0423c7b2fded00">commute</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Swap the operands and adjust the mask to preserve the semantics of the instruction. <a href="#aa94c68d274d913e05b0423c7b2fded00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overload to return most specific vector type. <a href="#a59c34209e9206120edf7ce3c5da4f872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0a8852e7507c86e07adfa474e804ec">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transparently provide more efficient getOperand methods. <a href="#a4a0a8852e7507c86e07adfa474e804ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fb8619f70f51242f81ef96da349c884">getMaskValue</a> (unsigned Elt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the shuffle mask value of this instruction for the given element index. <a href="#a3fb8619f70f51242f81ef96da349c884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47e641200982b63efd797a4e6ad7bbec">getShuffleMask</a> (SmallVectorImpl&lt; int &gt; &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the mask for this instruction as a vector of integers. <a href="#a47e641200982b63efd797a4e6ad7bbec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a073aada7666dbe03e2479f4ffb35a208">getShuffleMaskForBitcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the mask for this instruction, for use in bitcode. <a href="#a073aada7666dbe03e2479f4ffb35a208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b4bd9eb06ac3de46c77590e83b78e6">setShuffleMask</a> (ArrayRef&lt; int &gt; Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20966136ad311c1a48b6d8d0bab597c0">getShuffleMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1552dc44fac81fb75a474feaa2ffdab8">changesLength</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle returns a vector with a different number of elements than its source vectors. <a href="#a1552dc44fac81fb75a474feaa2ffdab8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6315811e3cc527c8f1ab15ae0c789b93">increasesLength</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle returns a vector with a greater number of elements than its source vectors. <a href="#a6315811e3cc527c8f1ab15ae0c789b93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ac44360981522c11402c34998b3e46">isSingleSource</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle chooses elements from exactly one source vector without changing the length of that vector. <a href="#a09ac44360981522c11402c34998b3e46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace370e43170f9080834219e96dc1f8cc">isIdentity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle chooses elements from exactly one source vector without lane crossings and does not change the number of elements from its input vectors. <a href="#ace370e43170f9080834219e96dc1f8cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b5b3795e2c685987d722d9c01dc3e82">isIdentityWithPadding</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle lengthens exactly one source vector with undefs in the high elements. <a href="#a6b5b3795e2c685987d722d9c01dc3e82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a379276cb10c6cc61146d8a95cd1a7">isIdentityWithExtract</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle extracts the first N elements of exactly one source vector. <a href="#a64a379276cb10c6cc61146d8a95cd1a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76264693f8ce45cd18d13f105c69928b">isConcat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle concatenates its 2 source vectors. <a href="#a76264693f8ce45cd18d13f105c69928b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747673ac3ea44aadc3907c6b9fd86237">isSelect</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle chooses elements from its source vectors without lane crossings and all operands have the same number of elements. <a href="#a747673ac3ea44aadc3907c6b9fd86237">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb62cb742477203397c2927b5af3a9ce">isReverse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle swaps the order of elements from exactly one source vector. <a href="#afb62cb742477203397c2927b5af3a9ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a18df94e5261a66bf51f5cad16d0be">isZeroEltSplat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all elements of this shuffle are the same value as the first element of exactly one source vector without changing the length of that vector. <a href="#a67a18df94e5261a66bf51f5cad16d0be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a887138919e4980f08b8570ed05ccec28">isTranspose</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle transposes the elements of its inputs without changing the length of the vectors. <a href="#a887138919e4980f08b8570ed05ccec28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe32d39533eb1bfc413016b2b460514">isSplice</a> (int &amp;Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle splices two inputs without changing the length of the vectors. <a href="#aafe32d39533eb1bfc413016b2b460514">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a157632c803f214768bc5f6bf5e68434e">isExtractSubvectorMask</a> (int &amp;Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is an extract subvector mask. <a href="#a157632c803f214768bc5f6bf5e68434e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6216fec0e57bbfd308e943f3da488ebd">isInsertSubvectorMask</a> (int &amp;NumSubElts, int &amp;Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is an insert subvector mask. <a href="#a6216fec0e57bbfd308e943f3da488ebd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95bfea765a042b239f46ea9fdb91787b">isReplicationMask</a> (int &amp;ReplicationFactor, int &amp;VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is a replication mask. <a href="#a95bfea765a042b239f46ea9fdb91787b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf7ca65bff05f19664f7994a03f988e4">isOneUseSingleSourceMask</a> (int VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is a one-use-single-source("clustered") mask. <a href="#aaf7ca65bff05f19664f7994a03f988e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891d016891d8c8ba74acaf3f6fec2c95">isInterleave</a> (unsigned Factor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if this shuffle interleaves its two input vectors together. <a href="#a891d016891d8c8ba74acaf3f6fec2c95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a815ceab21b998b00b5f6d31a1e59cbf2">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5238562cf6d85d6a2e7a4b7e58b5246">ShuffleMask</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379580c84b4b9a6886b9bb921ba282f1">ShuffleMaskForBitcode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4679b8d3496374b0f0fead1b778f99a2">isValidOperands</a> (const Value *V1, const Value *V2, const Value *Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a shufflevector instruction can be formed with the specified operands. <a href="#a4679b8d3496374b0f0fead1b778f99a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5050f6aa93de9b9e43146d95909839aa">isValidOperands</a> (const Value *V1, const Value *V2, ArrayRef&lt; int &gt; Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a> (const Constant *Mask, SmallVectorImpl&lt; int &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the input shuffle mask operand to a vector of integers. <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06dcf793a8b91871327c682d6f3f909">convertShuffleMaskForBitcode</a> (ArrayRef&lt; int &gt; Mask, Type *ResultTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d733b742b1b15bd19fd115db8fd2edd">isSingleSourceMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask chooses elements from exactly one source vector. <a href="#a6d733b742b1b15bd19fd115db8fd2edd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f8a0b7c7f8867de71a57c0582bd3dbb">isSingleSourceMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81aa4ff7f63f7988abea1abbe9eb0342">isIdentityMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask chooses elements from exactly one source vector without lane crossings. <a href="#a81aa4ff7f63f7988abea1abbe9eb0342">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae15b4e9393ce1b6d1fab81543132e035">isIdentityMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a527e61685c56e6fab3cd424f74fa71ec">isSelectMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask chooses elements from its source vectors without lane crossings. <a href="#a527e61685c56e6fab3cd424f74fa71ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf745600e535e9ae260ea7d098d0dc0">isSelectMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c637c167eabe74ec4453abf2258eddb">isReverseMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask swaps the order of elements from exactly one source vector. <a href="#a8c637c167eabe74ec4453abf2258eddb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3115347ae052cfc9b0ea34f76200d65">isReverseMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b836340e75383742d06fd0ad2f23ff8">isZeroEltSplatMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask chooses all elements with the same value as the first element of exactly one source vector. <a href="#a0b836340e75383742d06fd0ad2f23ff8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac70c28f75ec58460e2219d92e7e3a710">isZeroEltSplatMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c89d6ee326837db1cf0876959acf9c8">isTransposeMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is a transpose mask. <a href="#a9c89d6ee326837db1cf0876959acf9c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6334dd1d66f3d23bc0d6f30c4eb104b">isTransposeMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2474ac30a61257b802cf6ba054e3ef45">isSpliceMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts, int &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is a splice mask, concatenating the two inputs together and then extracts an original width vector starting from the splice index. <a href="#a2474ac30a61257b802cf6ba054e3ef45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a830c30a9142f735c9391eaa6f73ad343">isSpliceMask</a> (const Constant *Mask, int NumSrcElts, int &amp;Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a841e0c83f3c14a1b0979d86a1812f335">isExtractSubvectorMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts, int &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is an extract subvector mask. <a href="#a841e0c83f3c14a1b0979d86a1812f335">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e079700a3d1f00808c64a7c1f68213">isExtractSubvectorMask</a> (const Constant *Mask, int NumSrcElts, int &amp;Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c981efb05d9ee219a85648972f71bd">isInsertSubvectorMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts, int &amp;NumSubElts, int &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is an insert subvector mask. <a href="#ab9c981efb05d9ee219a85648972f71bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c6afa142641800c019ad2561cfd8794">isInsertSubvectorMask</a> (const Constant *Mask, int NumSrcElts, int &amp;NumSubElts, int &amp;Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded1d376d952f6c163f1020aca8a7d67">isReplicationMask</a> (ArrayRef&lt; int &gt; Mask, int &amp;ReplicationFactor, int &amp;VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask replicates each of the <span class="doxyComputerOutput">VF</span> elements in a vector <span class="doxyComputerOutput">ReplicationFactor</span> times. <a href="#aded1d376d952f6c163f1020aca8a7d67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f7d111f8ca0f934f456a3deea46439">isReplicationMask</a> (const Constant *Mask, int &amp;ReplicationFactor, int &amp;VF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6659bba6a4be5e7102bdb10e5fc3658c">isOneUseSingleSourceMask</a> (ArrayRef&lt; int &gt; Mask, int VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask represents "clustered" mask of size VF, i.e. <a href="#a6659bba6a4be5e7102bdb10e5fc3658c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9874bec83353914ed1e9309d5d9ccea0">commuteShuffleMask</a> (MutableArrayRef&lt; int &gt; Mask, unsigned InVecNumElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change values in a shuffle permute mask assuming the two vector operands of length InVecNumElts have swapped position. <a href="#a9874bec83353914ed1e9309d5d9ccea0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9582c096b5d287b663ec8ca4550aa72">isInterleaveMask</a> (ArrayRef&lt; int &gt; Mask, unsigned Factor, unsigned NumInputElts, SmallVectorImpl&lt; unsigned &gt; &amp;StartIndexes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the mask interleaves one or more input vectors together. <a href="#af9582c096b5d287b663ec8ca4550aa72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b39c7a51bfbf99d375d3790b73be25">isInterleaveMask</a> (ArrayRef&lt; int &gt; Mask, unsigned Factor, unsigned NumInputElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f15b97df1c138940047d9442b02b13b">isDeInterleaveMaskOfFactor</a> (ArrayRef&lt; int &gt; Mask, unsigned Factor, unsigned &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the mask is a DE-interleave mask of the given factor <span class="doxyComputerOutput">Factor</span> like: &lt;Index, Index+Factor, ..., Index+(NumElts-1)*Factor&gt; <a href="#a7f15b97df1c138940047d9442b02b13b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3962571b9194355e1d23a3f837aa43">isDeInterleaveMaskOfFactor</a> (ArrayRef&lt; int &gt; Mask, unsigned Factor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f0b0ca5ff870c4dca191f5133dbb60">isBitRotateMask</a> (ArrayRef&lt; int &gt; Mask, unsigned EltSizeInBits, unsigned MinSubElts, unsigned MaxSubElts, unsigned &amp;NumSubElts, unsigned &amp;RotateAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the shuffle is a bit rotation of the first operand across multiple subelements, e.g: <a href="#a54f0b0ca5ff870c4dca191f5133dbb60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44dc02e477528c1bd58d1167266290b">classof</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a026b9ddc0ddd046e1dc7961cb282c">classof</a> (const Value *V)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsallocmarker">IntrusiveOperandsAllocMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d81af4342860f2fffc1350201fbdefc">AllocMarker</a> {2}</td>
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

<p>This instruction constructs a fixed permutation of two input vectors.</p>


<p>For each element of the result vector, the shuffle mask selects an element from one of the input vectors to copy to the result. Non-negative elements in the mask represent an index into the concatenated pair of input vectors. PoisonMaskElem (-1) specifies that the result element is poison.</p>


<p>For scalable vectors, all the elements of the mask must be 0 or -1. This requirement may be relaxed in the future.</p>


<p>Definition at line 1901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Instruction {#a87273cb892a8182f137567e6b631695e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
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


<p>Definition at line 1909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a815ceab21b998b00b5f6d31a1e59cbf2">cloneImpl</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a> and <a href="#a46141ae6646785e46d48cae9f1011511">ShuffleVectorInst</a>.</p>


<p>Referenced by <a href="#ac44dc02e477528c1bd58d1167266290b">classof</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="#a50ca93f9d04de6b4256cdfdb677611ed">ShuffleVectorInst</a> and <a href="#a9550ae3e26eaa39468d80a6940709b5c">ShuffleVectorInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ShuffleVectorInst() {#a46141ae6646785e46d48cae9f1011511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShuffleVectorInst::ShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1656 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a2c53fab823052ea1278853d24a9d2731">createPlaceholderForShuffleVector</a> and <a href="#a46141ae6646785e46d48cae9f1011511">ShuffleVectorInst</a>.</p>


<p>Referenced by <a href="#a815ceab21b998b00b5f6d31a1e59cbf2">cloneImpl</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="#a9ef22019a6b173a2b6699d5bfccd19d3">ShuffleVectorInst</a> and <a href="#a46141ae6646785e46d48cae9f1011511">ShuffleVectorInst</a>.</p>

</div>
</div>

### ShuffleVectorInst() {#a9ef22019a6b173a2b6699d5bfccd19d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShuffleVectorInst::ShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1661 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a2c53fab823052ea1278853d24a9d2731">createPlaceholderForShuffleVector</a> and <a href="#a46141ae6646785e46d48cae9f1011511">ShuffleVectorInst</a>.</p>

</div>
</div>

### ShuffleVectorInst() {#a9550ae3e26eaa39468d80a6940709b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShuffleVectorInst::ShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1667 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a20966136ad311c1a48b6d8d0bab597c0">getShuffleMask</a>, <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="#a4679b8d3496374b0f0fead1b778f99a2">isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a> and <a href="#a85b4bd9eb06ac3de46c77590e83b78e6">setShuffleMask</a>.</p>

</div>
</div>

### ShuffleVectorInst() {#a50ca93f9d04de6b4256cdfdb677611ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShuffleVectorInst::ShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1685 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a4679b8d3496374b0f0fead1b778f99a2">isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="#a85b4bd9eb06ac3de46c77590e83b78e6">setShuffleMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#af07ba6cf6b7fc44d6ecb0b886f715fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ShuffleVectorInst::operator delete (void * Ptr)</td>
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



<p>Definition at line 1926 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### operator new() {#ac2d8d34447ef4ce6cb316c55d6ce8ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::ShuffleVectorInst::operator new (size_t S)</td>
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



<p>Definition at line 1925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changesLength() {#a1552dc44fac81fb75a474feaa2ffdab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::changesLength ()</td>
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

<p>Return true if this shuffle returns a vector with a different number of elements than its source vectors.</p>


<p>Examples: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;1,2,3&gt; shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;1,2,3,4,5&gt;</p>


<p>Definition at line 1980 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a747cca8cf8e4c4e41b81bb1cbf146a11">foldTruncShuffle</a>, <a href="#ace370e43170f9080834219e96dc1f8cc">isIdentity</a>, <a href="#afb62cb742477203397c2927b5af3a9ce">isReverse</a>, <a href="#a747673ac3ea44aadc3907c6b9fd86237">isSelect</a>, <a href="#a09ac44360981522c11402c34998b3e46">isSingleSource</a>, <a href="#aafe32d39533eb1bfc413016b2b460514">isSplice</a>, <a href="#a887138919e4980f08b8570ed05ccec28">isTranspose</a> and <a href="#a67a18df94e5261a66bf51f5cad16d0be">isZeroEltSplat</a>.</p>

</div>
</div>

### commute() {#aa94c68d274d913e05b0423c7b2fded00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ShuffleVectorInst::commute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Swap the operands and adjust the mask to preserve the semantics of the instruction.</p>

<p>Declaration at line 1930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1700 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a3fb8619f70f51242f81ef96da349c884">getMaskValue</a>, <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a> and <a href="#a85b4bd9eb06ac3de46c77590e83b78e6">setShuffleMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>.</p>

</div>
</div>

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a4a0a8852e7507c86e07adfa474e804ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ShuffleVectorInst::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transparently provide more efficient getOperand methods.</p>

<p>Definition at line 1946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### getMaskValue() {#a3fb8619f70f51242f81ef96da349c884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ShuffleVectorInst::getMaskValue (unsigned Elt)</td>
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

<p>Return the shuffle mask value of this instruction for the given element index.</p>


<p>Return PoisonMaskElem if the element is undef.</p>


<p>Definition at line 1950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="#aa94c68d274d913e05b0423c7b2fded00">commute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aa5aa7648807905cd7b63153812029fe2">findDemandedEltsBySingleUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab09fc7dee4f7e02c60f7a9c928dc1603">llvm::findScalarElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a42c33c78c903c369b359db824b70cb1b">foldIdentityExtractShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ace7029cdad3163ebfb8172d25e8a59e3">isShuffleEquivalentToSelect</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a22ba91d5d49420a24b01342672953762">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitShuffleVectorInst</a>.</p>

</div>
</div>

### getShuffleMask() {#a47e641200982b63efd797a4e6ad7bbec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ShuffleVectorInst::getShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Result)</td>
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

<p>Return the mask for this instruction as a vector of integers.</p>


<p>Undefined elements of the mask are returned as PoisonMaskElem.</p>


<p>Definition at line 1959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### getShuffleMask() {#a20966136ad311c1a48b6d8d0bab597c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; int &gt; llvm::ShuffleVectorInst::getShuffleMask ()</td>
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



<p>Definition at line 1974 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="#a815ceab21b998b00b5f6d31a1e59cbf2">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#ab200dfd5c34c21db06ff2139e68debc8">llvm::sandboxir::ShuffleVectorInst::getShuffleMask</a>, <a href="#a76264693f8ce45cd18d13f105c69928b">isConcat</a>, <a href="#a64a379276cb10c6cc61146d8a95cd1a7">isIdentityWithExtract</a>, <a href="#a6b5b3795e2c685987d722d9c01dc3e82">isIdentityWithPadding</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantexpressions/#gaf38b98a39df49182ae2937d0db681ce3">LLVMConstShuffleVector</a>, <a href="#a9550ae3e26eaa39468d80a6940709b5c">ShuffleVectorInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>.</p>

</div>
</div>

### getShuffleMaskForBitcode() {#a073aada7666dbe03e2479f4ffb35a208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::ShuffleVectorInst::getShuffleMaskForBitcode ()</td>
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

<p>Return the mask for this instruction, for use in bitcode.</p>


<p>TODO: This is temporary until we decide a new bitcode encoding for shufflevector.</p>


<p>Definition at line 1967 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### getType() {#a59c34209e9206120edf7ce3c5da4f872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::ShuffleVectorInst::getType ()</td>
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

<p>Overload to return most specific vector type.</p>

<p>Definition at line 1941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a6e6cf92e2cfe0eb48abec55606e0481e">canonicalizeInsertSplat</a>, <a href="#aa94c68d274d913e05b0423c7b2fded00">commute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab09fc7dee4f7e02c60f7a9c928dc1603">llvm::findScalarElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ab737e320d75547e2b43f6044fc3f3bcc">foldCastShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a42c33c78c903c369b359db824b70cb1b">foldIdentityExtractShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a332e7f93c5c4782c1a628a1b11ab5032">foldIdentityPaddedShuffles</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aabcb01976dc50b78faed7491a6d43042">foldShuffleOfUnaryOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a747cca8cf8e4c4e41b81bb1cbf146a11">foldTruncShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0096a88b01feba943407155e0b6a1e77">getShuffleDemandedElts</a>, <a href="#a76264693f8ce45cd18d13f105c69928b">isConcat</a>, <a href="#a64a379276cb10c6cc61146d8a95cd1a7">isIdentityWithExtract</a>, <a href="#a6b5b3795e2c685987d722d9c01dc3e82">isIdentityWithPadding</a>, <a href="#a891d016891d8c8ba74acaf3f6fec2c95">isInterleave</a>, <a href="#aaf7ca65bff05f19664f7994a03f988e4">isOneUseSingleSourceMask</a>, <a href="#a95bfea765a042b239f46ea9fdb91787b">isReplicationMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa3168bc53fc117710cec207cc6f60518">llvm::ARMTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab5881269962ffb5a6c2d4c5be45efbce">llvm::X86TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a746205e6d7f5c0bb265ecc8a911d5b82">narrowVectorSelect</a>, <a href="#a85b4bd9eb06ac3de46c77590e83b78e6">setShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab32574e30e8d85eaa2f692d8fc3c6766">llvm::ARMTargetLowering::shouldConvertSplatType</a>, <a href="#a50ca93f9d04de6b4256cdfdb677611ed">ShuffleVectorInst</a>, <a href="#a9550ae3e26eaa39468d80a6940709b5c">ShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a22ba91d5d49420a24b01342672953762">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitShuffleVectorInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>.</p>

</div>
</div>

### increasesLength() {#a6315811e3cc527c8f1ab15ae0c789b93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::increasesLength ()</td>
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

<p>Return true if this shuffle returns a vector with a greater number of elements than its source vectors.</p>


<p>Example: shufflevector &lt;2 x n&gt; A, &lt;2 x n&gt; B, &lt;1,2,3&gt;</p>


<p>Definition at line 1991 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a747cca8cf8e4c4e41b81bb1cbf146a11">foldTruncShuffle</a>.</p>

</div>
</div>

### isConcat() {#a76264693f8ce45cd18d13f105c69928b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isConcat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this shuffle concatenates its 2 source vectors.</p>


<p>This returns false if either input is undefined. In that case, the shuffle is is better classified as an identity with padding operation.</p>


<p>Declaration at line 2064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2150 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a20966136ad311c1a48b6d8d0bab597c0">getShuffleMask</a>, <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a9cfb895613ec4f3993f77dfcf0d2bfa8">isIdentityMaskImpl</a>.</p>

</div>
</div>

### isExtractSubvectorMask() {#a157632c803f214768bc5f6bf5e68434e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isExtractSubvectorMask (int &amp; Index)</td>
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

<p>Return true if this shuffle mask is an extract subvector mask.</p>

<p>Definition at line 2229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a841e0c83f3c14a1b0979d86a1812f335">isExtractSubvectorMask</a>.</p>

</div>
</div>

### isIdentity() {#ace370e43170f9080834219e96dc1f8cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isIdentity ()</td>
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

<p>Return true if this shuffle chooses elements from exactly one source vector without lane crossings and does not change the number of elements from its input vectors.</p>


<p>Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;4,undef,6,undef&gt;</p>


<p>Definition at line 2044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a1552dc44fac81fb75a474feaa2ffdab8">changesLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a81aa4ff7f63f7988abea1abbe9eb0342">isIdentityMask</a>.</p>

</div>
</div>

### isIdentityWithExtract() {#a64a379276cb10c6cc61146d8a95cd1a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isIdentityWithExtract ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this shuffle extracts the first N elements of exactly one source vector.</p>

<p>Declaration at line 2059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2136 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a20966136ad311c1a48b6d8d0bab597c0">getShuffleMask</a>, <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a9cfb895613ec4f3993f77dfcf0d2bfa8">isIdentityMaskImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a42c33c78c903c369b359db824b70cb1b">foldIdentityExtractShuffle</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a746205e6d7f5c0bb265ecc8a911d5b82">narrowVectorSelect</a>.</p>

</div>
</div>

### isIdentityWithPadding() {#a6b5b3795e2c685987d722d9c01dc3e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isIdentityWithPadding ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this shuffle lengthens exactly one source vector with undefs in the high elements.</p>

<p>Declaration at line 2055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2112 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a20966136ad311c1a48b6d8d0bab597c0">getShuffleMask</a>, <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a9cfb895613ec4f3993f77dfcf0d2bfa8">isIdentityMaskImpl</a>.</p>

</div>
</div>

### isInsertSubvectorMask() {#a6216fec0e57bbfd308e943f3da488ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isInsertSubvectorMask (int &amp; NumSubElts, int &amp; Index)</td>
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

<p>Return true if this shuffle mask is an insert subvector mask.</p>

<p>Definition at line 2259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#ab9c981efb05d9ee219a85648972f71bd">isInsertSubvectorMask</a>.</p>

</div>
</div>

### isInterleave() {#a891d016891d8c8ba74acaf3f6fec2c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isInterleave (unsigned Factor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return if this shuffle interleaves its two input vectors together.</p>

<p>Declaration at line 2320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2284 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a> and <a href="#af9582c096b5d287b663ec8ca4550aa72">isInterleaveMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#aa5abbc18f35b5384a55bfd244064493d">isReInterleaveMask</a>.</p>

</div>
</div>

### isOneUseSingleSourceMask() {#aaf7ca65bff05f19664f7994a03f988e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isOneUseSingleSourceMask (int VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this shuffle mask is a one-use-single-source("clustered") mask.</p>


<p>Return true if this shuffle mask is a replication mask.</p>


<p>Declaration at line 2304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2273 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a6659bba6a4be5e7102bdb10e5fc3658c">isOneUseSingleSourceMask</a> and <a href="#a6d733b742b1b15bd19fd115db8fd2edd">isSingleSourceMask</a>.</p>

</div>
</div>

### isReplicationMask() {#a95bfea765a042b239f46ea9fdb91787b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isReplicationMask (int &amp; ReplicationFactor, int &amp; VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this shuffle mask is a replication mask.</p>

<p>Declaration at line 2289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2238 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a95644d0b13092f37423d18945ec0f5be">isReplicationMaskWithParams</a>.</p>

</div>
</div>

### isReverse() {#afb62cb742477203397c2927b5af3a9ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isReverse ()</td>
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

<p>Return true if this shuffle swaps the order of elements from exactly one source vector.</p>


<p>Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;3,undef,1,undef&gt; TODO: Optionally allow length-changing shuffles.</p>


<p>Definition at line 2111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a1552dc44fac81fb75a474feaa2ffdab8">changesLength</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2b8fb99a1e250aac47d7fc77425edc8e">isReverseMask</a>.</p>

</div>
</div>

### isSelect() {#a747673ac3ea44aadc3907c6b9fd86237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isSelect ()</td>
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

<p>Return true if this shuffle chooses elements from its source vectors without lane crossings and all operands have the same number of elements.</p>


<p>In other words, this shuffle is equivalent to a vector select with a constant condition operand. Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;undef,1,6,3&gt; This returns false if the mask does not choose from both input vectors. In that case, the shuffle is better classified as an identity shuffle. TODO: Optionally allow length-changing shuffles.</p>


<p>Definition at line 2090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a1552dc44fac81fb75a474feaa2ffdab8">changesLength</a> and <a href="#a527e61685c56e6fab3cd424f74fa71ec">isSelectMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a98282716af42c878d4638603c6efb350">foldSelectShuffleOfSelectShuffle</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>.</p>

</div>
</div>

### isSingleSource() {#a09ac44360981522c11402c34998b3e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isSingleSource ()</td>
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

<p>Return true if this shuffle chooses elements from exactly one source vector without changing the length of that vector.</p>


<p>Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;3,0,undef,3&gt; TODO: Optionally allow length-changing shuffles.</p>


<p>Definition at line 2016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a1552dc44fac81fb75a474feaa2ffdab8">changesLength</a> and <a href="#a6d733b742b1b15bd19fd115db8fd2edd">isSingleSourceMask</a>.</p>

</div>
</div>

### isSplice() {#aafe32d39533eb1bfc413016b2b460514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isSplice (int &amp; Index)</td>
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

<p>Return true if this shuffle splices two inputs without changing the length of the vectors.</p>


<p>This operation concatenates the two inputs together and then extracts an original width vector starting from the splice index. Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;1,2,3,4&gt;</p>


<p>Definition at line 2206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a1552dc44fac81fb75a474feaa2ffdab8">changesLength</a> and <a href="#a2474ac30a61257b802cf6ba054e3ef45">isSpliceMask</a>.</p>

</div>
</div>

### isTranspose() {#a887138919e4980f08b8570ed05ccec28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isTranspose ()</td>
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

<p>Return true if this shuffle transposes the elements of its inputs without changing the length of the vectors.</p>


<p>This operation may also be known as a merge or interleave. See the description for <a href="#a9c89d6ee326837db1cf0876959acf9c8">isTransposeMask()</a> for the exact specification. Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;0,4,2,6&gt;</p>


<p>Definition at line 2184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a1552dc44fac81fb75a474feaa2ffdab8">changesLength</a> and <a href="#a9c89d6ee326837db1cf0876959acf9c8">isTransposeMask</a>.</p>

</div>
</div>

### isZeroEltSplat() {#a67a18df94e5261a66bf51f5cad16d0be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isZeroEltSplat ()</td>
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

<p>Return true if all elements of this shuffle are the same value as the first element of exactly one source vector without changing the length of that vector.</p>


<p>Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;undef,0,undef,0&gt; TODO: Optionally allow length-changing shuffles. TODO: Optionally allow splats from other elements.</p>


<p>Definition at line 2134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a1552dc44fac81fb75a474feaa2ffdab8">changesLength</a> and <a href="#a0b836340e75383742d06fd0ad2f23ff8">isZeroEltSplatMask</a>.</p>

</div>
</div>

### setShuffleMask() {#a85b4bd9eb06ac3de46c77590e83b78e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ShuffleVectorInst::setShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1972 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1822 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#ad06dcf793a8b91871327c682d6f3f909">convertShuffleMaskForBitcode</a> and <a href="#a59c34209e9206120edf7ce3c5da4f872">getType</a>.</p>


<p>Referenced by <a href="#aa94c68d274d913e05b0423c7b2fded00">commute</a>, <a href="#a50ca93f9d04de6b4256cdfdb677611ed">ShuffleVectorInst</a> and <a href="#a9550ae3e26eaa39468d80a6940709b5c">ShuffleVectorInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#a815ceab21b998b00b5f6d31a1e59cbf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShuffleVectorInst * ShuffleVectorInst::cloneImpl ()</td>
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



<p>Declaration at line 1911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4406 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a20966136ad311c1a48b6d8d0bab597c0">getShuffleMask</a> and <a href="#a46141ae6646785e46d48cae9f1011511">ShuffleVectorInst</a>.</p>


<p>Referenced by <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ShuffleMask {#ad5238562cf6d85d6a2e7a4b7e58b5246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int, 4&gt; llvm::ShuffleVectorInst::ShuffleMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### ShuffleMaskForBitcode {#a379580c84b4b9a6886b9bb921ba282f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* llvm::ShuffleVectorInst::ShuffleMaskForBitcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ac44dc02e477528c1bd58d1167266290b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 2376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a01a026b9ddc0ddd046e1dc7961cb282c">classof</a>.</p>

</div>
</div>

### classof() {#a01a026b9ddc0ddd046e1dc7961cb282c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 2379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac44dc02e477528c1bd58d1167266290b">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### commuteShuffleMask() {#a9874bec83353914ed1e9309d5d9ccea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ShuffleVectorInst::commuteShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; int &gt; Mask, unsigned InVecNumElts)</td>
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

<p>Change values in a shuffle permute mask assuming the two vector operands of length InVecNumElts have swapped position.</p>

<p>Definition at line 2308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a9038a51df4c44345a12abb05ab057a73">llvm::sandboxir::ShuffleVectorInst::commuteShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a98282716af42c878d4638603c6efb350">foldSelectShuffleOfSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a661440047dc1b2af077911d9cf92236a">foldShuffleWithInsert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0bf04415ab72b83b24140635c6a7ea52">simplifyShuffleVectorInst</a>.</p>

</div>
</div>

### convertShuffleMaskForBitcode() {#ad06dcf793a8b91871327c682d6f3f909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ShuffleVectorInst::convertShuffleMaskForBitcode (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultTy)</td>
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



<p>Declaration at line 1969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1827 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad78da75bd1f157e72100f97d1ecdc756">llvm::all_equal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a6224f807d740562c873c036926d0dfd9">llvm::sandboxir::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="#a85b4bd9eb06ac3de46c77590e83b78e6">setShuffleMask</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorconstantexpr/#a9a1de10288271bcf0f869d8121f8525a">llvm::ShuffleVectorConstantExpr::ShuffleVectorConstantExpr</a>.</p>

</div>
</div>

### getShuffleMask() {#a6eaff12d0d3ead952f2a2a2781df56ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ShuffleVectorInst::getShuffleMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Result)</td>
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

<p>Convert the input shuffle mask operand to a vector of integers.</p>


<p>Undefined elements of the mask are returned as PoisonMaskElem.</p>


<p>Declaration at line 1954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1788 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a6e6cf92e2cfe0eb48abec55606e0481e">canonicalizeInsertSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ab737e320d75547e2b43f6044fc3f3bcc">foldCastShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a332e7f93c5c4782c1a628a1b11ab5032">foldIdentityPaddedShuffles</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a98282716af42c878d4638603c6efb350">foldSelectShuffleOfSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aabcb01976dc50b78faed7491a6d43042">foldShuffleOfUnaryOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a661440047dc1b2af077911d9cf92236a">foldShuffleWithInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a747cca8cf8e4c4e41b81bb1cbf146a11">foldTruncShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0096a88b01feba943407155e0b6a1e77">getShuffleDemandedElts</a>, <a href="#a67e079700a3d1f00808c64a7c1f68213">isExtractSubvectorMask</a>, <a href="#ae15b4e9393ce1b6d1fab81543132e035">isIdentityMask</a>, <a href="#a2c6afa142641800c019ad2561cfd8794">isInsertSubvectorMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#aa5abbc18f35b5384a55bfd244064493d">isReInterleaveMask</a>, <a href="#ad8f7d111f8ca0f934f456a3deea46439">isReplicationMask</a>, <a href="#ab3115347ae052cfc9b0ea34f76200d65">isReverseMask</a>, <a href="#abdf745600e535e9ae260ea7d098d0dc0">isSelectMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ace7029cdad3163ebfb8172d25e8a59e3">isShuffleEquivalentToSelect</a>, <a href="#a2f8a0b7c7f8867de71a57c0582bd3dbb">isSingleSourceMask</a>, <a href="#a830c30a9142f735c9391eaa6f73ad343">isSpliceMask</a>, <a href="#af6334dd1d66f3d23bc0d6f30c4eb104b">isTransposeMask</a>, <a href="#ac70c28f75ec58460e2219d92e7e3a710">isZeroEltSplatMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa3168bc53fc117710cec207cc6f60518">llvm::ARMTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab5881269962ffb5a6c2d4c5be45efbce">llvm::X86TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a746205e6d7f5c0bb265ecc8a911d5b82">narrowVectorSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab18666f9305cc63df7009c9e4ec0e35a">llvm::InstCombinerImpl::simplifyBinOpSplats</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>.</p>

</div>
</div>

### isBitRotateMask() {#a54f0b0ca5ff870c4dca191f5133dbb60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isBitRotateMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned EltSizeInBits, unsigned MinSubElts, unsigned MaxSubElts, unsigned &amp; NumSubElts, unsigned &amp; RotateAmt)</td>
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

<p>Checks if the shuffle is a bit rotation of the first operand across multiple subelements, e.g:</p>


<p>shuffle &lt;8 x i8&gt; a, &lt;8 x i8&gt; poison, &lt;8 x i32&gt; &lt;1, 0, 3, 2, 5, 4, 7, 6&gt;</p>


<p>could be expressed as</p>


<p>rotl &lt;4 x i16&gt; a, 8</p>


<p>If it can be expressed as a rotation, returns the number of subelements to group by in NumSubElts and the number of bits to rotate left in RotateAmt.</p>


<p>Declaration at line 2371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2426 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a7b7c3e256f4f2912c037bd65b585cf4c">matchShuffleAsBitRotate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a7692cb204bee86bea3cb7f41a580347b">llvm::sandboxir::ShuffleVectorInst::isBitRotateMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3e9938aeee2aaef4ca5933920bb8c2af">isLegalBitRotate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a82d33c0896d1afa7242d2984185d7432">matchShuffleAsBitRotate</a>.</p>

</div>
</div>

### isDeInterleaveMaskOfFactor() {#a7f15b97df1c138940047d9442b02b13b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isDeInterleaveMaskOfFactor (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned Factor, unsigned &amp; Index)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the mask is a DE-interleave mask of the given factor <span class="doxyComputerOutput">Factor</span> like: &lt;Index, Index+Factor, ..., Index+(NumElts-1)*Factor&gt;</p>

<p>Declaration at line 2353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2379 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#a1197fc4e7554381767b15551de4f9334">isDeInterleaveMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a5295662c5a712596dd4f5ca1dd4a5154">llvm::sandboxir::ShuffleVectorInst::isDeInterleaveMaskOfFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#acc2195bf46bca7dd5464dd3580e4449d">llvm::sandboxir::ShuffleVectorInst::isDeInterleaveMaskOfFactor</a>, <a href="#a4c3962571b9194355e1d23a3f837aa43">isDeInterleaveMaskOfFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a036a964199eef5a0aab70732233b5e8d">performZExtDeinterleaveShuffleCombine</a>.</p>

</div>
</div>

### isDeInterleaveMaskOfFactor() {#a4c3962571b9194355e1d23a3f837aa43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isDeInterleaveMaskOfFactor (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned Factor)</td>
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



<p>Definition at line 2355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="#a7f15b97df1c138940047d9442b02b13b">isDeInterleaveMaskOfFactor</a>.</p>

</div>
</div>

### isExtractSubvectorMask() {#a841e0c83f3c14a1b0979d86a1812f335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isExtractSubvectorMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts, int &amp; Index)</td>
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

<p>Return true if this shuffle mask is an extract subvector mask.</p>


<p>A valid extract subvector mask returns a smaller vector from a single source operand. The base extraction index is returned as well.</p>


<p>Declaration at line 2214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2010 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#ab0c1a9d7c52853132262e899091d74d7">isSingleSourceMaskImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#af57aa964441f0796b3d49de878edaca5">areExtractShuffleVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a43d9b7161f7ae393a165599ca211fe2f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::improveShuffleKindFromMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a6376f131f9732efa3b04f6007d7a7e4a">llvm::sandboxir::ShuffleVectorInst::isExtractSubvectorMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a1ad3a22eb16aa72a2d2a4d8b7db77463">llvm::sandboxir::ShuffleVectorInst::isExtractSubvectorMask</a>, <a href="#a67e079700a3d1f00808c64a7c1f68213">isExtractSubvectorMask</a>, <a href="#a157632c803f214768bc5f6bf5e68434e">isExtractSubvectorMask</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a7c6c1a7f00536e9ea11d05420bda55cd">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::isIdentityMask</a>.</p>

</div>
</div>

### isExtractSubvectorMask() {#a67e079700a3d1f00808c64a7c1f68213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isExtractSubvectorMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int NumSrcElts, int &amp; Index)</td>
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



<p>Definition at line 2216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a841e0c83f3c14a1b0979d86a1812f335">isExtractSubvectorMask</a>.</p>

</div>
</div>

### isIdentityMask() {#a81aa4ff7f63f7988abea1abbe9eb0342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isIdentityMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask chooses elements from exactly one source vector without lane crossings.</p>


<p>A shuffle using this mask is not necessarily a no-op because it may change the number of elements from its input vectors or it may provide demanded bits knowledge via undef lanes. Example: &lt;undef,undef,2,3&gt;</p>


<p>Declaration at line 2026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1883 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a9cfb895613ec4f3993f77dfcf0d2bfa8">isIdentityMaskImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a65dff372171f9d4e3e07a272214fb94d">foldExtractSubvectorFromShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a98282716af42c878d4638603c6efb350">foldSelectShuffleOfSelectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="#ace370e43170f9080834219e96dc1f8cc">isIdentity</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a7c6c1a7f00536e9ea11d05420bda55cd">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::isIdentityMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a12ffa0b5875610369046b023b0e3b7ca">llvm::sandboxir::ShuffleVectorInst::isIdentityMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a50a5d48ed7d2f1d8ebba3d092afab021">llvm::sandboxir::ShuffleVectorInst::isIdentityMask</a>, <a href="#ae15b4e9393ce1b6d1fab81543132e035">isIdentityMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0feeaece30961860a542ba8ee2a1f9f3">isRepeatedNonIdentityClusteredMask</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a779e5a75f5bf9f3672698656b56663fc">llvm::ARMTargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a633db91afb11db086004de9e3eb37217">reorderOrder</a>.</p>

</div>
</div>

### isIdentityMask() {#ae15b4e9393ce1b6d1fab81543132e035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isIdentityMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 2027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a81aa4ff7f63f7988abea1abbe9eb0342">isIdentityMask</a>.</p>

</div>
</div>

### isInsertSubvectorMask() {#ab9c981efb05d9ee219a85648972f71bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isInsertSubvectorMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts, int &amp; NumSubElts, int &amp; Index)</td>
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

<p>Return true if this shuffle mask is an insert subvector mask.</p>


<p>A valid insert subvector mask inserts the lowest elements of a second source operand into an in-place first source operand. Both the sub vector width and the insertion index is returned.</p>


<p>Declaration at line 2244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2039 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8bad27827f46bca6baf814cbd2b64e84">llvm::APInt::countl_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a9cfb895613ec4f3993f77dfcf0d2bfa8">isIdentityMaskImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#ab0c1a9d7c52853132262e899091d74d7">isSingleSourceMaskImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a33f9f862dca8ee0f23bff5941bf433d8">llvm::APInt::setBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a43d9b7161f7ae393a165599ca211fe2f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::improveShuffleKindFromMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#aaac6402d988a5e91be8fed57216a6809">llvm::sandboxir::ShuffleVectorInst::isInsertSubvectorMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a82e490d4b7fe9b12f07733db1d8ab677">llvm::sandboxir::ShuffleVectorInst::isInsertSubvectorMask</a>, <a href="#a2c6afa142641800c019ad2561cfd8794">isInsertSubvectorMask</a>, <a href="#a6216fec0e57bbfd308e943f3da488ebd">isInsertSubvectorMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#add5b44a9fa06b625d7242da3a08957e8">lowerVECTOR_SHUFFLEAsVSlideup</a>.</p>

</div>
</div>

### isInsertSubvectorMask() {#a2c6afa142641800c019ad2561cfd8794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isInsertSubvectorMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int NumSrcElts, int &amp; NumSubElts, int &amp; Index)</td>
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



<p>Definition at line 2246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#ab9c981efb05d9ee219a85648972f71bd">isInsertSubvectorMask</a>.</p>

</div>
</div>

### isInterleaveMask() {#af9582c096b5d287b663ec8ca4550aa72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isInterleaveMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned Factor, unsigned NumInputElts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; StartIndexes)</td>
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

<p>Return true if the mask interleaves one or more input vectors together.</p>


<p>I.e. &lt;0, LaneLen, ... , LaneLen*(Factor - 1), 1, LaneLen + 1, ...&gt; E.g. For a Factor of 2 (LaneLen=4): &lt;0, 4, 1, 5, 2, 6, 3, 7&gt; E.g. For a Factor of 3 (LaneLen=4): &lt;4, 0, 9, 5, 1, 10, 6, 2, 11, 7, 3, 12&gt; E.g. For a Factor of 4 (LaneLen=2): &lt;0, 2, 6, 4, 1, 3, 7, 5&gt;</p>


<p>NumInputElts is the total number of elements in the input vectors.</p>


<p>StartIndexes are the first indexes of each vector being interleaved, substituting any indexes that were undef E.g. &lt;4, -1, 2, 5, 1, 3&gt; (Factor=3): StartIndexes=&lt;4, 0, 2&gt;</p>


<p>Note that this does not check if the input vectors are consecutive: It will return true for masks such as &lt;0, 4, 6, 1, 5, 7&gt; (Factor=3, LaneLen=2)</p>


<p>Declaration at line 2341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2295 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="#a891d016891d8c8ba74acaf3f6fec2c95">isInterleave</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a3c1ba6001c24f47b2a45280d830d2bab">llvm::sandboxir::ShuffleVectorInst::isInterleaveMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a1befcfac778c8aaa7cab09de808cbcb7">llvm::sandboxir::ShuffleVectorInst::isInterleaveMask</a>, <a href="#a03b39c7a51bfbf99d375d3790b73be25">isInterleaveMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b77bb8d8bdd5dbaaf125f1afbd96ebd">isInterleaveShuffle</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>.</p>

</div>
</div>

### isInterleaveMask() {#a03b39c7a51bfbf99d375d3790b73be25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isInterleaveMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned Factor, unsigned NumInputElts)</td>
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



<p>Definition at line 2344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="#af9582c096b5d287b663ec8ca4550aa72">isInterleaveMask</a>.</p>

</div>
</div>

### isOneUseSingleSourceMask() {#a6659bba6a4be5e7102bdb10e5fc3658c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isOneUseSingleSourceMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int VF)</td>
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

<p>Return true if this shuffle mask represents "clustered" mask of size VF, i.e.</p>


<p>each index between [0..VF) is used exactly once in each submask of size VF. For example, the mask for <span class="doxyComputerOutput">VF=4</span> is: 0, 1, 2, 3, 3, 2, 0, 1 - "clustered", because each submask of size 4 (0,1,2,3 and 3,2,0,1) uses indices [0..VF) exactly one time. 0, 1, 2, 3, 3, 3, 1, 0 - not "clustered", because element 3 is used twice in the second submask (3,3,1,0) and index 2 is not used at all.</p>


<p>Declaration at line 2300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2253 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a252c430f2d2ac65ad395418c6e4bf924">llvm::sandboxir::ShuffleVectorInst::isOneUseSingleSourceMask</a> and <a href="#aaf7ca65bff05f19664f7994a03f988e4">isOneUseSingleSourceMask</a>.</p>

</div>
</div>

### isReplicationMask() {#aded1d376d952f6c163f1020aca8a7d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isReplicationMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int &amp; ReplicationFactor, int &amp; VF)</td>
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

<p>Return true if this shuffle mask replicates each of the <span class="doxyComputerOutput">VF</span> elements in a vector <span class="doxyComputerOutput">ReplicationFactor</span> times.</p>


<p>For example, the mask for <span class="doxyComputerOutput">ReplicationFactor=3</span> and <span class="doxyComputerOutput">VF=4</span> is: &lt;0,0,0,1,1,1,2,2,2,3,3,3&gt;</p>


<p>Declaration at line 2274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 2192 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a95644d0b13092f37423d18945ec0f5be">isReplicationMaskWithParams</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c2ddf6dc4989447e45dca1bbbe8fc68">llvm::seq_inclusive</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a4392650bdea712205171ab9a5eb11990">llvm::sandboxir::ShuffleVectorInst::isReplicationMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a4f791365d06f0905613d0ac07e265c45">llvm::sandboxir::ShuffleVectorInst::isReplicationMask</a> and <a href="#ad8f7d111f8ca0f934f456a3deea46439">isReplicationMask</a>.</p>

</div>
</div>

### isReplicationMask() {#ad8f7d111f8ca0f934f456a3deea46439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isReplicationMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int &amp; ReplicationFactor, int &amp; VF)</td>
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



<p>Definition at line 2276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#aded1d376d952f6c163f1020aca8a7d67">isReplicationMask</a>.</p>

</div>
</div>

### isReverseMask() {#a8c637c167eabe74ec4453abf2258eddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isReverseMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask swaps the order of elements from exactly one source vector.</p>


<p>Example: &lt;7,6,undef,4&gt; This assumes that vector operands (of length <span class="doxyComputerOutput">NumSrcElts</span>) are the same length as the mask.</p>


<p>Declaration at line 2099 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1891 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a6d733b742b1b15bd19fd115db8fd2edd">isSingleSourceMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a43d9b7161f7ae393a165599ca211fe2f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::improveShuffleKindFromMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#abe002e091158d17d71e83b5daf1c2874">llvm::sandboxir::ShuffleVectorInst::isReverseMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a13fe0fbb66d0c3605749a8a366efa746">llvm::sandboxir::ShuffleVectorInst::isReverseMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab83ddc0d46d65b1f035e1c8599b22b8d">lowerBitreverseShuffle</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a>.</p>

</div>
</div>

### isReverseMask() {#ab3115347ae052cfc9b0ea34f76200d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isReverseMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 2100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2b8fb99a1e250aac47d7fc77425edc8e">isReverseMask</a>.</p>

</div>
</div>

### isSelectMask() {#a527e61685c56e6fab3cd424f74fa71ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isSelectMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask chooses elements from its source vectors without lane crossings.</p>


<p>A shuffle using this mask would be equivalent to a vector select with a constant condition operand. Example: &lt;4,1,6,undef&gt; This returns false if the mask does not choose from both input vectors. In that case, the shuffle is better classified as an identity shuffle. This assumes that vector operands are the same length as the mask (a length-changing shuffle can never be equivalent to a vector select).</p>


<p>Declaration at line 2074 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1925 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a6d733b742b1b15bd19fd115db8fd2edd">isSingleSourceMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a98282716af42c878d4638603c6efb350">foldSelectShuffleOfSelectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a43d9b7161f7ae393a165599ca211fe2f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::improveShuffleKindFromMask</a>, <a href="#a747673ac3ea44aadc3907c6b9fd86237">isSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a878990f42d3da1f18e414eab4d325f4e">llvm::sandboxir::ShuffleVectorInst::isSelectMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a736811741c0a6166d8b31452efe84f03">llvm::sandboxir::ShuffleVectorInst::isSelectMask</a>, <a href="#abdf745600e535e9ae260ea7d098d0dc0">isSelectMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>.</p>

</div>
</div>

### isSelectMask() {#abdf745600e535e9ae260ea7d098d0dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isSelectMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 2075 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a> and <a href="#a527e61685c56e6fab3cd424f74fa71ec">isSelectMask</a>.</p>

</div>
</div>

### isSingleSourceMask() {#a6d733b742b1b15bd19fd115db8fd2edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isSingleSourceMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask chooses elements from exactly one source vector.</p>


<p>Example: &lt;7,5,undef,7&gt; This assumes that vector operands (of length <span class="doxyComputerOutput">NumSrcElts</span>) are the same length as the mask.</p>


<p>Declaration at line 2004 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1865 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#ab0c1a9d7c52853132262e899091d74d7">isSingleSourceMaskImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a293fb71d9772916004e2e65674d0bed0">GenerateFixedLengthSVETBL</a>, <a href="#aaf7ca65bff05f19664f7994a03f988e4">isOneUseSingleSourceMask</a>, <a href="#a8c637c167eabe74ec4453abf2258eddb">isReverseMask</a>, <a href="#a527e61685c56e6fab3cd424f74fa71ec">isSelectMask</a>, <a href="#a09ac44360981522c11402c34998b3e46">isSingleSource</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#ac6dce782a19e29daaf4f9d380819641a">llvm::sandboxir::ShuffleVectorInst::isSingleSourceMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a0efdb192d3a624275250a4cd4f40a45a">llvm::sandboxir::ShuffleVectorInst::isSingleSourceMask</a>, <a href="#a2f8a0b7c7f8867de71a57c0582bd3dbb">isSingleSourceMask</a> and <a href="#a0b836340e75383742d06fd0ad2f23ff8">isZeroEltSplatMask</a>.</p>

</div>
</div>

### isSingleSourceMask() {#a2f8a0b7c7f8867de71a57c0582bd3dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isSingleSourceMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 2005 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a> and <a href="#a6d733b742b1b15bd19fd115db8fd2edd">isSingleSourceMask</a>.</p>

</div>
</div>

### isSpliceMask() {#a2474ac30a61257b802cf6ba054e3ef45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isSpliceMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts, int &amp; Index)</td>
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

<p>Return true if this shuffle mask is a splice mask, concatenating the two inputs together and then extracts an original width vector starting from the splice index.</p>


<p>Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;1,2,3,4&gt; This assumes that vector operands (of length <span class="doxyComputerOutput">NumSrcElts</span>) are the same length as the mask.</p>


<p>Declaration at line 2194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1976 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a43d9b7161f7ae393a165599ca211fe2f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::improveShuffleKindFromMask</a>, <a href="#aafe32d39533eb1bfc413016b2b460514">isSplice</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a8374f7f4b3b29372e9f1c0c5a69a9078">llvm::sandboxir::ShuffleVectorInst::isSpliceMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a73de1fc4493d72f5fa83947a2644d5c4">llvm::sandboxir::ShuffleVectorInst::isSpliceMask</a> and <a href="#a830c30a9142f735c9391eaa6f73ad343">isSpliceMask</a>.</p>

</div>
</div>

### isSpliceMask() {#a830c30a9142f735c9391eaa6f73ad343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isSpliceMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int NumSrcElts, int &amp; Index)</td>
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



<p>Definition at line 2195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a> and <a href="#a2474ac30a61257b802cf6ba054e3ef45">isSpliceMask</a>.</p>

</div>
</div>

### isTransposeMask() {#a9c89d6ee326837db1cf0876959acf9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isTransposeMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask is a transpose mask.</p>


<p>Transpose vector masks transpose a 2xn matrix. They read corresponding even- or odd-numbered vector elements from two n-dimensional source vectors and write each result into consecutive elements of an n-dimensional destination vector. Two shuffles are necessary to complete the transpose, one for the even elements and another for the odd elements. This description closely follows how the TRN1 and TRN2 <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> instructions operate.</p>


<p>For example, a simple 2x2 matrix can be transposed with:</p>


<p>; Original matrix m0 = &lt; a, b &gt; m1 = &lt; c, d &gt;</p>


<p>; Transposed matrix t0 = &lt; a, c &gt; = shufflevector m0, m1, &lt; 0, 2 &gt; t1 = &lt; b, d &gt; = shufflevector m0, m1, &lt; 1, 3 &gt;</p>


<p>For matrices having greater than n columns, the resulting nx2 transposed matrix is stored in two result vectors such that one vector contains interleaved elements from all the even-numbered rows and the other vector contains interleaved elements from all the odd-numbered rows. For example, a 2x4 matrix can be transposed with:</p>


<p>; Original matrix m0 = &lt; a, b, c, d &gt; m1 = &lt; e, f, g, h &gt;</p>


<p>; Transposed matrix t0 = &lt; a, e, c, g &gt; = shufflevector m0, m1 &lt; 0, 4, 2, 6 &gt; t1 = &lt; b, f, d, h &gt; = shufflevector m0, m1 &lt; 1, 5, 3, 7 &gt;</p>


<p>Declaration at line 2171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1940 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a43d9b7161f7ae393a165599ca211fe2f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::improveShuffleKindFromMask</a>, <a href="#a887138919e4980f08b8570ed05ccec28">isTranspose</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a28026e5094b94a512f9116384eed7c93">llvm::sandboxir::ShuffleVectorInst::isTransposeMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a348e3ae56c3bc5d21a0e461bd5e8f52d">llvm::sandboxir::ShuffleVectorInst::isTransposeMask</a> and <a href="#af6334dd1d66f3d23bc0d6f30c4eb104b">isTransposeMask</a>.</p>

</div>
</div>

### isTransposeMask() {#af6334dd1d66f3d23bc0d6f30c4eb104b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isTransposeMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 2172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a> and <a href="#a9c89d6ee326837db1cf0876959acf9c8">isTransposeMask</a>.</p>

</div>
</div>

### isValidOperands() {#a4679b8d3496374b0f0fead1b778f99a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isValidOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask)</td>
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

<p>Return true if a shufflevector instruction can be formed with the specified operands.</p>

<p>Declaration at line 1934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1738 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a6f6506f0bc515fe29da3b58565300017">llvm::ConstantExpr::getShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a7fd4a20d9af38768eb00b8065b71dd76">llvm::sandboxir::ShuffleVectorInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a72083a6afb8aa61a69cd177522a6d7ef">llvm::sandboxir::ShuffleVectorInst::isValidOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorconstantexpr/#a9a1de10288271bcf0f869d8121f8525a">llvm::ShuffleVectorConstantExpr::ShuffleVectorConstantExpr</a>, <a href="#a50ca93f9d04de6b4256cdfdb677611ed">ShuffleVectorInst</a>, <a href="#a9550ae3e26eaa39468d80a6940709b5c">ShuffleVectorInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#a1fdfe91f1f9e82078936d0cde2af8a3f">validShuffleVectorIndex</a>.</p>

</div>
</div>

### isValidOperands() {#a5050f6aa93de9b9e43146d95909839aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isValidOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
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



<p>Declaration at line 1936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1718 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad78da75bd1f157e72100f97d1ecdc756">llvm::all_equal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>.</p>

</div>
</div>

### isZeroEltSplatMask() {#a0b836340e75383742d06fd0ad2f23ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ShuffleVectorInst::isZeroEltSplatMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask chooses all elements with the same value as the first element of exactly one source vector.</p>


<p>Example: &lt;4,undef,undef,4&gt; This assumes that vector operands (of length <span class="doxyComputerOutput">NumSrcElts</span>) are the same length as the mask.</p>


<p>Declaration at line 2120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1911 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a6d733b742b1b15bd19fd115db8fd2edd">isSingleSourceMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a43d9b7161f7ae393a165599ca211fe2f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::improveShuffleKindFromMask</a>, <a href="#a67a18df94e5261a66bf51f5cad16d0be">isZeroEltSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a0161f6370b40c5f81caeb9003812124a">llvm::sandboxir::ShuffleVectorInst::isZeroEltSplatMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#ab95b6e9c804784bd5bc4a5d60b76233a">llvm::sandboxir::ShuffleVectorInst::isZeroEltSplatMask</a>, <a href="#ac70c28f75ec58460e2219d92e7e3a710">isZeroEltSplatMask</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a047b7995a79492824633a62540717492">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::peekThroughShuffles</a>.</p>

</div>
</div>

### isZeroEltSplatMask() {#ac70c28f75ec58460e2219d92e7e3a710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ShuffleVectorInst::isZeroEltSplatMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 2121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6eaff12d0d3ead952f2a2a2781df56ac">getShuffleMask</a> and <a href="#a0b836340e75383742d06fd0ad2f23ff8">isZeroEltSplatMask</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllocMarker {#a9d81af4342860f2fffc1350201fbdefc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveOperandsAllocMarker llvm::ShuffleVectorInst::AllocMarker {2}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
