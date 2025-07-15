---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/livedebugvariables
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LiveDebugVariables` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LiveDebugVariables { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">llvm/CodeGen/LiveDebugVariables.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56be0561be07663beaa3d4ffdcf32edc">LiveDebugVariables</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of the <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables">LiveDebugVariables</a> pass. <a href="#a56be0561be07663beaa3d4ffdcf32edc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803e600cd2dda473ce74a78b0ec3d294">LiveDebugVariables</a> (LiveDebugVariables &amp;&amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e28bd6ec9049e5b7f696dd38c14e02">~LiveDebugVariables</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e46a83de20d6656e5c4605b775da75b">analyze</a> (MachineFunction &amp;MF, LiveIntervals *LIS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f28bd39523be4c5b17c01624543c308">splitRegister</a> (Register OldReg, ArrayRef&lt; Register &gt; NewRegs, LiveIntervals &amp;LIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>splitRegister - Move any user variables in OldReg to the live ranges in NewRegs where they are live. <a href="#a3f28bd39523be4c5b17c01624543c308">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92070770e471a217507e4802436ebc92">emitDebugValues</a> (VirtRegMap *VRM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitDebugValues - Emit new DBG_VALUE instructions reflecting the changes that happened during register allocation. <a href="#a92070770e471a217507e4802436ebc92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224ae5ef2d871d35fcabace424654c2d">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - Print data structures to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>. <a href="#a224ae5ef2d871d35fcabace424654c2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cbf3e865e4410106fabce54174ef923">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f86af62c014de2a279fc87f524a32c6">releaseMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c2d5d3bb918342da8f156b7dc66a3c">invalidate</a> (MachineFunction &amp;MF, const PreservedAnalyses &amp;PA, MachineFunctionAnalysisManager::Invalidator &amp;Inv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl">LDVImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49b0b43512b33c6902403e3bd48eb82">PImpl</a></td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LiveDebugVariables() {#a56be0561be07663beaa3d4ffdcf32edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveDebugVariables::LiveDebugVariables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implementation of the <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables">LiveDebugVariables</a> pass.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>.</p>


<p>Referenced by <a href="#a803e600cd2dda473ce74a78b0ec3d294">LiveDebugVariables</a>.</p>

</div>
</div>

### LiveDebugVariables() {#a803e600cd2dda473ce74a78b0ec3d294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveDebugVariables::LiveDebugVariables (<a href="/web-llvm/docs/api/classes/llvm/livedebugvariables">LiveDebugVariables</a> &amp;&amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>.</p>


<p>Reference <a href="#a56be0561be07663beaa3d4ffdcf32edc">LiveDebugVariables</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LiveDebugVariables() {#a13e28bd6ec9049e5b7f696dd38c14e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveDebugVariables::~LiveDebugVariables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyze() {#a6e46a83de20d6656e5c4605b775da75b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::analyze (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>, definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#ac123ade0fd0d64a4bd01d49755b024c9">EnableLDV</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#af4d1eb21aa4aabfd1ae9a651f02c5332">removeDebugInstrs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2593b6762f74e112d695516c3b6fa9ce">llvm::MachineFunction::useDebugInstrRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livedebugvariablesanalysis/#a9fefe50c560d6fab257603f7e8b20ecc">llvm::LiveDebugVariablesAnalysis::run</a>.</p>

</div>
</div>

### dump() {#a224ae5ef2d871d35fcabace424654c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LiveDebugVariables::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - Print data structures to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>, definition at line 2012 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a5cbf3e865e4410106fabce54174ef923">print</a>.</p>

</div>
</div>

### emitDebugValues() {#a92070770e471a217507e4802436ebc92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::emitDebugValues (<a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * VRM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>emitDebugValues - Emit new DBG_VALUE instructions reflecting the changes that happened during register allocation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">VRM</td>
<td class="doxyParamItemDescription"><p>Rename virtual registers according to map.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>, definition at line 2006 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### invalidate() {#ae1c2d5d3bb918342da8f156b7dc66a3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugVariables::invalidate (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; PA, MachineFunctionAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>, definition at line 1348 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#aa7a1b769f9c57010cc41d9c3bb9d39c6">llvm::PreservedAnalyses::getChecker</a>.</p>

</div>
</div>

### print() {#a5cbf3e865e4410106fabce54174ef923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>, definition at line 2015 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>Referenced by <a href="#a224ae5ef2d871d35fcabace424654c2d">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#a4e5a4f513cd277250d246664b49e066b">llvm::LiveDebugVariables::LDVImpl::runOnMachineFunction</a>.</p>

</div>
</div>

### releaseMemory() {#a6f86af62c014de2a279fc87f524a32c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::releaseMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>, definition at line 1343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### splitRegister() {#a3f28bd39523be4c5b17c01624543c308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugVariables::splitRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; NewRegs, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>splitRegister - Move any user variables in OldReg to the live ranges in NewRegs where they are live.</p>


<p>Mark the values as unavailable where no new register is live.</p>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>, definition at line 1554 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PImpl {#ab49b0b43512b33c6902403e3bd48eb82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LDVImpl&gt; llvm::LiveDebugVariables::PImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">LiveDebugVariables.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
