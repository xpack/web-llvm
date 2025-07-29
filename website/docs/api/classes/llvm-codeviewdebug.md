---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeviewdebug
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CodeViewDebug` Class

<p>Collects and handles line tables information in a CodeView format. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CodeViewDebug { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeGen/AsmPrinter/CodeViewDebug.h</a>"
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; CVGlobalVariable, 1 &gt; <a href="#a07efe5183f849457916076ef950fc69b">GlobalVariableList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6445c4921f4b008c84579504a62f1a92">FileToFilepathMapTy</a> = std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> *, std::string &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab66ade790a1858a732cd1df06f65060a">InlinedEntity</a> = <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#ad623a98e1212d4fb4d655e67828066be">DbgValueHistoryMap::InlinedEntity</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3593e4824db4ccf2c7fe22a21922e734">CodeViewDebug</a> (AsmPrinter *AP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435833d0fa51b89ed044e840a28833a0">beginModule</a> (Module *M) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2cbcf1860cebff122bc6c8d2c9b7f9">endModule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section that holds the line table information. <a href="#a9a2cbcf1860cebff122bc6c8d2c9b7f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9defc9f8d2c86141967debd635709d4b">beginInstruction</a> (const MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> beginning of an instruction. <a href="#a9defc9f8d2c86141967debd635709d4b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c01405586751c3fce580c0e2321864">beginFunctionImpl</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather pre-function debug information. <a href="#ae3c01405586751c3fce580c0e2321864">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c1eb0bb9394b39e6edb45ae6a57bfe">endFunctionImpl</a> (const MachineFunction *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather post-function debug information. <a href="#a95c1eb0bb9394b39e6edb45ae6a57bfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d9d41f4c2d4203e0ce2fc8ab58be80">moduleIsInFortran</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the current module is in Fortran. <a href="#a46d9d41f4c2d4203e0ce2fc8ab58be80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad82b87f6cd740a2d76fabcac5cdf507a">switchToDebugSectionForSymbol</a> (const MCSymbol *GVSym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Switch to the appropriate .debug$S section for GVSym. <a href="#ad82b87f6cd740a2d76fabcac5cdf507a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a36a7723e76924ffbe94c9e7e040b4c9c">InlineSite</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3282fb8b82c76531f1738acdc321c6eb">getInlineSite</a> (const DILocation *InlinedAt, const DISubprogram *Inlinee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806f41a647aa8dc1a4c5a56b2364da2b">getFuncIdForSubprogram</a> (const DISubprogram *SP)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6da57c7214ac513b03fe02f4abb32a">calculateRanges</a> (LocalVariable &amp;Var, const DbgValueHistoryMap::Entries &amp;Entries)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc161123cbc40095a6ffac5a3e897420">getFullFilepath</a> (const DIFile *File)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf4e958ea27315767bd0f8665f98a70">maybeRecordFile</a> (const DIFile *F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3955768e7f63078b539bc5d284987d38">maybeRecordLocation</a> (const DebugLoc &amp;DL, const MachineFunction *MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a25047910d3b959df0233d3ed8eb3b">clear</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38d82b05c383c0b2a936619f105d118c">setCurrentSubprogram</a> (const DISubprogram *SP)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95fcaa0ee5a5fc92eee44225d08f9478">emitCodeViewMagicVersion</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the magic version number at the start of a CodeView type or symbol section. <a href="#a95fcaa0ee5a5fc92eee44225d08f9478">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08004a112f1f55ab7037d41eceb78ec6">emitTypeInformation</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c91c4e9761e88d2a09fc0a8de5032d">emitTypeGlobalHashes</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac451a3e8d9492479566dbe85eb0bcc6b">emitObjName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c0059d997558da8cfe711319409dcd">emitCompilerInformation</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aa5c0d8a4612a47ae4ce7631a2ebda9">emitBuildInfo</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac43d6e445cec90dd1357c68a23e48636">emitInlineeLinesSubsection</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21035984db697cc995a5e566a21a54a7">emitDebugInfoForThunk</a> (const Function *GV, FunctionInfo &amp;FI, const MCSymbol *Fn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fec3f5c281250e7fa3ef23cf48c7724">emitDebugInfoForFunction</a> (const Function *GV, FunctionInfo &amp;FI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825f8a01b1fe1360db7eb40abf2de461">emitDebugInfoForRetainedTypes</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2dd43714f9d6b2112e0693a62c6ab90">emitDebugInfoForUDTs</a> (const std::vector&lt; std::pair&lt; std::string, const DIType * &gt; &gt; &amp;UDTs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a163b53c20633408fbe7805c9a7b4b99d">collectDebugInfoForGlobals</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a8093aed0c81945f6abc4d4d41c4a54">emitDebugInfoForGlobals</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c198e2724b9d992be19cfd50bd0edf6">emitGlobalVariableList</a> (ArrayRef&lt; CVGlobalVariable &gt; Globals)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662f781fa403900e1c269ee75e2b8d51">emitConstantSymbolRecord</a> (const DIType *DTy, APSInt &amp;Value, const std::string &amp;QualifiedName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76aa8264cf02ee651db6c62393043a1a">emitDebugInfoForGlobal</a> (const CVGlobalVariable &amp;CVGV)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe45d8a8308ae77703aa4904f91fb6a6">emitStaticConstMemberList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7deb3f5e108e85469c56f28a8bed7566">beginCVSubsection</a> (codeview::DebugSubsectionKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opens a subsection of the given kind in a .debug$S codeview section. <a href="#a7deb3f5e108e85469c56f28a8bed7566">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f34b85d7299b946574a5657e8863aa4">endCVSubsection</a> (MCSymbol *EndLabel)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f9058e4e9615867b35e7bce6727ac5">beginSymbolRecord</a> (codeview::SymbolKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opens a symbol record of the given kind. <a href="#ae2f9058e4e9615867b35e7bce6727ac5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45e0976be6e8ab046ea31abd5c9a8e25">endSymbolRecord</a> (MCSymbol *SymEnd)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5a024243bdf067feb6e1c97832df17c">emitEndSymbolRecord</a> (codeview::SymbolKind EndKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits an S_END, S_INLINESITE_END, or S_PROC_ID_END record. <a href="#ab5a024243bdf067feb6e1c97832df17c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30578a41263693d6a6039d344f56b63b">emitInlinedCallSite</a> (const FunctionInfo &amp;FI, const DILocation *InlinedAt, const InlineSite &amp;Site)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd009dd1e025b6e8eb4f078c9f0a089c">emitInlinees</a> (const SmallSet&lt; codeview::TypeIndex, 1 &gt; &amp;Inlinees)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003c6819f10e2a9f991666fc8c91e60b">collectGlobalVariableInfo</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb017765f49e1b284464876eeac97466">collectVariableInfo</a> (const DISubprogram *SP)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a120e1f7e6e2badb0889dd300385eae38">collectVariableInfoFromMFTable</a> (DenseSet&lt; InlinedEntity &gt; &amp;Processed)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7f65030fcffe90bb7deb7d701f71d0">collectLexicalBlockInfo</a> (SmallVectorImpl&lt; LexicalScope * &gt; &amp;Scopes, SmallVectorImpl&lt; LexicalBlock * &gt; &amp;Blocks, SmallVectorImpl&lt; LocalVariable &gt; &amp;Locals, SmallVectorImpl&lt; CVGlobalVariable &gt; &amp;Globals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience routine for collecting lexical block information for a list of lexical scopes. <a href="#a4e7f65030fcffe90bb7deb7d701f71d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5d637a3cb1445a907e6ba6dc55f521f">collectLexicalBlockInfo</a> (LexicalScope &amp;Scope, SmallVectorImpl&lt; LexicalBlock * &gt; &amp;ParentBlocks, SmallVectorImpl&lt; LocalVariable &gt; &amp;ParentLocals, SmallVectorImpl&lt; CVGlobalVariable &gt; &amp;ParentGlobals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate the lexical blocks and local variable lists of the parent with information about the specified lexical scope. <a href="#ab5d637a3cb1445a907e6ba6dc55f521f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a5023e542e783303650f7bfef2e775">recordLocalVariable</a> (LocalVariable &amp;&amp;Var, const LexicalScope *LS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records information about a local variable in the appropriate scope. <a href="#a67a5023e542e783303650f7bfef2e775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad77d5c1b1638effaad5e3f9699b5664b">emitLocalVariableList</a> (const FunctionInfo &amp;FI, ArrayRef&lt; LocalVariable &gt; Locals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits local variables in the appropriate order. <a href="#ad77d5c1b1638effaad5e3f9699b5664b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e3455bcadb892311acbcaf8ae9dbb96">emitLocalVariable</a> (const FunctionInfo &amp;FI, const LocalVariable &amp;Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits an S_LOCAL record and its associated defined ranges. <a href="#a3e3455bcadb892311acbcaf8ae9dbb96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe49fd9c8f0472692b1d933793800026">emitLexicalBlockList</a> (ArrayRef&lt; LexicalBlock * &gt; Blocks, const FunctionInfo &amp;FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a sequence of lexical block scopes and their children. <a href="#afe49fd9c8f0472692b1d933793800026">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afefabb9ab143caceafb3588c2655ecb4">emitLexicalBlock</a> (const LexicalBlock &amp;Block, const FunctionInfo &amp;FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a lexical block scope and its children. <a href="#afefabb9ab143caceafb3588c2655ecb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a52b12db015bcad0eb4a3dcd3b9449f">getTypeIndex</a> (const DIType *Ty, const DIType *ClassTy=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Translates the <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> to codeview if necessary and returns a type index for it. <a href="#a1a52b12db015bcad0eb4a3dcd3b9449f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac041ddb56a294ba21faa7a468f486589">getTypeIndexForThisPtr</a> (const DIDerivedType *PtrTy, const DISubroutineType *SubroutineTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a9939e242427fdf904fb653354ba016">getTypeIndexForReferenceTo</a> (const DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86f8a0796bb486be003c9f522d07306">getMemberFunctionType</a> (const DISubprogram *SP, const DICompositeType *Class)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d1306e73c3813dac06f00e1ab0ba640">getScopeIndex</a> (const DIScope *Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94e66f0434d81029ea96f2123410b0e2">getVBPTypeIndex</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932c7e9db4b4828274ec62dbdcc33b8c">addToUDTs</a> (const DIType *Ty)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56a9507226e2f8dadb58dfa8ebc8f448">addUDTSrcLine</a> (const DIType *Ty, codeview::TypeIndex TI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb34fb2d4121444e9ca0437fa1650037">lowerType</a> (const DIType *Ty, const DIType *ClassTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b67e42a097c2ba3d24cdd0e99aa307">lowerTypeAlias</a> (const DIDerivedType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c6c92d7bd81a03645b9f6abf0026546">lowerTypeArray</a> (const DICompositeType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60434b7d6756cb5872e2730bf01e4cb7">lowerTypeString</a> (const DIStringType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa707327d4255da7600a76ff88aad6354">lowerTypeBasic</a> (const DIBasicType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167f070c23944345b9fc082e3652f319">lowerTypePointer</a> (const DIDerivedType *Ty, codeview::PointerOptions PO=codeview::PointerOptions::None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa530e09fa6e11419ca4e7c56a87d0a41">lowerTypeMemberPointer</a> (const DIDerivedType *Ty, codeview::PointerOptions PO=codeview::PointerOptions::None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc35dafb406b27039904652035651ad">lowerTypeModifier</a> (const DIDerivedType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85f755f0bff3ea20d56719fa3e5b40ac">lowerTypeFunction</a> (const DISubroutineType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea630c0e067a679e1ee0c2c4a265cae0">lowerTypeVFTableShape</a> (const DIDerivedType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc216d38c95dbed715ea75cbb57a492">lowerTypeMemberFunction</a> (const DISubroutineType *Ty, const DIType *ClassTy, int ThisAdjustment, bool IsStaticMethod, codeview::FunctionOptions FO=codeview::FunctionOptions::None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3584aedf1be62487b1e6873adf3d296">lowerTypeEnum</a> (const DICompositeType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acafc2d8cdf65ce9deed44d79ffa43bf3">lowerTypeClass</a> (const DICompositeType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4588ab2593970aa6dd05ae2912403851">lowerTypeUnion</a> (const DICompositeType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a12b669b29d0de3898a711f47587e86">getCompleteTypeIndex</a> (const DIType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbol records should point to complete types, but type records should always point to incomplete types to avoid cycles in the type graph. <a href="#a3a12b669b29d0de3898a711f47587e86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803ceffbfc1e9621e0a769e3bdb11061">lowerCompleteTypeClass</a> (const DICompositeType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b413f58e81c8e818b0f83392340d0a9">lowerCompleteTypeUnion</a> (const DICompositeType *Ty)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f2cf4a9d26b638a75e834f565542a6">emitDeferredCompleteTypes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all the deferred complete record types. <a href="#ab6f2cf4a9d26b638a75e834f565542a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37663c7c60fcf815d50b66ddc60d7d3e">collectMemberInfo</a> (ClassInfo &amp;Info, const DIDerivedType *DDTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/classinfo">ClassInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ecf59148b1f14a4cfdb5d6ebbcdc734">collectClassInfo</a> (const DICompositeType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a>, unsigned, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107e3fc4a7a4fc5098dd1c4635ff62fe">lowerRecordFieldList</a> (const DICompositeType *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common record member lowering functionality for record types, which are structs, classes, and unions. <a href="#a107e3fc4a7a4fc5098dd1c4635ff62fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad260abb3723f5b7652836c0a6468d1df">recordTypeIndexForDINode</a> (const DINode *Node, codeview::TypeIndex TI, const DIType *ClassTy=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts {{<a href="/web-llvm/docs/api/classes/node">Node</a>, ClassTy}, TI} into TypeIndices and checks for duplicates. <a href="#ad260abb3723f5b7652836c0a6468d1df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d6cb59a20a5984fe20575e840d7dae">collectParentScopeNames</a> (const DIScope *Scope, SmallVectorImpl&lt; StringRef &gt; &amp;ParentScopeNames)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect the names of parent scopes, innermost to outermost. <a href="#a20d6cb59a20a5984fe20575e840d7dae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef455b51284cef2ac656a735c881967">getFullyQualifiedName</a> (const DIScope *Scope, StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99272abcfde867c9f01355e232f17757">getFullyQualifiedName</a> (const DIScope *Scope)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0fc3717160552c46cbe50bdaa440abe">getPointerSizeInBytes</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72442bb4216f793a4a2afc7bb7eea8d9">discoverJumpTableBranches</a> (const MachineFunction *MF, bool isThumb)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aead9d0ef06c0b91ebef7593f7dcc323b">collectDebugInfoForJumpTables</a> (const MachineFunction *MF, bool isThumb)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da8be2613d68c9040238a4c13e89850">emitDebugInfoForJumpTables</a> (const FunctionInfo &amp;FI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea470f64ff5c574ecc58346fa468efc3">OS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c336070f8c7db72470fbc3172a57631">Allocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder">codeview::GlobalTypeTableBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2319e2a982100c5e3bc97402d3e857">TypeTable</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9dcb36748c75a86c627628eedd00931">EmitDebugGlobalHashes</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to emit type record hashes into .debug$H. <a href="#aa9dcb36748c75a86c627628eedd00931">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3a314f44c015362563c5333db978173d">codeview::CPUType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc4921bb78dd00289b12d4d42e4d9395">TheCPU</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The codeview CPU type used by the translation unit. <a href="#abc4921bb78dd00289b12d4d42e4d9395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionInfo *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa7621e015f18909b9991dca64248ab">CurFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af3d64ff2173fb2f45fdc714699cad09f">codeview::SourceLanguage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f72463ac3879db2e59d709d54e9205c">CurrentSourceLanguage</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1247a0103beae201227e42a9d6a882e7">CVGlobalVariableOffsets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; LocalVariable, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69e30a51900d996f41e5fb955dd5b924">ScopeVariables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">GlobalVariableList</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5a05d52426ff015e44633490a070faa">ScopeGlobals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; CVGlobalVariable, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a98b79554efbc76ea0b9b9c9872032">ComdatVariables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; CVGlobalVariable, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a602df68314740742d8af6963a1f3a2a5">GlobalVariables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae532933ba85a4b1692b24299c19e5245">StaticConstMembers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of static const data members to be emitted as S_CONSTANTs. <a href="#ae532933ba85a4b1692b24299c19e5245">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb6963f57d677c6d88b1cd39ed88be7">ComdatDebugSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of comdat .debug$S sections that we've seen so far. <a href="#acfb6963f57d677c6d88b1cd39ed88be7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab61f39c615a9b573d7afcb8eb00a4c34">NextFuncId</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The next available function index for use with our .cv_* directives. <a href="#ab61f39c615a9b573d7afcb8eb00a4c34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, std::unique_ptr&lt; FunctionInfo &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6277d398a761470aa206b8cb5d23ce2e">FnDebugInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remember some debug info about each function. <a href="#a6277d398a761470aa206b8cb5d23ce2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f9cf4bbf3bc2f4ff32a8e335e21133">FileIdMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from full file path to .cv_file id. <a href="#aa7f9cf4bbf3bc2f4ff32a8e335e21133">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7913dee54682e9055eabb99783fc42e9">InlinedSubprograms</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All inlined subprograms in the order they should be emitted. <a href="#a7913dee54682e9055eabb99783fc42e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e358b7d153a9c739e754c592a2780aa">TypeIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from a pair of DI metadata nodes and its DI type (or scope) that can be nullptr, to CodeView type indices. <a href="#a9e358b7d153a9c739e754c592a2780aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c09807f1bbbe96f98627ee534e65fd">CompleteTypeIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from DICompositeType* to complete type index. <a href="#a33c09807f1bbbe96f98627ee534e65fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a63ebc10a286d130d43c6c526c7ae0">DeferredCompleteTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Complete record types to emit after all active type lowerings are finished. <a href="#ad5a63ebc10a286d130d43c6c526c7ae0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0211a5eb4485dd37e607c312f9dac827">TypeEmissionLevel</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of type lowering frames active on the stack. <a href="#a0211a5eb4485dd37e607c312f9dac827">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ade379be9bc81c60e1b2e6c52884879">VBPType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a18c009110cac5812bd002459b2d7d">CurrentSubprogram</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; std::string, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24cb5d2c7db59b2861b86ab94483045b">LocalUDTs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; std::string, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdbda065f36495b9deae13b5f79546ce">GlobalUDTs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">FileToFilepathMapTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a2d65b55bb0d8679fce5a90d84fe51d">FileToFilepathMap</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/codeviewdebug/localvardef">LocalVarDef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0145112bca01eba10b0a16f29c44da3">createDefRangeMem</a> (uint16_t CVRegister, int Offset)</td>
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

<p>Collects and handles line tables information in a CodeView format.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FileToFilepathMapTy {#a6445c4921f4b008c84579504a62f1a92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CodeViewDebug::FileToFilepathMapTy =  std::map&lt;const DIFile *, std::string&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### GlobalVariableList {#a07efe5183f849457916076ef950fc69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVector&lt;CVGlobalVariable, 1&gt; llvm::CodeViewDebug::GlobalVariableList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### InlinedEntity {#ab66ade790a1858a732cd1df06f65060a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CodeViewDebug::InlinedEntity =  DbgValueHistoryMap::InlinedEntity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CodeViewDebug() {#a3593e4824db4ccf2c7fe22a21922e734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewDebug::CodeViewDebug (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * AP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a> and <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a966cbffb61d32a19d00616f851a5eb6e">llvm::DebugHandlerBase::DebugHandlerBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/codeviewdebug/typeloweringscope/#ad5ad95399b04c5c4983f2feaac04079c">llvm::CodeViewDebug::TypeLoweringScope::TypeLoweringScope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### beginInstruction() {#a9defc9f8d2c86141967debd635709d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::beginInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Declaration at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3090 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a99b73ffc5808cd622aa76eeb07fc3e87">llvm::DebugHandlerBase::beginInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#a2868f132b7ec18504f46e056d9826978">isUsableDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#aa57448b6774e5d6264452732dc188388">llvm::DebugHandlerBase::PrevInstBB</a>.</p>

</div>
</div>

### beginModule() {#a435833d0fa51b89ed044e840a28833a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::beginModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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



<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a86397deb1d9d25f7a17ce22c4d66482f">llvm::mdconst::extract_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a882d55a6aa2028e1a5ad708b275334e0">llvm::ConstantInt::isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#a3295ddab65594c464c09f48dede6bef5">mapArchToCVCPUType</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#a2154baa006b2f4e643709dcd0660f2d4">MapDWLangToCVLang</a>.</p>

</div>
</div>

### endModule() {#a9a2cbcf1860cebff122bc6c8d2c9b7f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::endModule ()</td>
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

<p>Emit the <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section that holds the line table information.</p>

<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa5214a8a633c296d1d9d504fc54556692">llvm::codeview::Symbols</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### beginFunctionImpl() {#ae3c01405586751c3fce580c0e2321864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::beginFunctionImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1442 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4b94e0ca517e149914aa0c34ee06c9fa">llvm::MachineFunction::exposesReturnsTwice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aa8c11d016a2dd473a4cf0ed1da777f5ea49320a34b9bc5986bc6081cde3c37f3c">llvm::codeview::FramePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab64be7aad4478fdbd1c73f0ec4dabaf8">llvm::MachineFrameInfo::getCVBytesOfCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ac83b44e69c9f9f4f9d60be2d72f4a5df">llvm::TargetSubtargetInfo::getFrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a60679e554cbf7092c8a0ae6c5db2661a">llvm::MachineFrameInfo::getOffsetAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6f77e4e800ba4dffd63e8ddb330062aa">llvm::Function::getPersonalityFn</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30baa0abac311da1c1659dfef85782d9e97e">llvm::codeview::HasAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30ba208335385809dcc02329f11e1c0b9284">llvm::codeview::HasExceptionHandling</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4070e578614e01d4c3f4aae3df10304c">llvm::MachineFunction::hasInlineAsm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30ba05a6ad49314641af6b0ed93ddd3327e6">llvm::codeview::HasInlineAssembly</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9c38a8cc0a38636c95bd2826de9d72d4">llvm::Function::hasOptNone</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a1c455e007178a24dfb18ac0e200ea02c">llvm::Function::hasOptSize</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6a0f6312963ee6fb0969243607174949">llvm::Function::hasPersonalityFn</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9084ce2576fad285c1c0dc1e165dd4b6">llvm::Function::hasProfileData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30ba43116986d202e3f8199ad58c07c1d604">llvm::codeview::HasSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a29db1a6c4a106d1720101b8d1adf9387">llvm::Function::hasStackProtectorFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac7c993678733273ea9d16db7ff87b2c6">llvm::MachineFrameInfo::hasStackProtectorIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30baa15918513d450f64b12c483365a8935b">llvm::codeview::HasStructuredExceptionHandling</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aaab8110aafc070c83bc701b13d2260df">llvm::Function::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c9fb92464f96c0e0f326d624e82eab">llvm::isAsynchronousEHPersonality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30bad52f2ee95fcec0572e4fa7bf7a1edcf2">llvm::codeview::MarkedInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a3a4faa309dc268374a2b3ea981c47c7b">llvm::DebugHandlerBase::MMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30bafa555455b01d6ff32568479afa1f1947">llvm::codeview::Naked</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aa8c11d016a2dd473a4cf0ed1da777f5ea6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30ba11216ec495bcfd9944befa42a24e5607">llvm::codeview::OptimizedForSpeed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30ba621456a153e476f98c16d5d047c29d2d">llvm::codeview::ProfileGuidedOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#af5173816befd317718323259ef8579cd">llvm::DebugHandlerBase::PrologEndLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#aaffb6bc659419af61a639d756f210137">llvm::DebugHandlerBase::requestLabelAfterInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#ad2b833d5bf85c69d922a140d1a917314">llvm::DebugHandlerBase::requestLabelBeforeInsn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30baeecad675d0daa8ae9766d572efc677a3">llvm::codeview::SafeBuffers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30ba0f155084e79eddf6137226acd7728a0d">llvm::codeview::SecurityChecks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aa8c11d016a2dd473a4cf0ed1da777f5eaf80f5476044d70697d689c8f32415ce9">llvm::codeview::StackPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30baf68e21949fe8601b3c7f49e2bd66d99c">llvm::codeview::StrictSecurityChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad25a1310d512e19d2f6318e963dcb30bad6f6a16b81b59b3fadc499a6d9e33aff">llvm::codeview::ValidProfileCounts</a>.</p>

</div>
</div>

### endFunctionImpl() {#a95c1eb0bb9394b39e6edb45ae6a57bfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::endFunctionImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather post-function debug information.</p>

<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3033 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a1e2d2b34f55d0b4cef8a429f0d5b8e6e">llvm::DebugHandlerBase::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af1350b00e2a02740328dd17b3d2e03d4">llvm::MachineFunction::getCodeViewAnnotations</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a89f0a308af7db83a48443c4512bd3268">llvm::DebugHandlerBase::getLabelAfterInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a369cc2e9b90b5786267c574639d22d3f">llvm::DebugHandlerBase::getLabelBeforeInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#aeaa635647755035e74d272e038b44dcc">llvm::DebugHandlerBase::LScopes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a3a4faa309dc268374a2b3ea981c47c7b">llvm::DebugHandlerBase::MMI</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>.</p>

</div>
</div>

### moduleIsInFortran() {#a46d9d41f4c2d4203e0ce2fc8ab58be80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeViewDebug::moduleIsInFortran ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the current module is in Fortran.</p>

<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af3d64ff2173fb2f45fdc714699cad09facf188d5829c01e2ee3a73de568033728">llvm::codeview::Fortran</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addToUDTs() {#a932c7e9db4b4828274ec62dbdcc33b8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::addToUDTs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1599 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### addUDTSrcLine() {#a56a9507226e2f8dadb58dfa8ebc8f448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::addUDTSrcLine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### beginCVSubsection() {#a7deb3f5e108e85469c56f28a8bed7566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * CodeViewDebug::beginCVSubsection (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2af">codeview::DebugSubsectionKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Opens a subsection of the given kind in a .debug$S codeview section.</p>


<p>Returns an end label for use with endCVSubsection when the subsection is finished.</p>


<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### beginSymbolRecord() {#ae2f9058e4e9615867b35e7bce6727ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * CodeViewDebug::beginSymbolRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">codeview::SymbolKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Opens a symbol record of the given kind.</p>


<p>Returns an end label for use with endSymbolRecord.</p>


<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### calculateRanges() {#a3b6da57c7214ac513b03fe02f4abb32a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::calculateRanges (LocalVariable &amp; Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a55838c99f2c13e8f8f19debd18034f0f">DbgValueHistoryMap::Entries</a> &amp; Entries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### clear() {#a10a25047910d3b959df0233d3ed8eb3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectClassInfo() {#a8ecf59148b1f14a4cfdb5d6ebbcdc734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassInfo CodeViewDebug::collectClassInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectDebugInfoForGlobals() {#a163b53c20633408fbe7805c9a7b4b99d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::collectDebugInfoForGlobals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectDebugInfoForJumpTables() {#aead9d0ef06c0b91ebef7593f7dcc323b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::collectDebugInfoForJumpTables (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, bool isThumb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3495 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectGlobalVariableInfo() {#a003c6819f10e2a9f991666fc8c91e60b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::collectGlobalVariableInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectLexicalBlockInfo() {#a4e7f65030fcffe90bb7deb7d701f71d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::collectLexicalBlockInfo (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * &gt; &amp; Scopes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; LexicalBlock * &gt; &amp; Blocks, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; LocalVariable &gt; &amp; Locals, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; CVGlobalVariable &gt; &amp; Globals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience routine for collecting lexical block information for a list of lexical scopes.</p>

<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2936 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectLexicalBlockInfo() {#ab5d637a3cb1445a907e6ba6dc55f521f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::collectLexicalBlockInfo (<a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> &amp; Scope, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; LexicalBlock * &gt; &amp; ParentBlocks, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; LocalVariable &gt; &amp; ParentLocals, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; CVGlobalVariable &gt; &amp; ParentGlobals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate the lexical blocks and local variable lists of the parent with information about the specified lexical scope.</p>

<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2947 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectMemberInfo() {#a37663c7c60fcf815d50b66ddc60d7d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::collectMemberInfo (<a href="/web-llvm/docs/api/structs/llvm/classinfo">ClassInfo</a> &amp; Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * DDTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectParentScopeNames() {#a20d6cb59a20a5984fe20575e840d7dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DISubprogram * CodeViewDebug::collectParentScopeNames (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; ParentScopeNames)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect the names of parent scopes, innermost to outermost.</p>


<p>Return the innermost subprogram scope if present. Ensure that parent type scopes are inserted into the type table.</p>


<p>Declaration at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectVariableInfo() {#afb017765f49e1b284464876eeac97466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::collectVariableInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### collectVariableInfoFromMFTable() {#a120e1f7e6e2badb0889dd300385eae38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::collectVariableInfoFromMFTable (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; InlinedEntity &gt; &amp; Processed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### discoverJumpTableBranches() {#a72442bb4216f793a4a2afc7bb7eea8d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::discoverJumpTableBranches (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, bool isThumb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3487 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitBuildInfo() {#a1aa5c0d8a4612a47ae4ce7631a2ebda9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitBuildInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 896 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitCodeViewMagicVersion() {#a95fcaa0ee5a5fc92eee44225d08f9478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitCodeViewMagicVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the magic version number at the start of a CodeView type or symbol section.</p>


<p>Appears at the front of every .debug$S or .debug$T or .debug$P section.</p>


<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitCompilerInformation() {#a67c0059d997558da8cfe711319409dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitCompilerInformation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitConstantSymbolRecord() {#a662f781fa403900e1c269ee75e2b8d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitConstantSymbolRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * DTy, <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; QualifiedName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitDebugInfoForFunction() {#a3fec3f5c281250e7fa3ef23cf48c7724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitDebugInfoForFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * GV, FunctionInfo &amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitDebugInfoForGlobal() {#a76aa8264cf02ee651db6c62393043a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitDebugInfoForGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CVGlobalVariable &amp; CVGV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitDebugInfoForGlobals() {#a1a8093aed0c81945f6abc4d4d41c4a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitDebugInfoForGlobals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitDebugInfoForJumpTables() {#a9da8be2613d68c9040238a4c13e89850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitDebugInfoForJumpTables (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FunctionInfo &amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3536 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitDebugInfoForRetainedTypes() {#a825f8a01b1fe1360db7eb40abf2de461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitDebugInfoForRetainedTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitDebugInfoForThunk() {#a21035984db697cc995a5e566a21a54a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitDebugInfoForThunk (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * GV, FunctionInfo &amp; FI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitDebugInfoForUDTs() {#ae2dd43714f9d6b2112e0693a62c6ab90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitDebugInfoForUDTs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::pair&lt; std::string, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * &gt; &gt; &amp; UDTs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitDeferredCompleteTypes() {#ab6f2cf4a9d26b638a75e834f565542a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitDeferredCompleteTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit all the deferred complete record types.</p>


<p>Try to do this in FIFO order, and do this until fixpoint, as each complete record type typically references many other record types.</p>


<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2775 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitEndSymbolRecord() {#ab5a024243bdf067feb6e1c97832df17c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitEndSymbolRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">codeview::SymbolKind</a> EndKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits an S_END, S_INLINESITE_END, or S_PROC_ID_END record.</p>


<p>These records are empty, so we emit them with a simpler assembly sequence that doesn't involve labels.</p>


<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitGlobalVariableList() {#a4c198e2724b9d992be19cfd50bd0edf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitGlobalVariableList (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; CVGlobalVariable &gt; Globals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitInlinedCallSite() {#a30578a41263693d6a6039d344f56b63b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitInlinedCallSite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FunctionInfo &amp; FI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * InlinedAt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a36a7723e76924ffbe94c9e7e040b4c9c">InlineSite</a> &amp; Site)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitInlineeLinesSubsection() {#ac43d6e445cec90dd1357c68a23e48636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitInlineeLinesSubsection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitInlinees() {#abd009dd1e025b6e8eb4f078c9f0a089c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitInlinees (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a>, 1 &gt; &amp; Inlinees)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3566 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitLexicalBlock() {#afefabb9ab143caceafb3588c2655ecb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitLexicalBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LexicalBlock &amp; Block, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FunctionInfo &amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a lexical block scope and its children.</p>


<p>Emit an S_BLOCK32 and S_END record pair delimiting the contents of a lexical block scope.</p>


<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2906 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitLexicalBlockList() {#afe49fd9c8f0472692b1d933793800026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitLexicalBlockList (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; LexicalBlock * &gt; Blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FunctionInfo &amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits a sequence of lexical block scopes and their children.</p>

<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2898 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitLocalVariable() {#a3e3455bcadb892311acbcaf8ae9dbb96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitLocalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FunctionInfo &amp; FI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LocalVariable &amp; Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits an S_LOCAL record and its associated defined ranges.</p>

<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2814 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitLocalVariableList() {#ad77d5c1b1638effaad5e3f9699b5664b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitLocalVariableList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FunctionInfo &amp; FI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; LocalVariable &gt; Locals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits local variables in the appropriate order.</p>

<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2785 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitObjName() {#ac451a3e8d9492479566dbe85eb0bcc6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitObjName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitStaticConstMemberList() {#abe45d8a8308ae77703aa4904f91fb6a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitStaticConstMemberList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitTypeGlobalHashes() {#ad2c91c4e9761e88d2a09fc0a8de5032d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitTypeGlobalHashes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### emitTypeInformation() {#a08004a112f1f55ab7037d41eceb78ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::emitTypeInformation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### endCVSubsection() {#a3f34b85d7299b946574a5657e8863aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::endCVSubsection (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### endSymbolRecord() {#a45e0976be6e8ab046ea31abd5c9a8e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::endSymbolRecord (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * SymEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 3156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getCompleteTypeIndex() {#a3a12b669b29d0de3898a711f47587e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::getCompleteTypeIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Symbol records should point to complete types, but type records should always point to incomplete types to avoid cycles in the type graph.</p>


<p>Only use this entry point when generating symbol records. The complete and incomplete type indices only differ for record types. All other types use the same index.</p>


<p>Declaration at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2701 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getFullFilepath() {#afc161123cbc40095a6ffac5a3e897420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef CodeViewDebug::getFullFilepath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getFullyQualifiedName() {#a4ef455b51284cef2ac656a735c881967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string CodeViewDebug::getFullyQualifiedName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getFullyQualifiedName() {#a99272abcfde867c9f01355e232f17757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string CodeViewDebug::getFullyQualifiedName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getFuncIdForSubprogram() {#a806f41a647aa8dc1a4c5a56b2364da2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::getFuncIdForSubprogram (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getInlineSite() {#a3282fb8b82c76531f1738acdc321c6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewDebug::InlineSite &amp; CodeViewDebug::getInlineSite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * InlinedAt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * Inlinee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getMemberFunctionType() {#ac86f8a0796bb486be003c9f522d07306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::getMemberFunctionType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Class)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getPointerSizeInBytes() {#af0fc3717160552c46cbe50bdaa440abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CodeViewDebug::getPointerSizeInBytes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getScopeIndex() {#a1d1306e73c3813dac06f00e1ab0ba640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::getScopeIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getTypeIndex() {#a1a52b12db015bcad0eb4a3dcd3b9449f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::getTypeIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * ClassTy=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Translates the <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> to codeview if necessary and returns a type index for it.</p>

<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2649 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getTypeIndexForReferenceTo() {#a5a9939e242427fdf904fb653354ba016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::getTypeIndexForReferenceTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2692 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getTypeIndexForThisPtr() {#ac041ddb56a294ba21faa7a468f486589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::TypeIndex CodeViewDebug::getTypeIndexForThisPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * PtrTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> * SubroutineTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2667 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### getVBPTypeIndex() {#a94e66f0434d81029ea96f2123410b0e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::getVBPTypeIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerCompleteTypeClass() {#a803ceffbfc1e9621e0a769e3bdb11061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerCompleteTypeClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerCompleteTypeUnion() {#a2b413f58e81c8e818b0f83392340d0a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerCompleteTypeUnion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2478 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerRecordFieldList() {#a107e3fc4a7a4fc5098dd1c4635ff62fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; TypeIndex, TypeIndex, unsigned, bool &gt; CodeViewDebug::lowerRecordFieldList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common record member lowering functionality for record types, which are structs, classes, and unions.</p>


<p>Returns the field list index and the member count.</p>


<p>Declaration at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerType() {#acb34fb2d4121444e9ca0437fa1650037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * ClassTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1627 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeAlias() {#a96b67e42a097c2ba3d24cdd0e99aa307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeAlias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1678 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeArray() {#a6c6c92d7bd81a03645b9f6abf0026546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeArray (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1694 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeBasic() {#aa707327d4255da7600a76ff88aad6354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeBasic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1771 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeClass() {#acafc2d8cdf65ce9deed44d79ffa43bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2397 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeEnum() {#af3584aedf1be62487b1e6873adf3d296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeEnum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeFunction() {#a85f755f0bff3ea20d56719fa3e5b40ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2034 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeMemberFunction() {#a9bc216d38c95dbed715ea75cbb57a492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeMemberFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * ClassTy, int ThisAdjustment, bool IsStaticMethod, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a819edb1b54a1cf56e9a04ddbb6285947">codeview::FunctionOptions</a> FO=<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a819edb1b54a1cf56e9a04ddbb6285947a6adf97f83acf6453d4a6a4b1070f3754">codeview::FunctionOptions::None</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2063 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeMemberPointer() {#aa530e09fa6e11419ca4e7c56a87d0a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeMemberPointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609f">codeview::PointerOptions</a> PO=<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa6adf97f83acf6453d4a6a4b1070f3754">codeview::PointerOptions::None</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1943 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeModifier() {#a2dc35dafb406b27039904652035651ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeModifier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1977 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypePointer() {#a167f070c23944345b9fc082e3652f319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypePointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609f">codeview::PointerOptions</a> PO=<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa6adf97f83acf6453d4a6a4b1070f3754">codeview::PointerOptions::None</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1872 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeString() {#a60434b7d6756cb5872e2730bf01e4cb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1756 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeUnion() {#a4588ab2593970aa6dd05ae2912403851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeUnion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2463 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### lowerTypeVFTableShape() {#aea630c0e067a679e1ee0c2c4a265cae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::lowerTypeVFTableShape (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 2111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### maybeRecordFile() {#a0bf4e958ea27315767bd0f8665f98a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CodeViewDebug::maybeRecordFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### maybeRecordLocation() {#a3955768e7f63078b539bc5d284987d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::maybeRecordLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### recordLocalVariable() {#a67a5023e542e783303650f7bfef2e775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::recordLocalVariable (LocalVariable &amp;&amp; Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> * LS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records information about a local variable in the appropriate scope.</p>


<p>In particular, locals from inlined code live inside the inlining site.</p>


<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### recordTypeIndexForDINode() {#ad260abb3723f5b7652836c0a6468d1df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex CodeViewDebug::recordTypeIndexForDINode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a> TI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * ClassTy=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts {{<a href="/web-llvm/docs/api/classes/node">Node</a>, ClassTy}, TI} into TypeIndices and checks for duplicates.</p>

<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

### setCurrentSubprogram() {#a38d82b05c383c0b2a936619f105d118c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewDebug::setCurrentSubprogram (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * SP)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### switchToDebugSectionForSymbol() {#ad82b87f6cd740a2d76fabcac5cdf507a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeViewDebug::switchToDebugSectionForSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * GVSym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Switch to the appropriate .debug$S section for GVSym.</p>


<p>If GVSym, the symbol of an emitted global value, is in a comdat <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section, this will switch to a new .debug$S section in that comdat. This method ensures that the section starts with the magic version number on first use. If GVSym is null, uses the main .debug$S section.</p>


<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a9c336070f8c7db72470fbc3172a57631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::CodeViewDebug::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### ComdatDebugSections {#acfb6963f57d677c6d88b1cd39ed88be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;MCSectionCOFF *&gt; llvm::CodeViewDebug::ComdatDebugSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of comdat .debug$S sections that we've seen so far.</p>


<p>Each section must start with a magic version number that must only be emitted once. This set tracks which sections we've already opened.</p>


<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### ComdatVariables {#ab9a98b79554efbc76ea0b9b9c9872032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CVGlobalVariable, 1&gt; llvm::CodeViewDebug::ComdatVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### CompleteTypeIndices {#a33c09807f1bbbe96f98627ee534e65fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DICompositeType *, codeview::TypeIndex&gt; llvm::CodeViewDebug::CompleteTypeIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from DICompositeType* to complete type index.</p>


<p>Non-record types are always looked up in the normal TypeIndices map.</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### CurFn {#a5fa7621e015f18909b9991dca64248ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionInfo* llvm::CodeViewDebug::CurFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### CurrentSourceLanguage {#a1f72463ac3879db2e59d709d54e9205c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::SourceLanguage llvm::CodeViewDebug::CurrentSourceLanguage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af3d64ff2173fb2f45fdc714699cad09fa93f50fe2193ced1d885bf6881db202c1">codeview::SourceLanguage::Masm</a>
</div>
</dd>
</dl>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### CurrentSubprogram {#a80a18c009110cac5812bd002459b2d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DISubprogram* llvm::CodeViewDebug::CurrentSubprogram = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### CVGlobalVariableOffsets {#a1247a0103beae201227e42a9d6a882e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DIGlobalVariable *, uint64_t&gt; llvm::CodeViewDebug::CVGlobalVariableOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### DeferredCompleteTypes {#ad5a63ebc10a286d130d43c6c526c7ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const DICompositeType *, 4&gt; llvm::CodeViewDebug::DeferredCompleteTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Complete record types to emit after all active type lowerings are finished.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### EmitDebugGlobalHashes {#aa9dcb36748c75a86c627628eedd00931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeViewDebug::EmitDebugGlobalHashes = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to emit type record hashes into .debug$H.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### FileIdMap {#aa7f9cf4bbf3bc2f4ff32a8e335e21133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;StringRef, unsigned&gt; llvm::CodeViewDebug::FileIdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from full file path to .cv_file id.</p>


<p>Full paths are built from DIFiles and are stored in FileToFilepathMap;</p>


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### FileToFilepathMap {#a1a2d65b55bb0d8679fce5a90d84fe51d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileToFilepathMapTy llvm::CodeViewDebug::FileToFilepathMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### FnDebugInfo {#a6277d398a761470aa206b8cb5d23ce2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;const Function *, std::unique_ptr&lt;FunctionInfo&gt; &gt; llvm::CodeViewDebug::FnDebugInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remember some debug info about each function.</p>


<p>Keep it in a stable order to emit at the end of the TU.</p>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### GlobalUDTs {#afdbda065f36495b9deae13b5f79546ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;std::string, const DIType *&gt; &gt; llvm::CodeViewDebug::GlobalUDTs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### GlobalVariables {#a602df68314740742d8af6963a1f3a2a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CVGlobalVariable, 1&gt; llvm::CodeViewDebug::GlobalVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### InlinedSubprograms {#a7913dee54682e9055eabb99783fc42e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;const DISubprogram *, 4&gt; llvm::CodeViewDebug::InlinedSubprograms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All inlined subprograms in the order they should be emitted.</p>

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### LocalUDTs {#a24cb5d2c7db59b2861b86ab94483045b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;std::string, const DIType *&gt; &gt; llvm::CodeViewDebug::LocalUDTs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### NextFuncId {#ab61f39c615a9b573d7afcb8eb00a4c34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CodeViewDebug::NextFuncId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The next available function index for use with our .cv_* directives.</p>


<p>Not to be confused with type indices for LF_FUNC_ID records.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### OS {#aea470f64ff5c574ecc58346fa468efc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer&amp; llvm::CodeViewDebug::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### ScopeGlobals {#ac5a05d52426ff015e44633490a070faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DIScope*, std::unique_ptr&lt;GlobalVariableList&gt; &gt; llvm::CodeViewDebug::ScopeGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### ScopeVariables {#a69e30a51900d996f41e5fb955dd5b924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const LexicalScope *, SmallVector&lt;LocalVariable, 1&gt; &gt; llvm::CodeViewDebug::ScopeVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### StaticConstMembers {#ae532933ba85a4b1692b24299c19e5245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const DIDerivedType *, 4&gt; llvm::CodeViewDebug::StaticConstMembers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of static const data members to be emitted as S_CONSTANTs.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### TheCPU {#abc4921bb78dd00289b12d4d42e4d9395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::CPUType llvm::CodeViewDebug::TheCPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The codeview CPU type used by the translation unit.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### TypeEmissionLevel {#a0211a5eb4485dd37e607c312f9dac827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CodeViewDebug::TypeEmissionLevel = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of type lowering frames active on the stack.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### TypeIndices {#a9e358b7d153a9c739e754c592a2780aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const DINode *, const DIType *&gt;, codeview::TypeIndex&gt; llvm::CodeViewDebug::TypeIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from a pair of DI metadata nodes and its DI type (or scope) that can be nullptr, to CodeView type indices.</p>


<p>Primarily indexed by {DIType*, DIType*} and {DISubprogram*, DIType*}.</p>


<p>The second entry in the key is needed for methods as <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> representing static method type are shared with non-method function type.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### TypeTable {#a5b2319e2a982100c5e3bc97402d3e857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::GlobalTypeTableBuilder llvm::CodeViewDebug::TypeTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

### VBPType {#a1ade379be9bc81c60e1b2e6c52884879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::TypeIndex llvm::CodeViewDebug::VBPType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### createDefRangeMem() {#aa0145112bca01eba10b0a16f29c44da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewDebug::LocalVarDef CodeViewDebug::createDefRangeMem (uint16_t CVRegister, int Offset)</td>
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



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a>, definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp">CodeViewDebug.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-h">CodeViewDebug.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
