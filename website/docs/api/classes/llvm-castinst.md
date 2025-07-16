---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/castinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CastInst` Class Reference

<p>This is the base class for all instructions that perform data casts. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CastInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unaryinstruction">UnaryInstruction</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst">AddrSpaceCastInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a conversion between pointers from one address space to another. <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a no-op cast from one type to another. <a href="/web-llvm/docs/api/classes/llvm/bitcastinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fpextinst">FPExtInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents an extension of floating point types. <a href="/web-llvm/docs/api/classes/llvm/fpextinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fptosiinst">FPToSIInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a cast from floating point to signed integer. <a href="/web-llvm/docs/api/classes/llvm/fptosiinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fptouiinst">FPToUIInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a cast from floating point to unsigned integer. <a href="/web-llvm/docs/api/classes/llvm/fptouiinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fptruncinst">FPTruncInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a truncation of floating point types. <a href="/web-llvm/docs/api/classes/llvm/fptruncinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inttoptrinst">IntToPtrInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a cast from an integer to a pointer. <a href="/web-llvm/docs/api/classes/llvm/inttoptrinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/possiblynonneginst">PossiblyNonNegInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that can have a nneg flag (zext/uitofp). <a href="/web-llvm/docs/api/classes/llvm/possiblynonneginst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ptrtointinst">PtrToIntInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a cast from a pointer to an integer. <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sextinst">SExtInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a sign extension of integer types. <a href="/web-llvm/docs/api/classes/llvm/sextinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sitofpinst">SIToFPInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a cast from signed integer to floating point. <a href="/web-llvm/docs/api/classes/llvm/sitofpinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/truncinst">TruncInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a truncation of integer types. <a href="/web-llvm/docs/api/classes/llvm/truncinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/uitofpinst">UIToFPInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a cast unsigned integer to floating point. <a href="/web-llvm/docs/api/classes/llvm/uitofpinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/zextinst">ZExtInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents zero extension of integer types. <a href="/web-llvm/docs/api/classes/llvm/zextinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a> (Type *Ty, unsigned iType, Value *S, const Twine &amp;NameStr="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor with insert-before-instruction semantics for subclasses. <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1b55a34e106493b57164146f40623b">isIntegerCast</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>There are several places where we need to know if a cast instruction only deals with integer source and destination types. <a href="#aeb1b55a34e106493b57164146f40623b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1438002c91e6e1c7a587a194b268239d">isNoopCast</a> (const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this cast is a no-op cast. <a href="#a1438002c91e6e1c7a587a194b268239d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3685b2128d8e6917000e4adc3b266ff6">getOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the opcode of this <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a>. <a href="#a3685b2128d8e6917000e4adc3b266ff6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01cc70c1e8052996fb44f59fa63a015c">getSrcTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the source type, as a convenience. <a href="#a01cc70c1e8052996fb44f59fa63a015c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba3c4846ce91323f585f957963d8f67">getDestTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the destination type, as a convenience. <a href="#aeba3c4846ce91323f585f957963d8f67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a> (Instruction::CastOps, Value *S, Type *Ty, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides a way to construct any of the <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> subclasses using an opcode instead of the subclass's constructor. <a href="#ad2e0ab6d7096fe67a2216fe349044387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad120ee39de5a92d1581ba9a5e1072296">CreateZExtOrBitCast</a> (Value *S, Type *Ty, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a ZExt or BitCast cast instruction. <a href="#ad120ee39de5a92d1581ba9a5e1072296">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff5766c114e19126ba79be81e93fcd1">CreateSExtOrBitCast</a> (Value *S, Type *Ty, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a SExt or BitCast cast instruction. <a href="#aeff5766c114e19126ba79be81e93fcd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac120250caf531b58acce9d8cc34c7032">CreatePointerCast</a> (Value *S, Type *Ty, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a BitCast, AddrSpaceCast or a PtrToInt cast instruction. <a href="#ac120250caf531b58acce9d8cc34c7032">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1536669cae3776862c9ed0a566595b7d">CreatePointerBitCastOrAddrSpaceCast</a> (Value *S, Type *Ty, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a BitCast or an AddrSpaceCast cast instruction. <a href="#a1536669cae3776862c9ed0a566595b7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb02479a44bbebcabf8b7b5e1baa921">CreateBitOrPointerCast</a> (Value *S, Type *Ty, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a BitCast, a PtrToInt, or an IntToPTr cast instruction. <a href="#acdb02479a44bbebcabf8b7b5e1baa921">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c8e2860ccc428282e30bf6a4d36a2c">CreateIntegerCast</a> (Value *S, Type *Ty, bool isSigned, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a ZExt, BitCast, or Trunc for int -&gt; int casts. <a href="#a60c8e2860ccc428282e30bf6a4d36a2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a877d5d2a2a1ab4fd979e1d3de94404b7">CreateFPCast</a> (Value *S, Type *Ty, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an FPExt, BitCast, or FPTrunc for fp -&gt; fp casts. <a href="#a877d5d2a2a1ab4fd979e1d3de94404b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab3f4e42107a79ae5939cd350e77b834">CreateTruncOrBitCast</a> (Value *S, Type *Ty, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a Trunc or BitCast cast instruction. <a href="#aab3f4e42107a79ae5939cd350e77b834">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2915714199e899f7766d49f87ec2ad6">isBitCastable</a> (Type *SrcTy, Type *DestTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a bitcast between these types is valid. <a href="#aa2915714199e899f7766d49f87ec2ad6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f850488e8bda1d1b400821d6d61bd1">isBitOrNoopPointerCastable</a> (Type *SrcTy, Type *DestTy, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a bitcast, inttoptr, or ptrtoint cast between these types is valid and a no-op. <a href="#a94f850488e8bda1d1b400821d6d61bd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06dc25da1f16f389f5244304e8d33127">getCastOpcode</a> (const Value *Val, bool SrcIsSigned, Type *Ty, bool DstIsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the opcode necessary to cast Val into Ty using usual casting rules. <a href="#a06dc25da1f16f389f5244304e8d33127">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace4c7b4bc6aba9506b1b60aac18881f3">isNoopCast</a> (Instruction::CastOps Opcode, Type *SrcTy, Type *DstTy, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A no-op cast is one that can be effected without changing any bits. <a href="#ace4c7b4bc6aba9506b1b60aac18881f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b805c54dc1ead67b711a4b1cb72f492">isEliminableCastPair</a> (Instruction::CastOps firstOpcode, Instruction::CastOps secondOpcode, Type *SrcTy, Type *MidTy, Type *DstTy, Type *SrcIntPtrTy, Type *MidIntPtrTy, Type *DstIntPtrTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine how a pair of casts can be eliminated, if they can be at all. <a href="#a8b805c54dc1ead67b711a4b1cb72f492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0e9f16b79d49af44209f202b31290a1">castIsValid</a> (Instruction::CastOps op, Type *SrcTy, Type *DstTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method can be used to determine if a cast from SrcTy to DstTy using Opcode op is valid or not. <a href="#af0e9f16b79d49af44209f202b31290a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99424675c5fc439756409a02a8f9405a">castIsValid</a> (Instruction::CastOps op, Value *S, Type *DstTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb50a3e6da6995bb3c025c6e6021e3ab">classof</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#afb50a3e6da6995bb3c025c6e6021e3ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5414ed44ee2aaac8f75cf2bbcecd52d9">classof</a> (const Value *V)</td>
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

<p>This is the base class for all instructions that perform data casts.</p>


<p>It is simply provided so that instruction category testing can be performed with code like:</p>


<p>if (isa&lt;CastInst&gt;(Instr)) { ... } Base class of casting instructions.</p>


<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### CastInst() {#a8eadc0b6c1d49a31d389dd611f44b08f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CastInst::CastInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned iType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Constructor with insert-before-instruction semantics for subclasses.</p>

<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a> and <a href="/web-llvm/docs/api/classes/llvm/unaryinstruction/#ad93ca9b74c44e7d8c00c72405e51262d">llvm::UnaryInstruction::UnaryInstruction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#abfb2dff4f8512dc089787af08e58034f">llvm::AddrSpaceCastInst::AddrSpaceCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcastinst/#adb9b2f6d25ecdf8b9e338b099448d28c">llvm::BitCastInst::BitCastInst</a>, <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a>, <a href="#acdb02479a44bbebcabf8b7b5e1baa921">CreateBitOrPointerCast</a>, <a href="#a877d5d2a2a1ab4fd979e1d3de94404b7">CreateFPCast</a>, <a href="#a60c8e2860ccc428282e30bf6a4d36a2c">CreateIntegerCast</a>, <a href="#a1536669cae3776862c9ed0a566595b7d">CreatePointerBitCastOrAddrSpaceCast</a>, <a href="#ac120250caf531b58acce9d8cc34c7032">CreatePointerCast</a>, <a href="#aeff5766c114e19126ba79be81e93fcd1">CreateSExtOrBitCast</a>, <a href="#aab3f4e42107a79ae5939cd350e77b834">CreateTruncOrBitCast</a>, <a href="#ad120ee39de5a92d1581ba9a5e1072296">CreateZExtOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/fpextinst/#ae1b263019bf1366a442ac5a5936b558a">llvm::FPExtInst::FPExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fptosiinst/#a401b4fdace4831a96ca02c26e0b10dd2">llvm::FPToSIInst::FPToSIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fptouiinst/#ad65760956ac8bae57d07194ec9e68511">llvm::FPToUIInst::FPToUIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fptruncinst/#a4aad9382ea53e7f9bbea4092bb6bae46">llvm::FPTruncInst::FPTruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/inttoptrinst/#a227d993ef7d18d698208b8d29bb439ae">llvm::IntToPtrInst::IntToPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#abe54ccb1d2b334b625b8579e840e2d49">llvm::PtrToIntInst::PtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sextinst/#ae6f745779dfe41fdb720a7f60380020a">llvm::SExtInst::SExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sitofpinst/#a340a4bd699984993320d0469b121b92e">llvm::SIToFPInst::SIToFPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/truncinst/#ac9915ef8f0e41058110048570f4e4c9e">llvm::TruncInst::TruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/uitofpinst/#a5a8f10535b0bb9d3515854cd415ae5ff">llvm::UIToFPInst::UIToFPInst</a> and <a href="/web-llvm/docs/api/classes/llvm/zextinst/#a5f17281ac526d2dfd7823374cb25ea8c">llvm::ZExtInst::ZExtInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDestTy() {#aeba3c4846ce91323f585f957963d8f67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CastInst::getDestTy ()</td>
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

<p>Return the destination type, as a convenience.</p>

<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a7467c1c3eff398cd97c3d8a2b2cebac0">constantFoldUser</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#af8fd85d6783b4f0fbb5f4a8d6bf40bdc">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithCastInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aabb3d90405099bce8007a11942f3ab92">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitBitCastInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a48bf838fb202d25d6b13ba8048182fba">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitCastInst</a>.</p>

</div>
</div>

### getOpcode() {#a3685b2128d8e6917000e4adc3b266ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction::CastOps llvm::CastInst::getOpcode ()</td>
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

<p>Return the opcode of this <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a>.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#abfb2dff4f8512dc089787af08e58034f">llvm::AddrSpaceCastInst::AddrSpaceCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcastinst/#adb9b2f6d25ecdf8b9e338b099448d28c">llvm::BitCastInst::BitCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#abb43e28c8e0376de4d419ac11fc5ffd8">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::calculateCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a9fe92d5d425b0ddab77a3bd58e734a74">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a38a01001593bf75700ee024b15bdf413">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialFromPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a7467c1c3eff398cd97c3d8a2b2cebac0">constantFoldUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a36b7410be1f86b52970bb1381904e282">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/fpextinst/#ae1b263019bf1366a442ac5a5936b558a">llvm::FPExtInst::FPExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fptosiinst/#a401b4fdace4831a96ca02c26e0b10dd2">llvm::FPToSIInst::FPToSIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fptouiinst/#ad65760956ac8bae57d07194ec9e68511">llvm::FPToUIInst::FPToUIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fptruncinst/#a4aad9382ea53e7f9bbea4092bb6bae46">llvm::FPTruncInst::FPTruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/inttoptrinst/#a227d993ef7d18d698208b8d29bb439ae">llvm::IntToPtrInst::IntToPtrInst</a>, <a href="#aeb1b55a34e106493b57164146f40623b">isIntegerCast</a>, <a href="#a1438002c91e6e1c7a587a194b268239d">isNoopCast</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#abe54ccb1d2b334b625b8579e840e2d49">llvm::PtrToIntInst::PtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sextinst/#ae6f745779dfe41fdb720a7f60380020a">llvm::SExtInst::SExtInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a77aac577d89abc9411adfdf918d7d539">shrinkInsertElt</a>, <a href="/web-llvm/docs/api/classes/llvm/sitofpinst/#a340a4bd699984993320d0469b121b92e">llvm::SIToFPInst::SIToFPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/truncinst/#ac9915ef8f0e41058110048570f4e4c9e">llvm::TruncInst::TruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/uitofpinst/#a5a8f10535b0bb9d3515854cd415ae5ff">llvm::UIToFPInst::UIToFPInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a48bf838fb202d25d6b13ba8048182fba">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitCastInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a57aff0646c7151c4158d839c386332cc">visitIVCast</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a0403c9b207ba733675ef20cb8828d00c">llvm::VPWidenCastRecipe::VPWidenCastRecipe</a> and <a href="/web-llvm/docs/api/classes/llvm/zextinst/#a5f17281ac526d2dfd7823374cb25ea8c">llvm::ZExtInst::ZExtInst</a>.</p>

</div>
</div>

### getSrcTy() {#a01cc70c1e8052996fb44f59fa63a015c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CastInst::getSrcTy ()</td>
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

<p>Return the source type, as a convenience.</p>

<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a45705c727d8388c014471504b4ab0c4e">foldLogicCastConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aabb3d90405099bce8007a11942f3ab92">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitBitCastInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a48bf838fb202d25d6b13ba8048182fba">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitCastInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>.</p>

</div>
</div>

### isIntegerCast() {#aeb1b55a34e106493b57164146f40623b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CastInst::isIntegerCast ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>There are several places where we need to know if a cast instruction only deals with integer source and destination types.</p>


<p>To simplify that logic, this method is provided.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff the cast has only integral typed operand and dest type. Determine if this is an integer-only cast.</p></dd>
</dl>


<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2696 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a3685b2128d8e6917000e4adc3b266ff6">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#af8fd85d6783b4f0fbb5f4a8d6bf40bdc">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithCastInst</a>.</p>

</div>
</div>

### isNoopCast() {#a1438002c91e6e1c7a587a194b268239d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CastInst::isNoopCast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if this cast is a no-op cast.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>is the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> to determine pointer size.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2747 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a3685b2128d8e6917000e4adc3b266ff6">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="#ace4c7b4bc6aba9506b1b60aac18881f3">isNoopCast</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### castIsValid() {#af0e9f16b79d49af44209f202b31290a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CastInst::castIsValid (<a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy)</td>
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

<p>This method can be used to determine if a cast from SrcTy to DstTy using Opcode op is valid or not.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that the construction parameters for a <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> are correct.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff the proposed cast is valid. Determine if a cast is valid without creating one.</p></dd>
</dl>


<p>This could be broken out into the separate constructors but it is useful to have it in one place and to eliminate the redundant code for getting the sizes of the types involved.</p>


<p>Declaration at line 621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3241 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8cbe006c6c069502d37891c438847c23">llvm::Type::isAggregateType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a82a7e98c00f5bb12e2c5481fe0ab3f1a">llvm::Type::isFirstClassType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad0709baa705ae62c4e09cdd47fb4b420">llvm::Type::isFPOrFPVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#abfb2dff4f8512dc089787af08e58034f">llvm::AddrSpaceCastInst::AddrSpaceCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcastinst/#adb9b2f6d25ecdf8b9e338b099448d28c">llvm::BitCastInst::BitCastInst</a>, <a href="#a99424675c5fc439756409a02a8f9405a">castIsValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d58e0e9c2196e30a314dbc5d3431524">llvm::ConstantFoldLoadThroughBitcast</a>, <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/fpextinst/#ae1b263019bf1366a442ac5a5936b558a">llvm::FPExtInst::FPExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fptosiinst/#a401b4fdace4831a96ca02c26e0b10dd2">llvm::FPToSIInst::FPToSIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fptouiinst/#ad65760956ac8bae57d07194ec9e68511">llvm::FPToUIInst::FPToUIInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fptruncinst/#a4aad9382ea53e7f9bbea4092bb6bae46">llvm::FPTruncInst::FPTruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#acac8bfd6018661b40690c621bece1540">llvm::ConstantExpr::getAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae79d05dd3d0b05e080e08f8c5c33f880">llvm::ConstantExpr::getBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a49b69843927f7cd96d866768b3aec92b">llvm::ConstantExpr::getCast</a>, <a href="/web-llvm/docs/api/classes/llvm/inttoptrinst/#a227d993ef7d18d698208b8d29bb439ae">llvm::IntToPtrInst::IntToPtrInst</a>, <a href="#ace4c7b4bc6aba9506b1b60aac18881f3">isNoopCast</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#abe54ccb1d2b334b625b8579e840e2d49">llvm::PtrToIntInst::PtrToIntInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sextinst/#ae6f745779dfe41fdb720a7f60380020a">llvm::SExtInst::SExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sitofpinst/#a340a4bd699984993320d0469b121b92e">llvm::SIToFPInst::SIToFPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/truncinst/#ac9915ef8f0e41058110048570f4e4c9e">llvm::TruncInst::TruncInst</a>, <a href="/web-llvm/docs/api/classes/llvm/uitofpinst/#a5a8f10535b0bb9d3515854cd415ae5ff">llvm::UIToFPInst::UIToFPInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a> and <a href="/web-llvm/docs/api/classes/llvm/zextinst/#a5f17281ac526d2dfd7823374cb25ea8c">llvm::ZExtInst::ZExtInst</a>.</p>

</div>
</div>

### castIsValid() {#a99424675c5fc439756409a02a8f9405a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CastInst::castIsValid (<a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> op, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy)</td>
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



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#af0e9f16b79d49af44209f202b31290a1">castIsValid</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>.</p>

</div>
</div>

### classof() {#afb50a3e6da6995bb3c025c6e6021e3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CastInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a5414ed44ee2aaac8f75cf2bbcecd52d9">classof</a>.</p>

</div>
</div>

### classof() {#a5414ed44ee2aaac8f75cf2bbcecd52d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CastInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#afb50a3e6da6995bb3c025c6e6021e3ab">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### Create() {#ad2e0ab6d7096fe67a2216fe349044387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * CastInst::Create (<a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> op, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Provides a way to construct any of the <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> subclasses using an opcode instead of the subclass's constructor.</p>


<p>The opcode must be in the <a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">CastOps</a> category (Instruction::isCast(opcode) returns true). This constructor has insert-before-instruction semantics to automatically insert the new <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> before InsertBefore (if it is non-null). Construct any of the <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> subclasses</p>


<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2972 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a>, <a href="#af0e9f16b79d49af44209f202b31290a1">castIsValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3e2793cc62829d80622b78cc681b25c2">canonicalizeBitCastExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a2efdcd5db2fb392d8ef38eca4bc0f570">convertNvvmIntrinsicToLlvm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a944b77cb28ad77cdf28380c4453f8d02">convertToParamAS</a>, <a href="#acdb02479a44bbebcabf8b7b5e1baa921">CreateBitOrPointerCast</a>, <a href="#a877d5d2a2a1ab4fd979e1d3de94404b7">CreateFPCast</a>, <a href="#a60c8e2860ccc428282e30bf6a4d36a2c">CreateIntegerCast</a>, <a href="#a1536669cae3776862c9ed0a566595b7d">CreatePointerBitCastOrAddrSpaceCast</a>, <a href="#ac120250caf531b58acce9d8cc34c7032">CreatePointerCast</a>, <a href="#aeff5766c114e19126ba79be81e93fcd1">CreateSExtOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="#aab3f4e42107a79ae5939cd350e77b834">CreateTruncOrBitCast</a>, <a href="#ad120ee39de5a92d1581ba9a5e1072296">CreateZExtOrBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ab737e320d75547e2b43f6044fc3f3bcc">foldCastShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab6b30eb5a835fd225bcd74248fa65693">llvm::InstCombinerImpl::foldSelectExtConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af9fc0080b4accc0b19bfbbc624701e30">llvm::ConstantExpr::getAsInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a04dad23556e58f793c9a508a1a2d9aa5">llvm::PPCTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#acb762c0dfb2a90596163f59e2dfbd029">narrowInsElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ace24fe825742577e78df32f725ad7b26">processSIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac20eb5c6ac0036298cbfb44d3b9cc82">llvm::UpgradeBitCastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abdfda4087597a7f3a1f6af6de43c30da">llvm::InstCombinerImpl::visitFPExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5c5efa376b5dcc0c0b0628d89882a498">llvm::InstCombinerImpl::visitSIToFP</a>.</p>

</div>
</div>

### CreateBitOrPointerCast() {#acdb02479a44bbebcabf8b7b5e1baa921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * CastInst::CreateBitOrPointerCast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Create a BitCast, a PtrToInt, or an IntToPTr cast instruction.</p>


<p>If the value is a pointer type and the destination an integer type, creates a PtrToInt cast. If the value is an integer type and the destination a pointer type, creates an IntToPtr cast. Otherwise, creates a bitcast.</p>


<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3047 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a>, <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#a8c9ae0be5e6bcad90cdf141962a117f3">createRetBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a6556e45ee27ad333bf33eda6b1f04b8a">foldBitCastBitwiseLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>.</p>

</div>
</div>

### CreateFPCast() {#a877d5d2a2a1ab4fd979e1d3de94404b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * CastInst::CreateFPCast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Create an FPExt, BitCast, or FPTrunc for fp -&gt; fp casts.</p>

<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3072 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a> and <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>.</p>

</div>
</div>

### CreateIntegerCast() {#a60c8e2860ccc428282e30bf6a4d36a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * CastInst::CreateIntegerCast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool isSigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Create a ZExt, BitCast, or Trunc for int -&gt; int casts.</p>

<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3058 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a>, <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>.</p>

</div>
</div>

### CreatePointerBitCastOrAddrSpaceCast() {#a1536669cae3776862c9ed0a566595b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * CastInst::CreatePointerBitCastOrAddrSpaceCast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Create a BitCast or an AddrSpaceCast cast instruction.</p>

<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3036 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a>, <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a68789c8159cee17d42d86c4b7fcce324">llvm::IRBuilderBase::CreatePointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/nofolder/#aa708bf3f31fa0019de686f8d536baebc">llvm::NoFolder::CreatePointerBitCastOrAddrSpaceCast</a>, <a href="#ac120250caf531b58acce9d8cc34c7032">CreatePointerCast</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a63540fe3243b44a62cb656c73274f8ac">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::ensureType</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>.</p>

</div>
</div>

### CreatePointerCast() {#ac120250caf531b58acce9d8cc34c7032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * CastInst::CreatePointerCast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Create a BitCast, AddrSpaceCast or a PtrToInt cast instruction.</p>


<p>Create a BitCast or a PtrToInt cast instruction.</p>


<p>Declaration at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3019 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a>, <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a>, <a href="#a1536669cae3776862c9ed0a566595b7d">CreatePointerBitCastOrAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/nofolder/#ac19bdfa9821070e22c61228942b74df3">llvm::NoFolder::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>.</p>

</div>
</div>

### CreateSExtOrBitCast() {#aeff5766c114e19126ba79be81e93fcd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * CastInst::CreateSExtOrBitCast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Create a SExt or BitCast cast instruction.</p>

<p>Declaration at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3004 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a>, <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

### CreateTruncOrBitCast() {#aab3f4e42107a79ae5939cd350e77b834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * CastInst::CreateTruncOrBitCast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Create a Trunc or BitCast cast instruction.</p>

<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3011 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a>, <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1347d52f024418efd43a77e0fcb57355">llvm::InstCombinerImpl::canonicalizeCondSignextOfHighBitExtractToSignextHighBitExtract</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa72b51b8f455c8a622bb6f8cc9c14860">llvm::InstCombinerImpl::foldVariableSignZeroExtensionOfVariableHighBitExtract</a>.</p>

</div>
</div>

### CreateZExtOrBitCast() {#ad120ee39de5a92d1581ba9a5e1072296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastInst * CastInst::CreateZExtOrBitCast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Create a ZExt or BitCast cast instruction.</p>

<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2997 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a8eadc0b6c1d49a31d389dd611f44b08f">CastInst</a>, <a href="#ad2e0ab6d7096fe67a2216fe349044387">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a84318f31145b081677697de64401238a">llvm::InstCombinerImpl::foldPHIArgZextsIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ad47460e620c33c83309f749ea8f34c6b">processSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1cdbee2aa0ed532c8d9e91a00cc91f37">llvm::InstCombinerImpl::visitUDiv</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2f39b95e8efb44737439c323b18a55d7">llvm::InstCombinerImpl::visitURem</a>.</p>

</div>
</div>

### getCastOpcode() {#a06dc25da1f16f389f5244304e8d33127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction::CastOps CastInst::getCastOpcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, bool SrcIsSigned, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool DstIsSigned)</td>
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

<p>Returns the opcode necessary to cast Val into Ty using usual casting rules.</p>


<p>Infer the opcode for cast operand and type</p>


<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3144 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a82a7e98c00f5bb12e2c5481fe0ab3f1a">llvm::Type::isFirstClassType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6f4eef604ff06e2b83fabf52e828c709">anonymous{ConstantFolding.cpp}::CastGEPIndices</a> and <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga25848ab388e076273d3f5c37e93e741a">LLVMGetCastOpcode</a>.</p>

</div>
</div>

### isBitCastable() {#aa2915714199e899f7766d49f87ec2ad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CastInst::isBitCastable (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DestTy)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a bitcast between these types is valid.</p>

<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3085 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a82a7e98c00f5bb12e2c5481fe0ab3f1a">llvm::Type::isFirstClassType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#a4813065b259c6f6a34961b286913f06c">llvm::coro::AnyRetconABI::init</a> and <a href="#a94f850488e8bda1d1b400821d6d61bd1">isBitOrNoopPointerCastable</a>.</p>

</div>
</div>

### isBitOrNoopPointerCastable() {#a94f850488e8bda1d1b400821d6d61bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CastInst::isBitOrNoopPointerCastable (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DestTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a bitcast, inttoptr, or ptrtoint cast between these types is valid and a no-op.</p>


<p>This ensures that any pointer&lt;-&gt;integer cast has enough bits in the integer and any other cast is a bitcast.</p>


<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3122 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#aa2915714199e899f7766d49f87ec2ad6">isBitCastable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a5662a5eb5436e4a9301827cca40b9b93">createBitOrPointerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#ad870908842303e62050abc131f00f91f">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::findStoreToLoadDependences</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#adccfbc5892aaeafbf2178ddc7c71bde5">getAvailableLoadStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aa602c4415d92f7060b1c0f1255fcf79d">isSupportedAccessType</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>.</p>

</div>
</div>

### isEliminableCastPair() {#a8b805c54dc1ead67b711a4b1cb72f492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CastInst::isEliminableCastPair (<a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> firstOp, <a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> secondOp, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * MidTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcIntPtrTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * MidIntPtrTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DstIntPtrTy)</td>
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

<p>Determine how a pair of casts can be eliminated, if they can be at all.</p>


<p>This function determines if a pair of casts can be eliminated and what opcode should be used in the elimination.</p>


<p>This is a helper function for both <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> and <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>0 if the <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> pair can't be eliminated, otherwise returns <a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> value for a cast that can replace the pair, casting SrcTy to DstTy. Determine if a cast pair is eliminable</p></dd>
</dl>


<p>This assumes that there are two instructions like this:</p>


<ul class="doxyList ">
<li>F = firstOpcode SrcTy x to MidTy</li>
<li>S = secondOpcode MidTy F to DstTy The function returns a resultOpcode so these two casts can be replaced with:</li>
<li>Replacement = resultOpcode SrcTy x to DstTy If no such cast is permitted, the function returns 0.</li>
</ul>

<p>Declaration at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2759 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a6032de0100164827a23f768261b4d53f">DisableI2pP2iOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a08c03a4228af93098afb6ab60e7283f6">foldConstantCastPair</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#abfcd971ce6ccafa5489dd3bf313219af">simplifyCastInst</a>.</p>

</div>
</div>

### isNoopCast() {#ace4c7b4bc6aba9506b1b60aac18881f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CastInst::isNoopCast (<a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SrcTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DestTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>A no-op cast is one that can be effected without changing any bits.</p>


<p>This function determines if the <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> does not require any bits to be changed in order to effect the cast.</p>


<p>It implies that the source and destination types are the same size. The <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> argument is to determine the pointer size when examining casts involving Integer and Pointer types. They are no-op casts if the integer is the same size as the pointer. However, pointer size varies with platform. Note that a precondition of this method is that the cast is legal - i.e. the instruction formed with these operands would verify.</p>


<p>Essentially, it identifies cases where no code gen is necessary for the cast, hence the name no-op cast. For example, the following are all no-op casts:</p>


## bitcast i32\* x to i8\* {#autotoc_md65}


## bitcast &lt;2 x i32&gt; x to &lt;4 x i16&gt; {#autotoc_md66}


## ptrtoint i32\* x to i32 ; on 32-bit plaforms only {#autotoc_md67}


<p>Determine if the described cast is a no-op.</p>


<p>Declaration at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 2717 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af0e9f16b79d49af44209f202b31290a1">castIsValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a1438002c91e6e1c7a587a194b268239d">isNoopCast</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a44232befb736ff8d861bd991a5a68239">isNoopPtrIntCastPair</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
