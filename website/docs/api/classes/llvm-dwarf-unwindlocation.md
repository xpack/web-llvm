---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf/unwindlocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UnwindLocation` Class Reference

<p>A class that represents a location for the Call Frame Address (CFA) or a register. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf::UnwindLocation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">llvm/DebugInfo/DWARF/DWARFDebugFrame.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Location { <a href="#a6fbbea6b3966c62608feb63d6d203ed5">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c88b29c7f2c99c559e34fa02f1cdc74">UnwindLocation</a> (Location K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, the resulting location must be dereferenced after the location value is computed. <a href="#a4c88b29c7f2c99c559e34fa02f1cdc74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6444ee206cc725c47a94275bca62da86">UnwindLocation</a> (Location K, uint32_t Reg, int32_t Off, std::optional&lt; uint32_t &gt; AS, bool Deref)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778896cbafc3272461fdc5ad8e5e3d42">UnwindLocation</a> (DWARFExpression E, bool Deref)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67b30c85270b84204fa8e271586527d8">operator==</a> (const UnwindLocation &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6fbbea6b3966c62608feb63d6d203ed5">Location</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705b7b05de3e2ad7476cdd80d39f383a">getLocation</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27cb1f60837aaed75fb3390f69def5ce">getRegister</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a578de70f175190f75774303e8dba5692">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e0d45a572684aeaf8e8478839af2ef2">getAddressSpace</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc948c517b3fad83c31e4c5074766a8e">getConstant</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63c9c35715da5aefcf74df2544b193e">setRegister</a> (uint32_t NewRegNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some opcodes will modify the CFA location's register only, so we need to be able to modify the CFA register when evaluating DWARF Call Frame Information opcodes. <a href="#af63c9c35715da5aefcf74df2544b193e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19679acc5a2e96feba0767791b3ebac9">setOffset</a> (int32_t NewOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some opcodes will modify the CFA location's offset only, so we need to be able to modify the CFA offset when evaluating DWARF Call Frame Information opcodes. <a href="#a19679acc5a2e96feba0767791b3ebac9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a111f89572fd57db9100d539d77fec9c9">setConstant</a> (int32_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some opcodes modify a constant value and we need to be able to update the constant value (DW_CFA_GNU_window_save which is also known as. <a href="#a111f89572fd57db9100d539d77fec9c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DWARFExpression</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2ad71df56a1b82ff7742d95508591c0">getDWARFExpressionBytes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9122a6af9ddf36a3a65346fe19ff520c">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a location expression as text and use the register information if some is provided. <a href="#a9122a6af9ddf36a3a65346fe19ff520c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6fbbea6b3966c62608feb63d6d203ed5">Location</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d7df51004cba0157426c6a30695e99b">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284fbbe76b0391343af1b2a8f4ec796e">RegNum</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the location that describes how to unwind it. <a href="#a284fbbe76b0391343af1b2a8f4ec796e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aede1a6d4ecafc02d1b0b43265605b98a">Offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The register number for Kind == RegPlusOffset. <a href="#aede1a6d4ecafc02d1b0b43265605b98a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995f0b010c7970b18de0fdf94702d43b">AddrSpace</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The offset for Kind == CFAPlusOffset or RegPlusOffset. <a href="#a995f0b010c7970b18de0fdf94702d43b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DWARFExpression</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e738a73d7c25492548ec31e6b1dda6d">Expr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The address space for Kind == RegPlusOffset for CFA. <a href="#a6e738a73d7c25492548ec31e6b1dda6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf434d239f8b5f06463f2cd7078ec262">Dereference</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DWARF expression for Kind == <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DWARFExpression</a>. <a href="#adf434d239f8b5f06463f2cd7078ec262">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa9468956d3c4c0b55c047547d380e0">createUnspecified</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a location whose rule is set to Unspecified. <a href="#a5fa9468956d3c4c0b55c047547d380e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a5fe24c77ef2016d57293d462d350f4">createUndefined</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a location where the value is undefined and not available. <a href="#a0a5fe24c77ef2016d57293d462d350f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf0dcdacc18895c617de0fe50ac8499c">createSame</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a location where the value is known to be in the register itself. <a href="#abf0dcdacc18895c617de0fe50ac8499c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af077ec9d425917adfcb44d3af3bbdd2d">createIsCFAPlusOffset</a> (int32_t Off)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a location that is in (Deref == false) or at (Deref == true) the CFA plus an offset. <a href="#af077ec9d425917adfcb44d3af3bbdd2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33e4503264ee06460bce047f0f1a36e">createAtCFAPlusOffset</a> (int32_t Off)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505c357efe3a5850808b45700527e471">createIsRegisterPlusOffset</a> (uint32_t Reg, int32_t Off, std::optional&lt; uint32_t &gt; AddrSpace=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a location where the saved value is in (Deref == false) or at (Deref == true) a regiser plus an offset and, optionally, in the specified address space (used mostly for the CFA). <a href="#a505c357efe3a5850808b45700527e471">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341ae4c735da746b35ffb8a9ef480563">createAtRegisterPlusOffset</a> (uint32_t Reg, int32_t Off, std::optional&lt; uint32_t &gt; AddrSpace=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67d7ed3b0a73532408da335d20a33751">createIsDWARFExpression</a> (DWARFExpression Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a location whose value is the result of evaluating a DWARF expression. <a href="#a67d7ed3b0a73532408da335d20a33751">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b85bd9e921a6b9fcb8bce54548ae9a">createAtDWARFExpression</a> (DWARFExpression Expr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fea449a2b4e7cbeadef2abad9181036">createIsConstant</a> (int32_t Value)</td>
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

<p>A class that represents a location for the Call Frame Address (CFA) or a register.</p>


<p>This is decoded from the DWARF Call Frame Information instructions and put into an <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a>.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Location {#a6fbbea6b3966c62608feb63d6d203ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::dwarf::UnwindLocation::Location </td>
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
<td class="doxyEnumItemName">Unspecified<a id="a6fbbea6b3966c62608feb63d6d203ed5add7aa992a49f11aaaf8acb7bde4df002"></a></td>
<td class="doxyEnumItemDescription">Not specified</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Undefined<a id="a6fbbea6b3966c62608feb63d6d203ed5a3b7284fc0e118c9df3bd29cd502641c7"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is not available and can't be recovered</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Same<a id="a6fbbea6b3966c62608feb63d6d203ed5a8b9b57123446c5515f1b63d437da76cd"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> value is in the register, nothing needs to be done to unwind it: reg = reg</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CFAPlusOffset<a id="a6fbbea6b3966c62608feb63d6d203ed5abc5d851f564326a0f6888ea674722984"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is in or at the CFA plus an offset: reg = CFA + offset reg = defef(CFA + offset)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegPlusOffset<a id="a6fbbea6b3966c62608feb63d6d203ed5ae4d12158085f5cfd9e7f5d9c8657265b"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> or CFA is in or at a register plus offset, optionally in an address space: reg = reg + offset [in addrspace] reg = deref(reg + offset [in addrspace])</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DWARFExpr<a id="a6fbbea6b3966c62608feb63d6d203ed5a68111aa49990ae2352b2ef771df0bae0"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> or CFA value is in or at a value found by evaluating a DWARF expression: reg = eval(dwarf_expr) reg = deref(eval(dwarf_expr))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Constant<a id="a6fbbea6b3966c62608feb63d6d203ed5a5e341c5a2c947be144c341dc933aa083"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is a constant value contained in "Offset": reg = Offset</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### UnwindLocation() {#a4c88b29c7f2c99c559e34fa02f1cdc74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf::UnwindLocation::UnwindLocation (<a href="#a6fbbea6b3966c62608feb63d6d203ed5">Location</a> K)</td>
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

<p>If true, the resulting location must be dereferenced after the location value is computed.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### UnwindLocation() {#a6444ee206cc725c47a94275bca62da86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf::UnwindLocation::UnwindLocation (<a href="#a6fbbea6b3966c62608feb63d6d203ed5">Location</a> K, uint32_t Reg, int32_t Off, std::optional&lt; uint32_t &gt; AS, bool Deref)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### UnwindLocation() {#a778896cbafc3272461fdc5ad8e5e3d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf::UnwindLocation::UnwindLocation (<a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DWARFExpression</a> E, bool Deref)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a67b30c85270b84204fa8e271586527d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UnwindLocation::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="#a6fbbea6b3966c62608feb63d6d203ed5abc5d851f564326a0f6888ea674722984">CFAPlusOffset</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5a5e341c5a2c947be144c341dc933aa083">Constant</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5a68111aa49990ae2352b2ef771df0bae0">DWARFExpr</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5ae4d12158085f5cfd9e7f5d9c8657265b">RegPlusOffset</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5a8b9b57123446c5515f1b63d437da76cd">Same</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5a3b7284fc0e118c9df3bd29cd502641c7">Undefined</a> and <a href="#a6fbbea6b3966c62608feb63d6d203ed5add7aa992a49f11aaaf8acb7bde4df002">Unspecified</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a9122a6af9ddf36a3a65346fe19ff520c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnwindLocation::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a location expression as text and use the register information if some is provided.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>the stream to use for output.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MRI</td>
<td class="doxyParamItemDescription"><p>register information that helps emit register names insteead of raw register numbers.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsEH</td>
<td class="doxyParamItemDescription"><p>true if the DWARF Call Frame Information is from .eh_frame instead of from .debug_frame. This is needed for register number conversion because some register numbers differ between the two sections for certain architectures like x86.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="#a6fbbea6b3966c62608feb63d6d203ed5abc5d851f564326a0f6888ea674722984">CFAPlusOffset</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5a5e341c5a2c947be144c341dc933aa083">Constant</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5a68111aa49990ae2352b2ef771df0bae0">DWARFExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp/#a5658f96977b9cb1730425f3ca3cb305c">printRegister</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5ae4d12158085f5cfd9e7f5d9c8657265b">RegPlusOffset</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5a8b9b57123446c5515f1b63d437da76cd">Same</a>, <a href="#a6fbbea6b3966c62608feb63d6d203ed5a3b7284fc0e118c9df3bd29cd502641c7">Undefined</a> and <a href="#a6fbbea6b3966c62608feb63d6d203ed5add7aa992a49f11aaaf8acb7bde4df002">Unspecified</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a3d6f50e0699b8d19a7f583abc191a3c5">llvm::dwarf::operator&lt;&lt;</a>.</p>

</div>
</div>

### getAddressSpace() {#a9e0d45a572684aeaf8e8478839af2ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dwarf::UnwindLocation::getAddressSpace ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a6fbbea6b3966c62608feb63d6d203ed5ae4d12158085f5cfd9e7f5d9c8657265b">RegPlusOffset</a>.</p>

</div>
</div>

### getConstant() {#acc948c517b3fad83c31e4c5074766a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::dwarf::UnwindLocation::getConstant ()</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### getDWARFExpressionBytes() {#ab2ad71df56a1b82ff7742d95508591c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFExpression &gt; llvm::dwarf::UnwindLocation::getDWARFExpressionBytes ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### getLocation() {#a705b7b05de3e2ad7476cdd80d39f383a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Location llvm::dwarf::UnwindLocation::getLocation ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### getOffset() {#a578de70f175190f75774303e8dba5692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::dwarf::UnwindLocation::getOffset ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### getRegister() {#a27cb1f60837aaed75fb3390f69def5ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dwarf::UnwindLocation::getRegister ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### setConstant() {#a111f89572fd57db9100d539d77fec9c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf::UnwindLocation::setConstant (int32_t Value)</td>
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

<p>Some opcodes modify a constant value and we need to be able to update the constant value (DW_CFA_GNU_window_save which is also known as.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### setOffset() {#a19679acc5a2e96feba0767791b3ebac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf::UnwindLocation::setOffset (int32_t NewOffset)</td>
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

<p>Some opcodes will modify the CFA location's offset only, so we need to be able to modify the CFA offset when evaluating DWARF Call Frame Information opcodes.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### setRegister() {#af63c9c35715da5aefcf74df2544b193e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf::UnwindLocation::setRegister (uint32_t NewRegNum)</td>
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

<p>Some opcodes will modify the CFA location's register only, so we need to be able to modify the CFA register when evaluating DWARF Call Frame Information opcodes.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrSpace {#a995f0b010c7970b18de0fdf94702d43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint32_t&gt; llvm::dwarf::UnwindLocation::AddrSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The offset for Kind == CFAPlusOffset or RegPlusOffset.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### Dereference {#adf434d239f8b5f06463f2cd7078ec262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf::UnwindLocation::Dereference</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The DWARF expression for Kind == <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DWARFExpression</a>.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### Expr {#a6e738a73d7c25492548ec31e6b1dda6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;DWARFExpression&gt; llvm::dwarf::UnwindLocation::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The address space for Kind == RegPlusOffset for CFA.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### Kind {#a7d7df51004cba0157426c6a30695e99b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Location llvm::dwarf::UnwindLocation::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### Offset {#aede1a6d4ecafc02d1b0b43265605b98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::dwarf::UnwindLocation::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The register number for Kind == RegPlusOffset.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### RegNum {#a284fbbe76b0391343af1b2a8f4ec796e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dwarf::UnwindLocation::RegNum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of the location that describes how to unwind it.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createAtCFAPlusOffset() {#ab33e4503264ee06460bce047f0f1a36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createAtCFAPlusOffset (int32_t Off)</td>
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



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="#a6fbbea6b3966c62608feb63d6d203ed5abc5d851f564326a0f6888ea674722984">CFAPlusOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a300b34d5b0ef9425864ea43eaab3173d">llvm::dwarf::InvalidRegisterNumber</a>.</p>

</div>
</div>

### createAtDWARFExpression() {#a57b85bd9e921a6b9fcb8bce54548ae9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createAtDWARFExpression (<a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DWARFExpression</a> Expr)</td>
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



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>

</div>
</div>

### createAtRegisterPlusOffset() {#a341ae4c735da746b35ffb8a9ef480563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createAtRegisterPlusOffset (uint32_t Reg, int32_t Off, std::optional&lt; uint32_t &gt; AddrSpace=std::nullopt)</td>
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



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>Reference <a href="#a6fbbea6b3966c62608feb63d6d203ed5ae4d12158085f5cfd9e7f5d9c8657265b">RegPlusOffset</a>.</p>

</div>
</div>

### createIsCFAPlusOffset() {#af077ec9d425917adfcb44d3af3bbdd2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createIsCFAPlusOffset (int32_t Off)</td>
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

<p>Create a location that is in (Deref == false) or at (Deref == true) the CFA plus an offset.</p>


<p>Most registers that are spilled onto the stack use this rule. The rule for the register will use this rule and specify a unique offset from the CFA with <em>Deref</em> set to true. This value will be relative to a CFA value which is typically defined using the register plus offset location.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>createRegisterPlusOffset(...) <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> more information.</p></dd>
</dl>


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="#a6fbbea6b3966c62608feb63d6d203ed5abc5d851f564326a0f6888ea674722984">CFAPlusOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a300b34d5b0ef9425864ea43eaab3173d">llvm::dwarf::InvalidRegisterNumber</a>.</p>

</div>
</div>

### createIsConstant() {#a8fea449a2b4e7cbeadef2abad9181036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createIsConstant (int32_t Value)</td>
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



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="#a6fbbea6b3966c62608feb63d6d203ed5a5e341c5a2c947be144c341dc933aa083">Constant</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a300b34d5b0ef9425864ea43eaab3173d">llvm::dwarf::InvalidRegisterNumber</a>.</p>

</div>
</div>

### createIsDWARFExpression() {#a67d7ed3b0a73532408da335d20a33751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createIsDWARFExpression (<a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DWARFExpression</a> Expr)</td>
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

<p>Create a location whose value is the result of evaluating a DWARF expression.</p>


<p>This allows complex expressions to be evaluated in order to unwind a register or CFA value.</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>

</div>
</div>

### createIsRegisterPlusOffset() {#a505c357efe3a5850808b45700527e471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createIsRegisterPlusOffset (uint32_t Reg, int32_t Off, std::optional&lt; uint32_t &gt; AddrSpace=std::nullopt)</td>
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

<p>Create a location where the saved value is in (Deref == false) or at (Deref == true) a regiser plus an offset and, optionally, in the specified address space (used mostly for the CFA).</p>


<p>The CFA is usually defined using this rule by using the stack pointer or frame pointer as the register, with an offset that accounts for all spilled registers and all local variables in a function, and Deref == false.</p>


<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>Reference <a href="#a6fbbea6b3966c62608feb63d6d203ed5ae4d12158085f5cfd9e7f5d9c8657265b">RegPlusOffset</a>.</p>

</div>
</div>

### createSame() {#abf0dcdacc18895c617de0fe50ac8499c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createSame ()</td>
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

<p>Create a location where the value is known to be in the register itself.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>Reference <a href="#a6fbbea6b3966c62608feb63d6d203ed5a8b9b57123446c5515f1b63d437da76cd">Same</a>.</p>

</div>
</div>

### createUndefined() {#a0a5fe24c77ef2016d57293d462d350f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createUndefined ()</td>
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

<p>Create a location where the value is undefined and not available.</p>


<p>This can happen when a register is volatile and can't be recovered.</p>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>Reference <a href="#a6fbbea6b3966c62608feb63d6d203ed5a3b7284fc0e118c9df3bd29cd502641c7">Undefined</a>.</p>

</div>
</div>

### createUnspecified() {#a5fa9468956d3c4c0b55c047547d380e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation UnwindLocation::createUnspecified ()</td>
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

<p>Create a location whose rule is set to Unspecified.</p>


<p>This means the register value might be in the same register but it wasn't specified in the unwind opcodes.</p>


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>Reference <a href="#a6fbbea6b3966c62608feb63d6d203ed5add7aa992a49f11aaaf8acb7bde4df002">Unspecified</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
