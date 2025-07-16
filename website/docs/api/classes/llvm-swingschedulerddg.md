---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/swingschedulerddg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SwingSchedulerDDG` Class Reference

<p>Represents dependencies between instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SwingSchedulerDDG { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">llvm/CodeGen/MachinePipeliner.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9251a5cfc2014c8e74b57101f2a855">EdgesType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddgedge">SwingSchedulerDDGEdge</a>, 4 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb41e4601ae2bd500431464f7f8a6532">SwingSchedulerDDG</a> (std::vector&lt; SUnit &gt; &amp;SUnits, SUnit *EntrySU, SUnit *ExitSU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">EdgesType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac155300b317b84aef98c8f6b5381c193">getInEdges</a> (const SUnit *SU) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">EdgesType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd6cd25113b672fb9e9ec1339355d82">getOutEdges</a> (const SUnit *SU) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02438c6c7e7660f1fa92df8ec9c17905">initEdges</a> (SUnit *SU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0803fff7f34ba81e92934c1830aea3f1">addEdge</a> (const SUnit *SU, const SwingSchedulerDDGEdge &amp;Edge)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">SwingSchedulerDDGEdges &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b02f5d580dc906eb5cbfef90cb819d4">getEdges</a> (const SUnit *SU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SwingSchedulerDDGEdges &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c644ce4a7a3dc98cb1e6f96b0288760">getEdges</a> (const SUnit *SU) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e6d3aa82a610c342e3cff2d274bc1f9">EntrySU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfee86d4fdf66d9a24dce76000c1c59">ExitSU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; SwingSchedulerDDGEdges &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91ca5595490b9c03abb4ee53b4ca88c3">EdgesVec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">SwingSchedulerDDGEdges</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa25002f685b32a1b089f597a8a5c0ec4">EntrySUEdges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">SwingSchedulerDDGEdges</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab380a326cf62cadbb8c2293942404b49">ExitSUEdges</a></td>
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

<p>Represents dependencies between instructions.</p>


<p>This class is a wrapper of <span class="doxyComputerOutput">SUnits</span> and its dependencies to manipulate back-edges in a natural way. Currently it only supports back-edges via PHI, which are expressed as anti-dependencies in the original DAG. FIXME: Support any other loop-carried dependencies</p>


<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### EdgesType {#aec9251a5cfc2014c8e74b57101f2a855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SwingSchedulerDDG::EdgesType =  SmallVector&lt;SwingSchedulerDDGEdge, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SwingSchedulerDDG() {#abb41e4601ae2bd500431464f7f8a6532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwingSchedulerDDG::SwingSchedulerDDG (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt; &amp; SUnits, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * EntrySU, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * ExitSU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3799 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInEdges() {#ac155300b317b84aef98c8f6b5381c193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SwingSchedulerDDG::EdgesType &amp; SwingSchedulerDDG::getInEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3811 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#acdcfdf9ee94eb9275888de3e3dec1a77">computePath</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#acfd4efd1c9f1a0174bd6f3942238c51b">llvm::SMSchedule::computeStart</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a326b69bb87197af5c7e9398da090d754">llvm::SMSchedule::earliestCycleInChain</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae26138aceef07cf5465c2840b437e1d8">llvm::SMSchedule::normalizeNonPipelinedInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a4dbd10ef0657470e3bd9f6fb48cf2307">llvm::SMSchedule::onlyHasLoopCarriedOutputOrOrderPreds</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a70c8219e8d9627e2373f281be45f96ae">llvm::SMSchedule::orderDependence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#ab8408c091ccee1b8697f580938e4e39c">pred_L</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#ad2abdeb611cf3d053632c2c1c8a6abb9">succ_L</a>.</p>

</div>
</div>

### getOutEdges() {#afbd6cd25113b672fb9e9ec1339355d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SwingSchedulerDDG::EdgesType &amp; SwingSchedulerDDG::getOutEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3816 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#acdcfdf9ee94eb9275888de3e3dec1a77">computePath</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#acfd4efd1c9f1a0174bd6f3942238c51b">llvm::SMSchedule::computeStart</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a7c7d5ab8d9814b721a1844a867ef948a">llvm::SMSchedule::isValidSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae7d28b348c77e17419b65d3f3d7d55a4">llvm::SMSchedule::latestCycleInChain</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae26138aceef07cf5465c2840b437e1d8">llvm::SMSchedule::normalizeNonPipelinedInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a70c8219e8d9627e2373f281be45f96ae">llvm::SMSchedule::orderDependence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#ab8408c091ccee1b8697f580938e4e39c">pred_L</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#ad2abdeb611cf3d053632c2c1c8a6abb9">succ_L</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addEdge() {#a0803fff7f34ba81e92934c1830aea3f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SwingSchedulerDDG::addEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddgedge">SwingSchedulerDDGEdge</a> &amp; Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3778 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

### getEdges() {#a0b02f5d580dc906eb5cbfef90cb819d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwingSchedulerDDG::SwingSchedulerDDGEdges &amp; SwingSchedulerDDG::getEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3761 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

### getEdges() {#a7c644ce4a7a3dc98cb1e6f96b0288760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SwingSchedulerDDG::SwingSchedulerDDGEdges &amp; SwingSchedulerDDG::getEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3770 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

### initEdges() {#a02438c6c7e7660f1fa92df8ec9c17905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SwingSchedulerDDG::initEdges (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3787 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EdgesVec {#a91ca5595490b9c03abb4ee53b4ca88c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SwingSchedulerDDGEdges&gt; llvm::SwingSchedulerDDG::EdgesVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### EntrySU {#a6e6d3aa82a610c342e3cff2d274bc1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit* llvm::SwingSchedulerDDG::EntrySU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### EntrySUEdges {#aa25002f685b32a1b089f597a8a5c0ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwingSchedulerDDGEdges llvm::SwingSchedulerDDG::EntrySUEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### ExitSU {#a4cfee86d4fdf66d9a24dce76000c1c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit* llvm::SwingSchedulerDDG::ExitSU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### ExitSUEdges {#ab380a326cf62cadbb8c2293942404b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwingSchedulerDDGEdges llvm::SwingSchedulerDDG::ExitSUEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
