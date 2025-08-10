---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/cgdata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `cgdata` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::cgdata { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/cgdata/streamcachedata">StreamCacheData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a429cd542137f6930d904d70bc864c451">hasOutlinedHashTree</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a566a3c31a37bef40996854be6a8d68e3">hasStableFunctionMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f779cac580e35591c444da3941d46f3">getOutlinedHashTree</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5dbda3760db631f85dcce8129a067c5">getStableFunctionMap</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a6f1d892a1ed8390de8835209b023b">emitCGData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2868ab61a4ce104901a8f12be4dbbf40">publishOutlinedHashTree</a> (std::unique_ptr&lt; OutlinedHashTree &gt; HashTree)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a816930fb508497c770b4fe53b5757541">publishStableFunctionMap</a> (std::unique_ptr&lt; StableFunctionMap &gt; FunctionMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa073bf33e4e66824238bc510dcdf0f4e">saveModuleForTwoRounds</a> (const Module &amp;TheModule, unsigned Task, AddStreamFn AddStream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save <span class="doxyComputerOutput">TheModule</span> before the first codegen round. <a href="#aa073bf33e4e66824238bc510dcdf0f4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedbd5b8bb99f2c1816738f4687a3b43a">loadModuleForTwoRounds</a> (BitcodeModule &amp;OrigModule, unsigned Task, LLVMContext &amp;Context, ArrayRef&lt; StringRef &gt; IRFiles)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load the optimized bitcode module for the second codegen round. <a href="#aedbd5b8bb99f2c1816738f4687a3b43a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b4c070c172287759f5f2f437a3edcb">mergeCodeGenData</a> (ArrayRef&lt; StringRef &gt; ObjectFiles)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the codegen data from the scratch objects <span class="doxyComputerOutput">ObjectFiles</span> from the first codegen round. <a href="#a05b4c070c172287759f5f2f437a3edcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594febf895e59fe42257c1d2918c4f65">warn</a> (Error E, StringRef Whence="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491b7adc108c1d48b21caa972d15ba0c">warn</a> (Twine Message, std::string Whence="", std::string Hint="")</td>
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

### emitCGData() {#ad1a6f1d892a1ed8390de8835209b023b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::cgdata::emitCGData ()</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegendata/#a1c2334570aeb5f51fc75d0ed0bba7768">llvm::CodeGenData::emitCGData</a> and <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a2488d432f5848fe22cde3e75c48b1b09">llvm::GlobalMergeFunc::initializeMergerMode</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a4636655f10db66966895ea366108f1e5">anonymous{MachineOutliner.cpp}::MachineOutliner::initializeOutlinerMode</a>.</p>

</div>
</div>

### getOutlinedHashTree() {#a5f779cac580e35591c444da3941d46f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OutlinedHashTree * llvm::cgdata::getOutlinedHashTree ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a> and <a href="/web-llvm/docs/api/classes/llvm/codegendata/#a8e5f32b1f85714a5fb918833048c04d8">llvm::CodeGenData::getOutlinedHashTree</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#af08090d2b358f57cbf6b3448a5ff2676">getMatchedEntries</a>.</p>

</div>
</div>

### getStableFunctionMap() {#ae5dbda3760db631f85dcce8129a067c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StableFunctionMap * llvm::cgdata::getStableFunctionMap ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a> and <a href="/web-llvm/docs/api/classes/llvm/codegendata/#a0ca8e548ef9d5c9ea700ef5ca967affd">llvm::CodeGenData::getStableFunctionMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#ac34d5c990cef52524ce44f37d869664f">llvm::GlobalMergeFunc::run</a>.</p>

</div>
</div>

### hasOutlinedHashTree() {#a429cd542137f6930d904d70bc864c451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::cgdata::hasOutlinedHashTree ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a> and <a href="/web-llvm/docs/api/classes/llvm/codegendata/#a743f557723374e2edf31ae04673b653a">llvm::CodeGenData::hasOutlinedHashTree</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#af08090d2b358f57cbf6b3448a5ff2676">getMatchedEntries</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a4636655f10db66966895ea366108f1e5">anonymous{MachineOutliner.cpp}::MachineOutliner::initializeOutlinerMode</a>.</p>

</div>
</div>

### hasStableFunctionMap() {#a566a3c31a37bef40996854be6a8d68e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::cgdata::hasStableFunctionMap ()</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a> and <a href="/web-llvm/docs/api/classes/llvm/codegendata/#a0074654a63d2717448e3ca65fb166b38">llvm::CodeGenData::hasStableFunctionMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a2488d432f5848fe22cde3e75c48b1b09">llvm::GlobalMergeFunc::initializeMergerMode</a>.</p>

</div>
</div>

### loadModuleForTwoRounds() {#aedbd5b8bb99f2c1816738f4687a3b43a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Module &gt; llvm::cgdata::loadModuleForTwoRounds (<a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &amp; OrigModule, unsigned Task, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; IRFiles)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Load the optimized bitcode module for the second codegen round.</p>


<p><span class="doxyComputerOutput">OrigModule</span> is the original bitcode module. <span class="doxyComputerOutput">Task</span> identifies the partition number in the parallel code generation process. <span class="doxyComputerOutput">Context</span> provides the environment settings for module operations. <span class="doxyComputerOutput">IRFiles</span> contains optimized bitcode module files needed for loading.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A unique_ptr to the loaded <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, or nullptr if loading fails.</p></dd>
</dl>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a80437440e99d3bf259d0346e9f1d4eb4">llvm::BitcodeModule::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a170525c5f5e06bd2555d40a0499b8b6d">llvm::parseBitcodeFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>.</p>

</div>
</div>

### mergeCodeGenData() {#a05b4c070c172287759f5f2f437a3edcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; stable_hash &gt; llvm::cgdata::mergeCodeGenData (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; ObjectFiles)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge the codegen data from the scratch objects <span class="doxyComputerOutput">ObjectFiles</span> from the first codegen round.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the combined hash of the merged codegen data.</p></dd>
</dl>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a3e5e2f09e5c13dfc26257ff0d02f3f86">llvm::OutlinedHashTreeRecord::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord/#a09340e3ef9295311df9e4ce96617ca99">llvm::StableFunctionMapRecord::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord/#a1cd1b3682ae88c0d68ea0a77a8cec60f">llvm::StableFunctionMapRecord::finalize</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord/#a6eadb49468a17cf63d04cfe7a47dc396">llvm::StableFunctionMapRecord::FunctionMap</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a959a2066fb03b6af9f7ddd79bc1f5004">llvm::OutlinedHashTreeRecord::HashTree</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#ad41848e26234890d2d908a09f6709022">llvm::CodeGenDataReader::mergeFromObjectFile</a>, <a href="#a2868ab61a4ce104901a8f12be4dbbf40">publishOutlinedHashTree</a>, <a href="#a816930fb508497c770b4fe53b5757541">publishStableFunctionMap</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### publishOutlinedHashTree() {#a2868ab61a4ce104901a8f12be4dbbf40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::cgdata::publishOutlinedHashTree (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> &gt; HashTree)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a> and <a href="/web-llvm/docs/api/classes/llvm/codegendata/#a565722c191eaf11d0247efe5104c4db8">llvm::CodeGenData::publishOutlinedHashTree</a>.</p>


<p>Referenced by <a href="#a05b4c070c172287759f5f2f437a3edcb">mergeCodeGenData</a>.</p>

</div>
</div>

### publishStableFunctionMap() {#a816930fb508497c770b4fe53b5757541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::cgdata::publishStableFunctionMap (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> &gt; FunctionMap)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a> and <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af1cd6547aef00b0dcd2f15e3e7fb954b">llvm::CodeGenData::publishStableFunctionMap</a>.</p>


<p>Referenced by <a href="#a05b4c070c172287759f5f2f437a3edcb">mergeCodeGenData</a>.</p>

</div>
</div>

### saveModuleForTwoRounds() {#aa073bf33e4e66824238bc510dcdf0f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::cgdata::saveModuleForTwoRounds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, unsigned Task, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Save <span class="doxyComputerOutput">TheModule</span> before the first codegen round.</p>


<p><span class="doxyComputerOutput">Task</span> represents the partition number in the parallel code generation process. <span class="doxyComputerOutput">AddStream</span> is the callback used to add the serialized module to the stream.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a9a4fa55f19f0d5bb47d1fe6802e18d1a">llvm::Module::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### warn() {#a594febf895e59fe42257c1d2918c4f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::cgdata::warn (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> E, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Whence="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/cgdataerror/#aa43a450f77d79dde035d8f5213adab48">llvm::CGDataError::message</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="#a594febf895e59fe42257c1d2918c4f65">warn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a> and <a href="#a594febf895e59fe42257c1d2918c4f65">warn</a>.</p>

</div>
</div>

### warn() {#a491b7adc108c1d48b21caa972d15ba0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::cgdata::warn (<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> Message, std::string Whence="", std::string Hint="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#ab5313a760f20fc53b44cc8dbabfd1ae1">llvm::WithColor::note</a> and <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a237ad6eae22f6b2746a542c02d309a5b">llvm::WithColor::warning</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">CodeGenData.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp">CodeGenData.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
