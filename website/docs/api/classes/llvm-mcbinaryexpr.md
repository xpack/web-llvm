---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcbinaryexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCBinaryExpr` Class Reference

<p>Binary assembler expressions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCBinaryExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for the full range of assembler expressions which are needed for parsing. <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Opcode { <a href="#afcbc8d46b6339dbbbe1af20c9c876629">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa11fec3318fc6e8a0b00842933ecbe11">MCBinaryExpr</a> (Opcode Op, const MCExpr *LHS, const MCExpr *RHS, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb20cbdce11e328cb0ea417832ae0b05">LHS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af76173126807a2d54af21335bf9e81c7">RHS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48adca21667701ac41350cfe0d5b2cf6">classof</a> (const MCExpr *E)</td>
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

## Construction Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac393df34745cae1433909c2049978bd4">create</a> (Opcode Op, const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx, SMLoc Loc=SMLoc())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cbe1086ebf00680e8dc374e07305cfb">createAdd</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d8557c5bc9e9a92ce9b663e21f5e47">createAnd</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf02d969009762015e1f45b7f9b17e90">createDiv</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fc65c1c33d36926fade150b9205991">createEQ</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1c84873133c2893284f143e3949b15b">createGT</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a944476a319c4dddd25f49bf1da4d1e9e">createGTE</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18d807a1b5c938811456307bfd3560b1">createLAnd</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a786dd04a46593c07b33f81fdc919ee4f">createLOr</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d82c00c5a59ac45d7fe9fbf7fdb256">createLT</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa681023ab973e112d1aeaad5ad6b6806">createLTE</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c32a58780aa68e18e47e0bfac6ad15">createMod</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a994d277dcd8d2765f20ddb1e81a1187e">createMul</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0a201b1e3eb4fe198d3eec3bc6ad61">createNE</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b303b433f43b901194dbf17adfb562c">createOr</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fa97ac31d48ef7708ba959db34f38d">createShl</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf1cb4447353da4a08ae3b5d55ca3eda">createAShr</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18a49f94de6b90d6fbc0c730b6a2ae5b">createLShr</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af766134165065939f49fb0662c246f66">createSub</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr">MCBinaryExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f6e7794e457483f87961dfb8ed3f06">createXor</a> (const MCExpr *LHS, const MCExpr *RHS, MCContext &amp;Ctx)</td>
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

## Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afcbc8d46b6339dbbbe1af20c9c876629">Opcode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5606d070331bbd494bcd8fe374540d4e">getOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the kind of this binary expression. <a href="#a5606d070331bbd494bcd8fe374540d4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071993fe404ae3387526e7a104b0f38c">getLHS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the left-hand side expression of the binary operator. <a href="#a071993fe404ae3387526e7a104b0f38c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201920f46caa494d398931ef46788de2">getRHS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the right-hand side expression of the binary operator. <a href="#a201920f46caa494d398931ef46788de2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Binary assembler expressions.</p>

<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Opcode {#afcbc8d46b6339dbbbe1af20c9c876629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCBinaryExpr::Opcode </td>
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
<td class="doxyEnumItemName">Add<a id="afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c"></a></td>
<td class="doxyEnumItemDescription">Addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">And<a id="afcbc8d46b6339dbbbe1af20c9c876629a4f10c2fcbde759540aed2b1bf0751481"></a></td>
<td class="doxyEnumItemDescription">Bitwise and</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Div<a id="afcbc8d46b6339dbbbe1af20c9c876629a0b0dd01b0b404f79f6c77d09b4291f99"></a></td>
<td class="doxyEnumItemDescription">Signed division</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EQ<a id="afcbc8d46b6339dbbbe1af20c9c876629a1cf6761d7f868d227481827f80c74e45"></a></td>
<td class="doxyEnumItemDescription">Equality comparison</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GT<a id="afcbc8d46b6339dbbbe1af20c9c876629a3cda1ebe5c1234eea7d27d545aba1738"></a></td>
<td class="doxyEnumItemDescription">Signed greater than comparison (result is either 0 or some target-specific non-zero value)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GTE<a id="afcbc8d46b6339dbbbe1af20c9c876629a13268dae72eac8a642225c0ff45dfcd0"></a></td>
<td class="doxyEnumItemDescription">Signed greater than or equal comparison (result is either 0 or some target-specific non-zero value)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAnd<a id="afcbc8d46b6339dbbbe1af20c9c876629a9af6b1faad71fbdd9d2a7a8958ed4ea9"></a></td>
<td class="doxyEnumItemDescription">Logical and</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOr<a id="afcbc8d46b6339dbbbe1af20c9c876629aaffa02e8782d8f2e11b90fb97b4d53cb"></a></td>
<td class="doxyEnumItemDescription">Logical or</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LT<a id="afcbc8d46b6339dbbbe1af20c9c876629ab9bf167f2d33f25da27ec2cc9ab65648"></a></td>
<td class="doxyEnumItemDescription">Signed less than comparison (result is either 0 or some target-specific non-zero value)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTE<a id="afcbc8d46b6339dbbbe1af20c9c876629af7fe864573da32fa4c66bef734c85456"></a></td>
<td class="doxyEnumItemDescription">Signed less than or equal comparison (result is either 0 or some target-specific non-zero value)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mod<a id="afcbc8d46b6339dbbbe1af20c9c876629a40ec3d6af8d23efa53e527ae4e1525f2"></a></td>
<td class="doxyEnumItemDescription">Signed remainder</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mul<a id="afcbc8d46b6339dbbbe1af20c9c876629a2cb7977b1f22c763fe362191442ec8b2"></a></td>
<td class="doxyEnumItemDescription">Multiplication</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NE<a id="afcbc8d46b6339dbbbe1af20c9c876629afa5c823b0ff7699d14051a05162d8288"></a></td>
<td class="doxyEnumItemDescription">Inequality comparison</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Or<a id="afcbc8d46b6339dbbbe1af20c9c876629a7cc60301ef15f92ae57708ed4fe403f7"></a></td>
<td class="doxyEnumItemDescription">Bitwise or</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OrNot<a id="afcbc8d46b6339dbbbe1af20c9c876629a952b1824a84c532fdcfa4e55e5548b5b"></a></td>
<td class="doxyEnumItemDescription">Bitwise or not</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Shl<a id="afcbc8d46b6339dbbbe1af20c9c876629a0bb5874c2ea71cc7d1f2e1304b1a4d3a"></a></td>
<td class="doxyEnumItemDescription">Shift left</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AShr<a id="afcbc8d46b6339dbbbe1af20c9c876629a0cd156d89940c517bc5add15227a62a0"></a></td>
<td class="doxyEnumItemDescription">Arithmetic shift right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LShr<a id="afcbc8d46b6339dbbbe1af20c9c876629a11c8e78341eb2a99a09a496a5511b068"></a></td>
<td class="doxyEnumItemDescription">Logical shift right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sub<a id="afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2"></a></td>
<td class="doxyEnumItemDescription">Subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Xor<a id="afcbc8d46b6339dbbbe1af20c9c876629a9039641f4bc6800217773d9688b7f7e5"></a></td>
<td class="doxyEnumItemDescription">Bitwise exclusive or</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MCBinaryExpr() {#aa11fec3318fc6e8a0b00842933ecbe11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCBinaryExpr::MCBinaryExpr (<a href="#afcbc8d46b6339dbbbe1af20c9c876629">Opcode</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LHS {#afb20cbdce11e328cb0ea417832ae0b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::MCBinaryExpr::LHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

### RHS {#af76173126807a2d54af21335bf9e81c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::MCBinaryExpr::RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a48adca21667701ac41350cfe0d5b2cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCBinaryExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51">llvm::MCExpr::Binary</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Construction

### create {#ac393df34745cae1433909c2049978bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * MCBinaryExpr::create (<a href="#afcbc8d46b6339dbbbe1af20c9c876629">Opcode</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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



<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#a4303712ca7aca04be8e4a7d4499c65c9">buildSymbolDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp/#ae8c82ca37d5404ad87bfb83a207ea712">buildSymbolDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp/#a2ea528bf7b0254b3ae2e1c0864022767">computeLabelDiff</a>, <a href="#a3cbe1086ebf00680e8dc374e07305cfb">createAdd</a>, <a href="#a37d8557c5bc9e9a92ce9b663e21f5e47">createAnd</a>, <a href="#aaf1cb4447353da4a08ae3b5d55ca3eda">createAShr</a>, <a href="#abf02d969009762015e1f45b7f9b17e90">createDiv</a>, <a href="#a12fc65c1c33d36926fade150b9205991">createEQ</a>, <a href="#ab1c84873133c2893284f143e3949b15b">createGT</a>, <a href="#a944476a319c4dddd25f49bf1da4d1e9e">createGTE</a>, <a href="#a18d807a1b5c938811456307bfd3560b1">createLAnd</a>, <a href="#a786dd04a46593c07b33f81fdc919ee4f">createLOr</a>, <a href="#a18a49f94de6b90d6fbc0c730b6a2ae5b">createLShr</a>, <a href="#a51d82c00c5a59ac45d7fe9fbf7fdb256">createLT</a>, <a href="#aa681023ab973e112d1aeaad5ad6b6806">createLTE</a>, <a href="#a70c32a58780aa68e18e47e0bfac6ad15">createMod</a>, <a href="#a994d277dcd8d2765f20ddb1e81a1187e">createMul</a>, <a href="#a7b0a201b1e3eb4fe198d3eec3bc6ad61">createNE</a>, <a href="#a6b303b433f43b901194dbf17adfb562c">createOr</a>, <a href="#ac3fa97ac31d48ef7708ba959db34f38d">createShl</a>, <a href="#af766134165065939f49fb0662c246f66">createSub</a>, <a href="#a26f6e7794e457483f87961dfb8ed3f06">createXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ad484999912240f5615d60831473902cd">makeStartPlusIntExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>.</p>

</div>
</div>

### createAdd {#a3cbe1086ebf00680e8dc374e07305cfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#afcbc8d46b6339dbbbe1af20c9c876629ae3bbdb1bec11d89ba5478648dcd3ec3c">Add</a>, <a href="#ac393df34745cae1433909c2049978bd4">create</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#ad7df82b40c89fe57a01cfd473dcfcd63">createPCXRelExprOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#aeac390246bd74f8e7897e99b30ae2c6f">llvm::MCResourceInfo::createTotalNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#abf468fdf1fecb6e06d29a8cbfaa808bb">llvm::AMDGPUTargetAsmStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a1b7e117c34782423f4cab2396b42b059">llvm::MCWinCOFFStreamer::emitCOFFImgRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a6dbbe16f1a57144b250b2b3ba1243e93">llvm::MCWinCOFFStreamer::emitCOFFSecRel32</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a25956df5af6db1ef928aa17999d28727">llvm::SystemZAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a11d81bc488e34bd6e757c2831ecc5e42">llvm::ARMAsmPrinter::emitJumpTableAddrs</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a27e1e6e35a8e68da67d5090a6e9f4c0d">llvm::ARMAsmPrinter::emitJumpTableTBInst</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2380b3abc7ab19ec1af9883a5f7bbd67">llvm::AsmPrinter::emitLabelPlusOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#ac7b652d5871240542b523c9d9fd950b5">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a9387871e1bade9ef3f96c2469ec92fe0">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a70e3e2288f783c384791e314b8e20231">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a0c5eda02c50a11f3dde025afe0675b6e">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::EmitTlsCall</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25e51557ff442df4d50f2ad5d1f55743">llvm::AsmPrinter::emitXRayTable</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kmccodeemitter-cpp-/m68kmccodeemitter/#ae9def4fef17a8e66265e30f687158adf">anonymous{M68kMCCodeEmitter.cpp}::M68kMCCodeEmitter::encodePCRelImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae7810a05a90e7fc6d13fa85c0242ab5f">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::getAdjustedFasterLocalExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a1a53bd2f56709e4b8ec00e8ae0447e4f">llvm::MipsMCCodeEmitter::getBranchTarget21OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#add4d66dd8382e6b4fe7fa789844f1e27">llvm::MipsMCCodeEmitter::getBranchTarget21OpValueMM</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a9332e7f86488ac03e792fde668bac68e">llvm::MipsMCCodeEmitter::getBranchTarget26OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a93c2d268f594d31d146df08d1c0e007e">llvm::MipsMCCodeEmitter::getBranchTarget26OpValueMM</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a6b63701360781e817473a4818ce94912">llvm::MipsMCCodeEmitter::getBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#aa1dfb38c5dc5e51389464d20e369678f">llvm::MipsMCCodeEmitter::getBranchTargetOpValue1SImm16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a07ecbb2c17eb03d8c4755dc5cfd88a5a">llvm::MipsMCCodeEmitter::getBranchTargetOpValueLsl2MMR6</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a6928f0f796b63f34abf586618d0ebba7">llvm::MipsMCCodeEmitter::getBranchTargetOpValueMMR6</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#a4824f185b09fa4322916df3508816b22">llvm::MipsTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/x86-64mcasminfodarwin/#a2718196f3a76adab2b39bcdff3f3cb44">llvm::X86_64MCAsmInfoDarwin::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#ab479db6c0dce9d07c70ea70016ed99ff">llvm::AArch64_ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#a62d13f21f5dde00137a248d95cf8acd6">llvm::ARMElfTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#affc824acbbe220a54656c5519b408c4b">llvm::RISCVELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64elftargetobjectfile/#a7fade16e9dc1ebc9b6974b12857f5abe">llvm::X86_64ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64machotargetobjectfile/#abe4296cf38fa7bebb355865172c0acac">llvm::X86_64MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp/#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64machotargetobjectfile/#a17558be02e5c14c099a7f347669a3132">llvm::X86_64MachoTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac2b1c517d194a6bdd00f66bce97f52c3">llvm::AsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a55d9cc47f7041c1afad87f88ec5c7636">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerConstantPtrAuth</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a55859f4a9f64b42f225c2f6c63212be5">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#a9bdd6ed65ae27d68d065f712e0d281de">llvm::LanaiMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ab8310eee0e086d64c49733dd9da4171b">llvm::M68kMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a8520755e983a50f3c24f91e0f8e06d03">llvm::MSP430MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a153a3f96b2710ef9d924d8168a93482b">llvm::XtensaAsmPrinter::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#a5edb97651738551635eb05cc3f9fa77c">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#acb4de1517ebc1f8095f87eef68f290f7">llvm::AVRMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a48efbf9c526eceb30f721ea086dc98fd">llvm::AArch64MCInstLower::lowerSymbolOperandCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ae4b8638e074c6af2301cd209d3d2021c">llvm::AArch64MCInstLower::lowerSymbolOperandMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### createAnd {#a37d8557c5bc9e9a92ce9b663e21f5e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createAnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#afcbc8d46b6339dbbbe1af20c9c876629a4f10c2fcbde759540aed2b1bf0751481">And</a>, <a href="#ac393df34745cae1433909c2049978bd4">create</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a74dc10b4ec4a74b8a4379ea8f6edb221">llvm::AMDGPU::MCKernelDescriptor::bits_get</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a9e9129ae20b8f08b24f78bd53bb0c11e">llvm::AMDGPU::MCKernelDescriptor::bits_set</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#af999327aaf208e1dcb5c3c60d6c2452c">MaskShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8749a42239506716ab09647dd0b31795">llvm::AMDGPU::maskShiftGet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f3ff39c7ddc47c851a92a89a6c68e3d">llvm::AMDGPU::maskShiftSet</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>.</p>

</div>
</div>

### createAShr {#aaf1cb4447353da4a08ae3b5d55ca3eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createAShr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#afcbc8d46b6339dbbbe1af20c9c876629a0cd156d89940c517bc5add15227a62a0">AShr</a>, <a href="#ac393df34745cae1433909c2049978bd4">create</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>.</p>

</div>
</div>

### createDiv {#abf02d969009762015e1f45b7f9b17e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createDiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="#afcbc8d46b6339dbbbe1af20c9c876629a0b0dd01b0b404f79f6c77d09b4291f99">Div</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#ae18928643ad012c59561c9e50dc452fa">computeAccumOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a27e1e6e35a8e68da67d5090a6e9f4c0d">llvm::ARMAsmPrinter::emitJumpTableTBInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aaab77f3694a5bc3b29ffbc6ce87444ad">GetSubDivExpr</a>.</p>

</div>
</div>

### createEQ {#a12fc65c1c33d36926fade150b9205991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createEQ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="#afcbc8d46b6339dbbbe1af20c9c876629a1cf6761d7f868d227481827f80c74e45">EQ</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>

</div>
</div>

### createGT {#ab1c84873133c2893284f143e3949b15b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createGT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="#afcbc8d46b6339dbbbe1af20c9c876629a3cda1ebe5c1234eea7d27d545aba1738">GT</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>

</div>
</div>

### createGTE {#a944476a319c4dddd25f49bf1da4d1e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createGTE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="#afcbc8d46b6339dbbbe1af20c9c876629a13268dae72eac8a642225c0ff45dfcd0">GTE</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>

</div>
</div>

### createLAnd {#a18d807a1b5c938811456307bfd3560b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createLAnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="#afcbc8d46b6339dbbbe1af20c9c876629a9af6b1faad71fbdd9d2a7a8958ed4ea9">LAnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>

</div>
</div>

### createLOr {#a786dd04a46593c07b33f81fdc919ee4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createLOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="#afcbc8d46b6339dbbbe1af20c9c876629aaffa02e8782d8f2e11b90fb97b4d53cb">LOr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>

</div>
</div>

### createLShr {#a18a49f94de6b90d6fbc0c730b6a2ae5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createLShr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="#afcbc8d46b6339dbbbe1af20c9c876629a11c8e78341eb2a99a09a496a5511b068">LShr</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a74dc10b4ec4a74b8a4379ea8f6edb221">llvm::AMDGPU::MCKernelDescriptor::bits_get</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a7b744276265a7587d11961d5cbf82dd0">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitJumpTableInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8749a42239506716ab09647dd0b31795">llvm::AMDGPU::maskShiftGet</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>.</p>

</div>
</div>

### createLT {#a51d82c00c5a59ac45d7fe9fbf7fdb256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createLT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="#afcbc8d46b6339dbbbe1af20c9c876629ab9bf167f2d33f25da27ec2cc9ab65648">LT</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>

</div>
</div>

### createLTE {#aa681023ab973e112d1aeaad5ad6b6806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createLTE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="#afcbc8d46b6339dbbbe1af20c9c876629af7fe864573da32fa4c66bef734c85456">LTE</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>

</div>
</div>

### createMod {#a70c32a58780aa68e18e47e0bfac6ad15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createMod (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a> and <a href="#afcbc8d46b6339dbbbe1af20c9c876629a40ec3d6af8d23efa53e527ae4e1525f2">Mod</a>.</p>

</div>
</div>

### createMul {#a994d277dcd8d2765f20ddb1e81a1187e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a> and <a href="#afcbc8d46b6339dbbbe1af20c9c876629a2cb7977b1f22c763fe362191442ec8b2">Mul</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#abf468fdf1fecb6e06d29a8cbfaa808bb">llvm::AMDGPUTargetAsmStreamer::EmitAmdhsaKernelDescriptor</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### createNE {#a7b0a201b1e3eb4fe198d3eec3bc6ad61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createNE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a> and <a href="#afcbc8d46b6339dbbbe1af20c9c876629afa5c823b0ff7699d14051a05162d8288">NE</a>.</p>

</div>
</div>

### createOr {#a6b303b433f43b901194dbf17adfb562c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a> and <a href="#afcbc8d46b6339dbbbe1af20c9c876629a7cc60301ef15f92ae57708ed4fe403f7">Or</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a9e9129ae20b8f08b24f78bd53bb0c11e">llvm::AMDGPU::MCKernelDescriptor::bits_set</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a64b42038a61a3c4b1880eea5331cdb44">llvm::AMDGPUDisassembler::decodeVersionImm</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet/#a766a8f22f00b2895f373b0328840e760">llvm::AMDGPU::AMDGPUMCKernelCodeT::EmitKernelCodeT</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a4c73e82c5082e2f77d5647e1034eb81d">llvm::SIProgramInfo::getComputePGMRSrc1</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a318d26ac513db990b9466b1ce9380032">llvm::SIProgramInfo::getComputePGMRSrc2</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#abe52a78f5c8a6b91ae15c4635ccf564e">llvm::SIProgramInfo::getPGMRSrc1</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a44fe092bd112e2eb16c1cba213922aca">llvm::AMDGPUPALMetadata::setRegister</a>.</p>

</div>
</div>

### createShl {#ac3fa97ac31d48ef7708ba959db34f38d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createShl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a> and <a href="#afcbc8d46b6339dbbbe1af20c9c876629a0bb5874c2ea71cc7d1f2e1304b1a4d3a">Shl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a9e9129ae20b8f08b24f78bd53bb0c11e">llvm::AMDGPU::MCKernelDescriptor::bits_set</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#af999327aaf208e1dcb5c3c60d6c2452c">MaskShift</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f3ff39c7ddc47c851a92a89a6c68e3d">llvm::AMDGPU::maskShiftSet</a>.</p>

</div>
</div>

### createSub {#af766134165065939f49fb0662c246f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a> and <a href="#afcbc8d46b6339dbbbe1af20c9c876629a2042f1a9af632c3d4d83f157201623d2">Sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a91eb97e39eb4e9b4befd1914be362617">llvm::CSKYConstantPool::addEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a773e13d9361edd4a75124c26e305bf13">addNegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#ae18928643ad012c59561c9e50dc452fa">computeAccumOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#ad7df82b40c89fe57a01cfd473dcfcd63">createPCXRelExprOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab68ca7cc744c7d305f655930067e0a64">EmitAbsDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a8061d1e593a8f095f0efe3ba0d793531">llvm::MCStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4f385d04b05418cfd8b1337ac541256c">llvm::MCStreamer::emitAbsoluteSymbolDiffAsULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#abc85cf8fcb99aada0bb615989928b516">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLineStartLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5b7c6daec7e647061052e0947de4703b">llvm::AsmPrinter::emitFunctionBody</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa07427c984394cc2c4b4cf8b7158def4">llvm::AMDGPUAsmPrinter::emitFunctionBodyEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a0e3f4587b93083fdc01e3ec8f66b3701">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitFunctionBodyStart</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#ac456206c08bdce2e1a11cf14b316bc9a">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a5f962a3da2e5e21ea73c8a2ba3d60cf1">llvm::AMDGPUTargetELFStreamer::EmitHSAMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#afb080cf7b9699890fae560c167c09291">llvm::AMDGPUTargetELFStreamer::EmitISAVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a11d81bc488e34bd6e757c2831ecc5e42">llvm::ARMAsmPrinter::emitJumpTableAddrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a7b744276265a7587d11961d5cbf82dd0">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a27e1e6e35a8e68da67d5090a6e9f4c0d">llvm::ARMAsmPrinter::emitJumpTableTBInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a09f6957ce3faffb065b97517e5a5ff76">llvm::X86AsmPrinter::emitKCFITypeId</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a9387871e1bade9ef3f96c2469ec92fe0">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#aa72747d7d3b33e66672520f5a3e93462">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitTTypeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25e51557ff442df4d50f2ad5d1f55743">llvm::AsmPrinter::emitXRayTable</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#ae3f7a2c3431323c5e22c2c175ebef9cb">llvm::WasmException::endFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a0eb22c22d4dc362aa5e15bb7cd1a4edb">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getBFAfterTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a9e11e3c1ca2c5f957aa7a7a16ff40e24">llvm::MCAsmInfo::getExprForFDESymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/aarch64mcasminfodarwin/#a1a05057cd3005401418d6bb6f4c53659">llvm::AArch64MCAsmInfoDarwin::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#aab2cc2813c5a774bb4f83b6f9ae5a98b">llvm::AArch64_MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa18d22b8d07f4376fcf7c00d5923422a">GetOptionalAbsDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aaab77f3694a5bc3b29ffbc6ce87444ad">GetSubDivExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#abda04e72e43a3aaef8a55e4ecf91d127">llvm::AArch64_MachoTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#ac1cd29692079a1f57202b9947c5f5521">llvm::TargetLoweringObjectFile::getTTypeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac2b1c517d194a6bdd00f66bce97f52c3">llvm::AsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a55d9cc47f7041c1afad87f88ec5c7636">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerConstantPtrAuth</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ad81befa82353e9ee9e205edffbe77d4e">llvm::VETargetLowering::LowerCustomJumpTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a745752b67a45e5dc6b1f2a6985f68937">llvm::TargetLoweringObjectFileELF::lowerRelativeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#a0d892b52d1df1d1cb59054c2dab539be">llvm::TargetLoweringObjectFileWasm::lowerRelativeReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a55859f4a9f64b42f225c2f6c63212be5">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a2e27ea385fabb6471aea3a5e37d3dd09">llvm::FaultMaps::recordFaultingOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### createXor {#a26f6e7794e457483f87961dfb8ed3f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCBinaryExpr * llvm::MCBinaryExpr::createXor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="#ac393df34745cae1433909c2049978bd4">create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a> and <a href="#afcbc8d46b6339dbbbe1af20c9c876629a9039641f4bc6800217773d9688b7f7e5">Xor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### getLHS {#a071993fe404ae3387526e7a104b0f38c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::MCBinaryExpr::getLHS ()</td>
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

<p>Get the left-hand side expression of the binary operator.</p>

<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a3d4443a5f4df398bcde06fae90a11c04">EvaluateCRExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a889d08bf85a0f9f722a635fc75dbf655">llvm::PPCMCCodeEmitter::getDispRI34PCRelEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/asmparser/sparcasmparser-cpp/#a719cb125836c429953e4eb35be1e93b4">hasGOTReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#ab29acfdfda391000c99d74b9922342c6">isEvaluated</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae066b71f79346e6cf0e978da4656e1bc">llvm::MCExpr::isSymbolUsedInExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#abd062e69c3b1b4a76b873edc1127443a">llvm::LoongArchAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a172850f33ba1afc4850ad347040d02a7">llvm::RISCVAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a09963de4b3b90f89cf9f9b6f154af6bd">llvm::LoongArchAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a3e9dd2df270e8ff9b688dc40af18e54e">startsWithGlobalOffsetTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

### getOpcode {#a5606d070331bbd494bcd8fe374540d4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Opcode llvm::MCBinaryExpr::getOpcode ()</td>
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

<p>Get the kind of this binary expression.</p>

<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ad7a73c5ca50f673d05234b59a93bfa29">llvm::MCExpr::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a3d4443a5f4df398bcde06fae90a11c04">EvaluateCRExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a889d08bf85a0f9f722a635fc75dbf655">llvm::PPCMCCodeEmitter::getDispRI34PCRelEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>.</p>

</div>
</div>

### getRHS {#a201920f46caa494d398931ef46788de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::MCBinaryExpr::getRHS ()</td>
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

<p>Get the right-hand side expression of the binary operator.</p>

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a5f1cbd9499b37094c4e6c9660d1dbe19">llvm::MCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a3d4443a5f4df398bcde06fae90a11c04">EvaluateCRExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae4694d7c3e8bb89a9c2fb6227b8aa1df">llvm::MCExpr::findAssociatedFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemcexpr-cpp/#ac6027fa44abc12bde25474a4a945f2cb">fixELFSymbolsInTLSFixupsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmccodeemitter/#a889d08bf85a0f9f722a635fc75dbf655">llvm::PPCMCCodeEmitter::getDispRI34PCRelEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/asmparser/sparcasmparser-cpp/#a719cb125836c429953e4eb35be1e93b4">hasGOTReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#ab29acfdfda391000c99d74b9922342c6">isEvaluated</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae066b71f79346e6cf0e978da4656e1bc">llvm::MCExpr::isSymbolUsedInExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#abd062e69c3b1b4a76b873edc1127443a">llvm::LoongArchAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a172850f33ba1afc4850ad347040d02a7">llvm::RISCVAsmBackend::relaxDwarfCFA</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a09963de4b3b90f89cf9f9b6f154af6bd">llvm::LoongArchAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a3e9dd2df270e8ff9b688dc40af18e54e">startsWithGlobalOffsetTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afb2fc7b7b30a601f94f8f5a6297ec68f">llvm::MCStreamer::visitUsedExpr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
