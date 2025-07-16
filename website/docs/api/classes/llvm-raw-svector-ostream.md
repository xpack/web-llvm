---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/raw-svector-ostream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `raw_svector_ostream` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to an <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> or <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::raw_svector_ostream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract base class for streams implementations that also support a pwrite operation. <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/buffer-ostream">buffer_ostream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/buffer-unique-ostream">buffer_unique_ostream</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5de2c3f4305e6a5f5a6076e5f60c7d7">raw_svector_ostream</a> (SmallVectorImpl&lt; char &gt; &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a new <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a>. <a href="#ac5de2c3f4305e6a5f5a6076e5f60c7d7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608256c456ebe57962adb677b8b7ed33">~raw_svector_ostream</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a945fc289b91d41a778681bc1ca63ce39">flush</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c2cac84e46d3e744aeca03dd3d557d1">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> for the vector contents. <a href="#a9c2cac84e46d3e744aeca03dd3d557d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df873fe46e3433cb3e5167d7f65f050">buffer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bec39d1b2d114ce2a7f131314c2254">reserveExtraSpace</a> (uint64_t ExtraSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If possible, pre-allocate <span class="doxyComputerOutput">ExtraSize</span> bytes for stream data. <a href="#a94bec39d1b2d114ce2a7f131314c2254">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4192d1b5ef282aa946f9713f7c55af13">write_impl</a> (const char *Ptr, size_t Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See raw_ostream::write_impl. <a href="#a4192d1b5ef282aa946f9713f7c55af13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656015c4c12ebed7c1aa201d9a068336">pwrite_impl</a> (const char *Ptr, size_t Size, uint64_t Offset) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4508ceb2b855cc9ff49deb4958f7bc">current_pos</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current position within the stream. <a href="#aae4508ceb2b855cc9ff49deb4958f7bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247c534080a44b70bce0cbde1f08cbbd">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e906e81aeac5d3671d26f966492f7ae">classof</a> (const raw_ostream *OS)</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to an <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> or <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>.</p>


<p>This is a simple adaptor class. This class does not encounter output errors. <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a> operates without a buffer, delegating all memory management to the <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>. Thus the <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> is always up-to-date, may be used directly and there is no need to call <a href="#a945fc289b91d41a778681bc1ca63ce39">flush()</a>.</p>


<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### raw\_svector\_ostream() {#ac5de2c3f4305e6a5f5a6076e5f60c7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_svector_ostream::raw_svector_ostream (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; O)</td>
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

<p>Construct a new <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The vector to write to; this should generally have at least 128 bytes free to avoid any extraneous memory overhead.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43a091bc9597603430daadbc899a42f6408">llvm::raw_ostream::OK_SVecStream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream/#a6114ce21446653490e1d609d876b42eb">llvm::raw_pwrite_stream::raw_pwrite_stream</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a75860636a752bc2592f6e4185e63efdc">llvm::raw_ostream::SetUnbuffered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/buffer-ostream/#a1a1840cb1b58f0477e5dc2e188308b79">llvm::buffer_ostream::buffer_ostream</a> and <a href="/web-llvm/docs/api/classes/llvm/buffer-unique-ostream/#a1975b37ec428a6bc633e879615bc568e">llvm::buffer_unique_ostream::buffer_unique_ostream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~raw\_svector\_ostream() {#a608256c456ebe57962adb677b8b7ed33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_svector_ostream::~raw_svector_ostream ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buffer() {#a7df873fe46e3433cb3e5167d7f65f050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; char &gt; &amp; llvm::raw_svector_ostream::buffer ()</td>
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



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### flush() {#a945fc289b91d41a778681bc1ca63ce39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_svector_ostream::flush ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### reserveExtraSpace() {#a94bec39d1b2d114ce2a7f131314c2254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_svector_ostream::reserveExtraSpace (uint64_t ExtraSize)</td>
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

<p>If possible, pre-allocate <span class="doxyComputerOutput">ExtraSize</span> bytes for stream data.</p>


<p>i.e. it extends internal buffers to keep additional ExtraSize bytes. So that the stream could keep at least <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">tell()</a> + ExtraSize bytes without re-allocations. <a href="#a94bec39d1b2d114ce2a7f131314c2254">reserveExtraSpace()</a> does not change the size/data of the stream.</p>


<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>

</div>
</div>

### str() {#a9c2cac84e46d3e744aeca03dd3d557d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::raw_svector_ostream::str ()</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> for the vector contents.</p>

<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/moduloscheduletestannotater/#a20dd6e00191a092f48bd5598b8829bb3">llvm::ModuloScheduleTestAnnotater::annotate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5443261ddc0795520b7c673e11af38f3">llvm::ComputeASanStackFrameDescription</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a67ae1ad562dccec0023641ab0e8fc48e">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::emitAttributeIfNotDefaultAfterClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ad62d119b377197260380bd8b53325375">emitDebugLabelComment</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#afa88bfe9ae2423322c5a88908de8ba22">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfFile0Directive</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#ac60cbf99d76cbbbbc3c094a7d78fb834">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::emitFrameDataRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a5f897499fea3f1a9fbb5c0fb2a363a20">llvm::GlobalMergeFunc::emitFunctionMap</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a20b936baf69fee8842582ca2ee924545">llvm::AMDGPUAsmPrinter::emitImplicitDef</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a82021d3572d66c5a53dd13c8ee5f0c71">llvm::AsmPrinter::emitImplicitDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#acdf3f4cb6342e67c42191cf29984df97">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetasmstreamer/#a3bed684acd63359143ccec5b37ccd397">llvm::XtensaTargetAsmStreamer::emitLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac4b91d37e671f74e4a67bef3ed4577f7">llvm::MCTargetStreamer::emitRawBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetstreamer/#a89b1d9f2451a16b36cb2ae1a3e335433">llvm::NVPTXTargetStreamer::emitRawBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae9c7bfbd6f1a6b08ebabb1ca16be3d7e">llvm::MCStreamer::emitSLEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#a46c66115be8a99f00d13569a94ae0678">llvm::MCTargetStreamer::emitValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a69996d98ab94d8335d082aabd9b1c12a">llvm::AMDGPU::generateCrashCode</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a63bdece47c81d3a6e63de19cb824b788">llvm::opt::Arg::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a9b5fd69cbe234f56395e6ddd4eeed8be">llvm::BlockFrequencyInfoImplBase::getBlockFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a79042b23c1c0edaae51e255486932cbb">llvm::AMDGPUMangledLibFunc::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/vecdesc/#a868d48926750a8df18b5c6d5463d4028">llvm::VecDesc::getVectorFunctionABIVariantString</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#gaaa9ce583969eb8754512e70ec4b80061">LLVMTargetMachineEmitToMemoryBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#adec0e730f80de19f31127faedf39008c">llvm::ExecutionEngine::LoadValueFromMemory</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#a858b2d1d8e8f50fb043e650fb6197d91">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::manifest</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#afaaaf7da6379fe3994da86bf71024ddc">anonymous{AsmParser.cpp}::AsmParser::parseAndMatchAndEmitTargetInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a7bc472aa7f200453c2fb1d5fbc404b66">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::populateSwMetadataGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3a4e8a88439506522a2a0f3850802d3f">llvm::Pattern::printSubstitutions</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a91f729b936911342abb6b606e0606cdc">llvm::Pattern::printVariableDefs</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmbackend-cpp-/m68kasmbackend/#a86fcebca1ff924c7d38226f00c8e3622">anonymous{M68kAsmBackend.cpp}::M68kAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a85095bdb81f7b2460ce2b158985cdfa9">anonymous{X86AsmBackend.cpp}::X86AsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#ad50e8c99a8ff188846367ea1a9ae2143">llvm::ARMAsmBackend::relaxInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a05377ec092a5d076c82dd3285317e6fa">llvm::opt::Arg::render</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66fc8969d714a36fb8b4918753d1b973">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#acdaf5010e3f77d9d6e8ae04f5e0248e8">solveTypeName</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa2807954a9bf3d29ba94545ebaa23584">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::tryEmitDwarfFileDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08f09f6a0568054ba5a1db783b6eeae5">llvm::UpgradeSectionAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a995e3c2084bb6204a7496128e9562fc0">llvm::yaml::yaml2ObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a960217c66ca1fa6c96ec78eba269b580">llvm::yaml::yaml2offload</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a47c3b2e1c47efa6dea510fdea8711d18">llvm::yaml::yamlize</a>, <a href="/web-llvm/docs/api/classes/llvm/buffer-ostream/#ad94eb5242102c4962ca05c3cb88a13cc">llvm::buffer_ostream::~buffer_ostream</a> and <a href="/web-llvm/docs/api/classes/llvm/buffer-unique-ostream/#a8f3c0cffed7c3552fb623ffb418e6d09">llvm::buffer_unique_ostream::~buffer_unique_ostream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### current\_pos() {#aae4508ceb2b855cc9ff49deb4958f7bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t raw_svector_ostream::current_pos ()</td>
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

<p>Return the current position within the stream.</p>

<p>Declaration at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### pwrite\_impl() {#a656015c4c12ebed7c1aa201d9a068336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_svector_ostream::pwrite_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size, uint64_t Offset)</td>
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



<p>Declaration at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### write\_impl() {#a4192d1b5ef282aa946f9713f7c55af13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_svector_ostream::write_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size)</td>
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

<p>See raw_ostream::write_impl.</p>

<p>Declaration at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OS {#a247c534080a44b70bce0cbde1f08cbbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;char&gt;&amp; llvm::raw_svector_ostream::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a2e906e81aeac5d3671d26f966492f7ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool raw_svector_ostream::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * OS)</td>
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



<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 979 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43a091bc9597603430daadbc899a42f6408">llvm::raw_ostream::OK_SVecStream</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
