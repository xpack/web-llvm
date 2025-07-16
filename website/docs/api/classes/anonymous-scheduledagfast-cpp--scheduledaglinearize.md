---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-scheduledagfast-cpp-/scheduledaglinearize
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScheduleDAGLinearize` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a> - A <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> for scheduling SDNode-based DAGs. <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2901e510164a94c5db134cc33cea486f">ScheduleDAGLinearize</a> (MachineFunction &amp;mf)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5dfad52f2ec0adbc920cf686c615e00">Schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Schedule - Order nodes according to selected style, filling in the Sequence member. <a href="#ac5dfad52f2ec0adbc920cf686c615e00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c498db76eb73d37731b36c18879ee4">EmitSchedule</a> (MachineBasicBlock::iterator &amp;InsertPos) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitSchedule - Insert MachineInstrs into the MachineBasicBlock according to the order specified in Sequence. <a href="#a16c498db76eb73d37731b36c18879ee4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6685b15927609ef03feaf39d75c409">ScheduleNode</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab620dc5d41e1a51682fb14f74b69b482">Sequence</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad449782ab6810025c8117e82cb10fc9a">GluedMap</a></td>
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


<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScheduleDAGLinearize() {#a2901e510164a94c5db134cc33cea486f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::ScheduleDAGLinearize (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf)</td>
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



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ad73652eab6e03e092e32bde82040c8c7">llvm::ScheduleDAGSDNodes::ScheduleDAGSDNodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a61df584d7cd50d992593adcbe1a6ffba">llvm::createDAGLinearizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitSchedule() {#a16c498db76eb73d37731b36c18879ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * ScheduleDAGLinearize::EmitSchedule (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; InsertPos)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitSchedule - Insert MachineInstrs into the MachineBasicBlock according to the order specified in Sequence.</p>


<p>EmitSchedule - Emit the machine code in scheduled order.</p>


<p>Return the new InsertPos and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> that contains this insertion point. ScheduleDAGSDNodes holds a BB pointer for convenience, but this does not necessarily refer to returned BB. The emitter may split blocks.</p>


<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a9f718397926caadcb301ca1e00aaf68c">llvm::ScheduleDAGSDNodes::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a2dbfb92f74a3067ce823a76e3266b0e0">llvm::ScheduleDAGSDNodes::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### Schedule() {#ac5dfad52f2ec0adbc920cf686c615e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGLinearize::Schedule ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Schedule - Order nodes according to selected style, filling in the Sequence member.</p>

<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a2dbfb92f74a3067ce823a76e3266b0e0">llvm::ScheduleDAGSDNodes::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a926013f6dca240eca95aca66c8d3e74b">llvm::ISD::EntryToken</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#ac50565f46bf17e6c180062066ad3842d">findGluedUser</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a2594280bfba5f9b0dff74cfb5b4f29d2">llvm::SDNode::getGluedUser</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1bdddc5f08b7b8b77e2518296dd4d84f">llvm::SDNode::getNodeId</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a901a96fb8eb2598eed200755554567c0">llvm::ScheduleDAGSDNodes::isPassiveNode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a5689e9ae35c6ceb3b9377299c98e0e97">llvm::SDNode::setNodeId</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad5596cf1822f4cc9e37fb75b6dff630f">llvm::SDNode::users</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ScheduleNode() {#a2b6685b15927609ef03feaf39d75c409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGLinearize::ScheduleNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GluedMap {#ad449782ab6810025c8117e82cb10fc9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;SDNode*, SDNode*&gt; anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::GluedMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

### Sequence {#ab620dc5d41e1a51682fb14f74b69b482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SDNode*&gt; anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::Sequence</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp">ScheduleDAGFast.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
