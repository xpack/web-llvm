---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Disassembler.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">llvm-c/Disassembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcdisassembler-h">llvm/MC/MCDisassembler/MCDisassembler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcrelocationinfo-h">llvm/MC/MCDisassembler/MCRelocationInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">llvm/MC/MCDisassembler/MCSymbolizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">llvm/MC/MCInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">llvm/MC/MCSchedule.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">llvm/Support/FormattedStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;cassert&gt;
#include &lt;cstring&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a> (LLVMDisasmContext *DC, formatted_raw_ostream &amp;FormattedOS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the comments that are stored in <span class="doxyComputerOutput">DC</span> comment stream. <a href="#a0e50dc982f01eab3eeb5eef624e25f03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7331753737602bb545def2c960c209d">emitLatency</a> (LLVMDisasmContext *DC, const MCInst &amp;Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits latency information in DC-&gt;CommentStream for <span class="doxyComputerOutput">Inst</span>, based on the information available in <span class="doxyComputerOutput">DC</span>. <a href="#ad7331753737602bb545def2c960c209d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a> (const char *Triple, const char *CPU, const char *Features, void *DisInfo, int TagType, LLVMOpInfoCallback GetOpInfo, LLVMSymbolLookupCallback SymbolLookUp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a disassembler for the TripleName, a specific CPU and specific feature string. <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga906d56cff22d17c94cae0c91fa36f6e2">LLVMCreateDisasmCPU</a> (const char *Triple, const char *CPU, void *DisInfo, int TagType, LLVMOpInfoCallback GetOpInfo, LLVMSymbolLookupCallback SymbolLookUp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a disassembler for the TripleName and a specific CPU. <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga906d56cff22d17c94cae0c91fa36f6e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h/#a4789aaabaa5bf3b7a549171b47cc4d4a">LLVM_C_EXTERN_C_BEGIN</a> <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gab2235be6ece819e49dbde7cd52c3a2d8">LLVMCreateDisasm</a> (const char *TripleName, void *DisInfo, int TagType, LLVMOpInfoCallback GetOpInfo, LLVMSymbolLookupCallback SymbolLookUp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a disassembler for the TripleName. <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gab2235be6ece819e49dbde7cd52c3a2d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga15b630b4a386bee86ad5a10ff7592af0">LLVMDisasmDispose</a> (LLVMDisasmContextRef DC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a disassembler context. <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga15b630b4a386bee86ad5a10ff7592af0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a> (LLVMDisasmContextRef DC, uint8_t *Bytes, uint64_t BytesSize, uint64_t PC, char *OutString, size_t OutStringSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disassemble a single instruction using the disassembler context specified in the parameter DC. <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a> (LLVMDisasmContextRef DC, uint64_t Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the disassembler's options. <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### emitComments() {#a0e50dc982f01eab3eeb5eef624e25f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitComments (<a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext">LLVMDisasmContext</a> * DC, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; FormattedOS)</td>
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

<p>Emits the comments that are stored in <span class="doxyComputerOutput">DC</span> comment stream.</p>


<p>Each comment in the comment stream must end with a newline.</p>


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp">Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#aca3253766aa266590e688a23f97ac612">llvm::LLVMDisasmContext::CommentsToEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a4aaa235a27bfb38f0a782db0e5945176">llvm::LLVMDisasmContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ad054eb14ffe126ed3587fd66b4230088">llvm::MCAsmInfo::getCommentColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a83dadee742338c79e561e3efff6ee00a">llvm::MCAsmInfo::getCommentString</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a1fc7f913807a21ba5a42df7cc2d2e748">llvm::formatted_raw_ostream::PadToColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a>.</p>

</div>
</div>

### emitLatency() {#ad7331753737602bb545def2c960c209d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitLatency (<a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext">LLVMDisasmContext</a> * DC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
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

<p>Emits latency information in DC-&gt;CommentStream for <span class="doxyComputerOutput">Inst</span>, based on the information available in <span class="doxyComputerOutput">DC</span>.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp">Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a26ae4b99e4c6cd8620f8603354572a33">llvm::LLVMDisasmContext::CommentStream</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a87b307b08bc0acbbf95fab6bca87983c">llvm::MCSchedModel::computeInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#ad1b025fe9218ff51f65b8d0be826e3db">llvm::LLVMDisasmContext::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a38cda99e294483fa025f4eb57f6544b9">llvm::LLVMDisasmContext::getSubtargetInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
