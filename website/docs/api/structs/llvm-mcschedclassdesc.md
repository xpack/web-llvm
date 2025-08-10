---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mcschedclassdesc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MCSchedClassDesc` Struct

<p>Summarize the scheduling resources required for an instruction of a particular scheduling class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MCSchedClassDesc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">llvm/MC/MCSchedule.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f7e8be243cde4843e2854d91bfa082">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a9a1303240e655d7c3efb1057b8e7a6">isVariant</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31b059b2a720d51c88a426539fa798c">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7b0ef1f5af7f95492f8bf39415123f2">NumMicroOps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b8909fd59169650f6fb6641a14ef7e">BeginGroup</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f573c4449021d09816cb0071d6fd9f2">EndGroup</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b0543cb51274908d84e1ec28c2e68f0">RetireOOO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7850c73a920bc955191ac8a388001685">WriteProcResIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcbad6df7e8d8c64c9944310967daac2">NumWriteProcResEntries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ccc40dcd0cf74dd6db784b0d56986f5">WriteLatencyIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eaebfb37c3f693c9b1644c38969d4c9">NumWriteLatencyEntries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0877db2dd00a3e65f88212756e5e3814">ReadAdvanceIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf852a03b56b36b08ed6b0d0bd221f1c">NumReadAdvanceEntries</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50089886ed3b164c779bb42fd2c3d52b">InvalidNumMicroOps</a> = (1U &lt;&lt; 13) - 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9af73b59bc7e0c387fc0a8b3b3e21a9">VariantNumMicroOps</a> = <a href="#a50089886ed3b164c779bb42fd2c3d52b">InvalidNumMicroOps</a> - 1</td>
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

<p>Summarize the scheduling resources required for an instruction of a particular scheduling class.</p>


<p>Defined as an aggregate struct for creating tables with initializer lists.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### isValid() {#a03f7e8be243cde4843e2854d91bfa082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSchedClassDesc::isValid ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>References <a href="#a50089886ed3b164c779bb42fd2c3d52b">InvalidNumMicroOps</a> and <a href="#ab7b0ef1f5af7f95492f8bf39415123f2">NumMicroOps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machinepipeliner-cpp-/funcunitsorter/#a7cb298b17050125133aeba2fdba44299">anonymous{MachinePipeliner.cpp}::FuncUnitSorter::calcCriticalResources</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#a13a8c4d3fbc72e8e2f7080411e2ea9cf">llvm::ResourceManager::calculateResMII</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#adfd05fb40b63f3fde78a81e119ed89e3">llvm::ResourceManager::canReserveResources</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac4e5dcb952f0c76bcbb366a37077ecce">llvm::MCSchedModel::computeInstrLatency</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ab7a645c3e2848203bdde8f7db2bff845">llvm::MCSchedModel::computeInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a486f9d8524dbb66766ea27c02709d3c7">llvm::TargetSchedModel::computeInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#abe764852febe90b22412f1acf299fb9e">llvm::TargetSchedModel::computeOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a5a00ff1e3eb19fe4001d742d93f8fade">llvm::TargetSchedModel::computeOutputLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a1b043aa01b559cc6f27b63a85332884b">llvm::TargetSchedModel::computeReciprocalThroughput</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac080bbec97a31ee8728ca9828700ad45">llvm::MCSchedModel::getReciprocalThroughput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp/#a82123100de61eeb10ee4fde2a11c1bec">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinepipeliner-cpp-/funcunitsorter/#a64d0e66977892f563370dbbcde3b8fc1">anonymous{MachinePipeliner.cpp}::FuncUnitSorter::minFuncUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#a66b0369aaa8c87a6969ec5b56700d0d8">llvm::ResourceManager::reserveResources</a> and <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#aad3a46af0e50906ff7193aa923b80c65">llvm::TargetSchedModel::resolveSchedClass</a>.</p>

</div>
</div>

### isVariant() {#a4a9a1303240e655d7c3efb1057b8e7a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSchedClassDesc::isVariant ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>References <a href="#ab7b0ef1f5af7f95492f8bf39415123f2">NumMicroOps</a> and <a href="#af9af73b59bc7e0c387fc0a8b3b3e21a9">VariantNumMicroOps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ab7a645c3e2848203bdde8f7db2bff845">llvm::MCSchedModel::computeInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a1b043aa01b559cc6f27b63a85332884b">llvm::TargetSchedModel::computeReciprocalThroughput</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac080bbec97a31ee8728ca9828700ad45">llvm::MCSchedModel::getReciprocalThroughput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64simdinstropt-cpp/#a82123100de61eeb10ee4fde2a11c1bec">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#aad3a46af0e50906ff7193aa923b80c65">llvm::TargetSchedModel::resolveSchedClass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BeginGroup {#a69b8909fd59169650f6fb6641a14ef7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::BeginGroup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>.</p>

</div>
</div>

### EndGroup {#a7f573c4449021d09816cb0071d6fd9f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::EndGroup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>.</p>

</div>
</div>

### Name {#ae31b059b2a720d51c88a426539fa798c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::MCSchedClassDesc::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>.</p>

</div>
</div>

### NumMicroOps {#ab7b0ef1f5af7f95492f8bf39415123f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::NumMicroOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#a13a8c4d3fbc72e8e2f7080411e2ea9cf">llvm::ResourceManager::calculateResMII</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ae119a8f604442c5d6b0abb586d6aa03e">llvm::MCSchedModel::getReciprocalThroughput</a>, <a href="#a03f7e8be243cde4843e2854d91bfa082">isValid</a> and <a href="#a4a9a1303240e655d7c3efb1057b8e7a6">isVariant</a>.</p>

</div>
</div>

### NumReadAdvanceEntries {#aaf852a03b56b36b08ed6b0d0bd221f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::NumReadAdvanceEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#abe764852febe90b22412f1acf299fb9e">llvm::TargetSchedModel::computeOperandLatency</a>.</p>

</div>
</div>

### NumWriteLatencyEntries {#a5eaebfb37c3f693c9b1644c38969d4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::NumWriteLatencyEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a87b307b08bc0acbbf95fab6bca87983c">llvm::MCSchedModel::computeInstrLatency</a>.</p>

</div>
</div>

### NumWriteProcResEntries {#abcbad6df7e8d8c64c9944310967daac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::NumWriteProcResEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>.</p>

</div>
</div>

### ReadAdvanceIdx {#a0877db2dd00a3e65f88212756e5e3814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::ReadAdvanceIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

### RetireOOO {#a9b0543cb51274908d84e1ec28c2e68f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::RetireOOO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#afe394be08220c92f22489a0f952d39ee">llvm::mca::InstrBuilder::createInstruction</a>.</p>

</div>
</div>

### WriteLatencyIdx {#a7ccc40dcd0cf74dd6db784b0d56986f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::WriteLatencyIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

### WriteProcResIdx {#a7850c73a920bc955191ac8a388001685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCSchedClassDesc::WriteProcResIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### InvalidNumMicroOps {#a50089886ed3b164c779bb42fd2c3d52b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned short llvm::MCSchedClassDesc::InvalidNumMicroOps = (1U &lt;&lt; 13) - 1</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#a03f7e8be243cde4843e2854d91bfa082">isValid</a>.</p>

</div>
</div>

### VariantNumMicroOps {#af9af73b59bc7e0c387fc0a8b3b3e21a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned short llvm::MCSchedClassDesc::VariantNumMicroOps = <a href="#a50089886ed3b164c779bb42fd2c3d52b">InvalidNumMicroOps</a> - 1</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#a4a9a1303240e655d7c3efb1057b8e7a6">isVariant</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
