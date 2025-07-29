---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/ve/lvlgen-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LVLGen.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/ve-h">VE.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vesubtarget-h">VESubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-lvlgen-cpp-">anonymous{LVLGen.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-lvlgen-cpp-/lvlgen">LVLGen</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"lvl-gen"</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>(no)&nbsp;&nbsp;&nbsp;  (<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">MBB.getParent</a>()-&gt;getSubtarget&lt;VESubtarget&gt;().getRegisterInfo()-&gt;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>(no))</td>
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

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"lvl-gen"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp">LVLGen.cpp</a>.</p>

</div>
</div>

### RegName {#a0a198e38a5def54ba58bebc655eda8e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RegName(no)&nbsp;&nbsp;&nbsp;  (<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">MBB.getParent</a>()-&gt;getSubtarget&lt;VESubtarget&gt;().getRegisterInfo()-&gt;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>(no))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp">LVLGen.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a299e5debf3d108b71fc6642ecd31e5e7">llvm::SparcTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#abc10c981c4505185b1d517237acaf9c2">llvm::AVRTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ae7573ce36a4dba9654c530165584e450">llvm::HexagonTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a7180fced62e46cab7a499bb2b914057e">llvm::LanaiTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#aae7bdcf65f4ce313299a333956258f10">llvm::LoongArchTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a21a0e970e98d8f88cee991fe790e1fe9">llvm::MipsTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/structs/llvm/pertargetmiparsingstate/#a95472d93916b6dd85bf2aa50d2caa68b">llvm::PerTargetMIParsingState::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a6fae73b0e495a895c3ce49f127bf8ef7">llvm::PPCTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a8c03ac21b9348135d67887e1246f2845">llvm::RISCVTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697cb1debe6ad1be7e59990072185844">llvm::SITargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af4f13984fe50ba9df4f0345922c76639">llvm::SparcTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#ae6cfa37e3a1c1da565288af32dad3e9f">llvm::SystemZTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a349007dec8d5a6ab5e7d338c282003ca">llvm::TargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aefa52d054df295e06e758af765e7dbf4">llvm::VETargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a42f7160579c4a68a75447d21da859821">llvm::X86TargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#a6e3d7579887f71bf2b4cf7def5a3d77b">llvm::logicalview::LVDWARFReader::getRegisterName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#accab5e4c51ff8b8d5f6e4f434d628f5a">getSpecialRegForName</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#af1c454669c5be28c6ce12b84bc5faa28">llvm::PerFunctionMIParsingState::getVRegInfoNamed</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a3f1861e30cebca3c33d71a2e73de0c5b">llvm::GCNTTIImpl::isReadRegisterSourceOfDivergence</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a3e5b6ff75680bf00cdbdfdf9624baca5">llvm::HexagonTargetLowering::LowerEH_LABEL</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aeb9094ce3f495cf3f81c2c7aa6a975f5">llvm::DWARFExpression::prettyPrintRegisterOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c87701e16414a07520790dfd88c52aa">anonymous{ARMAsmParser.cpp}::ARMOperand::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#adfbeadbc6d68319d9559978a6d365e00">anonymous{CSKYAsmParser.cpp}::CSKYOperand::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#af7a7958d8950902186c344eb8162e3ff">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a5c67f50a9eeeeebe54d2cb8393b3d956">anonymous{RISCVAsmParser.cpp}::RISCVOperand::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a0bbac805be0153c6ba2c002e08a77388">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a572727fd88c1b418c895f7140d2f4b58">llvm::printCompactDWARFExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a780f798424b2910363ba4ecef0f2e80d">printFormattedRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a4e3332cd25d363039de05d35a3ac1eef">llvm::AArch64InstPrinter::printMatrixTileVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a5f2fd1af8259132b7f1d061dc1446077">llvm::PPCInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp/#a5658f96977b9cb1730425f3ca3cb305c">printRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a5cdd59ea1c627d04625120cf2986cbbf">llvm::PPCInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/structs/anonymous-lvlgen-cpp-/lvlgen/#a4d8dd4320b10d7e35f44021a4519ab20">anonymous{LVLGen.cpp}::LVLGen::runOnMachineBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a2ddf0f8e0c9ad93a6c3a893df96ef599">llvm::PPC::stripRegisterPrefix</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#af405cf94e28aca3f12c108ff0b858aee">llvm::AMDGPUPALMetadata::toString</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
