---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineblockfrequencyinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineBlockFrequencyInfo` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> pass uses <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl">BlockFrequencyInfoImpl</a> implementation to estimate machine basic block frequencies. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineBlockFrequencyInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f0b5c00129a3653cb9bf98da741421">ImplType</a> = <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl">BlockFrequencyInfoImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc3904e54b6ae9dbc0693a5615546284">MachineBlockFrequencyInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd21a6bc6468597dc19d0c81d66de4a1">MachineBlockFrequencyInfo</a> (MachineFunction &amp;F, MachineBranchProbabilityInfo &amp;MBPI, MachineLoopInfo &amp;MLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbfe6d58052bf14b4eeaf2d0c1ba5af3">MachineBlockFrequencyInfo</a> (MachineBlockFrequencyInfo &amp;&amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4e40d1805e54076278fb32c89b7ca35">~MachineBlockFrequencyInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91486e3f4b23c4b8937543e36b97de2">invalidate</a> (MachineFunction &amp;F, const PreservedAnalyses &amp;PA, MachineFunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation explicitly. <a href="#aa91486e3f4b23c4b8937543e36b97de2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c7ee9bd2f71192c25e89f3cd58f799">calculate</a> (const MachineFunction &amp;F, const MachineBranchProbabilityInfo &amp;MBPI, const MachineLoopInfo &amp;MLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calculate - compute block frequency info for the given function. <a href="#a84c7ee9bd2f71192c25e89f3cd58f799">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a200416e5eaf8421802b1d2e01517141f">print</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a411003caee881ecd5005f081c711f8">releaseMemory</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd7fa8c0a91118934b08b516b6e9d37">getBlockFreq</a> (const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getblockFreq - Return block frequency. <a href="#a7dd7fa8c0a91118934b08b516b6e9d37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9be2cffeaf9bda65c4c49eeebaa5458f">getBlockFreqRelativeToEntryBlock</a> (const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the frequency of the block, relative to the entry block. <a href="#a9be2cffeaf9bda65c4c49eeebaa5458f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d35ccc615084c6e7da873a9d49c2ed">getBlockProfileCount</a> (const MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0741c990e9ba83713c7e5910b0dc12e">getProfileCountFromFreq</a> (BlockFrequency Freq) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e82c44e568ac755d81ecb860489d6c9">isIrrLoopHeader</a> (const MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b388502250fca34a5e23148e0d3bf2">onEdgeSplit</a> (const MachineBasicBlock &amp;NewPredecessor, const MachineBasicBlock &amp;NewSuccessor, const MachineBranchProbabilityInfo &amp;MBPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>incrementally calculate block frequencies when we split edges, to avoid full CFG traversal. <a href="#a83b388502250fca34a5e23148e0d3bf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ac588cee23e2f5f25b5656ff2010d19">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c773188891ca194070345ab04799109">getMBPI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fffc1a69ef51a1f23e7e5026b7e5733">view</a> (const Twine &amp;Name, bool isSimple=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pop up a ghostview window with the current block frequency propagation rendered using dot. <a href="#a0fffc1a69ef51a1f23e7e5026b7e5733">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9c041cb61532576659d652739439acc">getEntryFreq</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Divide a block's <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#a8e9ed6b20c2503f66f1fd0725297aedc">BlockFrequency::getFrequency()</a> value by this value to obtain the entry block - relative frequency of said block. <a href="#aa9c041cb61532576659d652739439acc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl">ImplType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a924649a834cc060e49c31841608aa3be">MBFI</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> pass uses <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl">BlockFrequencyInfoImpl</a> implementation to estimate machine basic block frequencies.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ImplType {#a86f0b5c00129a3653cb9bf98da741421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBlockFrequencyInfo::ImplType =  BlockFrequencyInfoImpl&lt;MachineBasicBlock&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineBlockFrequencyInfo() {#acc3904e54b6ae9dbc0693a5615546284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo::MachineBlockFrequencyInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#acbfe6d58052bf14b4eeaf2d0c1ba5af3">MachineBlockFrequencyInfo</a> and <a href="#a0fffc1a69ef51a1f23e7e5026b7e5733">view</a>.</p>

</div>
</div>

### MachineBlockFrequencyInfo() {#acd21a6bc6468597dc19d0c81d66de4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo::MachineBlockFrequencyInfo (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> &amp; MBPI, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp; MLI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="#a84c7ee9bd2f71192c25e89f3cd58f799">calculate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### MachineBlockFrequencyInfo() {#acbfe6d58052bf14b4eeaf2d0c1ba5af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo::MachineBlockFrequencyInfo (<a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> &amp;&amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>.</p>


<p>Reference <a href="#acc3904e54b6ae9dbc0693a5615546284">MachineBlockFrequencyInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineBlockFrequencyInfo() {#ab4e40d1805e54076278fb32c89b7ca35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo::~MachineBlockFrequencyInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### calculate() {#a84c7ee9bd2f71192c25e89f3cd58f799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockFrequencyInfo::calculate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> &amp; MBPI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp; MLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calculate - compute block frequency info for the given function.</p>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0bf055834b973decc2477a8061624ffa49315903a2559d882f356ae28a455556">llvm::GVDT_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a12ed6cda79362a16ba48b0849cf00df2">llvm::PrintBFIFuncName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5de3230111927782f6438f2fac5ea466">llvm::PrintMachineBlockFreq</a>, <a href="#a0fffc1a69ef51a1f23e7e5026b7e5733">view</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6391a34afa5b4ed1a5e556a8cc4d971b">llvm::ViewBlockFreqFuncName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a805bb3f1bbac9a9a6cdab01c69defaf8">llvm::ViewMachineBlockFreqPropagationDAG</a>.</p>


<p>Referenced by <a href="#acd21a6bc6468597dc19d0c81d66de4a1">MachineBlockFrequencyInfo</a>.</p>

</div>
</div>

### getBlockFreq() {#a7dd7fa8c0a91118934b08b516b6e9d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency MachineBlockFrequencyInfo::getBlockFreq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getblockFreq - Return block frequency.</p>


<p>Return 0 if we don't have the information. Please note that initial frequency is equal to 1024. It means that we should not rely on the value itself, but only on the comparison to the other block frequencies. We do this to avoid using of floating points. For example, to get the frequency of a block relative to the entry block, divide the integral value returned by this function (the <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#a8e9ed6b20c2503f66f1fd0725297aedc">BlockFrequency::getFrequency()</a> value) by <a href="#aa9c041cb61532576659d652739439acc">getEntryFreq()</a>.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopalign-cpp-/hexagonloopalign/#a49530a2f7101146544b49c809bc2e035">anonymous{HexagonLoopAlign.cpp}::HexagonLoopAlign::attemptToBalignSmallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5f32c10b46f4e956f21552b0984ae68f">llvm::AsmPrinter::emitBBAddrMapSection</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/instrinsertpoint/#acfe02f412f4221fbb6a31ca758ac297e">llvm::RegBankSelect::InstrInsertPoint::frequency</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mbbinsertpoint/#a93a33c37cd1f7261b08ca7a90062c3fd">llvm::RegBankSelect::MBBInsertPoint::frequency</a>, <a href="#a9be2cffeaf9bda65c4c49eeebaa5458f">getBlockFreqRelativeToEntryBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9b92e19787a628bdf0dcd444d4c85581">llvm::printBlockFreq</a>.</p>

</div>
</div>

### getBlockFreqRelativeToEntryBlock() {#a9be2cffeaf9bda65c4c49eeebaa5458f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::MachineBlockFrequencyInfo::getBlockFreqRelativeToEntryBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>Compute the frequency of the block, relative to the entry block.</p>


<p>This API assumes <a href="#aa9c041cb61532576659d652739439acc">getEntryFreq()</a> is non-zero.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7dd7fa8c0a91118934b08b516b6e9d37">getBlockFreq</a>, <a href="#aa9c041cb61532576659d652739439acc">getEntryFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#a8e9ed6b20c2503f66f1fd0725297aedc">llvm::BlockFrequency::getFrequency</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/coalescing/#a68a07c5954404c20c6abe9a6791f19c2">anonymous{RegAllocPBQP.cpp}::Coalescing::apply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d3e4802f0929af81173430c0786d52a">llvm::calculateRegAllocScore</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a9477f951deaab56a096380fc549d602c">llvm::LiveIntervals::getSpillWeight</a>.</p>

</div>
</div>

### getBlockProfileCount() {#ac9d35ccc615084c6e7da873a9d49c2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; MachineBlockFrequencyInfo::getBlockProfileCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#a0045721a7b443c9ed664f9e41abf5cad">isColdBlock</a>.</p>

</div>
</div>

### getEntryFreq() {#aa9c041cb61532576659d652739439acc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency MachineBlockFrequencyInfo::getEntryFreq ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Divide a block's <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#a8e9ed6b20c2503f66f1fd0725297aedc">BlockFrequency::getFrequency()</a> value by this value to obtain the entry block - relative frequency of said block.</p>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="#a9be2cffeaf9bda65c4c49eeebaa5458f">getBlockFreqRelativeToEntryBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7081c2939e4c0e45349f5daa75dd98cd">llvm::printBlockFreq</a>.</p>

</div>
</div>

### getFunction() {#a9ac588cee23e2f5f25b5656ff2010d19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction * MachineBlockFrequencyInfo::getFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>.</p>

</div>
</div>

### getMBPI() {#a6c773188891ca194070345ab04799109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBranchProbabilityInfo * MachineBlockFrequencyInfo::getMBPI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-98588480f432ad6b5e85a9f166846cbf/#a0f4682aefa53640aef6e5282a0c9a24b">llvm::DOTGraphTraits&lt; MachineBlockFrequencyInfo * &gt;::getEdgeAttributes</a>.</p>

</div>
</div>

### getProfileCountFromFreq() {#aa0741c990e9ba83713c7e5910b0dc12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; MachineBlockFrequencyInfo::getProfileCountFromFreq (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Freq)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### invalidate() {#aa91486e3f4b23c4b8937543e36b97de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockFrequencyInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; PA, MachineFunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle invalidation explicitly.</p>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#aa7a1b769f9c57010cc41d9c3bb9d39c6">llvm::PreservedAnalyses::getChecker</a>.</p>

</div>
</div>

### isIrrLoopHeader() {#a2e82c44e568ac755d81ecb860489d6c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBlockFrequencyInfo::isIrrLoopHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### onEdgeSplit() {#a83b388502250fca34a5e23148e0d3bf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockFrequencyInfo::onEdgeSplit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; NewPredecessor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; NewSuccessor, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> &amp; MBPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>incrementally calculate block frequencies when we split edges, to avoid full CFG traversal.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo/#ad78fb9b4721b71aa297bd2bda44e7e39">llvm::MachineBranchProbabilityInfo::getEdgeProbability</a>.</p>

</div>
</div>

### print() {#a200416e5eaf8421802b1d2e01517141f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockFrequencyInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>

</div>
</div>

### releaseMemory() {#a8a411003caee881ecd5005f081c711f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockFrequencyInfo::releaseMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>

</div>
</div>

### view() {#a0fffc1a69ef51a1f23e7e5026b7e5733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBlockFrequencyInfo::view (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, bool isSimple=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pop up a ghostview window with the current block frequency propagation rendered using dot.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3ca9742688618517cc4690fb947fb609">isSimple</a>, <a href="#acc3904e54b6ae9dbc0693a5615546284">MachineBlockFrequencyInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8635363d4287c93f64c55ad5567fcf0">llvm::ViewGraph</a>.</p>


<p>Referenced by <a href="#a84c7ee9bd2f71192c25e89f3cd58f799">calculate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MBFI {#a924649a834cc060e49c31841608aa3be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ImplType&gt; llvm::MachineBlockFrequencyInfo::MBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">MachineBlockFrequencyInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
