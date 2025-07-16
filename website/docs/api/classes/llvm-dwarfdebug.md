---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfdebug
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DwarfDebug` Class Reference

<p>Collects and handles dwarf debug information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DwarfDebug { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">CodeGen/AsmPrinter/DwarfDebug.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debughandlerbase">DebugHandlerBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for debug information backends. <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa35e9688e484e2bc6b8b28f29577e836">MDNodeSet</a> = <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, 2 &gt;, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, 2 &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map function-local imported entities to their parent local scope (either <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a> or <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a>) for a processed function (including inlined subprograms). <a href="#aa35e9688e484e2bc6b8b28f29577e836">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa596b67ba2e12b61bca47c497faf88">InlinedEntity</a> = <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#ad623a98e1212d4fb4d655e67828066be">DbgValueHistoryMap::InlinedEntity</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MinimizeAddrInV5 { <a href="#a535beef0b6ae2e8972ee23458cd7b629">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DWARF5AccelTableKind { <a href="#a16869ddb4e88c84883d14a2f2756f574">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3ee50c530039dd44c410b678a54ec6">DwarfDebug</a> (AsmPrinter *A)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef1988409d5331ca6f9a09e10b36ec5">~DwarfDebug</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f59a82f48553634ac4625cb8166071e">beginModule</a> (Module *M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all Dwarf sections that should come prior to the content. <a href="#a3f59a82f48553634ac4625cb8166071e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb62e2b6d18233c7069ea46cf3855b61">endModule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all Dwarf sections that should come after the content. <a href="#adb62e2b6d18233c7069ea46cf3855b61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0627dac3e2666638fa514a2d98299ef">emitInitialLocDirective</a> (const MachineFunction &amp;MF, unsigned CUID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits inital debug location directive. <a href="#ab0627dac3e2666638fa514a2d98299ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ae5e1ec2093c40fa0e3211bd043057b">beginInstruction</a> (const MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> beginning of an instruction. <a href="#a6ae5e1ec2093c40fa0e3211bd043057b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7819cf4c91db139508a49f5e0401243">beginCodeAlignment</a> (const MachineBasicBlock &amp;MBB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> beginning of code alignment. <a href="#ae7819cf4c91db139508a49f5e0401243">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06f166cd8884265b3a1ea2849f0c026">addDwarfTypeUnitType</a> (DwarfCompileUnit &amp;CU, StringRef Identifier, DIE &amp;Die, const DICompositeType *CTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to the set of types that we're going to pull into type units. <a href="#ad06f166cd8884265b3a1ea2849f0c026">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e772cb1e4a87f6e2ec29356d60ab89e">addArangeLabel</a> (SymbolCU SCU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a label so that arange data can be generated for it. <a href="#a5e772cb1e4a87f6e2ec29356d60ab89e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d98873019d57cc27c24b3e51ad11894">setSymbolSize</a> (const MCSymbol *Sym, uint64_t Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For symbols that have a size designated (e.g. <a href="#a2d98873019d57cc27c24b3e51ad11894">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a417b1e5a8cac92f3d915173aa72a9869">useAllLinkageNames</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether we should emit all DW_AT_[MIPS_]linkage_name. <a href="#a417b1e5a8cac92f3d915173aa72a9869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2270a27c4f224367aa5e7fd87cef7726">useGNUTLSOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether to use DW_OP_GNU_push_tls_address, instead of the standard DW_OP_form_tls_address opcode. <a href="#a2270a27c4f224367aa5e7fd87cef7726">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7782075e0f7e6801bd76aadc2f753a0">useDWARF2Bitfields</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether to use the DWARF2 format for bitfields instyead of the DWARF4 format. <a href="#ab7782075e0f7e6801bd76aadc2f753a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a63e95e94720e08548754358d0a1baa">useInlineStrings</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether to use inline strings. <a href="#a5a63e95e94720e08548754358d0a1baa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac339921df038ec6d83250746d09efd77">useRangesSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether ranges section should be emitted. <a href="#ac339921df038ec6d83250746d09efd77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f0b6e92cb91f8dbdc38083845e2462f">alwaysUseRanges</a> (const DwarfCompileUnit &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether range encodings should be used for single entry range lists. <a href="#a3f0b6e92cb91f8dbdc38083845e2462f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05f1a7c06166d9783b1fc4fbb94eda0">useAddrOffsetExpressions</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290ee02ad9767f2b33dd22d83fb3eb46">useAddrOffsetForm</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf5b76e85c6969ed83ad9330a1ba144">useSectionsAsReferences</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether to use sections as labels rather than temp symbols. <a href="#a7bf5b76e85c6969ed83ad9330a1ba144">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65337903876e29f1321b84f208590446">generateTypeUnits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether to generate DWARF v4 type units. <a href="#a65337903876e29f1321b84f208590446">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51f">AccelTableKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd711d7e6dd61972100f0338c3e3b910">getAccelTableKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns what kind (if any) of accelerator tables to emit. <a href="#afd711d7e6dd61972100f0338c3e3b910">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1836fd53620de40512b95c5db372af9">setTheAccelTableKind</a> (AccelTableKind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Seet TheAccelTableKind. <a href="#ab1836fd53620de40512b95c5db372af9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0cac76b9cd44a8e75eb1f7c44161f7">useAppleExtensionAttributes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa578b94a4e307580b4feed7ede93e3af">useSplitDwarf</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether or not to change the current debug info for the split dwarf proposal support. <a href="#aa578b94a4e307580b4feed7ede93e3af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fca111b048ad8daf6cc55fc02aab19">useSegmentedStringOffsetsTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether to generate a string offsets table with (possibly shared) contributions from each <a href="/web-llvm/docs/api/namespaces/cu">CU</a> and type unit. <a href="#a12fca111b048ad8daf6cc55fc02aab19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3608f879e120c9344fd7cdb2f0dddb0d">emitDebugEntryValues</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8798358ce24fcff571414ad2b949a3b3">useOpConvert</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d7b74e02d1e0dc4a555a18ad536f47">shareAcrossDWOCUs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ace4bbb6f50507e82b0fbec1ee7ea74">getDwarfVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Dwarf Version. <a href="#a3ace4bbb6f50507e82b0fbec1ee7ea74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46b0fb1505ef705cdf28d6b2612c5579">getDwarfSectionOffsetForm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a suitable DWARF form to represent a section offset, i.e. <a href="#a46b0fb1505ef705cdf28d6b2612c5579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299df286f8b78890bc5dc0ffe53ea751">getPrevCU</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the previous <a href="/web-llvm/docs/api/namespaces/cu">CU</a> that was being updated. <a href="#a299df286f8b78890bc5dc0ffe53ea751">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ccadedfcbf61f5b551d50299d4818b8">setPrevCU</a> (const DwarfCompileUnit *PrevCU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e76c771af1d9f50bb133eb3aeadb087">terminateLineTable</a> (const DwarfCompileUnit *CU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Terminate the line table by adding the last range label. <a href="#a8e76c771af1d9f50bb133eb3aeadb087">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debuglocstream">DebugLocStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d7651181b9b8aaee16273701c1b3e14">getDebugLocs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the entries for the .debug_loc section. <a href="#a7d7651181b9b8aaee16273701c1b3e14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1945df4a676ee30059653cc05be15a">emitDebugLocEntry</a> (ByteStreamer &amp;Streamer, const DebugLocStream::Entry &amp;Entry, const DwarfCompileUnit *CU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an entry for the debug loc section. <a href="#a3d1945df4a676ee30059653cc05be15a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a990840b65d04e11c55ea3c2eff5ad47c">emitDebugLocEntryLocation</a> (const DebugLocStream::Entry &amp;Entry, const DwarfCompileUnit *CU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the location for a debug loc entry, including the size header. <a href="#a990840b65d04e11c55ea3c2eff5ad47c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f60785d1dd3859ae53f738c01d366a7">addSubprogramNames</a> (const DwarfUnit &amp;Unit, const DICompileUnit::DebugNameTableKind NameTableKind, const DISubprogram *SP, DIE &amp;Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/addresspool">AddressPool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c58cede6903d5a3190eef36f0e1732e">getAddressPool</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac81660b2aac6a21b5b3c18eb6ace603e">addAccelName</a> (const DwarfUnit &amp;Unit, const DICompileUnit::DebugNameTableKind NameTableKind, StringRef Name, const DIE &amp;Die)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a450a3a1f0d314a6155817f3854957da8">addAccelObjC</a> (const DwarfUnit &amp;Unit, const DICompileUnit::DebugNameTableKind NameTableKind, StringRef Name, const DIE &amp;Die)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e8976df7c8f2c1513d641a5d46e5cf1">addAccelNamespace</a> (const DwarfUnit &amp;Unit, const DICompileUnit::DebugNameTableKind NameTableKind, StringRef Name, const DIE &amp;Die)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2cb1c03cabf7e346aec758eff539405">addAccelType</a> (const DwarfUnit &amp;Unit, const DICompileUnit::DebugNameTableKind NameTableKind, StringRef Name, const DIE &amp;Die, char Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53991b8335c42c8720bd5ed5af77371e">getCurrentFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb34ac66067af067228eaaab8df6e982">isLexicalScopeDIENull</a> (LexicalScope *Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function to check whether the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for a given Scope is going to be null. <a href="#acb34ac66067af067228eaaab8df6e982">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b235aebc8b1bd478885e18120f2e50e">lookupCU</a> (const DIE *Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the matching <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> for the given <a href="/web-llvm/docs/api/namespaces/cu">CU</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a9b235aebc8b1bd478885e18120f2e50e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391c85ac8c1a5f6da2fc65c3a827213e">lookupCU</a> (const DIE *Die) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac946573bbb92083695b8e056178878cd">getStringTypeLoc</a> (const DIStringType *ST) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ff7e038b33d8e36bf36122af99d59a">addStringTypeLoc</a> (const DIStringType *ST, unsigned Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa185d37e50840c4efe89db1f96a44540">getSectionLabel</a> (const MCSection *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41f368207329f5957e26e92ca87ebdbf">insertSectionLabel</a> (const MCSymbol *S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee028fdde7a97c3cb31217670eff28f">getMD5AsBytes</a> (const DIFile *File) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the <span class="doxyComputerOutput">File</span> has an <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> checksum, return it as an MD5Result allocated in the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a>. <a href="#a1ee028fdde7a97c3cb31217670eff28f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">MDNodeSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18bb61a9ecdbe2308a41c82c73c4b23c">getLocalDeclsForScope</a> (const DILocalScope *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3edd84f3526327ef72c9c5300eb07865">setCurrentDWARF5AccelTable</a> (const DWARF5AccelTableKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the current <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> to use. <a href="#a3edd84f3526327ef72c9c5300eb07865">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ca9a74fb66831c613c1a0fa1d7b5b3">getCurrentDWARF5AccelTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns either <a href="/web-llvm/docs/api/namespaces/cu">CU</a> or TU <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a>. <a href="#a71ca9a74fb66831c613c1a0fa1d7b5b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/debuggertuning/#ga7967d9d5ff2b6b0344d919d2d27965cb">tuneForGDB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/debuggertuning/#ga98337eccc708fb48a33a9755764014ab">tuneForLLDB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/debuggertuning/#ga12d17eb7e0ee4182377397d9fb39459d">tuneForSCE</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/debuggertuning/#ga42e75cae125454aea72ff1c76dabd5b3">tuneForDBX</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af89d6d0bd3c47fc34cb897ea7131f9ac">beginFunctionImpl</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather pre-function debug information. <a href="#af89d6d0bd3c47fc34cb897ea7131f9ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f0353f65281b2b560d4421d439ed836">endFunctionImpl</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather and emit post-function debug information. <a href="#a8f0353f65281b2b560d4421d439ed836">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa2a9e9b8cba40b4beaf474f7ffb914d">getDwarfCompileUnitIDForLineTable</a> (const DwarfCompileUnit &amp;CU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get Dwarf compile unit <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for line table. <a href="#aaa2a9e9b8cba40b4beaf474f7ffb914d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a541a61ef08e721f29862af1393d30ce3">skippedNonDebugFunction</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdwarfdwolinetable">MCDwarfDwoLineTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aafc4e1b1f9b18164683efd15c7dd29">getDwoLineTable</a> (const DwarfCompileUnit &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ad22adbcd64241446cd3474f1e0cb5d">getUnits</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b40452731caadd40954e8044960858">ensureAbstractEntityIsCreatedIfScoped</a> (DwarfCompileUnit &amp;CU, const DINode *Node, const MDNode *Scope)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa679bfc2b2dfe25f593e4983e0a32e">createConcreteEntity</a> (DwarfCompileUnit &amp;TheCU, LexicalScope &amp;Scope, const DINode *Node, const DILocation *Location, const MCSymbol *Sym=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e35f96e21c4cb9e827cdd4fa63742c">constructAbstractSubprogramScopeDIE</a> (DwarfCompileUnit &amp;SrcCU, LexicalScope *Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for this abstract scope. <a href="#a78e35f96e21c4cb9e827cdd4fa63742c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d2f34319b3009ed68be026f80ce56c">constructCallSiteEntryDIEs</a> (const DISubprogram &amp;SP, DwarfCompileUnit &amp;CU, DIE &amp;ScopeDIE, const MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct DIEs for call site entries describing the calls in <span class="doxyComputerOutput">MF</span>. <a href="#ab7d2f34319b3009ed68be026f80ce56c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DataT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7d552ce38bc2faf81c2f9ff6bca7f9b">addAccelNameImpl</a> (const DwarfUnit &amp;Unit, const DICompileUnit::DebugNameTableKind NameTableKind, AccelTable&lt; DataT &gt; &amp;AppleAccel, StringRef Name, const DIE &amp;Die)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6abdc9280ceb60fcd1a42b77398056f">finishEntityDefinitions</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411599050c5297d34d6025d4f393aafe">finishSubprogramDefinitions</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4101787ca7936838ac4f857e747c0ae">finalizeModuleInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finish off debug information after all functions have been processed. <a href="#ae4101787ca7936838ac4f857e747c0ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea1b427736649d887359105c322a3ebd">emitDebugInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug info section. <a href="#aea1b427736649d887359105c322a3ebd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae62db5220f39dcae803c8bd3a469362b">emitAbbreviations</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the abbreviation section. <a href="#ae62db5220f39dcae803c8bd3a469362b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a1021ce688e7ba4d47d0f58563c1e9a">emitStringOffsetsTableHeader</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the string offsets table header. <a href="#a6a1021ce688e7ba4d47d0f58563c1e9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AccelTableT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d8a1896cb87dd31738565620f00e843">emitAccel</a> (AccelTableT &amp;Accel, MCSection *Section, StringRef TableName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a specified accelerator table. <a href="#a5d8a1896cb87dd31738565620f00e843">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb732e5079052a90275442c3098166b">emitAccelDebugNames</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit DWARF v5 accelerator table. <a href="#a9cb732e5079052a90275442c3098166b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a222cf09e6c4804ae1896685ad7836db6">emitAccelNames</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit visible names into a hashed accelerator table section. <a href="#a222cf09e6c4804ae1896685ad7836db6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3156c1a41c07201b14d9f4a59549d286">emitAccelObjC</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit objective C classes and categories into a hashed accelerator table section. <a href="#a3156c1a41c07201b14d9f4a59549d286">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2f7182c65dfe8615c6338bf665dc46a">emitAccelNamespaces</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit namespace dies into a hashed accelerator table. <a href="#aa2f7182c65dfe8615c6338bf665dc46a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888cbe0d940d41680b3e3e7ea20e76ea">emitAccelTypes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit type dies into a hashed accelerator table. <a href="#a888cbe0d940d41680b3e3e7ea20e76ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe392b37305b49c975ef940dbfaf0ab">emitDebugPubSections</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit visible names and types into debug pubnames and pubtypes sections. <a href="#aafe392b37305b49c975ef940dbfaf0ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb2d847bb9041ed400ecbcc93d6d868">emitDebugPubSection</a> (bool GnuStyle, StringRef Name, DwarfCompileUnit *TheU, const StringMap&lt; const DIE * &gt; &amp;Globals)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabbfeba2992aab537c72e4af80236898">emitDebugStr</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit null-terminated strings into a debug str section. <a href="#aabbfeba2992aab537c72e4af80236898">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08fb18e1a80a3c5290445e5ec6e506e1">emitDebugLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit variable locations into a debug loc section. <a href="#a08fb18e1a80a3c5290445e5ec6e506e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7041a619e2c6e5b7f3a2f9b3b8e1998">emitDebugLocDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit variable locations into a debug loc dwo section. <a href="#ac7041a619e2c6e5b7f3a2f9b3b8e1998">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae073459a24daa629ee53ca43b503c652">emitDebugLocImpl</a> (MCSection *Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a9bd2e4d25cb2ea4690794fdcf638c">emitDebugARanges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit address ranges into a debug aranges section. <a href="#af8a9bd2e4d25cb2ea4690794fdcf638c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665b2fdd208909f9df63787126d47bb2">emitDebugRanges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit address ranges into a debug ranges section. <a href="#a665b2fdd208909f9df63787126d47bb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8407a67cede0cd93673ac1bc98ea4ff7">emitDebugRangesDWO</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12df3a3d908e91050692b5f838787ceb">emitDebugRangesImpl</a> (const DwarfFile &amp;Holder, MCSection *Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b132d74962e2aec9ebd9087209f23d">emitDebugMacinfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit macros into a debug macinfo section. <a href="#a50b132d74962e2aec9ebd9087209f23d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9495f66fa67ac05c526e2c3ab6f99b31">emitDebugMacinfoDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit macros into a debug macinfo.dwo section. <a href="#a9495f66fa67ac05c526e2c3ab6f99b31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac14b0270bd04b91f0cc2de450d701dfe">emitDebugMacinfoImpl</a> (MCSection *Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a349fff9263cc6f5c65af5d72920fb488">emitMacro</a> (DIMacro &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35c7729ffbf9826835858e12627b377d">emitMacroFile</a> (DIMacroFile &amp;F, DwarfCompileUnit &amp;U)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6859f6c576af9fea71e7d74ed16a2252">emitMacroFileImpl</a> (DIMacroFile &amp;F, DwarfCompileUnit &amp;U, unsigned StartFile, unsigned EndFile, StringRef(*MacroFormToString)(unsigned Form))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c11b20a9e91bc1876436e759ccc3a5">handleMacroNodes</a> (DIMacroNodeArray Nodes, DwarfCompileUnit &amp;U)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66e759a9643c0126a9743873c2da77f8">initSkeletonUnit</a> (const DwarfUnit &amp;U, DIE &amp;Die, std::unique_ptr&lt; DwarfCompileUnit &gt; NewU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DWARF 5 Experimental Split Dwarf Emitters. <a href="#a66e759a9643c0126a9743873c2da77f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11e63b2669496597b49776bd43f8cd1a">constructSkeletonCU</a> (const DwarfCompileUnit &amp;CU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the split debug info compile unit for the debug info section. <a href="#a11e63b2669496597b49776bd43f8cd1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa6d09046c99728772f75a756b482461">emitDebugInfoDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug info dwo section. <a href="#aaa6d09046c99728772f75a756b482461">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e7d359ba0a473e548ef36850c362a92">emitDebugAbbrevDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug abbrev dwo section. <a href="#a6e7d359ba0a473e548ef36850c362a92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee7718a0a7de787cb74a433db5aa02e">emitDebugLineDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug line dwo section. <a href="#aaee7718a0a7de787cb74a433db5aa02e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2c5aead48d7a3d30265ab9222ba0df7">emitStringOffsetsTableHeaderDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the dwo stringoffsets table header. <a href="#ac2c5aead48d7a3d30265ab9222ba0df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a664d15cb0e7f12f055b566b892dec891">emitDebugStrDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the debug str dwo section. <a href="#a664d15cb0e7f12f055b566b892dec891">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a199120090d949c0f7d55dbb14df0b618">emitDebugAddr</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit DWO addresses. <a href="#a199120090d949c0f7d55dbb14df0b618">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd003f1f72bd6bcf577a2eee9ff37af">addGnuPubAttributes</a> (DwarfCompileUnit &amp;U, DIE &amp;D) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags to let the linker know we have emitted new style pubnames. <a href="#a2cd003f1f72bd6bcf577a2eee9ff37af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a0abfa2e3ed4c261513379e04bde84">getOrCreateDwarfCompileUnit</a> (const DICompileUnit *DIUnit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create new <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> for the given metadata node with tag DW_TAG_compile_unit. <a href="#a87a0abfa2e3ed4c261513379e04bde84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53644e89934d54d6c7c1774760f87790">finishUnitAttributes</a> (const DICompileUnit *DIUnit, DwarfCompileUnit &amp;NewCU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb786901de44bbb2c3c308b4356d9eb">recordSourceLine</a> (unsigned Line, unsigned Col, const MDNode *Scope, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a source line with debug info. <a href="#abdb786901de44bbb2c3c308b4356d9eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abefe636ceb049d6b02263735de861d32">collectEntityInfo</a> (DwarfCompileUnit &amp;TheCU, const DISubprogram *SP, DenseSet&lt; InlinedEntity &gt; &amp;ProcessedVars)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> entries with variables' info. <a href="#abefe636ceb049d6b02263735de861d32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5da7a3b9a8b224312fbad048eb0d905">buildLocationList</a> (SmallVectorImpl&lt; DebugLocEntry &gt; &amp;DebugLoc, const DbgValueHistoryMap::Entries &amp;Entries)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the location list for all DBG_VALUEs in the function that describe the same variable. <a href="#ab5da7a3b9a8b224312fbad048eb0d905">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8801d8baf1a12047392159d26e6428ff">collectVariableInfoFromMFTable</a> (DwarfCompileUnit &amp;TheCU, DenseSet&lt; InlinedEntity &gt; &amp;P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect variable information from the side table maintained by MF. <a href="#a8801d8baf1a12047392159d26e6428ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937274a98c024eb43a569b89b7de25ab">emitSectionReference</a> (const DwarfCompileUnit &amp;CU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the reference to the section. <a href="#a937274a98c024eb43a569b89b7de25ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a078a9376524eef530002e250fa15bbdc">findForceIsStmtInstrs</a> (const MachineFunction *MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the function <span class="doxyComputerOutput">MF</span>, finds the set of instructions which may represent a change in line number from one or more of the preceding MBBs. <a href="#a078a9376524eef530002e250fa15bbdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51f">AccelTableKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b05c497a012a2087c0fc05cdb2e2da">TheAccelTableKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DWARF5 Experimental Options. <a href="#a79b05c497a012a2087c0fc05cdb2e2da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83b0ac199fd7ce9e644e3a8aec0380b">HasAppleExtensionAttributes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5731544252c847bf684b414e7ddc8137">HasSplitDwarf</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38cf250fe78d76053765355b07257ba">UseSegmentedStringOffsetsTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to generate the DWARF v5 string offsets table. <a href="#ac38cf250fe78d76053765355b07257ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab358b7ac5f8f1d053139c7613c9199f6">EmitDebugEntryValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable production of call site parameters needed to print the debug entry values. <a href="#ab358b7ac5f8f1d053139c7613c9199f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarffile">DwarfFile</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449e18a480a13dc6a23044284e4aa64a">SkeletonHolder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Separated Dwarf Variables In general these will all be for bits that are left in the original object file, rather than things that are meant to be in the .dwo sections. <a href="#a449e18a480a13dc6a23044284e4aa64a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdwarfdwolinetable">MCDwarfDwoLineTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d730840e0c9b3539878f32feb02a83b">SplitTypeUnitFileTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Store file names for type units under fission in a line table header that will be emitted into debug_line.dwo. <a href="#a0d730840e0c9b3539878f32feb02a83b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c7b5f890b3be1add7eb86e87b093647">DIEValueAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All DIEValues are allocated through this allocator. <a href="#a3c7b5f890b3be1add7eb86e87b093647">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca56b478dc5d874a3d4efc10ae7b517">CUMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> with its corresponding <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a>. <a href="#abca56b478dc5d874a3d4efc10ae7b517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcdcfc17d1f545a5168149da810508dc">CUDieMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a <a href="/web-llvm/docs/api/namespaces/cu">CU</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with its corresponding <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a>. <a href="#adcdcfc17d1f545a5168149da810508dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/symbolcu">SymbolCU</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebbfca5f6653345fb49693dfa3a2fb27">ArangeLabels</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of all labels used in aranges generation. <a href="#aebbfca5f6653345fb49693dfa3a2fb27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec499b4dafc5a631b0029d267a4b329">SymSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of each symbol emitted (for those symbols that have a specific size). <a href="#a1ec499b4dafc5a631b0029d267a4b329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgentity">DbgEntity</a> &gt;, 64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5987dc252786a8a7e31fddc13d18251">ConcreteEntities</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of abstract variables/labels. <a href="#ab5987dc252786a8a7e31fddc13d18251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debuglocstream">DebugLocStream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2810e3e4c18d6b95a84ca51c36906b2c">DebugLocs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of <a href="/web-llvm/docs/api/classes/llvm/debuglocentry">DebugLocEntry</a>. <a href="#a2810e3e4c18d6b95a84ca51c36906b2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8afc211969408c80ac4e2856280603a1">ProcessedSPNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a collection of subprogram MDNodes that are processed to create DIEs. <a href="#a8afc211969408c80ac4e2856280603a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/setvector">MDNodeSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0cab1042e62317188a2bdd091bcea04">LocalDeclsPerLS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a169ca09ee6350ab958cad9f8fc71e8df">ForceIsStmtInstrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1581f52d7e1fa50de9c9836788d4d60a">CurFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If nonnull, stores the current machine function we're processing. <a href="#a1581f52d7e1fa50de9c9836788d4d60a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084021d79d3dec37a3ef7bc57136658d">PrevCU</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If nonnull, stores the <a href="/web-llvm/docs/api/namespaces/cu">CU</a> in which the previous subprogram was contained. <a href="#a084021d79d3dec37a3ef7bc57136658d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fd51b890e8358d5a4a71d7c7fae6ec3">CompilationDir</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>As an optimization, there is no need to emit an entry in the directory table for the same directory as DW_AT_comp_dir. <a href="#a4fd51b890e8358d5a4a71d7c7fae6ec3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarffile">DwarfFile</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad266ebd3206242a7b2d82fe8705ca64f">InfoHolder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holder for the file specific debug information. <a href="#ad266ebd3206242a7b2d82fe8705ca64f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb88fa5d6f6900fce0ae40852f9798e">TypeSignatures</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holders for the various debug information flags that we might need to have exposed. <a href="#a7fb88fa5d6f6900fce0ae40852f9798e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ec2952a3f36af596031541a2cdffd1">SectionLabels</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DwarfTypeUnit</a> &gt;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * &gt;, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a989215730a5171852dfc50bbf0bf23b9">TypeUnitsUnderConstruction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c79dc66ba7a4d70ecca6752936167a7">FunctionLineTableLabel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbol pointing to the current function's DWARF line table entries. <a href="#a8c79dc66ba7a4d70ecca6752936167a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a250907aeb5bd936490df1c8d3bd16427">NumTypeUnitsCreated</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to set a uniqe <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for a <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit. <a href="#a250907aeb5bd936490df1c8d3bd16427">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4438f98379b5e2439f38cd4b800c8a8">UseGNUTLSOpcode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to use the GNU TLS opcode (instead of the standard opcode). <a href="#ab4438f98379b5e2439f38cd4b800c8a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafde27433a1a5cd24e70d9efc5a78bfc">UseDWARF2Bitfields</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to use DWARF 2 bitfields (instead of the DWARF 4 format). <a href="#aafde27433a1a5cd24e70d9efc5a78bfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17f25a9694a664118c1bde1bc684832">UseAllLinkageNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to emit all linkage names, or just abstract subprograms. <a href="#af17f25a9694a664118c1bde1bc684832">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d7514d60e64bd0b2c7804ec2af8109">UseInlineStrings</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> inlined strings. <a href="#a03d7514d60e64bd0b2c7804ec2af8109">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4c2af65fbcf43c19382781ac028b06">UseRangesSection</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow emission of .debug_ranges section. <a href="#ada4c2af65fbcf43c19382781ac028b06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806cc89f121f18eda3a2807d9a5f2bf8">UseSectionsAsReferences</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the sections itself must be used as references and don't create temp symbols inside DWARF sections. <a href="#a806cc89f121f18eda3a2807d9a5f2bf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1cc5f57add2c38507a2ef540165869e">UseARangesSection</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow emission of .debug_aranges section. <a href="#af1cc5f57add2c38507a2ef540165869e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b2b325925de020f1799c367c057232">GenerateTypeUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate DWARF v4 type units. <a href="#a58b2b325925de020f1799c367c057232">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46854f5f0a6b931c1756f3e17c0607a8">UseDebugMacroSection</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a .debug_macro section instead of .debug_macinfo. <a href="#a46854f5f0a6b931c1756f3e17c0607a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b825626bcfe499bb099ae1207b1b2a8">EnableOpConvert</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Avoid using DW_OP_convert due to consumer incompatibilities. <a href="#a1b825626bcfe499bb099ae1207b1b2a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a535beef0b6ae2e8972ee23458cd7b629">MinimizeAddrInV5</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae21b8bcaad4933ff846c985f265dc420">MinimizeAddr</a> = <a href="#a535beef0b6ae2e8972ee23458cd7b629ab9f5c797ebbf55adccdd8539a65a0241">MinimizeAddrInV5::Disabled</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Force the use of DW_AT_ranges even for single-entry range lists. <a href="#ae21b8bcaad4933ff846c985f265dc420">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581ada33f72d8fd09a03b9efc2eebdcf">SingleCU</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff there are multiple CUs in this module. <a href="#a581ada33f72d8fd09a03b9efc2eebdcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a660db8e7332ecbb1c0e5167236807bf9">IsDarwin</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4fc37763d7146fc9af189cc6a623be">StringTypeLocMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map for tracking Fortran deferred CHARACTER lengths. <a href="#a6f4fc37763d7146fc9af189cc6a623be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/addresspool">AddressPool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad551c9d7f14cc242b5d6d57581ac53a4">AddrPool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93db82d5ab95c066058baba4549659f0">AccelDebugNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator tables. <a href="#a93db82d5ab95c066058baba4549659f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55921afed50b607dc83c5a22662be83d">AccelTypeUnitsDebugNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73e3c137b3914b434452f51e504b930">CurrentDebugNames</a> = &amp;AccelDebugNames</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to hide which <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> we are using now. <a href="#aa73e3c137b3914b434452f51e504b930">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata">AppleAccelTableOffsetData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade72bebeec25baca23ed1d3800b03215">AccelNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata">AppleAccelTableOffsetData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26224edf3aee61983644f9a25f8b77ed">AccelObjC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata">AppleAccelTableOffsetData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a68a302b52565aa49d1d110842cd8e">AccelNamespace</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltabletypedata">AppleAccelTableTypeData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b27336dfbc0b951aa844cad0e39783">AccelTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6">DebuggerKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54129029a64182f5396367db5ee913d9">DebuggerTuning</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a7a1920d61156abc05a60135aefe8bc67">DebuggerKind::Default</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify a debugger for "tuning" the debug info. <a href="#a54129029a64182f5396367db5ee913d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd65b6c842827550ed102e2d82b90fa">makeTypeSignature</a> (StringRef Identifier)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform an <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> checksum of <span class="doxyComputerOutput">Identifier</span> and return the lower 64 bits. <a href="#affd65b6c842827550ed102e2d82b90fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa441f906c99d29f50a64369799d8f737">emitDebugLocValue</a> (const AsmPrinter &amp;AP, const DIBasicType *BT, const DbgValueLoc &amp;Value, DwarfExpression &amp;DwarfExpr)</td>
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

<p>Collects and handles dwarf debug information.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### InlinedEntity {#a0aa596b67ba2e12b61bca47c497faf88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DwarfDebug::InlinedEntity =  DbgValueHistoryMap::InlinedEntity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### MDNodeSet {#aa35e9688e484e2bc6b8b28f29577e836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DwarfDebug::MDNodeSet =  SetVector&lt;const MDNode *, SmallVector&lt;const MDNode *, 2&gt;,
                              SmallPtrSet&lt;const MDNode *, 2&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map function-local imported entities to their parent local scope (either <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a> or <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a>) for a processed function (including inlined subprograms).</p>

<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DWARF5AccelTableKind {#a16869ddb4e88c84883d14a2f2756f574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DwarfDebug::DWARF5AccelTableKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">CU<a id="a16869ddb4e88c84883d14a2f2756f574ac83f077534a373cb63a0a91969fdce54"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TU<a id="a16869ddb4e88c84883d14a2f2756f574aca3361ad64c4cfc6cf56de774c7a903c"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### MinimizeAddrInV5 {#a535beef0b6ae2e8972ee23458cd7b629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DwarfDebug::MinimizeAddrInV5 </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Default<a id="a535beef0b6ae2e8972ee23458cd7b629a7a1920d61156abc05a60135aefe8bc67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Disabled<a id="a535beef0b6ae2e8972ee23458cd7b629ab9f5c797ebbf55adccdd8539a65a0241"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ranges<a id="a535beef0b6ae2e8972ee23458cd7b629a92711ef5b0215a076fef4a3abbfc2258"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Expressions<a id="a535beef0b6ae2e8972ee23458cd7b629ad3c7279c25a23f98e777a7bebe35d002"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Form<a id="a535beef0b6ae2e8972ee23458cd7b629ad359c6df99b25183d81f7d728b71de0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DwarfDebug() {#aef3ee50c530039dd44c410b678a54ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfDebug::DwarfDebug (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a3e54c1066c04500fd0af373629ba8836a94950d486a1e79b2cd8c2a2ff65abad7">AllLinkageNames</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#ab0cf9c667fac80b129426688faab9fa0">computeAccelTableKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a5fbfc9a3585a158500a5f9a274c7403a">llvm::DBX</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a966cbffb61d32a19d00616f851a5eb6e">llvm::DebugHandlerBase::DebugHandlerBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="#a535beef0b6ae2e8972ee23458cd7b629a7a1920d61156abc05a60135aefe8bc67">Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a3e54c1066c04500fd0af373629ba8836a3c914ea6f17fa3943a27cf24c14043ff">DefaultLinkageNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a38b0a647f0c66aab00e83aa2a7dab431">llvm::dwarf::DWARF_VERSION</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a169962e34ef6fb9b13f0f8df8df3d182">DwarfInlinedStrings</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a25d1a0bf5394df5cd2fa3f1e80b02a19">DwarfLinkageNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a4efc5df5d826c7f5b50734466fd555d8">DwarfOpConvert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a9c2c8281c0f1b5d8d5243444f6ac3470">DwarfSectionsAsReferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6abbc0db17ceadc889cc561add9763afc5">llvm::GDB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a1a3cdc6ab7ebefd74bf333be98e35dce">GenerateARangeSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a2a1837e04ee7b0480e6e578824a47801">GenerateDwarfTypeUnits</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6ac45aa7e8859a50c36c0daa43d65d9fa1">llvm::LLDB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#afd9bd69f105f9c3804beca40d277c43f">MinimizeAddrInV5Option</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a3a4faa309dc268374a2b3ea981c47c7b">llvm::DebugHandlerBase::MMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a0d71cb3b4b55f18ed1efc9dbc986858c">NoDwarfRangesSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a4f1fcf80c07532facc35db354783b0b2">llvm::SCE</a>, <a href="/web-llvm/docs/api/groups/debuggertuning/#ga42e75cae125454aea72ff1c76dabd5b3">tuneForDBX</a>, <a href="/web-llvm/docs/api/groups/debuggertuning/#ga7967d9d5ff2b6b0344d919d2d27965cb">tuneForGDB</a>, <a href="/web-llvm/docs/api/groups/debuggertuning/#ga98337eccc708fb48a33a9755764014ab">tuneForLLDB</a>, <a href="/web-llvm/docs/api/groups/debuggertuning/#ga12d17eb7e0ee4182377397d9fb39459d">tuneForSCE</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a12dae658f43e5d9e58d4629af2bd63eb">UseGNUDebugMacro</a> and <a href="#aa578b94a4e307580b4feed7ede93e3af">useSplitDwarf</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DwarfDebug() {#a8ef1988409d5331ca6f9a09e10b36ec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfDebug::~DwarfDebug ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAccelName() {#ac81660b2aac6a21b5b3c18eb6ace603e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::addAccelName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01">DICompileUnit::DebugNameTableKind</a> NameTableKind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 872 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3865 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="#a3f60785d1dd3859ae53f738c01d366a7">addSubprogramNames</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3554b83e3e334e00da341d9aba81a47e">llvm::DwarfCompileUnit::finishEntityDefinition</a>.</p>

</div>
</div>

### addAccelNamespace() {#a3e8976df7c8f2c1513d641a5d46e5cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::addAccelNamespace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01">DICompileUnit::DebugNameTableKind</a> NameTableKind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 880 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3881 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### addAccelObjC() {#a450a3a1f0d314a6155817f3854957da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::addAccelObjC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01">DICompileUnit::DebugNameTableKind</a> NameTableKind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3872 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fa9f6290f4436e5a2351f12e03b6433c3c">llvm::Apple</a> and <a href="#afd711d7e6dd61972100f0338c3e3b910">getAccelTableKind</a>.</p>


<p>Referenced by <a href="#a3f60785d1dd3859ae53f738c01d366a7">addSubprogramNames</a>.</p>

</div>
</div>

### addAccelType() {#ae2cb1c03cabf7e346aec758eff539405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::addAccelType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01">DICompileUnit::DebugNameTableKind</a> NameTableKind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, char Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 884 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3888 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### addArangeLabel() {#a5e772cb1e4a87f6e2ec29356d60ab89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfDebug::addArangeLabel (<a href="/web-llvm/docs/api/structs/llvm/symbolcu">SymbolCU</a> SCU)</td>
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

<p>Add a label so that arange data can be generated for it.</p>

<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Referenced by <a href="#a8f0353f65281b2b560d4421d439ed836">endFunctionImpl</a>.</p>

</div>
</div>

### addDwarfTypeUnitType() {#ad06f166cd8884265b3a1ea2849f0c026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::addDwarfTypeUnitType (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Identifier, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * CTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to the set of types that we're going to pull into type units.</p>

<p>Declaration at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3707 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a40aa1e13b1e51c58c3463a519990fd51">llvm::DwarfUnit::addString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c1d3ec37aec1008ed52018d257a2608">llvm::DwarfUnit::addStringOffsetsStart</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3d00f6235eca359e429053abedd6cfa5">llvm::DwarfUnit::addUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a64cca2d21cc17e087bd22d4cc648b4a5">llvm::DwarfUnit::createTypeDIE</a>, <a href="#a16869ddb4e88c84883d14a2f2756f574ac83f077534a373cb63a0a91969fdce54">CU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fabc5183644c3cfe8d28e144b1518446d9">llvm::Dwarf</a>, <a href="#afd711d7e6dd61972100f0338c3e3b910">getAccelTableKind</a>, <a href="#a3ace4bbb6f50507e82b0fbec1ee7ea74">getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#af38242c719f0cacb09b91e354bd3145e">llvm::DIType::getScope</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#abf2a1b885dfb5c0adb161aa1f0bc5d50">llvm::DIEUnit::getUnitDie</a>, <a href="#affd65b6c842827550ed102e2d82b90fa">makeTypeSignature</a>, <a href="#a3edd84f3526327ef72c9c5300eb07865">setCurrentDWARF5AccelTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dieunit/#a012f5b123fd34a3a0818e949d33280e8">llvm::DIEUnit::setSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#af9da75d885b939ff54b482ea296d8ad4">llvm::DwarfTypeUnit::setType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#af721bccc4eb36071c3f0ea05bc8dab99">llvm::DwarfTypeUnit::setTypeSignature</a>, <a href="#a16869ddb4e88c84883d14a2f2756f574aca3361ad64c4cfc6cf56de774c7a903c">TU</a>, <a href="#a12fca111b048ad8daf6cc55fc02aab19">useSegmentedStringOffsetsTable</a> and <a href="#aa578b94a4e307580b4feed7ede93e3af">useSplitDwarf</a>.</p>

</div>
</div>

### addStringTypeLoc() {#a92ff7e038b33d8e36bf36122af99d59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfDebug::addStringTypeLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> * ST, unsigned Loc)</td>
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



<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### addSubprogramNames() {#a3f60785d1dd3859ae53f738c01d366a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::addSubprogramNames (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01">DICompileUnit::DebugNameTableKind</a> NameTableKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="#ac81660b2aac6a21b5b3c18eb6ace603e">addAccelName</a>, <a href="#a450a3a1f0d314a6155817f3854957da8">addAccelObjC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fa9f6290f4436e5a2351f12e03b6433c3c">llvm::Apple</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01a9f6290f4436e5a2351f12e03b6433c3c">llvm::DICompileUnit::Apple</a>, <a href="#afd711d7e6dd61972100f0338c3e3b910">getAccelTableKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#affb04f368f98abaa344a09796faf75b1">getObjCClassCategory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#afdfcd6bc2b365e5524d5b8cea4966c3d">getObjCMethodName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a01598e7ae0603f525013f0d98f52e8b5">isObjCClass</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01a6adf97f83acf6453d4a6a4b1070f3754">llvm::DICompileUnit::None</a> and <a href="#a417b1e5a8cac92f3d915173aa72a9869">useAllLinkageNames</a>.</p>

</div>
</div>

### alwaysUseRanges() {#a3f0b6e92cb91f8dbdc38083845e2462f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfDebug::alwaysUseRanges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether range encodings should be used for single entry range lists.</p>

<p>Declaration at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3936 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="#a535beef0b6ae2e8972ee23458cd7b629a7a1920d61156abc05a60135aefe8bc67">Default</a>, <a href="#a535beef0b6ae2e8972ee23458cd7b629a92711ef5b0215a076fef4a3abbfc2258">Ranges</a> and <a href="#aa578b94a4e307580b4feed7ede93e3af">useSplitDwarf</a>.</p>

</div>
</div>

### beginCodeAlignment() {#ae7819cf4c91db139508a49f5e0401243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::beginCodeAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> beginning of code alignment.</p>

<p>Declaration at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3946 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66dadb74da0a389a2704e8e01c66ace2913e">llvm::DICompileUnit::NoDebug</a>.</p>

</div>
</div>

### beginInstruction() {#a6ae5e1ec2093c40fa0e3211bd043057b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::beginInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> beginning of an instruction.</p>

<p>Declaration at line 737 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2000 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">llvm::MachineInstr::AnyInBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a99b73ffc5808cd622aa76eeb07fc3e87">llvm::DebugHandlerBase::beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a03bc61adaddbb1e6c2a2d7cabcb555d3">llvm::DebugHandlerBase::CurMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2abcfaccebf745acfd5e75351095a5394a">llvm::Disable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#aefa88a895bd349d0750ded8be4a29dda">DWARF2_FLAG_EPILOGUE_BEGIN</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#a377ba69923635f8154cad5784be89ff6">DWARF2_FLAG_IS_STMT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#ac0c23e2e79a5713602b44382a3ecc960">DWARF2_FLAG_PROLOGUE_END</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#ae9447598df768a1aba7a9006b0458e0c">llvm::DebugHandlerBase::EpilogBeginBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">llvm::MachineInstr::FrameDestroy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66dadb74da0a389a2704e8e01c66ace2913e">llvm::DICompileUnit::NoDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#aa57448b6774e5d6264452732dc188388">llvm::DebugHandlerBase::PrevInstBB</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a68492cf3d8769e02ee84f61e8c4e9328">llvm::DebugHandlerBase::PrevInstLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a58506448d8b951c82476a20b39b947af">llvm::DebugHandlerBase::PrevLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#af5173816befd317718323259ef8579cd">llvm::DebugHandlerBase::PrologEndLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#aaffb6bc659419af61a639d756f210137">llvm::DebugHandlerBase::requestLabelAfterInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#ad2b833d5bf85c69d922a140d1a917314">llvm::DebugHandlerBase::requestLabelBeforeInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#adb76e7c781cf7bf8ed347c7b95133b4f">UnknownLocations</a>.</p>

</div>
</div>

### beginModule() {#a3f59a82f48553634ac4625cb8166071e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::beginModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all Dwarf sections that should come prior to the content.</p>

<p>Declaration at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#ac1299778170e0f0cd04e48329df7d7f7">llvm::DebugHandlerBase::beginModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a3ace4bbb6f50507e82b0fbec1ee7ea74">getDwarfVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bfa4cc6684df7b4a92b1dec6fce3264fac8">llvm::Global</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a590dd1a0073f9187bf45366c69ba7c12">llvm::DwarfFile::setRnglistsTableBaseSym</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a38e68958dd4cc9e1c90b0abc432f5b09">sortGlobalExprs</a>, <a href="#a12fca111b048ad8daf6cc55fc02aab19">useSegmentedStringOffsetsTable</a> and <a href="#aa578b94a4e307580b4feed7ede93e3af">useSplitDwarf</a>.</p>

</div>
</div>

### emitDebugEntryValues() {#a3608f879e120c9344fd7cdb2f0dddb0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::emitDebugEntryValues ()</td>
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



<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### emitDebugLocEntry() {#a3d1945df4a676ee30059653cc05be15a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugLocEntry (<a href="/web-llvm/docs/api/classes/llvm/bytestreamer">ByteStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/debuglocstream/entry">DebugLocStream::Entry</a> &amp; Entry, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> * CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an entry for the debug loc section.</p>


<p>This can be used to handle an entry that's going to be emitted into the debug loc section.</p>


<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2852 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/bytestreamer/#a75cdbc07f36ab67dae3b3a51d0e25d07">llvm::ByteStreamer::emitDIERef</a>, <a href="/web-llvm/docs/api/classes/llvm/bytestreamer/#a5fce4472fcb321a0e4534cf656399b39">llvm::ByteStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a990840b65d04e11c55ea3c2eff5ad47c">emitDebugLocEntryLocation</a>.</p>

</div>
</div>

### emitDebugLocEntryLocation() {#a990840b65d04e11c55ea3c2eff5ad47c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugLocEntryLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/debuglocstream/entry">DebugLocStream::Entry</a> &amp; Entry, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> * CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the location for a debug loc entry, including the size header.</p>

<p>Declaration at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3021 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="#a3d1945df4a676ee30059653cc05be15a">emitDebugLocEntry</a> and <a href="#a3ace4bbb6f50507e82b0fbec1ee7ea74">getDwarfVersion</a>.</p>

</div>
</div>

### emitInitialLocDirective() {#ab0627dac3e2666638fa514a2d98299ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * DwarfDebug::emitInitialLocDirective (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned CUID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits inital debug location directive.</p>


<p>Returns instruction at which the function prologue ends.</p>


<p>Declaration at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2293 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#a377ba69923635f8154cad5784be89ff6">DWARF2_FLAG_IS_STMT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a541bb79da42e4b8f77617678e7f47d83">findPrologueEndLoc</a>, <a href="#a3ace4bbb6f50507e82b0fbec1ee7ea74">getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#af5173816befd317718323259ef8579cd">llvm::DebugHandlerBase::PrologEndLoc</a>.</p>


<p>Referenced by <a href="#af89d6d0bd3c47fc34cb897ea7131f9ac">beginFunctionImpl</a>.</p>

</div>
</div>

### endModule() {#adb62e2b6d18233c7069ea46cf3855b61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::endModule ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all Dwarf sections that should come after the content.</p>

<p>Declaration at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fa9f6290f4436e5a2351f12e03b6433c3c">llvm::Apple</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a03bc61adaddbb1e6c2a2d7cabcb555d3">llvm::DebugHandlerBase::CurMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fabc5183644c3cfe8d28e144b1518446d9">llvm::Dwarf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#afd711d7e6dd61972100f0338c3e3b910">getAccelTableKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fa6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a8e76c771af1d9f50bb133eb3aeadb087">terminateLineTable</a> and <a href="#aa578b94a4e307580b4feed7ede93e3af">useSplitDwarf</a>.</p>

</div>
</div>

### generateTypeUnits() {#a65337903876e29f1321b84f208590446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::generateTypeUnits ()</td>
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

<p>Returns whether to generate DWARF v4 type units.</p>

<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### getAccelTableKind() {#afd711d7e6dd61972100f0338c3e3b910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTableKind llvm::DwarfDebug::getAccelTableKind ()</td>
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

<p>Returns what kind (if any) of accelerator tables to emit.</p>

<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Referenced by <a href="#a450a3a1f0d314a6155817f3854957da8">addAccelObjC</a>, <a href="#ad06f166cd8884265b3a1ea2849f0c026">addDwarfTypeUnitType</a>, <a href="#a3f60785d1dd3859ae53f738c01d366a7">addSubprogramNames</a> and <a href="#adb62e2b6d18233c7069ea46cf3855b61">endModule</a>.</p>

</div>
</div>

### getAddressPool() {#a6c58cede6903d5a3190eef36f0e1732e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressPool &amp; llvm::DwarfDebug::getAddressPool ()</td>
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



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#afe65683534ca819c702e4eb5f158f387">emitRangeList</a>.</p>

</div>
</div>

### getCurrentDWARF5AccelTable() {#a71ca9a74fb66831c613c1a0fa1d7b5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARF5AccelTable &amp; llvm::DwarfDebug::getCurrentDWARF5AccelTable ()</td>
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

<p>Returns either <a href="/web-llvm/docs/api/namespaces/cu">CU</a> or TU <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a>.</p>

<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### getCurrentFunction() {#a53991b8335c42c8720bd5ed5af77371e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction * llvm::DwarfDebug::getCurrentFunction ()</td>
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



<p>Definition at line 888 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### getDebugLocs() {#a7d7651181b9b8aaee16273701c1b3e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLocStream &amp; llvm::DwarfDebug::getDebugLocs ()</td>
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

<p>Returns the entries for the .debug_loc section.</p>

<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a8e27b745d3930b5f8bbcf30b919f42ce">emitLocList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#ac157948fef752ac31b048eb0de2cd6d2">emitLoclistsTableHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/dieloclist/#ab79493e879f7c7f008969fbcb802d6f6">llvm::DIELocList::emitValue</a>.</p>

</div>
</div>

### getDwarfSectionOffsetForm() {#a46b0fb1505ef705cdf28d6b2612c5579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Form DwarfDebug::getDwarfSectionOffsetForm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a suitable DWARF form to represent a section offset, i.e.</p>


<ul class="doxyList ">
<li>DW_FORM_sec_offset for DWARF version &gt;= 4;</li>
<li>DW_FORM_data8 for 64-bit DWARFv3;</li>
<li>DW_FORM_data4 for 32-bit DWARFv3 and DWARFv2.</li>
</ul>

<p>Declaration at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3899 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getDwarfVersion() {#a3ace4bbb6f50507e82b0fbec1ee7ea74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t DwarfDebug::getDwarfVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the Dwarf Version.</p>

<p>Declaration at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3895 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>.</p>


<p>Referenced by <a href="#ad06f166cd8884265b3a1ea2849f0c026">addDwarfTypeUnitType</a>, <a href="#a3f59a82f48553634ac4625cb8166071e">beginModule</a>, <a href="#a990840b65d04e11c55ea3c2eff5ad47c">emitDebugLocEntryLocation</a>, <a href="#ab0627dac3e2666638fa514a2d98299ef">emitInitialLocDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a35938fd3189af5f6ef0e2d893b9fd60d">emitRangeList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#afe65683534ca819c702e4eb5f158f387">emitRangeList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#ad1a794474d8b6577eeeac7c922590641">GetCompileUnitType</a>, <a href="#a1ee028fdde7a97c3cb31217670eff28f">getMD5AsBytes</a> and <a href="#a41f368207329f5957e26e92ca87ebdbf">insertSectionLabel</a>.</p>

</div>
</div>

### getLocalDeclsForScope() {#a18bb61a9ecdbe2308a41c82c73c4b23c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNodeSet &amp; llvm::DwarfDebug::getLocalDeclsForScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> * S)</td>
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



<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### getMD5AsBytes() {#a1ee028fdde7a97c3cb31217670eff28f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MD5::MD5Result &gt; DwarfDebug::getMD5AsBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the <span class="doxyComputerOutput">File</span> has an <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> checksum, return it as an MD5Result allocated in the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a>.</p>

<p>Declaration at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3919 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/difile/#a9da65c9c7c45937ab7da70348f7fb75aacdbc9e47dd59830cf2507147e7b732b6">llvm::DIFile::CSK_MD5</a> and <a href="#a3ace4bbb6f50507e82b0fbec1ee7ea74">getDwarfVersion</a>.</p>

</div>
</div>

### getPrevCU() {#a299df286f8b78890bc5dc0ffe53ea751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DwarfCompileUnit * llvm::DwarfDebug::getPrevCU ()</td>
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

<p>Returns the previous <a href="/web-llvm/docs/api/namespaces/cu">CU</a> that was being updated.</p>

<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### getSectionLabel() {#aa185d37e50840c4efe89db1f96a44540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol * DwarfDebug::getSectionLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 920 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3908 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#afe65683534ca819c702e4eb5f158f387">emitRangeList</a>.</p>

</div>
</div>

### getStringTypeLoc() {#ac946573bbb92083695b8e056178878cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfDebug::getStringTypeLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> * ST)</td>
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



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### insertSectionLabel() {#a41f368207329f5957e26e92ca87ebdbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::insertSectionLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3912 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="#a3ace4bbb6f50507e82b0fbec1ee7ea74">getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aab8c6e58e0fb2534a0b6289f30b1d25d">llvm::MCSymbol::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a> and <a href="#aa578b94a4e307580b4feed7ede93e3af">useSplitDwarf</a>.</p>

</div>
</div>

### isLexicalScopeDIENull() {#acb34ac66067af067228eaaab8df6e982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfDebug::isLexicalScopeDIENull (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function to check whether the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for a given Scope is going to be null.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether we should create a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given Scope, return true if we don't create a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> (the corresponding <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is null).</p>


<p>Declaration at line 892 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a89f0a308af7db83a48443c4512bd3268">llvm::DebugHandlerBase::getLabelAfterInsn</a> and <a href="#a535beef0b6ae2e8972ee23458cd7b629a92711ef5b0215a076fef4a3abbfc2258">Ranges</a>.</p>

</div>
</div>

### lookupCU() {#a9b235aebc8b1bd478885e18120f2e50e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCompileUnit * llvm::DwarfDebug::lookupCU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die)</td>
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

<p>Find the matching <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> for the given <a href="/web-llvm/docs/api/namespaces/cu">CU</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### lookupCU() {#a391c85ac8c1a5f6da2fc65c3a827213e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DwarfCompileUnit * llvm::DwarfDebug::lookupCU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die)</td>
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



<p>Definition at line 896 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### setCurrentDWARF5AccelTable() {#a3edd84f3526327ef72c9c5300eb07865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfDebug::setCurrentDWARF5AccelTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a16869ddb4e88c84883d14a2f2756f574">DWARF5AccelTableKind</a> Kind)</td>
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

<p>Sets the current <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> to use.</p>

<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>References <a href="#a16869ddb4e88c84883d14a2f2756f574ac83f077534a373cb63a0a91969fdce54">CU</a> and <a href="#a16869ddb4e88c84883d14a2f2756f574aca3361ad64c4cfc6cf56de774c7a903c">TU</a>.</p>


<p>Referenced by <a href="#ad06f166cd8884265b3a1ea2849f0c026">addDwarfTypeUnitType</a>.</p>

</div>
</div>

### setPrevCU() {#a4ccadedfcbf61f5b551d50299d4818b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfDebug::setPrevCU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> * PrevCU)</td>
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



<p>Definition at line 848 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### setSymbolSize() {#a2d98873019d57cc27c24b3e51ad11894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfDebug::setSymbolSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, uint64_t Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For symbols that have a size designated (e.g.</p>


<p>common symbols), this tracks that size.</p>


<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### setTheAccelTableKind() {#ab1836fd53620de40512b95c5db372af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DwarfDebug::setTheAccelTableKind (<a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51f">AccelTableKind</a> K)</td>
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

<p>Seet TheAccelTableKind.</p>

<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### shareAcrossDWOCUs() {#a84d7b74e02d1e0dc4a555a18ad536f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfDebug::shareAcrossDWOCUs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a7f8c37f7db4defd1901dda2096f2daa3">SplitDwarfCrossCuReferences</a>.</p>

</div>
</div>

### terminateLineTable() {#a8e76c771af1d9f50bb133eb3aeadb087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::terminateLineTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> * CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Terminate the line table by adding the last range label.</p>

<p>Declaration at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a> and <a href="#aaa2a9e9b8cba40b4beaf474f7ffb914d">getDwarfCompileUnitIDForLineTable</a>.</p>


<p>Referenced by <a href="#adb62e2b6d18233c7069ea46cf3855b61">endModule</a> and <a href="#a541a61ef08e721f29862af1393d30ce3">skippedNonDebugFunction</a>.</p>

</div>
</div>

### useAddrOffsetExpressions() {#ac05f1a7c06166d9783b1fc4fbb94eda0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useAddrOffsetExpressions ()</td>
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



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Reference <a href="#a535beef0b6ae2e8972ee23458cd7b629ad3c7279c25a23f98e777a7bebe35d002">Expressions</a>.</p>

</div>
</div>

### useAddrOffsetForm() {#a290ee02ad9767f2b33dd22d83fb3eb46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useAddrOffsetForm ()</td>
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



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Reference <a href="#a535beef0b6ae2e8972ee23458cd7b629ad359c6df99b25183d81f7d728b71de0e">Form</a>.</p>

</div>
</div>

### useAllLinkageNames() {#a417b1e5a8cac92f3d915173aa72a9869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useAllLinkageNames ()</td>
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

<p>Returns whether we should emit all DW_AT_[MIPS_]linkage_name.</p>


<p>If not, we still might emit certain cases.</p>


<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Referenced by <a href="#a3f60785d1dd3859ae53f738c01d366a7">addSubprogramNames</a>.</p>

</div>
</div>

### useAppleExtensionAttributes() {#a4a0cac76b9cd44a8e75eb1f7c44161f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useAppleExtensionAttributes ()</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### useDWARF2Bitfields() {#ab7782075e0f7e6801bd76aadc2f753a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useDWARF2Bitfields ()</td>
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

<p>Returns whether to use the DWARF2 format for bitfields instyead of the DWARF4 format.</p>

<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### useGNUTLSOpcode() {#a2270a27c4f224367aa5e7fd87cef7726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useGNUTLSOpcode ()</td>
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

<p>Returns whether to use DW_OP_GNU_push_tls_address, instead of the standard DW_OP_form_tls_address opcode.</p>

<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### useInlineStrings() {#a5a63e95e94720e08548754358d0a1baa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useInlineStrings ()</td>
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

<p>Returns whether to use inline strings.</p>

<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### useOpConvert() {#a8798358ce24fcff571414ad2b949a3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useOpConvert ()</td>
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



<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### useRangesSection() {#ac339921df038ec6d83250746d09efd77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useRangesSection ()</td>
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

<p>Returns whether ranges section should be emitted.</p>

<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### useSectionsAsReferences() {#a7bf5b76e85c6969ed83ad9330a1ba144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useSectionsAsReferences ()</td>
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

<p>Returns whether to use sections as labels rather than temp symbols.</p>

<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### useSegmentedStringOffsetsTable() {#a12fca111b048ad8daf6cc55fc02aab19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useSegmentedStringOffsetsTable ()</td>
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

<p>Returns whether to generate a string offsets table with (possibly shared) contributions from each <a href="/web-llvm/docs/api/namespaces/cu">CU</a> and type unit.</p>


<p>This implies the use of DW_FORM_strx* indirect references with DWARF v5 and beyond. Note that DW_FORM_GNU_str_index is also an indirect reference, but it is used with a pre-DWARF v5 implementation of split DWARF sections, which uses a monolithic string offsets table.</p>


<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Referenced by <a href="#ad06f166cd8884265b3a1ea2849f0c026">addDwarfTypeUnitType</a> and <a href="#a3f59a82f48553634ac4625cb8166071e">beginModule</a>.</p>

</div>
</div>

### useSplitDwarf() {#aa578b94a4e307580b4feed7ede93e3af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::useSplitDwarf ()</td>
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

<p>Returns whether or not to change the current debug info for the split dwarf proposal support.</p>

<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>


<p>Referenced by <a href="#ad06f166cd8884265b3a1ea2849f0c026">addDwarfTypeUnitType</a>, <a href="#a3f0b6e92cb91f8dbdc38083845e2462f">alwaysUseRanges</a>, <a href="#a3f59a82f48553634ac4625cb8166071e">beginModule</a>, <a href="#aef3ee50c530039dd44c410b678a54ec6">DwarfDebug</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4372f5cbd92647d1f4f90fcdb8a5474">llvm::emitDWARF5AccelTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aec4510f9b5a8aa0a063d61428e052c96">emitMacroHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dieloclist/#ab79493e879f7c7f008969fbcb802d6f6">llvm::DIELocList::emitValue</a>, <a href="#adb62e2b6d18233c7069ea46cf3855b61">endModule</a> and <a href="#a41f368207329f5957e26e92ca87ebdbf">insertSectionLabel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### beginFunctionImpl() {#af89d6d0bd3c47fc34cb897ea7131f9ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::beginFunctionImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gather pre-function debug information.</p>

<p>Declaration at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2469 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab0627dac3e2666638fa514a2d98299ef">emitInitialLocDirective</a>, <a href="#aaa2a9e9b8cba40b4beaf474f7ffb914d">getDwarfCompileUnitIDForLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#aeaa635647755035e74d272e038b44dcc">llvm::DebugHandlerBase::LScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66dadb74da0a389a2704e8e01c66ace2913e">llvm::DICompileUnit::NoDebug</a> and <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#af5173816befd317718323259ef8579cd">llvm::DebugHandlerBase::PrologEndLoc</a>.</p>

</div>
</div>

### endFunctionImpl() {#a8f0353f65281b2b560d4421d439ed836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::endFunctionImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gather and emit post-function debug information.</p>

<p>Declaration at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="#a5e772cb1e4a87f6e2ec29356d60ab89e">addArangeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a39cb0b18cc6f463c1d383db1ee6c6226">llvm::DwarfCompileUnit::addRange</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a8cbe3dd2e5c24c363d750bd49f46838a">llvm::DwarfCompileUnit::constructSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a77347a4881397840dcd27b24ce537976">llvm::DwarfCompileUnit::createAbstractEntity</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abebd15dd4b82e33ca73757397490ea80">llvm::DwarfUnit::getCUNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a100f52daef15eef06fddf617f6933d88">llvm::DICompileUnit::getDebugInfoForProfiling</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#afeaa84c982a7493e02d1b547297e0e69">llvm::DICompileUnit::getEmissionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad9c9bcc6b272753369d8b7d322c879c8">llvm::DwarfCompileUnit::getExistingAbstractEntity</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#ac285fd5fed8c9963ff45f4aa56c2dc41">getRetainedNodeScope</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope/#a55c32cfbb5a9cf63e9a9576666d17796">llvm::LexicalScope::getScopeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9d8fd9011312799cf4f440538b8cb79c">llvm::DwarfCompileUnit::getSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a8580ec112636cac325223ad51b031dd4">llvm::DICompileUnit::getSplitDebugInlining</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a36ac215f97478b9332071e06786aed77">llvm::DICompileUnit::isDebugDirectivesOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66da6b16b60468715f43621c437edef9a3b3">llvm::DICompileUnit::LineTablesOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#aeaa635647755035e74d272e038b44dcc">llvm::DebugHandlerBase::LScopes</a> and <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a58506448d8b951c82476a20b39b947af">llvm::DebugHandlerBase::PrevLabel</a>.</p>

</div>
</div>

### getDwarfCompileUnitIDForLineTable() {#aaa2a9e9b8cba40b4beaf474f7ffb914d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DwarfDebug::getDwarfCompileUnitIDForLineTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU)</td>
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

<p>Get Dwarf compile unit <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for line table.</p>

<p>Declaration at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2493 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>.</p>


<p>Referenced by <a href="#af89d6d0bd3c47fc34cb897ea7131f9ac">beginFunctionImpl</a> and <a href="#a8e76c771af1d9f50bb133eb3aeadb087">terminateLineTable</a>.</p>

</div>
</div>

### skippedNonDebugFunction() {#a541a61ef08e721f29862af1393d30ce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::skippedNonDebugFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2513 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Reference <a href="#a8e76c771af1d9f50bb133eb3aeadb087">terminateLineTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addAccelNameImpl() {#ae7d552ce38bc2faf81c2f9ff6bca7f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DataT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::addAccelNameImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01">DICompileUnit::DebugNameTableKind</a> NameTableKind, <a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; DataT &gt; &amp; AppleAccel, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3822 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### addGnuPubAttributes() {#a2cd003f1f72bd6bcf577a2eee9ff37af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::addGnuPubAttributes (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; U, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags to let the linker know we have emitted new style pubnames.</p>


<p>Only emit it here if we don't have a skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a> for split dwarf.</p>


<p>Declaration at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1002 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### buildLocationList() {#ab5da7a3b9a8b224312fbad048eb0d905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DwarfDebug::buildLocationList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/debuglocentry">DebugLocEntry</a> &gt; &amp; DebugLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a55838c99f2c13e8f8f19debd18034f0f">DbgValueHistoryMap::Entries</a> &amp; Entries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build the location list for all DBG_VALUEs in the function that describe the same variable.</p>


<p>If the resulting list has only one entry that is valid for entire variable's scope return true.</p>


<p>The resulting DebugLocEntries will have strict monotonically increasing begin addresses and will never overlap. If the resulting list has only one entry that is valid throughout variable's scope return true.</p>


<p>Declaration at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1693 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### collectEntityInfo() {#abefe636ceb049d6b02263735de861d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::collectEntityInfo (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; TheCU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; InlinedEntity &gt; &amp; ProcessedVars)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> entries with variables' info.</p>

<p>Declaration at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1877 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### collectVariableInfoFromMFTable() {#a8801d8baf1a12047392159d26e6428ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::collectVariableInfoFromMFTable (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; TheCU, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; InlinedEntity &gt; &amp; P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect variable information from the side table maintained by MF.</p>

<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1531 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### constructAbstractSubprogramScopeDIE() {#a78e35f96e21c4cb9e827cdd4fa63742c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::constructAbstractSubprogramScopeDIE (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; SrcCU, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for this abstract scope.</p>

<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### constructCallSiteEntryDIEs() {#ab7d2f34319b3009ed68be026f80ce56c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::constructCallSiteEntryDIEs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> &amp; SP, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; ScopeDIE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct DIEs for call site entries describing the calls in <span class="doxyComputerOutput">MF</span>.</p>

<p>Declaration at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### constructSkeletonCU() {#a11e63b2669496597b49776bd43f8cd1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCompileUnit &amp; DwarfDebug::constructSkeletonCU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the split debug info compile unit for the debug info section.</p>


<p>In DWARF v5, the skeleton unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> may have the following attributes: DW_AT_addr_base, DW_AT_comp_dir, DW_AT_dwo_name, DW_AT_high_pc, DW_AT_low_pc, DW_AT_ranges, DW_AT_stmt_list, and DW_AT_str_offsets_base. Prior to DWARF v5 it may also have DW_AT_GNU_dwo_id. DW_AT_GNU_dwo_name is used instead of DW_AT_dwo_name, Dw_AT_GNU_addr_base instead of DW_AT_addr_base, and DW_AT_GNU_ranges_base instead of DW_AT_rnglists_base.</p>


<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3622 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### createConcreteEntity() {#a6aa679bfc2b2dfe25f593e4983e0a32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgEntity * DwarfDebug::createConcreteEntity (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; TheCU, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> &amp; Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * Node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * Location, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1854 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitAbbreviations() {#ae62db5220f39dcae803c8bd3a469362b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitAbbreviations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the abbreviation section.</p>

<p>Declaration at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2637 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitAccel() {#a5d8a1896cb87dd31738565620f00e843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AccelTableT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitAccel (AccelTableT &amp; Accel, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TableName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a specified accelerator table.</p>

<p>Declaration at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2651 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitAccelDebugNames() {#a9cb732e5079052a90275442c3098166b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitAccelDebugNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit DWARF v5 accelerator table.</p>

<p>Declaration at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2659 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitAccelNames() {#a222cf09e6c4804ae1896685ad7836db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitAccelNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit visible names into a hashed accelerator table section.</p>

<p>Declaration at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2668 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitAccelNamespaces() {#aa2f7182c65dfe8615c6338bf665dc46a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitAccelNamespaces ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit namespace dies into a hashed accelerator table.</p>

<p>Declaration at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2681 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitAccelObjC() {#a3156c1a41c07201b14d9f4a59549d286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitAccelObjC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit objective C classes and categories into a hashed accelerator table section.</p>

<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2675 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitAccelTypes() {#a888cbe0d940d41680b3e3e7ea20e76ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitAccelTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit type dies into a hashed accelerator table.</p>

<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2688 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugAbbrevDWO() {#a6e7d359ba0a473e548ef36850c362a92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugAbbrevDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the debug abbrev dwo section.</p>

<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3650 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugAddr() {#a199120090d949c0f7d55dbb14df0b618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugAddr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit DWO addresses.</p>

<p>Declaration at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3682 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugARanges() {#af8a9bd2e4d25cb2ea4690794fdcf638c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugARanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit address ranges into a debug aranges section.</p>

<p>Declaration at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3263 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugInfo() {#aea1b427736649d887359105c322a3ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the debug info section.</p>

<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2631 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugInfoDWO() {#aaa6d09046c99728772f75a756b482461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugInfoDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the debug info dwo section.</p>

<p>Declaration at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3642 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugLineDWO() {#aaee7718a0a7de787cb74a433db5aa02e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugLineDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the debug line dwo section.</p>

<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3655 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugLoc() {#a08fb18e1a80a3c5290445e5ec6e506e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit variable locations into a debug loc section.</p>

<p>Declaration at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugLocDWO() {#ac7041a619e2c6e5b7f3a2f9b3b8e1998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugLocDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit variable locations into a debug loc dwo section.</p>

<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugLocImpl() {#ae073459a24daa629ee53ca43b503c652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugLocImpl (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugMacinfo() {#a50b132d74962e2aec9ebd9087209f23d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugMacinfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit macros into a debug macinfo section.</p>


<p>Emit macros into a debug macinfo/macro section.</p>


<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3596 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugMacinfoDWO() {#a9495f66fa67ac05c526e2c3ab6f99b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugMacinfoDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit macros into a debug macinfo.dwo section.</p>

<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3603 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugMacinfoImpl() {#ac14b0270bd04b91f0cc2de450d701dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugMacinfoImpl (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3576 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugPubSection() {#afbb2d847bb9041ed400ecbcc93d6d868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugPubSection (bool GnuStyle, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> * TheU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt; &amp; Globals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2793 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugPubSections() {#aafe392b37305b49c975ef940dbfaf0ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugPubSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit visible names and types into debug pubnames and pubtypes sections.</p>


<p>emitDebugPubSections - Emit visible names and types into debug pubnames and pubtypes sections.</p>


<p>Declaration at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2764 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugRanges() {#a665b2fdd208909f9df63787126d47bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugRanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit address ranges into a debug ranges section.</p>


<p>Emit address ranges into the .debug_ranges section or into the DWARF v5 .debug_rnglists section.</p>


<p>Declaration at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3448 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugRangesDWO() {#a8407a67cede0cd93673ac1bc98ea4ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugRangesDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3457 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugRangesImpl() {#a12df3a3d908e91050692b5f838787ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugRangesImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarffile">DwarfFile</a> &amp; Holder, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3423 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugStr() {#aabbfeba2992aab537c72e4af80236898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugStr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit null-terminated strings into a debug str section.</p>

<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2841 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitDebugStrDWO() {#a664d15cb0e7f12f055b566b892dec891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugStrDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the debug str dwo section.</p>

<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3672 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitMacro() {#a349fff9263cc6f5c65af5d72920fb488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitMacro (<a href="/web-llvm/docs/api/classes/llvm/dimacro">DIMacro</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3499 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitMacroFile() {#a35c7729ffbf9826835858e12627b377d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitMacroFile (<a href="/web-llvm/docs/api/classes/llvm/dimacrofile">DIMacroFile</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3563 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitMacroFileImpl() {#a6859f6c576af9fea71e7d74ed16a2252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitMacroFileImpl (<a href="/web-llvm/docs/api/classes/llvm/dimacrofile">DIMacroFile</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; U, unsigned StartFile, unsigned EndFile, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(*)(unsigned <a href="#a535beef0b6ae2e8972ee23458cd7b629ad359c6df99b25183d81f7d728b71de0e">Form</a>) MacroFormToString)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3542 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitSectionReference() {#a937274a98c024eb43a569b89b7de25ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitSectionReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the reference to the section.</p>

<p>Declaration at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2785 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitStringOffsetsTableHeader() {#a6a1021ce688e7ba4d47d0f58563c1e9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitStringOffsetsTableHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the string offsets table header.</p>

<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2643 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### emitStringOffsetsTableHeaderDWO() {#ac2c5aead48d7a3d30265ab9222ba0df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitStringOffsetsTableHeaderDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the dwo stringoffsets table header.</p>

<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3662 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### ensureAbstractEntityIsCreatedIfScoped() {#a13b40452731caadd40954e8044960858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::ensureAbstractEntityIsCreatedIfScoped (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * Node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1505 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### finalizeModuleInfo() {#ae4101787ca7936838ac4f857e747c0ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::finalizeModuleInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finish off debug information after all functions have been processed.</p>

<p>Declaration at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### findForceIsStmtInstrs() {#a078a9376524eef530002e250fa15bbdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::findForceIsStmtInstrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For the function <span class="doxyComputerOutput">MF</span>, finds the set of instructions which may represent a change in line number from one or more of the preceding MBBs.</p>


<p>Stores the resulting set of instructions, which should have is_stmt set, in ForceIsStmtInstrs.</p>


<p>Declaration at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### finishEntityDefinitions() {#af6abdc9280ceb60fcd1a42b77398056f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::finishEntityDefinitions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### finishSubprogramDefinitions() {#a411599050c5297d34d6025d4f393aafe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::finishSubprogramDefinitions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### finishUnitAttributes() {#a53644e89934d54d6c7c1774760f87790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::finishUnitAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * DIUnit, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; NewCU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### getDwoLineTable() {#a8aafc4e1b1f9b18164683efd15c7dd29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDwarfDwoLineTable * DwarfDebug::getDwoLineTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3686 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### getOrCreateDwarfCompileUnit() {#a87a0abfa2e3ed4c261513379e04bde84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCompileUnit &amp; DwarfDebug::getOrCreateDwarfCompileUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * DIUnit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create new <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> for the given metadata node with tag DW_TAG_compile_unit.</p>

<p>Declaration at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 1075 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### getUnits() {#a9ad22adbcd64241446cd3474f1e0cb5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; std::unique_ptr&lt; DwarfCompileUnit &gt; &gt; &amp; llvm::DwarfDebug::getUnits ()</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### handleMacroNodes() {#aa5c11b20a9e91bc1876436e759ccc3a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::handleMacroNodes (DIMacroNodeArray Nodes, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3488 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### initSkeletonUnit() {#a66e759a9643c0126a9743873c2da77f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::initSkeletonUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> &amp; U, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &gt; NewU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DWARF 5 Experimental Split Dwarf Emitters.</p>


<p>Initialize common features of skeleton units.</p>


<p>Declaration at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3612 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### recordSourceLine() {#abdb786901de44bbb2c3c308b4356d9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::recordSourceLine (unsigned Line, unsigned Col, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Scope, unsigned Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a source line with debug info.</p>


<p>Returns the unique label that was emitted and which provides correspondence to the source line list.</p>


<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2619 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EmitDebugEntryValues {#ab358b7ac5f8f1d053139c7613c9199f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::EmitDebugEntryValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable production of call site parameters needed to print the debug entry values.</p>


<p>Useful for testing purposes when a debugger does not support the feature yet.</p>


<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### HasAppleExtensionAttributes {#aa83b0ac199fd7ce9e644e3a8aec0380b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::HasAppleExtensionAttributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### HasSplitDwarf {#a5731544252c847bf684b414e7ddc8137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::HasSplitDwarf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### SkeletonHolder {#a449e18a480a13dc6a23044284e4aa64a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfFile llvm::DwarfDebug::SkeletonHolder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Separated Dwarf Variables In general these will all be for bits that are left in the original object file, rather than things that are meant to be in the .dwo sections.</p>


<p>Holder for the skeleton information.</p>


<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### SplitTypeUnitFileTable {#a0d730840e0c9b3539878f32feb02a83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDwarfDwoLineTable llvm::DwarfDebug::SplitTypeUnitFileTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Store file names for type units under fission in a line table header that will be emitted into debug_line.dwo.</p>

<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### TheAccelTableKind {#a79b05c497a012a2087c0fc05cdb2e2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTableKind llvm::DwarfDebug::TheAccelTableKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DWARF5 Experimental Options.</p>

<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### UseSegmentedStringOffsetsTable {#ac38cf250fe78d76053765355b07257ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::UseSegmentedStringOffsetsTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to generate the DWARF v5 string offsets table.</p>


<p>It consists of a series of contributions, each preceded by a header. The pre-DWARF v5 string offsets table for split dwarf is, in contrast, a monolithic sequence of string offsets.</p>


<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AccelDebugNames {#a93db82d5ab95c066058baba4549659f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARF5AccelTable llvm::DwarfDebug::AccelDebugNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accelerator tables.</p>

<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### AccelNames {#ade72bebeec25baca23ed1d3800b03215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTable&lt;AppleAccelTableOffsetData&gt; llvm::DwarfDebug::AccelNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### AccelNamespace {#ab2a68a302b52565aa49d1d110842cd8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTable&lt;AppleAccelTableOffsetData&gt; llvm::DwarfDebug::AccelNamespace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### AccelObjC {#a26224edf3aee61983644f9a25f8b77ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTable&lt;AppleAccelTableOffsetData&gt; llvm::DwarfDebug::AccelObjC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### AccelTypes {#ae3b27336dfbc0b951aa844cad0e39783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTable&lt;AppleAccelTableTypeData&gt; llvm::DwarfDebug::AccelTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### AccelTypeUnitsDebugNames {#a55921afed50b607dc83c5a22662be83d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARF5AccelTable llvm::DwarfDebug::AccelTypeUnitsDebugNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### AddrPool {#ad551c9d7f14cc242b5d6d57581ac53a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressPool llvm::DwarfDebug::AddrPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### ArangeLabels {#aebbfca5f6653345fb49693dfa3a2fb27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SymbolCU&gt; llvm::DwarfDebug::ArangeLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of all labels used in aranges generation.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### CompilationDir {#a4fd51b890e8358d5a4a71d7c7fae6ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DwarfDebug::CompilationDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>As an optimization, there is no need to emit an entry in the directory table for the same directory as DW_AT_comp_dir.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### ConcreteEntities {#ab5987dc252786a8a7e31fddc13d18251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;DbgEntity&gt;, 64&gt; llvm::DwarfDebug::ConcreteEntities</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of abstract variables/labels.</p>

<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### CUDieMap {#adcdcfc17d1f545a5168149da810508dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DIE *, DwarfCompileUnit *&gt; llvm::DwarfDebug::CUDieMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a <a href="/web-llvm/docs/api/namespaces/cu">CU</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with its corresponding <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a>.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### CUMap {#abca56b478dc5d874a3d4efc10ae7b517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;const MDNode *, DwarfCompileUnit *&gt; llvm::DwarfDebug::CUMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> with its corresponding <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a>.</p>

<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### CurFn {#a1581f52d7e1fa50de9c9836788d4d60a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction* llvm::DwarfDebug::CurFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If nonnull, stores the current machine function we're processing.</p>

<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### CurrentDebugNames {#aa73e3c137b3914b434452f51e504b930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARF5AccelTable* llvm::DwarfDebug::CurrentDebugNames = &amp;AccelDebugNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to hide which <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> we are using now.</p>

<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### DebuggerTuning {#a54129029a64182f5396367db5ee913d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebuggerKind llvm::DwarfDebug::DebuggerTuning = <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6a7a1920d61156abc05a60135aefe8bc67">DebuggerKind::Default</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify a debugger for "tuning" the debug info.</p>


<p>The "tuning" should be used to set defaults for individual feature flags in <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a>; if a given feature has a more specific command-line option, that option should take precedence over the tuning.</p>


<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### DebugLocs {#a2810e3e4c18d6b95a84ca51c36906b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLocStream llvm::DwarfDebug::DebugLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of <a href="/web-llvm/docs/api/classes/llvm/debuglocentry">DebugLocEntry</a>.</p>


<p>Stored in a linked list so that DIELocLists can refer to them in spite of insertions into this list.</p>


<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### DIEValueAllocator {#a3c7b5f890b3be1add7eb86e87b093647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::DwarfDebug::DIEValueAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All DIEValues are allocated through this allocator.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### EnableOpConvert {#a1b825626bcfe499bb099ae1207b1b2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::EnableOpConvert</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Avoid using DW_OP_convert due to consumer incompatibilities.</p>

<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### ForceIsStmtInstrs {#a169ca09ee6350ab958cad9f8fc71e8df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseSet&lt;const MachineInstr *&gt; llvm::DwarfDebug::ForceIsStmtInstrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### FunctionLineTableLabel {#a8c79dc66ba7a4d70ecca6752936167a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::DwarfDebug::FunctionLineTableLabel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Symbol pointing to the current function's DWARF line table entries.</p>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### GenerateTypeUnits {#a58b2b325925de020f1799c367c057232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::GenerateTypeUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate DWARF v4 type units.</p>

<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### InfoHolder {#ad266ebd3206242a7b2d82fe8705ca64f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfFile llvm::DwarfDebug::InfoHolder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holder for the file specific debug information.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### IsDarwin {#a660db8e7332ecbb1c0e5167236807bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::IsDarwin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### LocalDeclsPerLS {#ab0cab1042e62317188a2bdd091bcea04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DILocalScope *, MDNodeSet&gt; llvm::DwarfDebug::LocalDeclsPerLS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### MinimizeAddr {#ae21b8bcaad4933ff846c985f265dc420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MinimizeAddrInV5 llvm::DwarfDebug::MinimizeAddr = <a href="#a535beef0b6ae2e8972ee23458cd7b629ab9f5c797ebbf55adccdd8539a65a0241">MinimizeAddrInV5::Disabled</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Force the use of DW_AT_ranges even for single-entry range lists.</p>

<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### NumTypeUnitsCreated {#a250907aeb5bd936490df1c8d3bd16427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfDebug::NumTypeUnitsCreated = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to set a uniqe <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for a <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit.</p>


<p>This counter represents number of DwarfTypeUnits created, not necessarily number of type units that will be emitted.</p>


<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### PrevCU {#a084021d79d3dec37a3ef7bc57136658d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DwarfCompileUnit* llvm::DwarfDebug::PrevCU = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If nonnull, stores the <a href="/web-llvm/docs/api/namespaces/cu">CU</a> in which the previous subprogram was contained.</p>

<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### ProcessedSPNodes {#a8afc211969408c80ac4e2856280603a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;const DISubprogram *, 16&gt; llvm::DwarfDebug::ProcessedSPNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a collection of subprogram MDNodes that are processed to create DIEs.</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### SectionLabels {#a58ec2952a3f36af596031541a2cdffd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSection *, const MCSymbol *&gt; llvm::DwarfDebug::SectionLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### SingleCU {#a581ada33f72d8fd09a03b9efc2eebdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::SingleCU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True iff there are multiple CUs in this module.</p>

<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### StringTypeLocMap {#a6f4fc37763d7146fc9af189cc6a623be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DIStringType *, unsigned&gt; llvm::DwarfDebug::StringTypeLocMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map for tracking Fortran deferred CHARACTER lengths.</p>

<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### SymSize {#a1ec499b4dafc5a631b0029d267a4b329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSymbol *, uint64_t&gt; llvm::DwarfDebug::SymSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of each symbol emitted (for those symbols that have a specific size).</p>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### TypeSignatures {#a7fb88fa5d6f6900fce0ae40852f9798e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MDNode *, uint64_t&gt; llvm::DwarfDebug::TypeSignatures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holders for the various debug information flags that we might need to have exposed.</p>


<p>See accessor functions below for description. Map from MDNodes for user-defined types to their type signatures. Also used to keep track of which types we have emitted type units for.</p>


<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### TypeUnitsUnderConstruction {#a989215730a5171852dfc50bbf0bf23b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; std::pair&lt;std::unique_ptr&lt;DwarfTypeUnit&gt;, const DICompositeType *&gt;, 1&gt; llvm::DwarfDebug::TypeUnitsUnderConstruction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### UseAllLinkageNames {#af17f25a9694a664118c1bde1bc684832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::UseAllLinkageNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to emit all linkage names, or just abstract subprograms.</p>

<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### UseARangesSection {#af1cc5f57add2c38507a2ef540165869e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::UseARangesSection = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow emission of .debug_aranges section.</p>

<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### UseDebugMacroSection {#a46854f5f0a6b931c1756f3e17c0607a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::UseDebugMacroSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a .debug_macro section instead of .debug_macinfo.</p>

<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### UseDWARF2Bitfields {#aafde27433a1a5cd24e70d9efc5a78bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::UseDWARF2Bitfields</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to use DWARF 2 bitfields (instead of the DWARF 4 format).</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### UseGNUTLSOpcode {#ab4438f98379b5e2439f38cd4b800c8a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::UseGNUTLSOpcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to use the GNU TLS opcode (instead of the standard opcode).</p>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### UseInlineStrings {#a03d7514d60e64bd0b2c7804ec2af8109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::UseInlineStrings = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> inlined strings.</p>

<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### UseRangesSection {#ada4c2af65fbcf43c19382781ac028b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::UseRangesSection = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow emission of .debug_ranges section.</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

### UseSectionsAsReferences {#a806cc89f121f18eda3a2807d9a5f2bf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfDebug::UseSectionsAsReferences = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the sections itself must be used as references and don't create temp symbols inside DWARF sections.</p>

<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### emitDebugLocValue() {#aa441f906c99d29f50a64369799d8f737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfDebug::emitDebugLocValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp; AP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> * BT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc">DbgValueLoc</a> &amp; Value, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression">DwarfExpression</a> &amp; DwarfExpr)</td>
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



<p>Declaration at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 2896 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">llvm::DwarfExpression::addConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ac2e0ff8d944ddd6ebf0ab7f7ab7b9775">llvm::DwarfExpression::addExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2fdab5e48a4c62a742df876d4e55940f">llvm::DwarfExpression::addFragmentOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">llvm::DwarfExpression::addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#ad676cf44e0c249e17c08edb7d3270b45">llvm::DwarfExpression::addSignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aa7a84268a368e42a1bed6f9e4def555b">llvm::DwarfExpression::addUnsignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af2a335e267a7975d64235e578d89a2c9">llvm::DwarfExpression::addWasmLocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#af496d6e3f88f3b85e879bfdfe19b0b40">llvm::DwarfExpression::beginEntryValueExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1cdcee0a67dceede7f2a7b4bafccc900">llvm::AsmPrinter::getDwarfDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aeb3392fbf967daeb60cb65f9abcd541b">llvm::AsmPrinter::getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33fe94054a904130a7c774f78423c8b7">llvm::TargetMachine::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#acf7f07dbe7dd1f7edd291b75005280bb">llvm::Triple::isWasm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a082b9984a203d2a2ba3dd4b5986d4706">llvm::DwarfExpression::setLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a509852c6998b529c06357c2bba7aeabb">llvm::DwarfExpression::setMemoryLocationKind</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/groups/debuggertuning/#ga12d17eb7e0ee4182377397d9fb39459d">tuneForSCE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">llvm::DwarfCompileUnit::constructCallSiteParmEntryDIEs</a> and <a href="/web-llvm/docs/api/classes/llvm/debuglocentry/#accfecad1691b64f7eba86e5080680b64">llvm::DebugLocEntry::finalize</a>.</p>

</div>
</div>

### makeTypeSignature() {#affd65b6c842827550ed102e2d82b90fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DwarfDebug::makeTypeSignature (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Identifier)</td>
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

<p>Perform an <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> checksum of <span class="doxyComputerOutput">Identifier</span> and return the lower 64 bits.</p>

<p>Declaration at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>, definition at line 3696 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/md5/#a5138672d89124f45e2217d8484a59a40">llvm::MD5::final</a> and <a href="/web-llvm/docs/api/classes/llvm/md5/#a3f41856aade4440631544e50238f75f5">llvm::MD5::update</a>.</p>


<p>Referenced by <a href="#ad06f166cd8884265b3a1ea2849f0c026">addDwarfTypeUnitType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
