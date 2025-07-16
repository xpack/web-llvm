---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DwarfDebug.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-h">DwarfDebug.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/bytestreamer-h">ByteStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/diehash-h">DIEHash.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-h">DwarfCompileUnit.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexpression-h">DwarfExpression.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfunit-h">DwarfUnit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/asmprinter-h">llvm/CodeGen/AsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">llvm/CodeGen/DIE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">llvm/CodeGen/LexicalScopes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">llvm/DebugInfo/DWARF/DWARFDataExtractor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfexpression-h">llvm/DebugInfo/DWARF/DWARFExpression.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">llvm/MC/MCSection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/machinelocation-h">llvm/MC/MachineLocation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">llvm/Support/MD5.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetloweringobjectfile-h">llvm/Target/TargetLoweringObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;algorithm&gt;
#include &lt;cstddef&gt;
#include &lt;iterator&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include "llvm/BinaryFormat/Dwarf.def"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/fwdregparaminfo">FwdRegParamInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a parameter whose call site value can be described by applying a debug expression to a register in the forwarded register worklist. <a href="/web-llvm/docs/api/structs/fwdregparaminfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/arangespan">ArangeSpan</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d79e0d182dd31455c7e64573f69ae8">FwdRegWorklist</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/fwdregparaminfo">FwdRegParamInfo</a>, 2 &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> worklist for finding call site values. <a href="#a82d79e0d182dd31455c7e64573f69ae8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f83bea317dfeaddd1db751ea4db102">ClobberedRegSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 16 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Container for the set of registers known to be clobbered on the path to a call site. <a href="#a86f83bea317dfeaddd1db751ea4db102">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DefaultOnOff { <a href="#aaf2a32c0f2738e57cac623b73b2c88ab">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LinkageNameOption { <a href="#a3e54c1066c04500fd0af373629ba8836">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb70a75b445652df10364074085b02f4">STATISTIC</a> (NumCSParams, "Number of dbg call site params created")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc">DbgValueLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff31f82e78047b9ec0867b80a925d6df">getDebugLocValue</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get .debug_loc entry for the instruction range starting at MI. <a href="#aff31f82e78047b9ec0867b80a925d6df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c82990aaa735486cf25766512679d77">getFragmentOffsetInBits</a> (const DIExpression &amp;Expr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51f">AccelTableKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0cf9c667fac80b129426688faab9fa0">computeAccelTableKind</a> (unsigned DwarfVersion, bool GenerateTypeUnits, DebuggerKind Tuning, const Triple &amp;TT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01598e7ae0603f525013f0d98f52e8b5">isObjCClass</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e686df7fae332faba14c60600a5110">hasObjCCategory</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affb04f368f98abaa344a09796faf75b1">getObjCClassCategory</a> (StringRef In, StringRef &amp;Class, StringRef &amp;Category)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdfcd6bc2b365e5524d5b8cea4966c3d">getObjCMethodName</a> (StringRef In)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab72c9affbe5b5afe20d98b25fbb1eaea">forBothCUs</a> (DwarfCompileUnit &amp;CU, Func F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca4868511b7a594d12cd9581b9777e9f">combineDIExpressions</a> (const DIExpression *Original, const DIExpression *Addition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the expression <span class="doxyComputerOutput">Addition</span> to <span class="doxyComputerOutput">Original</span> and return the result. <a href="#aca4868511b7a594d12cd9581b9777e9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12d9c2c86e33faf07858a46c4bad9544">finishCallSiteParams</a> (ValT Val, const DIExpression *Expr, ArrayRef&lt; FwdRegParamInfo &gt; DescribedParams, ParamSet &amp;Params)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit call site parameter entries that are described by the given value and debug expression. <a href="#a12d9c2c86e33faf07858a46c4bad9544">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278669a31bed59a4491aa93f70d0606f">addToFwdRegWorklist</a> (FwdRegWorklist &amp;Worklist, unsigned Reg, const DIExpression *Expr, ArrayRef&lt; FwdRegParamInfo &gt; ParamsToAdd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <span class="doxyComputerOutput">Reg</span> to the worklist, if it's not already present, and mark that the given parameter registers' values can (potentially) be described using that register and an debug expression. <a href="#a278669a31bed59a4491aa93f70d0606f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a> (const MachineInstr *CurMI, FwdRegWorklist &amp;ForwardedRegWorklist, ParamSet &amp;Params, ClobberedRegSet &amp;ClobberedRegUnits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interpret values loaded into registers by <span class="doxyComputerOutput">CurMI</span>. <a href="#a88d50bb943ed6d9b7bf0a34367d018af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e190b21eafd467bfcb3cad647c2b3d3">interpretNextInstr</a> (const MachineInstr *CurMI, FwdRegWorklist &amp;ForwardedRegWorklist, ParamSet &amp;Params, ClobberedRegSet &amp;ClobberedRegUnits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a> (const MachineInstr *CallMI, ParamSet &amp;Params)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to interpret values loaded into registers that forward parameters for <span class="doxyComputerOutput">CallMI</span>. <a href="#a5fc63c934f29c38bfba9692a6a2166ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfcompileunit/globalexpr">DwarfCompileUnit::GlobalExpr</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e68958dd4cc9e1c90b0abc432f5b09">sortGlobalExprs</a> (SmallVectorImpl&lt; DwarfCompileUnit::GlobalExpr &gt; &amp;GVEs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort and unique GVEs by comparing their fragment offset. <a href="#a38e68958dd4cc9e1c90b0abc432f5b09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalscope">DILocalScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac285fd5fed8c9963ff45f4aa56c2dc41">getRetainedNodeScope</a> (const MDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1894915deb9e2c5abb856c02fe1513ff">validThroughout</a> (LexicalScopes &amp;LScopes, const MachineInstr *DbgValue, const MachineInstr *RangeEnd, const InstructionOrdering &amp;Ordering)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether a <em>singular</em> DBG_VALUE is valid for the entirety of its enclosing lexical scope. <a href="#a1894915deb9e2c5abb856c02fe1513ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a541bb79da42e4b8f77617678e7f47d83">findPrologueEndLoc</a> (const MachineFunction *MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a783b1f4fedfa3b58e9d2afea56d7664a">recordSourceLine</a> (AsmPrinter &amp;Asm, unsigned Line, unsigned Col, const MDNode *S, unsigned Flags, unsigned CUID, uint16_t DwarfVersion, ArrayRef&lt; std::unique_ptr&lt; DwarfCompileUnit &gt; &gt; DCUs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a source line with debug info. <a href="#a783b1f4fedfa3b58e9d2afea56d7664a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/dwarf/pubindexentrydescriptor">dwarf::PubIndexEntryDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6055a40e65d2916f98811698ce5b4f">computeIndexValue</a> (DwarfUnit *CU, const DIE *Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>computeIndexValue - Compute the gdb index value for the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and <a href="/web-llvm/docs/api/namespaces/cu">CU</a>. <a href="#a4a6055a40e65d2916f98811698ce5b4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69aff64b0c559a54640422a7024e02a9">emitRnglistsTableHeader</a> (AsmPrinter *Asm, const DwarfFile &amp;Holder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac157948fef752ac31b048eb0de2cd6d2">emitLoclistsTableHeader</a> (AsmPrinter *Asm, const DwarfDebug &amp;DD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Ranges, typename PayloadEmitter&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe65683534ca819c702e4eb5f158f387">emitRangeList</a> (DwarfDebug &amp;DD, AsmPrinter *Asm, MCSymbol *Sym, const Ranges &amp;R, const DwarfCompileUnit &amp;CU, unsigned BaseAddressx, unsigned OffsetPair, unsigned StartxLength, unsigned EndOfList, StringRef(*StringifyEnum)(unsigned), bool ShouldUseBaseAddress, PayloadEmitter EmitPayload)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e27b745d3930b5f8bbcf30b919f42ce">emitLocList</a> (DwarfDebug &amp;DD, AsmPrinter *Asm, const DebugLocStream::List &amp;List)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35938fd3189af5f6ef0e2d893b9fd60d">emitRangeList</a> (DwarfDebug &amp;DD, AsmPrinter *Asm, const RangeSpanList &amp;List)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a single range list. We handle both DWARF v5 and earlier. <a href="#a35938fd3189af5f6ef0e2d893b9fd60d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec4510f9b5a8aa0a063d61428e052c96">emitMacroHeader</a> (AsmPrinter *Asm, const DwarfDebug &amp;DD, const DwarfCompileUnit &amp;CU, uint16_t DwarfVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the header of a DWARF 5 macro section, or the GNU extension for DWARF 4. <a href="#aec4510f9b5a8aa0a063d61428e052c96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8681f84cc4b9a200073ea3442657d83a">UseDwarfRangesBaseAddressSpecifier</a>("use-dwarf-ranges-base-address-specifier", cl::Hidden, cl::desc("Use base address specifiers in debug_ranges"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a3cdc6ab7ebefd74bf333be98e35dce">GenerateARangeSection</a>("generate-arange-section", cl::Hidden, cl::desc("Generate dwarf aranges"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a1837e04ee7b0480e6e578824a47801">GenerateDwarfTypeUnits</a>("generate-type-units", cl::Hidden, cl::desc("Generate DWARF4 type units."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f8c37f7db4defd1901dda2096f2daa3">SplitDwarfCrossCuReferences</a>("split-dwarf-cross-cu-references", cl::Hidden, cl::desc("Enable cross-cu references in DWO files"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#aaf2a32c0f2738e57cac623b73b2c88ab">DefaultOnOff</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb76e7c781cf7bf8ed347c7b95133b4f">UnknownLocations</a>("use-unknown-locations", cl::Hidden, cl::desc("Make an absence of debug location information explicit."), cl::values(clEnumVal(Default, "At top of block or after label"), clEnumVal(Enable, "In all cases"), clEnumVal(Disable, "Never")), cl::init(Default))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51f">AccelTableKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5874dc118486a3f1d3e99a347937a34">AccelTables</a>("accel-tables", cl::Hidden, cl::desc("Output dwarf accelerator tables."), cl::values(clEnumValN(AccelTableKind::Default, "Default", "Default for platform"), clEnumValN(AccelTableKind::None, "Disable", "Disabled."), clEnumValN(AccelTableKind::Apple, "Apple", "Apple"), clEnumValN(AccelTableKind::Dwarf, "Dwarf", "DWARF")), cl::init(AccelTableKind::Default))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#aaf2a32c0f2738e57cac623b73b2c88ab">DefaultOnOff</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a169962e34ef6fb9b13f0f8df8df3d182">DwarfInlinedStrings</a>("dwarf-inlined-strings", cl::Hidden, cl::desc("Use inlined strings rather than string section."), cl::values(clEnumVal(Default, "Default for platform"), clEnumVal(Enable, "Enabled"), clEnumVal(Disable, "Disabled")), cl::init(Default))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d71cb3b4b55f18ed1efc9dbc986858c">NoDwarfRangesSection</a>("no-dwarf-ranges-section", cl::Hidden, cl::desc("Disable emission .debug_ranges section."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#aaf2a32c0f2738e57cac623b73b2c88ab">DefaultOnOff</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c2c8281c0f1b5d8d5243444f6ac3470">DwarfSectionsAsReferences</a>("dwarf-sections-as-references", cl::Hidden, cl::desc("Use sections+offset as references rather than labels."), cl::values(clEnumVal(Default, "Default for platform"), clEnumVal(Enable, "Enabled"), clEnumVal(Disable, "Disabled")), cl::init(Default))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12dae658f43e5d9e58d4629af2bd63eb">UseGNUDebugMacro</a>("use-gnu-debug-macro", cl::Hidden, cl::desc("Emit the GNU .debug_macro format with DWARF <5"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#aaf2a32c0f2738e57cac623b73b2c88ab">DefaultOnOff</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4efc5df5d826c7f5b50734466fd555d8">DwarfOpConvert</a>("dwarf-op-convert", cl::Hidden, cl::desc("Enable use of the DWARFv5 DW_OP_convert operator"), cl::values(clEnumVal(Default, "Default for platform"), clEnumVal(Enable, "Enabled"), clEnumVal(Disable, "Disabled")), cl::init(Default))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#a3e54c1066c04500fd0af373629ba8836">LinkageNameOption</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d1a0bf5394df5cd2fa3f1e80b02a19">DwarfLinkageNames</a>("dwarf-linkage-names", cl::Hidden, cl::desc("Which DWARF linkage-name attributes to emit."), cl::values(clEnumValN(DefaultLinkageNames, "Default", "Default for platform"), clEnumValN(AllLinkageNames, "All", "All"), clEnumValN(AbstractLinkageNames, "Abstract", "Abstract subprograms")), cl::init(DefaultLinkageNames))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a535beef0b6ae2e8972ee23458cd7b629">DwarfDebug::MinimizeAddrInV5</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9bd69f105f9c3804beca40d277c43f">MinimizeAddrInV5Option</a>("minimize-addr-in-v5", cl::Hidden, cl::desc("Always use DW_AT_ranges in DWARFv5 whenever it could allow more " "address pool entry sharing to reduce relocations/object size"), cl::values(clEnumValN(DwarfDebug::MinimizeAddrInV5::Default, "Default", "Default address minimization strategy"), clEnumValN(DwarfDebug::MinimizeAddrInV5::Ranges, "Ranges", "Use rnglists for contiguous ranges if that allows " "using a pre-existing base address"), clEnumValN(DwarfDebug::MinimizeAddrInV5::Expressions, "Expressions", "Use exprloc addrx+offset expressions for any " "address with a prior base address"), clEnumValN(DwarfDebug::MinimizeAddrInV5::Form, "Form", "Use addrx+offset extension form for any address " "with a prior base address"), clEnumValN(DwarfDebug::MinimizeAddrInV5::Disabled, "Disabled", "Stuff")), cl::init(DwarfDebug::MinimizeAddrInV5::Default))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9928cc9a0944c203d8eb254cfc5e9ed8">ULEB128PadSize</a> = 4</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"dwarfdebug"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a970e3e524dbb588a227e103d23ed579e">HANDLE_MACRO_FLAG</a>(ID, NAME)&nbsp;&nbsp;&nbsp;MACRO_FLAG_##NAME = ID,</td>
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


<div class="doxySectionDef">

## Typedefs

### ClobberedRegSet {#a86f83bea317dfeaddd1db751ea4db102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ClobberedRegSet =  SmallSet&lt;Register, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Container for the set of registers known to be clobbered on the path to a call site.</p>

<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### FwdRegWorklist {#a82d79e0d182dd31455c7e64573f69ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using FwdRegWorklist =  MapVector&lt;uint64_t, SmallVector&lt;FwdRegParamInfo, 2&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> worklist for finding call site values.</p>

<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DefaultOnOff {#aaf2a32c0f2738e57cac623b73b2c88ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum DefaultOnOff </td>
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
<td class="doxyEnumItemName">Default<a id="aaf2a32c0f2738e57cac623b73b2c88aba79935518a3889663d8688b6b01fff051"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Enable<a id="aaf2a32c0f2738e57cac623b73b2c88aba80cb2080e90221d1f5b425387d9bd030"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Disable<a id="aaf2a32c0f2738e57cac623b73b2c88aba9f306dd8981a103d6827f8b4e80da8aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### LinkageNameOption {#a3e54c1066c04500fd0af373629ba8836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LinkageNameOption </td>
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
<td class="doxyEnumItemName">DefaultLinkageNames<a id="a3e54c1066c04500fd0af373629ba8836a3c914ea6f17fa3943a27cf24c14043ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllLinkageNames<a id="a3e54c1066c04500fd0af373629ba8836a94950d486a1e79b2cd8c2a2ff65abad7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AbstractLinkageNames<a id="a3e54c1066c04500fd0af373629ba8836a41469a0ecc310bbf0a9bf4a43bddacd0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addToFwdRegWorklist() {#a278669a31bed59a4491aa93f70d0606f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addToFwdRegWorklist (<a href="#a82d79e0d182dd31455c7e64573f69ae8">FwdRegWorklist</a> &amp; Worklist, unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/fwdregparaminfo">FwdRegParamInfo</a> &gt; ParamsToAdd)</td>
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

<p>Add <span class="doxyComputerOutput">Reg</span> to the worklist, if it's not already present, and mark that the given parameter registers' values can (potentially) be described using that register and an debug expression.</p>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aca4868511b7a594d12cd9581b9777e9f">combineDIExpressions</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>.</p>

</div>
</div>

### collectCallSiteParameters() {#a5fc63c934f29c38bfba9692a6a2166ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void collectCallSiteParameters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CallMI, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ef71d98aee5d94f5c4046f1bfeb283c">ParamSet</a> &amp; Params)</td>
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

<p>Try to interpret values loaded into registers that forward parameters for <span class="doxyComputerOutput">CallMI</span>.</p>


<p>Store parameters with interpreted value into <span class="doxyComputerOutput">Params</span>.</p>


<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a3a8171298a7d19a309d599de01906703">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#a12d9c2c86e33faf07858a46c4bad9544">finishCallSiteParams</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2b7ecbdbe9013ca2794761934d2bd9">llvm::getBundleEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6f7a9feaea337124196cf22723879cf4">llvm::MachineFunction::getCallSitesInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#ad4bb544993573a6677d97cf5413110c7">llvm::ilist_node_impl&lt; OptionsT &gt;::getReverseIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a996207483728c6ed75938076623eb642">llvm::MachineInstr::hasDelaySlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert</a>, <a href="#a8e190b21eafd467bfcb3cad647c2b3d3">interpretNextInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3949f157e1034f6cb5d16ad708059aa3">llvm::MachineInstr::uses</a>.</p>

</div>
</div>

### combineDIExpressions() {#aca4868511b7a594d12cd9581b9777e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIExpression * combineDIExpressions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Original, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Addition)</td>
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

<p>Append the expression <span class="doxyComputerOutput">Addition</span> to <span class="doxyComputerOutput">Original</span> and return the result.</p>

<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a15f4de7989cc83855e8f65792ae94bc4">llvm::DIExpression::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a9b7e344136f26c673bbd64e6cb88178a">llvm::DIExpression::getElements</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a40cd3c3332ecc579f7a92924714d6d5c">llvm::DIExpression::isImplicit</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a1d0fa3771a3eafd8df26bca2518b5ad7">llvm::ArrayRef&lt; T &gt;::vec</a>.</p>


<p>Referenced by <a href="#a278669a31bed59a4491aa93f70d0606f">addToFwdRegWorklist</a> and <a href="#a12d9c2c86e33faf07858a46c4bad9544">finishCallSiteParams</a>.</p>

</div>
</div>

### computeAccelTableKind() {#ab0cf9c667fac80b129426688faab9fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTableKind computeAccelTableKind (unsigned DwarfVersion, bool GenerateTypeUnits, <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6">DebuggerKind</a> Tuning, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="#af5874dc118486a3f1d3e99a347937a34">AccelTables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fa9f6290f4436e5a2351f12e03b6433c3c">llvm::Apple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fabc5183644c3cfe8d28e144b1518446d9">llvm::Dwarf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6ac45aa7e8859a50c36c0daa43d65d9fa1">llvm::LLDB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7af5fd6eac5e3429291e19a0bc6fd51fa6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### computeIndexValue() {#a4a6055a40e65d2916f98811698ce5b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::PubIndexEntryDescriptor computeIndexValue (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DwarfUnit</a> * CU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Die)</td>
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

<p>computeIndexValue - Compute the gdb index value for the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and <a href="/web-llvm/docs/api/namespaces/cu">CU</a>.</p>

<p>Definition at line 2708 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a008bf8f3472eb0014e766bac06fbe537">llvm::DIE::findAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#aeac16c22ec5a0c13658381144c7e3439">llvm::DIE::getTag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa8b16f5736856a2cf2a7b6760e780496a858e9e297d58ff949a8bb658f235879b">llvm::dwarf::GIEK_FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa8b16f5736856a2cf2a7b6760e780496a1b4daf507f907548e0592207459f397c">llvm::dwarf::GIEK_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa8b16f5736856a2cf2a7b6760e780496a4ef881709af4e033eb6d446b74d6c9da">llvm::dwarf::GIEK_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa8b16f5736856a2cf2a7b6760e780496aecf7ca117030bc2f430f401697840de0">llvm::dwarf::GIEK_VARIABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af7fa49be5f14db1ae78725f042601075abd7dd3283cd836680c9779f0ca7960e8">llvm::dwarf::GIEL_EXTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af7fa49be5f14db1ae78725f042601075ad1eb90c94d024ec52ae1026fc7f3d426">llvm::dwarf::GIEL_STATIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aaedb78de657237c48255243a68e1dbc1">llvm::dwarf::isCPlusPlus</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilfinalizelinkage-cpp/#ae721973516c2b86042a5127b776e2806">Linkage</a>.</p>

</div>
</div>

### emitLocList() {#a8e27b745d3930b5f8bbcf30b919f42ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitLocList (<a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> &amp; DD, <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/debuglocstream/list">DebugLocStream::List</a> &amp; List)</td>
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



<p>Definition at line 3186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#afe65683534ca819c702e4eb5f158f387">emitRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a7d7651181b9b8aaee16273701c1b3e14">llvm::DwarfDebug::getDebugLocs</a>, <a href="/web-llvm/docs/api/classes/llvm/debuglocstream/#a5ccfc50b864ea1f1e82cbc14b251b6f8">llvm::DebugLocStream::getEntries</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga579df9d304fa35f6c02846b389469dd4">llvm::dwarf::LocListEncodingString</a>.</p>

</div>
</div>

### emitLoclistsTableHeader() {#ac157948fef752ac31b048eb0de2cd6d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * emitLoclistsTableHeader (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> &amp; DD)</td>
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



<p>Definition at line 3061 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a7d7651181b9b8aaee16273701c1b3e14">llvm::DwarfDebug::getDebugLocs</a>.</p>

</div>
</div>

### emitMacroHeader() {#aec4510f9b5a8aa0a063d61428e052c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitMacroHeader (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> &amp; DD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU, uint16_t DwarfVersion)</td>
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

<p>Emit the header of a DWARF 5 macro section, or the GNU extension for DWARF 4.</p>

<p>Definition at line 3464 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa578b94a4e307580b4feed7ede93e3af">llvm::DwarfDebug::useSplitDwarf</a>.</p>

</div>
</div>

### emitRangeList() {#afe65683534ca819c702e4eb5f158f387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Ranges, typename PayloadEmitter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitRangeList (<a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> &amp; DD, <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Ranges &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU, unsigned BaseAddressx, unsigned OffsetPair, unsigned StartxLength, unsigned EndOfList, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(*)(unsigned) StringifyEnum, bool ShouldUseBaseAddress, PayloadEmitter EmitPayload)</td>
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



<p>Definition at line 3079 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eea3d516faa526d601aa8b16c176189f1a6">EndOfList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6c58cede6903d5a3190eef36f0e1732e">llvm::DwarfDebug::getAddressPool</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3ace4bbb6f50507e82b0fbec1ee7ea74">llvm::DwarfDebug::getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/addresspool/#a7e7f44ae5cd653026e1d18b9a251fd86">llvm::AddressPool::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa185d37e50840c4efe89db1f96a44540">llvm::DwarfDebug::getSectionLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/groups/debuggertuning/#ga7967d9d5ff2b6b0344d919d2d27965cb">llvm::DwarfDebug::tuneForGDB</a>.</p>


<p>Referenced by <a href="#a8e27b745d3930b5f8bbcf30b919f42ce">emitLocList</a> and <a href="#a35938fd3189af5f6ef0e2d893b9fd60d">emitRangeList</a>.</p>

</div>
</div>

### emitRangeList() {#a35938fd3189af5f6ef0e2d893b9fd60d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitRangeList (<a href="/web-llvm/docs/api/classes/llvm/dwarfdebug">DwarfDebug</a> &amp; DD, <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rangespanlist">RangeSpanList</a> &amp; List)</td>
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

<p>Emit a single range list. We handle both DWARF v5 and earlier.</p>

<p>Definition at line 3412 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="#afe65683534ca819c702e4eb5f158f387">emitRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3ace4bbb6f50507e82b0fbec1ee7ea74">llvm::DwarfDebug::getDwarfVersion</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga01f206798c5c6fc8bf8ee1c8e83e37e4">llvm::dwarf::RangeListEncodingString</a>.</p>

</div>
</div>

### emitRnglistsTableHeader() {#a69aff64b0c559a54640422a7024e02a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * emitRnglistsTableHeader (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarffile">DwarfFile</a> &amp; Holder)</td>
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



<p>Definition at line 3043 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a670be7a4b0b07c446a778eebea56e478">llvm::DwarfFile::getRangeLists</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a7768ffc89068edb9c388c02b96d086cf">llvm::DwarfFile::getRnglistsTableBaseSym</a>.</p>

</div>
</div>

### findPrologueEndLoc() {#a541bb79da42e4b8f77617678e7f47d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const MachineInstr *, bool &gt; findPrologueEndLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Definition at line 2148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9d017af749f76484cb9aec9ff6e4330c">llvm::MachineFunction::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2itblockpass-cpp/#a50d5ffcdff34240e824dc5f8265dc845">isCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ab0627dac3e2666638fa514a2d98299ef">llvm::DwarfDebug::emitInitialLocDirective</a>.</p>

</div>
</div>

### finishCallSiteParams() {#a12d9c2c86e33faf07858a46c4bad9544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void finishCallSiteParams (ValT Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/fwdregparaminfo">FwdRegParamInfo</a> &gt; DescribedParams, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ef71d98aee5d94f5c4046f1bfeb283c">ParamSet</a> &amp; Params)</td>
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

<p>Emit call site parameter entries that are described by the given value and debug expression.</p>

<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aca4868511b7a594d12cd9581b9777e9f">combineDIExpressions</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a1b59c8fe81267b338774bf6c542f90ee">llvm::DIExpression::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a012168d44e49d5120cf8919cd096fd3b">llvm::DIExpression::isEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ad63287a310a4434048a6ee1abeea261e">llvm::DIExpression::isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a> and <a href="#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>.</p>

</div>
</div>

### forBothCUs() {#ab72c9affbe5b5afe20d98b25fbb1eaea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void forBothCUs (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &amp; CU, Func F)</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getDebugLocValue() {#aff31f82e78047b9ec0867b80a925d6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgValueLoc getDebugLocValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Get .debug_loc entry for the instruction range starting at MI.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a854dc7a14b5443f6244301690474c7a0">llvm::DIExpression::convertToNonVariadicExpression</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loc/single/#af4ef98c2f03e123fbe5d26d9b05e979d">llvm::Loc::Single::Single</a>.</p>

</div>
</div>

### getFragmentOffsetInBits() {#a4c82990aaa735486cf25766512679d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getFragmentOffsetInBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> &amp; Expr)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a7cc5f1632a4c520497898439c17dc026">llvm::DIExpression::getFragmentInfo</a>.</p>

</div>
</div>

### getObjCClassCategory() {#affb04f368f98abaa344a09796faf75b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getObjCClassCategory (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> In, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Class, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Category)</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aac3e993fa38b2fd4caaacd62e4e152a4">hasObjCCategory</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3f60785d1dd3859ae53f738c01d366a7">llvm::DwarfDebug::addSubprogramNames</a>.</p>

</div>
</div>

### getObjCMethodName() {#afdfcd6bc2b365e5524d5b8cea4966c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getObjCMethodName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> In)</td>
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



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3f60785d1dd3859ae53f738c01d366a7">llvm::DwarfDebug::addSubprogramNames</a>.</p>

</div>
</div>

### getRetainedNodeScope() {#ac285fd5fed8c9963ff45f4aa56c2dc41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DILocalScope * getRetainedNodeScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N)</td>
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



<p>Definition at line 1515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/discope/#abfb5e80306fec86349d69fd373f83d84">llvm::DIScope::getScope</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a8f0353f65281b2b560d4421d439ed836">llvm::DwarfDebug::endFunctionImpl</a>.</p>

</div>
</div>

### hasObjCCategory() {#ac2e686df7fae332faba14c60600a5110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasObjCCategory (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Reference <a href="#a01598e7ae0603f525013f0d98f52e8b5">isObjCClass</a>.</p>

</div>
</div>

### interpretNextInstr() {#a8e190b21eafd467bfcb3cad647c2b3d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool interpretNextInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CurMI, <a href="#a82d79e0d182dd31455c7e64573f69ae8">FwdRegWorklist</a> &amp; ForwardedRegWorklist, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ef71d98aee5d94f5c4046f1bfeb283c">ParamSet</a> &amp; Params, <a href="#a86f83bea317dfeaddd1db751ea4db102">ClobberedRegSet</a> &amp; ClobberedRegUnits)</td>
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



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a8da97c44f514ad1ae9ccf4518b0f88aa">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3e2f795dfcb9269e1263453796f4b994">llvm::MachineInstr::isBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a>.</p>


<p>Referenced by <a href="#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>.</p>

</div>
</div>

### interpretValues() {#a88d50bb943ed6d9b7bf0a34367d018af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void interpretValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CurMI, <a href="#a82d79e0d182dd31455c7e64573f69ae8">FwdRegWorklist</a> &amp; ForwardedRegWorklist, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ef71d98aee5d94f5c4046f1bfeb283c">ParamSet</a> &amp; Params, <a href="#a86f83bea317dfeaddd1db751ea4db102">ClobberedRegSet</a> &amp; ClobberedRegUnits)</td>
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

<p>Interpret values loaded into registers by <span class="doxyComputerOutput">CurMI</span>.</p>

<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="#a278669a31bed59a4491aa93f70d0606f">addToFwdRegWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a0d7ad8e1022557e52ac17dddf1f5db2f">llvm::SmallSet&lt; T, N, C &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#ae091b147039557cf8ce505740e7ff7ac">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#ac51f13177f0eb63f139dde87ef60a149">llvm::SmallSet&lt; T, N, C &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a3a8171298a7d19a309d599de01906703">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::erase</a>, <a href="#a12d9c2c86e33faf07858a46c4bad9544">finishCallSiteParams</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a8e190b21eafd467bfcb3cad647c2b3d3">interpretNextInstr</a>.</p>

</div>
</div>

### isObjCClass() {#a01598e7ae0603f525013f0d98f52e8b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isObjCClass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3f60785d1dd3859ae53f738c01d366a7">llvm::DwarfDebug::addSubprogramNames</a> and <a href="#ac2e686df7fae332faba14c60600a5110">hasObjCCategory</a>.</p>

</div>
</div>

### recordSourceLine() {#a783b1f4fedfa3b58e9d2afea56d7664a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void recordSourceLine (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp; Asm, unsigned Line, unsigned Col, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * S, unsigned Flags, unsigned CUID, uint16_t DwarfVersion, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DwarfCompileUnit</a> &gt; &gt; DCUs)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a source line with debug info.</p>


<p>Returns the unique label that was emitted and which provides correspondence to the source line list.</p>


<p>Definition at line 2272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### sortGlobalExprs() {#a38e68958dd4cc9e1c90b0abc432f5b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; DwarfCompileUnit::GlobalExpr &gt; &amp; sortGlobalExprs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfcompileunit/globalexpr">DwarfCompileUnit::GlobalExpr</a> &gt; &amp; GVEs)</td>
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

<p>Sort and unique GVEs by comparing their fragment offset.</p>

<p>Definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a48f85da577c6ce7d9aed90437dc0d07c">llvm::unique</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a3f59a82f48553634ac4625cb8166071e">llvm::DwarfDebug::beginModule</a>.</p>

</div>
</div>

### STATISTIC() {#afb70a75b445652df10364074085b02f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCSParams, "Number of dbg call site params created")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### validThroughout() {#a1894915deb9e2c5abb856c02fe1513ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool validThroughout (<a href="/web-llvm/docs/api/classes/llvm/lexicalscopes">LexicalScopes</a> &amp; LScopes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DbgValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * RangeEnd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructionordering">InstructionOrdering</a> &amp; Ordering)</td>
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

<p>Determine whether a <em>singular</em> DBG_VALUE is valid for the entirety of its enclosing lexical scope.</p>


<p>The check ensures there are no other instructions in the same lexical scope preceding the DBG_VALUE and that its range is either open or otherwise rolls off the end of the scope.</p>


<p>Definition at line 1596 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscopes/#a3245044b58379359df4673c0ed9308b0">llvm::LexicalScopes::findLexicalScope</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope/#a4f977132f8ef94fe76347543705ad47b">llvm::LexicalScope::getRanges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AccelTables {#af5874dc118486a3f1d3e99a347937a34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; AccelTableKind &gt; AccelTables("accel-tables", cl::Hidden, cl::desc("Output dwarf accelerator tables."), cl::values(clEnumValN(AccelTableKind::Default, "Default", "Default for platform"), clEnumValN(AccelTableKind::None, "Disable", "Disabled."), clEnumValN(AccelTableKind::Apple, "Apple", "Apple"), clEnumValN(AccelTableKind::Dwarf, "Dwarf", "DWARF")), cl::init(AccelTableKind::Default))</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="#ab0cf9c667fac80b129426688faab9fa0">computeAccelTableKind</a>.</p>

</div>
</div>

### DwarfInlinedStrings {#a169962e34ef6fb9b13f0f8df8df3d182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; DefaultOnOff &gt; DwarfInlinedStrings("dwarf-inlined-strings", cl::Hidden, cl::desc("Use inlined strings rather than string section."), cl::values(clEnumVal(Default, "Default for platform"), clEnumVal(Enable, "Enabled"), clEnumVal(Disable, "Disabled")), cl::init(Default))</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### DwarfLinkageNames {#a25d1a0bf5394df5cd2fa3f1e80b02a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; LinkageNameOption &gt; DwarfLinkageNames("dwarf-linkage-names", cl::Hidden, cl::desc("Which DWARF linkage-name attributes to emit."), cl::values(clEnumValN(DefaultLinkageNames, "Default", "Default for platform"), clEnumValN(AllLinkageNames, "All", "All"), clEnumValN(AbstractLinkageNames, "Abstract", "Abstract subprograms")), cl::init(DefaultLinkageNames))</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### DwarfOpConvert {#a4efc5df5d826c7f5b50734466fd555d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; DefaultOnOff &gt; DwarfOpConvert("dwarf-op-convert", cl::Hidden, cl::desc("Enable use of the DWARFv5 DW_OP_convert operator"), cl::values(clEnumVal(Default, "Default for platform"), clEnumVal(Enable, "Enabled"), clEnumVal(Disable, "Disabled")), cl::init(Default))</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### DwarfSectionsAsReferences {#a9c2c8281c0f1b5d8d5243444f6ac3470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; DefaultOnOff &gt; DwarfSectionsAsReferences("dwarf-sections-as-references", cl::Hidden, cl::desc("Use sections+offset as references rather than labels."), cl::values(clEnumVal(Default, "Default for platform"), clEnumVal(Enable, "Enabled"), clEnumVal(Disable, "Disabled")), cl::init(Default))</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### GenerateARangeSection {#a1a3cdc6ab7ebefd74bf333be98e35dce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; GenerateARangeSection("generate-arange-section", cl::Hidden, cl::desc("Generate dwarf aranges"), cl::init(false))</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### GenerateDwarfTypeUnits {#a2a1837e04ee7b0480e6e578824a47801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; GenerateDwarfTypeUnits("generate-type-units", cl::Hidden, cl::desc("Generate DWARF4 type units."), cl::init(false))</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### MinimizeAddrInV5Option {#afd9bd69f105f9c3804beca40d277c43f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; DwarfDebug::MinimizeAddrInV5 &gt; MinimizeAddrInV5Option("minimize-addr-in-v5", cl::Hidden, cl::desc("Always use DW_AT_ranges in DWARFv5 whenever it could allow more " "address pool entry sharing to reduce relocations/object size"), cl::values(clEnumValN(DwarfDebug::MinimizeAddrInV5::Default, "Default", "Default address minimization strategy"), clEnumValN(DwarfDebug::MinimizeAddrInV5::Ranges, "Ranges", "Use rnglists for contiguous ranges if that allows " "using a pre-existing base address"), clEnumValN(DwarfDebug::MinimizeAddrInV5::Expressions, "Expressions", "Use exprloc addrx+offset expressions for any " "address with a prior base address"), clEnumValN(DwarfDebug::MinimizeAddrInV5::Form, "Form", "Use addrx+offset extension form for any address " "with a prior base address"), clEnumValN(DwarfDebug::MinimizeAddrInV5::Disabled, "Disabled", "Stuff")), cl::init(DwarfDebug::MinimizeAddrInV5::Default))</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### NoDwarfRangesSection {#a0d71cb3b4b55f18ed1efc9dbc986858c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; NoDwarfRangesSection("no-dwarf-ranges-section", cl::Hidden, cl::desc("Disable emission .debug_ranges section."), cl::init(false))</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

### SplitDwarfCrossCuReferences {#a7f8c37f7db4defd1901dda2096f2daa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SplitDwarfCrossCuReferences("split-dwarf-cross-cu-references", cl::Hidden, cl::desc("Enable cross-cu references in DWO files"), cl::init(false))</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a84d7b74e02d1e0dc4a555a18ad536f47">llvm::DwarfDebug::shareAcrossDWOCUs</a>.</p>

</div>
</div>

### ULEB128PadSize {#a9928cc9a0944c203d8eb254cfc5e9ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ULEB128PadSize = 4</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apbytestreamer/#a18d4f175c48ba5f43fdb4a7086c504ab">llvm::APByteStreamer::emitDIERef</a> and <a href="/web-llvm/docs/api/classes/llvm/bufferbytestreamer/#a2e002ff1d0adbc0cbf4d70cfbee67145">llvm::BufferByteStreamer::emitDIERef</a>.</p>

</div>
</div>

### UnknownLocations {#adb76e7c781cf7bf8ed347c7b95133b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; DefaultOnOff &gt; UnknownLocations("use-unknown-locations", cl::Hidden, cl::desc("Make an absence of debug location information explicit."), cl::values(clEnumVal(Default, "At top of block or after label"), clEnumVal(Enable, "In all cases"), clEnumVal(Disable, "Never")), cl::init(Default))</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a>.</p>

</div>
</div>

### UseDwarfRangesBaseAddressSpecifier {#a8681f84cc4b9a200073ea3442657d83a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseDwarfRangesBaseAddressSpecifier("use-dwarf-ranges-base-address-specifier", cl::Hidden, cl::desc("Use base address specifiers in debug_ranges"), cl::init(false))</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### UseGNUDebugMacro {#a12dae658f43e5d9e58d4629af2bd63eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseGNUDebugMacro("use-gnu-debug-macro", cl::Hidden, cl::desc("Emit the GNU .debug_macro format with DWARF &lt;5"), cl::init(false))</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"dwarfdebug"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

### HANDLE\_MACRO\_FLAG {#a970e3e524dbb588a227e103d23ed579e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_MACRO_FLAG(ID, NAME)&nbsp;&nbsp;&nbsp;MACRO_FLAG_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp">DwarfDebug.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
