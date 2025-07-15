---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/livedebugvalues/dbgop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DbgOp` Struct Reference

<p>TODO: Might pack better if we changed this to a Struct of Arrays, since <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> is width 32, making this struct width 33. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct LiveDebugValues::DbgOp { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">CodeGen/LiveDebugValues/InstrRefBasedImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae35236cc0c758398ed842f8fb3e548">DbgOp</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8517fd0a0b2c695ca5d45fea01f984b0">DbgOp</a> (ValueIDNum ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f5001e487e43d4dd4471e2155722c7">DbgOp</a> (MachineOperand MO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e137fe2e3773e0a6f40980d2e99083d">isUndef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645a31ec228d2d3f5ec064b726514cd2">dump</a> (const MLocTracker *MTrack) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b174ad71c91584d987861d5e8e5d2d">ID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8daff935ad1c509d14a73342911354">MO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop">LiveDebugValues::DbgOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a851e86f8921eebbb12b2af85d6e9a810"></a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa155f40c0f7c56ae215ee41a52d5f9ad">IsConst</a></td>
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

<p>TODO: Might pack better if we changed this to a Struct of Arrays, since <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> is width 32, making this struct width 33.</p>


<p>We could also potentially avoid storing the whole <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> (sizeof=32), instead choosing to store just the contents portion (sizeof=8) and a Kind enum, since we already know it is some type of immediate value. Stores a single debug operand, which can either be a <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> for directly storing immediate values, or a <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> representing some value computed at some point in the program. IsConst is used as a discriminator.</p>


<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DbgOp() {#a2ae35236cc0c758398ed842f8fb3e548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::DbgOp::DbgOp ()</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a17b174ad71c91584d987861d5e8e5d2d">ID</a> and <a href="#aa155f40c0f7c56ae215ee41a52d5f9ad">IsConst</a>.</p>

</div>
</div>

### DbgOp() {#a8517fd0a0b2c695ca5d45fea01f984b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::DbgOp::DbgOp (<a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> ID)</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a17b174ad71c91584d987861d5e8e5d2d">ID</a> and <a href="#aa155f40c0f7c56ae215ee41a52d5f9ad">IsConst</a>.</p>

</div>
</div>

### DbgOp() {#a71f5001e487e43d4dd4471e2155722c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::DbgOp::DbgOp (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> MO)</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#aa155f40c0f7c56ae215ee41a52d5f9ad">IsConst</a>, <a href="#aad8daff935ad1c509d14a73342911354">MO</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a645a31ec228d2d3f5ec064b726514cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgOp::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> * MTrack)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 983 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a17b174ad71c91584d987861d5e8e5d2d">ID</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a70d5f445ba9f76ce9d0a11bc11e8e1a9">LiveDebugValues::MLocTracker::IDAsString</a>, <a href="#aa155f40c0f7c56ae215ee41a52d5f9ad">IsConst</a>, <a href="#a4e137fe2e3773e0a6f40980d2e99083d">isUndef</a> and <a href="#aad8daff935ad1c509d14a73342911354">MO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid/#a743561a2288ede30c2992d98e1866505">LiveDebugValues::DbgOpID::dump</a>.</p>

</div>
</div>

### isUndef() {#a4e137fe2e3773e0a6f40980d2e99083d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgOp::isUndef ()</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a98d44bec6b754ac8786ab97f219f06f1">LiveDebugValues::ValueIDNum::EmptyValue</a>, <a href="#a17b174ad71c91584d987861d5e8e5d2d">ID</a> and <a href="#aa155f40c0f7c56ae215ee41a52d5f9ad">IsConst</a>.</p>


<p>Referenced by <a href="#a645a31ec228d2d3f5ec064b726514cd2">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a851e86f8921eebbb12b2af85d6e9a810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union LiveDebugValues::DbgOp LiveDebugValues::DbgOp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### ID {#a17b174ad71c91584d987861d5e8e5d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueIDNum LiveDebugValues::DbgOp::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a2ae35236cc0c758398ed842f8fb3e548">DbgOp</a>, <a href="#a8517fd0a0b2c695ca5d45fea01f984b0">DbgOp</a>, <a href="#a645a31ec228d2d3f5ec064b726514cd2">dump</a>, <a href="#a4e137fe2e3773e0a6f40980d2e99083d">isUndef</a> and <a href="/web-llvm/docs/api/classes/transfertracker/#a304b877a673788ae4edd0e8f5fa1d5d8">TransferTracker::loadInlocs</a>.</p>

</div>
</div>

### IsConst {#aa155f40c0f7c56ae215ee41a52d5f9ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::DbgOp::IsConst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a2ae35236cc0c758398ed842f8fb3e548">DbgOp</a>, <a href="#a71f5001e487e43d4dd4471e2155722c7">DbgOp</a>, <a href="#a8517fd0a0b2c695ca5d45fea01f984b0">DbgOp</a>, <a href="#a645a31ec228d2d3f5ec064b726514cd2">dump</a> and <a href="#a4e137fe2e3773e0a6f40980d2e99083d">isUndef</a>.</p>

</div>
</div>

### MO {#aad8daff935ad1c509d14a73342911354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand LiveDebugValues::DbgOp::MO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a71f5001e487e43d4dd4471e2155722c7">DbgOp</a> and <a href="#a645a31ec228d2d3f5ec064b726514cd2">dump</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
