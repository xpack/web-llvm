---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfexpression-2
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DwarfExpression` Class Reference

<p>Base class containing the logic for constructing DWARF expressions independently of whether they are emitted into a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> or into a .debug_loc entry. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DwarfExpression { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">CodeGen/AsmPrinter/DwarfExpression.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diedwarfexpression">DIEDwarfExpression</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DwarfExpression</a> implementation for singular DW_AT_location. <a href="/web-llvm/docs/api/classes/llvm/diedwarfexpression/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debuglocdwarfexpression">DebugLocDwarfExpression</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DwarfExpression</a> implementation for .debug_loc entries. <a href="/web-llvm/docs/api/classes/llvm/debuglocdwarfexpression/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a2d4874c3f450184303a741b477b8529f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of location description being produced. <a href="#a2d4874c3f450184303a741b477b8529f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a467e19938e9af2b1003b8e56a07f8919">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Additional location flags which may be combined with any location kind. <a href="#a467e19938e9af2b1003b8e56a07f8919">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f024a1be631b3865a2ac37210ad57c">DwarfExpression</a> (unsigned DwarfVersion, DwarfCompileUnit &amp;CU)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89fb4d2b1507375553c2c749364c155f">~DwarfExpression</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082b9984a203d2a2ba3dd4b5986d4706">setLocation</a> (const MachineLocation &amp;Loc, const DIExpression *DIExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the location (<span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>) and <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> (<span class="doxyComputerOutput">DIExpr</span>) to describe. <a href="#a082b9984a203d2a2ba3dd4b5986d4706">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238ed978a8838070e8eec9168fc08764">isUnknownLocation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6f5b7e87b7ed3a688215c95f870e0d5">isMemoryLocation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a480fc786a688aa08fbad50cb961bbdf5">isRegisterLocation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6821f93d5f8c85cb416bf56acb135409">isImplicitLocation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6233f16f7169eca9b6afd2f0a5635f">isEntryValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a901d1bd450dc954f08cb3e435ff9560a">isIndirect</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaef0bfcd27f5f3266c56a477f288d8a">isParameterValue</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2faa879061bc4989e0b78a0928d74e29">finalize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This needs to be called last to commit any pending changes. <a href="#a2faa879061bc4989e0b78a0928d74e29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad676cf44e0c249e17c08edb7d3270b45">addSignedConstant</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a signed constant. <a href="#ad676cf44e0c249e17c08edb7d3270b45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a84268a368e42a1bed6f9e4def555b">addUnsignedConstant</a> (uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an unsigned constant. <a href="#aa7a84268a368e42a1bed6f9e4def555b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83b4a350a8392e1524327661a874f0a">addUnsignedConstant</a> (const APInt &amp;Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an unsigned constant. <a href="#ab83b4a350a8392e1524327661a874f0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed44f2251a99b3c609481e114ae9295">addConstantFP</a> (const APFloat &amp;Value, const AsmPrinter &amp;AP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an floating point constant. <a href="#a7ed44f2251a99b3c609481e114ae9295">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509852c6998b529c06357c2bba7aeabb">setMemoryLocationKind</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lock this down to become a memory location description. <a href="#a509852c6998b529c06357c2bba7aeabb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69edc735ccf08fa2817b548619ddd34">setEntryValueFlags</a> (const MachineLocation &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lock this down to become an entry value location. <a href="#ae69edc735ccf08fa2817b548619ddd34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7188211a4157e4f38345d90d6030c562">setCallSiteParamValueFlag</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lock this down to become a call site parameter location. <a href="#a7188211a4157e4f38345d90d6030c562">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a> (const TargetRegisterInfo &amp;TRI, DIExpressionCursor &amp;Expr, llvm::Register MachineReg, unsigned FragmentOffsetInBits=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a machine register location. <a href="#a8337bafd341ca7fa36509bf0ad142c57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af496d6e3f88f3b85e879bfdfe19b0b40">beginEntryValueExpression</a> (DIExpressionCursor &amp;ExprCursor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Begin emission of an entry value dwarf operation. <a href="#af496d6e3f88f3b85e879bfdfe19b0b40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6564714268867b9179bfcfc0112c43">getOrCreateBaseType</a> (unsigned BitSize, dwarf::TypeKind Encoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of a base type with the given properties and create one if necessary. <a href="#acb6564714268867b9179bfcfc0112c43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e0ff8d944ddd6ebf0ab7f7ab7b9775">addExpression</a> (DIExpressionCursor &amp;&amp;Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all remaining operations in the <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a>. <a href="#ac2e0ff8d944ddd6ebf0ab7f7ab7b9775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb41a8033222f6fdded66f62cb3acf07">addExpression</a> (DIExpressionCursor &amp;&amp;Expr, llvm::function_ref&lt; bool(unsigned, DIExpressionCursor &amp;)&gt; InsertArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all remaining operations in the <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a>. <a href="#acb41a8033222f6fdded66f62cb3acf07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdab5e48a4c62a742df876d4e55940f">addFragmentOffset</a> (const DIExpression *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If applicable, emit an empty DW_OP_piece / DW_OP_bit_piece to advance to the fragment described by <span class="doxyComputerOutput">Expr</span>. <a href="#a2fdab5e48a4c62a742df876d4e55940f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4533dc140e9df632163f28cb90d31393">emitLegacySExt</a> (unsigned FromBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad910bc547f0601c7152736e444af19d3">emitLegacyZExt</a> (unsigned FromBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2a335e267a7975d64235e578d89a2c9">addWasmLocation</a> (unsigned Index, uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit location information expressed via <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> location + offset The Index is an identifier for locals, globals or operand stack. <a href="#af2a335e267a7975d64235e578d89a2c9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf06301b75ad04934e944056d7e3b06d">setSubRegisterPiece</a> (unsigned SizeInBits, unsigned OffsetInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Push a DW_OP_piece / DW_OP_bit_piece for emitting later, if one is needed to represent a subregister. <a href="#abf06301b75ad04934e944056d7e3b06d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82020f82890e18c9863c168c761d9093">maskSubRegister</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add masking operations to stencil out a subregister. <a href="#a82020f82890e18c9863c168c761d9093">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a138888316d44c8f4e83e75958d0b2125">emitOp</a> (uint8_t Op, const char *Comment=nullptr)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output a dwarf operand and an optional assembler comment. <a href="#a138888316d44c8f4e83e75958d0b2125">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e37c2238da26915e18ce4f433a1872">emitSigned</a> (int64_t Value)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a raw signed value. <a href="#ae0e37c2238da26915e18ce4f433a1872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a> (uint64_t Value)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a raw unsigned value. <a href="#a7420aaf331a0e070180d072dd5f7e4a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53524798940ea32cd77f95057d678aba">emitData1</a> (uint8_t Value)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535243c026735fb647637cdee450d3b9">emitBaseTypeRef</a> (uint64_t Idx)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2fbe56f4cb2d8d947912719b32204bb">enableTemporaryBuffer</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start emitting data to the temporary buffer. <a href="#af2fbe56f4cb2d8d947912719b32204bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e32622eb9d47e4da545f349300010a">disableTemporaryBuffer</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable emission to the temporary buffer. <a href="#a20e32622eb9d47e4da545f349300010a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a255788cd514b624b5c962a02d16a6a65">getTemporaryBufferSize</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the emitted size, in number of bytes, for the data stored in the temporary buffer. <a href="#a255788cd514b624b5c962a02d16a6a65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f7bf56f59e4092017760acc2cd2f6c">commitTemporaryBuffer</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Commit the data stored in the temporary buffer to the main output. <a href="#ae9f7bf56f59e4092017760acc2cd2f6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32ea6310f5bc49d7bd68f9ce8770a77">emitConstu</a> (uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a normalized unsigned constant. <a href="#af32ea6310f5bc49d7bd68f9ce8770a77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c49fb1fb9fd56187b3a506c56c726f2">isFrameRegister</a> (const TargetRegisterInfo &amp;TRI, llvm::Register MachineReg)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the given machine register is the frame register in the current function. <a href="#a2c49fb1fb9fd56187b3a506c56c726f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2889592749021f38232e4aae86bbe44">addReg</a> (int64_t DwarfReg, const char *Comment=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a DW_OP_reg operation. <a href="#ae2889592749021f38232e4aae86bbe44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9d55590b1fef275ffe1c03ff36643e">addBReg</a> (int64_t DwarfReg, int64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a DW_OP_breg operation. <a href="#aff9d55590b1fef275ffe1c03ff36643e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f8efc4431eaf9ad6b7521f1e64a419">addFBReg</a> (int64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit DW_OP_fbreg &lt;Offset&gt;. <a href="#ab5f8efc4431eaf9ad6b7521f1e64a419">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57484713254f31f8412d08ff85259761">addMachineReg</a> (const TargetRegisterInfo &amp;TRI, llvm::Register MachineReg, unsigned MaxSize=~1U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a partial DWARF register operation. <a href="#a57484713254f31f8412d08ff85259761">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8bf7600af257516de6368b0350d5e9c">addOpPiece</a> (unsigned SizeInBits, unsigned OffsetInBits=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a DW_OP_piece or DW_OP_bit_piece operation for a variable fragment. <a href="#af8bf7600af257516de6368b0350d5e9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecec7107d071835d6ad55d7b2006e816">addShr</a> (unsigned ShiftBy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a shift-right dwarf operation. <a href="#aecec7107d071835d6ad55d7b2006e816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b9dafb0c9b15379c0987735ba76809">addAnd</a> (unsigned Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a bitwise and dwarf operation. <a href="#a03b9dafb0c9b15379c0987735ba76809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93f0796a16275cd71f21761c339cd19f">addStackValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a DW_OP_stack_value, if supported. <a href="#a93f0796a16275cd71f21761c339cd19f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize an entry value by emitting its size operand, and committing the DWARF block which has been emitted to the temporary buffer. <a href="#a9e8af6b5a740749d2953cdca8c833e92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4766cf577f992a4cd6286696c47c01c0">cancelEntryValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cancel the emission of an entry value. <a href="#a4766cf577f992a4cd6286696c47c01c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f932b026f333235fb286cb5206fc208">TagOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add8b8103361d8eaacd6060718059b5d9">IsEmittingEntryValue</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether we are currently emitting an entry value operation. <a href="#add8b8103361d8eaacd6060718059b5d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b9ee4a6edb2c1d9fe79128d97da5b8">CU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfexpression/register">Register</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82429fe91ba06ffa4385d20115182958">DwarfRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The register location, if any. <a href="#a82429fe91ba06ffa4385d20115182958">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e56563110c3919f11b5c08eb4457dd">OffsetInBits</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current Fragment Offset in Bits. <a href="#a27e56563110c3919f11b5c08eb4457dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd5bdc1449ccfe9054e3d540647c5c7">SubRegisterSizeInBits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sometimes we need to add a DW_OP_bit_piece to describe a subregister. <a href="#aacd5bdc1449ccfe9054e3d540647c5c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4743278317e43a8e8c097f187a392d7">SubRegisterOffsetInBits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff61409e6730c315d8356d73919da19">LocationKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9195ccfa14791ecd5d29c144b32ac2">SavedLocationKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c17a9605c4bfbb9986ff36ff1c35f77">LocationFlags</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5ba761b851d8fd81d469598cd9b678">DwarfVersion</a></td>
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

<p>Base class containing the logic for constructing DWARF expressions independently of whether they are emitted into a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> or into a .debug_loc entry.</p>


<p>Some DWARF operations, e.g. DW_OP_entry_value, need to calculate the size of a succeeding DWARF block before the latter is emitted to the output. To handle such cases, data can conditionally be emitted to a temporary buffer, which can later on be committed to the main output. The size of the temporary buffer is queryable, allowing for the size of the data to be emitted before the data is committed.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a2d4874c3f450184303a741b477b8529f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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

<p>The kind of location description being produced.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="a2d4874c3f450184303a741b477b8529fa4a2d696e428f1286b5d265cd77d6aac1"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="a2d4874c3f450184303a741b477b8529fa45b8219495a8256b810b162208b9b734"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Memory<a id="a2d4874c3f450184303a741b477b8529faffed6f101874163407cc07f9c5d84c23"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Implicit<a id="a2d4874c3f450184303a741b477b8529faedb8d8635e8871156b211802e87bba39"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>

</div>
</div>

### anonymous enum  {#a467e19938e9af2b1003b8e56a07f8919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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

<p>Additional location flags which may be combined with any location kind.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EntryValue<a id="a467e19938e9af2b1003b8e56a07f8919a64e30e01fb92fbed321319e4cbc7b868"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Indirect<a id="a467e19938e9af2b1003b8e56a07f8919a9e467bd00311a19e75a75f808990ac0f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallSiteParamValue<a id="a467e19938e9af2b1003b8e56a07f8919a54208072c432df3a9f411db14390bb64"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

</table>
</dd>
</dl>


<p>Currently, entry values are not supported for the Memory location kind.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DwarfExpression() {#af0f024a1be631b3865a2ac37210ad57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DwarfExpression::DwarfExpression (unsigned DwarfVersion, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aef5ba761b851d8fd81d469598cd9b678">DwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0c17a9605c4bfbb9986ff36ff1c35f77">LocationFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a5b9195ccfa14791ecd5d29c144b32ac2">SavedLocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae4743278317e43a8e8c097f187a392d7">SubRegisterOffsetInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aacd5bdc1449ccfe9054e3d540647c5c7">SubRegisterSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529fa4a2d696e428f1286b5d265cd77d6aac1">Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debuglocdwarfexpression/#a8895b94063c2f4c1d323fe1c8bdd44cd">llvm::DebugLocDwarfExpression::DebugLocDwarfExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/diedwarfexpression/#a5ef7ffd7796ad4423f7cd36c564cb5c0">llvm::DIEDwarfExpression::DIEDwarfExpression</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~DwarfExpression() {#a89fb4d2b1507375553c2c749364c155f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DwarfExpression::~DwarfExpression ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addConstantFP() {#a7ed44f2251a99b3c609481e114ae9295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addConstantFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp; AP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an floating point constant.</p>

<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ace0bd40e4bee1851ebebb276178d65fc">llvm::APInt::byteSwap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a53524798940ea32cd77f95057d678aba">emitData1</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae4a28f2ce2647934f469d4bb2144612a">llvm::AsmPrinter::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a84c1d72001dd5f34d9a55b3a7bb8a474">llvm::DataLayout::isBigEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a6821f93d5f8c85cb416bf56acb135409">isImplicitLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a238ed978a8838070e8eec9168fc08764">isUnknownLocation</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>.</p>

</div>
</div>

### addExpression() {#ac2e0ff8d944ddd6ebf0ab7f7ab7b9775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addExpression (<a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp;&amp; Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all remaining operations in the <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a>.</p>


<p>The cursor must not contain any DW_OP_LLVM_arg operations.</p>


<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ac2e0ff8d944ddd6ebf0ab7f7ab7b9775">addExpression</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ac2e0ff8d944ddd6ebf0ab7f7ab7b9775">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### addExpression() {#acb41a8033222f6fdded66f62cb3acf07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfExpression::addExpression (<a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp;&amp; Expr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; bool(unsigned, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp;)&gt; InsertArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all remaining operations in the <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a>.</p>


<p>DW_OP_LLVM_arg operations are resolved by calling (<span class="doxyComputerOutput">InsertArg</span>).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if any call to (<span class="doxyComputerOutput">InsertArg</span>) returns false.</p></dd>
</dl>


<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aff9d55590b1fef275ffe1c03ff36643e">addBReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af8bf7600af257516de6368b0350d5e9c">addOpPiece</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a93f0796a16275cd71f21761c339cd19f">addStackValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0caee0952c3cd8bf8106bbfa0a323c1ca82">llvm::dwarf::DW_OP_LLVM_convert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cafa8715d4f64791c3f0b479ececa39d34">llvm::dwarf::DW_OP_LLVM_extract_bits_sext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca3d02f9a2d8b9066b6c6ef1a39018de7f">llvm::dwarf::DW_OP_LLVM_extract_bits_zext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca989f426170b8ef321ffeb4838b4c590f">llvm::dwarf::DW_OP_LLVM_tag_offset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aef5ba761b851d8fd81d469598cd9b678">DwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a535243c026735fb647637cdee450d3b9">emitBaseTypeRef</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af32ea6310f5bc49d7bd68f9ce8770a77">emitConstu</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a53524798940ea32cd77f95057d678aba">emitData1</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a4533dc140e9df632163f28cb90d31393">emitLegacySExt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ad910bc547f0601c7152736e444af19d3">emitLegacyZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae0e37c2238da26915e18ce4f433a1872">emitSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb6564714268867b9179bfcfc0112c43">getOrCreateBaseType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faedb8d8635e8871156b211802e87bba39">Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#add8b8103361d8eaacd6060718059b5d9">IsEmittingEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a6821f93d5f8c85cb416bf56acb135409">isImplicitLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aa6f5b7e87b7ed3a688215c95f870e0d5">isMemoryLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#adaef0bfcd27f5f3266c56a477f288d8a">isParameterValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a480fc786a688aa08fbad50cb961bbdf5">isRegisterLocation</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faffed6f101874163407cc07f9c5d84c23">Memory</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a27e56563110c3919f11b5c08eb4457dd">OffsetInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#abf06301b75ad04934e944056d7e3b06d">setSubRegisterPiece</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae4743278317e43a8e8c097f187a392d7">SubRegisterOffsetInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aacd5bdc1449ccfe9054e3d540647c5c7">SubRegisterSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a5f932b026f333235fb286cb5206fc208">TagOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529fa4a2d696e428f1286b5d265cd77d6aac1">Unknown</a>.</p>

</div>
</div>

### addFragmentOffset() {#a2fdab5e48a4c62a742df876d4e55940f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addFragmentOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If applicable, emit an empty DW_OP_piece / DW_OP_bit_piece to advance to the fragment described by <span class="doxyComputerOutput">Expr</span>.</p>

<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af8bf7600af257516de6368b0350d5e9c">addOpPiece</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a7cc5f1632a4c520497898439c17dc026">llvm::DIExpression::getFragmentInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a09cb593dee41c8fc24828091be9f992f">llvm::DIExpression::isFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a27e56563110c3919f11b5c08eb4457dd">OffsetInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>.</p>

</div>
</div>

### addMachineRegExpression() {#a8337bafd341ca7fa36509bf0ad142c57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfExpression::addMachineRegExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp; Expr, <a href="/web-llvm/docs/api/classes/llvm/register">llvm::Register</a> MachineReg, unsigned FragmentOffsetInBits=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a machine register location.</p>


<p>As an optimization this may also consume the prefix of a <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DwarfExpression</a> if a more efficient representation for combining the register location and the first operation exists.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FragmentOffsetInBits</td>
<td class="doxyParamItemDescription"><p>If this is one fragment out of a fragmented location, this is the offset of the fragment inside the entire variable.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if no DWARF register exists for MachineReg.</p></dd>
</dl>


<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aff9d55590b1fef275ffe1c03ff36643e">addBReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ab5f8efc4431eaf9ad6b7521f1e64a419">addFBReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a57484713254f31f8412d08ff85259761">addMachineReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af8bf7600af257516de6368b0350d5e9c">addOpPiece</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae2889592749021f38232e4aae86bbe44">addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a4766cf577f992a4cd6286696c47c01c0">cancelEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a83bd5b46867c5a738a0ad4ac51fc2187">llvm::DIExpressionCursor::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a82429fe91ba06ffa4385d20115182958">DwarfRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aef5ba761b851d8fd81d469598cd9b678">DwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a0aad1c5c3b32063a952fce1c03f31b98">llvm::DIExpressionCursor::getFragmentInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#add8b8103361d8eaacd6060718059b5d9">IsEmittingEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb6233f16f7169eca9b6afd2f0a5635f">isEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2c49fb1fb9fd56187b3a506c56c726f2">isFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a901d1bd450dc954f08cb3e435ff9560a">isIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aa6f5b7e87b7ed3a688215c95f870e0d5">isMemoryLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#adaef0bfcd27f5f3266c56a477f288d8a">isParameterValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a82020f82890e18c9863c168c761d9093">maskSubRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a76ebfb1bca92ec8cf347deae857a2b35">llvm::DIExpressionCursor::peek</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a01f4fc152711818825bc2fd1d279063d">llvm::DIExpressionCursor::peekNext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a9c374320ed4e895f9afa199987182bd2">RegSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aacd5bdc1449ccfe9054e3d540647c5c7">SubRegisterSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a92d8aed91aadf9006640cd9896e46b27">llvm::DIExpressionCursor::take</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529fa4a2d696e428f1286b5d265cd77d6aac1">Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>.</p>

</div>
</div>

### addSignedConstant() {#ad676cf44e0c249e17c08edb7d3270b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addSignedConstant (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a signed constant.</p>

<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae0e37c2238da26915e18ce4f433a1872">emitSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faedb8d8635e8871156b211802e87bba39">Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a6821f93d5f8c85cb416bf56acb135409">isImplicitLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a238ed978a8838070e8eec9168fc08764">isUnknownLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>.</p>

</div>
</div>

### addUnsignedConstant() {#aa7a84268a368e42a1bed6f9e4def555b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addUnsignedConstant (uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an unsigned constant.</p>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af32ea6310f5bc49d7bd68f9ce8770a77">emitConstu</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faedb8d8635e8871156b211802e87bba39">Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a6821f93d5f8c85cb416bf56acb135409">isImplicitLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a238ed978a8838070e8eec9168fc08764">isUnknownLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ab83b4a350a8392e1524327661a874f0a">addUnsignedConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>.</p>

</div>
</div>

### addUnsignedConstant() {#ab83b4a350a8392e1524327661a874f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addUnsignedConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an unsigned constant.</p>

<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af8bf7600af257516de6368b0350d5e9c">addOpPiece</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a93f0796a16275cd71f21761c339cd19f">addStackValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aa7a84268a368e42a1bed6f9e4def555b">addUnsignedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faedb8d8635e8871156b211802e87bba39">Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a6821f93d5f8c85cb416bf56acb135409">isImplicitLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a238ed978a8838070e8eec9168fc08764">isUnknownLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### addWasmLocation() {#af2a335e267a7975d64235e578d89a2c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addWasmLocation (unsigned Index, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit location information expressed via <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> location + offset The Index is an identifier for locals, globals or operand stack.</p>

<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faedb8d8635e8871156b211802e87bba39">Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faffed6f101874163407cc07f9c5d84c23">Memory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529fa4a2d696e428f1286b5d265cd77d6aac1">Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### beginEntryValueExpression() {#af496d6e3f88f3b85e879bfdfe19b0b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::beginEntryValueExpression (<a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp; ExprCursor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Begin emission of an entry value dwarf operation.</p>


<p>The entry value's first operand is the size of the DWARF block (its second operand), which needs to be calculated at time of emission, so we don't emit any operands here.</p>


<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca0c7ecbb9cc8d5fb23652e00de7b288a0">llvm::dwarf::DW_OP_LLVM_entry_value</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af2fbe56f4cb2d8d947912719b32204bb">enableTemporaryBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a467e19938e9af2b1003b8e56a07f8919a64e30e01fb92fbed321319e4cbc7b868">EntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#add8b8103361d8eaacd6060718059b5d9">IsEmittingEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0c17a9605c4bfbb9986ff36ff1c35f77">LocationFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a5b9195ccfa14791ecd5d29c144b32ac2">SavedLocationKind</a> and <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a92d8aed91aadf9006640cd9896e46b27">llvm::DIExpressionCursor::take</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>.</p>

</div>
</div>

### emitLegacySExt() {#a4533dc140e9df632163f28cb90d31393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::emitLegacySExt (unsigned FromBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>.</p>

</div>
</div>

### emitLegacyZExt() {#ad910bc547f0601c7152736e444af19d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::emitLegacyZExt (unsigned FromBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>.</p>

</div>
</div>

### finalize() {#a2faa879061bc4989e0b78a0928d74e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::finalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This needs to be called last to commit any pending changes.</p>

<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af8bf7600af257516de6368b0350d5e9c">addOpPiece</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a82429fe91ba06ffa4385d20115182958">DwarfRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae4743278317e43a8e8c097f187a392d7">SubRegisterOffsetInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aacd5bdc1449ccfe9054e3d540647c5c7">SubRegisterSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debuglocentry/#accfecad1691b64f7eba86e5080680b64">llvm::DebugLocEntry::finalize</a> and <a href="/web-llvm/docs/api/classes/llvm/diedwarfexpression/#a24b5a14abc09026d9bf5b13f6fe0b2fa">llvm::DIEDwarfExpression::finalize</a>.</p>

</div>
</div>

### getOrCreateBaseType() {#acb6564714268867b9179bfcfc0112c43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DwarfExpression::getOrCreateBaseType (unsigned BitSize, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a3cbae81b76554a92ff2b02baad6931bb">dwarf::TypeKind</a> Encoding)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the index of a base type with the given properties and create one if necessary.</p>

<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>.</p>

</div>
</div>

### isEntryValue() {#acb6233f16f7169eca9b6afd2f0a5635f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfExpression::isEntryValue ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a467e19938e9af2b1003b8e56a07f8919a64e30e01fb92fbed321319e4cbc7b868">EntryValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0c17a9605c4bfbb9986ff36ff1c35f77">LocationFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### isImplicitLocation() {#a6821f93d5f8c85cb416bf56acb135409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfExpression::isImplicitLocation ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faedb8d8635e8871156b211802e87bba39">Implicit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">addConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ad676cf44e0c249e17c08edb7d3270b45">addSignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ab83b4a350a8392e1524327661a874f0a">addUnsignedConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aa7a84268a368e42a1bed6f9e4def555b">addUnsignedConstant</a>.</p>

</div>
</div>

### isIndirect() {#a901d1bd450dc954f08cb3e435ff9560a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfExpression::isIndirect ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a467e19938e9af2b1003b8e56a07f8919a9e467bd00311a19e75a75f808990ac0f">Indirect</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0c17a9605c4bfbb9986ff36ff1c35f77">LocationFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### isMemoryLocation() {#aa6f5b7e87b7ed3a688215c95f870e0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfExpression::isMemoryLocation ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faffed6f101874163407cc07f9c5d84c23">Memory</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### isParameterValue() {#adaef0bfcd27f5f3266c56a477f288d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfExpression::isParameterValue ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a467e19938e9af2b1003b8e56a07f8919a54208072c432df3a9f411db14390bb64">CallSiteParamValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0c17a9605c4bfbb9986ff36ff1c35f77">LocationFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### isRegisterLocation() {#a480fc786a688aa08fbad50cb961bbdf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfExpression::isRegisterLocation ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aff9d55590b1fef275ffe1c03ff36643e">addBReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae2889592749021f38232e4aae86bbe44">addReg</a>.</p>

</div>
</div>

### isUnknownLocation() {#a238ed978a8838070e8eec9168fc08764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfExpression::isUnknownLocation ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529fa4a2d696e428f1286b5d265cd77d6aac1">Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">addConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae2889592749021f38232e4aae86bbe44">addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ad676cf44e0c249e17c08edb7d3270b45">addSignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ab83b4a350a8392e1524327661a874f0a">addUnsignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aa7a84268a368e42a1bed6f9e4def555b">addUnsignedConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a509852c6998b529c06357c2bba7aeabb">setMemoryLocationKind</a>.</p>

</div>
</div>

### setCallSiteParamValueFlag() {#a7188211a4157e4f38345d90d6030c562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfExpression::setCallSiteParamValueFlag ()</td>
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

<p>Lock this down to become a call site parameter location.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a467e19938e9af2b1003b8e56a07f8919a54208072c432df3a9f411db14390bb64">CallSiteParamValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0c17a9605c4bfbb9986ff36ff1c35f77">LocationFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">llvm::DwarfCompileUnit::constructCallSiteParmEntryDIEs</a>.</p>

</div>
</div>

### setEntryValueFlags() {#ae69edc735ccf08fa2817b548619ddd34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::setEntryValueFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lock this down to become an entry value location.</p>

<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a467e19938e9af2b1003b8e56a07f8919a64e30e01fb92fbed321319e4cbc7b868">EntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a467e19938e9af2b1003b8e56a07f8919a9e467bd00311a19e75a75f808990ac0f">Indirect</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0c17a9605c4bfbb9986ff36ff1c35f77">LocationFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a082b9984a203d2a2ba3dd4b5986d4706">setLocation</a>.</p>

</div>
</div>

### setLocation() {#a082b9984a203d2a2ba3dd4b5986d4706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::setLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinelocation">MachineLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * DIExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the location (<span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>) and <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> (<span class="doxyComputerOutput">DIExpr</span>) to describe.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a012168d44e49d5120cf8919cd096fd3b">llvm::DIExpression::isEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae69edc735ccf08fa2817b548619ddd34">setEntryValueFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a509852c6998b529c06357c2bba7aeabb">setMemoryLocationKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>.</p>

</div>
</div>

### setMemoryLocationKind() {#a509852c6998b529c06357c2bba7aeabb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfExpression::setMemoryLocationKind ()</td>
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

<p>Lock this down to become a memory location description.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a238ed978a8838070e8eec9168fc08764">isUnknownLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2d4874c3f450184303a741b477b8529faffed6f101874163407cc07f9c5d84c23">Memory</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a082b9984a203d2a2ba3dd4b5986d4706">setLocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addAnd() {#a03b9dafb0c9b15379c0987735ba76809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addAnd (unsigned Mask)</td>
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

<p>Emit a bitwise and dwarf operation.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af32ea6310f5bc49d7bd68f9ce8770a77">emitConstu</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a82020f82890e18c9863c168c761d9093">maskSubRegister</a>.</p>

</div>
</div>

### addBReg() {#aff9d55590b1fef275ffe1c03ff36643e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addBReg (int64_t DwarfReg, int64_t Offset)</td>
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

<p>Emit a DW_OP_breg operation.</p>

<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae0e37c2238da26915e18ce4f433a1872">emitSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a480fc786a688aa08fbad50cb961bbdf5">isRegisterLocation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### addFBReg() {#ab5f8efc4431eaf9ad6b7521f1e64a419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addFBReg (int64_t Offset)</td>
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

<p>Emit DW_OP_fbreg &lt;Offset&gt;.</p>

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae0e37c2238da26915e18ce4f433a1872">emitSigned</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### addMachineReg() {#a57484713254f31f8412d08ff85259761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfExpression::addMachineReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/register">llvm::Register</a> MachineReg, unsigned MaxSize=~1U)</td>
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

<p>Emit a partial DWARF register operation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MachineReg</td>
<td class="doxyParamItemDescription"><p>The register number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxSize</td>
<td class="doxyParamItemDescription"><p>If the register must be composed from sub-registers this is an upper bound for how many bits the emitted DW_OP_piece may cover.</p></td>
</tr>
</table>
</dd>
</dl>

<p>If size and offset is zero an operation for the entire register is emitted: Some targets do not provide a DWARF register number for every register. If this is the case, this function will attempt to emit a DWARF register by emitting a fragment of a super-register or by piecing together multiple subregisters that alias the register.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if no DWARF register exists for MachineReg.</p></dd>
</dl>


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarfexpression/register/#a299b21f22318cb802f9136554ef10585">llvm::DwarfExpression::Register::createRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfexpression/register/#ad5c60e74c887beef5da6437bba2327c4">llvm::DwarfExpression::Register::createSubRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a82429fe91ba06ffa4385d20115182958">DwarfRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2c49fb1fb9fd56187b3a506c56c726f2">isFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a9c374320ed4e895f9afa199987182bd2">RegSize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#abf06301b75ad04934e944056d7e3b06d">setSubRegisterPiece</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a585f149dd8c344a40c53b1694d3161ed">llvm::SmallBitVector::test</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### addOpPiece() {#af8bf7600af257516de6368b0350d5e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addOpPiece (unsigned SizeInBits, unsigned OffsetInBits=0)</td>
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

<p>Emit a DW_OP_piece or DW_OP_bit_piece operation for a variable fragment.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>This is an optional offset into the location that is at the top of the DWARF stack.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a27e56563110c3919f11b5c08eb4457dd">OffsetInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2fdab5e48a4c62a742df876d4e55940f">addFragmentOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ab83b4a350a8392e1524327661a874f0a">addUnsignedConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2faa879061bc4989e0b78a0928d74e29">finalize</a>.</p>

</div>
</div>

### addReg() {#ae2889592749021f38232e4aae86bbe44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addReg (int64_t DwarfReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Comment=nullptr)</td>
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

<p>Emit a DW_OP_reg operation.</p>


<p>Note that this is only legal inside a DWARF register location description.</p>


<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a480fc786a688aa08fbad50cb961bbdf5">isRegisterLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a238ed978a8838070e8eec9168fc08764">isUnknownLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### addShr() {#aecec7107d071835d6ad55d7b2006e816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addShr (unsigned ShiftBy)</td>
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

<p>Emit a shift-right dwarf operation.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af32ea6310f5bc49d7bd68f9ce8770a77">emitConstu</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a82020f82890e18c9863c168c761d9093">maskSubRegister</a>.</p>

</div>
</div>

### addStackValue() {#a93f0796a16275cd71f21761c339cd19f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::addStackValue ()</td>
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

<p>Emit a DW_OP_stack_value, if supported.</p>


<p>The proper way to describe a constant value is DW_OP_constu &lt;const&gt;, DW_OP_stack_value. Unfortunately, DW_OP_stack_value was not available until DWARF 4, so we will continue to generate DW_OP_constu &lt;const&gt; for DWARF 2 and DWARF 3. Technically, this is incorrect since DW_OP_const &lt;const&gt; actually describes a value at a constant address, not a constant value. However, in the past there was no better way to describe a constant value, so the producers and consumers started to rely on heuristics to disambiguate the value vs. location status of the expression. See PR21176 for more details.</p>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aef5ba761b851d8fd81d469598cd9b678">DwarfVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ab83b4a350a8392e1524327661a874f0a">addUnsignedConstant</a>.</p>

</div>
</div>

### cancelEntryValue() {#a4766cf577f992a4cd6286696c47c01c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::cancelEntryValue ()</td>
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

<p>Cancel the emission of an entry value.</p>

<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a20e32622eb9d47e4da545f349300010a">disableTemporaryBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a255788cd514b624b5c962a02d16a6a65">getTemporaryBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#add8b8103361d8eaacd6060718059b5d9">IsEmittingEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a5b9195ccfa14791ecd5d29c144b32ac2">SavedLocationKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### commitTemporaryBuffer() {#ae9f7bf56f59e4092017760acc2cd2f6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfExpression::commitTemporaryBuffer ()</td>
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

<p>Commit the data stored in the temporary buffer to the main output.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>.</p>

</div>
</div>

### disableTemporaryBuffer() {#a20e32622eb9d47e4da545f349300010a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfExpression::disableTemporaryBuffer ()</td>
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

<p>Disable emission to the temporary buffer.</p>


<p>This does not commit data in the temporary buffer to the main output.</p>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a4766cf577f992a4cd6286696c47c01c0">cancelEntryValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>.</p>

</div>
</div>

### emitBaseTypeRef() {#a535243c026735fb647637cdee450d3b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfExpression::emitBaseTypeRef (uint64_t Idx)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>.</p>

</div>
</div>

### emitConstu() {#af32ea6310f5bc49d7bd68f9ce8770a77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::emitConstu (uint64_t Value)</td>
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

<p>Emit a normalized unsigned constant.</p>

<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a03b9dafb0c9b15379c0987735ba76809">addAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aecec7107d071835d6ad55d7b2006e816">addShr</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aa7a84268a368e42a1bed6f9e4def555b">addUnsignedConstant</a>.</p>

</div>
</div>

### emitData1() {#a53524798940ea32cd77f95057d678aba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfExpression::emitData1 (uint8_t Value)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">addConstantFP</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>.</p>

</div>
</div>

### emitOp() {#a138888316d44c8f4e83e75958d0b2125}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfExpression::emitOp (uint8_t Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Comment=nullptr)</td>
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

<p>Output a dwarf operand and an optional assembler comment.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a03b9dafb0c9b15379c0987735ba76809">addAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aff9d55590b1fef275ffe1c03ff36643e">addBReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">addConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ab5f8efc4431eaf9ad6b7521f1e64a419">addFBReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af8bf7600af257516de6368b0350d5e9c">addOpPiece</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae2889592749021f38232e4aae86bbe44">addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aecec7107d071835d6ad55d7b2006e816">addShr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ad676cf44e0c249e17c08edb7d3270b45">addSignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a93f0796a16275cd71f21761c339cd19f">addStackValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af2a335e267a7975d64235e578d89a2c9">addWasmLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af32ea6310f5bc49d7bd68f9ce8770a77">emitConstu</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a4533dc140e9df632163f28cb90d31393">emitLegacySExt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ad910bc547f0601c7152736e444af19d3">emitLegacyZExt</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>.</p>

</div>
</div>

### emitSigned() {#ae0e37c2238da26915e18ce4f433a1872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfExpression::emitSigned (int64_t Value)</td>
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

<p>Emit a raw signed value.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aff9d55590b1fef275ffe1c03ff36643e">addBReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ab5f8efc4431eaf9ad6b7521f1e64a419">addFBReg</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ad676cf44e0c249e17c08edb7d3270b45">addSignedConstant</a>.</p>

</div>
</div>

### emitUnsigned() {#a7420aaf331a0e070180d072dd5f7e4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfExpression::emitUnsigned (uint64_t Value)</td>
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

<p>Emit a raw unsigned value.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aff9d55590b1fef275ffe1c03ff36643e">addBReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">addConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af8bf7600af257516de6368b0350d5e9c">addOpPiece</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae2889592749021f38232e4aae86bbe44">addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af2a335e267a7975d64235e578d89a2c9">addWasmLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af32ea6310f5bc49d7bd68f9ce8770a77">emitConstu</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a4533dc140e9df632163f28cb90d31393">emitLegacySExt</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ad910bc547f0601c7152736e444af19d3">emitLegacyZExt</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>.</p>

</div>
</div>

### enableTemporaryBuffer() {#af2fbe56f4cb2d8d947912719b32204bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DwarfExpression::enableTemporaryBuffer ()</td>
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

<p>Start emitting data to the temporary buffer.</p>


<p>The data stored in the temporary buffer can be committed to the main output using <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae9f7bf56f59e4092017760acc2cd2f6c">commitTemporaryBuffer()</a>.</p>


<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af496d6e3f88f3b85e879bfdfe19b0b40">beginEntryValueExpression</a>.</p>

</div>
</div>

### finalizeEntryValue() {#a9e8af6b5a740749d2953cdca8c833e92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::finalizeEntryValue ()</td>
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

<p>Finalize an entry value by emitting its size operand, and committing the DWARF block which has been emitted to the temporary buffer.</p>

<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae9f7bf56f59e4092017760acc2cd2f6c">commitTemporaryBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a20e32622eb9d47e4da545f349300010a">disableTemporaryBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a138888316d44c8f4e83e75958d0b2125">emitOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7420aaf331a0e070180d072dd5f7e4a6">emitUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a467e19938e9af2b1003b8e56a07f8919a64e30e01fb92fbed321319e4cbc7b868">EntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a255788cd514b624b5c962a02d16a6a65">getTemporaryBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#add8b8103361d8eaacd6060718059b5d9">IsEmittingEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0c17a9605c4bfbb9986ff36ff1c35f77">LocationFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a0ff61409e6730c315d8356d73919da19">LocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a5b9195ccfa14791ecd5d29c144b32ac2">SavedLocationKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### getTemporaryBufferSize() {#a255788cd514b624b5c962a02d16a6a65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::DwarfExpression::getTemporaryBufferSize ()</td>
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

<p>Return the emitted size, in number of bytes, for the data stored in the temporary buffer.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a4766cf577f992a4cd6286696c47c01c0">cancelEntryValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>.</p>

</div>
</div>

### isFrameRegister() {#a2c49fb1fb9fd56187b3a506c56c726f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::DwarfExpression::isFrameRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/register">llvm::Register</a> MachineReg)</td>
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

<p>Return whether the given machine register is the frame register in the current function.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a27e56563110c3919f11b5c08eb4457dd">OffsetInBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a57484713254f31f8412d08ff85259761">addMachineReg</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### maskSubRegister() {#a82020f82890e18c9863c168c761d9093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfExpression::maskSubRegister ()</td>
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

<p>Add masking operations to stencil out a subregister.</p>


<p>add masking operations to stencil out a subregister.</p>


<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a03b9dafb0c9b15379c0987735ba76809">addAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aecec7107d071835d6ad55d7b2006e816">addShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae4743278317e43a8e8c097f187a392d7">SubRegisterOffsetInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aacd5bdc1449ccfe9054e3d540647c5c7">SubRegisterSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>.</p>

</div>
</div>

### setSubRegisterPiece() {#abf06301b75ad04934e944056d7e3b06d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfExpression::setSubRegisterPiece (unsigned SizeInBits, unsigned OffsetInBits)</td>
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

<p>Push a DW_OP_piece / DW_OP_bit_piece for emitting later, if one is needed to represent a subregister.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a27e56563110c3919f11b5c08eb4457dd">OffsetInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae4743278317e43a8e8c097f187a392d7">SubRegisterOffsetInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aacd5bdc1449ccfe9054e3d540647c5c7">SubRegisterSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a57484713254f31f8412d08ff85259761">addMachineReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### TagOffset {#a5f932b026f333235fb286cb5206fc208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint8_t&gt; llvm::DwarfExpression::TagOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/debuglocentry/#accfecad1691b64f7eba86e5080680b64">llvm::DebugLocEntry::finalize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CU {#a64b9ee4a6edb2c1d9fe79128d97da5b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCompileUnit&amp; llvm::DwarfExpression::CU</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>

</div>
</div>

### DwarfRegs {#a82429fe91ba06ffa4385d20115182958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 2&gt; llvm::DwarfExpression::DwarfRegs</td>
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

<p>The register location, if any.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a57484713254f31f8412d08ff85259761">addMachineReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2faa879061bc4989e0b78a0928d74e29">finalize</a>.</p>

</div>
</div>

### DwarfVersion {#aef5ba761b851d8fd81d469598cd9b678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfExpression::DwarfVersion</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a93f0796a16275cd71f21761c339cd19f">addStackValue</a>, <a href="/web-llvm/docs/api/classes/llvm/debuglocdwarfexpression/#a8895b94063c2f4c1d323fe1c8bdd44cd">llvm::DebugLocDwarfExpression::DebugLocDwarfExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af0f024a1be631b3865a2ac37210ad57c">DwarfExpression</a>.</p>

</div>
</div>

### IsEmittingEntryValue {#add8b8103361d8eaacd6060718059b5d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfExpression::IsEmittingEntryValue = false</td>
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

<p>Whether we are currently emitting an entry value operation.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af496d6e3f88f3b85e879bfdfe19b0b40">beginEntryValueExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a4766cf577f992a4cd6286696c47c01c0">cancelEntryValue</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>.</p>

</div>
</div>

### LocationFlags {#a0c17a9605c4bfbb9986ff36ff1c35f77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfExpression::LocationFlags</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af496d6e3f88f3b85e879bfdfe19b0b40">beginEntryValueExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af0f024a1be631b3865a2ac37210ad57c">DwarfExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb6233f16f7169eca9b6afd2f0a5635f">isEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a901d1bd450dc954f08cb3e435ff9560a">isIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#adaef0bfcd27f5f3266c56a477f288d8a">isParameterValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7188211a4157e4f38345d90d6030c562">setCallSiteParamValueFlag</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae69edc735ccf08fa2817b548619ddd34">setEntryValueFlags</a>.</p>

</div>
</div>

### LocationKind {#a0ff61409e6730c315d8356d73919da19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfExpression::LocationKind</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ae2889592749021f38232e4aae86bbe44">addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ad676cf44e0c249e17c08edb7d3270b45">addSignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ab83b4a350a8392e1524327661a874f0a">addUnsignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aa7a84268a368e42a1bed6f9e4def555b">addUnsignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af2a335e267a7975d64235e578d89a2c9">addWasmLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af496d6e3f88f3b85e879bfdfe19b0b40">beginEntryValueExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a4766cf577f992a4cd6286696c47c01c0">cancelEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af0f024a1be631b3865a2ac37210ad57c">DwarfExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a6821f93d5f8c85cb416bf56acb135409">isImplicitLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aa6f5b7e87b7ed3a688215c95f870e0d5">isMemoryLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a480fc786a688aa08fbad50cb961bbdf5">isRegisterLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a238ed978a8838070e8eec9168fc08764">isUnknownLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a509852c6998b529c06357c2bba7aeabb">setMemoryLocationKind</a>.</p>

</div>
</div>

### OffsetInBits {#a27e56563110c3919f11b5c08eb4457dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DwarfExpression::OffsetInBits = 0</td>
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

<p>Current Fragment Offset in Bits.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2fdab5e48a4c62a742df876d4e55940f">addFragmentOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af8bf7600af257516de6368b0350d5e9c">addOpPiece</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2c49fb1fb9fd56187b3a506c56c726f2">isFrameRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#abf06301b75ad04934e944056d7e3b06d">setSubRegisterPiece</a>.</p>

</div>
</div>

### SavedLocationKind {#a5b9195ccfa14791ecd5d29c144b32ac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfExpression::SavedLocationKind</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af496d6e3f88f3b85e879bfdfe19b0b40">beginEntryValueExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a4766cf577f992a4cd6286696c47c01c0">cancelEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af0f024a1be631b3865a2ac37210ad57c">DwarfExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a9e8af6b5a740749d2953cdca8c833e92">finalizeEntryValue</a>.</p>

</div>
</div>

### SubRegisterOffsetInBits {#ae4743278317e43a8e8c097f187a392d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfExpression::SubRegisterOffsetInBits</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af0f024a1be631b3865a2ac37210ad57c">DwarfExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2faa879061bc4989e0b78a0928d74e29">finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a82020f82890e18c9863c168c761d9093">maskSubRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#abf06301b75ad04934e944056d7e3b06d">setSubRegisterPiece</a>.</p>

</div>
</div>

### SubRegisterSizeInBits {#aacd5bdc1449ccfe9054e3d540647c5c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfExpression::SubRegisterSizeInBits</td>
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

<p>Sometimes we need to add a DW_OP_bit_piece to describe a subregister.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#acb41a8033222f6fdded66f62cb3acf07">addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af0f024a1be631b3865a2ac37210ad57c">DwarfExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2faa879061bc4989e0b78a0928d74e29">finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a82020f82890e18c9863c168c761d9093">maskSubRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#abf06301b75ad04934e944056d7e3b06d">setSubRegisterPiece</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-cpp">DwarfExpression.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
