---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mca/retirecontrolunit/rutoken
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RUToken` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::mca::RetireControlUnit::RUToken { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/retirecontrolunit-h">llvm/MCA/HardwareUnits/RetireControlUnit.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082a604d529a20e0c27cca3ccff88686">IR</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f776b0f155d7da8044a7fd88f83515f">NumSlots</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a416015919b2e463d01b7483253f02dca">Executed</a></td>
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


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/retirecontrolunit-h">RetireControlUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Executed {#a416015919b2e463d01b7483253f02dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::RetireControlUnit::RUToken::Executed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/retirecontrolunit-h">RetireControlUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/retirestage/#a48f565b3ef8a44c8a88c66000a8175a4">llvm::mca::RetireStage::cycleStart</a>.</p>

</div>
</div>

### IR {#a082a604d529a20e0c27cca3ccff88686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstRef llvm::mca::RetireControlUnit::RUToken::IR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/retirecontrolunit-h">RetireControlUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mca/retirecontrolunit/#af830bc0573e2b15a668a9ae57edcab3d">llvm::mca::RetireControlUnit::consumeCurrentToken</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/retirestage/#a48f565b3ef8a44c8a88c66000a8175a4">llvm::mca::RetireStage::cycleStart</a> and <a href="/web-llvm/docs/api/structs/llvm/mca/retirecontrolunit/#acab7dc4684afbbe5d4d3e3fb3d6c6d40">llvm::mca::RetireControlUnit::getCurrentToken</a>.</p>

</div>
</div>

### NumSlots {#a3f776b0f155d7da8044a7fd88f83515f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::RetireControlUnit::RUToken::NumSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/retirecontrolunit-h">RetireControlUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mca/retirecontrolunit/#af830bc0573e2b15a668a9ae57edcab3d">llvm::mca::RetireControlUnit::consumeCurrentToken</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/retirecontrolunit-h">RetireControlUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
