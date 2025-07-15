---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/swingschedulerddgedge
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SwingSchedulerDDGEdge` Class Reference

<p>Represents a dependence between two instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SwingSchedulerDDGEdge { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">llvm/CodeGen/MachinePipeliner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb31935c5b586aefe79b47d172a5746c">SwingSchedulerDDGEdge</a> (SUnit *PredOrSucc, const SDep &amp;Dep, bool IsSucc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an edge corresponding to an edge represented by <span class="doxyComputerOutput">PredOrSucc</span> and <span class="doxyComputerOutput">Dep</span> in the original DAG. <a href="#afb31935c5b586aefe79b47d172a5746c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81995fff228b0618a43adce97ba17a0">getSrc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> from which the edge comes (source node). <a href="#ad81995fff228b0618a43adce97ba17a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aefcbe2a86ca46fe2922647b8fe59d3">getDst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to which the edge points (destination node). <a href="#a0aefcbe2a86ca46fe2922647b8fe59d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac11386970c365363a170325ef4def4d9">getLatency</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the latency value for the edge. <a href="#ac11386970c365363a170325ef4def4d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382e983c8430141b4cb68d074b6a82a0">setLatency</a> (unsigned Latency)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the latency for the edge. <a href="#a382e983c8430141b4cb68d074b6a82a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af40f8e40739c91d488986dade575f934">getDistance</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the distance value for the edge. <a href="#af40f8e40739c91d488986dade575f934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0f39592f72f0092ab2297bcf0ec1fd">setDistance</a> (unsigned D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the distance value for the edge. <a href="#a0f0f39592f72f0092ab2297bcf0ec1fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c570837139314ae97de7d84ed2d9376">getReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the register associated with the edge. <a href="#a0c570837139314ae97de7d84ed2d9376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ca0f6fb102a1b482926f7077b00fd95">isAntiDep</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the edge represents anti dependence. <a href="#a3ca0f6fb102a1b482926f7077b00fd95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaced81233f9b39ad10460d45ab3aa7f">isOutputDep</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the edge represents output dependence. <a href="#afaced81233f9b39ad10460d45ab3aa7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea10afa64b24da641a7f32eb6660aa7">isOrderDep</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the edge represents a dependence that is not data, anti or output dependence. <a href="#abea10afa64b24da641a7f32eb6660aa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21471bbd722a9500ae9a0984641896fd">isBarrier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the edge represents unknown scheduling barrier. <a href="#a21471bbd722a9500ae9a0984641896fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7546cfd3a51205cd1363536fc75df325">isArtificial</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the edge represents an artificial dependence. <a href="#a7546cfd3a51205cd1363536fc75df325">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5489ef79138dbe80a00499e014f7bc93">isAssignedRegDep</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this is a Data dependence that is associated with a register. <a href="#a5489ef79138dbe80a00499e014f7bc93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ceeb69a98ceced68af8215b02cecbb2">ignoreDependence</a> (bool IgnoreAnti) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true for DDG nodes that we ignore when computing the cost functions. <a href="#a7ceeb69a98ceced68af8215b02cecbb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a922aa4623c1574e93d9e726564ee9b">Dst</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09051043dd024757705fbe9701774ebf">Pred</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7671bfbd1eb543bbf46d2990a48cf56c">Distance</a> = 0</td>
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

<p>Represents a dependence between two instruction.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SwingSchedulerDDGEdge() {#afb31935c5b586aefe79b47d172a5746c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwingSchedulerDDGEdge::SwingSchedulerDDGEdge (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * PredOrSucc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Dep, bool IsSucc)</td>
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

<p>Creates an edge corresponding to an edge represented by <span class="doxyComputerOutput">PredOrSucc</span> and <span class="doxyComputerOutput">Dep</span> in the original DAG.</p>


<p>This pair has no information about the direction of the edge, so we need to pass an additional argument <span class="doxyComputerOutput">IsSucc</span>.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDistance() {#af40f8e40739c91d488986dade575f934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwingSchedulerDDGEdge::getDistance ()</td>
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

<p>Returns the distance value for the edge.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### getDst() {#a0aefcbe2a86ca46fe2922647b8fe59d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * llvm::SwingSchedulerDDGEdge::getDst ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to which the edge points (destination node).</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae7d28b348c77e17419b65d3f3d7d55a4">llvm::SMSchedule::latestCycleInChain</a>.</p>

</div>
</div>

### getLatency() {#ac11386970c365363a170325ef4def4d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwingSchedulerDDGEdge::getLatency ()</td>
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

<p>Returns the latency value for the edge.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### getReg() {#a0c570837139314ae97de7d84ed2d9376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SwingSchedulerDDGEdge::getReg ()</td>
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

<p>Returns the register associated with the edge.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### getSrc() {#ad81995fff228b0618a43adce97ba17a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * llvm::SwingSchedulerDDGEdge::getSrc ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> from which the edge comes (source node).</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a326b69bb87197af5c7e9398da090d754">llvm::SMSchedule::earliestCycleInChain</a>.</p>

</div>
</div>

### ignoreDependence() {#a7ceeb69a98ceced68af8215b02cecbb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SwingSchedulerDDGEdge::ignoreDependence (bool IgnoreAnti)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true for DDG nodes that we ignore when computing the cost functions.</p>


<p>We ignore the back-edge recurrence in order to avoid unbounded recursion in the calculation of the ASAP, ALAP, etc functions.</p>


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3751 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>.</p>

</div>
</div>

### isAntiDep() {#a3ca0f6fb102a1b482926f7077b00fd95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwingSchedulerDDGEdge::isAntiDep ()</td>
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

<p>Returns true if the edge represents anti dependence.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>.</p>

</div>
</div>

### isArtificial() {#a7546cfd3a51205cd1363536fc75df325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwingSchedulerDDGEdge::isArtificial ()</td>
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

<p>Returns true if the edge represents an artificial dependence.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### isAssignedRegDep() {#a5489ef79138dbe80a00499e014f7bc93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwingSchedulerDDGEdge::isAssignedRegDep ()</td>
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

<p>Tests if this is a Data dependence that is associated with a register.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### isBarrier() {#a21471bbd722a9500ae9a0984641896fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwingSchedulerDDGEdge::isBarrier ()</td>
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

<p>Returns true if the edge represents unknown scheduling barrier.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### isOrderDep() {#abea10afa64b24da641a7f32eb6660aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwingSchedulerDDGEdge::isOrderDep ()</td>
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

<p>Returns true if the edge represents a dependence that is not data, anti or output dependence.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">llvm::SDep::Order</a>.</p>

</div>
</div>

### isOutputDep() {#afaced81233f9b39ad10460d45ab3aa7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwingSchedulerDDGEdge::isOutputDep ()</td>
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

<p>Returns true if the edge represents output dependence.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">llvm::SDep::Output</a>.</p>

</div>
</div>

### setDistance() {#a0f0f39592f72f0092ab2297bcf0ec1fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwingSchedulerDDGEdge::setDistance (unsigned D)</td>
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

<p>Sets the distance value for the edge.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>

</div>
</div>

### setLatency() {#a382e983c8430141b4cb68d074b6a82a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwingSchedulerDDGEdge::setLatency (unsigned Latency)</td>
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

<p>Sets the latency for the edge.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Distance {#a7671bfbd1eb543bbf46d2990a48cf56c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwingSchedulerDDGEdge::Distance = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### Dst {#a1a922aa4623c1574e93d9e726564ee9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit* llvm::SwingSchedulerDDGEdge::Dst = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### Pred {#a09051043dd024757705fbe9701774ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDep llvm::SwingSchedulerDDGEdge::Pred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
