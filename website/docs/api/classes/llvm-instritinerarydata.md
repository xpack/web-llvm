---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instritinerarydata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstrItineraryData` Class Reference

<p>Itinerary data supplied by a subtarget to be used by a target. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InstrItineraryData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">llvm/MC/MCInstrItineraries.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac56cf30888e6ece9481d748dc06eca78">InstrItineraryData</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8232a821e649877de8f0db96cc5afac">InstrItineraryData</a> (const MCSchedModel &amp;SM, const InstrStage *S, const unsigned *OS, const unsigned *F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe6bc9136f849e9b46fbccf620b3409">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there are no itineraries. <a href="#affe6bc9136f849e9b46fbccf620b3409">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5444e9509ebf2f90a116001248300120">isEndMarker</a> (unsigned ItinClassIndx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the index is for the end marker itinerary. <a href="#a5444e9509ebf2f90a116001248300120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrstage">InstrStage</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7327da535eb156175c5a9ec7b7fea629">beginStage</a> (unsigned ItinClassIndx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first stage of the itinerary. <a href="#a7327da535eb156175c5a9ec7b7fea629">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrstage">InstrStage</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4cf1d46c5e7c0f1f877c2cd4f834a8">endStage</a> (unsigned ItinClassIndx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last+1 stage of the itinerary. <a href="#adb4cf1d46c5e7c0f1f877c2cd4f834a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51623c0621a7c092ac9210065f861a33">getStageLatency</a> (unsigned ItinClassIndx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the total stage latency of the given class. <a href="#a51623c0621a7c092ac9210065f861a33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb39c8a77b3091e6a569fe24055e06f">getOperandCycle</a> (unsigned ItinClassIndx, unsigned OperandIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cycle for the given class and operand. <a href="#a0fb39c8a77b3091e6a569fe24055e06f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94e1f552980744a8937ef75c00232c8d">hasPipelineForwarding</a> (unsigned DefClass, unsigned DefIdx, unsigned UseClass, unsigned UseIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is a pipeline forwarding between instructions of itinerary classes DefClass and UseClasses so that value produced by an instruction of itinerary class DefClass, operand index DefIdx can be bypassed when it's read by an instruction of itinerary class UseClass, operand index UseIdx. <a href="#a94e1f552980744a8937ef75c00232c8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a702e147674b97e4ec87922e263e1ca73">getOperandLatency</a> (unsigned DefClass, unsigned DefIdx, unsigned UseClass, unsigned UseIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and return the use operand latency of a given itinerary class and operand index if the value is produced by an instruction of the specified itinerary class and def operand index. <a href="#a702e147674b97e4ec87922e263e1ca73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035351039a05ded742d1958d3d63d92b">getNumMicroOps</a> (unsigned ItinClassIndx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of micro-ops that the given class decodes to. <a href="#a035351039a05ded742d1958d3d63d92b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a869c0916b27a3b9990abe48e2ff9b3c6">SchedModel</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Basic machine properties. <a href="#a869c0916b27a3b9990abe48e2ff9b3c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrstage">InstrStage</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a932c41180f005df409d7a78ab84d45">Stages</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Array of stages selected. <a href="#a2a932c41180f005df409d7a78ab84d45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f429bbda07a9bc2cec72092dfd1a97">OperandCycles</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Array of operand cycles selected. <a href="#ae7f429bbda07a9bc2cec72092dfd1a97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d1dc9148e002610c21c5644f412eeb">Forwardings</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Array of pipeline forwarding paths. <a href="#ac2d1dc9148e002610c21c5644f412eeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instritinerary">InstrItinerary</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1bc954cd72ba2c13fd0d00fd47343a9">Itineraries</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Array of itineraries selected. <a href="#af1bc954cd72ba2c13fd0d00fd47343a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Itinerary data supplied by a subtarget to be used by a target.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrItineraryData() {#ac56cf30888e6ece9481d748dc06eca78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrItineraryData::InstrItineraryData ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>

</div>
</div>

### InstrItineraryData() {#ab8232a821e649877de8f0db96cc5afac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrItineraryData::InstrItineraryData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrstage">InstrStage</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned * OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned * F)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ac2d1dc9148e002610c21c5644f412eeb">Forwardings</a>, <a href="#af1bc954cd72ba2c13fd0d00fd47343a9">Itineraries</a>, <a href="#ae7f429bbda07a9bc2cec72092dfd1a97">OperandCycles</a>, <a href="#a869c0916b27a3b9990abe48e2ff9b3c6">SchedModel</a> and <a href="#a2a932c41180f005df409d7a78ab84d45">Stages</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### beginStage() {#a7327da535eb156175c5a9ec7b7fea629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrStage * llvm::InstrItineraryData::beginStage (unsigned ItinClassIndx)</td>
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

<p>Return the first stage of the itinerary.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>References <a href="#af1bc954cd72ba2c13fd0d00fd47343a9">Itineraries</a> and <a href="#a2a932c41180f005df409d7a78ab84d45">Stages</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#aee2c79683d10f7414452500ae1210f0a">llvm::MCSchedModel::getReciprocalThroughput</a> and <a href="#a51623c0621a7c092ac9210065f861a33">getStageLatency</a>.</p>

</div>
</div>

### endStage() {#adb4cf1d46c5e7c0f1f877c2cd4f834a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrStage * llvm::InstrItineraryData::endStage (unsigned ItinClassIndx)</td>
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

<p>Return the last+1 stage of the itinerary.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>References <a href="#af1bc954cd72ba2c13fd0d00fd47343a9">Itineraries</a> and <a href="#a2a932c41180f005df409d7a78ab84d45">Stages</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#aee2c79683d10f7414452500ae1210f0a">llvm::MCSchedModel::getReciprocalThroughput</a> and <a href="#a51623c0621a7c092ac9210065f861a33">getStageLatency</a>.</p>

</div>
</div>

### getNumMicroOps() {#a035351039a05ded742d1958d3d63d92b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InstrItineraryData::getNumMicroOps (unsigned ItinClassIndx)</td>
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

<p>Return the number of micro-ops that the given class decodes to.</p>


<p>Return -1 for classes that require dynamic lookup via <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a>.</p>


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>References <a href="#affe6bc9136f849e9b46fbccf620b3409">isEmpty</a> and <a href="#af1bc954cd72ba2c13fd0d00fd47343a9">Itineraries</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a41289ca8ad61ff8ab86bc82a0afd8e1c">llvm::ARMBaseInstrInfo::getNumMicroOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a546b8cefb687c85f2a1383240bb5f4da">getNumMicroOpsSwiftLdSt</a>.</p>

</div>
</div>

### getOperandCycle() {#a0fb39c8a77b3091e6a569fe24055e06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::InstrItineraryData::getOperandCycle (unsigned ItinClassIndx, unsigned OperandIdx)</td>
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

<p>Return the cycle for the given class and operand.</p>


<p>Return std::nullopt if the information is not available for the operand.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>References <a href="#affe6bc9136f849e9b46fbccf620b3409">isEmpty</a>, <a href="#af1bc954cd72ba2c13fd0d00fd47343a9">Itineraries</a> and <a href="#ae7f429bbda07a9bc2cec72092dfd1a97">OperandCycles</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ac4e5dcb952f0c76bcbb366a37077ecce">llvm::MCSchedModel::computeInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aa88dfb98a274ef5f8da3ce147c8c45eb">llvm::PPCInstrInfo::getInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="#a702e147674b97e4ec87922e263e1ca73">getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa65c4a19ddc8ce7ddec084e5a1a4a62a">llvm::TargetInstrInfo::getOperandLatency</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0aa73253579dd1c4acde85953454e838">llvm::TargetInstrInfo::hasLowDefLatency</a>.</p>

</div>
</div>

### getOperandLatency() {#a702e147674b97e4ec87922e263e1ca73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::InstrItineraryData::getOperandLatency (unsigned DefClass, unsigned DefIdx, unsigned UseClass, unsigned UseIdx)</td>
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

<p>Compute and return the use operand latency of a given itinerary class and operand index if the value is produced by an instruction of the specified itinerary class and def operand index.</p>


<p>Return std::nullopt if the information is not available for the operand.</p>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>References <a href="#a0fb39c8a77b3091e6a569fe24055e06f">getOperandCycle</a>, <a href="#a94e1f552980744a8937ef75c00232c8d">hasPipelineForwarding</a> and <a href="#affe6bc9136f849e9b46fbccf620b3409">isEmpty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a9b1e693dee703f46fd28221e99d4acff">llvm::TargetInstrInfo::getOperandLatency</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa65c4a19ddc8ce7ddec084e5a1a4a62a">llvm::TargetInstrInfo::getOperandLatency</a>.</p>

</div>
</div>

### getStageLatency() {#a51623c0621a7c092ac9210065f861a33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InstrItineraryData::getStageLatency (unsigned ItinClassIndx)</td>
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

<p>Return the total stage latency of the given class.</p>


<p>The latency is the maximum completion time for any stage in the itinerary. If no stages exist, it defaults to one cycle.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>References <a href="#a7327da535eb156175c5a9ec7b7fea629">beginStage</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#adb4cf1d46c5e7c0f1f877c2cd4f834a8">endStage</a>, <a href="#affe6bc9136f849e9b46fbccf620b3409">isEmpty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ac45af359a246cde99ce09578e3998985">llvm::TargetInstrInfo::getInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a86ea143f1ea40632ba851badcf377101">llvm::TargetInstrInfo::getInstrLatency</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a72d325594d9e663ccddea2f07dfaabac">llvm::HexagonInstrInfo::getInstrTimingClassLatency</a>.</p>

</div>
</div>

### hasPipelineForwarding() {#a94e1f552980744a8937ef75c00232c8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrItineraryData::hasPipelineForwarding (unsigned DefClass, unsigned DefIdx, unsigned UseClass, unsigned UseIdx)</td>
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

<p>Return true if there is a pipeline forwarding between instructions of itinerary classes DefClass and UseClasses so that value produced by an instruction of itinerary class DefClass, operand index DefIdx can be bypassed when it's read by an instruction of itinerary class UseClass, operand index UseIdx.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>References <a href="#ac2d1dc9148e002610c21c5644f412eeb">Forwardings</a> and <a href="#af1bc954cd72ba2c13fd0d00fd47343a9">Itineraries</a>.</p>


<p>Referenced by <a href="#a702e147674b97e4ec87922e263e1ca73">getOperandLatency</a>.</p>

</div>
</div>

### isEmpty() {#affe6bc9136f849e9b46fbccf620b3409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrItineraryData::isEmpty ()</td>
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

<p>Returns true if there are no itineraries.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Reference <a href="#af1bc954cd72ba2c13fd0d00fd47343a9">Itineraries</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a86ea143f1ea40632ba851badcf377101">llvm::TargetInstrInfo::getInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a41289ca8ad61ff8ab86bc82a0afd8e1c">llvm::ARMBaseInstrInfo::getNumMicroOps</a>, <a href="#a035351039a05ded742d1958d3d63d92b">getNumMicroOps</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a16bf43322793449e23ced7810ac16ecb">llvm::TargetInstrInfo::getNumMicroOps</a>, <a href="#a0fb39c8a77b3091e6a569fe24055e06f">getOperandCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="#a702e147674b97e4ec87922e263e1ca73">getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa65c4a19ddc8ce7ddec084e5a1a4a62a">llvm::TargetInstrInfo::getOperandLatency</a>, <a href="#a51623c0621a7c092ac9210065f861a33">getStageLatency</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0aa73253579dd1c4acde85953454e838">llvm::TargetInstrInfo::hasLowDefLatency</a>.</p>

</div>
</div>

### isEndMarker() {#a5444e9509ebf2f90a116001248300120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrItineraryData::isEndMarker (unsigned ItinClassIndx)</td>
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

<p>Returns true if the index is for the end marker itinerary.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Reference <a href="#af1bc954cd72ba2c13fd0d00fd47343a9">Itineraries</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Forwardings {#ac2d1dc9148e002610c21c5644f412eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned* llvm::InstrItineraryData::Forwardings = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Array of pipeline forwarding paths.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Referenced by <a href="#a94e1f552980744a8937ef75c00232c8d">hasPipelineForwarding</a> and <a href="#ab8232a821e649877de8f0db96cc5afac">InstrItineraryData</a>.</p>

</div>
</div>

### Itineraries {#af1bc954cd72ba2c13fd0d00fd47343a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItinerary* llvm::InstrItineraryData::Itineraries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Array of itineraries selected.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      nullptr
</div>
</dd>
</dl>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Referenced by <a href="#a7327da535eb156175c5a9ec7b7fea629">beginStage</a>, <a href="#adb4cf1d46c5e7c0f1f877c2cd4f834a8">endStage</a>, <a href="#a035351039a05ded742d1958d3d63d92b">getNumMicroOps</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a16bf43322793449e23ced7810ac16ecb">llvm::TargetInstrInfo::getNumMicroOps</a>, <a href="#a0fb39c8a77b3091e6a569fe24055e06f">getOperandCycle</a>, <a href="#a94e1f552980744a8937ef75c00232c8d">hasPipelineForwarding</a>, <a href="#ab8232a821e649877de8f0db96cc5afac">InstrItineraryData</a>, <a href="#affe6bc9136f849e9b46fbccf620b3409">isEmpty</a> and <a href="#a5444e9509ebf2f90a116001248300120">isEndMarker</a>.</p>

</div>
</div>

### OperandCycles {#ae7f429bbda07a9bc2cec72092dfd1a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned* llvm::InstrItineraryData::OperandCycles = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Array of operand cycles selected.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Referenced by <a href="#a0fb39c8a77b3091e6a569fe24055e06f">getOperandCycle</a> and <a href="#ab8232a821e649877de8f0db96cc5afac">InstrItineraryData</a>.</p>

</div>
</div>

### SchedModel {#a869c0916b27a3b9990abe48e2ff9b3c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSchedModel llvm::InstrItineraryData::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Basic machine properties.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a090d8f8a40ae8bd7f4ac776d186d0203">MCSchedModel::Default</a>
</div>
</dd>
</dl>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Referenced by <a href="#ab8232a821e649877de8f0db96cc5afac">InstrItineraryData</a>.</p>

</div>
</div>

### Stages {#a2a932c41180f005df409d7a78ab84d45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrStage* llvm::InstrItineraryData::Stages = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Array of stages selected.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Referenced by <a href="#a7327da535eb156175c5a9ec7b7fea629">beginStage</a>, <a href="#adb4cf1d46c5e7c0f1f877c2cd4f834a8">endStage</a> and <a href="#ab8232a821e649877de8f0db96cc5afac">InstrItineraryData</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
