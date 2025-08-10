---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mcschedmodel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MCSchedModel` Struct

<p>Machine model for scheduling, bundling, and heuristics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MCSchedModel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">llvm/MC/MCSchedule.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f622a0eb535373587d2e08d14eb1a76">InstrItineraryData</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20ed429316e50733da37685169d39f68">hasExtraProcessorInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ecfe5545130090b71f09f178effa55">getProcessorID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68fa67076e0244cf21e80f2c43b6fa02">hasInstrSchedModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this machine model include instruction-level scheduling. <a href="#a68fa67076e0244cf21e80f2c43b6fa02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcextraprocessorinfo">MCExtraProcessorInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f78162e652232c8233dcb3967834780">getExtraProcessorInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af541a495f189de322fedcb22bb236124">isComplete</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this machine model data for all instructions with a scheduling class (itinerary class or SchedRW list). <a href="#af541a495f189de322fedcb22bb236124">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c82641b0ce9632ce1baaf54a71db6e">isOutOfOrder</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if machine supports out of order execution. <a href="#a17c82641b0ce9632ce1baaf54a71db6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5268bc4b5673e84a8f75df74b024d374">getNumProcResourceKinds</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc">MCProcResourceDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7376c4db05cd0fbb107dd0b1fecc9ba">getProcResource</a> (unsigned ProcResourceIdx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3837bacedb8dfa32c6a3b949bfdd6877">getSchedClassDesc</a> (unsigned SchedClassIdx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7a645c3e2848203bdde8f7db2bff845">computeInstrLatency</a> (const MCSubtargetInfo &amp;STI, unsigned SClass) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09947650a7df617e008df474a1388b6">computeInstrLatency</a> (const MCSubtargetInfo &amp;STI, const MCInstrInfo &amp;MCII, const MCInst &amp;Inst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac4e5dcb952f0c76bcbb366a37077ecce">computeInstrLatency</a> (const MCSubtargetInfo &amp;STI, const MCInstrInfo &amp;MCII, const MCInstOrMachineInstr &amp;Inst, llvm::function_ref&lt; const MCSchedClassDesc *(const MCSchedClassDesc *)&gt; ResolveVariantSchedClass=[](const MCSchedClassDesc *SCDesc) { return SCDesc;}) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac080bbec97a31ee8728ca9828700ad45">getReciprocalThroughput</a> (const MCSubtargetInfo &amp;STI, const MCInstrInfo &amp;MCII, const MCInst &amp;Inst) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f11354e854441ac5fefd72d91dd8ee">IssueWidth</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaca528ae14befaac95c11df31faf36b">MicroOpBufferSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a33138b76ebc2cae1b3cf65411a9e6">LoopMicroOpBufferSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077ff8557ccaf81471558635ca37f7a3">LoadLatency</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26358cf24f3d0a23e6dee0bf807061be">HighLatency</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af664056329bd39a8610479a584e4b2f7">MispredictPenalty</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a217252d2d49715e81f43a0d313e4f646">PostRAScheduler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a312b576ca5c909cbff1e85ba2cb65">CompleteModel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e1ea4e27bcba230e5f86df65af8636">EnableIntervals</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc3246f3710fe97ff81dd87bc054b1d">ProcID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc">MCProcResourceDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ee2bb9fa1d41b69c587580e157f6fa">ProcResourceTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0cca41833e3be960d97a296a2f58ff2">SchedClassTable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec103d6812b2bfd0489d48ecb3148e3d">NumProcResourceKinds</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab08090fb8f3a647be37d191b92a1c0b5">NumSchedClasses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instritinerary">InstrItinerary</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e6e84ef828ad8129b514f898fbbf8c">InstrItineraries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcextraprocessorinfo">MCExtraProcessorInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac52ec5efbce3915a63171827440096f8">ExtraProcessorInfo</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b307b08bc0acbbf95fab6bca87983c">computeInstrLatency</a> (const MCSubtargetInfo &amp;STI, const MCSchedClassDesc &amp;SCDesc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the latency value for the scheduling class. <a href="#a87b307b08bc0acbbf95fab6bca87983c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae119a8f604442c5d6b0abb586d6aa03e">getReciprocalThroughput</a> (const MCSubtargetInfo &amp;STI, const MCSchedClassDesc &amp;SCDesc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee2c79683d10f7414452500ae1210f0a">getReciprocalThroughput</a> (unsigned SchedClass, const InstrItineraryData &amp;IID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ffebbabe0c187d8c92743daf4e83edb">getForwardingDelayCycles</a> (ArrayRef&lt; MCReadAdvanceEntry &gt; Entries, unsigned WriteResourceIdx=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum forwarding delay for register reads dependent on writes of scheduling class WriteResourceIdx. <a href="#a2ffebbabe0c187d8c92743daf4e83edb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea43dda92a2d44bcad9ac8b8b174083d">DefaultIssueWidth</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a10a315de4fe27b96441bba140667a">DefaultMicroOpBufferSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318f6bd038b41e5318769859b0682f53">DefaultLoopMicroOpBufferSize</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cd425228c2c4565e4308d74e2eb403b">DefaultLoadLatency</a> = 4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f1eefb7b52cfe5876f9a8671e8eead">DefaultHighLatency</a> = 10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa77d6093fb6e4dbfdef6ec063cfcc627">DefaultMispredictPenalty</a> = 10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a090d8f8a40ae8bd7f4ac776d186d0203">Default</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the default initialized model. <a href="#a090d8f8a40ae8bd7f4ac776d186d0203">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Machine model for scheduling, bundling, and heuristics.</p>


<p>The machine model directly provides basic information about the microarchitecture to the scheduler in the form of properties. It also optionally refers to scheduler resource tables and itinerary tables. Scheduler resource tables model the latency and cost for each instruction type. Itinerary tables are an independent mechanism that provides a detailed reservation table describing each cycle of instruction execution. Subtargets may define any or all of the above categories of data depending on the type of CPU and selected scheduler.</p>


<p>The machine independent properties defined here are used by the scheduler as an abstract machine model. A real micro-architecture has a number of buffers, queues, and stages. Declaring that a given machine-independent abstract property corresponds to a specific physical property across all subtargets can't be done. Nonetheless, the abstract model is useful. Futhermore, subtargets typically extend this model with processor specific resources to model any hardware features that can be exploited by scheduling heuristics and aren't sufficiently represented in the abstract.</p>


<p>The abstract pipeline is built around the notion of an "issue point". This is merely a reference point for counting machine cycles. The physical machine will have pipeline stages that delay execution. The scheduler does not model those delays because they are irrelevant as long as they are consistent. Inaccuracies arise when instructions have different execution delays relative to each other, in addition to their intrinsic latency. Those special cases can be handled by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> constructs such as, ReadAdvance, which reduces latency when reading data, and ReleaseAtCycles, which consumes a processor resource when writing data for a number of abstract cycles.</p>


<p>TODO: One tool currently missing is the ability to add a delay to ReleaseAtCycles. That would be easy to add and would likely cover all cases currently handled by the legacy itinerary tables.</p>


<p>A note on out-of-order execution and, more generally, instruction buffers. Part of the CPU pipeline is always in-order. The issue point, which is the point of reference for counting cycles, only makes sense as an in-order part of the pipeline. Other parts of the pipeline are sometimes falling behind and sometimes catching up. It's only interesting to model those other, decoupled parts of the pipeline if they may be predictably resource constrained in a way that the scheduler can exploit.</p>


<p>The LLVM machine model distinguishes between in-order constraints and out-of-order constraints so that the target's scheduling strategy can apply appropriate heuristics. For a well-balanced CPU pipeline, out-of-order resources would not typically be treated as a hard scheduling constraint. For example, in the <a href="/web-llvm/docs/api/classes/llvm/genericscheduler">GenericScheduler</a>, a delay caused by limited out-of-order resources is not directly reflected in the number of cycles that the scheduler sees between issuing an instruction and its dependent instructions. In other words, out-of-order resources don't directly increase the latency between pairs of instructions. However, they can still be used to detect potential bottlenecks across a sequence of instructions and bias the scheduling heuristics appropriately.</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<div class="doxySectionDef">

## Friends

### InstrItineraryData {#a8f622a0eb535373587d2e08d14eb1a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Reference <a href="#a8f622a0eb535373587d2e08d14eb1a76">InstrItineraryData</a>.</p>


<p>Referenced by <a href="#ad09947650a7df617e008df474a1388b6">computeInstrLatency</a>, <a href="#ac4e5dcb952f0c76bcbb366a37077ecce">computeInstrLatency</a>, <a href="#aee2c79683d10f7414452500ae1210f0a">getReciprocalThroughput</a> and <a href="#a8f622a0eb535373587d2e08d14eb1a76">InstrItineraryData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeInstrLatency() {#ab7a645c3e2848203bdde8f7db2bff845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MCSchedModel::computeInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, unsigned SClass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcschedule-cpp">MCSchedule.cpp</a>.</p>


<p>References <a href="#a87b307b08bc0acbbf95fab6bca87983c">computeInstrLatency</a>, <a href="#a3837bacedb8dfa32c6a3b949bfdd6877">getSchedClassDesc</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a4a9a1303240e655d7c3efb1057b8e7a6">llvm::MCSchedClassDesc::isVariant</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### computeInstrLatency() {#ad09947650a7df617e008df474a1388b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MCSchedModel::computeInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcschedule-cpp">MCSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a87b307b08bc0acbbf95fab6bca87983c">computeInstrLatency</a>, <a href="#a45ecfe5545130090b71f09f178effa55">getProcessorID</a>, <a href="#a3837bacedb8dfa32c6a3b949bfdd6877">getSchedClassDesc</a>, <a href="#a8f622a0eb535373587d2e08d14eb1a76">InstrItineraryData</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a18de37f60c9c80f7974dbf8dfd3795cb">llvm::MCSubtargetInfo::resolveVariantSchedClass</a>.</p>

</div>
</div>

### computeInstrLatency() {#ac4e5dcb952f0c76bcbb366a37077ecce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MCSubtargetInfo, typename MCInstrInfo, typename InstrItineraryData, typename MCInstOrMachineInstr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MCSchedModel::computeInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MCInstOrMachineInstr &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> *(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> *)&gt; ResolveVariantSchedClass=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> *SCDesc) { return SCDesc;})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>References <a href="#a87b307b08bc0acbbf95fab6bca87983c">computeInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#ab1512f856548a309c48c6dc944d7db7e">llvm::MCSubtargetInfo::getInstrItineraryForCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a0fb39c8a77b3091e6a569fe24055e06f">llvm::InstrItineraryData::getOperandCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a03a564c2840cb8d27314596549fc04b8">llvm::MCInstrDesc::getSchedClass</a>, <a href="#a3837bacedb8dfa32c6a3b949bfdd6877">getSchedClassDesc</a>, <a href="#a68fa67076e0244cf21e80f2c43b6fa02">hasInstrSchedModel</a>, <a href="#a8f622a0eb535373587d2e08d14eb1a76">InstrItineraryData</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>.</p>

</div>
</div>

### getExtraProcessorInfo() {#a4f78162e652232c8233dcb3967834780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExtraProcessorInfo &amp; llvm::MCSchedModel::getExtraProcessorInfo ()</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac52ec5efbce3915a63171827440096f8">ExtraProcessorInfo</a> and <a href="#a20ed429316e50733da37685169d39f68">hasExtraProcessorInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mca/retirecontrolunit/#a90de9bdaf1a6c428ea958a2850bdc6a9">llvm::mca::RetireControlUnit::RetireControlUnit</a>.</p>

</div>
</div>

### getNumProcResourceKinds() {#a5268bc4b5673e84a8f75df74b024d374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::getNumProcResourceKinds ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Reference <a href="#aec103d6812b2bfd0489d48ecb3148e3d">NumProcResourceKinds</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a0a98238e0b4ad204e6bf241ab4cefe47">llvm::mca::computeBlockRThroughput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae1d3c5a1f43dcec43774a3767b41e447">llvm::mca::computeProcResourceMasks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#a54e306500b1968dcb5c02cb0570675bf">llvm::mca::InstrBuilder::InstrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a7d000778dc6adcdb34b656a83939800a">llvm::mca::ResourceManager::ResourceManager</a>.</p>

</div>
</div>

### getProcessorID() {#a45ecfe5545130090b71f09f178effa55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::getProcessorID ()</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Reference <a href="#a6cc3246f3710fe97ff81dd87bc054b1d">ProcID</a>.</p>


<p>Referenced by <a href="#ad09947650a7df617e008df474a1388b6">computeInstrLatency</a> and <a href="#ac080bbec97a31ee8728ca9828700ad45">getReciprocalThroughput</a>.</p>

</div>
</div>

### getProcResource() {#ac7376c4db05cd0fbb107dd0b1fecc9ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCProcResourceDesc * llvm::MCSchedModel::getProcResource (unsigned ProcResourceIdx)</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a68fa67076e0244cf21e80f2c43b6fa02">hasInstrSchedModel</a>, <a href="#aec103d6812b2bfd0489d48ecb3148e3d">NumProcResourceKinds</a> and <a href="#aa0ee2bb9fa1d41b69c587580e157f6fa">ProcResourceTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a0a98238e0b4ad204e6bf241ab4cefe47">llvm::mca::computeBlockRThroughput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae1d3c5a1f43dcec43774a3767b41e447">llvm::mca::computeProcResourceMasks</a>, <a href="#ae119a8f604442c5d6b0abb586d6aa03e">getReciprocalThroughput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a7d000778dc6adcdb34b656a83939800a">llvm::mca::ResourceManager::ResourceManager</a>.</p>

</div>
</div>

### getReciprocalThroughput() {#ac080bbec97a31ee8728ca9828700ad45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double MCSchedModel::getReciprocalThroughput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcschedule-cpp">MCSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="#a45ecfe5545130090b71f09f178effa55">getProcessorID</a>, <a href="#ae119a8f604442c5d6b0abb586d6aa03e">getReciprocalThroughput</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a03a564c2840cb8d27314596549fc04b8">llvm::MCInstrDesc::getSchedClass</a>, <a href="#a3837bacedb8dfa32c6a3b949bfdd6877">getSchedClassDesc</a>, <a href="#ac0f11354e854441ac5fefd72d91dd8ee">IssueWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a4a9a1303240e655d7c3efb1057b8e7a6">llvm::MCSchedClassDesc::isVariant</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a18de37f60c9c80f7974dbf8dfd3795cb">llvm::MCSubtargetInfo::resolveVariantSchedClass</a>.</p>

</div>
</div>

### getSchedClassDesc() {#a3837bacedb8dfa32c6a3b949bfdd6877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedClassDesc * llvm::MCSchedModel::getSchedClassDesc (unsigned SchedClassIdx)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a68fa67076e0244cf21e80f2c43b6fa02">hasInstrSchedModel</a>, <a href="#ab08090fb8f3a647be37d191b92a1c0b5">NumSchedClasses</a> and <a href="#aa0cca41833e3be960d97a296a2f58ff2">SchedClassTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#aa27ad78489e8c685d427e45e6c4bc14d">llvm::mca::RegisterFile::addRegisterRead</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a6f9761f8807ef5c507cadfd2e1e99cd9">llvm::mca::RegisterFile::checkRAWHazards</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>, <a href="#ad09947650a7df617e008df474a1388b6">computeInstrLatency</a>, <a href="#ac4e5dcb952f0c76bcbb366a37077ecce">computeInstrLatency</a>, <a href="#ab7a645c3e2848203bdde8f7db2bff845">computeInstrLatency</a> and <a href="#ac080bbec97a31ee8728ca9828700ad45">getReciprocalThroughput</a>.</p>

</div>
</div>

### hasExtraProcessorInfo() {#a20ed429316e50733da37685169d39f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSchedModel::hasExtraProcessorInfo ()</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Reference <a href="#ac52ec5efbce3915a63171827440096f8">ExtraProcessorInfo</a>.</p>


<p>Referenced by <a href="#a4f78162e652232c8233dcb3967834780">getExtraProcessorInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#ae26462941069e163c658782b4132b79d">llvm::mca::LSUnitBase::LSUnitBase</a> and <a href="/web-llvm/docs/api/structs/llvm/mca/retirecontrolunit/#a90de9bdaf1a6c428ea958a2850bdc6a9">llvm::mca::RetireControlUnit::RetireControlUnit</a>.</p>

</div>
</div>

### hasInstrSchedModel() {#a68fa67076e0244cf21e80f2c43b6fa02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSchedModel::hasInstrSchedModel ()</td>
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

<p>Does this machine model include instruction-level scheduling.</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Reference <a href="#aa0cca41833e3be960d97a296a2f58ff2">SchedClassTable</a>.</p>


<p>Referenced by <a href="#ac4e5dcb952f0c76bcbb366a37077ecce">computeInstrLatency</a>, <a href="#ac7376c4db05cd0fbb107dd0b1fecc9ba">getProcResource</a> and <a href="#a3837bacedb8dfa32c6a3b949bfdd6877">getSchedClassDesc</a>.</p>

</div>
</div>

### isComplete() {#af541a495f189de322fedcb22bb236124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSchedModel::isComplete ()</td>
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

<p>Return true if this machine model data for all instructions with a scheduling class (itinerary class or SchedRW list).</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Reference <a href="#ab9a312b576ca5c909cbff1e85ba2cb65">CompleteModel</a>.</p>

</div>
</div>

### isOutOfOrder() {#a17c82641b0ce9632ce1baaf54a71db6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSchedModel::isOutOfOrder ()</td>
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

<p>Return true if machine supports out of order execution.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Reference <a href="#aaaca528ae14befaac95c11df31faf36b">MicroOpBufferSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a> and <a href="/web-llvm/docs/api/structs/llvm/mca/retirecontrolunit/#a90de9bdaf1a6c428ea958a2850bdc6a9">llvm::mca::RetireControlUnit::RetireControlUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CompleteModel {#ab9a312b576ca5c909cbff1e85ba2cb65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSchedModel::CompleteModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#af541a495f189de322fedcb22bb236124">isComplete</a>.</p>

</div>
</div>

### EnableIntervals {#ae4e1ea4e27bcba230e5f86df65af8636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSchedModel::EnableIntervals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

### ExtraProcessorInfo {#ac52ec5efbce3915a63171827440096f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExtraProcessorInfo* llvm::MCSchedModel::ExtraProcessorInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#a4f78162e652232c8233dcb3967834780">getExtraProcessorInfo</a> and <a href="#a20ed429316e50733da37685169d39f68">hasExtraProcessorInfo</a>.</p>

</div>
</div>

### HighLatency {#a26358cf24f3d0a23e6dee0bf807061be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::HighLatency</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5424d7c9e608bd5b2087f1021908a08">llvm::TargetInstrInfo::defaultDefLatency</a>.</p>

</div>
</div>

### InstrItineraries {#a33e6e84ef828ad8129b514f898fbbf8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItinerary* llvm::MCSchedModel::InstrItineraries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a2913834d48cd087ac10ba131aae887a4">llvm::HexagonMCInstrInfo::getCVIResources</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ab488aa3ae070d9de98e958be991ea9cc">llvm::HexagonMCInstrInfo::getOtherReservedSlots</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a9211aa0b9d52257601df75d2818dab7c">llvm::HexagonMCInstrInfo::getUnits</a>.</p>

</div>
</div>

### IssueWidth {#ac0f11354e854441ac5fefd72d91dd8ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::IssueWidth</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/dispatchstage/#ad86d7a96f763205596d8770f8ebf5d6e">llvm::mca::DispatchStage::DispatchStage</a>, <a href="#ac080bbec97a31ee8728ca9828700ad45">getReciprocalThroughput</a> and <a href="#ae119a8f604442c5d6b0abb586d6aa03e">getReciprocalThroughput</a>.</p>

</div>
</div>

### LoadLatency {#a077ff8557ccaf81471558635ca37f7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::LoadLatency</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5424d7c9e608bd5b2087f1021908a08">llvm::TargetInstrInfo::defaultDefLatency</a>.</p>

</div>
</div>

### LoopMicroOpBufferSize {#a74a33138b76ebc2cae1b3cf65411a9e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::LoopMicroOpBufferSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

### MicroOpBufferSize {#aaaca528ae14befaac95c11df31faf36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::MicroOpBufferSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#a17c82641b0ce9632ce1baaf54a71db6e">isOutOfOrder</a>.</p>

</div>
</div>

### MispredictPenalty {#af664056329bd39a8610479a584e4b2f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::MispredictPenalty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

### NumProcResourceKinds {#aec103d6812b2bfd0489d48ecb3148e3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::NumProcResourceKinds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#a5268bc4b5673e84a8f75df74b024d374">getNumProcResourceKinds</a> and <a href="#ac7376c4db05cd0fbb107dd0b1fecc9ba">getProcResource</a>.</p>

</div>
</div>

### NumSchedClasses {#ab08090fb8f3a647be37d191b92a1c0b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::NumSchedClasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#a3837bacedb8dfa32c6a3b949bfdd6877">getSchedClassDesc</a>.</p>

</div>
</div>

### PostRAScheduler {#a217252d2d49715e81f43a0d313e4f646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSchedModel::PostRAScheduler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ad8d442c18b35ab8bc3468c1e9de23791">llvm::TargetSubtargetInfo::enablePostRAScheduler</a>.</p>

</div>
</div>

### ProcID {#a6cc3246f3710fe97ff81dd87bc054b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSchedModel::ProcID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#a45ecfe5545130090b71f09f178effa55">getProcessorID</a>.</p>

</div>
</div>

### ProcResourceTable {#aa0ee2bb9fa1d41b69c587580e157f6fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCProcResourceDesc* llvm::MCSchedModel::ProcResourceTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#ac7376c4db05cd0fbb107dd0b1fecc9ba">getProcResource</a>.</p>

</div>
</div>

### SchedClassTable {#aa0cca41833e3be960d97a296a2f58ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedClassDesc* llvm::MCSchedModel::SchedClassTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#a3837bacedb8dfa32c6a3b949bfdd6877">getSchedClassDesc</a> and <a href="#a68fa67076e0244cf21e80f2c43b6fa02">hasInstrSchedModel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### computeInstrLatency() {#a87b307b08bc0acbbf95fab6bca87983c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MCSchedModel::computeInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> &amp; SCDesc)</td>
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

<p>Returns the latency value for the scheduling class.</p>

<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcschedule-cpp">MCSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcwritelatencyentry/#acb109cb600fa4c75a40124a9dafd85cc">llvm::MCWriteLatencyEntry::Cycles</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a36abba0bcbba153c7227e631eae79e7a">llvm::MCSubtargetInfo::getWriteLatencyEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a> and <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a5eaebfb37c3f693c9b1644c38969d4c9">llvm::MCSchedClassDesc::NumWriteLatencyEntries</a>.</p>


<p>Referenced by <a href="#ad09947650a7df617e008df474a1388b6">computeInstrLatency</a>, <a href="#ac4e5dcb952f0c76bcbb366a37077ecce">computeInstrLatency</a>, <a href="#ab7a645c3e2848203bdde8f7db2bff845">computeInstrLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a1c6db15622cacf1b8f1d6a89c199d51b">llvm::mca::computeMaxLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a98f815de250b90a65a5f83503fc7b288">emitComments</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#ad7331753737602bb545def2c960c209d">emitLatency</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fixupinsttuning-cpp-/x86fixupinsttuningpass/#af4fc51360b5ca432e573316e0609d182">anonymous{X86FixupInstTuning.cpp}::X86FixupInstTuningPass::processInstruction</a>.</p>

</div>
</div>

### getForwardingDelayCycles() {#a2ffebbabe0c187d8c92743daf4e83edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCSchedModel::getForwardingDelayCycles (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcreadadvanceentry">MCReadAdvanceEntry</a> &gt; Entries, unsigned WriteResourceIdx=0)</td>
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

<p>Returns the maximum forwarding delay for register reads dependent on writes of scheduling class WriteResourceIdx.</p>

<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcschedule-cpp">MCSchedule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>.</p>

</div>
</div>

### getReciprocalThroughput() {#ae119a8f604442c5d6b0abb586d6aa03e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double MCSchedModel::getReciprocalThroughput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> &amp; SCDesc)</td>
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



<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcschedule-cpp">MCSchedule.cpp</a>.</p>


<p>References <a href="#ac7376c4db05cd0fbb107dd0b1fecc9ba">getProcResource</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af31aa7690c77c36f2ffeb083b9917804">llvm::MCSubtargetInfo::getWriteProcResBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a08d8cf817aece246e6f804227cfbea77">llvm::MCSubtargetInfo::getWriteProcResEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac0f11354e854441ac5fefd72d91dd8ee">IssueWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#ab7b0ef1f5af7f95492f8bf39415123f2">llvm::MCSchedClassDesc::NumMicroOps</a> and <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc/#a9d4d0cc34fcce4779dc4445d8265fffc">llvm::MCProcResourceDesc::NumUnits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#ace4f0c2aacc5c769605f6af20cbb91f3">llvm::TargetSchedModel::computeReciprocalThroughput</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a1b043aa01b559cc6f27b63a85332884b">llvm::TargetSchedModel::computeReciprocalThroughput</a>, <a href="#ac080bbec97a31ee8728ca9828700ad45">getReciprocalThroughput</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fixupinsttuning-cpp-/x86fixupinsttuningpass/#af4fc51360b5ca432e573316e0609d182">anonymous{X86FixupInstTuning.cpp}::X86FixupInstTuningPass::processInstruction</a>.</p>

</div>
</div>

### getReciprocalThroughput() {#aee2c79683d10f7414452500ae1210f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double MCSchedModel::getReciprocalThroughput (unsigned SchedClass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> &amp; IID)</td>
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



<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcschedule-cpp">MCSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a7327da535eb156175c5a9ec7b7fea629">llvm::InstrItineraryData::beginStage</a>, <a href="#aea43dda92a2d44bcad9ac8b8b174083d">DefaultIssueWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#adb4cf1d46c5e7c0f1f877c2cd4f834a8">llvm::InstrItineraryData::endStage</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a8f622a0eb535373587d2e08d14eb1a76">InstrItineraryData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Default {#a090d8f8a40ae8bd7f4ac776d186d0203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedModel MCSchedModel::Default</td>
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

<p>Returns the default initialized model.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {<a href="#aea43dda92a2d44bcad9ac8b8b174083d">DefaultIssueWidth</a>,
                                            <a href="#a89a10a315de4fe27b96441bba140667a">DefaultMicroOpBufferSize</a>,
                                            <a href="#a318f6bd038b41e5318769859b0682f53">DefaultLoopMicroOpBufferSize</a>,
                                            <a href="#a6cd425228c2c4565e4308d74e2eb403b">DefaultLoadLatency</a>,
                                            <a href="#a35f1eefb7b52cfe5876f9a8671e8eead">DefaultHighLatency</a>,
                                            <a href="#aa77d6093fb6e4dbfdef6ec063cfcc627">DefaultMispredictPenalty</a>,
                                            false,
                                            <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>,
                                            false,
                                            0,
                                            nullptr,
                                            nullptr,
                                            0,
                                            0,
                                            nullptr,
                                            nullptr}
</div>
</dd>
</dl>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a2eddfb1a986d95b7f9e8e0988f72960c">llvm::MCSubtargetInfo::getSchedModelForCPU</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#adea593fdfefa11ea2aa7ed07d9df6155">llvm::MCSubtargetInfo::InitMCProcessorInfo</a>.</p>

</div>
</div>

### DefaultHighLatency {#a35f1eefb7b52cfe5876f9a8671e8eead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCSchedModel::DefaultHighLatency = 10</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

### DefaultIssueWidth {#aea43dda92a2d44bcad9ac8b8b174083d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCSchedModel::DefaultIssueWidth = 1</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>


<p>Referenced by <a href="#aee2c79683d10f7414452500ae1210f0a">getReciprocalThroughput</a>.</p>

</div>
</div>

### DefaultLoadLatency {#a6cd425228c2c4565e4308d74e2eb403b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCSchedModel::DefaultLoadLatency = 4</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

### DefaultLoopMicroOpBufferSize {#a318f6bd038b41e5318769859b0682f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCSchedModel::DefaultLoopMicroOpBufferSize = 0</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

### DefaultMicroOpBufferSize {#a89a10a315de4fe27b96441bba140667a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCSchedModel::DefaultMicroOpBufferSize = 0</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

### DefaultMispredictPenalty {#aa77d6093fb6e4dbfdef6ec063cfcc627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCSchedModel::DefaultMispredictPenalty = 10</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcschedule-h">MCSchedule.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcschedule-cpp">MCSchedule.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
