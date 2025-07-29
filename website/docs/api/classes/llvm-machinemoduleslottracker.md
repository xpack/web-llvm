---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinemoduleslottracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineModuleSlotTracker` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MachineModuleSlotTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">llvm/CodeGen/MachineModuleSlotTracker.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Manage lifetime of a slot tracker for printing IR. <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46f7561b1384a882cfabf8ef2b7326c">MachineModuleSlotTracker</a> (const MachineModuleInfo &amp;MMI, const MachineFunction *MF, bool ShouldInitializeAllMetadata=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71722f40d1ad8dd65847bae0d9625ede">~MachineModuleSlotTracker</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac196d286114a87387bcd505f13c5d6b">collectMachineMDNodes</a> (MachineMDNodeListType &amp;L) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec7851423d8367967470047ae9fd076">processMachineFunctionMetadata</a> (AbstractSlotTrackerStorage *AST, const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2825db30b6a23e752f142546d71a511b">processMachineModule</a> (AbstractSlotTrackerStorage *AST, const Module *M, bool ShouldInitializeAllMetadata)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c383c28c5e0420c55cfdfed7d1e9f26">processMachineFunction</a> (AbstractSlotTrackerStorage *AST, const Function *F, bool ShouldInitializeAllMetadata)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da809fadb75184e91499633b8ef6b18">TheFunction</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897d6eb12dc1cf302d4971eb53f13b81">TheMMI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d651c1c41b765533bb014e5a1d95b1">MDNStartSlot</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4935be2763fe63c5dda3db15ebff1032">MDNEndSlot</a> = 0</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineModuleSlotTracker() {#ad46f7561b1384a882cfabf8ef2b7326c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleSlotTracker::MachineModuleSlotTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, bool ShouldInitializeAllMetadata=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleslottracker-cpp">MachineModuleSlotTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a2151720842982c4facf057f92f5ec500">llvm::ModuleSlotTracker::ModuleSlotTracker</a> and <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#aa61b8a507ee7183bce9f0656efd5d492">llvm::ModuleSlotTracker::setProcessHook</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineModuleSlotTracker() {#a71722f40d1ad8dd65847bae0d9625ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleSlotTracker::~MachineModuleSlotTracker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectMachineMDNodes() {#aac196d286114a87387bcd505f13c5d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleSlotTracker::collectMachineMDNodes (<a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a6aef0029425988cbe468cf78bf898bdb">MachineMDNodeListType</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleslottracker-cpp">MachineModuleSlotTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a7ee16368586349a8a3d889fd848a0a39">llvm::ModuleSlotTracker::collectMDNodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#ae7de4da09df7011d92c1f4abd46134a2">llvm::MIRPrinter::convertMachineMetadataNodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### processMachineFunction() {#a9c383c28c5e0420c55cfdfed7d1e9f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleSlotTracker::processMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/abstractslottrackerstorage">AbstractSlotTrackerStorage</a> * AST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, bool ShouldInitializeAllMetadata)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleslottracker-cpp">MachineModuleSlotTracker.cpp</a>.</p>

</div>
</div>

### processMachineFunctionMetadata() {#aeec7851423d8367967470047ae9fd076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleSlotTracker::processMachineFunctionMetadata (<a href="/web-llvm/docs/api/classes/llvm/abstractslottrackerstorage">AbstractSlotTrackerStorage</a> * AST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleslottracker-cpp">MachineModuleSlotTracker.cpp</a>.</p>

</div>
</div>

### processMachineModule() {#a2825db30b6a23e752f142546d71a511b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleSlotTracker::processMachineModule (<a href="/web-llvm/docs/api/classes/llvm/abstractslottrackerstorage">AbstractSlotTrackerStorage</a> * AST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, bool ShouldInitializeAllMetadata)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleslottracker-cpp">MachineModuleSlotTracker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MDNEndSlot {#a4935be2763fe63c5dda3db15ebff1032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineModuleSlotTracker::MDNEndSlot = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>.</p>

</div>
</div>

### MDNStartSlot {#aa1d651c1c41b765533bb014e5a1d95b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineModuleSlotTracker::MDNStartSlot = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>.</p>

</div>
</div>

### TheFunction {#a2da809fadb75184e91499633b8ef6b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function&amp; llvm::MachineModuleSlotTracker::TheFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>.</p>

</div>
</div>

### TheMMI {#a897d6eb12dc1cf302d4971eb53f13b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineModuleInfo&amp; llvm::MachineModuleSlotTracker::TheMMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleslottracker-h">MachineModuleSlotTracker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleslottracker-cpp">MachineModuleSlotTracker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
