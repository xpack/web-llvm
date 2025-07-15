---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-machinescheduler-cpp-/ilporder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ILPOrder` Struct Reference

<p>Order nodes by the ILP metric. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MachineScheduler.cpp}::ILPOrder { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf160a684d52727348fa1a8a64a68799">ILPOrder</a> (bool MaxILP)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cef0fc1ea3d0a80f8e881d1a60f0a04">operator()</a> (const SUnit *A, const SUnit *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a less-than relation on node priority. <a href="#a9cef0fc1ea3d0a80f8e881d1a60f0a04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult">SchedDFSResult</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a0399d3f96b0838922377265fa8626d">DFSResult</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066bf2acd636df6d9c364efc9020e9b1">ScheduledTrees</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a508685c4207a0b1b88ad607d06efd">MaximizeILP</a></td>
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

<p>Order nodes by the ILP metric.</p>

<p>Definition at line 4172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ILPOrder() {#abf160a684d52727348fa1a8a64a68799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineScheduler.cpp}::ILPOrder::ILPOrder (bool MaxILP)</td>
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



<p>Definition at line 4177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Reference <a href="#ad8a508685c4207a0b1b88ad607d06efd">MaximizeILP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a9cef0fc1ea3d0a80f8e881d1a60f0a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineScheduler.cpp}::ILPOrder::operator() (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * B)</td>
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

<p>Apply a less-than relation on node priority.</p>


<p>(Return true if A comes after B in the Q.)</p>


<p>Definition at line 4182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a2a0399d3f96b0838922377265fa8626d">DFSResult</a>, <a href="#ad8a508685c4207a0b1b88ad607d06efd">MaximizeILP</a> and <a href="#a066bf2acd636df6d9c364efc9020e9b1">ScheduledTrees</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DFSResult {#a2a0399d3f96b0838922377265fa8626d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SchedDFSResult* anonymous{MachineScheduler.cpp}::ILPOrder::DFSResult = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="#a9cef0fc1ea3d0a80f8e881d1a60f0a04">operator()</a>.</p>

</div>
</div>

### MaximizeILP {#ad8a508685c4207a0b1b88ad607d06efd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineScheduler.cpp}::ILPOrder::MaximizeILP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="#abf160a684d52727348fa1a8a64a68799">ILPOrder</a> and <a href="#a9cef0fc1ea3d0a80f8e881d1a60f0a04">operator()</a>.</p>

</div>
</div>

### ScheduledTrees {#a066bf2acd636df6d9c364efc9020e9b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector* anonymous{MachineScheduler.cpp}::ILPOrder::ScheduledTrees = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a>.</p>


<p>Referenced by <a href="#a9cef0fc1ea3d0a80f8e881d1a60f0a04">operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp">MachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
