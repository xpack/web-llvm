---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/physicalregisterusageinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PhysicalRegisterUsageInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::PhysicalRegisterUsageInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">llvm/CodeGen/RegisterUsageInfo.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa454216fa5dcec0918bafb27b16b3fc7">setTargetMachine</a> (const TargetMachine &amp;TM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> which is used to print analysis. <a href="#aa454216fa5dcec0918bafb27b16b3fc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7523768c1b244acca7b83c7a04fa9d9f">doInitialization</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dec3d5d7e698c6135fd00104ecda257">doFinalization</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4ae6575718249d21f984def4a3ac130">storeUpdateRegUsageInfo</a> (const Function &amp;FP, ArrayRef&lt; uint32_t &gt; RegMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To store RegMask for given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *. <a href="#ad4ae6575718249d21f984def4a3ac130">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c457b2f14402490654cd3e4589d920">getRegUsageInfo</a> (const Function &amp;FP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To query stored RegMask for given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, it will returns ane empty array if function is not known. <a href="#a72c457b2f14402490654cd3e4589d920">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa2c354cf7353f24dac62741d54bc98b">print</a> (raw_ostream &amp;OS, const Module *M=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08cca56920d14f500104268455af4306">invalidate</a> (Module &amp;M, const PreservedAnalyses &amp;PA, ModuleAnalysisManager::Invalidator &amp;Inv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, std::vector&lt; uint32_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f67ffaaf31a4a93d170c05933c4e76">RegMasks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A Dense map from <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * to RegMask. <a href="#a77f67ffaaf31a4a93d170c05933c4e76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae12b6dc4fd4cbd94c9723658629951c5">TM</a> = nullptr</td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### doFinalization() {#a5dec3d5d7e698c6135fd00104ecda257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PhysicalRegisterUsageInfo::doFinalization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerusageinfo-cpp">RegisterUsageInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerusageinfo-cpp/#af27d2e58f606ecad6f858363528c3084">DumpRegUsage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="#aaa2c354cf7353f24dac62741d54bc98b">print</a>.</p>

</div>
</div>

### doInitialization() {#a7523768c1b244acca7b83c7a04fa9d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PhysicalRegisterUsageInfo::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerusageinfo-cpp">RegisterUsageInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/physicalregisterusageanalysis/#a11bdf8f4dd462baafeec6df9252bf451">llvm::PhysicalRegisterUsageAnalysis::run</a>.</p>

</div>
</div>

### getRegUsageInfo() {#a72c457b2f14402490654cd3e4589d920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint32_t &gt; PhysicalRegisterUsageInfo::getRegUsageInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; FP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>To query stored RegMask for given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, it will returns ane empty array if function is not known.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerusageinfo-cpp">RegisterUsageInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>.</p>

</div>
</div>

### invalidate() {#a08cca56920d14f500104268455af4306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PhysicalRegisterUsageInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, ModuleAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerusageinfo-cpp">RegisterUsageInfo.cpp</a>.</p>

</div>
</div>

### print() {#aaa2c354cf7353f24dac62741d54bc98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PhysicalRegisterUsageInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerusageinfo-cpp">RegisterUsageInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a5dec3d5d7e698c6135fd00104ecda257">doFinalization</a>.</p>

</div>
</div>

### setTargetMachine() {#aa454216fa5dcec0918bafb27b16b3fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PhysicalRegisterUsageInfo::setTargetMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> which is used to print analysis.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>.</p>

</div>
</div>

### storeUpdateRegUsageInfo() {#ad4ae6575718249d21f984def4a3ac130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PhysicalRegisterUsageInfo::storeUpdateRegUsageInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; FP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; RegMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>To store RegMask for given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerusageinfo-cpp">RegisterUsageInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RegMasks {#a77f67ffaaf31a4a93d170c05933c4e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, std::vector&lt;uint32_t&gt; &gt; llvm::PhysicalRegisterUsageInfo::RegMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A Dense map from <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * to RegMask.</p>


<p>In RegMask 0 means register used (clobbered) by function. and 1 means content of register will be preserved around function call.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>.</p>

</div>
</div>

### TM {#ae12b6dc4fd4cbd94c9723658629951c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine* llvm::PhysicalRegisterUsageInfo::TM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerusageinfo-h">RegisterUsageInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerusageinfo-cpp">RegisterUsageInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
