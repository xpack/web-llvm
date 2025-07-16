---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/shufflevectorinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ShuffleVectorInst` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::ShuffleVectorInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">llvm/SandboxIR/Instruction.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/singlellvminstructionimpl">SingleLLVMInstructionImpl&lt;LLVMT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructions that contain a single LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> can inherit from this. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/singlellvminstructionimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a362d0cae5a216badfbd2b30321653278">ShuffleVectorInst</a> (llvm::Instruction *I, Context &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a8372a0db9a902956a6b93ba28739989f">Context::createShuffleVectorInst()</a> instead. <a href="#a362d0cae5a216badfbd2b30321653278">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e70e997a39fb055c1bfab8f994be745">commute</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Swap the operands and adjust the mask to preserve the semantics of the instruction. <a href="#a3e70e997a39fb055c1bfab8f994be745">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09cb3d33809f47986e5023a1b50cdcce">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overload to return most specific vector type. <a href="#a09cb3d33809f47986e5023a1b50cdcce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0879eed4456688b10e2231cc6b7ac6">getMaskValue</a> (unsigned Elt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the shuffle mask value of this instruction for the given element index. <a href="#acf0879eed4456688b10e2231cc6b7ac6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a006c582c4bec3e2881c674cd4ccddefb">getShuffleMask</a> (SmallVectorImpl&lt; int &gt; &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the mask for this instruction as a vector of integers. <a href="#a006c582c4bec3e2881c674cd4ccddefb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149a0f4e491d68dd8d10aaf94cedabb4">getShuffleMaskForBitcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the mask for this instruction, for use in bitcode. <a href="#a149a0f4e491d68dd8d10aaf94cedabb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc00dfadd75bc8833db0eccafcfda661">setShuffleMask</a> (ArrayRef&lt; int &gt; Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13eb72c67a4a11f538aceb15713aef25">getShuffleMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a075f39a7a4718844c3f0e0930715414d">changesLength</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle returns a vector with a different number of elements than its source vectors. <a href="#a075f39a7a4718844c3f0e0930715414d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94792cee6fbfd24ae383b9ce70fd2769">increasesLength</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle returns a vector with a greater number of elements than its source vectors. <a href="#a94792cee6fbfd24ae383b9ce70fd2769">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6341116bfdd3308eb2f018ecc7e2eef7">isSingleSource</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle chooses elements from exactly one source vector without changing the length of that vector. <a href="#a6341116bfdd3308eb2f018ecc7e2eef7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee544a72a6e1d59226d110722e09904">isIdentity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle chooses elements from exactly one source vector without lane crossings and does not change the number of elements from its input vectors. <a href="#a4ee544a72a6e1d59226d110722e09904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09d88ec2c7c034d2bce983202dcddedf">isIdentityWithPadding</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle lengthens exactly one source vector with undefs in the high elements. <a href="#a09d88ec2c7c034d2bce983202dcddedf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11224683dad9098eaf168e8274724db2">isIdentityWithExtract</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle extracts the first N elements of exactly one source vector. <a href="#a11224683dad9098eaf168e8274724db2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7923d3ae310bd0a3d16e0e5233f85109">isConcat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle concatenates its 2 source vectors. <a href="#a7923d3ae310bd0a3d16e0e5233f85109">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c3174242fb6e6a4c1267aa36f0f131">isSelect</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle chooses elements from its source vectors without lane crossings and all operands have the same number of elements. <a href="#ae3c3174242fb6e6a4c1267aa36f0f131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0763e53db0aa8ae2bef6d1579cdae416">isReverse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle swaps the order of elements from exactly one source vector. <a href="#a0763e53db0aa8ae2bef6d1579cdae416">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f05307d2dc546546e4f1eb3e2a6e251">isZeroEltSplat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all elements of this shuffle are the same value as the first element of exactly one source vector without changing the length of that vector. <a href="#a9f05307d2dc546546e4f1eb3e2a6e251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4551913fa0855cc9e0f29340a40bb0d">isTranspose</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle transposes the elements of its inputs without changing the length of the vectors. <a href="#af4551913fa0855cc9e0f29340a40bb0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cb0a07bcdfef68e90f786fd32209866">isSplice</a> (int &amp;Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle splices two inputs without changing the length of the vectors. <a href="#a6cb0a07bcdfef68e90f786fd32209866">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a072f0057fbdcc7d9ee6f383640ba5fae">isExtractSubvectorMask</a> (int &amp;Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is an extract subvector mask. <a href="#a072f0057fbdcc7d9ee6f383640ba5fae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2471b32c45d852920a7a9d51661931">isInsertSubvectorMask</a> (int &amp;NumSubElts, int &amp;Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is an insert subvector mask. <a href="#adb2471b32c45d852920a7a9d51661931">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d59877a3691fd972c58f257b86026f">isReplicationMask</a> (int &amp;ReplicationFactor, int &amp;VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is a replication mask. <a href="#a76d59877a3691fd972c58f257b86026f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7bc0d2b9c9db44107b4e72223c4da07">isOneUseSingleSourceMask</a> (int VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is a one-use-single-source("clustered") mask. <a href="#ac7bc0d2b9c9db44107b4e72223c4da07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b39e6114949bf8f91785c82ce7e3e30">isInterleave</a> (unsigned Factor) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if this shuffle interleaves its two input vectors together. <a href="#a1b39e6114949bf8f91785c82ce7e3e30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca5925f8d91859a70ccb210b60aac65">create</a> (Value *V1, Value *V2, Value *Mask, InsertPosition Pos, Context &amp;Ctx, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab162771ca7877c597181850f69bd208c">create</a> (Value *V1, Value *V2, ArrayRef&lt; int &gt; Mask, InsertPosition Pos, Context &amp;Ctx, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afedc432860565b4f67bb8e52df73ba7d">classof</a> (const Value *From)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72083a6afb8aa61a69cd177522a6d7ef">isValidOperands</a> (const Value *V1, const Value *V2, const Value *Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a shufflevector instruction can be formed with the specified operands. <a href="#a72083a6afb8aa61a69cd177522a6d7ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd4a20d9af38768eb00b8065b71dd76">isValidOperands</a> (const Value *V1, const Value *V2, ArrayRef&lt; int &gt; Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab200dfd5c34c21db06ff2139e68debc8">getShuffleMask</a> (const Constant *Mask, SmallVectorImpl&lt; int &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the input shuffle mask operand to a vector of integers. <a href="#ab200dfd5c34c21db06ff2139e68debc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6224f807d740562c873c036926d0dfd9">convertShuffleMaskForBitcode</a> (ArrayRef&lt; int &gt; Mask, Type *ResultTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6dce782a19e29daaf4f9d380819641a">isSingleSourceMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask chooses elements from exactly one source vector. <a href="#ac6dce782a19e29daaf4f9d380819641a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0efdb192d3a624275250a4cd4f40a45a">isSingleSourceMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ffa0b5875610369046b023b0e3b7ca">isIdentityMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask chooses elements from exactly one source vector without lane crossings. <a href="#a12ffa0b5875610369046b023b0e3b7ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a5d48ed7d2f1d8ebba3d092afab021">isIdentityMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a878990f42d3da1f18e414eab4d325f4e">isSelectMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask chooses elements from its source vectors without lane crossings. <a href="#a878990f42d3da1f18e414eab4d325f4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a736811741c0a6166d8b31452efe84f03">isSelectMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe002e091158d17d71e83b5daf1c2874">isReverseMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask swaps the order of elements from exactly one source vector. <a href="#abe002e091158d17d71e83b5daf1c2874">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13fe0fbb66d0c3605749a8a366efa746">isReverseMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0161f6370b40c5f81caeb9003812124a">isZeroEltSplatMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask chooses all elements with the same value as the first element of exactly one source vector. <a href="#a0161f6370b40c5f81caeb9003812124a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab95b6e9c804784bd5bc4a5d60b76233a">isZeroEltSplatMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28026e5094b94a512f9116384eed7c93">isTransposeMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is a transpose mask. <a href="#a28026e5094b94a512f9116384eed7c93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348e3ae56c3bc5d21a0e461bd5e8f52d">isTransposeMask</a> (const Constant *Mask, int NumSrcElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8374f7f4b3b29372e9f1c0c5a69a9078">isSpliceMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts, int &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is a splice mask, concatenating the two inputs together and then extracts an original width vector starting from the splice index. <a href="#a8374f7f4b3b29372e9f1c0c5a69a9078">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73de1fc4493d72f5fa83947a2644d5c4">isSpliceMask</a> (const Constant *Mask, int NumSrcElts, int &amp;Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6376f131f9732efa3b04f6007d7a7e4a">isExtractSubvectorMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts, int &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is an extract subvector mask. <a href="#a6376f131f9732efa3b04f6007d7a7e4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad3a22eb16aa72a2d2a4d8b7db77463">isExtractSubvectorMask</a> (const Constant *Mask, int NumSrcElts, int &amp;Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac6402d988a5e91be8fed57216a6809">isInsertSubvectorMask</a> (ArrayRef&lt; int &gt; Mask, int NumSrcElts, int &amp;NumSubElts, int &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask is an insert subvector mask. <a href="#aaac6402d988a5e91be8fed57216a6809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e490d4b7fe9b12f07733db1d8ab677">isInsertSubvectorMask</a> (const Constant *Mask, int NumSrcElts, int &amp;NumSubElts, int &amp;Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4392650bdea712205171ab9a5eb11990">isReplicationMask</a> (ArrayRef&lt; int &gt; Mask, int &amp;ReplicationFactor, int &amp;VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask replicates each of the <span class="doxyComputerOutput">VF</span> elements in a vector <span class="doxyComputerOutput">ReplicationFactor</span> times. <a href="#a4392650bdea712205171ab9a5eb11990">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f791365d06f0905613d0ac07e265c45">isReplicationMask</a> (const Constant *Mask, int &amp;ReplicationFactor, int &amp;VF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a252c430f2d2ac65ad395418c6e4bf924">isOneUseSingleSourceMask</a> (ArrayRef&lt; int &gt; Mask, int VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this shuffle mask represents "clustered" mask of size VF, i.e. <a href="#a252c430f2d2ac65ad395418c6e4bf924">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9038a51df4c44345a12abb05ab057a73">commuteShuffleMask</a> (MutableArrayRef&lt; int &gt; Mask, unsigned InVecNumElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change values in a shuffle permute mask assuming the two vector operands of length InVecNumElts have swapped position. <a href="#a9038a51df4c44345a12abb05ab057a73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1befcfac778c8aaa7cab09de808cbcb7">isInterleaveMask</a> (ArrayRef&lt; int &gt; Mask, unsigned Factor, unsigned NumInputElts, SmallVectorImpl&lt; unsigned &gt; &amp;StartIndexes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the mask interleaves one or more input vectors together. <a href="#a1befcfac778c8aaa7cab09de808cbcb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1ba6001c24f47b2a45280d830d2bab">isInterleaveMask</a> (ArrayRef&lt; int &gt; Mask, unsigned Factor, unsigned NumInputElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc2195bf46bca7dd5464dd3580e4449d">isDeInterleaveMaskOfFactor</a> (ArrayRef&lt; int &gt; Mask, unsigned Factor, unsigned &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the mask is a DE-interleave mask of the given factor <span class="doxyComputerOutput">Factor</span> like: &lt;Index, Index+Factor, ..., Index+(NumElts-1)*Factor&gt; <a href="#acc2195bf46bca7dd5464dd3580e4449d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5295662c5a712596dd4f5ca1dd4a5154">isDeInterleaveMaskOfFactor</a> (ArrayRef&lt; int &gt; Mask, unsigned Factor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7692cb204bee86bea3cb7f41a580347b">isBitRotateMask</a> (ArrayRef&lt; int &gt; Mask, unsigned EltSizeInBits, unsigned MinSubElts, unsigned MaxSubElts, unsigned &amp;NumSubElts, unsigned &amp;RotateAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the shuffle is a bit rotation of the first operand across multiple subelements, e.g: <a href="#a7692cb204bee86bea3cb7f41a580347b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Context {#ac26c806e60ca4a0547680edb68f6e39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>.</p>


<p>Referenced by <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="#ab162771ca7877c597181850f69bd208c">create</a> and <a href="#a4ca5925f8d91859a70ccb210b60aac65">create</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ShuffleVectorInst() {#a362d0cae5a216badfbd2b30321653278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::ShuffleVectorInst::ShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a8372a0db9a902956a6b93ba28739989f">Context::createShuffleVectorInst()</a> instead.</p>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changesLength() {#a075f39a7a4718844c3f0e0930715414d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::changesLength ()</td>
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


<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### commute() {#a3e70e997a39fb055c1bfab8f994be745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::ShuffleVectorInst::commute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Swap the operands and adjust the mask to preserve the semantics of the instruction.</p>

<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 1504 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#acb9166dd8e540f8c9e6efad7e9cccba0">llvm::sandboxir::User::getOperandUse</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getMaskValue() {#acf0879eed4456688b10e2231cc6b7ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::sandboxir::ShuffleVectorInst::getMaskValue (unsigned Elt)</td>
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


<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getShuffleMask() {#a006c582c4bec3e2881c674cd4ccddefb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::ShuffleVectorInst::getShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Result)</td>
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


<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getShuffleMask() {#a13eb72c67a4a11f538aceb15713aef25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; int &gt; llvm::sandboxir::ShuffleVectorInst::getShuffleMask ()</td>
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



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getShuffleMaskForBitcode() {#a149a0f4e491d68dd8d10aaf94cedabb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::sandboxir::ShuffleVectorInst::getShuffleMaskForBitcode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the mask for this instruction, for use in bitcode.</p>

<p>Declaration at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 1511 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="#a149a0f4e491d68dd8d10aaf94cedabb4">getShuffleMaskForBitcode</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="#a149a0f4e491d68dd8d10aaf94cedabb4">getShuffleMaskForBitcode</a>.</p>

</div>
</div>

### getType() {#a09cb3d33809f47986e5023a1b50cdcce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::sandboxir::ShuffleVectorInst::getType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Overload to return most specific vector type.</p>

<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 1499 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### increasesLength() {#a94792cee6fbfd24ae383b9ce70fd2769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::increasesLength ()</td>
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


<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isConcat() {#a7923d3ae310bd0a3d16e0e5233f85109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isConcat ()</td>
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

<p>Return true if this shuffle concatenates its 2 source vectors.</p>


<p>This returns false if either input is undefined. In that case, the shuffle is is better classified as an identity with padding operation.</p>


<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isExtractSubvectorMask() {#a072f0057fbdcc7d9ee6f383640ba5fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isExtractSubvectorMask (int &amp; Index)</td>
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

<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isIdentity() {#a4ee544a72a6e1d59226d110722e09904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isIdentity ()</td>
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


<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isIdentityWithExtract() {#a11224683dad9098eaf168e8274724db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isIdentityWithExtract ()</td>
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

<p>Return true if this shuffle extracts the first N elements of exactly one source vector.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isIdentityWithPadding() {#a09d88ec2c7c034d2bce983202dcddedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isIdentityWithPadding ()</td>
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

<p>Return true if this shuffle lengthens exactly one source vector with undefs in the high elements.</p>

<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isInsertSubvectorMask() {#adb2471b32c45d852920a7a9d51661931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isInsertSubvectorMask (int &amp; NumSubElts, int &amp; Index)</td>
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

<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isInterleave() {#a1b39e6114949bf8f91785c82ce7e3e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isInterleave (unsigned Factor)</td>
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

<p>Return if this shuffle interleaves its two input vectors together.</p>

<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isOneUseSingleSourceMask() {#ac7bc0d2b9c9db44107b4e72223c4da07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isOneUseSingleSourceMask (int VF)</td>
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

<p>Return true if this shuffle mask is a one-use-single-source("clustered") mask.</p>

<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isReplicationMask() {#a76d59877a3691fd972c58f257b86026f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isReplicationMask (int &amp; ReplicationFactor, int &amp; VF)</td>
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

<p>Return true if this shuffle mask is a replication mask.</p>

<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isReverse() {#a0763e53db0aa8ae2bef6d1579cdae416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isReverse ()</td>
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


<p>Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;3,undef,1,undef&gt;</p>


<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isSelect() {#ae3c3174242fb6e6a4c1267aa36f0f131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isSelect ()</td>
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


<p>In other words, this shuffle is equivalent to a vector select with a constant condition operand. Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;undef,1,6,3&gt; This returns false if the mask does not choose from both input vectors. In that case, the shuffle is better classified as an identity shuffle.</p>


<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isSingleSource() {#a6341116bfdd3308eb2f018ecc7e2eef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isSingleSource ()</td>
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


<p>Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;3,0,undef,3&gt;</p>


<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isSplice() {#a6cb0a07bcdfef68e90f786fd32209866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isSplice (int &amp; Index)</td>
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


<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isTranspose() {#af4551913fa0855cc9e0f29340a40bb0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isTranspose ()</td>
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


<p>This operation may also be known as a merge or interleave. See the description for <a href="#a28026e5094b94a512f9116384eed7c93">isTransposeMask()</a> for the exact specification. Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;0,4,2,6&gt;</p>


<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isZeroEltSplat() {#a9f05307d2dc546546e4f1eb3e2a6e251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isZeroEltSplat ()</td>
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


<p>Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;undef,0,undef,0&gt;</p>


<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### setShuffleMask() {#abc00dfadd75bc8833db0eccafcfda661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::ShuffleVectorInst::setShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 1494 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#afedc432860565b4f67bb8e52df73ba7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * From)</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a27b9af008c6420f3340805e50297f9fb">llvm::sandboxir::Value::getSubclassID</a>.</p>

</div>
</div>

### commuteShuffleMask() {#a9038a51df4c44345a12abb05ab057a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::ShuffleVectorInst::commuteShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; int &gt; Mask, unsigned InVecNumElts)</td>
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

<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a9874bec83353914ed1e9309d5d9ccea0">llvm::ShuffleVectorInst::commuteShuffleMask</a>.</p>

</div>
</div>

### convertShuffleMaskForBitcode() {#a6224f807d740562c873c036926d0dfd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::sandboxir::ShuffleVectorInst::convertShuffleMaskForBitcode (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * ResultTy)</td>
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



<p>Declaration at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ad06dcf793a8b91871327c682d6f3f909">llvm::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#ae662f556252fe75768094c7976518409">llvm::sandboxir::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a7bf97c49fc62d8d7b10f346d1887c727">llvm::sandboxir::Context::getOrCreateConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a330bbaf89b90196df6960be4724513c6">llvm::sandboxir::Type::LLVMTy</a>.</p>

</div>
</div>

### create() {#a4ca5925f8d91859a70ccb210b60aac65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::ShuffleVectorInst::create (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * Mask, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertposition">InsertPosition</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 1471 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### create() {#ab162771ca7877c597181850f69bd208c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::ShuffleVectorInst::create (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertposition">InsertPosition</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
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



<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 1483 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getShuffleMask() {#ab200dfd5c34c21db06ff2139e68debc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::ShuffleVectorInst::getShuffleMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Result)</td>
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

<p>Convert the input shuffle mask operand to a vector of integers.</p>


<p>Undefined elements of the mask are returned as PoisonMaskElem.</p>


<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a20966136ad311c1a48b6d8d0bab597c0">llvm::ShuffleVectorInst::getShuffleMask</a>.</p>

</div>
</div>

### isBitRotateMask() {#a7692cb204bee86bea3cb7f41a580347b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isBitRotateMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned EltSizeInBits, unsigned MinSubElts, unsigned MaxSubElts, unsigned &amp; NumSubElts, unsigned &amp; RotateAmt)</td>
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

<p>Checks if the shuffle is a bit rotation of the first operand across multiple subelements, e.g:</p>


<p>shuffle &lt;8 x i8&gt; a, &lt;8 x i8&gt; poison, &lt;8 x i32&gt; &lt;1, 0, 3, 2, 5, 4, 7, 6&gt;</p>


<p>could be expressed as</p>


<p>rotl &lt;4 x i16&gt; a, 8</p>


<p>If it can be expressed as a rotation, returns the number of subelements to group by in NumSubElts and the number of bits to rotate left in RotateAmt.</p>


<p>Definition at line 951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a54f0b0ca5ff870c4dca191f5133dbb60">llvm::ShuffleVectorInst::isBitRotateMask</a>.</p>

</div>
</div>

### isDeInterleaveMaskOfFactor() {#acc2195bf46bca7dd5464dd3580e4449d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isDeInterleaveMaskOfFactor (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned Factor, unsigned &amp; Index)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the mask is a DE-interleave mask of the given factor <span class="doxyComputerOutput">Factor</span> like: &lt;Index, Index+Factor, ..., Index+(NumElts-1)*Factor&gt;</p>

<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a7f15b97df1c138940047d9442b02b13b">llvm::ShuffleVectorInst::isDeInterleaveMaskOfFactor</a>.</p>

</div>
</div>

### isDeInterleaveMaskOfFactor() {#a5295662c5a712596dd4f5ca1dd4a5154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isDeInterleaveMaskOfFactor (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned Factor)</td>
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



<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a7f15b97df1c138940047d9442b02b13b">llvm::ShuffleVectorInst::isDeInterleaveMaskOfFactor</a>.</p>

</div>
</div>

### isExtractSubvectorMask() {#a6376f131f9732efa3b04f6007d7a7e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isExtractSubvectorMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts, int &amp; Index)</td>
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

<p>Return true if this shuffle mask is an extract subvector mask.</p>


<p>A valid extract subvector mask returns a smaller vector from a single source operand. The base extraction index is returned as well.</p>


<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a841e0c83f3c14a1b0979d86a1812f335">llvm::ShuffleVectorInst::isExtractSubvectorMask</a>.</p>

</div>
</div>

### isExtractSubvectorMask() {#a1ad3a22eb16aa72a2d2a4d8b7db77463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isExtractSubvectorMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int NumSrcElts, int &amp; Index)</td>
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



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a841e0c83f3c14a1b0979d86a1812f335">llvm::ShuffleVectorInst::isExtractSubvectorMask</a>.</p>

</div>
</div>

### isIdentityMask() {#a12ffa0b5875610369046b023b0e3b7ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isIdentityMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask chooses elements from exactly one source vector without lane crossings.</p>


<p>A shuffle using this mask is not necessarily a no-op because it may change the number of elements from its input vectors or it may provide demanded bits knowledge via undef lanes. Example: &lt;undef,undef,2,3&gt;</p>


<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a81aa4ff7f63f7988abea1abbe9eb0342">llvm::ShuffleVectorInst::isIdentityMask</a>.</p>

</div>
</div>

### isIdentityMask() {#a50a5d48ed7d2f1d8ebba3d092afab021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isIdentityMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a81aa4ff7f63f7988abea1abbe9eb0342">llvm::ShuffleVectorInst::isIdentityMask</a>.</p>

</div>
</div>

### isInsertSubvectorMask() {#aaac6402d988a5e91be8fed57216a6809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isInsertSubvectorMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts, int &amp; NumSubElts, int &amp; Index)</td>
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

<p>Return true if this shuffle mask is an insert subvector mask.</p>


<p>A valid insert subvector mask inserts the lowest elements of a second source operand into an in-place first source operand. Both the sub vector width and the insertion index is returned.</p>


<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ab9c981efb05d9ee219a85648972f71bd">llvm::ShuffleVectorInst::isInsertSubvectorMask</a>.</p>

</div>
</div>

### isInsertSubvectorMask() {#a82e490d4b7fe9b12f07733db1d8ab677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isInsertSubvectorMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int NumSrcElts, int &amp; NumSubElts, int &amp; Index)</td>
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



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ab9c981efb05d9ee219a85648972f71bd">llvm::ShuffleVectorInst::isInsertSubvectorMask</a>.</p>

</div>
</div>

### isInterleaveMask() {#a1befcfac778c8aaa7cab09de808cbcb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isInterleaveMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned Factor, unsigned NumInputElts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; StartIndexes)</td>
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

<p>Return true if the mask interleaves one or more input vectors together.</p>


<p>I.e. &lt;0, LaneLen, ... , LaneLen*(Factor - 1), 1, LaneLen + 1, ...&gt; E.g. For a Factor of 2 (LaneLen=4): &lt;0, 4, 1, 5, 2, 6, 3, 7&gt; E.g. For a Factor of 3 (LaneLen=4): &lt;4, 0, 9, 5, 1, 10, 6, 2, 11, 7, 3, 12&gt; E.g. For a Factor of 4 (LaneLen=2): &lt;0, 2, 6, 4, 1, 3, 7, 5&gt;</p>


<p>NumInputElts is the total number of elements in the input vectors.</p>


<p>StartIndexes are the first indexes of each vector being interleaved, substituting any indexes that were undef E.g. &lt;4, -1, 2, 5, 1, 3&gt; (Factor=3): StartIndexes=&lt;4, 0, 2&gt;</p>


<p>Note that this does not check if the input vectors are consecutive: It will return true for masks such as &lt;0, 4, 6, 1, 5, 7&gt; (Factor=3, LaneLen=2)</p>


<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#af9582c096b5d287b663ec8ca4550aa72">llvm::ShuffleVectorInst::isInterleaveMask</a>.</p>

</div>
</div>

### isInterleaveMask() {#a3c1ba6001c24f47b2a45280d830d2bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isInterleaveMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned Factor, unsigned NumInputElts)</td>
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



<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#af9582c096b5d287b663ec8ca4550aa72">llvm::ShuffleVectorInst::isInterleaveMask</a>.</p>

</div>
</div>

### isOneUseSingleSourceMask() {#a252c430f2d2ac65ad395418c6e4bf924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isOneUseSingleSourceMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int VF)</td>
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

<p>Return true if this shuffle mask represents "clustered" mask of size VF, i.e.</p>


<p>each index between [0..VF) is used exactly once in each submask of size VF. For example, the mask for <span class="doxyComputerOutput">VF=4</span> is: 0, 1, 2, 3, 3, 2, 0, 1 - "clustered", because each submask of size 4 (0,1,2,3 and 3,2,0,1) uses indices [0..VF) exactly one time. 0, 1, 2, 3, 3, 3, 1, 0 - not "clustered", because element 3 is used twice in the second submask (3,3,1,0) and index 2 is not used at all.</p>


<p>Definition at line 875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a6659bba6a4be5e7102bdb10e5fc3658c">llvm::ShuffleVectorInst::isOneUseSingleSourceMask</a>.</p>

</div>
</div>

### isReplicationMask() {#a4392650bdea712205171ab9a5eb11990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isReplicationMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int &amp; ReplicationFactor, int &amp; VF)</td>
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

<p>Return true if this shuffle mask replicates each of the <span class="doxyComputerOutput">VF</span> elements in a vector <span class="doxyComputerOutput">ReplicationFactor</span> times.</p>


<p>For example, the mask for <span class="doxyComputerOutput">ReplicationFactor=3</span> and <span class="doxyComputerOutput">VF=4</span> is: &lt;0,0,0,1,1,1,2,2,2,3,3,3&gt;</p>


<p>Definition at line 849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#aded1d376d952f6c163f1020aca8a7d67">llvm::ShuffleVectorInst::isReplicationMask</a>.</p>

</div>
</div>

### isReplicationMask() {#a4f791365d06f0905613d0ac07e265c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isReplicationMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int &amp; ReplicationFactor, int &amp; VF)</td>
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



<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#aded1d376d952f6c163f1020aca8a7d67">llvm::ShuffleVectorInst::isReplicationMask</a>.</p>

</div>
</div>

### isReverseMask() {#abe002e091158d17d71e83b5daf1c2874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isReverseMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask swaps the order of elements from exactly one source vector.</p>


<p>Example: &lt;7,6,undef,4&gt; This assumes that vector operands (of length <span class="doxyComputerOutput">NumSrcElts</span>) are the same length as the mask.</p>


<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a8c637c167eabe74ec4453abf2258eddb">llvm::ShuffleVectorInst::isReverseMask</a>.</p>

</div>
</div>

### isReverseMask() {#a13fe0fbb66d0c3605749a8a366efa746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isReverseMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a8c637c167eabe74ec4453abf2258eddb">llvm::ShuffleVectorInst::isReverseMask</a>.</p>

</div>
</div>

### isSelectMask() {#a878990f42d3da1f18e414eab4d325f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isSelectMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask chooses elements from its source vectors without lane crossings.</p>


<p>A shuffle using this mask would be equivalent to a vector select with a constant condition operand. Example: &lt;4,1,6,undef&gt; This returns false if the mask does not choose from both input vectors. In that case, the shuffle is better classified as an identity shuffle. This assumes that vector operands are the same length as the mask (a length-changing shuffle can never be equivalent to a vector select).</p>


<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a527e61685c56e6fab3cd424f74fa71ec">llvm::ShuffleVectorInst::isSelectMask</a>.</p>

</div>
</div>

### isSelectMask() {#a736811741c0a6166d8b31452efe84f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isSelectMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a527e61685c56e6fab3cd424f74fa71ec">llvm::ShuffleVectorInst::isSelectMask</a>.</p>

</div>
</div>

### isSingleSourceMask() {#ac6dce782a19e29daaf4f9d380819641a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isSingleSourceMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask chooses elements from exactly one source vector.</p>


<p>Example: &lt;7,5,undef,7&gt; This assumes that vector operands (of length <span class="doxyComputerOutput">NumSrcElts</span>) are the same length as the mask.</p>


<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a6d733b742b1b15bd19fd115db8fd2edd">llvm::ShuffleVectorInst::isSingleSourceMask</a>.</p>

</div>
</div>

### isSingleSourceMask() {#a0efdb192d3a624275250a4cd4f40a45a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isSingleSourceMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a6d733b742b1b15bd19fd115db8fd2edd">llvm::ShuffleVectorInst::isSingleSourceMask</a>.</p>

</div>
</div>

### isSpliceMask() {#a8374f7f4b3b29372e9f1c0c5a69a9078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isSpliceMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts, int &amp; Index)</td>
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

<p>Return true if this shuffle mask is a splice mask, concatenating the two inputs together and then extracts an original width vector starting from the splice index.</p>


<p>Example: shufflevector &lt;4 x n&gt; A, &lt;4 x n&gt; B, &lt;1,2,3,4&gt; This assumes that vector operands (of length <span class="doxyComputerOutput">NumSrcElts</span>) are the same length as the mask.</p>


<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a2474ac30a61257b802cf6ba054e3ef45">llvm::ShuffleVectorInst::isSpliceMask</a>.</p>

</div>
</div>

### isSpliceMask() {#a73de1fc4493d72f5fa83947a2644d5c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isSpliceMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int NumSrcElts, int &amp; Index)</td>
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



<p>Definition at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a2474ac30a61257b802cf6ba054e3ef45">llvm::ShuffleVectorInst::isSpliceMask</a>.</p>

</div>
</div>

### isTransposeMask() {#a28026e5094b94a512f9116384eed7c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isTransposeMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask is a transpose mask.</p>


<p>Transpose vector masks transpose a 2xn matrix. They read corresponding even- or odd-numbered vector elements from two n-dimensional source vectors and write each result into consecutive elements of an n-dimensional destination vector. Two shuffles are necessary to complete the transpose, one for the even elements and another for the odd elements. This description closely follows how the TRN1 and TRN2 <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> instructions operate.</p>


<p>For example, a simple 2x2 matrix can be transposed with:</p>


<p>; Original matrix m0 = &lt; a, b &gt; m1 = &lt; c, d &gt;</p>


<p>; Transposed matrix t0 = &lt; a, c &gt; = shufflevector m0, m1, &lt; 0, 2 &gt; t1 = &lt; b, d &gt; = shufflevector m0, m1, &lt; 1, 3 &gt;</p>


<p>For matrices having greater than n columns, the resulting nx2 transposed matrix is stored in two result vectors such that one vector contains interleaved elements from all the even-numbered rows and the other vector contains interleaved elements from all the odd-numbered rows. For example, a 2x4 matrix can be transposed with:</p>


<p>; Original matrix m0 = &lt; a, b, c, d &gt; m1 = &lt; e, f, g, h &gt;</p>


<p>; Transposed matrix t0 = &lt; a, e, c, g &gt; = shufflevector m0, m1 &lt; 0, 4, 2, 6 &gt; t1 = &lt; b, f, d, h &gt; = shufflevector m0, m1 &lt; 1, 5, 3, 7 &gt;</p>


<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a9c89d6ee326837db1cf0876959acf9c8">llvm::ShuffleVectorInst::isTransposeMask</a>.</p>

</div>
</div>

### isTransposeMask() {#a348e3ae56c3bc5d21a0e461bd5e8f52d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isTransposeMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a9c89d6ee326837db1cf0876959acf9c8">llvm::ShuffleVectorInst::isTransposeMask</a>.</p>

</div>
</div>

### isValidOperands() {#a72083a6afb8aa61a69cd177522a6d7ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isValidOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * Mask)</td>
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

<p>Return true if a shufflevector instruction can be formed with the specified operands.</p>

<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a4679b8d3496374b0f0fead1b778f99a2">llvm::ShuffleVectorInst::isValidOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isValidOperands() {#a7fd4a20d9af38768eb00b8065b71dd76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isValidOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
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



<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a4679b8d3496374b0f0fead1b778f99a2">llvm::ShuffleVectorInst::isValidOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isZeroEltSplatMask() {#a0161f6370b40c5f81caeb9003812124a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isZeroEltSplatMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, int NumSrcElts)</td>
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

<p>Return true if this shuffle mask chooses all elements with the same value as the first element of exactly one source vector.</p>


<p>Example: &lt;4,undef,undef,4&gt; This assumes that vector operands (of length <span class="doxyComputerOutput">NumSrcElts</span>) are the same length as the mask.</p>


<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a0b836340e75383742d06fd0ad2f23ff8">llvm::ShuffleVectorInst::isZeroEltSplatMask</a>.</p>

</div>
</div>

### isZeroEltSplatMask() {#ab95b6e9c804784bd5bc4a5d60b76233a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ShuffleVectorInst::isZeroEltSplatMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a> * Mask, int NumSrcElts)</td>
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



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a0b836340e75383742d06fd0ad2f23ff8">llvm::ShuffleVectorInst::isZeroEltSplatMask</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
