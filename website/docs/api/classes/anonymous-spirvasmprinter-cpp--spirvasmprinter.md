---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SPIRVAsmPrinter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is intended to be used as a driving class for all asm writers. <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf37ee3eeb9b61a6555077dbfb9fe3e">SPIRVAsmPrinter</a> (TargetMachine &amp;TM, std::unique_ptr&lt; MCStreamer &gt; Streamer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73fa6447d27478aacba7e5800efaa6f0">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a73fa6447d27478aacba7e5800efaa6f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84913da63189f7b4166625f0f01a37e5">printOperand</a> (const MachineInstr *MI, int OpNum, raw_ostream &amp;O)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146fee6d5d7a1e6d7b4c02fe33e9216b">PrintAsmOperand</a> (const MachineInstr *MI, unsigned OpNo, const char *ExtraCode, raw_ostream &amp;O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant. <a href="#a146fee6d5d7a1e6d7b4c02fe33e9216b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a> (MCInst &amp;Inst)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4d4a78b2bc398e0b077e77c2838d7f">outputInstruction</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f434349f8430ae84cd072e3bcd6cf6c">outputModuleSection</a> (SPIRV::ModuleSectionType MSType)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d0742eff167655206896feab35cd4b">outputGlobalRequirements</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a1086f0aa442d022ef86a57757ef94">outputEntryPoints</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adac6a6f0dd9ecdd7b774da11940ce88b">outputDebugSourceAndStrings</a> (const Module &amp;M)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a996dc62cedd72ad61d739065da84a232">outputOpExtInstImports</a> (const Module &amp;M)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4a667381f5644b8c90d6e9c78642b9">outputOpMemoryModel</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9ff97cd854e60b8561792b2b3fd2d0f">outputOpFunctionEnd</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22518f296231106bdd60c1d4397965a6">outputExtFuncDecls</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc68a425d6211a1b46e2df470bf12439">outputExecutionModeFromMDNode</a> (Register Reg, MDNode *Node, SPIRV::ExecutionMode::ExecutionMode EM, unsigned ExpectMDOps, int64_t DefVal)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0594bfc35119c8d898c51bb3697823">outputExecutionModeFromNumthreadsAttribute</a> (const Register &amp;Reg, const Attribute &amp;Attr, SPIRV::ExecutionMode::ExecutionMode EM)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc046e9fee2ff69250264feef8baaf15">outputExecutionMode</a> (const Module &amp;M)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef83676a470a77d6e089737fb024de94">outputAnnotations</a> (const Module &amp;M)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02b6570000092bd33dabbb33f860b51f">isHidden</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bdba76620eb0f11738a259fe07c0492">emitInstruction</a> (const MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets should implement this to emit instructions. <a href="#a8bdba76620eb0f11738a259fe07c0492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6563b12bd1566b6b24d81c810052795">emitFunctionEntryLabel</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitFunctionEntryLabel - Emit the label that is the entrypoint for the function. <a href="#ae6563b12bd1566b6b24d81c810052795">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bbcf6e7814ab7970d3a03436bf2eb4">emitFunctionHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method emits the header for the current function. <a href="#a94bbcf6e7814ab7970d3a03436bf2eb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb7019ee67f4bc4f83e2975b079f4e1">emitFunctionBodyStart</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can override this to emit stuff before the first basic block in the function. <a href="#afdb7019ee67f4bc4f83e2975b079f4e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e4eb9d8bad834b43080dd9f51ba5ba4">emitFunctionBodyEnd</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can override this to emit stuff after the last basic block in the function. <a href="#a8e4eb9d8bad834b43080dd9f51ba5ba4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a17d03c273bf57b84b3c6dd9bb1efa">emitBasicBlockStart</a> (const MachineBasicBlock &amp;MBB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can override this to emit stuff at the start of a basic block. <a href="#a06a17d03c273bf57b84b3c6dd9bb1efa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a0324824839feefcdc23a9512aabfdd">emitBasicBlockEnd</a> (const MachineBasicBlock &amp;MBB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can override this to emit stuff at the end of a basic block. <a href="#a6a0324824839feefcdc23a9512aabfdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa88a3ee4331bf05aa38bcb033eb97e19">emitGlobalVariable</a> (const GlobalVariable *GV) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the specified global variable to the .s file. <a href="#aa88a3ee4331bf05aa38bcb033eb97e19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95377c6337c8286d00bfd8a2ff437029">emitOpLabel</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25207d3e0755fe9eb686906a41392b9d">emitEndOfAsmFile</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This virtual method can be overridden by targets that want to emit something at the end of their file. <a href="#a25207d3e0755fe9eb686906a41392b9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ca8b2967965da1d5de352f26a77a7f8">doInitialization</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up the AsmPrinter when we are working on a new module. <a href="#a0ca8b2967965da1d5de352f26a77a7f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adce8f406f264753a41f5271df4cf0e0c">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Record analysis usage. <a href="#adce8f406f264753a41f5271df4cf0e0c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b81f0df4aa35dec58dc381e6beb5bb">cleanUp</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8494156281dfecc4b402ee74a519b5f5">ModuleSectionsEmitted</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvsubtarget">SPIRVSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01fb69540ab1d216584a2e2547642384">ST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo">SPIRVInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16044b50a8acbad43bf3655a777a6095">TII</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SPIRV::ModuleAnalysisInfo *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc493588d05ddcd99f390c48625e7893">NLabels</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfbebdf28c69925b6bdc0b4c7722d24f">LabeledMBB</a></td>
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


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SPIRVAsmPrinter() {#aadf37ee3eeb9b61a6555077dbfb9fe3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::SPIRVAsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; Streamer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#afcfe4636c15aaef711e33ecc8638f9b4">llvm::AsmPrinter::AsmPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a01fb69540ab1d216584a2e2547642384">ST</a>, <a href="#a16044b50a8acbad43bf3655a777a6095">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doInitialization() {#a0ca8b2967965da1d5de352f26a77a7f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVAsmPrinter::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Set up the AsmPrinter when we are working on a new module.</p>


<p>If your pass overrides this, it must make sure to explicitly call this implementation.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7cd6d58462a0ebf3fa2c3d1423b0e2c6">llvm::AsmPrinter::doInitialization</a> and <a href="#a8494156281dfecc4b402ee74a519b5f5">ModuleSectionsEmitted</a>.</p>

</div>
</div>

### emitBasicBlockEnd() {#a6a0324824839feefcdc23a9512aabfdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::emitBasicBlockEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Targets can override this to emit stuff at the end of a basic block.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### emitBasicBlockStart() {#a06a17d03c273bf57b84b3c6dd9bb1efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::emitBasicBlockStart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Targets can override this to emit stuff at the start of a basic block.</p>


<p>emitBasicBlockStart - This method prints the label for the specified <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>, an alignment (if present) and a comment describing it if appropriate.</p>


<p>By default, this method prints the label for the specified <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>, an alignment (if present) and a comment describing it if appropriate.</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="#a95377c6337c8286d00bfd8a2ff437029">emitOpLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### emitEndOfAsmFile() {#a25207d3e0755fe9eb686906a41392b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::emitEndOfAsmFile (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>This virtual method can be overridden by targets that want to emit something at the end of their file.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="#a26b81f0df4aa35dec58dc381e6beb5bb">cleanUp</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a56a72b8793b8e0df7217c9b19a83320b">llvm::VersionTuple::getMajor</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#af16679f141c8a480a1e6dcc0b8bcf5de">llvm::VersionTuple::getMinor</a>, <a href="#a8494156281dfecc4b402ee74a519b5f5">ModuleSectionsEmitted</a>, <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvobjectwriter/#ace1849570653b063c042244c177928d7">llvm::SPIRVObjectWriter::setBuildVersion</a>, <a href="#a01fb69540ab1d216584a2e2547642384">ST</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>

</div>
</div>

### emitFunctionBodyEnd() {#a8e4eb9d8bad834b43080dd9f51ba5ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::emitFunctionBodyEnd ()</td>
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

<p>Targets can override this to emit stuff after the last basic block in the function.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="#a02b6570000092bd33dabbb33f860b51f">isHidden</a> and <a href="#aa9ff97cd854e60b8561792b2b3fd2d0f">outputOpFunctionEnd</a>.</p>

</div>
</div>

### emitFunctionBodyStart() {#afdb7019ee67f4bc4f83e2975b079f4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::emitFunctionBodyStart ()</td>
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

<p>Targets can override this to emit stuff before the first basic block in the function.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>

</div>
</div>

### emitFunctionEntryLabel() {#ae6563b12bd1566b6b24d81c810052795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::emitFunctionEntryLabel ()</td>
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

<p>EmitFunctionEntryLabel - Emit the label that is the entrypoint for the function.</p>


<p>This can be overridden by targets as required to do custom stuff.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>

</div>
</div>

### emitFunctionHeader() {#a94bbcf6e7814ab7970d3a03436bf2eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::emitFunctionHeader ()</td>
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

<p>This method emits the header for the current function.</p>


<p>EmitFunctionHeader - This method emits the header for the current function.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3e999e4bb7297d284f931638721840e5">llvm::GlobalValue::dropLLVMManglingEscape</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a0580b05cc0794957d4ac1ce2f209ac87">llvm::AsmPrinter::getObjFileLowering</a>, <a href="#a02b6570000092bd33dabbb33f860b51f">isHidden</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ad50f5d7186d7a17abb53860320a2a5b1">llvm::AsmPrinter::isVerbose</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="#a8494156281dfecc4b402ee74a519b5f5">ModuleSectionsEmitted</a>, <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="#a01fb69540ab1d216584a2e2547642384">ST</a>, <a href="#a16044b50a8acbad43bf3655a777a6095">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>

</div>
</div>

### emitGlobalVariable() {#aa88a3ee4331bf05aa38bcb033eb97e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::emitGlobalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
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

<p>Emit the specified global variable to the .s file.</p>


<p>EmitGlobalVariable - Emit the specified global variable to the .s file.</p>


<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>

</div>
</div>

### emitInstruction() {#a8bdba76620eb0f11738a259fe07c0492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *)</td>
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

<p>Targets should implement this to emit instructions.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a95377c6337c8286d00bfd8a2ff437029">emitOpLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aebe7e48735a59049062e384e810c108a">llvm::AsmPrinter::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp/#a4417352a06e1e874494b01798d6ab1bc">isFuncOrHeaderInstr</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#afc4d4a78b2bc398e0b077e77c2838d7f">outputInstruction</a> and <a href="#a16044b50a8acbad43bf3655a777a6095">TII</a>.</p>

</div>
</div>

### emitOpLabel() {#a95377c6337c8286d00bfd8a2ff437029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::emitOpLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a02b6570000092bd33dabbb33f860b51f">isHidden</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#a06a17d03c273bf57b84b3c6dd9bb1efa">emitBasicBlockStart</a> and <a href="#a8bdba76620eb0f11738a259fe07c0492">emitInstruction</a>.</p>

</div>
</div>

### getAnalysisUsage() {#adce8f406f264753a41f5271df4cf0e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>Record analysis usage.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a83d7606b4830b8a51e2b3e12bf83632a">llvm::AsmPrinter::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#a73fa6447d27478aacba7e5800efaa6f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>

</div>
</div>

### isHidden() {#a02b6570000092bd33dabbb33f860b51f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::isHidden ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvutils-h/#a2803bd4e0ee3046106eef7903037ba0d">SPIRV_BACKEND_SERVICE_FUN_NAME</a>.</p>


<p>Referenced by <a href="#a8e4eb9d8bad834b43080dd9f51ba5ba4">emitFunctionBodyEnd</a>, <a href="#a94bbcf6e7814ab7970d3a03436bf2eb4">emitFunctionHeader</a> and <a href="#a95377c6337c8286d00bfd8a2ff437029">emitOpLabel</a>.</p>

</div>
</div>

### outputAnnotations() {#aef83676a470a77d6e089737fb024de94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputAnnotations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7695a0e4d476e4df011486af1bb63e8">llvm::addStringImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bcd261c0da622d37e1c5aeb02496e12">llvm::getConstantStringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2cef054c0c3ca62b709eb640501e0d1ba3c09c5b4b8345d2c1b8ae49e23fdb37a">llvm::SPIRV::MB_Annotations</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a>, <a href="#a9f434349f8430ae84cd072e3bcd6cf6c">outputModuleSection</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a966eb231e7d4e572874d2cb49b18faea">llvm::Value::stripPointerCasts</a>.</p>


<p>Referenced by <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>.</p>

</div>
</div>

### outputDebugSourceAndStrings() {#adac6a6f0dd9ecdd7b774da11940ce88b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputDebugSourceAndStrings (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7695a0e4d476e4df011486af1bb63e8">llvm::addStringImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2cef054c0c3ca62b709eb640501e0d1babcacfbd962adb526fa13d6caa8a3fe3c">llvm::SPIRV::MB_DebugStrings</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a>, <a href="#a9f434349f8430ae84cd072e3bcd6cf6c">outputModuleSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>.</p>

</div>
</div>

### outputEntryPoints() {#a26a1086f0aa442d022ef86a57757ef94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputEntryPoints ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2cef054c0c3ca62b709eb640501e0d1baea37977cca9860f19a9776b4ad6e8db9">llvm::SPIRV::MB_EntryPoints</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a> and <a href="#a01fb69540ab1d216584a2e2547642384">ST</a>.</p>


<p>Referenced by <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>.</p>

</div>
</div>

### outputExecutionMode() {#afc046e9fee2ff69250264feef8baaf15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputExecutionMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp/#a099dfc173455c7f27311d9c9cfa9cd62">addOpsFromMDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp/#abc274f1603cc07b1d85b856d43fae6ac">encodeVecTypeHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5da18dc4025a639cd5ecc7a288f9d31">llvm::getMDOperandAsType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9457afaedec0cec9eec46986b6e20fdb">llvm::isEntryPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="#abc68a425d6211a1b46e2df470bf12439">outputExecutionModeFromMDNode</a>, <a href="#add0594bfc35119c8d898c51bb3697823">outputExecutionModeFromNumthreadsAttribute</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a> and <a href="#a01fb69540ab1d216584a2e2547642384">ST</a>.</p>


<p>Referenced by <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>.</p>

</div>
</div>

### outputExecutionModeFromMDNode() {#abc68a425d6211a1b46e2df470bf12439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputExecutionModeFromMDNode (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Node, SPIRV::ExecutionMode::ExecutionMode EM, unsigned ExpectMDOps, int64_t DefVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp/#a099dfc173455c7f27311d9c9cfa9cd62">addOpsFromMDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#afc046e9fee2ff69250264feef8baaf15">outputExecutionMode</a>.</p>

</div>
</div>

### outputExecutionModeFromNumthreadsAttribute() {#add0594bfc35119c8d898c51bb3697823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputExecutionModeFromNumthreadsAttribute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &amp; Attr, SPIRV::ExecutionMode::ExecutionMode EM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="#afc046e9fee2ff69250264feef8baaf15">outputExecutionMode</a>.</p>

</div>
</div>

### outputExtFuncDecls() {#a22518f296231106bdd60c1d4397965a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputExtFuncDecls ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2cef054c0c3ca62b709eb640501e0d1bad434d9cb6c56f35f9521b2c973790233">llvm::SPIRV::MB_ExtFuncDecls</a>, <a href="#afc4d4a78b2bc398e0b077e77c2838d7f">outputInstruction</a> and <a href="#aa9ff97cd854e60b8561792b2b3fd2d0f">outputOpFunctionEnd</a>.</p>


<p>Referenced by <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>.</p>

</div>
</div>

### outputGlobalRequirements() {#ac9d0742eff167655206896feab35cd4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputGlobalRequirements ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7695a0e4d476e4df011486af1bb63e8">llvm::addStringImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a93d7a87f617e779623a45518a54db3eb">llvm::getSymbolicOperandMnemonic</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a> and <a href="#a01fb69540ab1d216584a2e2547642384">ST</a>.</p>


<p>Referenced by <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>.</p>

</div>
</div>

### outputInstruction() {#afc4d4a78b2bc398e0b077e77c2838d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a>.</p>


<p>Referenced by <a href="#a8bdba76620eb0f11738a259fe07c0492">emitInstruction</a>, <a href="#a22518f296231106bdd60c1d4397965a6">outputExtFuncDecls</a> and <a href="#a9f434349f8430ae84cd072e3bcd6cf6c">outputModuleSection</a>.</p>

</div>
</div>

### outputMCInst() {#abf1b15213fc33c056b83e3892dbb9516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputMCInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>


<p>Referenced by <a href="#a95377c6337c8286d00bfd8a2ff437029">emitOpLabel</a>, <a href="#aef83676a470a77d6e089737fb024de94">outputAnnotations</a>, <a href="#adac6a6f0dd9ecdd7b774da11940ce88b">outputDebugSourceAndStrings</a>, <a href="#a26a1086f0aa442d022ef86a57757ef94">outputEntryPoints</a>, <a href="#afc046e9fee2ff69250264feef8baaf15">outputExecutionMode</a>, <a href="#abc68a425d6211a1b46e2df470bf12439">outputExecutionModeFromMDNode</a>, <a href="#add0594bfc35119c8d898c51bb3697823">outputExecutionModeFromNumthreadsAttribute</a>, <a href="#ac9d0742eff167655206896feab35cd4b">outputGlobalRequirements</a>, <a href="#afc4d4a78b2bc398e0b077e77c2838d7f">outputInstruction</a>, <a href="#a996dc62cedd72ad61d739065da84a232">outputOpExtInstImports</a>, <a href="#aa9ff97cd854e60b8561792b2b3fd2d0f">outputOpFunctionEnd</a> and <a href="#a4f4a667381f5644b8c90d6e9c78642b9">outputOpMemoryModel</a>.</p>

</div>
</div>

### outputModuleSection() {#a9f434349f8430ae84cd072e3bcd6cf6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputModuleSection (SPIRV::ModuleSectionType MSType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#afc4d4a78b2bc398e0b077e77c2838d7f">outputInstruction</a>.</p>


<p>Referenced by <a href="#aef83676a470a77d6e089737fb024de94">outputAnnotations</a>, <a href="#adac6a6f0dd9ecdd7b774da11940ce88b">outputDebugSourceAndStrings</a> and <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>.</p>

</div>
</div>

### outputModuleSections() {#ad666dc94c5ec06121c1cf3a1dc5af34d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputModuleSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvmoduleanalysis/#a05886598201aad1f7d78d80510ea352c">llvm::SPIRVModuleAnalysis::MAI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2cef054c0c3ca62b709eb640501e0d1ba29e82652bcf93f6b3ffe2d4f08ea123b">llvm::SPIRV::MB_DebugModuleProcessed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2cef054c0c3ca62b709eb640501e0d1bab6dfa3080138274f2b58fc615f737ec3">llvm::SPIRV::MB_DebugNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2cef054c0c3ca62b709eb640501e0d1ba5ab9e10ce14abf3ae8cd4cf398e4df1c">llvm::SPIRV::MB_NonSemanticGlobalDI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2cef054c0c3ca62b709eb640501e0d1bab45db00a8b7c110dfe9e2e9be8a1cec1">llvm::SPIRV::MB_TypeConstVars</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa1316da87e093c08b6657877572b19a4">llvm::AsmPrinter::MMI</a>, <a href="#aef83676a470a77d6e089737fb024de94">outputAnnotations</a>, <a href="#adac6a6f0dd9ecdd7b774da11940ce88b">outputDebugSourceAndStrings</a>, <a href="#a26a1086f0aa442d022ef86a57757ef94">outputEntryPoints</a>, <a href="#afc046e9fee2ff69250264feef8baaf15">outputExecutionMode</a>, <a href="#a22518f296231106bdd60c1d4397965a6">outputExtFuncDecls</a>, <a href="#ac9d0742eff167655206896feab35cd4b">outputGlobalRequirements</a>, <a href="#a9f434349f8430ae84cd072e3bcd6cf6c">outputModuleSection</a>, <a href="#a996dc62cedd72ad61d739065da84a232">outputOpExtInstImports</a>, <a href="#a4f4a667381f5644b8c90d6e9c78642b9">outputOpMemoryModel</a>, <a href="#a01fb69540ab1d216584a2e2547642384">ST</a>, <a href="#a16044b50a8acbad43bf3655a777a6095">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>


<p>Referenced by <a href="#a25207d3e0755fe9eb686906a41392b9d">emitEndOfAsmFile</a> and <a href="#a94bbcf6e7814ab7970d3a03436bf2eb4">emitFunctionHeader</a>.</p>

</div>
</div>

### outputOpExtInstImports() {#a996dc62cedd72ad61d739065da84a232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputOpExtInstImports (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7695a0e4d476e4df011486af1bb63e8">llvm::addStringImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45f0630daa0aa1b4eaf43d8bc2d00c0c">llvm::getExtInstSetName</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>.</p>

</div>
</div>

### outputOpFunctionEnd() {#aa9ff97cd854e60b8561792b2b3fd2d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputOpFunctionEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#a8e4eb9d8bad834b43080dd9f51ba5ba4">emitFunctionBodyEnd</a> and <a href="#a22518f296231106bdd60c1d4397965a6">outputExtFuncDecls</a>.</p>

</div>
</div>

### outputOpMemoryModel() {#a4f4a667381f5644b8c90d6e9c78642b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::outputOpMemoryModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#ad36783e2ed7b017039b01da1f894acc1">MAI</a>, <a href="#abf1b15213fc33c056b83e3892dbb9516">outputMCInst</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>.</p>

</div>
</div>

### PrintAsmOperand() {#a146fee6d5d7a1e6d7b4c02fe33e9216b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVAsmPrinter::PrintAsmOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ExtraCode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant.</p>


<p>PrintAsmOperand - Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant.</p>


<p>Targets should override this to format as appropriate. This method can return true if the operand is erroneous.</p>


<p>Targets should override this to format as appropriate for machine specific ExtraCodes or when the arch-independent handling would be too complex otherwise.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a84913da63189f7b4166625f0f01a37e5">printOperand</a>.</p>

</div>
</div>

### printOperand() {#a84913da63189f7b4166625f0f01a37e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::printOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, int OpNum, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a94f5b10f666acf5a0cddd5ac8302d0b8">llvm::MachineOperand::getBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae285dffa957552fa3fe1d34e1bcb7963">llvm::AsmPrinter::GetBlockAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaac6d709ea6a14a69a632a3685936c92">llvm::AsmPrinter::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aee59c647052fc9557561e596681da3c0">llvm::MachineOperand::getFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a0d38ec90351abf4bdf9f903110573ecd">llvm::SPIRVInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1cc134bd22a318835dc929323da70ea4">llvm::MachineBasicBlock::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab59b255f78cd503133d032152a41d105">llvm::MachineOperand::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab313591ae4ea1e3a4ab59121a7dc2a2b">llvm::MachineOperand::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">llvm::MachineOperand::MO_BlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">llvm::MachineOperand::MO_ConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">llvm::MachineOperand::MO_ExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639bac4edc21072344f5aafa2a8f307c78b81">llvm::MachineOperand::MO_FPImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">llvm::MachineOperand::MO_JumpTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">llvm::MachineOperand::MO_MachineBasicBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>.</p>


<p>Referenced by <a href="#a146fee6d5d7a1e6d7b4c02fe33e9216b">PrintAsmOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cleanUp() {#a26b81f0df4aa35dec58dc381e6beb5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVAsmPrinter::cleanUp (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="#a25207d3e0755fe9eb686906a41392b9d">emitEndOfAsmFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MAI {#ad36783e2ed7b017039b01da1f894acc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRV::ModuleAnalysisInfo* anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::MAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="#a8bdba76620eb0f11738a259fe07c0492">emitInstruction</a>, <a href="#a95377c6337c8286d00bfd8a2ff437029">emitOpLabel</a>, <a href="#aef83676a470a77d6e089737fb024de94">outputAnnotations</a>, <a href="#adac6a6f0dd9ecdd7b774da11940ce88b">outputDebugSourceAndStrings</a>, <a href="#a26a1086f0aa442d022ef86a57757ef94">outputEntryPoints</a>, <a href="#afc046e9fee2ff69250264feef8baaf15">outputExecutionMode</a>, <a href="#abc68a425d6211a1b46e2df470bf12439">outputExecutionModeFromMDNode</a>, <a href="#a22518f296231106bdd60c1d4397965a6">outputExtFuncDecls</a>, <a href="#ac9d0742eff167655206896feab35cd4b">outputGlobalRequirements</a>, <a href="#afc4d4a78b2bc398e0b077e77c2838d7f">outputInstruction</a>, <a href="#a9f434349f8430ae84cd072e3bcd6cf6c">outputModuleSection</a>, <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a>, <a href="#a996dc62cedd72ad61d739065da84a232">outputOpExtInstImports</a> and <a href="#a4f4a667381f5644b8c90d6e9c78642b9">outputOpMemoryModel</a>.</p>

</div>
</div>

### ModuleSectionsEmitted {#a8494156281dfecc4b402ee74a519b5f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::ModuleSectionsEmitted</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="#a0ca8b2967965da1d5de352f26a77a7f8">doInitialization</a>, <a href="#a25207d3e0755fe9eb686906a41392b9d">emitEndOfAsmFile</a> and <a href="#a94bbcf6e7814ab7970d3a03436bf2eb4">emitFunctionHeader</a>.</p>

</div>
</div>

### ST {#a01fb69540ab1d216584a2e2547642384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SPIRVSubtarget* anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="#a25207d3e0755fe9eb686906a41392b9d">emitEndOfAsmFile</a>, <a href="#a94bbcf6e7814ab7970d3a03436bf2eb4">emitFunctionHeader</a>, <a href="#a26a1086f0aa442d022ef86a57757ef94">outputEntryPoints</a>, <a href="#afc046e9fee2ff69250264feef8baaf15">outputExecutionMode</a>, <a href="#ac9d0742eff167655206896feab35cd4b">outputGlobalRequirements</a>, <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a> and <a href="#aadf37ee3eeb9b61a6555077dbfb9fe3e">SPIRVAsmPrinter</a>.</p>

</div>
</div>

### TII {#a16044b50a8acbad43bf3655a777a6095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SPIRVInstrInfo* anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="#a94bbcf6e7814ab7970d3a03436bf2eb4">emitFunctionHeader</a>, <a href="#a8bdba76620eb0f11738a259fe07c0492">emitInstruction</a>, <a href="#ad666dc94c5ec06121c1cf3a1dc5af34d">outputModuleSections</a> and <a href="#aadf37ee3eeb9b61a6555077dbfb9fe3e">SPIRVAsmPrinter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LabeledMBB {#acfbebdf28c69925b6bdc0b4c7722d24f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const MachineBasicBlock *, 8&gt; anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::LabeledMBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>

</div>
</div>

### NLabels {#adc493588d05ddcd99f390c48625e7893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::NLabels = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp">SPIRVAsmPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
