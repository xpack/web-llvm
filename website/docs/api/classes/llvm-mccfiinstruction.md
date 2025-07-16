---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mccfiinstruction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCCFIInstruction` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCCFIInstruction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OpType : uint8_t { <a href="#aaf905b9d7696f2b8da2e4c89c860f6ec">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f86a21ebeb7c0d0600572c681f60b5">MCCFIInstruction</a> (OpType Op, MCSymbol *L, unsigned R, int64_t O, SMLoc Loc, StringRef V="", StringRef Comment="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81dc0f35f9cf5345072417960c948397">MCCFIInstruction</a> (OpType Op, MCSymbol *L, unsigned R1, unsigned R2, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a5bc293d2849b2a55d486ec37688bc8">MCCFIInstruction</a> (OpType Op, MCSymbol *L, unsigned R, int64_t O, unsigned AS, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a476dd07903cd873f379b4fb900373a22">MCCFIInstruction</a> (OpType Op, MCSymbol *L, MCSymbol *CfiLabel, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaf905b9d7696f2b8da2e4c89c860f6ec">OpType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d7ee9c6eaabde95dd9695326a77f253">getOperation</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0607bec0f8845b94270b8039f0d975ce">getLabel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57846002cda511da6585cb417cf9d392">getRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49509b83b020570fb6efb6c2b10b7b6f">getRegister2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a07e509ef445f6d35b9e7cfd3bed74">getAddressSpace</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef30e8b2caf06dd1513a1c9aacf45097">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d1d1b430facb52916c3fd6458bc10c">getCfiLabel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb6341197e146d69c1fa9cbde53f22d4">getValues</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaebbb9a44e37ca37f2c4e47266ca9dbd">getComment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b96d4b3808f7c4beee57bcb394246bf">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee04ad715305095660699ec6c51d6b91">Register</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5a5b785d4b4e1b2557a7802bfae647">Offset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c967af9a5607f8b0ce2cd7ec8f71398">RI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64bfb5a7f9cb64315cf51c91295c20a3">AddressSpace</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57c6670f5c9ff5c45b3ed2487686f443">RIA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c26d2b2bee165324d19edade6b4dea9">Register2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c13041282a10acee22c5f49389b04c7">RR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad91975cf8ffb5b614aa91d07d5954213">CfiLabel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c87bd8b29d053541903b01788f77ff">Label</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">llvm::MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657b5b3e36c0b5357c4fddcf1e8aca9c">U</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaf905b9d7696f2b8da2e4c89c860f6ec">OpType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a934ad805d8a3a69e77349ece1a804932">Operation</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abddce33f0c6a0bdb7629385fbd80ddec">Loc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98f3de834524a7fe9541280c4a0acfbb">Values</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae07a88c2c22602d287fd13f88ccf03f4">Comment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64fe578753bb594671a8e440e32a2b95">cfiDefCfa</a> (MCSymbol *L, unsigned Register, int64_t Offset, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_def_cfa defines a rule for computing CFA as: take address from <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> and add Offset to it. <a href="#a64fe578753bb594671a8e440e32a2b95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03445be1c81520587d5bb31b353f5558">createDefCfaRegister</a> (MCSymbol *L, unsigned Register, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_def_cfa_register modifies a rule for computing CFA. <a href="#a03445be1c81520587d5bb31b353f5558">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbe481ab35db0dcfa03f9f5bbabb9def">cfiDefCfaOffset</a> (MCSymbol *L, int64_t Offset, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_def_cfa_offset modifies a rule for computing CFA. <a href="#abbe481ab35db0dcfa03f9f5bbabb9def">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a85756410e7929f561fc1454069563">createAdjustCfaOffset</a> (MCSymbol *L, int64_t Adjustment, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_adjust_cfa_offset Same as .cfi_def_cfa_offset, but Offset is a relative value that is added/subtracted from the previous offset. <a href="#ad6a85756410e7929f561fc1454069563">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5243e6ada761524b2689a8b52cbe9d0c">createLLVMDefAspaceCfa</a> (MCSymbol *L, unsigned Register, int64_t Offset, unsigned AddressSpace, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_llvm_def_aspace_cfa defines the rule for computing the CFA to be the result of evaluating the DWARF operation expression <span class="doxyComputerOutput">DW_OP_constu AS; DW_OP_aspace_bregx R, B</span> as a location description. <a href="#a5243e6ada761524b2689a8b52cbe9d0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a60a82f8cb445e9e7029e38733b2d30">createOffset</a> (MCSymbol *L, unsigned Register, int64_t Offset, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_offset Previous value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is saved at offset Offset from CFA. <a href="#a6a60a82f8cb445e9e7029e38733b2d30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f57b410a806f657695bfb7e19400c0">createRelOffset</a> (MCSymbol *L, unsigned Register, int64_t Offset, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_rel_offset Previous value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is saved at offset Offset from the current CFA register. <a href="#ae4f57b410a806f657695bfb7e19400c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5efbfe5cee3e83355dec981c2d43611f">createRegister</a> (MCSymbol *L, unsigned Register1, unsigned Register2, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_register Previous value of Register1 is saved in register Register2. <a href="#a5efbfe5cee3e83355dec981c2d43611f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd3d6ea5364f4dd2460d0e31a191de4">createWindowSave</a> (MCSymbol *L, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_window_save SPARC register window is saved. <a href="#acdd3d6ea5364f4dd2460d0e31a191de4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897ff5de2f1ce15003e513758c7cf7b1">createNegateRAState</a> (MCSymbol *L, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_negate_ra_state <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> negate RA state. <a href="#a897ff5de2f1ce15003e513758c7cf7b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8546686a46d43f38c7104b866513fa2e">createNegateRAStateWithPC</a> (MCSymbol *L, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_negate_ra_state_with_pc <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> negate RA state with PC. <a href="#a8546686a46d43f38c7104b866513fa2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43cce47857fdb1dfec97aeba83ab82a3">createRestore</a> (MCSymbol *L, unsigned Register, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_restore says that the rule for <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is now the same as it was at the beginning of the function, after all initial instructions added by .cfi_startproc were executed. <a href="#a43cce47857fdb1dfec97aeba83ab82a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a4f533e313a1288ce2cad49aa92d5e5">createUndefined</a> (MCSymbol *L, unsigned Register, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_undefined From now on the previous value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> can't be restored anymore. <a href="#a1a4f533e313a1288ce2cad49aa92d5e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae43652fadd6c5abd6a6554cd3395baee">createSameValue</a> (MCSymbol *L, unsigned Register, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_same_value Current value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is the same as in the previous frame. <a href="#ae43652fadd6c5abd6a6554cd3395baee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c6c95634a9db9cd0fc23175a01afd80">createRememberState</a> (MCSymbol *L, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_remember_state Save all current rules for all registers. <a href="#a8c6c95634a9db9cd0fc23175a01afd80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bed50736717b1120a41c6dcc41428f">createRestoreState</a> (MCSymbol *L, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_restore_state Restore the previously saved state. <a href="#ae2bed50736717b1120a41c6dcc41428f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6eb36207cf2c7ebbd9a67e63dcc5568">createEscape</a> (MCSymbol *L, StringRef Vals, SMLoc Loc={}, StringRef Comment="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_escape Allows the user to add arbitrary bytes to the unwind info. <a href="#ac6eb36207cf2c7ebbd9a67e63dcc5568">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2097ca045c7251b81f97c5fc3efdcfc8">createGnuArgsSize</a> (MCSymbol *L, int64_t Size, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A special wrapper for .cfi_escape that indicates GNU_ARGS_SIZE. <a href="#a2097ca045c7251b81f97c5fc3efdcfc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af806d86ab5b0d3a03de968f53959d056">createLabel</a> (MCSymbol *L, MCSymbol *CfiLabel, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8114c7601abcdb9e9fcf48c8abce7fb9">createValOffset</a> (MCSymbol *L, unsigned Register, int64_t Offset, SMLoc Loc={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.cfi_val_offset Previous value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is offset Offset from the current CFA register. <a href="#a8114c7601abcdb9e9fcf48c8abce7fb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### OpType {#aaf905b9d7696f2b8da2e4c89c860f6ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCCFIInstruction::OpType : uint8_t</td>
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
<td class="doxyEnumItemName">OpSameValue<a id="aaf905b9d7696f2b8da2e4c89c860f6ecab85cb8f2dc33b315db03abc258d2d7d0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpRememberState<a id="aaf905b9d7696f2b8da2e4c89c860f6eca9725887cea764021d6f8d670f28f1ae5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpRestoreState<a id="aaf905b9d7696f2b8da2e4c89c860f6eca52e7e859e3f36138023caadf8991d04b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpOffset<a id="aaf905b9d7696f2b8da2e4c89c860f6eca74ec33979cec7221719caa137b50da3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpLLVMDefAspaceCfa<a id="aaf905b9d7696f2b8da2e4c89c860f6eca41d79805b057315fb8e3593987b4fe6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpDefCfaRegister<a id="aaf905b9d7696f2b8da2e4c89c860f6eca238c64d5f2c2fea57085c0238948b04f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpDefCfaOffset<a id="aaf905b9d7696f2b8da2e4c89c860f6eca5822faf65b27795cd48bd44712d48927"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpDefCfa<a id="aaf905b9d7696f2b8da2e4c89c860f6ecacbbd41f459c6cea155b66a7ba10f1058"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpRelOffset<a id="aaf905b9d7696f2b8da2e4c89c860f6eca829be22c6230d5b270c57913ab767d66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpAdjustCfaOffset<a id="aaf905b9d7696f2b8da2e4c89c860f6ecaea7047186e58e6304947fbe2b12963ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpEscape<a id="aaf905b9d7696f2b8da2e4c89c860f6ecaf15acea66ebc677cba2af933cc86c953"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpRestore<a id="aaf905b9d7696f2b8da2e4c89c860f6ecab1624e2be4e6b5b590bcc4743241c0a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpUndefined<a id="aaf905b9d7696f2b8da2e4c89c860f6eca3d6a7342ab1bccb9ac138911f12e2eb4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpRegister<a id="aaf905b9d7696f2b8da2e4c89c860f6eca47154c1d7af6be5e653ad8d1647efef1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpWindowSave<a id="aaf905b9d7696f2b8da2e4c89c860f6eca3316e063e766219c3a12d004d2d10afd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpNegateRAState<a id="aaf905b9d7696f2b8da2e4c89c860f6ecaa66d4b16f63e1a1f48ab0a412e105d84"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpNegateRAStateWithPC<a id="aaf905b9d7696f2b8da2e4c89c860f6eca66624166e3d049539c5275c2a92993bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpGnuArgsSize<a id="aaf905b9d7696f2b8da2e4c89c860f6eca3f760b48a6b6d7dbd15f414986c12dc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpLabel<a id="aaf905b9d7696f2b8da2e4c89c860f6ecad8166a4b87f2c30cb19a0d8095736fd6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpValOffset<a id="aaf905b9d7696f2b8da2e4c89c860f6eca9bc8a1d177bcfde894a63285618df9c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MCCFIInstruction() {#a29f86a21ebeb7c0d0600572c681f60b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCCFIInstruction::MCCFIInstruction (<a href="#aaf905b9d7696f2b8da2e4c89c860f6ec">OpType</a> Op, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned R, int64_t O, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> V="", <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Comment="")</td>
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



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### MCCFIInstruction() {#a81dc0f35f9cf5345072417960c948397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCCFIInstruction::MCCFIInstruction (<a href="#aaf905b9d7696f2b8da2e4c89c860f6ec">OpType</a> Op, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned R1, unsigned R2, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### MCCFIInstruction() {#a1a5bc293d2849b2a55d486ec37688bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCCFIInstruction::MCCFIInstruction (<a href="#aaf905b9d7696f2b8da2e4c89c860f6ec">OpType</a> Op, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned R, int64_t O, unsigned AS, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### MCCFIInstruction() {#a476dd07903cd873f379b4fb900373a22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCCFIInstruction::MCCFIInstruction (<a href="#aaf905b9d7696f2b8da2e4c89c860f6ec">OpType</a> Op, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * CfiLabel, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddressSpace() {#a31a07e509ef445f6d35b9e7cfd3bed74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCCFIInstruction::getAddressSpace ()</td>
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



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca41d79805b057315fb8e3593987b4fe6d">OpLLVMDefAspaceCfa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae485f2c7965fde7294a28a57874e9387">llvm::AsmPrinter::emitCFIInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>.</p>

</div>
</div>

### getCfiLabel() {#ae1d1d1b430facb52916c3fd6458bc10c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::MCCFIInstruction::getCfiLabel ()</td>
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



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaf905b9d7696f2b8da2e4c89c860f6ecad8166a4b87f2c30cb19a0d8095736fd6">OpLabel</a>.</p>

</div>
</div>

### getComment() {#aaebbb9a44e37ca37f2c4e47266ca9dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCCFIInstruction::getComment ()</td>
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



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae485f2c7965fde7294a28a57874e9387">llvm::AsmPrinter::emitCFIInstruction</a>.</p>

</div>
</div>

### getLabel() {#a0607bec0f8845b94270b8039f0d975ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::MCCFIInstruction::getLabel ()</td>
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



<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>.</p>

</div>
</div>

### getLoc() {#a6b96d4b3808f7c4beee57bcb394246bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCCFIInstruction::getLoc ()</td>
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



<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae485f2c7965fde7294a28a57874e9387">llvm::AsmPrinter::emitCFIInstruction</a>.</p>

</div>
</div>

### getOffset() {#aef30e8b2caf06dd1513a1c9aacf45097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MCCFIInstruction::getOffset ()</td>
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



<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6ecaea7047186e58e6304947fbe2b12963ca">OpAdjustCfaOffset</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6ecacbbd41f459c6cea155b66a7ba10f1058">OpDefCfa</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca5822faf65b27795cd48bd44712d48927">OpDefCfaOffset</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca3f760b48a6b6d7dbd15f414986c12dc9">OpGnuArgsSize</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca41d79805b057315fb8e3593987b4fe6d">OpLLVMDefAspaceCfa</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca74ec33979cec7221719caa137b50da3f">OpOffset</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca829be22c6230d5b270c57913ab767d66">OpRelOffset</a> and <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca9bc8a1d177bcfde894a63285618df9c9">OpValOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae485f2c7965fde7294a28a57874e9387">llvm::AsmPrinter::emitCFIInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#a26e5b6731c22761e5c4e7abe1dc13a21">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>.</p>

</div>
</div>

### getOperation() {#a9d7ee9c6eaabde95dd9695326a77f253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpType llvm::MCCFIInstruction::getOperation ()</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aef0079a40a972f2942156b2d73bbf190">llvm::X86FrameLowering::BuildCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae485f2c7965fde7294a28a57874e9387">llvm::AsmPrinter::emitCFIInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#a26e5b6731c22761e5c4e7abe1dc13a21">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a94c1ab02555b5022baf4e16d66032338">maybeMoveCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af1d6349ca67f14c36e41916e41536da4">llvm::X86FrameLowering::mergeSPUpdates</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>.</p>

</div>
</div>

### getRegister() {#a57846002cda511da6585cb417cf9d392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCCFIInstruction::getRegister ()</td>
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



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6ecacbbd41f459c6cea155b66a7ba10f1058">OpDefCfa</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca238c64d5f2c2fea57085c0238948b04f">OpDefCfaRegister</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca41d79805b057315fb8e3593987b4fe6d">OpLLVMDefAspaceCfa</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca74ec33979cec7221719caa137b50da3f">OpOffset</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca47154c1d7af6be5e653ad8d1647efef1">OpRegister</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca829be22c6230d5b270c57913ab767d66">OpRelOffset</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6ecab1624e2be4e6b5b590bcc4743241c0a8">OpRestore</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6ecab85cb8f2dc33b315db03abc258d2d7d0">OpSameValue</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca3d6a7342ab1bccb9ac138911f12e2eb4">OpUndefined</a> and <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca9bc8a1d177bcfde894a63285618df9c9">OpValOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae485f2c7965fde7294a28a57874e9387">llvm::AsmPrinter::emitCFIInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#a26e5b6731c22761e5c4e7abe1dc13a21">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>.</p>

</div>
</div>

### getRegister2() {#a49509b83b020570fb6efb6c2b10b7b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCCFIInstruction::getRegister2 ()</td>
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



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca47154c1d7af6be5e653ad8d1647efef1">OpRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae485f2c7965fde7294a28a57874e9387">llvm::AsmPrinter::emitCFIInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>.</p>

</div>
</div>

### getValues() {#abb6341197e146d69c1fa9cbde53f22d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCCFIInstruction::getValues ()</td>
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



<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaf905b9d7696f2b8da2e4c89c860f6ecaf15acea66ebc677cba2af933cc86c953">OpEscape</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae485f2c7965fde7294a28a57874e9387">llvm::AsmPrinter::emitCFIInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddressSpace {#a64bfb5a7f9cb64315cf51c91295c20a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCCFIInstruction::AddressSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#a5243e6ada761524b2689a8b52cbe9d0c">createLLVMDefAspaceCfa</a>.</p>

</div>
</div>

### CfiLabel {#ad91975cf8ffb5b614aa91d07d5954213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCCFIInstruction::CfiLabel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#af806d86ab5b0d3a03de968f53959d056">createLabel</a>.</p>

</div>
</div>

### Offset {#a9e5a5b785d4b4e1b2557a7802bfae647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MCCFIInstruction::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#a64fe578753bb594671a8e440e32a2b95">cfiDefCfa</a>, <a href="#abbe481ab35db0dcfa03f9f5bbabb9def">cfiDefCfaOffset</a>, <a href="#a5243e6ada761524b2689a8b52cbe9d0c">createLLVMDefAspaceCfa</a>, <a href="#a6a60a82f8cb445e9e7029e38733b2d30">createOffset</a>, <a href="#ae4f57b410a806f657695bfb7e19400c0">createRelOffset</a> and <a href="#a8114c7601abcdb9e9fcf48c8abce7fb9">createValOffset</a>.</p>

</div>
</div>

### Register {#aee04ad715305095660699ec6c51d6b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCCFIInstruction::Register</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#a64fe578753bb594671a8e440e32a2b95">cfiDefCfa</a>, <a href="#a03445be1c81520587d5bb31b353f5558">createDefCfaRegister</a>, <a href="#a5243e6ada761524b2689a8b52cbe9d0c">createLLVMDefAspaceCfa</a>, <a href="#a6a60a82f8cb445e9e7029e38733b2d30">createOffset</a>, <a href="#ae4f57b410a806f657695bfb7e19400c0">createRelOffset</a>, <a href="#a43cce47857fdb1dfec97aeba83ab82a3">createRestore</a>, <a href="#ae43652fadd6c5abd6a6554cd3395baee">createSameValue</a>, <a href="#a1a4f533e313a1288ce2cad49aa92d5e5">createUndefined</a> and <a href="#a8114c7601abcdb9e9fcf48c8abce7fb9">createValOffset</a>.</p>

</div>
</div>

### Register2 {#a4c26d2b2bee165324d19edade6b4dea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCCFIInstruction::Register2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#a5efbfe5cee3e83355dec981c2d43611f">createRegister</a>.</p>

</div>
</div>

### RI {#a9c967af9a5607f8b0ce2cd7ec8f71398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::MCCFIInstruction llvm::MCCFIInstruction::RI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### RIA {#a57c6670f5c9ff5c45b3ed2487686f443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::MCCFIInstruction llvm::MCCFIInstruction::RIA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### RR {#a6c13041282a10acee22c5f49389b04c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::MCCFIInstruction llvm::MCCFIInstruction::RR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Comment {#ae07a88c2c22602d287fd13f88ccf03f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCCFIInstruction::Comment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### Label {#ac0c87bd8b29d053541903b01788f77ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCCFIInstruction::Label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### Loc {#abddce33f0c6a0bdb7629385fbd80ddec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCCFIInstruction::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### Operation {#a934ad805d8a3a69e77349ece1a804932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpType llvm::MCCFIInstruction::Operation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### U {#a657b5b3e36c0b5357c4fddcf1e8aca9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::MCCFIInstruction llvm::MCCFIInstruction::U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### Values {#a98f3de834524a7fe9541280c4a0acfbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;char&gt; llvm::MCCFIInstruction::Values</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### cfiDefCfa() {#a64fe578753bb594671a8e440e32a2b95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::cfiDefCfa (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_def_cfa defines a rule for computing CFA as: take address from <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> and add Offset to it.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="#a9e5a5b785d4b4e1b2557a7802bfae647">Offset</a> and <a href="#aee04ad715305095660699ec6c51d6b91">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ae215c9475e5b6a8ae5efa8ff60202dfe">createAArch64MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcmctargetdesc-cpp/#a1565c040d38239145f29ebdacdbc9960">createARCMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#af517e546ece4970a718601f99698bb82">createARMMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#ad68a92d238fff893e319960f0f041c2e">createCSKYMCAsmInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1170c3796a8947456c2d7841642b96eb">llvm::createDefCFA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ad7b9e848c3ce6d787fb6bea4dd329e1c">createHexagonMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a6ed6f31ffab8182a589835bc963da246">createLoongArchMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a3f5da376731086646a271047c4e96c08">createM68kMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae59e9e7664d68a9e1be3952fae4a5d56">createMSP430MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#ac87ba800a84c083b0ff262ecb6b7f2a4">createPPCMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#ada9867cc472d39a0fd48dee8f5890156">createRISCVMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a1bc684eccb765b481edaf1bfa0de9897">createSparcMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a2d97a732765b2f5e4ffc1541a191facb">createSparcV9MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#ac73ad4da40108adef2c801643363b333">createSystemZMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#a14864e8babd0d6b24342db6e6b2ca9fd">createVEMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoremctargetdesc-cpp/#a4526e8f149bf434d68660772e445d1f1">createXCoreMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a06d947eb9b24c3c09aec7dae8b242d36">llvm::MCStreamer::emitCFIDefCfa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1886741049357a9b7cea7f8e8784a818">emitDefineCFAWithFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a3a9df23d95cdadc6a77b12dc3377a331">llvm::MSP430FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a5c22366d9b2f68fba8285148c794a74d">llvm::AArch64FrameLowering::resetCFIToInitialState</a>.</p>

</div>
</div>

### cfiDefCfaOffset() {#abbe481ab35db0dcfa03f9f5bbabb9def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::cfiDefCfaOffset (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_def_cfa_offset modifies a rule for computing CFA.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> remains the same, but offset is new. Note that it is the absolute offset that will be added to a defined register to the compute CFA address.</p>


<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Reference <a href="#a9e5a5b785d4b4e1b2557a7802bfae647">Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ab08619b14fe0d6edc17b186c5a452e9e">buildCFAOffs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a73f427af3525340f74d7e85b984b82d6">convertCalleeSaveRestoreToSPPrePostIncDec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1170c3796a8947456c2d7841642b96eb">llvm::createDefCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad00e491df6ac397c2836f4823486b814">llvm::MCStreamer::emitCFIDefCfaOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a794b27dd421465dc20f1f47855a75a5c">EmitDefCfaOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-armframelowering-cpp-/stackadjustinginsts/#a042cf3c899a8ad17fe7a9509c1ed60c4">anonymous{ARMFrameLowering.cpp}::StackAdjustingInsts::emitDefCFAOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a3a9df23d95cdadc6a77b12dc3377a331">llvm::MSP430FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a921a457b786497c2309b9f63abd9c951">llvm::MSP430FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createAdjustCfaOffset() {#ad6a85756410e7929f561fc1454069563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createAdjustCfaOffset (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, int64_t Adjustment, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_adjust_cfa_offset Same as .cfi_def_cfa_offset, but Offset is a relative value that is added/subtracted from the previous offset.</p>

<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a9a9a690dd5678ad91fe6622af79116fd">llvm::M68kFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ab30ade3265bd079731057aafc0ff6e9f">llvm::MSP430FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aa5f78769915f0742f77e73e45abab318">llvm::X86FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab98cdd0259874847cd346b396f87ed29">llvm::MCStreamer::emitCFIAdjustCfaOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createDefCfaRegister() {#a03445be1c81520587d5bb31b353f5558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createDefCfaRegister (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_def_cfa_register modifies a rule for computing CFA.</p>


<p>From now on <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> will be used instead of the old one. Offset remains the same.</p>


<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Reference <a href="#aee04ad715305095660699ec6c51d6b91">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a28391c59e5f478e4513f021226549734">buildDefCFAReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#aa98f7a893c9bee1f49edf77722615817">createMipsMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa3cb8bdbc2ba4f13b85ae876c8db72c8">llvm::MCStreamer::emitCFIDefCfaRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#ae193832c4a427e1aa8a6ad3240a0898e">EmitDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a921a457b786497c2309b9f63abd9c951">llvm::MSP430FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createEscape() {#ac6eb36207cf2c7ebbd9a67e63dcc5568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createEscape (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Vals, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={}, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Comment="")</td>
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

<p>.cfi_escape Allows the user to add arbitrary bytes to the unwind info.</p>

<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd95c4fd57b9c1804bc70a37ac24574">llvm::createCFAOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad301df8bf0c11d0c17113d3c221025d8">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af7b1b04b85a4e865d887cbf6f5889a10">createDefCFAOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7f85a7656080c1cece6d55421409c2ac">llvm::MCStreamer::emitCFIEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ae5f813adf7cab5ad0f7a542b681ca95c">emitShadowCallStackPrologue</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createGnuArgsSize() {#a2097ca045c7251b81f97c5fc3efdcfc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createGnuArgsSize (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, int64_t Size, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>A special wrapper for .cfi_escape that indicates GNU_ARGS_SIZE.</p>

<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a9a9a690dd5678ad91fe6622af79116fd">llvm::M68kFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aa5f78769915f0742f77e73e45abab318">llvm::X86FrameLowering::eliminateCallFramePseudoInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a00b5e27ba702e289d1355d83634496e8">llvm::MCStreamer::emitCFIGnuArgsSize</a>.</p>

</div>
</div>

### createLabel() {#af806d86ab5b0d3a03de968f53959d056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * CfiLabel, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="#ad91975cf8ffb5b614aa91d07d5954213">CfiLabel</a> and <a href="#aaf905b9d7696f2b8da2e4c89c860f6ecad8166a4b87f2c30cb19a0d8095736fd6">OpLabel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a886df281f466da825e86d3db00309322">llvm::MCStreamer::emitCFILabelDirective</a>.</p>

</div>
</div>

### createLLVMDefAspaceCfa() {#a5243e6ada761524b2689a8b52cbe9d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createLLVMDefAspaceCfa (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register, int64_t Offset, unsigned AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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

<p>.cfi_llvm_def_aspace_cfa defines the rule for computing the CFA to be the result of evaluating the DWARF operation expression <span class="doxyComputerOutput">DW_OP_constu AS; DW_OP_aspace_bregx R, B</span> as a location description.</p>

<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="#a64bfb5a7f9cb64315cf51c91295c20a3">AddressSpace</a>, <a href="#a9e5a5b785d4b4e1b2557a7802bfae647">Offset</a>, <a href="#aaf905b9d7696f2b8da2e4c89c860f6eca41d79805b057315fb8e3593987b4fe6d">OpLLVMDefAspaceCfa</a> and <a href="#aee04ad715305095660699ec6c51d6b91">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afd9cd40e1c8cda6d287b38bbbc4a65dd">llvm::MCStreamer::emitCFILLVMDefAspaceCfa</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createNegateRAState() {#a897ff5de2f1ce15003e513758c7cf7b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createNegateRAState (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_negate_ra_state <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> negate RA state.</p>

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5e417903a64e0e2e03a881cc22988c03">llvm::MCStreamer::emitCFINegateRAState</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#a181216377a992592ea7e30fc0ce07f0d">emitPACCFI</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a5c22366d9b2f68fba8285148c794a74d">llvm::AArch64FrameLowering::resetCFIToInitialState</a>.</p>

</div>
</div>

### createNegateRAStateWithPC() {#a8546686a46d43f38c7104b866513fa2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createNegateRAStateWithPC (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_negate_ra_state_with_pc <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> negate RA state with PC.</p>

<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2f9a65946cfd95e5fee5434be8061fba">llvm::MCStreamer::emitCFINegateRAStateWithPC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#a181216377a992592ea7e30fc0ce07f0d">emitPACCFI</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a5c22366d9b2f68fba8285148c794a74d">llvm::AArch64FrameLowering::resetCFIToInitialState</a>.</p>

</div>
</div>

### createOffset() {#a6a60a82f8cb445e9e7029e38733b2d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createOffset (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_offset Previous value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is saved at offset Offset from CFA.</p>

<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="#a9e5a5b785d4b4e1b2557a7802bfae647">Offset</a> and <a href="#aee04ad715305095660699ec6c51d6b91">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd95c4fd57b9c1804bc70a37ac24574">llvm::createCFAOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a3f5da376731086646a271047c4e96c08">createM68kMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae59e9e7664d68a9e1be3952fae4a5d56">createMSP430MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#aeafb06413605da840d52ad76655540e8">createX86MCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvframelowering-cpp-/cfisaveregisteremitter/#aeaf54bb6240fb6bea4e1cd52e6a74ae1">anonymous{RISCVFrameLowering.cpp}::CFISaveRegisterEmitter::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a66fceb6b28377362e963e250c5c865c1">llvm::MSP430FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#acbd4fee4d18fa2066d758dff7168ef36">llvm::X86FrameLowering::emitCalleeSavedFrameMovesFullCFA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a6b6e001aaffc1977dbbfa8570ffe6565">EmitCfiOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc89f9e1b110cc78d0b3782c7169fee3">llvm::MCStreamer::emitCFIOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a921a457b786497c2309b9f63abd9c951">llvm::MSP430FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createRegister() {#a5efbfe5cee3e83355dec981c2d43611f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createRegister (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register1, unsigned Register2, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_register Previous value of Register1 is saved in register Register2.</p>

<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Reference <a href="#a4c26d2b2bee165324d19edade6b4dea9">Register2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa640c4cba0755dc19a91bdb98fec5998">llvm::MCStreamer::emitCFIRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createRelOffset() {#ae4f57b410a806f657695bfb7e19400c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createRelOffset (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_rel_offset Previous value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is saved at offset Offset from the current CFA register.</p>


<p>This is transformed to .cfi_offset using the known displacement of the CFA register from the CFA.</p>


<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="#a9e5a5b785d4b4e1b2557a7802bfae647">Offset</a> and <a href="#aee04ad715305095660699ec6c51d6b91">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac21d03105248455242c40d1b663dfea1">llvm::MCStreamer::emitCFIRelOffset</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createRememberState() {#a8c6c95634a9db9cd0fc23175a01afd80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createRememberState (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_remember_state Save all current rules for all registers.</p>

<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a861747a0f3a48a53fdff7bdc6c1856d8">llvm::MCStreamer::emitCFIRememberState</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a313dff6a75b3ae9c5c5d6802f3007a56">insertRememberRestorePair</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createRestore() {#a43cce47857fdb1dfec97aeba83ab82a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createRestore (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_restore says that the rule for <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is now the same as it was at the beginning of the function, after all initial instructions added by .cfi_startproc were executed.</p>

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Reference <a href="#aee04ad715305095660699ec6c51d6b91">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvframelowering-cpp-/cfirestoreregisteremitter/#a92aa2c10d7a31b9713443dd938973738">anonymous{RISCVFrameLowering.cpp}::CFIRestoreRegisterEmitter::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a66fceb6b28377362e963e250c5c865c1">llvm::MSP430FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af5f8c58b6d8f44d96b1f1d02ba7af4af">llvm::MCStreamer::emitCFIRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a3a9df23d95cdadc6a77b12dc3377a331">llvm::MSP430FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a02cddefc96e08fba507c3d0eac7f6c1f">emitShadowCallStackEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createRestoreState() {#ae2bed50736717b1120a41c6dcc41428f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createRestoreState (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_restore_state Restore the previously saved state.</p>

<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aca048ea2881b4d098c005349f99bab62">llvm::MCStreamer::emitCFIRestoreState</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a313dff6a75b3ae9c5c5d6802f3007a56">insertRememberRestorePair</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createSameValue() {#ae43652fadd6c5abd6a6554cd3395baee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createSameValue (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_same_value Current value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is the same as in the previous frame.</p>


<p>I.e., no restoration is needed.</p>


<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Reference <a href="#aee04ad715305095660699ec6c51d6b91">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a30e73886a8c818640b69a5ca9dfe3b60">llvm::MCStreamer::emitCFISameValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2faad2c2b19346a6b6d4e497e3619169">insertCFISameValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createUndefined() {#a1a4f533e313a1288ce2cad49aa92d5e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createUndefined (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_undefined From now on the previous value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> can't be restored anymore.</p>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Reference <a href="#aee04ad715305095660699ec6c51d6b91">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a52d332cc8f6e4738d2b9c3f78ab28f1a">llvm::MCStreamer::emitCFIUndefined</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### createValOffset() {#a8114c7601abcdb9e9fcf48c8abce7fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createValOffset (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Register, int64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_val_offset Previous value of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is offset Offset from the current CFA register.</p>

<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="#a9e5a5b785d4b4e1b2557a7802bfae647">Offset</a> and <a href="#aee04ad715305095660699ec6c51d6b91">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae0930d72d21ce9df1f3d41b685411bd9">llvm::MCStreamer::emitCFIValOffset</a>.</p>

</div>
</div>

### createWindowSave() {#acdd3d6ea5364f4dd2460d0e31a191de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction llvm::MCCFIInstruction::createWindowSave (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc={})</td>
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

<p>.cfi_window_save SPARC register window is saved.</p>

<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a396af4f92c9743bcf60f86474c7ebadf">llvm::MCStreamer::emitCFIWindowSave</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
