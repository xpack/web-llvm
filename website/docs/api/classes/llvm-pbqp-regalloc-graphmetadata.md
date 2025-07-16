---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pbqp/regalloc/graphmetadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GraphMetadata` Class Reference

<p>Holds graph-level metadata relevant to <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> RA problems. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PBQP::RegAlloc::GraphMetadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">llvm/CodeGen/RegAllocPBQP.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fddac374392f4c80beb527cdf716a74">AllowedRegVecRef</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/valuepool/#ab7c10a02f8ab0a4e772aec0a15ab8687">AllowedRegVecPool::PoolRef</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fa101bd7344eb12035e3c094d0607d0">AllowedRegVecPool</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/valuepool">ValuePool</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/allowedregvector">AllowedRegVector</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b836a9813e2ab2cc4146f97f460f388">GraphMetadata</a> (MachineFunction &amp;MF, LiveIntervals &amp;LIS, MachineBlockFrequencyInfo &amp;MBFI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fcef5a425faf54a4b3b3276419226fd">setNodeIdForVReg</a> (Register VReg, GraphBase::NodeId NId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">GraphBase::NodeId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81930259d550d1d804d0accf4cf5f18">getNodeIdForVReg</a> (Register VReg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fddac374392f4c80beb527cdf716a74">AllowedRegVecRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54416ed411b240f1ae42c12aef6465d">getAllowedRegs</a> (AllowedRegVector Allowed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2722f63617c77f1a7ead633b417ea003">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6986cf9e3b35f99b429fa0492015e9bf">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbae2304ebc4b255df558c21b8086542">MBFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">GraphBase::NodeId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63003eaa3499819d57a805e301fad58">VRegToNodeId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/valuepool">AllowedRegVecPool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a499c4cdcdcec27b7e06a1e9c5056a01a">AllowedRegVecs</a></td>
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

<p>Holds graph-level metadata relevant to <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> RA problems.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AllowedRegVecRef {#a3fddac374392f4c80beb527cdf716a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::GraphMetadata::AllowedRegVecRef =  AllowedRegVecPool::PoolRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### AllowedRegVecPool {#a3fa101bd7344eb12035e3c094d0607d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::GraphMetadata::AllowedRegVecPool =  ValuePool&lt;AllowedRegVector&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GraphMetadata() {#a1b836a9813e2ab2cc4146f97f460f388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::RegAlloc::GraphMetadata::GraphMetadata (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> &amp; MBFI)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>References <a href="#a6986cf9e3b35f99b429fa0492015e9bf">LIS</a>, <a href="#acbae2304ebc4b255df558c21b8086542">MBFI</a> and <a href="#a2722f63617c77f1a7ead633b417ea003">MF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAllowedRegs() {#af54416ed411b240f1ae42c12aef6465d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllowedRegVecRef llvm::PBQP::RegAlloc::GraphMetadata::getAllowedRegs (<a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/allowedregvector">AllowedRegVector</a> Allowed)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### getNodeIdForVReg() {#af81930259d550d1d804d0accf4cf5f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GraphBase::NodeId llvm::PBQP::RegAlloc::GraphMetadata::getNodeIdForVReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a2366726d459890a3700b57920166ab06">llvm::PBQP::GraphBase::invalidNodeId</a>.</p>

</div>
</div>

### setNodeIdForVReg() {#a5fcef5a425faf54a4b3b3276419226fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::GraphMetadata::setNodeIdForVReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">GraphBase::NodeId</a> NId)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/register/#afcfb1380ec9ff3f6106193a6ea9313c6">llvm::Register::id</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LIS {#a6986cf9e3b35f99b429fa0492015e9bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals&amp; llvm::PBQP::RegAlloc::GraphMetadata::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Referenced by <a href="#a1b836a9813e2ab2cc4146f97f460f388">GraphMetadata</a>.</p>

</div>
</div>

### MBFI {#acbae2304ebc4b255df558c21b8086542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo&amp; llvm::PBQP::RegAlloc::GraphMetadata::MBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Referenced by <a href="#a1b836a9813e2ab2cc4146f97f460f388">GraphMetadata</a>.</p>

</div>
</div>

### MF {#a2722f63617c77f1a7ead633b417ea003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::PBQP::RegAlloc::GraphMetadata::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Referenced by <a href="#a1b836a9813e2ab2cc4146f97f460f388">GraphMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllowedRegVecs {#a499c4cdcdcec27b7e06a1e9c5056a01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllowedRegVecPool llvm::PBQP::RegAlloc::GraphMetadata::AllowedRegVecs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### VRegToNodeId {#aa63003eaa3499819d57a805e301fad58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, GraphBase::NodeId&gt; llvm::PBQP::RegAlloc::GraphMetadata::VRegToNodeId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
