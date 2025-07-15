---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bitcodemodule
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BitcodeModule` Class Reference

<p>Represents a module in a bitcode file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BitcodeModule { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/bitcodefilecontents">BitcodeFileContents</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af91b526d8407e4b8d8cc54d6cbc1ad50">getBitcodeFileContents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the contents of a bitcode file. <a href="#af91b526d8407e4b8d8cc54d6cbc1ad50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10cd78dbf4982d8f8fda2ea6b1bda7e5">BitcodeModule</a> (ArrayRef&lt; uint8_t &gt; Buffer, StringRef ModuleIdentifier, uint64_t IdentificationBit, uint64_t ModuleBit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cad8ae720266e772dea86311e5f0b54">getBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa8b158e934274ef87af0fe980e65d6">getStrtab</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80437440e99d3bf259d0346e9f1d4eb4">getModuleIdentifier</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe66e1a1da43dba262f5d2fa96bfdf75">getLazyModule</a> (LLVMContext &amp;Context, bool ShouldLazyLoadMetadata, bool IsImporting, ParserCallbacks Callbacks={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the bitcode module and prepare for lazy deserialization of function bodies. <a href="#afe66e1a1da43dba262f5d2fa96bfdf75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad91675f9de94dd24bcee05126b1d7aeb">parseModule</a> (LLVMContext &amp;Context, ParserCallbacks Callbacks={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the entire bitcode module and return it. <a href="#ad91675f9de94dd24bcee05126b1d7aeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/bitcodeltoinfo">BitcodeLTOInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9508697fd741b13841d7563c897e01f3">getLTOInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns information about the module to be used for LTO: whether to compile with ThinLTO, and whether it has a summary. <a href="#a9508697fd741b13841d7563c897e01f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c3f83a2551791b8b6bc2859aa258f02">getSummary</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the specified bitcode buffer, returning the module summary index. <a href="#a8c3f83a2551791b8b6bc2859aa258f02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6e0b0fddee91c9c5def6803934868b5">readSummary</a> (ModuleSummaryIndex &amp;CombinedIndex, StringRef ModulePath, std::function&lt; bool(GlobalValue::GUID)&gt; IsPrevailing=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the specified bitcode buffer and merge its module summary index into CombinedIndex. <a href="#ab6e0b0fddee91c9c5def6803934868b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a141f45690e1ffd6527d530731d65619d">getModuleImpl</a> (LLVMContext &amp;Context, bool MaterializeAll, bool ShouldLazyLoadMetadata, bool IsImporting, ParserCallbacks Callbacks={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a lazy one-at-time loading module from bitcode. <a href="#a141f45690e1ffd6527d530731d65619d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1ace3282a5c68d669616d63fa478a9">Buffer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a457c91c07b62c8f8031821a95de39a6b">ModuleIdentifier</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597615d47afecaa04e7fd979b525ae99">Strtab</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bbb5839eca66d627ba5cbf0790ac3b2">IdentificationBit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e47dccfd9afde805a490ae991b7be9b">ModuleBit</a></td>
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

<p>Represents a module in a bitcode file.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>


<div class="doxySectionDef">

## Friends

### getBitcodeFileContents {#af91b526d8407e4b8d8cc54d6cbc1ad50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/bitcodefilecontents">BitcodeFileContents</a> &gt; <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the contents of a bitcode file.</p>


<p>This includes the raw contents of the symbol table embedded in the bitcode file. Clients which require a symbol table should prefer to use irsymtab::read instead of this function because it creates a reader for the irsymtab and handles upgrading bitcode files without a symbol table or with an old symbol table.</p>


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### BitcodeModule() {#a10cd78dbf4982d8f8fda2ea6b1bda7e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitcodeModule::BitcodeModule (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleIdentifier, uint64_t IdentificationBit, uint64_t ModuleBit)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBuffer() {#a9cad8ae720266e772dea86311e5f0b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BitcodeModule::getBuffer ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>

</div>
</div>

### getLazyModule() {#afe66e1a1da43dba262f5d2fa96bfdf75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Module &gt; &gt; BitcodeModule::getLazyModule (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, bool ShouldLazyLoadMetadata, bool IsImporting, <a href="/web-llvm/docs/api/structs/llvm/parsercallbacks">ParserCallbacks</a> Callbacks={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read the bitcode module and prepare for lazy deserialization of function bodies.</p>


<p>If ShouldLazyLoadMetadata is true, lazily load metadata as well. If IsImporting is true, this module is being parsed for ThinLTO importing into another module.</p>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>, definition at line 8531 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### getLTOInfo() {#a9508697fd741b13841d7563c897e01f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; BitcodeLTOInfo &gt; BitcodeModule::getLTOInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns information about the module to be used for LTO: whether to compile with ThinLTO, and whether it has a summary.</p>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>, definition at line 8621 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/structs/llvm/bitcodeltoinfo/#ae56c82b85b7076e251b305c35b85310e">llvm::BitcodeLTOInfo::EnableSplitLTOUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daca3afe4e93910906ab7d0c2e3bd2b90e">llvm::bitc::FULL_LTO_GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a3d0c0fef256a92c13760a52971b805b5">getEnableSplitLTOUnitAndUnifiedFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da642102503aff012fc2975f165138b454">llvm::bitc::GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/structs/llvm/bitcodeltoinfo/#aeb54ac9a328141108dfaf04522806ac0">llvm::BitcodeLTOInfo::HasSummary</a>, <a href="/web-llvm/docs/api/structs/llvm/bitcodeltoinfo/#a83a35aa860ab725fa2c538fb4580cdec">llvm::BitcodeLTOInfo::IsThinLTO</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a003287dcd6e4d73526b117b2709e2347">llvm::BitstreamCursor::JumpToBit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a73257c6f5ab8032f22e06c1da0bc109f">llvm::BitstreamCursor::SkipBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a> and <a href="/web-llvm/docs/api/structs/llvm/bitcodeltoinfo/#a80ca25bd62c75c8b2c5322f9aea4e98b">llvm::BitcodeLTOInfo::UnifiedLTO</a>.</p>

</div>
</div>

### getModuleIdentifier() {#a80437440e99d3bf259d0346e9f1d4eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BitcodeModule::getModuleIdentifier ()</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#aedbd5b8bb99f2c1816738f4687a3b43a">llvm::cgdata::loadModuleForTwoRounds</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#af0f9c1c44f600c3385ef076febf8c440">anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a5eaa0d8072fbaa8f8304a531ca7bc48e">anonymous{LTO.cpp}::InProcessThinBackend::start</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#a55d36203adadf1f53c19463943f24196">anonymous{LTO.cpp}::WriteIndexesThinBackend::start</a>.</p>

</div>
</div>

### getStrtab() {#aefa8b158e934274ef87af0fe980e65d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BitcodeModule::getStrtab ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>

</div>
</div>

### getSummary() {#a8c3f83a2551791b8b6bc2859aa258f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ModuleSummaryIndex &gt; &gt; BitcodeModule::getSummary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the specified bitcode buffer, returning the module summary index.</p>

<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>, definition at line 8554 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a003287dcd6e4d73526b117b2709e2347">llvm::BitstreamCursor::JumpToBit</a>.</p>

</div>
</div>

### parseModule() {#ad91675f9de94dd24bcee05126b1d7aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Module &gt; &gt; BitcodeModule::parseModule (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/parsercallbacks">ParserCallbacks</a> Callbacks={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read the entire bitcode module and return it.</p>

<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>, definition at line 8714 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#af0f9c1c44f600c3385ef076febf8c440">anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread</a>.</p>

</div>
</div>

### readSummary() {#ab6e0b0fddee91c9c5def6803934868b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error BitcodeModule::readSummary (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModulePath, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>)&gt; IsPrevailing=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the specified bitcode buffer and merge its module summary index into CombinedIndex.</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>, definition at line 8541 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a003287dcd6e4d73526b117b2709e2347">llvm::BitstreamCursor::JumpToBit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getModuleImpl() {#a141f45690e1ffd6527d530731d65619d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Module &gt; &gt; BitcodeModule::getModuleImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, bool MaterializeAll, bool ShouldLazyLoadMetadata, bool IsImporting, <a href="/web-llvm/docs/api/structs/llvm/parsercallbacks">ParserCallbacks</a> Callbacks={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a lazy one-at-time loading module from bitcode.</p>


<p>This isn't always used in a lazy context. In particular, it's also used by <em><a href="#ad91675f9de94dd24bcee05126b1d7aeb">parseModule()</a></em>. If this is truly lazy, then we need to eagerly pull in forward-referenced functions from block address references.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MaterializeAll</td>
<td class="doxyParamItemDescription"><p>Set to <span class="doxyComputerOutput">true</span> if we should materialize everything.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>, definition at line 8489 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buffer {#aee1ace3282a5c68d669616d63fa478a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::BitcodeModule::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>

</div>
</div>

### IdentificationBit {#a9bbb5839eca66d627ba5cbf0790ac3b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BitcodeModule::IdentificationBit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>

</div>
</div>

### ModuleBit {#a4e47dccfd9afde805a490ae991b7be9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BitcodeModule::ModuleBit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>

</div>
</div>

### ModuleIdentifier {#a457c91c07b62c8f8031821a95de39a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BitcodeModule::ModuleIdentifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>

</div>
</div>

### Strtab {#a597615d47afecaa04e7fd979b525ae99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BitcodeModule::Strtab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">BitcodeReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
