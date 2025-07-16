---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mangler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Mangler` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::Mangler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">llvm/IR/Mangler.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c9296fd511eb96bb487befbf5e7cea">getNameWithPrefix</a> (raw_ostream &amp;OS, const GlobalValue *GV, bool CannotUsePrivateLabel) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the appropriate prefix and the specified global variable's name. <a href="#aa1c9296fd511eb96bb487befbf5e7cea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2117656d5c445c2303f7dcf8095f750">getNameWithPrefix</a> (SmallVectorImpl&lt; char &gt; &amp;OutName, const GlobalValue *GV, bool CannotUsePrivateLabel) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21a21f12c3dd76b2ed24a1348d73484">AnonGlobalIDs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We need to give global values the same name every time they are mangled. <a href="#af21a21f12c3dd76b2ed24a1348d73484">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ad1eca7487362ad8eb58d38790d44d8">getNameWithPrefix</a> (raw_ostream &amp;OS, const Twine &amp;GVName, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the appropriate prefix and the specified name as the global variable name. <a href="#a0ad1eca7487362ad8eb58d38790d44d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0111414b44a22750d3d13bbcf015e55">getNameWithPrefix</a> (SmallVectorImpl&lt; char &gt; &amp;OutName, const Twine &amp;GVName, const DataLayout &amp;DL)</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">Mangler.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getNameWithPrefix() {#aa1c9296fd511eb96bb487befbf5e7cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Mangler::getNameWithPrefix (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, bool CannotUsePrivateLabel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the appropriate prefix and the specified global variable's name.</p>


<p>If the global variable doesn't have a name, this fills in a unique name for the global.</p>


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">Mangler.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp">Mangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp/#a6d85315a5388a1fba592fe04ebf36646">addByteCountSuffix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a788ede5201dc9b44e419e9fd2fbb38bf">llvm::GlobalValue::getAliaseeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa5d2c67dadc073dac78224224ee89350">llvm::GlobalValue::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp/#a608b7db33905c3d2bd010323d0da431a">getNameWithPrefixImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp/#aa4e6a2a2e5be7595f63ae2029e14628b">hasByteCountSuffix</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ed4c5535997ad77ffee00f92430b576">llvm::GlobalValue::hasPrivateLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aa73c6ba4efcd37a9afc738793d50b2c9">llvm::Function::hasStructRetAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafde87569738f9e23963e8735f71c33eb">llvm::CallingConv::X86_FastCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cacfa4cc9bcdaefd5e969c258c994052b9">llvm::CallingConv::X86_VectorCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ocamlgcprinter-cpp/#aa776a466c28ef5250df0206206360b8c">EmitCamlGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#ab671a798b9580f337321bc4a8523fe25">llvm::WasmException::endModule</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaac6d709ea6a14a69a632a3685936c92">llvm::AsmPrinter::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a3b63142ca24145028afa3a5bdf3fe7fb">llvm::ExecutionEngine::getMangledName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#ab74a50e826e0105a5a0f724700c5d5c2">llvm::AArch64_MachoTargetObjectFile::getNameWithPrefix</a>, <a href="#ae2117656d5c445c2303f7dcf8095f750">getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ab61c33276b67ea22d0ad922a545ced9a">llvm::TargetLoweringObjectFileCOFF::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a2aa25f7f2b406e074ebced65fa3dd531">llvm::TargetLoweringObjectFileMachO::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#af25263afe4b2685f4571b432ced7d171">llvm::TargetMachine::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#ab9a66732fec3f835f54f4bb8f5388389">llvm::MCJIT::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#aaa9fafc42db7a667c344ce753b989101">GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#a094b53ae338bc1ed10ec35facf8e07b0">llvm::M68kMCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac50c544ca2ade87e7ad0dd6afccdf84c">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a43dd1528c301e983d792f169a209cfaa">llvm::orc::LLJIT::mangle</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/mangleandinterner/#a2503063c99264a98f5380e7fee30209a">llvm::orc::MangleAndInterner::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuopenclenqueuedblocklowering-cpp-/amdgpuopenclenqueuedblocklowering/#ac3eeb5c96b81aa7ad07041b3c20eeb04">anonymous{AMDGPUOpenCLEnqueuedBlockLowering.cpp}::AMDGPUOpenCLEnqueuedBlockLowering::run</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo/#a68e52e8dcf5848c74cb89308b41cff89">llvm::FastISel::CallLoweringInfo::setCallee</a>.</p>

</div>
</div>

### getNameWithPrefix() {#ae2117656d5c445c2303f7dcf8095f750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Mangler::getNameWithPrefix (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; OutName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, bool CannotUsePrivateLabel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">Mangler.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp">Mangler.cpp</a>.</p>


<p>Reference <a href="#aa1c9296fd511eb96bb487befbf5e7cea">getNameWithPrefix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AnonGlobalIDs {#af21a21f12c3dd76b2ed24a1348d73484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const GlobalValue*, unsigned&gt; llvm::Mangler::AnonGlobalIDs</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We need to give global values the same name every time they are mangled.</p>


<p>This keeps track of the number we give to anonymous ones.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">Mangler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getNameWithPrefix() {#a0ad1eca7487362ad8eb58d38790d44d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Mangler::getNameWithPrefix (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; GVName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Print the appropriate prefix and the specified name as the global variable name.</p>


<p>GVName must not be empty.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">Mangler.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp">Mangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp/#a608b7db33905c3d2bd010323d0da431a">getNameWithPrefixImpl</a>.</p>

</div>
</div>

### getNameWithPrefix() {#ae0111414b44a22750d3d13bbcf015e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Mangler::getNameWithPrefix (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; OutName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; GVName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">Mangler.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp">Mangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp/#a608b7db33905c3d2bd010323d0da431a">getNameWithPrefixImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">Mangler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp">Mangler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
