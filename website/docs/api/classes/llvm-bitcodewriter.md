---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bitcodewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BitcodeWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::BitcodeWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">llvm/Bitcode/BitcodeWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebebbee7033640e87126667a63bd2357">BitcodeWriter</a> (SmallVectorImpl&lt; char &gt; &amp;Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/bitcodewriter">BitcodeWriter</a> that writes to Buffer. <a href="#aebebbee7033640e87126667a63bd2357">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d51c2e883aaae6b692f2babd7f6311f">BitcodeWriter</a> (raw_ostream &amp;FS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99469a121e6001ddda44844fac8dfd1e">~BitcodeWriter</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaca861df948bd93da0afb6891e9d662">writeSymtab</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to write a symbol table to the bitcode file. <a href="#aaaca861df948bd93da0afb6891e9d662">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d48eebf776ab619a0174721ddd90872">writeStrtab</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the bitcode file's string table. <a href="#a8d48eebf776ab619a0174721ddd90872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a495eadc82261ad39d242b9d7e477c3e2">copyStrtab</a> (StringRef Strtab)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy the string table for another module into this bitcode file. <a href="#a495eadc82261ad39d242b9d7e477c3e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acedecaa6f87d31e343286c46148e119a">writeModule</a> (const Module &amp;M, bool ShouldPreserveUseListOrder=false, const ModuleSummaryIndex *Index=nullptr, bool GenerateHash=false, ModuleHash *ModHash=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the specified module to the buffer specified at construction time. <a href="#acedecaa6f87d31e343286c46148e119a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f3ffa01b7de15ab90e804ead0472b4">writeThinLinkBitcode</a> (const Module &amp;M, const ModuleSummaryIndex &amp;Index, const ModuleHash &amp;ModHash)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the specified thin link bitcode file (i.e., the minimized bitcode file) to the buffer specified at construction time. <a href="#a03f3ffa01b7de15ab90e804ead0472b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a301cb081638a5035bb80e799543bf53f">writeIndex</a> (const ModuleSummaryIndex *Index, const ModuleToSummariesForIndexTy *ModuleToSummariesForIndex, const GVSummaryPtrSet *DecSummaries)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a388fc471d24c3370b2f495ba8c8f704f">writeBlob</a> (unsigned Block, unsigned Record, StringRef Blob)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcde7a7bc5e64c334fe7d06ec64a7c6">Stream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accead85d0fb6adfadb3139985a1c2293">StrtabBuilder</a> {<a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73aa7276fc7b95014e9041e70e8d0bfcdc3d">StringTableBuilder::RAW</a>}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a182b2ce264fd626b9c0e1f48e9fc0333">Alloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac68282a745dbec1b94c8b34c4e15aadd">WroteStrtab</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9ad29246ef3ed30a4fa5621215f7d8">WroteSymtab</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9be882e3df317489a884e1dd8b1d75">Mods</a></td>
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


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitcodeWriter() {#aebebbee7033640e87126667a63bd2357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitcodeWriter::BitcodeWriter (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/bitcodewriter">BitcodeWriter</a> that writes to Buffer.</p>

<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5266 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a90f3f0ae5027fb62fc0090c0b0722d0f">writeBitcodeHeader</a>.</p>

</div>
</div>

### BitcodeWriter() {#a4d51c2e883aaae6b692f2babd7f6311f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitcodeWriter::BitcodeWriter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5271 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a7a4f14026a779acb2eda1e8107a62f24">FlushThreshold</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a90f3f0ae5027fb62fc0090c0b0722d0f">writeBitcodeHeader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BitcodeWriter() {#a99469a121e6001ddda44844fac8dfd1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitcodeWriter::~BitcodeWriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5276 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyStrtab() {#a495eadc82261ad39d242b9d7e477c3e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitcodeWriter::copyStrtab (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Strtab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy the string table for another module into this bitcode file.</p>


<p>This should be called after copying the module itself into the bitcode file.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5337 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aa5f5b04f18dd0147ec2e2ee1dff56c06a8a6e8086acc7a4f894b953311c088549">llvm::bitc::STRTAB_BLOB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da33a2dbf49ae958238e75eb871a9f0b2e">llvm::bitc::STRTAB_BLOCK_ID</a>.</p>

</div>
</div>

### writeIndex() {#a301cb081638a5035bb80e799543bf53f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitcodeWriter::writeIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a855e9319bbdff7f7c70bb2b2c5a0650e">ModuleToSummariesForIndexTy</a> * ModuleToSummariesForIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a126f52d391b28545496b57f7de17fc61">GVSummaryPtrSet</a> * DecSummaries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5361 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5858c9c8d861a0d36e7c8f99b8faf7fe">llvm::writeIndexToFile</a>.</p>

</div>
</div>

### writeModule() {#acedecaa6f87d31e343286c46148e119a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitcodeWriter::writeModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, bool ShouldPreserveUseListOrder=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * Index=nullptr, bool GenerateHash=false, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b53e399f7a71b096a6caef6be6ff12d">ModuleHash</a> * ModHash=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the specified module to the buffer specified at construction time.</p>


<p>If <span class="doxyComputerOutput">ShouldPreserveUseListOrder</span>, encode the use-list order for each <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> in <span class="doxyComputerOutput">M</span>. These will be reconstructed exactly when <em>M</em> is deserialized.</p>


<p>If <span class="doxyComputerOutput">Index</span> is supplied, the bitcode will contain the summary index (currently for use in ThinLTO optimization).</p>


<p><span class="doxyComputerOutput">GenerateHash</span> enables hashing the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> and including the hash in the bitcode (currently for use in ThinLTO incremental build).</p>


<p>If <span class="doxyComputerOutput">ModHash</span> is non-null, when GenerateHash is true, the resulting hash is written into ModHash. When GenerateHash is false, that value is used as the hash instead of computing from the generated bitcode. Can be used to produce the same module hash for a minimized bitcode used just for the thin link as in the regular full bitcode that will be used in the backend.</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5342 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#acb572d27661acd51c80b1bca18cd1ee3">llvm::orc::cloneToNewContext</a>.</p>

</div>
</div>

### writeStrtab() {#a8d48eebf776ab619a0174721ddd90872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitcodeWriter::writeStrtab ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the bitcode file's string table.</p>


<p>This must be called exactly once after all modules and the optional symbol table have been written.</p>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5323 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aa5f5b04f18dd0147ec2e2ee1dff56c06a8a6e8086acc7a4f894b953311c088549">llvm::bitc::STRTAB_BLOB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da33a2dbf49ae958238e75eb871a9f0b2e">llvm::bitc::STRTAB_BLOCK_ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#acb572d27661acd51c80b1bca18cd1ee3">llvm::orc::cloneToNewContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5858c9c8d861a0d36e7c8f99b8faf7fe">llvm::writeIndexToFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a33564097625c6a9b619c60a71343c058">llvm::writeThinLinkBitcodeToFile</a>.</p>

</div>
</div>

### writeSymtab() {#aaaca861df948bd93da0afb6891e9d662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitcodeWriter::writeSymtab ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to write a symbol table to the bitcode file.</p>


<p>This must be called at most once after all modules have been written.</p>


<p>A reader does not require a symbol table to interpret a bitcode file; the symbol table is needed only to improve link-time performance. So this function may decide not to write a symbol table. It may so decide if, for example, the target is unregistered or the IR is malformed.</p>


<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5291 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/#a8af0e7caf92ff2e049dc40eceafc15be">llvm::irsymtab::build</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aeb428612b856bd084feccd8f480330dea1329b6bf1ed0b214660309e1a7e4e04c">llvm::bitc::SYMTAB_BLOB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da466acfef0eae5774264a2115c0c1496a">llvm::bitc::SYMTAB_BLOCK_ID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#acb572d27661acd51c80b1bca18cd1ee3">llvm::orc::cloneToNewContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a33564097625c6a9b619c60a71343c058">llvm::writeThinLinkBitcodeToFile</a>.</p>

</div>
</div>

### writeThinLinkBitcode() {#a03f3ffa01b7de15ab90e804ead0472b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitcodeWriter::writeThinLinkBitcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a2b53e399f7a71b096a6caef6be6ff12d">ModuleHash</a> &amp; ModHash)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the specified thin link bitcode file (i.e., the minimized bitcode file) to the buffer specified at construction time.</p>


<p>The thin link bitcode file is used for thin link, and it only contains the necessary information for thin link.</p>


<p>ModHash is for use in ThinLTO incremental build, generated while the IR bitcode file writing.</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5559 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a33564097625c6a9b619c60a71343c058">llvm::writeThinLinkBitcodeToFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### writeBlob() {#a388fc471d24c3370b2f495ba8c8f704f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BitcodeWriter::writeBlob (unsigned Block, unsigned Record, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>, definition at line 5278 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alloc {#a182b2ce264fd626b9c0e1f48e9fc0333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::BitcodeWriter::Alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>.</p>

</div>
</div>

### Mods {#a3f9be882e3df317489a884e1dd8b1d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Module *&gt; llvm::BitcodeWriter::Mods</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>.</p>

</div>
</div>

### Stream {#a0fcde7a7bc5e64c334fe7d06ec64a7c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BitstreamWriter&gt; llvm::BitcodeWriter::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>.</p>

</div>
</div>

### StrtabBuilder {#accead85d0fb6adfadb3139985a1c2293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder llvm::BitcodeWriter::StrtabBuilder {<a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73aa7276fc7b95014e9041e70e8d0bfcdc3d">StringTableBuilder::RAW</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>.</p>

</div>
</div>

### WroteStrtab {#ac68282a745dbec1b94c8b34c4e15aadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitcodeWriter::WroteStrtab = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>.</p>

</div>
</div>

### WroteSymtab {#a7b9ad29246ef3ed30a4fa5621215f7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitcodeWriter::WroteSymtab = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">BitcodeWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
