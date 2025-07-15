---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IndexBitcodeWriter` Class Reference

<p>Class to manage the bitcode writing for a combined index. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase">BitcodeWriterBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract class to manage the bitcode writing, subclassed for each bitcode file type. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e01fd1353d2dd3b147f87cce57ab5a2">GVInfo</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The below iterator returns the GUID and associated summary. <a href="#a3e01fd1353d2dd3b147f87cce57ab5a2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8723cbabc5c7064728c2fdcc5b14b771">IndexBitcodeWriter</a> (BitstreamWriter &amp;Stream, StringTableBuilder &amp;StrtabBuilder, const ModuleSummaryIndex &amp;Index, const GVSummaryPtrSet *DecSummaries=nullptr, const ModuleToSummariesForIndexTy *ModuleToSummariesForIndex=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter">IndexBitcodeWriter</a> object for the given combined index, writing to the provided <span class="doxyComputerOutput">Buffer</span>. <a href="#a8723cbabc5c7064728c2fdcc5b14b771">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Functor&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3645d133a2e3aefbb5c9ae55065b671">forEachSummary</a> (Functor Callback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls the callback for each value GUID and summary to be written to bitcode. <a href="#aa3645d133a2e3aefbb5c9ae55065b671">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Functor&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5796fcdd25688200886925c4f3878799">forEachModule</a> (Functor Callback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls the callback for each entry in the modulePaths <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> that should be written to the module path string table. <a href="#a5796fcdd25688200886925c4f3878799">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaade9f75fd9ed6de54fefd2d0e0bb2e8">write</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main entry point for writing a combined index to bitcode. <a href="#aaade9f75fd9ed6de54fefd2d0e0bb2e8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf24c56a25c4d24f4e666522899b1df9">writeModStrings</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the module path strings, currently only used when generating a combined index file. <a href="#aaf24c56a25c4d24f4e666522899b1df9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8180964bd4215b549fe00601f57240">writeCombinedGlobalValueSummary</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the combined summary section into the combined index file. <a href="#afa8180964bd4215b549fe00601f57240">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a752949100743d4b5a71cdf927ec3f4b3">getValueId</a> (GlobalValue::GUID ValGUID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, unsigned &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f51e9a836a012fb98dedb3ac0393036">valueIds</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e5edf3662d5621af52d9080edb15d4">Index</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The combined index to write to bitcode. <a href="#ae9e5edf3662d5621af52d9080edb15d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a126f52d391b28545496b57f7de17fc61">GVSummaryPtrSet</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12dceadce0c788d32deeeef4c2b53e28">DecSummaries</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When writing combined summaries, provides the set of global value summaries for which the value (function, function alias, etc) should be imported as a declaration. <a href="#a12dceadce0c788d32deeeef4c2b53e28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a855e9319bbdff7f7c70bb2b2c5a0650e">ModuleToSummariesForIndexTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed721ae27f7d431e5e2e2f880aaf5b9">ModuleToSummariesForIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When writing a subset of the index for distributed backends, client provides a map of modules to the corresponding GUIDs/summaries to write. <a href="#a7ed721ae27f7d431e5e2e2f880aaf5b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7699988709e9a8243ab16f3fa60284bb">GUIDToValueIdMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map that holds the correspondence between the GUID used in the combined index and a value id generated by this class to use in references. <a href="#a7699988709e9a8243ab16f3fa60284bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a18f1302fd4be21703e76f40045d5d0">StackIds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86208ee055a6f3c94056febc6affb4a7">StackIdIndicesToIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603b60879f9223e028c894902de78dca">GlobalValueId</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks the last value id recorded in the GUIDToValueMap. <a href="#a603b60879f9223e028c894902de78dca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae74286b752896ecd2e07cebc0d43ce96">ModuleIdMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks the assignment of module paths in the module path string table to an id assigned for use in summary references to the module path. <a href="#ae74286b752896ecd2e07cebc0d43ce96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class to manage the bitcode writing for a combined index.</p>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GVInfo {#a3e01fd1353d2dd3b147f87cce57ab5a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::GVInfo =  std::pair&lt;GlobalValue::GUID, GlobalValueSummary *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The below iterator returns the GUID and associated summary.</p>

<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IndexBitcodeWriter() {#a8723cbabc5c7064728c2fdcc5b14b771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::IndexBitcodeWriter (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrtabBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a126f52d391b28545496b57f7de17fc61">GVSummaryPtrSet</a> * DecSummaries=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a855e9319bbdff7f7c70bb2b2c5a0650e">ModuleToSummariesForIndexTy</a> * ModuleToSummariesForIndex=nullptr)</td>
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

<p>Constructs a <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter">IndexBitcodeWriter</a> object for the given combined index, writing to the provided <span class="doxyComputerOutput">Buffer</span>.</p>


<p>When writing a subset of the index for a distributed backend, provide a <span class="doxyComputerOutput">ModuleToSummariesForIndex</span> map. If provided, <span class="doxyComputerOutput">DecSummaries</span> specifies the set of summaries for which the corresponding functions or aliased functions should be imported as a declaration (but not definition) for each module.</p>


<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#ad88d45a4534c867c5b0fab73d70f176f">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::BitcodeWriterBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aa3645d133a2e3aefbb5c9ae55065b671">forEachSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#a31291fbb3033f9d35b27cc4cd51c90c2">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::Stream</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#a25c3139775b4aef5f6a1cb287f304430">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::StrtabBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### forEachModule() {#a5796fcdd25688200886925c4f3878799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Functor&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::forEachModule (Functor Callback)</td>
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

<p>Calls the callback for each entry in the modulePaths <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> that should be written to the module path string table.</p>


<p>This hides the details of whether they are being pulled from the entire index or just those in a provided ModuleToSummariesForIndex map.</p>


<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### forEachSummary() {#aa3645d133a2e3aefbb5c9ae55065b671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Functor&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::forEachSummary (Functor Callback)</td>
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

<p>Calls the callback for each value GUID and summary to be written to bitcode.</p>


<p>This hides the details of whether they are being pulled from the entire index or just those in a provided ModuleToSummariesForIndex map.</p>


<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a8723cbabc5c7064728c2fdcc5b14b771">IndexBitcodeWriter</a>.</p>

</div>
</div>

### write() {#aaade9f75fd9ed6de54fefd2d0e0bb2e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexBitcodeWriter::write ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Main entry point for writing a combined index to bitcode.</p>

<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#a31291fbb3033f9d35b27cc4cd51c90c2">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::Stream</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#a505f027441489e465875cc1b95d98b39">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::writeModuleVersion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getValueId() {#a752949100743d4b5a71cdf927ec3f4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::getValueId (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> ValGUID)</td>
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



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### valueIds() {#a9f51e9a836a012fb98dedb3ac0393036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt; GlobalValue::GUID, unsigned &gt; &amp; anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::valueIds ()</td>
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



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeCombinedGlobalValueSummary() {#afa8180964bd4215b549fe00601f57240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexBitcodeWriter::writeCombinedGlobalValueSummary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the combined summary section into the combined index file.</p>

<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeModStrings() {#aaf24c56a25c4d24f4e666522899b1df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexBitcodeWriter::writeModStrings ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the module path strings, currently only used when generating a combined index file.</p>

<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DecSummaries {#a12dceadce0c788d32deeeef4c2b53e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GVSummaryPtrSet* anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::DecSummaries = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When writing combined summaries, provides the set of global value summaries for which the value (function, function alias, etc) should be imported as a declaration.</p>

<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### GlobalValueId {#a603b60879f9223e028c894902de78dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::GlobalValueId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tracks the last value id recorded in the GUIDToValueMap.</p>

<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### GUIDToValueIdMap {#a7699988709e9a8243ab16f3fa60284bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;GlobalValue::GUID, unsigned&gt; anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::GUIDToValueIdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map that holds the correspondence between the GUID used in the combined index and a value id generated by this class to use in references.</p>

<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### Index {#ae9e5edf3662d5621af52d9080edb15d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleSummaryIndex&amp; anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The combined index to write to bitcode.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### ModuleIdMap {#ae74286b752896ecd2e07cebc0d43ce96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;StringRef, uint64_t&gt; anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::ModuleIdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tracks the assignment of module paths in the module path string table to an id assigned for use in summary references to the module path.</p>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### ModuleToSummariesForIndex {#a7ed721ae27f7d431e5e2e2f880aaf5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleToSummariesForIndexTy* anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::ModuleToSummariesForIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When writing a subset of the index for distributed backends, client provides a map of modules to the corresponding GUIDs/summaries to write.</p>

<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### StackIdIndicesToIndex {#a86208ee055a6f3c94056febc6affb4a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::StackIdIndicesToIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### StackIds {#a5a18f1302fd4be21703e76f40045d5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; anonymous{BitcodeWriter.cpp}::IndexBitcodeWriter::StackIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
