---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/legalizerhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LegalizerHelper` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LegalizerHelper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">llvm/CodeGen/GlobalISel/LegalizerHelper.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LegalizeResult { <a href="#a97444fdd32d8610e39f82294399f3adc">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa10024dcff51f09d4751794584609e85">LegalizerHelper</a> (MachineFunction &amp;MF, GISelChangeObserver &amp;Observer, MachineIRBuilder &amp;B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9006a4423b6daf984091f1b43e549f17">LegalizerHelper</a> (MachineFunction &amp;MF, const LegalizerInfo &amp;LI, GISelChangeObserver &amp;Observer, MachineIRBuilder &amp;B, GISelKnownBits *KB=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ead1a81ece71a564c51ee5b5e9bd2f0">getLegalizerInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expose <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> so the clients can re-use. <a href="#a8ead1a81ece71a564c51ee5b5e9bd2f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6630af3b97791f4a324cd84f01911408">getTargetLowering</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0e092c7b577c4a6c2607581405d6a23">getKnownBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8ec769be431aa1296a7c786eb456f53">legalizeInstrStep</a> (MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace <span class="doxyComputerOutput">MI</span> by a sequence of legal instructions that can implement the same operation. <a href="#af8ec769be431aa1296a7c786eb456f53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a495f4190353f60d1cd5e471283f40">libcall</a> (MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize an instruction by emiting a runtime library call instead. <a href="#ad8a495f4190353f60d1cd5e471283f40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize an instruction by reducing the width of the underlying scalar type. <a href="#a6701d040466d73f3dc51481d3186c294">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacc36b9bbb74a3cdb987aa8f28b269e3">widenScalar</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT WideTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize an instruction by performing the operation on a wider scalar type (for example a 16-bit addition can be safely performed at 32-bits precision, ignoring the unused bits). <a href="#aacc36b9bbb74a3cdb987aa8f28b269e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize an instruction by replacing the value type. <a href="#a6c12dbad109a5d725ce01a9a8363f948">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize an instruction by splitting it into simpler parts, hopefully understood by the target. <a href="#aa411af5653e9ed6cd4f664853b61bf0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a vector instruction by splitting into multiple components, each acting on the same scalar type as the original but with fewer elements. <a href="#aa8fe481cda91a90b364e410009785003">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ffccbb574e8a2cf63b8ede89f53090b">moreElementsVector</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT MoreTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a vector instruction by increasing the number of vector elements involved and ignoring the added elements later. <a href="#a2ffccbb574e8a2cf63b8ede89f53090b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6c42a7b5fe244fad430ca7df32d346">coerceToScalar</a> (Register Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast the given value to an <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">LLT::scalar</a> with an equivalent size. <a href="#acc6c42a7b5fe244fad430ca7df32d346">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1675c68d181eacf6dde19dc7d0cdd20c">widenScalarSrc</a> (MachineInstr &amp;MI, LLT WideTy, unsigned OpIdx, unsigned ExtOpcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> by extending the operand's type to <span class="doxyComputerOutput">WideTy</span> using the specified <span class="doxyComputerOutput">ExtOpcode</span> for the extension instruction, and replacing the vreg of the operand in place. <a href="#a1675c68d181eacf6dde19dc7d0cdd20c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cafcb9996d69b6f864daa6c7d00c48a">narrowScalarSrc</a> (MachineInstr &amp;MI, LLT NarrowTy, unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> by truncating the operand's type to <span class="doxyComputerOutput">NarrowTy</span> using G_TRUNC, and replacing the vreg of the operand in place. <a href="#a5cafcb9996d69b6f864daa6c7d00c48a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af704613be9bed4ecd92e5aee263c2d5f">widenScalarDst</a> (MachineInstr &amp;MI, LLT WideTy, unsigned OpIdx=0, unsigned TruncOpcode=TargetOpcode::G_TRUNC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a Def by extending the operand's type to <span class="doxyComputerOutput">WideTy</span> and truncating it back with the <span class="doxyComputerOutput">TruncOpcode</span>, and replacing the vreg of the operand in place. <a href="#af704613be9bed4ecd92e5aee263c2d5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f8e31fdc4b07d287c52567a2d259f4">narrowScalarDst</a> (MachineInstr &amp;MI, LLT NarrowTy, unsigned OpIdx, unsigned ExtOpcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a4c14864c6f574bc99e19e15a8b4d2">moreElementsVectorDst</a> (MachineInstr &amp;MI, LLT MoreTy, unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a Def by performing it with additional vector elements and extracting the result elements, and replacing the vreg of the operand in place. <a href="#a25a4c14864c6f574bc99e19e15a8b4d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac465c012a999bcab06235573fcb0860f">moreElementsVectorSrc</a> (MachineInstr &amp;MI, LLT MoreTy, unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> by producing a vector with undefined high elements, extracting the original vector type, and replacing the vreg of the operand in place. <a href="#ac465c012a999bcab06235573fcb0860f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6cbca2857caf659c388e189c948a1fd">bitcastSrc</a> (MachineInstr &amp;MI, LLT CastTy, unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a use by inserting a G_BITCAST to <span class="doxyComputerOutput">CastTy</span>. <a href="#ad6cbca2857caf659c388e189c948a1fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa02ab5ab2c50cce96f4fec73c8186c3">bitcastDst</a> (MachineInstr &amp;MI, LLT CastTy, unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a def by inserting a G_BITCAST from <span class="doxyComputerOutput">CastTy</span>. <a href="#aaa02ab5ab2c50cce96f4fec73c8186c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee39b6aa6b9299acb9388393e34f3937">getStackTemporaryAlignment</a> (LLT Type, Align MinAlign=Align()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment to use for a stack temporary object with the given type. <a href="#aee39b6aa6b9299acb9388393e34f3937">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a576b964fe2d7d8750601681e04f05a9c">createStackTemporary</a> (TypeSize Bytes, Align Alignment, MachinePointerInfo &amp;PtrInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a stack temporary based on the size in bytes and the alignment. <a href="#a576b964fe2d7d8750601681e04f05a9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92bad93a924413adf3652db02e467a21">createStackStoreLoad</a> (const DstOp &amp;Res, const SrcOp &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a store of <span class="doxyComputerOutput">Val</span> to a stack temporary and return a load as the same type as <span class="doxyComputerOutput">Res</span>. <a href="#a92bad93a924413adf3652db02e467a21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d8b5e9460092c4517e5e594756fcb82">scalarizeVectorBooleanStore</a> (GStore &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a store of a boolean vector, scalarize it. <a href="#a6d8b5e9460092c4517e5e594756fcb82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae91b4ff9d9c084c672f78adb9ed4006a">getVectorElementPointer</a> (Register VecPtr, LLT VecTy, Register Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to vector element <span class="doxyComputerOutput">Index</span> located in memory for a vector of type <span class="doxyComputerOutput">VecTy</span> starting at a base address of <span class="doxyComputerOutput">VecPtr</span>. <a href="#ae91b4ff9d9c084c672f78adb9ed4006a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6d92157833612e9b4cd0085e181b7e">fewerElementsVectorMultiEltType</a> (GenericMachineInstr &amp;MI, unsigned NumElts, std::initializer_list&lt; unsigned &gt; NonVecOpIndices={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handles most opcodes. <a href="#a8f6d92157833612e9b4cd0085e181b7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e4161d46b020a55403acd13e31df9a">fewerElementsVectorPhi</a> (GenericMachineInstr &amp;MI, unsigned NumElts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e3f12f0b3d7f35251e1e71336b480c">moreElementsVectorPhi</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT MoreTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a3548d0921506d0cd736b7960c12485">moreElementsVectorShuffle</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT MoreTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abce993680c63fae7b6cc5814e9b07826">fewerElementsVectorUnmergeValues</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2458b37415bd3ed547b405507ebc6b">fewerElementsVectorMerge</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae18cc835581a3f8882d7725891b67e4e">fewerElementsVectorExtractInsertVectorElt</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0935a3e7269909f95115fb8452b1058c">equalizeVectorShuffleLengths</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equalize source and destination vector sizes of G_SHUFFLE_VECTOR. <a href="#a0935a3e7269909f95115fb8452b1058c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eb21f893b8039f4edcc3e3bce0c319e">reduceLoadStoreWidth</a> (GLoadStore &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ab7155d5feabf02f01c4d3b7d9c422">narrowScalarShiftByConstant</a> (MachineInstr &amp;MI, const APInt &amp;Amt, LLT HalfTy, LLT ShiftAmtTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd0c111e12b07d02698a1fdcba59b0d">fewerElementsVectorReductions</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6561daa27ec7fcc5335edb91ddae768">fewerElementsVectorSeqReductions</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e425f7e61cda2ed4db6054c39beb18">fewerElementsBitcast</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eac84349f5abc12d101036412730c5c">fewerElementsVectorShuffle</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f99d62852a3fab708983d8ea2139755">narrowScalarShift</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea9d2b3b2a626fb7c5093f5f8fa9cf95">narrowScalarAddSub</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT NarrowTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c0426a2303d102874f24e00608e3de4">narrowScalarMul</a> (MachineInstr &amp;MI, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687c20941b83380477f4a3d95ad4e390">narrowScalarFPTOI</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaec7c9b0ed49d3297c833d8d9def42c0">narrowScalarExtract</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43f277d8baa4b080bfd1beed8542bd6">narrowScalarInsert</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a4aeb9640ed05629f69b925f53ae366">narrowScalarBasic</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab483400178810f8c04f3ee4ebe5db4c9">narrowScalarExt</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6f143ae3ebc33b4f3f97e486bf7112">narrowScalarSelect</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25927a69e107ef1477822b884ca034b">narrowScalarCTLZ</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db1bc1a16d89298b92a13857146e28d">narrowScalarCTTZ</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048378560a1f3ddd48ddf9c60ae488f5">narrowScalarCTPOP</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad66885c64b6a5ee434c62d1583de8589">narrowScalarFLDEXP</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50dd9fe6220347f8306e3694a8129cb">bitcastExtractVectorElt</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT CastTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform Bitcast legalize action on G_EXTRACT_VECTOR_ELT. <a href="#ac50dd9fe6220347f8306e3694a8129cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a37f8fb6797142b53677bc4b59bf540">bitcastInsertVectorElt</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT CastTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform Bitcast legalize action on G_INSERT_VECTOR_ELT. <a href="#a0a37f8fb6797142b53677bc4b59bf540">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f5bc640bcfb6af808fee1216d3895d6">bitcastConcatVector</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT CastTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc9d5942b26515a4412b230f2672e647">bitcastShuffleVector</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT CastTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4871db57e613d42877b6c9e1b901f6be">bitcastExtractSubvector</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT CastTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This attempts to bitcast G_EXTRACT_SUBVECTOR to CastTy. <a href="#a4871db57e613d42877b6c9e1b901f6be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6988a4a2d7b33093620e7a456e811a4b">bitcastInsertSubvector</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT CastTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This attempts to bitcast G_INSERT_SUBVECTOR to CastTy. <a href="#a6988a4a2d7b33093620e7a456e811a4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefeacc46707017018d95faf6751da717">lowerConstant</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297f161b2970f693a98a4bf30c7eb630">lowerFConstant</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fb535803cbc7430528cdb19a157dd47">lowerBitcast</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dbb219846876149646e81e84ee81a47">lowerLoad</a> (GAnyLoad &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e2e64056fc2e2dabadfb9ceae338f6">lowerStore</a> (GStore &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9d961c3e0a9fa4c0e9ce806e972c4c">lowerBitCount</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332b012f0983179618526234e605c9aa">lowerFunnelShiftWithInverse</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7359ee87521122d9315cb47df7ec57c5">lowerFunnelShiftAsShifts</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6564387d7a51c85b557861c8f2d30ba">lowerFunnelShift</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40558d23c7bc31dd0b4f1d6b00199487">lowerEXT</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae51c8cf31e26c03753e3f6acb6f48d56">lowerTRUNC</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa30414996e4930e5be9e10e0bab811d0">lowerRotateWithReverseRotate</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5df097268459420f2dd52a648379463">lowerRotate</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5ad9f5de612dc98a4f3232a98ab754">lowerU64ToF32BitOps</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9599381b406afe38a263b028248e407">lowerU64ToF32WithSITOFP</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13531e23193d32ac81bdefa1db2ad987">lowerU64ToF64BitFloatOps</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba403eaa336a6c9d869717c9e54edd9c">lowerUITOFP</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a4f859f973b7f797f2d510c369980ad">lowerSITOFP</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f47636eb4667460ea08f358d6d39da">lowerFPTOUI</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99f92278021f1921be23b762056a9cc">lowerFPTOSI</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee5abf8664d1ea66e6d93fd6cf61065">lowerFPTOINT_SAT</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04ee040b3b0253a0832ddb7915d55ae1">lowerFPTRUNC_F64_TO_F16</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa03d66b30e1b6173c99b9a4266b7da9">lowerFPTRUNC</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84a1b0b6afe8ccff8b1c5fd66de228af">lowerFPOWI</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ddea5769637d54074168769084f404">lowerISFPCLASS</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a0bfc5807bbedc770b17d4691e3142">lowerThreewayCompare</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7287c6cc84f805db4ae46d581b4deecc">lowerMinMax</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc8c9b527c43cc36ac86886d18f00e4">lowerFCopySign</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105bd213837c5c2e30520113d885b8f3">lowerFMinNumMaxNum</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac36a82fb8a9d486c3b59ccab7769e4d">lowerFMad</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1422ed8c8a0aea2d84dc7e2f35d24874">lowerIntrinsicRound</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab031376e8eddaebf70d2cbcce069b4ba">lowerFFloor</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abce8515ac1fb3b6be13d5a39418847cb">lowerMergeValues</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6abe0f5db91bf445b3962dba969c5c7f">lowerUnmergeValues</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdcff9cc28cfffa71717b8d3c32c781">lowerExtractInsertVectorElt</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a vector extract or insert by writing the vector to a stack temporary and reloading the element or vector. <a href="#a2fdcff9cc28cfffa71717b8d3c32c781">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac7927a227a6c370e26ee82af77567d">lowerShuffleVector</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29774c06843a7c183ae3fd328d43bc8">lowerVECTOR_COMPRESS</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab95d4485884d2e093f534590f24cfe0d">getDynStackAllocTargetPtr</a> (Register SPReg, Register AllocSize, Align Alignment, LLT PtrTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b54c43cec90635e63e99f792b9207bc">lowerDynStackAlloc</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf3aec1c39ff3bf8683b13d186f5b617">lowerStackSave</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc929c22e98b3fab30eeec645ccb999a">lowerStackRestore</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76e5a8c6363a48b3ca4e924a8f59f0e5">lowerExtract</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a743aa32715279bdb86b53f20065950c9">lowerInsert</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545272144fee7632786d2fc0427ec6db">lowerSADDO_SSUBO</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813d1719803526d9839b4ae8d0a6b93d">lowerAddSubSatToMinMax</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6d16ec0f044086e929d63d532178bf">lowerAddSubSatToAddoSubo</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a7edf44feca96dfa6abdc4ae5d705d">lowerShlSat</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae62214791d9e4dcb2f7eda048092458f">lowerBswap</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed659cad017d524d63d763e19ef756f">lowerBitreverse</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76df0b752eddd8b0711d1af16a3658ad">lowerReadWriteRegister</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a84546a5ff646ed05b5772e00084db6">lowerSMULH_UMULH</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29042068469adc2859360985494dbb9">lowerSelect</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9b958e28468570d5cc74682e326f3b">lowerDIVREM</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f36be0b82249def611e5709ff7dd15">lowerAbsToAddXor</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f7e7a55fa5743fadeef838b7c9ece9">lowerAbsToMaxNeg</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41da6a2461e80e2d3b6b226281477bfa">lowerAbsToCNeg</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87cbc5eaa4440f62bdad70cce2296f3b">lowerFAbs</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e25418b93784160f4a660950f5fa806">lowerVectorReduction</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e30c8ffe7b84b2ca54cc12aabbe768">lowerMemcpyInline</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca820b14c7ae2e658cefd8a3be4da035">lowerMemCpyFamily</a> (MachineInstr &amp;MI, unsigned MaxLen=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9511578c9aa47dc8c5d7df3e9b623be3">lowerVAArg</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22804688cfeafb51c0c77b9478db1da1">widenScalarMergeValues</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT WideTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde517a7245357dab62a2592c0d61adb">widenScalarUnmergeValues</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT WideTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded61f7210de0bf2f93c8b9ebabd236d">widenScalarExtract</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT WideTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1dd017d8dc7e8787f611ffc5e4cbd40">widenScalarInsert</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT WideTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d4ed6e80d675d4709751e2a467592c">widenScalarAddSubOverflow</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT WideTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a723e3c31461b4484206915d1ecfa3786">widenScalarAddSubShlSat</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT WideTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ed4e6a9bfd3270a3ef5de186ec8ed0">widenScalarMulo</a> (MachineInstr &amp;MI, unsigned TypeIdx, LLT WideTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa82481b7d6e8565de31bfc00ab3101d6">insertParts</a> (Register DstReg, LLT ResultTy, LLT PartTy, ArrayRef&lt; Register &gt; PartRegs, LLT LeftoverTy=LLT(), ArrayRef&lt; Register &gt; LeftoverRegs={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to build a wide generic register <span class="doxyComputerOutput">DstReg</span> of type <span class="doxyComputerOutput">RegTy</span> from smaller parts. <a href="#aa82481b7d6e8565de31bfc00ab3101d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e5308413896e7a8bf9c7fb409a2cfe5">mergeMixedSubvectors</a> (Register DstReg, ArrayRef&lt; Register &gt; PartRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge <span class="doxyComputerOutput">PartRegs</span> with different types into <span class="doxyComputerOutput">DstReg</span>. <a href="#a3e5308413896e7a8bf9c7fb409a2cfe5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79a081ac765fe905177432422fde428">appendVectorElts</a> (SmallVectorImpl&lt; Register &gt; &amp;Elts, Register Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e66a1d57f8c9d7199a7ff8a6c4225a">extractGCDType</a> (SmallVectorImpl&lt; Register &gt; &amp;Parts, LLT DstTy, LLT NarrowTy, Register SrcReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unmerge <span class="doxyComputerOutput">SrcReg</span> into smaller sized values, and append them to <span class="doxyComputerOutput">Parts</span>. <a href="#a28e66a1d57f8c9d7199a7ff8a6c4225a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae135d7958df9bb50d4c13bdc533e3c33">extractGCDType</a> (SmallVectorImpl&lt; Register &gt; &amp;Parts, LLT GCDTy, Register SrcReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unmerge <span class="doxyComputerOutput">SrcReg</span> into <span class="doxyComputerOutput">GCDTy</span> typed registers. <a href="#ae135d7958df9bb50d4c13bdc533e3c33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe48c77dc4845bfcf8d3caade230465d">buildLCMMergePieces</a> (LLT DstTy, LLT NarrowTy, LLT GCDTy, SmallVectorImpl&lt; Register &gt; &amp;VRegs, unsigned PadStrategy=TargetOpcode::G_ANYEXT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce a merge of values in <span class="doxyComputerOutput">VRegs</span> to define <span class="doxyComputerOutput">DstReg</span>. <a href="#abe48c77dc4845bfcf8d3caade230465d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168e500e8c67d0a40c0c83933644a1f1">buildWidenedRemergeToDst</a> (Register DstReg, LLT LCMTy, ArrayRef&lt; Register &gt; RemergeRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the values in <span class="doxyComputerOutput">RemergeRegs</span> to an <span class="doxyComputerOutput">LCMTy</span> typed value. <a href="#a168e500e8c67d0a40c0c83933644a1f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b19d275bab47f74d90695f97bc550e5">multiplyRegisters</a> (SmallVectorImpl&lt; Register &gt; &amp;DstRegs, ArrayRef&lt; Register &gt; Src1Regs, ArrayRef&lt; Register &gt; Src2Regs, LLT NarrowTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform generic multiplication of values held in multiple registers. <a href="#a9b19d275bab47f74d90695f97bc550e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e436ca3addc49b0d2992e730c340df">changeOpcode</a> (MachineInstr &amp;MI, unsigned NewOpcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee7fe9cae519bdd0e377513a132a826">tryNarrowPow2Reduction</a> (MachineInstr &amp;MI, Register SrcReg, LLT SrcTy, LLT NarrowTy, unsigned ScalarOpc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadfe0fcfb9706ea40ffca7310671d7e4">lowerMemset</a> (MachineInstr &amp;MI, Register Dst, Register Val, uint64_t KnownLen, Align Alignment, bool IsVolatile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c3f48c25be63d1a637a01ea8d54dc9">lowerMemcpyInline</a> (MachineInstr &amp;MI, Register Dst, Register Src, uint64_t KnownLen, Align DstAlign, Align SrcAlign, bool IsVolatile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b29f154ef0a5f3d79384ae79e08428b">lowerMemcpy</a> (MachineInstr &amp;MI, Register Dst, Register Src, uint64_t KnownLen, uint64_t Limit, Align DstAlign, Align SrcAlign, bool IsVolatile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada5ffb602ee9242bde82ab21bc7e31d1">lowerMemmove</a> (MachineInstr &amp;MI, Register Dst, Register Src, uint64_t KnownLen, Align DstAlign, Align SrcAlign, bool IsVolatile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9711313d362123a5753bbf9e11e87c5">createGetStateLibcall</a> (MachineIRBuilder &amp;MIRBuilder, MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f63d865c7380365ac9112f22a97af3f">createSetStateLibcall</a> (MachineIRBuilder &amp;MIRBuilder, MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a1c31f58480869d68238838c32c9680">createResetStateLibcall</a> (MachineIRBuilder &amp;MIRBuilder, MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97444fdd32d8610e39f82294399f3adc">LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4597e902c58a7e7edfa7fc26f103c370">createFCMPLibcall</a> (MachineIRBuilder &amp;MIRBuilder, MachineInstr &amp;MI, LostDebugLocObserver &amp;LocObserver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f1199bf7af1596d93e9bcf6e3a53ccc">getNeutralElementForVecReduce</a> (unsigned Opcode, MachineIRBuilder &amp;MIRBuilder, LLT Ty)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expose MIRBuilder so clients can set their own RecordInsertInstruction functions. <a href="#ae50d11fc026093629c27142780ff1405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To keep track of changes made by the <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a>. <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7d8ceb9e3fc4f2394c7dffe8201e6d">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af30f3f8583797f392d039b50c47ebc">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed601381a5ccdbde58328fb872287c99">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb5536fead52e721fc5c416d1d738e6">KB</a></td>
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


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### LegalizeResult {#a97444fdd32d8610e39f82294399f3adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LegalizerHelper::LegalizeResult </td>
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
<td class="doxyEnumItemName">AlreadyLegal<a id="a97444fdd32d8610e39f82294399f3adca766fa3e68dde7dab82b6f063229a863f"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> was already legal and no change was made to the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Legalized<a id="a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> has been legalized and the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> changed</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnableToLegalize<a id="a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf"></a></td>
<td class="doxyEnumItemDescription">Some kind of error has occurred and we could not legalize this instruction</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LegalizerHelper() {#aa10024dcff51f09d4751794584609e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizerHelper (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a8ead1a81ece71a564c51ee5b5e9bd2f0">getLegalizerInfo</a>, <a href="#a6630af3b97791f4a324cd84f01911408">getTargetLowering</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>.</p>

</div>
</div>

### LegalizerHelper() {#a9006a4423b6daf984091f1b43e549f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizerHelper (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> * KB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a6630af3b97791f4a324cd84f01911408">getTargetLowering</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### bitcast() {#a6c12dbad109a5d725ce01a9a8363f948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::bitcast (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize an instruction by replacing the value type.</p>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a9f5bc640bcfb6af808fee1216d3895d6">bitcastConcatVector</a>, <a href="#aaa02ab5ab2c50cce96f4fec73c8186c3">bitcastDst</a>, <a href="#a4871db57e613d42877b6c9e1b901f6be">bitcastExtractSubvector</a>, <a href="#ac50dd9fe6220347f8306e3694a8129cb">bitcastExtractVectorElt</a>, <a href="#a6988a4a2d7b33093620e7a456e811a4b">bitcastInsertSubvector</a>, <a href="#a0a37f8fb6797142b53677bc4b59bf540">bitcastInsertVectorElt</a>, <a href="#acc9d5942b26515a4412b230f2672e647">bitcastShuffleVector</a>, <a href="#ad6cbca2857caf659c388e189c948a1fd">bitcastSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a42f1b2797add6ad1d60e895ad57ecf12">llvm::MachineMemOperand::clearRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3e9d2a9063bce7f5b3d7dd21fd05c79d">llvm::MachineMemOperand::getMemoryType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0204ff8c047858d1fb330cafa728b51e">llvm::MachineMemOperand::setType</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#af8ec769be431aa1296a7c786eb456f53">legalizeInstrStep</a>.</p>

</div>
</div>

### bitcastConcatVector() {#a9f5bc640bcfb6af808fee1216d3895d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::bitcastConcatVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> CastTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3768 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>.</p>

</div>
</div>

### bitcastDst() {#aaa02ab5ab2c50cce96f4fec73c8186c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::bitcastDst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> CastTy, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a def by inserting a G_BITCAST from <span class="doxyComputerOutput">CastTy</span>.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2066 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>.</p>

</div>
</div>

### bitcastExtractSubvector() {#a4871db57e613d42877b6c9e1b901f6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::bitcastExtractSubvector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> CastTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This attempts to bitcast G_EXTRACT_SUBVECTOR to CastTy.</p>


<p>&lt;vscale x 8 x i1&gt; = G_EXTRACT_SUBVECTOR &lt;vscale x 16 x i1&gt;, N</p>


<p>===&gt;</p>


<p>&lt;vscale x 2 x i1&gt; = G_BITCAST &lt;vscale x 16 x i1&gt; &lt;vscale x 1 x i8&gt; = G_EXTRACT_SUBVECTOR &lt;vscale x 2 x i1&gt;, N / 8 &lt;vscale x 8 x i1&gt; = G_BITCAST &lt;vscale x 1 x i8&gt;</p>


<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3847 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ae7510a639ca53c1bfa1c90c6dfc7eb2e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::divideCoefficientBy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>.</p>


<p>Referenced by <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>.</p>

</div>
</div>

### bitcastExtractVectorElt() {#ac50dd9fe6220347f8306e3694a8129cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::bitcastExtractVectorElt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> CastTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform Bitcast legalize action on G_EXTRACT_VECTOR_ELT.</p>


<p>Perform a G_EXTRACT_VECTOR_ELT in a different sized vector element.</p>


<p>If this is casting to a vector with a smaller element size, perform multiple element extracts and merge the results. If this is coercing to a vector with larger elements, index the bitcasted vector and extract the target element with bit operations. This is intended to force the indexing in the native register size for architectures that can dynamically index the register file.</p>


<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a5f65ab13a2645935d21a119b722a55a1">getBitcastWiderVectorElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae74a60e5edcee0609a1e4fddc62a8a01">llvm::LLT::scalarOrVector</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>.</p>

</div>
</div>

### bitcastInsertSubvector() {#a6988a4a2d7b33093620e7a456e811a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::bitcastInsertSubvector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> CastTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This attempts to bitcast G_INSERT_SUBVECTOR to CastTy.</p>


<p>&lt;vscale x 16 x i1&gt; = G_INSERT_SUBVECTOR &lt;vscale x 16 x i1&gt;, &lt;vscale x 8 x i1&gt;, N</p>


<p>===&gt;</p>


<p>&lt;vscale x 2 x i8&gt; = G_BITCAST &lt;vscale x 16 x i1&gt; &lt;vscale x 1 x i8&gt; = G_BITCAST &lt;vscale x 8 x i1&gt; &lt;vscale x 2 x i8&gt; = G_INSERT_SUBVECTOR &lt;vscale x 2 x i8&gt;, &lt;vscale x 1 x i8&gt;, N / 8 &lt;vscale x 16 x i1&gt; = G_BITCAST &lt;vscale x 2 x i8&gt;</p>


<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3910 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ae7510a639ca53c1bfa1c90c6dfc7eb2e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::divideCoefficientBy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>.</p>


<p>Referenced by <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>.</p>

</div>
</div>

### bitcastInsertVectorElt() {#a0a37f8fb6797142b53677bc4b59bf540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::bitcastInsertVectorElt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> CastTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform Bitcast legalize action on G_INSERT_VECTOR_ELT.</p>


<p>Perform a G_INSERT_VECTOR_ELT in a different sized vector element.</p>


<p>If this is increasing the element size, perform the indexing in the target element type, and use bit operations to insert at the element position. This is intended for architectures that can dynamically index the register file and want to force indexing in the native register size.</p>


<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3695 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2b99673a7e084ea8e75699f04b5f683a">buildBitFieldInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a5f65ab13a2645935d21a119b722a55a1">getBitcastWiderVectorElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>.</p>

</div>
</div>

### bitcastShuffleVector() {#acc9d5942b26515a4412b230f2672e647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::bitcastShuffleVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> CastTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3813 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>.</p>

</div>
</div>

### bitcastSrc() {#ad6cbca2857caf659c388e189c948a1fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::bitcastSrc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> CastTy, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a use by inserting a G_BITCAST to <span class="doxyComputerOutput">CastTy</span>.</p>

<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2061 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>.</p>

</div>
</div>

### coerceToScalar() {#acc6c42a7b5fe244fad430ca7df32d346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LegalizerHelper::coerceToScalar (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cast the given value to an <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">LLT::scalar</a> with an equivalent size.</p>


<p>Returns the register to use if an instruction was inserted. Returns the original register if no coercion was necessary.</p>


<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 1991 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#a6abe0f5db91bf445b3962dba969c5c7f">lowerUnmergeValues</a>.</p>

</div>
</div>

### createStackStoreLoad() {#a92bad93a924413adf3652db02e467a21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder LegalizerHelper::createStackStoreLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a store of <span class="doxyComputerOutput">Val</span> to a stack temporary and return a load as the same type as <span class="doxyComputerOutput">Res</span>.</p>

<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4708 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a576b964fe2d7d8750601681e04f05a9c">createStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a99fb11458708b57172b6b0df633fd4fc">llvm::SrcOp::getLLTTy</a>, <a href="#aee39b6aa6b9299acb9388393e34f3937">getStackTemporaryAlignment</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>

</div>
</div>

### createStackTemporary() {#a576b964fe2d7d8750601681e04f05a9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder LegalizerHelper::createStackTemporary (<a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Bytes, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; PtrInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a stack temporary based on the size in bytes and the alignment.</p>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4695 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>.</p>


<p>Referenced by <a href="#a92bad93a924413adf3652db02e467a21">createStackStoreLoad</a>, <a href="#a2fdcff9cc28cfffa71717b8d3c32c781">lowerExtractInsertVectorElt</a> and <a href="#ac29774c06843a7c183ae3fd328d43bc8">lowerVECTOR_COMPRESS</a>.</p>

</div>
</div>

### equalizeVectorShuffleLengths() {#a0935a3e7269909f95115fb8452b1058c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::equalizeVectorShuffleLengths (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Equalize source and destination vector sizes of G_SHUFFLE_VECTOR.</p>

<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6285 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb650e853db0ddbb60411b885c499737">llvm::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a25a4c14864c6f574bc99e19e15a8b4d2">moreElementsVectorDst</a>.</p>


<p>Referenced by <a href="#a1a3548d0921506d0cd736b7960c12485">moreElementsVectorShuffle</a>.</p>

</div>
</div>

### fewerElementsBitcast() {#a78e425f7e61cda2ed4db6054c39beb18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsBitcast (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5463 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>.</p>

</div>
</div>

### fewerElementsVector() {#aa8fe481cda91a90b364e410009785003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a vector instruction by splitting into multiple components, each acting on the same scalar type as the original but with fewer elements.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5288 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a78e425f7e61cda2ed4db6054c39beb18">fewerElementsBitcast</a>, <a href="#ae18cc835581a3f8882d7725891b67e4e">fewerElementsVectorExtractInsertVectorElt</a>, <a href="#abb2458b37415bd3ed547b405507ebc6b">fewerElementsVectorMerge</a>, <a href="#a8f6d92157833612e9b4cd0085e181b7e">fewerElementsVectorMultiEltType</a>, <a href="#a60e4161d46b020a55403acd13e31df9a">fewerElementsVectorPhi</a>, <a href="#addd0c111e12b07d02698a1fdcba59b0d">fewerElementsVectorReductions</a>, <a href="#ab6561daa27ec7fcc5335edb91ddae768">fewerElementsVectorSeqReductions</a>, <a href="#a1eac84349f5abc12d101036412730c5c">fewerElementsVectorShuffle</a>, <a href="#abce993680c63fae7b6cc5814e9b07826">fewerElementsVectorUnmergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h/#a42d8e909f2bea1119192cca95df057fa">GISEL_VECREDUCE_CASES_NONSEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a8eb21f893b8039f4edcc3e3bce0c319e">reduceLoadStoreWidth</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a1c822a5562978796947ffc71a1e9a1b0">anonymous{AArch64PostLegalizerLowering.cpp}::applyExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a> and <a href="#af8ec769be431aa1296a7c786eb456f53">legalizeInstrStep</a>.</p>

</div>
</div>

### fewerElementsVectorExtractInsertVectorElt() {#ae18cc835581a3f8882d7725891b67e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsVectorExtractInsertVectorElt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="#a2fdcff9cc28cfffa71717b8d3c32c781">lowerExtractInsertVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>.</p>

</div>
</div>

### fewerElementsVectorMerge() {#abb2458b37415bd3ed547b405507ebc6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsVectorMerge (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5033 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>.</p>

</div>
</div>

### fewerElementsVectorMultiEltType() {#a8f6d92157833612e9b4cd0085e181b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsVectorMultiEltType (<a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr">GenericMachineInstr</a> &amp; MI, unsigned NumElts, std::initializer_list&lt; unsigned &gt; NonVecOpIndices={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handles most opcodes.</p>


<p>Split <span class="doxyComputerOutput">MI</span> into same instruction on sub-vectors or scalars with <span class="doxyComputerOutput">NumElts</span> elements (1 for scalar). Supports uneven splits: there can be leftover sub-vector with fewer then <span class="doxyComputerOutput">NumElts</span> or a leftover scalar. To avoid this use moreElements first and set MI number of elements to multiple of <span class="doxyComputerOutput">NumElts</span>. Non-vector operands that should be used on all sub-instructions without split are listed in <span class="doxyComputerOutput">NonVecOpIndices</span>.</p>


<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4860 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a497ca5acebfbe31e76e7c05991519336">broadcastSrcOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4c0f443e3b75e7b2ffaf53d2ab73fc0">llvm::extractVectorParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aacaa5cd359fad565f73313045b5c83f0">hasSameNumEltsOnAllVectorOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a74212fb91857a365ae5c6c85a0646d97">makeDstOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>


<p>Referenced by <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>.</p>

</div>
</div>

### fewerElementsVectorPhi() {#a60e4161d46b020a55403acd13e31df9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsVectorPhi (<a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr">GenericMachineInstr</a> &amp; MI, unsigned NumElts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4931 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af4c0f443e3b75e7b2ffaf53d2ab73fc0">llvm::extractVectorParts</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0fab3e644b3457f90ed7f64876a037d2">llvm::MachineBasicBlock::getFirstTerminatorForward</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a74212fb91857a365ae5c6c85a0646d97">makeDstOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>.</p>

</div>
</div>

### fewerElementsVectorReductions() {#addd0c111e12b07d02698a1fdcba59b0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsVectorReductions (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5631 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>.</p>

</div>
</div>

### fewerElementsVectorSeqReductions() {#ab6561daa27ec7fcc5335edb91ddae768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsVectorSeqReductions (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5718 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>.</p>

</div>
</div>

### fewerElementsVectorShuffle() {#a1eac84349f5abc12d101036412730c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsVectorShuffle (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5493 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#adabd45e67a1847750a117317b5ef8f9f">llvm::LLT::changeElementCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a7df34dbf636f2fbbb00f2b86eccdb1eb">High</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>.</p>

</div>
</div>

### fewerElementsVectorUnmergeValues() {#abce993680c63fae7b6cc5814e9b07826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::fewerElementsVectorUnmergeValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4984 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>.</p>

</div>
</div>

### getDynStackAllocTargetPtr() {#ab95d4485884d2e093f534590f24cfe0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LegalizerHelper::getDynStackAllocTargetPtr (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SPReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> AllocSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> PtrTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8501 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8376734f311508662dd7e737752e5953">llvm::APInt::negate</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a0b54c43cec90635e63e99f792b9207bc">lowerDynStackAlloc</a>.</p>

</div>
</div>

### getKnownBits() {#ad0e092c7b577c4a6c2607581405d6a23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelKnownBits * llvm::LegalizerHelper::getKnownBits ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>.</p>

</div>
</div>

### getLegalizerInfo() {#a8ead1a81ece71a564c51ee5b5e9bd2f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo &amp; llvm::LegalizerHelper::getLegalizerInfo ()</td>
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

<p>Expose <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> so the clients can re-use.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>


<p>Referenced by <a href="#aa10024dcff51f09d4751794584609e85">LegalizerHelper</a>.</p>

</div>
</div>

### getStackTemporaryAlignment() {#aee39b6aa6b9299acb9388393e34f3937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align LegalizerHelper::getStackTemporaryAlignment (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Type, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> MinAlign=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the alignment to use for a stack temporary object with the given type.</p>

<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4684 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a59f98bbb1f440db8d5db1c8b5bd819f6">llvm::MinAlign</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a>.</p>


<p>Referenced by <a href="#a92bad93a924413adf3652db02e467a21">createStackStoreLoad</a>, <a href="#a2fdcff9cc28cfffa71717b8d3c32c781">lowerExtractInsertVectorElt</a> and <a href="#ac29774c06843a7c183ae3fd328d43bc8">lowerVECTOR_COMPRESS</a>.</p>

</div>
</div>

### getTargetLowering() {#a6630af3b97791f4a324cd84f01911408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering &amp; llvm::LegalizerHelper::getTargetLowering ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>


<p>Referenced by <a href="#a9006a4423b6daf984091f1b43e549f17">LegalizerHelper</a> and <a href="#aa10024dcff51f09d4751794584609e85">LegalizerHelper</a>.</p>

</div>
</div>

### getVectorElementPointer() {#ae91b4ff9d9c084c672f78adb9ed4006a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LegalizerHelper::getVectorElementPointer (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VecPtr, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> VecTy, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to vector element <span class="doxyComputerOutput">Index</span> located in memory for a vector of type <span class="doxyComputerOutput">VecTy</span> starting at a base address of <span class="doxyComputerOutput">VecPtr</span>.</p>


<p>If <span class="doxyComputerOutput">Index</span> is out of bounds the returned pointer is unspecified, but will be within the vector bounds.</p>


<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4743 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aaa6f42b31892a929914872c879e4b365">llvm::LLT::changeElementSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab16bdfa03e042a77b677e032fa495959">clampVectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>.</p>


<p>Referenced by <a href="#a2fdcff9cc28cfffa71717b8d3c32c781">lowerExtractInsertVectorElt</a>, <a href="#ac29774c06843a7c183ae3fd328d43bc8">lowerVECTOR_COMPRESS</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a28a0f1422b780a83a9632e5d46993dfc">llvm::CombinerHelper::matchCombineExtractedVectorLoad</a>.</p>

</div>
</div>

### legalizeInstrStep() {#af8ec769be431aa1296a7c786eb456f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::legalizeInstrStep (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace <span class="doxyComputerOutput">MI</span> by a sequence of legal instructions that can implement the same operation.</p>


<p>Note that this means <span class="doxyComputerOutput">MI</span> may be deleted, so any iterator steps should be performed before calling this function. <span class="doxyComputerOutput">Helper</span> should be initialized to the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> containing <span class="doxyComputerOutput">MI</span>.</p>


<p>Considered as an opaque blob, the legal code will use and define the same registers as <span class="doxyComputerOutput">MI</span>.</p>


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca766fa3e68dde7dab82b6f063229a863f">AlreadyLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654ac37bb600575f12795f12c117b2d86740">llvm::LegalizeActions::Bitcast</a>, <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654adbc4d3a46a3d7a515b5458a671394536">llvm::LegalizeActions::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a123b973f813232425a88cae2ef685a5a">llvm::LegalizeActions::FewerElements</a>, <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a1e5ed9cc15d3744694855efcdf0b948e">llvm::LegalizeActions::Libcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#aeaa43ab635ee98b9e2055d0f217558c2ad9dbfb96b7805fecf168bf553c423cce">libcall</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654af7c712e88ef2300e4bc43089d1cdf3e5">llvm::LegalizeActions::MoreElements</a>, <a href="#a2ffccbb574e8a2cf63b8ede89f53090b">moreElementsVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654ad0868c394d6503253b0d29c7e383e78b">llvm::LegalizeActions::NarrowScalar</a>, <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>, <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654aad899913ed8431ad4b1c81f717f7a909">llvm::LegalizeActions::WidenScalar</a> and <a href="#aacc36b9bbb74a3cdb987aa8f28b269e3">widenScalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a>.</p>

</div>
</div>

### libcall() {#ad8a495f4190353f60d1cd5e471283f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::libcall (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize an instruction by emiting a runtime library call instead.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a3918a234a708d84f71e7eb9c07cff516">conversionLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#af297fe5d0800d4319a7ca39cc7128f1a">getFloatTypeForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a316be66b059419e22aefc98fd49e1081">getRTLibDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a1e5ed9cc15d3744694855efcdf0b948e">llvm::LegalizeActions::Libcall</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a57a4c274fa487db3aa41be87d492e19b">simpleLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>

</div>
</div>

### lower() {#aa411af5653e9ed6cd4f664853b61bf0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lower (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize an instruction by splitting it into simpler parts, hopefully understood by the target.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4332 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1e6f0d8dfed0ab631b488a3e6317718e">llvm::APInt::getSignMask</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h/#a42d8e909f2bea1119192cca95df057fa">GISEL_VECREDUCE_CASES_NONSEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="#a21f36be0b82249def611e5709ff7dd15">lowerAbsToAddXor</a>, <a href="#aae6d16ec0f044086e929d63d532178bf">lowerAddSubSatToAddoSubo</a>, <a href="#a813d1719803526d9839b4ae8d0a6b93d">lowerAddSubSatToMinMax</a>, <a href="#a6fb535803cbc7430528cdb19a157dd47">lowerBitcast</a>, <a href="#a0b9d961c3e0a9fa4c0e9ce806e972c4c">lowerBitCount</a>, <a href="#a2ed659cad017d524d63d763e19ef756f">lowerBitreverse</a>, <a href="#ae62214791d9e4dcb2f7eda048092458f">lowerBswap</a>, <a href="#ace9b958e28468570d5cc74682e326f3b">lowerDIVREM</a>, <a href="#a0b54c43cec90635e63e99f792b9207bc">lowerDynStackAlloc</a>, <a href="#a40558d23c7bc31dd0b4f1d6b00199487">lowerEXT</a>, <a href="#a76e5a8c6363a48b3ca4e924a8f59f0e5">lowerExtract</a>, <a href="#a2fdcff9cc28cfffa71717b8d3c32c781">lowerExtractInsertVectorElt</a>, <a href="#a87cbc5eaa4440f62bdad70cce2296f3b">lowerFAbs</a>, <a href="#a297f161b2970f693a98a4bf30c7eb630">lowerFConstant</a>, <a href="#a9dc8c9b527c43cc36ac86886d18f00e4">lowerFCopySign</a>, <a href="#ab031376e8eddaebf70d2cbcce069b4ba">lowerFFloor</a>, <a href="#aac36a82fb8a9d486c3b59ccab7769e4d">lowerFMad</a>, <a href="#a105bd213837c5c2e30520113d885b8f3">lowerFMinNumMaxNum</a>, <a href="#a84a1b0b6afe8ccff8b1c5fd66de228af">lowerFPOWI</a>, <a href="#a3ee5abf8664d1ea66e6d93fd6cf61065">lowerFPTOINT_SAT</a>, <a href="#ab99f92278021f1921be23b762056a9cc">lowerFPTOSI</a>, <a href="#a64f47636eb4667460ea08f358d6d39da">lowerFPTOUI</a>, <a href="#aaa03d66b30e1b6173c99b9a4266b7da9">lowerFPTRUNC</a>, <a href="#aa6564387d7a51c85b557861c8f2d30ba">lowerFunnelShift</a>, <a href="#a743aa32715279bdb86b53f20065950c9">lowerInsert</a>, <a href="#a1422ed8c8a0aea2d84dc7e2f35d24874">lowerIntrinsicRound</a>, <a href="#a79ddea5769637d54074168769084f404">lowerISFPCLASS</a>, <a href="#a1dbb219846876149646e81e84ee81a47">lowerLoad</a>, <a href="#aca820b14c7ae2e658cefd8a3be4da035">lowerMemCpyFamily</a>, <a href="#abce8515ac1fb3b6be13d5a39418847cb">lowerMergeValues</a>, <a href="#a7287c6cc84f805db4ae46d581b4deecc">lowerMinMax</a>, <a href="#a76df0b752eddd8b0711d1af16a3658ad">lowerReadWriteRegister</a>, <a href="#ac5df097268459420f2dd52a648379463">lowerRotate</a>, <a href="#a545272144fee7632786d2fc0427ec6db">lowerSADDO_SSUBO</a>, <a href="#ad29042068469adc2859360985494dbb9">lowerSelect</a>, <a href="#a00a7edf44feca96dfa6abdc4ae5d705d">lowerShlSat</a>, <a href="#abac7927a227a6c370e26ee82af77567d">lowerShuffleVector</a>, <a href="#a0a4f859f973b7f797f2d510c369980ad">lowerSITOFP</a>, <a href="#a1a84546a5ff646ed05b5772e00084db6">lowerSMULH_UMULH</a>, <a href="#adc929c22e98b3fab30eeec645ccb999a">lowerStackRestore</a>, <a href="#adf3aec1c39ff3bf8683b13d186f5b617">lowerStackSave</a>, <a href="#a40e2e64056fc2e2dabadfb9ceae338f6">lowerStore</a>, <a href="#a04a0bfc5807bbedc770b17d4691e3142">lowerThreewayCompare</a>, <a href="#ae51c8cf31e26c03753e3f6acb6f48d56">lowerTRUNC</a>, <a href="#aba403eaa336a6c9d869717c9e54edd9c">lowerUITOFP</a>, <a href="#a6abe0f5db91bf445b3962dba969c5c7f">lowerUnmergeValues</a>, <a href="#a9511578c9aa47dc8c5d7df3e9b623be3">lowerVAArg</a>, <a href="#ac29774c06843a7c183ae3fd328d43bc8">lowerVECTOR_COMPRESS</a>, <a href="#a8e25418b93784160f4a660950f5fa806">lowerVectorReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a13a6a6b42a21b2d435af5a2ef097f694">anonymous{AArch64PostLegalizerLowering.cpp}::applyVectorSextInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a> and <a href="#af8ec769be431aa1296a7c786eb456f53">legalizeInstrStep</a>.</p>

</div>
</div>

### lowerAbsToAddXor() {#a21f36be0b82249def611e5709ff7dd15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerAbsToAddXor (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9320 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerAbsToCNeg() {#a41da6a2461e80e2d3b6b226281477bfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerAbsToCNeg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9352 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#a14251e7cc7c001be8b83a76caa7acd92">llvm::AArch64LegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### lowerAbsToMaxNeg() {#a34f7e7a55fa5743fadeef838b7c9ece9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerAbsToMaxNeg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9337 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### lowerAddSubSatToAddoSubo() {#aae6d16ec0f044086e929d63d532178bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerAddSubSatToAddoSubo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8828 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerAddSubSatToMinMax() {#a813d1719803526d9839b4ae8d0a6b93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerAddSubSatToMinMax (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8753 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerBitcast() {#a6fb535803cbc7430528cdb19a157dd47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerBitcast (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a944828d894ed9e13fbdfac2652d88745">getUnmergePieces</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerBitCount() {#a0b9d961c3e0a9fa4c0e9ce806e972c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerBitCount (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6984 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654adbc4d3a46a3d7a515b5458a671394536">llvm::LegalizeActions::Custom</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8c55d8510ad4b7cb957d8f5a7cd6944e">llvm::APInt::getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a1e5ed9cc15d3744694855efcdf0b948e">llvm::LegalizeActions::Libcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654aad899913ed8431ad4b1c81f717f7a909">llvm::LegalizeActions::WidenScalar</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerBitreverse() {#a2ed659cad017d524d63d763e19ef756f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerBitreverse (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8970 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a8c55d8510ad4b7cb957d8f5a7cd6944e">llvm::APInt::getSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a7d7927ce19d14acc525d683585b8c58d">SwapN</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerBswap() {#ae62214791d9e4dcb2f7eda048092458f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerBswap (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8925 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerConstant() {#aefeacc46707017018d95faf6751da717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3445 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a29e05cd075864928ae65e1751fdc346e">llvm::MachineOperand::getCImm</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### lowerDIVREM() {#ace9b958e28468570d5cc74682e326f3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerDIVREM (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9303 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerDynStackAlloc() {#a0b54c43cec90635e63e99f792b9207bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerDynStackAlloc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad4b2e7a84faf3d7b6ffb84b541358e00">llvm::assumeAligned</a>, <a href="#ab95d4485884d2e093f534590f24cfe0d">getDynStackAllocTargetPtr</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50ca5a5dea77f2a0aaffed9741ae04e8d865">llvm::TargetFrameLowering::StackGrowsUp</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerEXT() {#a40558d23c7bc31dd0b4f1d6b00199487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerEXT (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7287 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#adabd45e67a1847750a117317b5ef8f9f">llvm::LLT::changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aaa6f42b31892a929914872c879e4b365">llvm::LLT::changeElementSize</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ae7510a639ca53c1bfa1c90c6dfc7eb2e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::divideCoefficientBy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerExtract() {#a76e5a8c6363a48b3ca4e924a8f59f0e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerExtract (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8570 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerExtractInsertVectorElt() {#a2fdcff9cc28cfffa71717b8d3c32c781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerExtractInsertVectorElt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lower a vector extract or insert by writing the vector to a stack temporary and reloading the element or vector.</p>


<p>dst = G_EXTRACT_VECTOR_ELT vec, idx =&gt; stack_temp = G_FRAME_INDEX G_STORE vec, stack_temp idx = clamp(idx, vec.getNumElements()) element_ptr = G_PTR_ADD stack_temp, idx dst = G_LOAD element_ptr</p>


<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a>, <a href="#a576b964fe2d7d8750601681e04f05a9c">createStackTemporary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae456a811703836ee5d9e32c3e51a15b6">llvm::LLT::getSizeInBytes</a>, <a href="#aee39b6aa6b9299acb9388393e34f3937">getStackTemporaryAlignment</a>, <a href="#ae91b4ff9d9c084c672f78adb9ed4006a">getVectorElementPointer</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a9459055a98e20980521289e8d20fcc7e">llvm::MachinePointerInfo::getWithOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a8b8f5d788ec31cd57f429ce38b5e3bb7">llvm::LLT::isByteSized</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a441b9fc17e390be4c8dc6a1f1dd3d424">llvm::MIPatternMatch::m_ICst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#ae18cc835581a3f8882d7725891b67e4e">fewerElementsVectorExtractInsertVectorElt</a> and <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFAbs() {#a87cbc5eaa4440f62bdad70cce2296f3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFAbs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9364 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFConstant() {#a297f161b2970f693a98a4bf30c7eb630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3456 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aee59c647052fc9557561e596681da3c0">llvm::MachineOperand::getFPImm</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFCopySign() {#a9dc8c9b527c43cc36ac86886d18f00e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFCopySign (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8083 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518ab9f2d292718c407a75b2f2c829c1c874">llvm::MachineInstr::Disjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1e6f0d8dfed0ab631b488a3e6317718e">llvm::APInt::getSignMask</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFFloor() {#ab031376e8eddaebf70d2cbcce069b4ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFFloor (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFMad() {#aac36a82fb8a9d486c3b59ccab7769e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFMad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4774d239d20e55380840e775aed66efc">llvm::AMDGPULegalizerInfo::legalizeFMad</a> and <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFMinNumMaxNum() {#a105bd213837c5c2e30520113d885b8f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFMinNumMaxNum (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518aba11aa58176a446ba70d4f0ad0e04418">llvm::MachineInstr::FmNoNans</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acbbab4f4f342da97b2f73b4b1fedc983">llvm::isKnownNeverSNaN</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a91b85787aa32d7f1f0d38d59a77cee68">llvm::AMDGPULegalizerInfo::legalizeMinNumMaxNum</a> and <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFPOWI() {#a84a1b0b6afe8ccff8b1c5fd66de228af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFPOWI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7997 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFPTOINT\_SAT() {#a3ee5abf8664d1ea66e6d93fd6cf61065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFPTOINT_SAT (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7770 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a7a046fe3d1230e4804494ce18bae1175">llvm::APFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518aba11aa58176a446ba70d4f0ad0e04418">llvm::MachineInstr::FmNoNans</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25ebf05ccdc20f3355715fb29ee82427">llvm::getFltSemanticForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aaba98149aef517089f9868bde5b8c41bc">llvm::APFloatBase::opInexact</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFPTOSI() {#ab99f92278021f1921be23b762056a9cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFPTOSI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7705 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faf5ccb8d51ca38e2f3329955fc0149cd4">llvm::Exponent</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1e6f0d8dfed0ab631b488a3e6317718e">llvm::APInt::getSignMask</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFPTOUI() {#a64f47636eb4667460ea08f358d6d39da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFPTOUI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7665 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a7a046fe3d1230e4804494ce18bae1175">llvm::APFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1e6f0d8dfed0ab631b488a3e6317718e">llvm::APInt::getSignMask</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFPTRUNC() {#aaa03d66b30e1b6173c99b9a4266b7da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFPTRUNC (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7986 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a04ee040b3b0253a0832ddb7915d55ae1">lowerFPTRUNC_F64_TO_F16</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#acd57bd926bf1c8815e21e1291a54d151">S16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFPTRUNC\_F64\_TO\_F16() {#a04ee040b3b0253a0832ddb7915d55ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFPTRUNC_F64_TO_F16 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7871 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aaa03d66b30e1b6173c99b9a4266b7da9">lowerFPTRUNC</a>.</p>

</div>
</div>

### lowerFunnelShift() {#aa6564387d7a51c85b557861c8f2d30ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFunnelShift (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerFunnelShiftAsShifts() {#a7359ee87521122d9315cb47df7ec57c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFunnelShiftAsShifts (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aced5d43b6a199d148e877d5536e95739">isNonZeroModBitWidthOrUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### lowerFunnelShiftWithInverse() {#a332b012f0983179618526234e605c9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerFunnelShiftWithInverse (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aced5d43b6a199d148e877d5536e95739">isNonZeroModBitWidthOrUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### lowerInsert() {#a743aa32715279bdb86b53f20065950c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerInsert (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8624 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ac33fa4c8cfeb9287f51f95404a459de8">llvm::LLT::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af3bee3e462a14abdf3858c354a5cd222">llvm::APInt::getBitsSetWithWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerIntrinsicRound() {#a1422ed8c8a0aea2d84dc7e2f35d24874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerIntrinsicRound (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerISFPCLASS() {#a79ddea5769637d54074168769084f404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerISFPCLASS (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9072 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabf7829a22591343ad790b1357955a7df">llvm::fcAllFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da3cf35410333eec89d6a707787b5f9d97">llvm::fcFinite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da00a4419741933f5cb7ec001aaa6e6bb5">llvm::fcInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da75a5f5e11ee279c94146d767d3b0a631">llvm::fcNegFinite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab003a118cd0b76a814ba4dfc7077034a">llvm::fcNegNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da023ad3d9b33a1af5eb90b8b543fb3ccb">llvm::fcNegSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da4759a508982cd525d9f17024f09aea22">llvm::fcNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dadb8c9ce3197adf47c7f889bab120b77c">llvm::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1daade2c185d2f6d759a0f2c1a2b7d956ba">llvm::fcPosFinite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dada0d259988860d7a2f882aa40b25fee1">llvm::fcPosInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da052ace75708c251359ff22dd036417a6">llvm::fcPosNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dad0940edb5f5bf512669b72928b527d0c">llvm::fcPosSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da7ace586671df3e62fa392d5144a8b3da">llvm::fcPosZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da05bb099c0a65e5b835ed8cd0b326df7c">llvm::fcQNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da449c8fca7f540cc314102a67944fcd6e">llvm::fcSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab6ede72b2b2219068b9bb89732d24e2f">llvm::fcZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25ebf05ccdc20f3355715fb29ee82427">llvm::getFltSemanticForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aaa67fe0741c2b3712630ae636f8c2c20">llvm::APFloat::getLargest</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1e6f0d8dfed0ab631b488a3e6317718e">llvm::APInt::getSignMask</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerLoad() {#a1dbb219846876149646e81e84ee81a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerLoad (<a href="/web-llvm/docs/api/classes/llvm/ganyload">GAnyLoad</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 3967 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae22967d11b695d268992470debfae4b2">llvm::bit_floor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/ganyload/#a4fe5ff0257f5b8749cbe223b848b2570">llvm::GAnyLoad::getDstReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3e9d2a9063bce7f5b3d7dd21fd05c79d">llvm::MachineMemOperand::getMemoryType</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a130e12a0a8b3fe8149fe7b5eecfa603e">llvm::GMemOperation::getMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaf6610b5b6565e4f1b56ca78c804654f">llvm::MachineMemOperand::getPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae456a811703836ee5d9e32c3e51a15b6">llvm::LLT::getSizeInBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a>, <a href="#a8eb21f893b8039f4edcc3e3bce0c319e">reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerMemCpyFamily() {#aca820b14c7ae2e658cefd8a3be4da035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerMemCpyFamily (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned MaxLen=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9922 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a755eb2d2f25e8da3b2d904146e61b1a5">shouldLowerMemFuncForSize</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae1fd41e303fcb42122f8a0432efcd87d">llvm::CombinerHelper::tryCombineMemCpyFamily</a>.</p>

</div>
</div>

### lowerMemcpyInline() {#a70e30c8ffe7b84b2ca54cc12aabbe768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerMemcpyInline (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9669 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### lowerMergeValues() {#abce8515ac1fb3b6be13d5a39418847cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerMergeValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerMinMax() {#a7287c6cc84f805db4ae46d581b4deecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerMinMax (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8022 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#aaa6f42b31892a929914872c879e4b365">llvm::LLT::changeElementSize</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a96bf442f65306b9a5ffda8ca473f0ce1">minMaxToCompare</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerReadWriteRegister() {#a76df0b752eddd8b0711d1af16a3658ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerReadWriteRegister (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9024 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#ae44259d9edd71181ea8b89d18f27a967">llvm::MDString::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerRotate() {#ac5df097268459420f2dd52a648379463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerRotate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7398 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerRotateWithReverseRotate() {#aa30414996e4930e5be9e10e0bab811d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerRotateWithReverseRotate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7387 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>

</div>
</div>

### lowerSADDO\_SSUBO() {#a545272144fee7632786d2fc0427ec6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerSADDO_SSUBO (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8714 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerSelect() {#ad29042068469adc2859360985494dbb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerShlSat() {#a00a7edf44feca96dfa6abdc4ae5d705d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerShlSat (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8894 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerShuffleVector() {#abac7927a227a6c370e26ee82af77567d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerShuffleVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerSITOFP() {#a0a4f859f973b7f797f2d510c369980ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerSITOFP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7622 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerSMULH\_UMULH() {#a1a84546a5ff646ed05b5772e00084db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerSMULH_UMULH (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9050 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#aaa6f42b31892a929914872c879e4b365">llvm::LLT::changeElementSize</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerStackRestore() {#adc929c22e98b3fab30eeec645ccb999a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerStackRestore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerStackSave() {#adf3aec1c39ff3bf8683b13d186f5b617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerStackSave (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8548 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerStore() {#a40e2e64056fc2e2dabadfb9ceae338f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerStore (<a href="/web-llvm/docs/api/classes/llvm/gstore">GStore</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae22967d11b695d268992470debfae4b2">llvm::bit_floor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3e9d2a9063bce7f5b3d7dd21fd05c79d">llvm::MachineMemOperand::getMemoryType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaf6610b5b6565e4f1b56ca78c804654f">llvm::MachineMemOperand::getPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae456a811703836ee5d9e32c3e51a15b6">llvm::LLT::getSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/gstore/#ab80d0571fdf63877734e0f7bea4e886b">llvm::GStore::getValueReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa5ff177bc1498508696aaf27235db3fc">llvm::MachineInstr::memoperands_begin</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a>, <a href="#a8eb21f893b8039f4edcc3e3bce0c319e">reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="#a6d8b5e9460092c4517e5e594756fcb82">scalarizeVectorBooleanStore</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerThreewayCompare() {#a04a0bfc5807bbedc770b17d4691e3142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerThreewayCompare (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8036 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aaa6f42b31892a929914872c879e4b365">llvm::LLT::changeElementSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c2999836b5dd4ca2d272970cc0b9a0f">llvm::getApproximateEVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a145391af8fd5e5455ffa3170c2d701ce">llvm::TargetLoweringBase::UndefinedBooleanContent</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa61af767c51a95e2dd0dff2001168755a695a19c9c3ae14638be151add82755cb">llvm::TargetLoweringBase::ZeroOrNegativeOneBooleanContent</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerTRUNC() {#ae51c8cf31e26c03753e3f6acb6f48d56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerTRUNC (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#adabd45e67a1847750a117317b5ef8f9f">llvm::LLT::changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aaa6f42b31892a929914872c879e4b365">llvm::LLT::changeElementSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600clausemergepass-cpp/#aba99928790de45fa7aa12b47fbd828ff">Merge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerU64ToF32BitOps() {#a9b5ad9f5de612dc98a4f3232a98ab754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerU64ToF32BitOps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7468 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### lowerU64ToF32WithSITOFP() {#ac9599381b406afe38a263b028248e407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerU64ToF32WithSITOFP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7526 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#aba403eaa336a6c9d869717c9e54edd9c">lowerUITOFP</a>.</p>

</div>
</div>

### lowerU64ToF64BitFloatOps() {#a13531e23193d32ac81bdefa1db2ad987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerU64ToF64BitFloatOps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7561 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#aba403eaa336a6c9d869717c9e54edd9c">lowerUITOFP</a>.</p>

</div>
</div>

### lowerUITOFP() {#aba403eaa336a6c9d869717c9e54edd9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerUITOFP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 7595 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="#ac9599381b406afe38a263b028248e407">lowerU64ToF32WithSITOFP</a>, <a href="#a13531e23193d32ac81bdefa1db2ad987">lowerU64ToF64BitFloatOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerUnmergeValues() {#a6abe0f5db91bf445b3962dba969c5c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerUnmergeValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#acc6c42a7b5fe244fad430ca7df32d346">coerceToScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerVAArg() {#a9511578c9aa47dc8c5d7df3e9b623be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerVAArg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9399 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a0911ef4a610d70c5104c1932fec0e1">llvm::getTypeForLLT</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerVECTOR\_COMPRESS() {#ac29774c06843a7c183ae3fd328d43bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerVECTOR_COMPRESS (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 8415 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a576b964fe2d7d8750601681e04f05a9c">createStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#aee39b6aa6b9299acb9388393e34f3937">getStackTemporaryAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#aa5f0f4a7de5def1c9d9f6a750a9b1aa1">llvm::MachinePointerInfo::getUnknownStack</a>, <a href="#ae91b4ff9d9c084c672f78adb9ed4006a">getVectorElementPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a496914f81c80c3adc8866dec3586859d">llvm::isConstantOrConstantSplatVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### lowerVectorReduction() {#a8e25418b93784160f4a660950f5fa806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerVectorReduction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>.</p>

</div>
</div>

### moreElementsVector() {#a2ffccbb574e8a2cf63b8ede89f53090b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::moreElementsVector (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MoreTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a vector instruction by increasing the number of vector elements involved and ignoring the added elements later.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6032 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#adabd45e67a1847750a117317b5ef8f9f">llvm::LLT::changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a79ea372f9aa69492fccfafc0e5a1589c">llvm::ElementCount::get</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a8028200b9efbd55fe7db4c69199893d2">llvm::LLT::isScalable</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#a25a4c14864c6f574bc99e19e15a8b4d2">moreElementsVectorDst</a>, <a href="#a98e3f12f0b3d7f35251e1e71336b480c">moreElementsVectorPhi</a>, <a href="#a1a3548d0921506d0cd736b7960c12485">moreElementsVectorShuffle</a>, <a href="#ac465c012a999bcab06235573fcb0860f">moreElementsVectorSrc</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#af8ec769be431aa1296a7c786eb456f53">legalizeInstrStep</a>.</p>

</div>
</div>

### moreElementsVectorDst() {#a25a4c14864c6f574bc99e19e15a8b4d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::moreElementsVectorDst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MoreTy, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a Def by performing it with additional vector elements and extracting the result elements, and replacing the vreg of the operand in place.</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2044 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="#a0935a3e7269909f95115fb8452b1058c">equalizeVectorShuffleLengths</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>, <a href="#a2ffccbb574e8a2cf63b8ede89f53090b">moreElementsVector</a>, <a href="#a98e3f12f0b3d7f35251e1e71336b480c">moreElementsVectorPhi</a> and <a href="#a1a3548d0921506d0cd736b7960c12485">moreElementsVectorShuffle</a>.</p>

</div>
</div>

### moreElementsVectorPhi() {#a98e3f12f0b3d7f35251e1e71336b480c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::moreElementsVectorPhi (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MoreTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5976 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a7f0521fa2de44271fd4b909ea7351ef3">llvm::MachineBasicBlock::getFirstTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#a25a4c14864c6f574bc99e19e15a8b4d2">moreElementsVectorDst</a>, <a href="#ac465c012a999bcab06235573fcb0860f">moreElementsVectorSrc</a> and <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>.</p>


<p>Referenced by <a href="#a2ffccbb574e8a2cf63b8ede89f53090b">moreElementsVector</a>.</p>

</div>
</div>

### moreElementsVectorShuffle() {#a1a3548d0921506d0cd736b7960c12485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::moreElementsVectorShuffle (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MoreTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="#a0935a3e7269909f95115fb8452b1058c">equalizeVectorShuffleLengths</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#a25a4c14864c6f574bc99e19e15a8b4d2">moreElementsVectorDst</a>, <a href="#ac465c012a999bcab06235573fcb0860f">moreElementsVectorSrc</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a2ffccbb574e8a2cf63b8ede89f53090b">moreElementsVector</a>.</p>

</div>
</div>

### moreElementsVectorSrc() {#ac465c012a999bcab06235573fcb0860f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::moreElementsVectorSrc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MoreTy, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> by producing a vector with undefined high elements, extracting the original vector type, and replacing the vreg of the operand in place.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2054 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="#a2ffccbb574e8a2cf63b8ede89f53090b">moreElementsVector</a>, <a href="#a98e3f12f0b3d7f35251e1e71336b480c">moreElementsVectorPhi</a> and <a href="#a1a3548d0921506d0cd736b7960c12485">moreElementsVectorShuffle</a>.</p>

</div>
</div>

### narrowScalar() {#a6701d040466d73f3dc51481d3186c294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalar (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize an instruction by reducing the width of the underlying scalar type.</p>

<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0fab3e644b3457f90ed7f64876a037d2">llvm::MachineBasicBlock::getFirstTerminatorForward</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abcceb535a4bb1e23c320e7628476bd5d">llvm::MachineMemOperand::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#af07a09f1cda33d984cc725dc9e856d40">llvm::ICmpInst::getUnsignedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#aea9d2b3b2a626fb7c5093f5f8fa9cf95">narrowScalarAddSub</a>, <a href="#a8a4aeb9640ed05629f69b925f53ae366">narrowScalarBasic</a>, <a href="#ae25927a69e107ef1477822b884ca034b">narrowScalarCTLZ</a>, <a href="#a048378560a1f3ddd48ddf9c60ae488f5">narrowScalarCTPOP</a>, <a href="#a2db1bc1a16d89298b92a13857146e28d">narrowScalarCTTZ</a>, <a href="#ad7f8e31fdc4b07d287c52567a2d259f4">narrowScalarDst</a>, <a href="#ab483400178810f8c04f3ee4ebe5db4c9">narrowScalarExt</a>, <a href="#aaec7c9b0ed49d3297c833d8d9def42c0">narrowScalarExtract</a>, <a href="#ad66885c64b6a5ee434c62d1583de8589">narrowScalarFLDEXP</a>, <a href="#a687c20941b83380477f4a3d95ad4e390">narrowScalarFPTOI</a>, <a href="#ad43f277d8baa4b080bfd1beed8542bd6">narrowScalarInsert</a>, <a href="#a0c0426a2303d102874f24e00608e3de4">narrowScalarMul</a>, <a href="#a8f6f143ae3ebc33b4f3f97e486bf7112">narrowScalarSelect</a>, <a href="#a2f99d62852a3fab708983d8ea2139755">narrowScalarShift</a>, <a href="#a5cafcb9996d69b6f864daa6c7d00c48a">narrowScalarSrc</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a8eb21f893b8039f4edcc3e3bce0c319e">reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>, <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a1e12ed6a5b2d3f3dd790e2c48f7d7906">llvm::MipsRegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a> and <a href="#af8ec769be431aa1296a7c786eb456f53">legalizeInstrStep</a>.</p>

</div>
</div>

### narrowScalarAddSub() {#aea9d2b3b2a626fb7c5093f5f8fa9cf95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarAddSub (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarBasic() {#a8a4aeb9640ed05629f69b925f53ae366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarBasic (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6762 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarCTLZ() {#ae25927a69e107ef1477822b884ca034b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarCTLZ (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6870 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarCTPOP() {#a048378560a1f3ddd48ddf9c60ae488f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarCTPOP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6936 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarCTTZ() {#a2db1bc1a16d89298b92a13857146e28d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarCTTZ (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6903 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarDst() {#ad7f8e31fdc4b07d287c52567a2d259f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::narrowScalarDst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy, unsigned OpIdx, unsigned ExtOpcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2035 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a> and <a href="#a687c20941b83380477f4a3d95ad4e390">narrowScalarFPTOI</a>.</p>

</div>
</div>

### narrowScalarExt() {#ab483400178810f8c04f3ee4ebe5db4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarExt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6803 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarExtract() {#aaec7c9b0ed49d3297c833d8d9def42c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarExtract (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6611 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarFLDEXP() {#ad66885c64b6a5ee434c62d1583de8589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarFLDEXP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6959 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08b6d5c69d7933ac65aae84e1b50fa62">llvm::maxIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9a9168454d9535e1d4ef88fb4a3592d">llvm::minIntN</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarFPTOI() {#a687c20941b83380477f4a3d95ad4e390}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarFPTOI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6586 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ad7f8e31fdc4b07d287c52567a2d259f4">narrowScalarDst</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarInsert() {#ad43f277d8baa4b080bfd1beed8542bd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarInsert (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6679 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarMul() {#a0c0426a2303d102874f24e00608e3de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarMul (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6556 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarSelect() {#a8f6f143ae3ebc33b4f3f97e486bf7112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6824 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarShift() {#a2f99d62852a3fab708983d8ea2139755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarShift (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5867 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#a79ab7155d5feabf02f01c4d3b7d9c422">narrowScalarShiftByConstant</a>, <a href="#a5cafcb9996d69b6f864daa6c7d00c48a">narrowScalarSrc</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### narrowScalarShiftByConstant() {#a79ab7155d5feabf02f01c4d3b7d9c422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::narrowScalarShiftByConstant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Amt, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> HalfTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ShiftAmtTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5778 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a>.</p>


<p>Referenced by <a href="#a2f99d62852a3fab708983d8ea2139755">narrowScalarShift</a>.</p>

</div>
</div>

### narrowScalarSrc() {#a5cafcb9996d69b6f864daa6c7d00c48a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::narrowScalarSrc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> by truncating the operand's type to <span class="doxyComputerOutput">NarrowTy</span> using G_TRUNC, and replacing the vreg of the operand in place.</p>

<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2019 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a> and <a href="#a2f99d62852a3fab708983d8ea2139755">narrowScalarShift</a>.</p>

</div>
</div>

### reduceLoadStoreWidth() {#a8eb21f893b8039f4edcc3e3bce0c319e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::reduceLoadStoreWidth (<a href="/web-llvm/docs/api/classes/llvm/gloadstore">GLoadStore</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a515116c40bd191aee04f328b504d5692">llvm::GMemOperation::getMemSize</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a130e12a0a8b3fe8149fe7b5eecfa603e">llvm::GMemOperation::getMMO</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a9c309120c87f6a16704169f193bfc711">llvm::GMemOperation::isAtomic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#aad6842fbf58844d974611a4915a00aae">isBigEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="#aa8fe481cda91a90b364e410009785003">fewerElementsVector</a>, <a href="#a1dbb219846876149646e81e84ee81a47">lowerLoad</a>, <a href="#a40e2e64056fc2e2dabadfb9ceae338f6">lowerStore</a> and <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>.</p>

</div>
</div>

### scalarizeVectorBooleanStore() {#a6d8b5e9460092c4517e5e594756fcb82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::scalarizeVectorBooleanStore (<a href="/web-llvm/docs/api/classes/llvm/gstore">GStore</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a store of a boolean vector, scalarize it.</p>

<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45e006fa9af3ebf9405bb3154f70f9af">llvm::getLLTForMVT</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3e9d2a9063bce7f5b3d7dd21fd05c79d">llvm::MachineMemOperand::getMemoryType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaf6610b5b6565e4f1b56ca78c804654f">llvm::MachineMemOperand::getPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gstore/#ab80d0571fdf63877734e0f7bea4e886b">llvm::GStore::getValueReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a84c1d72001dd5f34d9a55b3a7bb8a474">llvm::DataLayout::isBigEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a8b8f5d788ec31cd57f429ce38b5e3bb7">llvm::LLT::isByteSized</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa5ff177bc1498508696aaf27235db3fc">llvm::MachineInstr::memoperands_begin</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>.</p>


<p>Referenced by <a href="#a40e2e64056fc2e2dabadfb9ceae338f6">lowerStore</a>.</p>

</div>
</div>

### widenScalar() {#aacc36b9bbb74a3cdb987aa8f28b269e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::widenScalar (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize an instruction by performing the operation on a wider scalar type (for example a 16-bit addition can be safely performed at 32-bits precision, ignoring the unused bits).</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2605 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c2999836b5dd4ca2d272970cc0b9a0f">llvm::getApproximateEVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertsubvector/#a7f5a93aed60bbe1badb84e5e06f46b31">llvm::GInsertSubvector::getBigVec</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a29e05cd075864928ae65e1751fdc346e">llvm::MachineOperand::getCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0fab3e644b3457f90ed7f64876a037d2">llvm::MachineBasicBlock::getFirstTerminatorForward</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aee59c647052fc9557561e596681da3c0">llvm::MachineOperand::getFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertsubvector/#aa2e5c0f1932c6d84f43c0f2a7ca780eb">llvm::GInsertSubvector::getIndexImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaf6610b5b6565e4f1b56ca78c804654f">llvm::MachineMemOperand::getPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertsubvector/#a2045dc53a7fe26b15fca8c2904955fa0">llvm::GInsertSubvector::getSubVec</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a>, <a href="#aa910c5e501ff9679cc81de15bf3b9c1d">Observer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aae70dd97002db997dfc96303fa9e6971">llvm::MachineOperand::setCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">UnableToLegalize</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>, <a href="#af704613be9bed4ecd92e5aee263c2d5f">widenScalarDst</a>, <a href="#a1675c68d181eacf6dde19dc7d0cdd20c">widenScalarSrc</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a> and <a href="#af8ec769be431aa1296a7c786eb456f53">legalizeInstrStep</a>.</p>

</div>
</div>

### widenScalarDst() {#af704613be9bed4ecd92e5aee263c2d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::widenScalarDst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy, unsigned OpIdx=0, unsigned TruncOpcode=TargetOpcode::G_TRUNC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a Def by extending the operand's type to <span class="doxyComputerOutput">WideTy</span> and truncating it back with the <span class="doxyComputerOutput">TruncOpcode</span>, and replacing the vreg of the operand in place.</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2026 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a> and <a href="#aacc36b9bbb74a3cdb987aa8f28b269e3">widenScalar</a>.</p>

</div>
</div>

### widenScalarSrc() {#a1675c68d181eacf6dde19dc7d0cdd20c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::widenScalarSrc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy, unsigned OpIdx, unsigned ExtOpcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize a single operand <span class="doxyComputerOutput">OpIdx</span> of the machine instruction <span class="doxyComputerOutput">MI</span> as a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> by extending the operand's type to <span class="doxyComputerOutput">WideTy</span> using the specified <span class="doxyComputerOutput">ExtOpcode</span> for the extension instruction, and replacing the vreg of the operand in place.</p>

<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2012 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae50d11fc026093629c27142780ff1405">MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a> and <a href="#aacc36b9bbb74a3cdb987aa8f28b269e3">widenScalar</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### appendVectorElts() {#aa79a081ac765fe905177432422fde428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::appendVectorElts (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Elts, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### buildLCMMergePieces() {#abe48c77dc4845bfcf8d3caade230465d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT LegalizerHelper::buildLCMMergePieces (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> DstTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> GCDTy, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; VRegs, unsigned PadStrategy=TargetOpcode::G_ANYEXT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produce a merge of values in <span class="doxyComputerOutput">VRegs</span> to define <span class="doxyComputerOutput">DstReg</span>.</p>


<p>Perform a merge from the least common multiple type, and convert as appropriate to <span class="doxyComputerOutput">DstReg</span>.</p>


<p><span class="doxyComputerOutput">VRegs</span> should each have type <span class="doxyComputerOutput">GCDTy</span>. This type should be greatest common divisor type of <span class="doxyComputerOutput">DstReg</span>, <span class="doxyComputerOutput">NarrowTy</span>, and an undetermined source type.</p>


<p><span class="doxyComputerOutput">NarrowTy</span> is the desired result merge source type. If the source value needs to be widened to evenly cover <span class="doxyComputerOutput">DstReg</span>, inserts high bits corresponding to the extension opcode <span class="doxyComputerOutput">PadStrategy</span>.</p>


<p><span class="doxyComputerOutput">VRegs</span> will be cleared, and the result <span class="doxyComputerOutput">NarrowTy</span> register pieces will replace it. Returns The complete LCMTy that <span class="doxyComputerOutput">VRegs</span> will cover when merged.</p>


<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### buildWidenedRemergeToDst() {#a168e500e8c67d0a40c0c83933644a1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::buildWidenedRemergeToDst (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> LCMTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; RemergeRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge the values in <span class="doxyComputerOutput">RemergeRegs</span> to an <span class="doxyComputerOutput">LCMTy</span> typed value.</p>


<p>Extract the low bits into <span class="doxyComputerOutput">DstReg</span>. This is intended to use the outputs from buildLCMMergePieces after processing.</p>


<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### changeOpcode() {#ae4e436ca3addc49b0d2992e730c340df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::changeOpcode (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned NewOpcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 4325 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### createFCMPLibcall() {#a4597e902c58a7e7edfa7fc26f103c370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::createFCMPLibcall (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### createGetStateLibcall() {#ac9711313d362123a5753bbf9e11e87c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::createGetStateLibcall (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 940 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### createResetStateLibcall() {#a2a1c31f58480869d68238838c32c9680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::createResetStateLibcall (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### createSetStateLibcall() {#a4f63d865c7380365ac9112f22a97af3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::createSetStateLibcall (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### extractGCDType() {#a28e66a1d57f8c9d7199a7ff8a6c4225a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT LegalizerHelper::extractGCDType (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Parts, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> DstTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unmerge <span class="doxyComputerOutput">SrcReg</span> into smaller sized values, and append them to <span class="doxyComputerOutput">Parts</span>.</p>


<p>The elements of <span class="doxyComputerOutput">Parts</span> will be the greatest common divisor type of <span class="doxyComputerOutput">DstTy</span>, <span class="doxyComputerOutput">NarrowTy</span> and the type of <span class="doxyComputerOutput">SrcReg</span>. This will compute and return the GCD type.</p>


<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### extractGCDType() {#ae135d7958df9bb50d4c13bdc533e3c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::extractGCDType (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Parts, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> GCDTy, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unmerge <span class="doxyComputerOutput">SrcReg</span> into <span class="doxyComputerOutput">GCDTy</span> typed registers.</p>


<p>This will append all of the unpacked registers to <span class="doxyComputerOutput">Parts</span>. This version is if the common unmerge type is already known.</p>


<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### getNeutralElementForVecReduce() {#a3f1199bf7af1596d93e9bcf6e3a53ccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder LegalizerHelper::getNeutralElementForVecReduce (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5994 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### insertParts() {#aa82481b7d6e8565de31bfc00ab3101d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::insertParts (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ResultTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> PartTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; PartRegs, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> LeftoverTy=<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>(), <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; LeftoverRegs={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to build a wide generic register <span class="doxyComputerOutput">DstReg</span> of type <span class="doxyComputerOutput">RegTy</span> from smaller parts.</p>


<p>This will produce a G_MERGE_VALUES, G_BUILD_VECTOR, G_CONCAT_VECTORS, or sequence of G_INSERT as appropriate for the types.</p>


<p><span class="doxyComputerOutput">PartRegs</span> must be registers of type <span class="doxyComputerOutput">PartTy</span>.</p>


<p>If <span class="doxyComputerOutput">ResultTy</span> does not evenly break into <span class="doxyComputerOutput">PartTy</span> sized pieces, the remainder must be specified with <span class="doxyComputerOutput">LeftoverRegs</span> of type <span class="doxyComputerOutput">LeftoverTy</span>.</p>


<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### lowerMemcpy() {#a7b29f154ef0a5f3d79384ae79e08428b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerMemcpy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, uint64_t KnownLen, uint64_t Limit, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> DstAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> SrcAlign, bool IsVolatile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9709 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### lowerMemcpyInline() {#a53c3f48c25be63d1a637a01ea8d54dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerMemcpyInline (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, uint64_t KnownLen, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> DstAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> SrcAlign, bool IsVolatile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9699 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### lowerMemmove() {#ada5ffb602ee9242bde82ab21bc7e31d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerMemmove (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, uint64_t KnownLen, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> DstAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> SrcAlign, bool IsVolatile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9816 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### lowerMemset() {#aadfe0fcfb9706ea40ffca7310671d7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::lowerMemset (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, uint64_t KnownLen, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool IsVolatile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 9556 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### mergeMixedSubvectors() {#a3e5308413896e7a8bf9c7fb409a2cfe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::mergeMixedSubvectors (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; PartRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge <span class="doxyComputerOutput">PartRegs</span> with different types into <span class="doxyComputerOutput">DstReg</span>.</p>

<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### multiplyRegisters() {#a9b19d275bab47f74d90695f97bc550e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LegalizerHelper::multiplyRegisters (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; DstRegs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Src1Regs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; Src2Regs, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform generic multiplication of values held in multiple registers.</p>


<p>Generated instructions use only types NarrowTy and i1. Destination can be same or two times size of the source.</p>


<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 6396 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### tryNarrowPow2Reduction() {#aaee7fe9cae519bdd0e377513a132a826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::tryNarrowPow2Reduction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> SrcTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy, unsigned ScalarOpc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 5748 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### widenScalarAddSubOverflow() {#a15d4ed6e80d675d4709751e2a467592c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::widenScalarAddSubOverflow (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2411 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### widenScalarAddSubShlSat() {#a723e3c31461b4484206915d1ecfa3786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::widenScalarAddSubShlSat (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2494 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### widenScalarExtract() {#aded61f7210de0bf2f93c8b9ebabd236d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::widenScalarExtract (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2325 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### widenScalarInsert() {#ad1dd017d8dc7e8787f611ffc5e4cbd40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::widenScalarInsert (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2399 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### widenScalarMergeValues() {#a22804688cfeafb51c0c77b9478db1da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::widenScalarMergeValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2075 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### widenScalarMulo() {#ae0ed4e6a9bfd3270a3ef5de186ec8ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::widenScalarMulo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### widenScalarUnmergeValues() {#abde517a7245357dab62a2592c0d61adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult LegalizerHelper::widenScalarUnmergeValues (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned TypeIdx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> WideTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>, definition at line 2196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MIRBuilder {#ae50d11fc026093629c27142780ff1405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilder&amp; llvm::LegalizerHelper::MIRBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expose MIRBuilder so clients can set their own RecordInsertInstruction functions.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>


<p>Referenced by <a href="#aaa02ab5ab2c50cce96f4fec73c8186c3">bitcastDst</a>, <a href="#a4871db57e613d42877b6c9e1b901f6be">bitcastExtractSubvector</a>, <a href="#ac50dd9fe6220347f8306e3694a8129cb">bitcastExtractVectorElt</a>, <a href="#a6988a4a2d7b33093620e7a456e811a4b">bitcastInsertSubvector</a>, <a href="#a0a37f8fb6797142b53677bc4b59bf540">bitcastInsertVectorElt</a>, <a href="#acc9d5942b26515a4412b230f2672e647">bitcastShuffleVector</a>, <a href="#ad6cbca2857caf659c388e189c948a1fd">bitcastSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="#acc6c42a7b5fe244fad430ca7df32d346">coerceToScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp/#a3b8f2c8dafaf2b1007b8661546ce5aca">convertPtrToInt</a>, <a href="#a92bad93a924413adf3652db02e467a21">createStackStoreLoad</a>, <a href="#a576b964fe2d7d8750601681e04f05a9c">createStackTemporary</a>, <a href="#a0935a3e7269909f95115fb8452b1058c">equalizeVectorShuffleLengths</a>, <a href="#a78e425f7e61cda2ed4db6054c39beb18">fewerElementsBitcast</a>, <a href="#ae18cc835581a3f8882d7725891b67e4e">fewerElementsVectorExtractInsertVectorElt</a>, <a href="#abb2458b37415bd3ed547b405507ebc6b">fewerElementsVectorMerge</a>, <a href="#a8f6d92157833612e9b4cd0085e181b7e">fewerElementsVectorMultiEltType</a>, <a href="#a60e4161d46b020a55403acd13e31df9a">fewerElementsVectorPhi</a>, <a href="#addd0c111e12b07d02698a1fdcba59b0d">fewerElementsVectorReductions</a>, <a href="#ab6561daa27ec7fcc5335edb91ddae768">fewerElementsVectorSeqReductions</a>, <a href="#a1eac84349f5abc12d101036412730c5c">fewerElementsVectorShuffle</a>, <a href="#abce993680c63fae7b6cc5814e9b07826">fewerElementsVectorUnmergeValues</a>, <a href="#ab95d4485884d2e093f534590f24cfe0d">getDynStackAllocTargetPtr</a>, <a href="#ae91b4ff9d9c084c672f78adb9ed4006a">getVectorElementPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2324ad614c957fc91b34a00f32e89d60">llvm::AMDGPULegalizerInfo::legalizeBufferStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#a14251e7cc7c001be8b83a76caa7acd92">llvm::AArch64LegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5fcff4c2edfd92fa5cfbd95768477c26">llvm::AMDGPULegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6bd6caf03c29de76c97c536f89349bd7">llvm::SPIRVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#a088615ef5bf315b474c43859307730ec">llvm::X86LegalizerInfo::legalizeCustom</a>, <a href="#af8ec769be431aa1296a7c786eb456f53">legalizeInstrStep</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#aabf8e09177e2ae41bc06eb1f2be342e8">llvm::MipsLegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#aa97467a5c0d54755f0e725e9310ffaa0">llvm::RISCVLegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af4667ecbc4447b41863430fb572d8f82">llvm::AMDGPULegalizerInfo::legalizeLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a91b85787aa32d7f1f0d38d59a77cee68">llvm::AMDGPULegalizerInfo::legalizeMinNumMaxNum</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2645b2c5fc9b404821322ad403c87810">llvm::AMDGPULegalizerInfo::legalizeMul</a>, <a href="#a9006a4423b6daf984091f1b43e549f17">LegalizerHelper</a>, <a href="#aa10024dcff51f09d4751794584609e85">LegalizerHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a51ac04efbaa3282a12478341fa0a7b9a">llvm::AMDGPULegalizerInfo::legalizeSBufferPrefetch</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5fb58d2b96b0e7a4a021fbe21869aaa8">llvm::AMDGPULegalizerInfo::legalizeStore</a>, <a href="#ad8a495f4190353f60d1cd5e471283f40">libcall</a>, <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>, <a href="#a21f36be0b82249def611e5709ff7dd15">lowerAbsToAddXor</a>, <a href="#a41da6a2461e80e2d3b6b226281477bfa">lowerAbsToCNeg</a>, <a href="#a34f7e7a55fa5743fadeef838b7c9ece9">lowerAbsToMaxNeg</a>, <a href="#aae6d16ec0f044086e929d63d532178bf">lowerAddSubSatToAddoSubo</a>, <a href="#a813d1719803526d9839b4ae8d0a6b93d">lowerAddSubSatToMinMax</a>, <a href="#a6fb535803cbc7430528cdb19a157dd47">lowerBitcast</a>, <a href="#a0b9d961c3e0a9fa4c0e9ce806e972c4c">lowerBitCount</a>, <a href="#a2ed659cad017d524d63d763e19ef756f">lowerBitreverse</a>, <a href="#ae62214791d9e4dcb2f7eda048092458f">lowerBswap</a>, <a href="#aefeacc46707017018d95faf6751da717">lowerConstant</a>, <a href="#ace9b958e28468570d5cc74682e326f3b">lowerDIVREM</a>, <a href="#a0b54c43cec90635e63e99f792b9207bc">lowerDynStackAlloc</a>, <a href="#a40558d23c7bc31dd0b4f1d6b00199487">lowerEXT</a>, <a href="#a76e5a8c6363a48b3ca4e924a8f59f0e5">lowerExtract</a>, <a href="#a2fdcff9cc28cfffa71717b8d3c32c781">lowerExtractInsertVectorElt</a>, <a href="#a87cbc5eaa4440f62bdad70cce2296f3b">lowerFAbs</a>, <a href="#a297f161b2970f693a98a4bf30c7eb630">lowerFConstant</a>, <a href="#a9dc8c9b527c43cc36ac86886d18f00e4">lowerFCopySign</a>, <a href="#ab031376e8eddaebf70d2cbcce069b4ba">lowerFFloor</a>, <a href="#aac36a82fb8a9d486c3b59ccab7769e4d">lowerFMad</a>, <a href="#a105bd213837c5c2e30520113d885b8f3">lowerFMinNumMaxNum</a>, <a href="#a84a1b0b6afe8ccff8b1c5fd66de228af">lowerFPOWI</a>, <a href="#a3ee5abf8664d1ea66e6d93fd6cf61065">lowerFPTOINT_SAT</a>, <a href="#ab99f92278021f1921be23b762056a9cc">lowerFPTOSI</a>, <a href="#a64f47636eb4667460ea08f358d6d39da">lowerFPTOUI</a>, <a href="#a04ee040b3b0253a0832ddb7915d55ae1">lowerFPTRUNC_F64_TO_F16</a>, <a href="#a7359ee87521122d9315cb47df7ec57c5">lowerFunnelShiftAsShifts</a>, <a href="#a332b012f0983179618526234e605c9aa">lowerFunnelShiftWithInverse</a>, <a href="#a743aa32715279bdb86b53f20065950c9">lowerInsert</a>, <a href="#a1422ed8c8a0aea2d84dc7e2f35d24874">lowerIntrinsicRound</a>, <a href="#a79ddea5769637d54074168769084f404">lowerISFPCLASS</a>, <a href="#a1dbb219846876149646e81e84ee81a47">lowerLoad</a>, <a href="#abce8515ac1fb3b6be13d5a39418847cb">lowerMergeValues</a>, <a href="#a7287c6cc84f805db4ae46d581b4deecc">lowerMinMax</a>, <a href="#a76df0b752eddd8b0711d1af16a3658ad">lowerReadWriteRegister</a>, <a href="#ac5df097268459420f2dd52a648379463">lowerRotate</a>, <a href="#aa30414996e4930e5be9e10e0bab811d0">lowerRotateWithReverseRotate</a>, <a href="#a545272144fee7632786d2fc0427ec6db">lowerSADDO_SSUBO</a>, <a href="#ad29042068469adc2859360985494dbb9">lowerSelect</a>, <a href="#a00a7edf44feca96dfa6abdc4ae5d705d">lowerShlSat</a>, <a href="#abac7927a227a6c370e26ee82af77567d">lowerShuffleVector</a>, <a href="#a0a4f859f973b7f797f2d510c369980ad">lowerSITOFP</a>, <a href="#a1a84546a5ff646ed05b5772e00084db6">lowerSMULH_UMULH</a>, <a href="#adc929c22e98b3fab30eeec645ccb999a">lowerStackRestore</a>, <a href="#adf3aec1c39ff3bf8683b13d186f5b617">lowerStackSave</a>, <a href="#a40e2e64056fc2e2dabadfb9ceae338f6">lowerStore</a>, <a href="#a04a0bfc5807bbedc770b17d4691e3142">lowerThreewayCompare</a>, <a href="#ae51c8cf31e26c03753e3f6acb6f48d56">lowerTRUNC</a>, <a href="#a9b5ad9f5de612dc98a4f3232a98ab754">lowerU64ToF32BitOps</a>, <a href="#ac9599381b406afe38a263b028248e407">lowerU64ToF32WithSITOFP</a>, <a href="#a13531e23193d32ac81bdefa1db2ad987">lowerU64ToF64BitFloatOps</a>, <a href="#aba403eaa336a6c9d869717c9e54edd9c">lowerUITOFP</a>, <a href="#a6abe0f5db91bf445b3962dba969c5c7f">lowerUnmergeValues</a>, <a href="#a9511578c9aa47dc8c5d7df3e9b623be3">lowerVAArg</a>, <a href="#ac29774c06843a7c183ae3fd328d43bc8">lowerVECTOR_COMPRESS</a>, <a href="#a8e25418b93784160f4a660950f5fa806">lowerVectorReduction</a>, <a href="#a2ffccbb574e8a2cf63b8ede89f53090b">moreElementsVector</a>, <a href="#a25a4c14864c6f574bc99e19e15a8b4d2">moreElementsVectorDst</a>, <a href="#a98e3f12f0b3d7f35251e1e71336b480c">moreElementsVectorPhi</a>, <a href="#a1a3548d0921506d0cd736b7960c12485">moreElementsVectorShuffle</a>, <a href="#ac465c012a999bcab06235573fcb0860f">moreElementsVectorSrc</a>, <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>, <a href="#aea9d2b3b2a626fb7c5093f5f8fa9cf95">narrowScalarAddSub</a>, <a href="#a8a4aeb9640ed05629f69b925f53ae366">narrowScalarBasic</a>, <a href="#ae25927a69e107ef1477822b884ca034b">narrowScalarCTLZ</a>, <a href="#a048378560a1f3ddd48ddf9c60ae488f5">narrowScalarCTPOP</a>, <a href="#a2db1bc1a16d89298b92a13857146e28d">narrowScalarCTTZ</a>, <a href="#ad7f8e31fdc4b07d287c52567a2d259f4">narrowScalarDst</a>, <a href="#aaec7c9b0ed49d3297c833d8d9def42c0">narrowScalarExtract</a>, <a href="#ad66885c64b6a5ee434c62d1583de8589">narrowScalarFLDEXP</a>, <a href="#ad43f277d8baa4b080bfd1beed8542bd6">narrowScalarInsert</a>, <a href="#a0c0426a2303d102874f24e00608e3de4">narrowScalarMul</a>, <a href="#a8f6f143ae3ebc33b4f3f97e486bf7112">narrowScalarSelect</a>, <a href="#a2f99d62852a3fab708983d8ea2139755">narrowScalarShift</a>, <a href="#a79ab7155d5feabf02f01c4d3b7d9c422">narrowScalarShiftByConstant</a>, <a href="#a5cafcb9996d69b6f864daa6c7d00c48a">narrowScalarSrc</a>, <a href="#a8eb21f893b8039f4edcc3e3bce0c319e">reduceLoadStoreWidth</a>, <a href="#a6d8b5e9460092c4517e5e594756fcb82">scalarizeVectorBooleanStore</a>, <a href="#aacc36b9bbb74a3cdb987aa8f28b269e3">widenScalar</a>, <a href="#af704613be9bed4ecd92e5aee263c2d5f">widenScalarDst</a> and <a href="#a1675c68d181eacf6dde19dc7d0cdd20c">widenScalarSrc</a>.</p>

</div>
</div>

### Observer {#aa910c5e501ff9679cc81de15bf3b9c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelChangeObserver&amp; llvm::LegalizerHelper::Observer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>To keep track of changes made by the <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a>.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>


<p>Referenced by <a href="#a6c12dbad109a5d725ce01a9a8363f948">bitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#a14251e7cc7c001be8b83a76caa7acd92">llvm::AArch64LegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="#a9006a4423b6daf984091f1b43e549f17">LegalizerHelper</a>, <a href="#aa10024dcff51f09d4751794584609e85">LegalizerHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a51ac04efbaa3282a12478341fa0a7b9a">llvm::AMDGPULegalizerInfo::legalizeSBufferPrefetch</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5fb58d2b96b0e7a4a021fbe21869aaa8">llvm::AMDGPULegalizerInfo::legalizeStore</a>, <a href="#aa411af5653e9ed6cd4f664853b61bf0d">lower</a>, <a href="#a0b9d961c3e0a9fa4c0e9ce806e972c4c">lowerBitCount</a>, <a href="#a8e25418b93784160f4a660950f5fa806">lowerVectorReduction</a>, <a href="#a2ffccbb574e8a2cf63b8ede89f53090b">moreElementsVector</a>, <a href="#a98e3f12f0b3d7f35251e1e71336b480c">moreElementsVectorPhi</a>, <a href="#a6701d040466d73f3dc51481d3186c294">narrowScalar</a>, <a href="#ad66885c64b6a5ee434c62d1583de8589">narrowScalarFLDEXP</a>, <a href="#a687c20941b83380477f4a3d95ad4e390">narrowScalarFPTOI</a>, <a href="#a2f99d62852a3fab708983d8ea2139755">narrowScalarShift</a> and <a href="#aacc36b9bbb74a3cdb987aa8f28b269e3">widenScalar</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### KB {#a3cb5536fead52e721fc5c416d1d738e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelKnownBits* llvm::LegalizerHelper::KB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>

</div>
</div>

### LI {#a4af30f3f8583797f392d039b50c47ebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo&amp; llvm::LegalizerHelper::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>

</div>
</div>

### MRI {#a9b7d8ceb9e3fc4f2394c7dffe8201e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::LegalizerHelper::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>

</div>
</div>

### TLI {#aed601381a5ccdbde58328fb872287c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering&amp; llvm::LegalizerHelper::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">LegalizerHelper.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
