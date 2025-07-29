---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/codegentargetmachineimpl-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `CodeGenTargetMachineImpl.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegentargetmachineimpl-h">llvm/CodeGen/CodeGenTargetMachineImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/asmprinter-h">llvm/CodeGen/AsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">llvm/CodeGen/BasicTTIImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasmbackend-h">llvm/MC/MCAsmBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeemitter-h">llvm/MC/MCCodeEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">llvm/Support/FormattedStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addeead06865b9438fa8c2b57eecbe876">addPassesToGenerateCode</a> (CodeGenTargetMachineImpl &amp;TM, PassManagerBase &amp;PM, bool DisableVerify, MachineModuleInfoWrapperPass &amp;MMIWP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addPassesToX helper drives creation and initialization of <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a>. <a href="#addeead06865b9438fa8c2b57eecbe876">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a2224b83a83fe88dea533d74fc0dd5">EnableTrapUnreachable</a>("trap-unreachable", cl::Hidden, cl::desc("Enable generating trap for unreachable"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec737c3a60a1737392ee5ad7400f5b49">EnableNoTrapAfterNoreturn</a>("no-trap-after-noreturn", cl::Hidden, cl::desc("Do not emit a trap instruction for 'unreachable' IR instructions " "after noreturn calls, even if --trap-unreachable is set."))</td>
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

## Functions

### addPassesToGenerateCode() {#addeead06865b9438fa8c2b57eecbe876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetPassConfig * addPassesToGenerateCode (<a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl">CodeGenTargetMachineImpl</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM, bool DisableVerify, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowrapperpass">MachineModuleInfoWrapperPass</a> &amp; MMIWP)</td>
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

<p>addPassesToX helper drives creation and initialization of <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a>.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegentargetmachineimpl-cpp">CodeGenTargetMachineImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase/#a2ce2eacfa52640d3a2feb2d46d561b85">llvm::legacy::PassManagerBase::add</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#af5bbe3a77f5ca8c38bb4c24bbd491ff0">llvm::TargetPassConfig::addISelPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ac499270ee3de7c9ef7ca42a4ea82d837">llvm::TargetPassConfig::setDisableVerify</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a11c66344e126e4a01ff3205661bb4b21">llvm::TargetPassConfig::setInitialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a407b9cf0cf2cf2eead54ec1ffac0fa77">llvm::CodeGenTargetMachineImpl::addPassesToEmitFile</a> and <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnableNoTrapAfterNoreturn {#aec737c3a60a1737392ee5ad7400f5b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableNoTrapAfterNoreturn("no-trap-after-noreturn", cl::Hidden, cl::desc("Do not emit a trap instruction for 'unreachable' IR instructions " "after noreturn calls, even if --trap-unreachable is set."))</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegentargetmachineimpl-cpp">CodeGenTargetMachineImpl.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>.</p>

</div>
</div>

### EnableTrapUnreachable {#ae5a2224b83a83fe88dea533d74fc0dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableTrapUnreachable("trap-unreachable", cl::Hidden, cl::desc("Enable generating trap for unreachable"))</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegentargetmachineimpl-cpp">CodeGenTargetMachineImpl.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
