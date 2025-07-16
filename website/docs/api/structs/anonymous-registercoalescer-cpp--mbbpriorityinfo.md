---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-registercoalescer-cpp-/mbbpriorityinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MBBPriorityInfo` Struct Reference

<p>Information concerning MBB coalescing priority. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{RegisterCoalescer.cpp}::MBBPriorityInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab70bf96dbc4f92c49f46eac4e433d3ed">MBBPriorityInfo</a> (MachineBasicBlock *mbb, unsigned depth, bool issplit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a376d83d1a6024515746955db21739d">MBB</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c318abdccc5e19786e20e936cab8c7">Depth</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6275cdfa9397d920d591ddce7ec42fb1">IsSplit</a></td>
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

<p>Information concerning MBB coalescing priority.</p>

<p>Definition at line 3981 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MBBPriorityInfo() {#ab70bf96dbc4f92c49f46eac4e433d3ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RegisterCoalescer.cpp}::MBBPriorityInfo::MBBPriorityInfo (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb, unsigned depth, bool issplit)</td>
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



<p>Definition at line 3986 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="#a14c318abdccc5e19786e20e936cab8c7">Depth</a>, <a href="#a6275cdfa9397d920d591ddce7ec42fb1">IsSplit</a> and <a href="#a4a376d83d1a6024515746955db21739d">MBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Depth {#a14c318abdccc5e19786e20e936cab8c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RegisterCoalescer.cpp}::MBBPriorityInfo::Depth</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3983 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>Referenced by <a href="#ab70bf96dbc4f92c49f46eac4e433d3ed">MBBPriorityInfo</a>.</p>

</div>
</div>

### IsSplit {#a6275cdfa9397d920d591ddce7ec42fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RegisterCoalescer.cpp}::MBBPriorityInfo::IsSplit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3984 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>Referenced by <a href="#ab70bf96dbc4f92c49f46eac4e433d3ed">MBBPriorityInfo</a>.</p>

</div>
</div>

### MBB {#a4a376d83d1a6024515746955db21739d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{RegisterCoalescer.cpp}::MBBPriorityInfo::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3982 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>Referenced by <a href="#ab70bf96dbc4f92c49f46eac4e433d3ed">MBBPriorityInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
