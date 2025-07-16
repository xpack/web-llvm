---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/debughandlerbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DebugHandlerBase` Class Reference

<p>Base class for debug information backends. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DebugHandlerBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">llvm/CodeGen/DebugHandlerBase.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinterhandler">AsmPrinterHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects and handles <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> objects required to build debug or EH information. <a href="/web-llvm/docs/api/classes/llvm/asmprinterhandler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/btfdebug">BTFDebug</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect and emit <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> information. <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeviewdebug">CodeViewDebug</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects and handles line tables information in a CodeView format. <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects and handles dwarf debug information. <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a966cbffb61d32a19d00616f851a5eb6e">DebugHandlerBase</a> (AsmPrinter *A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8427022ab8db75eee9b9e615e6a53523">~DebugHandlerBase</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1299778170e0f0cd04e48329df7d7f7">beginModule</a> (Module *M) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b73ffc5808cd622aa76eeb07fc3e87">beginInstruction</a> (const MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> beginning of an instruction. <a href="#a99b73ffc5808cd622aa76eeb07fc3e87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b59f94fbe83b95be73b11dcfefdb1e">endInstruction</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> end of an instruction. <a href="#a82b59f94fbe83b95be73b11dcfefdb1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6917b0d19333a9557db102d973490178">beginFunction</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather pre-function debug information. <a href="#a6917b0d19333a9557db102d973490178">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5289ab365c11603605983aaffe7cc908">endFunction</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather post-function debug information. <a href="#a5289ab365c11603605983aaffe7cc908">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab11ae5ad7e5425363269b222cf113f40">beginBasicBlockSection</a> (const MachineBasicBlock &amp;MBB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the beginning of a new basic-block-section within a function. <a href="#ab11ae5ad7e5425363269b222cf113f40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e11974dc6a4adcf263f0dce1e0c5c1">endBasicBlockSection</a> (const MachineBasicBlock &amp;MBB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the end of a basic-block-section within a function. <a href="#a40e11974dc6a4adcf263f0dce1e0c5c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a369cc2e9b90b5786267c574639d22d3f">getLabelBeforeInsn</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return Label preceding the instruction. <a href="#a369cc2e9b90b5786267c574639d22d3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f0a308af7db83a48443c4512bd3268">getLabelAfterInsn</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return Label immediately following the instruction. <a href="#a89f0a308af7db83a48443c4512bd3268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructionordering">InstructionOrdering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5198fd449df907998c1a04e3083703a">getInstOrdering</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a457f3c8acd738586fab8d9ac08f44013">identifyScopeMarkers</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indentify instructions that are marking the beginning of or ending of a scope. <a href="#a457f3c8acd738586fab8d9ac08f44013">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b833d5bf85c69d922a140d1a917314">requestLabelBeforeInsn</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure that a label will be emitted before MI. <a href="#ad2b833d5bf85c69d922a140d1a917314">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaffb6bc659419af61a639d756f210137">requestLabelAfterInsn</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure that a label will be emitted after MI. <a href="#aaffb6bc659419af61a639d756f210137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa945cd2ffd421de27ee161a7547e716e">beginFunctionImpl</a> (const MachineFunction *MF)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a351f8a03d6f25422698ac3c654277859">endFunctionImpl</a> (const MachineFunction *MF)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b1c2ef0788d92043b6a059e38c6ab23">skippedNonDebugFunction</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">Asm</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> of debug info emission. <a href="#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a4faa309dc268374a2b3ea981c47c7b">MMI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collected machine module information. <a href="#a3a4faa309dc268374a2b3ea981c47c7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68492cf3d8769e02ee84f61e8c4e9328">PrevInstLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Previous instruction's location information. <a href="#a68492cf3d8769e02ee84f61e8c4e9328">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58506448d8b951c82476a20b39b947af">PrevLabel</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa57448b6774e5d6264452732dc188388">PrevInstBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5173816befd317718323259ef8579cd">PrologEndLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This location indicates end of function prologue and beginning of function body. <a href="#af5173816befd317718323259ef8579cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9447598df768a1aba7a9006b0458e0c">EpilogBeginBlock</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This block includes epilogue instructions. <a href="#ae9447598df768a1aba7a9006b0458e0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03bc61adaddbb1e6c2a2d7cabcb555d3">CurMI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If nonnull, stores the current machine instruction we're processing. <a href="#a03bc61adaddbb1e6c2a2d7cabcb555d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscopes">LexicalScopes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa635647755035e74d272e038b44dcc">LScopes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap">DbgValueHistoryMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9136548c5b20521d9294807ea08c419">DbgValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>History of DBG_VALUE and clobber instructions for each user variable. <a href="#ab9136548c5b20521d9294807ea08c419">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbglabelinstrmap">DbgLabelInstrMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d84007d4d57392392ef7de7ff13c51">DbgLabels</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of inlined labels and DBG_LABEL machine instruction. <a href="#ab9d84007d4d57392392ef7de7ff13c51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd042f61013391ccefba25d04c1eff10">LabelsBeforeInsn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps instruction with label emitted before instruction. <a href="#abd042f61013391ccefba25d04c1eff10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac532e9ba9faea79ac2ed53b25e4907f4">LabelsAfterInsn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps instruction with label emitted after instruction. <a href="#ac532e9ba9faea79ac2ed53b25e4907f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionordering">InstructionOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc992871be04f3981c7aef3b5ec5435c">InstOrdering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe484f4318d274ce8302f2650cd399bd">getBaseTypeSize</a> (const DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this type is derived from a base type then return base type size. <a href="#afe484f4318d274ce8302f2650cd399bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a001a32e3894866f526f81677bb7d1b08">isUnsignedDIType</a> (const DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if type encoding is unsigned. <a href="#a001a32e3894866f526f81677bb7d1b08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class for debug information backends.</p>


<p>Common functionality related to tracking which variables and scopes are alive at a given PC live here.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### DebugHandlerBase() {#a966cbffb61d32a19d00616f851a5eb6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugHandlerBase::DebugHandlerBase (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A)</td>
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



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">Asm</a> and <a href="#a3a4faa309dc268374a2b3ea981c47c7b">MMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a2c6578835c232d441544863a86c04728">llvm::BTFDebug::BTFDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a3593e4824db4ccf2c7fe22a21922e734">llvm::CodeViewDebug::CodeViewDebug</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DebugHandlerBase() {#a8427022ab8db75eee9b9e615e6a53523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugHandlerBase::~DebugHandlerBase ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### beginBasicBlockSection() {#ab11ae5ad7e5425363269b222cf113f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugHandlerBase::beginBasicBlockSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the beginning of a new basic-block-section within a function.</p>


<p>Always called immediately after beginFunction for the first basic-block. When basic-block-sections are enabled, called before the first block of each such section.</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="#ae9447598df768a1aba7a9006b0458e0c">EpilogBeginBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a58506448d8b951c82476a20b39b947af">PrevLabel</a>.</p>

</div>
</div>

### beginFunction() {#a6917b0d19333a9557db102d973490178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugHandlerBase::beginFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather pre-function debug information.</p>


<p>Every beginFunction(MF) call should be followed by an endFunction(MF) call.</p>


<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa945cd2ffd421de27ee161a7547e716e">beginFunctionImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>, <a href="#ab9d84007d4d57392392ef7de7ff13c51">DbgLabels</a>, <a href="#ab9136548c5b20521d9294807ea08c419">DbgValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af648a1ecd9b0189801c2c8f8f15ffba3">llvm::getDISubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a38229438b1c22802074b3181b0b80b85">llvm::DILocalVariable::getScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp/#a9810fe86e30b35178c82eeb9d29811d8">hasDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a457f3c8acd738586fab8d9ac08f44013">identifyScopeMarkers</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a45c267092569766aa684c6ba3bae9634">llvm::DILocalVariable::isParameter</a>, <a href="#abd042f61013391ccefba25d04c1eff10">LabelsBeforeInsn</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aeaa635647755035e74d272e038b44dcc">LScopes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#aa57448b6774e5d6264452732dc188388">PrevInstBB</a>, <a href="#a68492cf3d8769e02ee84f61e8c4e9328">PrevInstLoc</a>, <a href="#a58506448d8b951c82476a20b39b947af">PrevLabel</a>, <a href="#aaffb6bc659419af61a639d756f210137">requestLabelAfterInsn</a>, <a href="#ad2b833d5bf85c69d922a140d1a917314">requestLabelBeforeInsn</a>, <a href="#a4b1c2ef0788d92043b6a059e38c6ab23">skippedNonDebugFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp/#a7c6652a76e58d8c5cd34b5f45deccf0b">TrimVarLocs</a>.</p>

</div>
</div>

### beginInstruction() {#a99b73ffc5808cd622aa76eeb07fc3e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugHandlerBase::beginInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a03bc61adaddbb1e6c2a2d7cabcb555d3">CurMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#abd042f61013391ccefba25d04c1eff10">LabelsBeforeInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a3a4faa309dc268374a2b3ea981c47c7b">MMI</a> and <a href="#a58506448d8b951c82476a20b39b947af">PrevLabel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a392dd12827c5ede927d490ccc16f38ab">llvm::BTFDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a9defc9f8d2c86141967debd635709d4b">llvm::CodeViewDebug::beginInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a>.</p>

</div>
</div>

### beginModule() {#ac1299778170e0f0cd04e48329df7d7f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugHandlerBase::beginModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>Reference <a href="#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">Asm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3f59a82f48553634ac4625cb8166071e">llvm::DwarfDebug::beginModule</a>.</p>

</div>
</div>

### endBasicBlockSection() {#a40e11974dc6a4adcf263f0dce1e0c5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugHandlerBase::endBasicBlockSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the end of a basic-block-section within a function.</p>


<p>When basic-block-sections are enabled, called after the last block in each such section (including the last section in the function). When basic-block-sections are disabled, called at the end of a function, immediately prior to markFunctionEnd.</p>


<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a58506448d8b951c82476a20b39b947af">PrevLabel</a>.</p>

</div>
</div>

### endFunction() {#a5289ab365c11603605983aaffe7cc908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugHandlerBase::endFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather post-function debug information.</p>

<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">Asm</a>, <a href="#ab9d84007d4d57392392ef7de7ff13c51">DbgLabels</a>, <a href="#ab9136548c5b20521d9294807ea08c419">DbgValues</a>, <a href="#a351f8a03d6f25422698ac3c654277859">endFunctionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp/#a9810fe86e30b35178c82eeb9d29811d8">hasDebugInfo</a>, <a href="#ac532e9ba9faea79ac2ed53b25e4907f4">LabelsAfterInsn</a> and <a href="#abd042f61013391ccefba25d04c1eff10">LabelsBeforeInsn</a>.</p>

</div>
</div>

### endInstruction() {#a82b59f94fbe83b95be73b11dcfefdb1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugHandlerBase::endInstruction ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> end of an instruction.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a03bc61adaddbb1e6c2a2d7cabcb555d3">CurMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac532e9ba9faea79ac2ed53b25e4907f4">LabelsAfterInsn</a>, <a href="#a3a4faa309dc268374a2b3ea981c47c7b">MMI</a>, <a href="#aa57448b6774e5d6264452732dc188388">PrevInstBB</a> and <a href="#a58506448d8b951c82476a20b39b947af">PrevLabel</a>.</p>

</div>
</div>

### getInstOrdering() {#ac5198fd449df907998c1a04e3083703a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstructionOrdering &amp; llvm::DebugHandlerBase::getInstOrdering ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>

</div>
</div>

### getLabelAfterInsn() {#a89f0a308af7db83a48443c4512bd3268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * DebugHandlerBase::getLabelAfterInsn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return Label immediately following the instruction.</p>

<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="#ac532e9ba9faea79ac2ed53b25e4907f4">LabelsAfterInsn</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a95c1eb0bb9394b39e6edb45ae6a57bfe">llvm::CodeViewDebug::endFunctionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#acb34ac66067af067228eaaab8df6e982">llvm::DwarfDebug::isLexicalScopeDIENull</a>.</p>

</div>
</div>

### getLabelBeforeInsn() {#a369cc2e9b90b5786267c574639d22d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * DebugHandlerBase::getLabelBeforeInsn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return Label preceding the instruction.</p>

<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abd042f61013391ccefba25d04c1eff10">LabelsBeforeInsn</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a95c1eb0bb9394b39e6edb45ae6a57bfe">llvm::CodeViewDebug::endFunctionImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### beginFunctionImpl() {#aa945cd2ffd421de27ee161a7547e716e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DebugHandlerBase::beginFunctionImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>.</p>

</div>
</div>

### endFunctionImpl() {#a351f8a03d6f25422698ac3c654277859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DebugHandlerBase::endFunctionImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a5289ab365c11603605983aaffe7cc908">endFunction</a>.</p>

</div>
</div>

### identifyScopeMarkers() {#a457f3c8acd738586fab8d9ac08f44013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DebugHandlerBase::identifyScopeMarkers ()</td>
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

<p>Indentify instructions that are marking the beginning of or ending of a scope.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope/#a1e1fdb87c9819b28634bea00da2b6ca1">llvm::LexicalScope::getChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope/#a4f977132f8ef94fe76347543705ad47b">llvm::LexicalScope::getRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope/#af179324c1aaa5b134c51c4bda72cb357">llvm::LexicalScope::isAbstractScope</a>, <a href="#aeaa635647755035e74d272e038b44dcc">LScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#aaffb6bc659419af61a639d756f210137">requestLabelAfterInsn</a> and <a href="#ad2b833d5bf85c69d922a140d1a917314">requestLabelBeforeInsn</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>.</p>

</div>
</div>

### requestLabelAfterInsn() {#aaffb6bc659419af61a639d756f210137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DebugHandlerBase::requestLabelAfterInsn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Ensure that a label will be emitted after MI.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>References <a href="#ac532e9ba9faea79ac2ed53b25e4907f4">LabelsAfterInsn</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a> and <a href="#a457f3c8acd738586fab8d9ac08f44013">identifyScopeMarkers</a>.</p>

</div>
</div>

### requestLabelBeforeInsn() {#ad2b833d5bf85c69d922a140d1a917314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DebugHandlerBase::requestLabelBeforeInsn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Ensure that a label will be emitted before MI.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>References <a href="#abd042f61013391ccefba25d04c1eff10">LabelsBeforeInsn</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a> and <a href="#a457f3c8acd738586fab8d9ac08f44013">identifyScopeMarkers</a>.</p>

</div>
</div>

### skippedNonDebugFunction() {#a4b1c2ef0788d92043b6a059e38c6ab23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DebugHandlerBase::skippedNonDebugFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Asm {#a1e2d2b34f55d0b4cef8a429f0d5b8e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter* llvm::DebugHandlerBase::Asm = nullptr</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> of debug info emission.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ad06f166cd8884265b3a1ea2849f0c026">llvm::DwarfDebug::addDwarfTypeUnitType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ae7819cf4c91db139508a49f5e0401243">llvm::DwarfDebug::beginCodeAlignment</a>, <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#af5b3d468d882817a49ac012840023d10">llvm::BTFDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#af89d6d0bd3c47fc34cb897ea7131f9ac">llvm::DwarfDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a392dd12827c5ede927d490ccc16f38ab">llvm::BTFDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a9defc9f8d2c86141967debd635709d4b">llvm::CodeViewDebug::beginInstruction</a>, <a href="#a99b73ffc5808cd622aa76eeb07fc3e87">beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a435833d0fa51b89ed044e840a28833a0">llvm::CodeViewDebug::beginModule</a>, <a href="#ac1299778170e0f0cd04e48329df7d7f7">beginModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3f59a82f48553634ac4625cb8166071e">llvm::DwarfDebug::beginModule</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a2c6578835c232d441544863a86c04728">llvm::BTFDebug::BTFDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a3593e4824db4ccf2c7fe22a21922e734">llvm::CodeViewDebug::CodeViewDebug</a>, <a href="#a966cbffb61d32a19d00616f851a5eb6e">DebugHandlerBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3d1945df4a676ee30059653cc05be15a">llvm::DwarfDebug::emitDebugLocEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a990840b65d04e11c55ea3c2eff5ad47c">llvm::DwarfDebug::emitDebugLocEntryLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ab0627dac3e2666638fa514a2d98299ef">llvm::DwarfDebug::emitInitialLocDirective</a>, <a href="#a5289ab365c11603605983aaffe7cc908">endFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a95c1eb0bb9394b39e6edb45ae6a57bfe">llvm::CodeViewDebug::endFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>, <a href="#a82b59f94fbe83b95be73b11dcfefdb1e">endInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a9a2cbcf1860cebff122bc6c8d2c9b7f9">llvm::CodeViewDebug::endModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#adb62e2b6d18233c7069ea46cf3855b61">llvm::DwarfDebug::endModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aaa2a9e9b8cba40b4beaf474f7ffb914d">llvm::DwarfDebug::getDwarfCompileUnitIDForLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a46b0fb1505ef705cdf28d6b2612c5579">llvm::DwarfDebug::getDwarfSectionOffsetForm</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3ace4bbb6f50507e82b0fbec1ee7ea74">llvm::DwarfDebug::getDwarfVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8e76c771af1d9f50bb133eb3aeadb087">llvm::DwarfDebug::terminateLineTable</a>.</p>

</div>
</div>

### CurMI {#a03bc61adaddbb1e6c2a2d7cabcb555d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* llvm::DebugHandlerBase::CurMI = nullptr</td>
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

<p>If nonnull, stores the current machine instruction we're processing.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a392dd12827c5ede927d490ccc16f38ab">llvm::BTFDebug::beginInstruction</a>, <a href="#a99b73ffc5808cd622aa76eeb07fc3e87">beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a>, <a href="#a82b59f94fbe83b95be73b11dcfefdb1e">endInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#adb62e2b6d18233c7069ea46cf3855b61">llvm::DwarfDebug::endModule</a>.</p>

</div>
</div>

### DbgLabels {#ab9d84007d4d57392392ef7de7ff13c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgLabelInstrMap llvm::DebugHandlerBase::DbgLabels</td>
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

<p>Mapping of inlined labels and DBG_LABEL machine instruction.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a> and <a href="#a5289ab365c11603605983aaffe7cc908">endFunction</a>.</p>

</div>
</div>

### DbgValues {#ab9136548c5b20521d9294807ea08c419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgValueHistoryMap llvm::DebugHandlerBase::DbgValues</td>
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

<p>History of DBG_VALUE and clobber instructions for each user variable.</p>


<p>Variables are listed in order of appearance.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a> and <a href="#a5289ab365c11603605983aaffe7cc908">endFunction</a>.</p>

</div>
</div>

### EpilogBeginBlock {#ae9447598df768a1aba7a9006b0458e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::DebugHandlerBase::EpilogBeginBlock = nullptr</td>
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

<p>This block includes epilogue instructions.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#ab11ae5ad7e5425363269b222cf113f40">beginBasicBlockSection</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a>.</p>

</div>
</div>

### LabelsAfterInsn {#ac532e9ba9faea79ac2ed53b25e4907f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineInstr *, MCSymbol *&gt; llvm::DebugHandlerBase::LabelsAfterInsn</td>
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

<p>Maps instruction with label emitted after instruction.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a5289ab365c11603605983aaffe7cc908">endFunction</a>, <a href="#a82b59f94fbe83b95be73b11dcfefdb1e">endInstruction</a>, <a href="#a89f0a308af7db83a48443c4512bd3268">getLabelAfterInsn</a> and <a href="#aaffb6bc659419af61a639d756f210137">requestLabelAfterInsn</a>.</p>

</div>
</div>

### LabelsBeforeInsn {#abd042f61013391ccefba25d04c1eff10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineInstr *, MCSymbol *&gt; llvm::DebugHandlerBase::LabelsBeforeInsn</td>
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

<p>Maps instruction with label emitted before instruction.</p>


<p>FIXME: Make this private from <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a>, we have the necessary accessors for it.</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>, <a href="#a99b73ffc5808cd622aa76eeb07fc3e87">beginInstruction</a>, <a href="#a5289ab365c11603605983aaffe7cc908">endFunction</a>, <a href="#a369cc2e9b90b5786267c574639d22d3f">getLabelBeforeInsn</a> and <a href="#ad2b833d5bf85c69d922a140d1a917314">requestLabelBeforeInsn</a>.</p>

</div>
</div>

### LScopes {#aeaa635647755035e74d272e038b44dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScopes llvm::DebugHandlerBase::LScopes</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#af89d6d0bd3c47fc34cb897ea7131f9ac">llvm::DwarfDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a95c1eb0bb9394b39e6edb45ae6a57bfe">llvm::CodeViewDebug::endFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a> and <a href="#a457f3c8acd738586fab8d9ac08f44013">identifyScopeMarkers</a>.</p>

</div>
</div>

### MMI {#a3a4faa309dc268374a2b3ea981c47c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfo* llvm::DebugHandlerBase::MMI = nullptr</td>
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

<p>Collected machine module information.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="#a99b73ffc5808cd622aa76eeb07fc3e87">beginInstruction</a>, <a href="#a966cbffb61d32a19d00616f851a5eb6e">DebugHandlerBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a95c1eb0bb9394b39e6edb45ae6a57bfe">llvm::CodeViewDebug::endFunctionImpl</a> and <a href="#a82b59f94fbe83b95be73b11dcfefdb1e">endInstruction</a>.</p>

</div>
</div>

### PrevInstBB {#aa57448b6774e5d6264452732dc188388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::DebugHandlerBase::PrevInstBB = nullptr</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a9defc9f8d2c86141967debd635709d4b">llvm::CodeViewDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a> and <a href="#a82b59f94fbe83b95be73b11dcfefdb1e">endInstruction</a>.</p>

</div>
</div>

### PrevInstLoc {#a68492cf3d8769e02ee84f61e8c4e9328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::DebugHandlerBase::PrevInstLoc</td>
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

<p>Previous instruction's location information.</p>


<p>This is used to determine label location to indicate scope boundaries in debug info. We track the previous instruction's source location (if not line 0), whether it was a label, and its parent BB.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a392dd12827c5ede927d490ccc16f38ab">llvm::BTFDebug::beginInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a>.</p>

</div>
</div>

### PrevLabel {#a58506448d8b951c82476a20b39b947af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::DebugHandlerBase::PrevLabel = nullptr</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="#ab11ae5ad7e5425363269b222cf113f40">beginBasicBlockSection</a>, <a href="#a6917b0d19333a9557db102d973490178">beginFunction</a>, <a href="#a99b73ffc5808cd622aa76eeb07fc3e87">beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a>, <a href="#a40e11974dc6a4adcf263f0dce1e0c5c1">endBasicBlockSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a> and <a href="#a82b59f94fbe83b95be73b11dcfefdb1e">endInstruction</a>.</p>

</div>
</div>

### PrologEndLoc {#af5173816befd317718323259ef8579cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* llvm::DebugHandlerBase::PrologEndLoc</td>
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

<p>This location indicates end of function prologue and beginning of function body.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#af89d6d0bd3c47fc34cb897ea7131f9ac">llvm::DwarfDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ab0627dac3e2666638fa514a2d98299ef">llvm::DwarfDebug::emitInitialLocDirective</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InstOrdering {#adc992871be04f3981c7aef3b5ec5435c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionOrdering llvm::DebugHandlerBase::InstOrdering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getBaseTypeSize() {#afe484f4318d274ce8302f2650cd399bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DebugHandlerBase::getBaseTypeSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
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

<p>If this type is derived from a base type then return base type size.</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#afe484f4318d274ce8302f2650cd399bd">getBaseTypeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a8b53bdd5b8f1d8cd12a392c256cb54f3">llvm::DIType::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a13471a1f55ae60d82d774585bfd3c5da">llvm::DINode::getTag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>


<p>Referenced by <a href="#afe484f4318d274ce8302f2650cd399bd">getBaseTypeSize</a>.</p>

</div>
</div>

### isUnsignedDIType() {#a001a32e3894866f526f81677bb7d1b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DebugHandlerBase::isUnsignedDIType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
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

<p>Return true if type encoding is unsigned.</p>

<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a001a32e3894866f526f81677bb7d1b08">isUnsignedDIType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a001a32e3894866f526f81677bb7d1b08">isUnsignedDIType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/debughandlerbase-h">DebugHandlerBase.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/debughandlerbase-cpp">DebugHandlerBase.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
