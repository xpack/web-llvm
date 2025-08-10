---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/winexception
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WinException` Class



## Declaration

<div class="doxyDeclaration">
class llvm::WinException { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">CodeGen/AsmPrinter/WinException.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ehstreamer">EHStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits exception handling directives. <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c131e14aaffab522028a174694b29ad">WinException</a> (AsmPrinter *A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad4b7909b582ecc413ac0ba90f103b34">~WinException</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83914a214e61b299cd1a8ee9a7eade71">endModule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all exception information that should come after the content. <a href="#a83914a214e61b299cd1a8ee9a7eade71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa5422d8ee3dd96aca4513a89a94035">beginFunction</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather pre-function exception information. <a href="#aeaa5422d8ee3dd96aca4513a89a94035">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b2d68aa2cdbb373f491a58dc2a9aed1">markFunctionEnd</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a2af29c117a6bab2aaecaefb17f4d8">endFunction</a> (const MachineFunction *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather and emit post-function exception information. <a href="#a10a2af29c117a6bab2aaecaefb17f4d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a404abd4e71fcd8ee5d5b0277163dda55">beginFunclet</a> (const MachineBasicBlock &amp;MBB, MCSymbol *Sym) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific EH funclet machinery. <a href="#a404abd4e71fcd8ee5d5b0277163dda55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad926330cb107f609d6bdbedb07980e79">endFunclet</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeffe1eee83e8bfedddfa88873f3e2928">emitCSpecificHandlerTable</a> (const MachineFunction *MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the language-specific data that __C_specific_handler expects. <a href="#aeffe1eee83e8bfedddfa88873f3e2928">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f811e5ffec02c8a327ab13ac526389">emitSEHActionsForRange</a> (const WinEHFuncInfo &amp;FuncInfo, const MCSymbol *BeginLabel, const MCSymbol *EndLabel, int State)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4c141aeacc3dc90f19d14dd14647e3">emitCXXFrameHandler3Table</a> (const MachineFunction *MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the EH table data for 32-bit and 64-bit functions using the __CxxFrameHandler3 personality. <a href="#acc4c141aeacc3dc90f19d14dd14647e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b424a881a6309e3b4480224ce15a0c">emitExceptHandlerTable</a> (const MachineFunction *MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the EH table data for _except_handler3 and _except_handler4 personality functions. <a href="#ac7b424a881a6309e3b4480224ce15a0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38666b2d4c409342f9a07c1f57b03c05">emitCLRExceptionTable</a> (const MachineFunction *MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf2127f23e9ee6fe63ea9d0173e64445">computeIP2StateTable</a> (const MachineFunction *MF, const WinEHFuncInfo &amp;FuncInfo, SmallVectorImpl&lt; std::pair&lt; const MCExpr *, int &gt; &gt; &amp;IPToStateTable)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e58e3ed449c0eb19fee71b8012a3e4c">emitEHRegistrationOffsetLabel</a> (const WinEHFuncInfo &amp;FuncInfo, StringRef FLinkageName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the label used with llvm.eh.recoverfp, which is used by outlined funclets. <a href="#a6e58e3ed449c0eb19fee71b8012a3e4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68462b63ec9c220108aa6d6ffd49fd47">create32bitRef</a> (const MCSymbol *Value)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026db2106fa04e523a2fa2b19565a394">create32bitRef</a> (const GlobalValue *GV)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0691bae5a504897759c037a0184462e">getLabel</a> (const MCSymbol *Label)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73b1ed4f89910a10ecae6e81df71baf7">getLabelPlusOne</a> (const MCSymbol *Label)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ad4470c7cf57055324b1c65fc136bd">getOffset</a> (const MCSymbol *OffsetOf, const MCSymbol *OffsetFrom)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49875a5931d8fd3e46ce834ebf5e4ebb">getOffsetPlusOne</a> (const MCSymbol *OffsetOf, const MCSymbol *OffsetFrom)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa31d960ead73596874fa343733c1f924">getFrameIndexOffset</a> (int FrameIndex, const WinEHFuncInfo &amp;FuncInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the offset that we should use in a table for a stack object with the given index. <a href="#aa31d960ead73596874fa343733c1f924">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced3e0b94058dd50fc862d55a4eb6b0f">endFuncletImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe55fa407d95f9e70c2fe28a4e3e9cad">shouldEmitPersonality</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-function flag to indicate if personality info should be emitted. <a href="#abe55fa407d95f9e70c2fe28a4e3e9cad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c68261fdd14500412a16f51069a408">shouldEmitLSDA</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-function flag to indicate if the LSDA should be emitted. <a href="#ae9c68261fdd14500412a16f51069a408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a548fba7149ccb3b227a50b85b176dc4a">shouldEmitMoves</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-function flag to indicate if frame moves info should be emitted. <a href="#a548fba7149ccb3b227a50b85b176dc4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8049cfa227f1a9ea3ae98e8a16c20d40">useImageRel32</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is a 64-bit target and we should use image relative offsets. <a href="#a8049cfa227f1a9ea3ae98e8a16c20d40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d319c75ced62fb57b7fc9399544e759">isAArch64</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we are generating exception handling on Windows for ARM64. <a href="#a0d319c75ced62fb57b7fc9399544e759">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c42e0179fbe5a47abcbf66be2c63a9">isThumb</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we are generating exception handling on Windows for <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> (Thumb). <a href="#af6c42e0179fbe5a47abcbf66be2c63a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acecae7f9f625276926983b3ab3b021">CurrentFuncletEntry</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the current funclet entry BB. <a href="#a6acecae7f9f625276926983b3ab3b021">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ba0b0ea37f606553cc4059ca336abf5">CurrentFuncletTextSection</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The section of the last funclet start. <a href="#a3ba0b0ea37f606553cc4059ca336abf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4523e4d4845a98201ad9c2d08615f8d2">EHContTargets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of symbols to add to the ehcont section. <a href="#a4523e4d4845a98201ad9c2d08615f8d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WinException() {#a9c131e14aaffab522028a174694b29ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinException::WinException (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a> and <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#ae951249a56bafbb7b57c4f571f9b4a3a">llvm::EHStreamer::EHStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WinException() {#aad4b7909b582ecc413ac0ba90f103b34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinException::~WinException ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>


<p>References <a href="#a404abd4e71fcd8ee5d5b0277163dda55">beginFunclet</a>, <a href="#aeaa5422d8ee3dd96aca4513a89a94035">beginFunction</a>, <a href="#ad926330cb107f609d6bdbedb07980e79">endFunclet</a>, <a href="#a10a2af29c117a6bab2aaecaefb17f4d8">endFunction</a>, <a href="#a83914a214e61b299cd1a8ee9a7eade71">endModule</a>, <a href="#a2b2d68aa2cdbb373f491a58dc2a9aed1">markFunctionEnd</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### beginFunclet() {#a404abd4e71fcd8ee5d5b0277163dda55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::beginFunclet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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

<p>Emit target-specific EH funclet machinery.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a5603bcae76f2c812e71b8eecf54a7104">llvm::TargetLoweringObjectFile::getCFIPersonalitySymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp/#ab78e5a2681b144ee04d3e4ae5dbc170e">getMCSymbolForMBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afc617a23fd5e4cce7f2adfc7c2966e1c">llvm::COFF::IMAGE_SYM_CLASS_STATIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120aabbef750c1bc8143f79535ea20699385">llvm::COFF::IMAGE_SYM_DTYPE_FUNCTION</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a8cb51f746d76c12843c38bba07e25377">llvm::EHStreamer::MMI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120af01942289377f5c52c8771699eea5144">llvm::COFF::SCT_COMPLEX_TYPE_SHIFT</a>.</p>


<p>Referenced by <a href="#aeaa5422d8ee3dd96aca4513a89a94035">beginFunction</a> and <a href="#aad4b7909b582ecc413ac0ba90f103b34">~WinException</a>.</p>

</div>
</div>

### beginFunction() {#aeaa5422d8ee3dd96aca4513a89a94035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::beginFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather pre-function exception information.</p>


<p>Assumes being emitted immediately after the function entry point.</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>, <a href="#a404abd4e71fcd8ee5d5b0277163dda55">beginFunclet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3e999e4bb7297d284f931638721840e5">llvm::GlobalValue::dropLLVMManglingEscape</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255af88641d07cb5fdb688ad0d4e78314222">llvm::dwarf::DW_EH_PE_omit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fd81545fc9f10418752ee043f8645f">llvm::MachineFunction::getLandingPads</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a504aef9e44f9b0eb4531479466587ca4">llvm::TargetLoweringObjectFile::getLSDAEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a6a79201edcd6ca5c3159c17b20dfe273">llvm::TargetLoweringObjectFile::getPersonalityEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a11cf771f7f11ea4fdacdbd5420371172">llvm::MachineFunction::getWinEHFuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4a8d56726b9e91d336422a546d126a0f">llvm::MachineFunction::hasWinCFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a53aef6c19072ac0d22e5d5820898733f">llvm::isNoOpWithoutInvoke</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa1d0ce965d5884b3d11d6f26fac012613">llvm::MSVC_X86SEH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>


<p>Referenced by <a href="#aad4b7909b582ecc413ac0ba90f103b34">~WinException</a>.</p>

</div>
</div>

### endFunclet() {#ad926330cb107f609d6bdbedb07980e79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::endFunclet ()</td>
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



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>.</p>


<p>Referenced by <a href="#aad4b7909b582ecc413ac0ba90f103b34">~WinException</a>.</p>

</div>
</div>

### endFunction() {#a10a2af29c117a6bab2aaecaefb17f4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::endFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather and emit post-function exception information.</p>


<p>endFunction - Gather and emit post-function exception information.</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa05b0e25c98ba4300ca28989a35dab72a">llvm::CoreCLR</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac4d1df80ee92d83ebe500f9ed29efc59">llvm::MachineFunction::getCatchretTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aab34bedfd8d86f0adbefe4ae0e708f428">llvm::MSVC_CXX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa5fe2b2d01019e4b6a9828d4b9820a7ce">llvm::MSVC_TableSEH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa1d0ce965d5884b3d11d6f26fac012613">llvm::MSVC_X86SEH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>


<p>Referenced by <a href="#aad4b7909b582ecc413ac0ba90f103b34">~WinException</a>.</p>

</div>
</div>

### endModule() {#a83914a214e61b299cd1a8ee9a7eade71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::endModule ()</td>
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

<p>Emit all exception information that should come after the content.</p>


<p>endModule - Emit all exception information that should come after the content.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a8cb51f746d76c12843c38bba07e25377">llvm::EHStreamer::MMI</a>.</p>


<p>Referenced by <a href="#aad4b7909b582ecc413ac0ba90f103b34">~WinException</a>.</p>

</div>
</div>

### markFunctionEnd() {#a2b2d68aa2cdbb373f491a58dc2a9aed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::markFunctionEnd ()</td>
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



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>.</p>


<p>Referenced by <a href="#aad4b7909b582ecc413ac0ba90f103b34">~WinException</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeIP2StateTable() {#abf2127f23e9ee6fe63ea9d0173e64445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::computeIP2StateTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo">WinEHFuncInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *, int &gt; &gt; &amp; IPToStateTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### create32bitRef() {#a68462b63ec9c220108aa6d6ffd49fd47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * WinException::create32bitRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### create32bitRef() {#a026db2106fa04e523a2fa2b19565a394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * WinException::create32bitRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### emitCLRExceptionTable() {#a38666b2d4c409342f9a07c1f57b03c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::emitCLRExceptionTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 1118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### emitCSpecificHandlerTable() {#aeffe1eee83e8bfedddfa88873f3e2928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::emitCSpecificHandlerTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the language-specific data that __C_specific_handler expects.</p>


<p>This handler lives in the x64 Microsoft C runtime and allows catching or cleaning up after faults with __try, __except, and __finally. The typeinfo values are not really RTTI data, but pointers to filter functions that return an integer (1, 0, or -1) indicating how to handle the exception. For __finally blocks and other cleanups, the landing pad label is zero, and the filter function is actually a cleanup handler with the same prototype. A catch-all entry is modeled with a null filter function field and a non-zero landing pad label.</p>


<p>Possible filter function return values: EXCEPTION_EXECUTE_HANDLER (1): Jump to the landing pad label after cleanups. EXCEPTION_CONTINUE_SEARCH (0): Continue searching this table or continue unwinding. EXCEPTION_CONTINUE_EXECUTION (-1): Resume execution at the trapping PC.</p>


<p>Inferred table structure: struct Table { int NumEntries; struct Entry { imagerel32 LabelStart; // Inclusive imagerel32 LabelEnd; // Exclusive imagerel32 FilterOrFinally; // One means catch-all. imagerel32 LabelLPad; // Zero means __finally. } Entries[NumEntries]; };</p>


<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### emitCXXFrameHandler3Table() {#acc4c141aeacc3dc90f19d14dd14647e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::emitCXXFrameHandler3Table (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the EH table data for 32-bit and 64-bit functions using the __CxxFrameHandler3 personality.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### emitEHRegistrationOffsetLabel() {#a6e58e3ed449c0eb19fee71b8012a3e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::emitEHRegistrationOffsetLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo">WinEHFuncInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FLinkageName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits the label used with llvm.eh.recoverfp, which is used by outlined funclets.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### emitExceptHandlerTable() {#ac7b424a881a6309e3b4480224ce15a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::emitExceptHandlerTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the EH table data for _except_handler3 and _except_handler4 personality functions.</p>


<p>Emit the language-specific data that _except_handler3 and 4 expect.</p>


<p>These are only used on 32-bit and do not use CFI tables.</p>


<p>This is functionally equivalent to the __C_specific_handler table, except it is indexed by state number instead of IP.</p>


<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### emitSEHActionsForRange() {#a44f811e5ffec02c8a327ab13ac526389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::emitSEHActionsForRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo">WinEHFuncInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * BeginLabel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel, int State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### endFuncletImpl() {#aced3e0b94058dd50fc862d55a4eb6b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinException::endFuncletImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### getFrameIndexOffset() {#aa31d960ead73596874fa343733c1f924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WinException::getFrameIndexOffset (int FrameIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo">WinEHFuncInfo</a> &amp; FuncInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the offset that we should use in a table for a stack object with the given index.</p>


<p>For targets using CFI (Win64, etc), this is relative to the established SP at the end of the prologue. For targets without CFI (Win32 only), it is relative to the frame pointer.</p>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### getLabel() {#ad0691bae5a504897759c037a0184462e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * WinException::getLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### getLabelPlusOne() {#a73b1ed4f89910a10ecae6e81df71baf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * WinException::getLabelPlusOne (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### getOffset() {#ac5ad4470c7cf57055324b1c65fc136bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * WinException::getOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * OffsetOf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * OffsetFrom)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### getOffsetPlusOne() {#a49875a5931d8fd3e46ce834ebf5e4ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * WinException::getOffsetPlusOne (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * OffsetOf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * OffsetFrom)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentFuncletEntry {#a6acecae7f9f625276926983b3ab3b021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::WinException::CurrentFuncletEntry = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the current funclet entry BB.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>

</div>
</div>

### CurrentFuncletTextSection {#a3ba0b0ea37f606553cc4059ca336abf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::WinException::CurrentFuncletTextSection = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The section of the last funclet start.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>

</div>
</div>

### EHContTargets {#a4523e4d4845a98201ad9c2d08615f8d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;const MCSymbol *&gt; llvm::WinException::EHContTargets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of symbols to add to the ehcont section.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>

</div>
</div>

### isAArch64 {#a0d319c75ced62fb57b7fc9399544e759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinException::isAArch64 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if we are generating exception handling on Windows for ARM64.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>

</div>
</div>

### isThumb {#af6c42e0179fbe5a47abcbf66be2c63a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinException::isThumb = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if we are generating exception handling on Windows for <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> (Thumb).</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>

</div>
</div>

### shouldEmitLSDA {#ae9c68261fdd14500412a16f51069a408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinException::shouldEmitLSDA = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Per-function flag to indicate if the LSDA should be emitted.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>

</div>
</div>

### shouldEmitMoves {#a548fba7149ccb3b227a50b85b176dc4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinException::shouldEmitMoves = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Per-function flag to indicate if frame moves info should be emitted.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>

</div>
</div>

### shouldEmitPersonality {#abe55fa407d95f9e70c2fe28a4e3e9cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinException::shouldEmitPersonality = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Per-function flag to indicate if personality info should be emitted.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>

</div>
</div>

### useImageRel32 {#a8049cfa227f1a9ea3ae98e8a16c20d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinException::useImageRel32 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this is a 64-bit target and we should use image relative offsets.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-h">WinException.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
