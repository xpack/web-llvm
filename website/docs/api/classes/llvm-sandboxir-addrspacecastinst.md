---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/addrspacecastinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AddrSpaceCastInst` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::AddrSpaceCastInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">llvm/SandboxIR/Instruction.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/castinstimpl">CastInstImpl&lt;Op&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f6bec606b3746e5df49ef03c5e89805">getPointerOperand</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the pointer operand. <a href="#a3f6bec606b3746e5df49ef03c5e89805">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac97c287e4292708a851eba745cf402fe">getPointerOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the pointer operand. <a href="#ac97c287e4292708a851eba745cf402fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088eb1bfed8c280333c53c97e981b4e0">getSrcAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the address space of the pointer operand. <a href="#a088eb1bfed8c280333c53c97e981b4e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774a0a887b03ce2aa37b5409105ebf6f">getDestAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the address space of the result. <a href="#a774a0a887b03ce2aa37b5409105ebf6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44fc9801a4bafb7bcbe2dd4128de018">getPointerOperandIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the operand index of the pointer operand. <a href="#ad44fc9801a4bafb7bcbe2dd4128de018">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 2356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getDestAddressSpace() {#a774a0a887b03ce2aa37b5409105ebf6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::AddrSpaceCastInst::getDestAddressSpace ()</td>
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

<p>\Returns the address space of the result.</p>

<p>Definition at line 2372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a636cb45b78340dd800a37d42120f52cc">llvm::sandboxir::Type::getPointerAddressSpace</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a5f93ad2195368bba2202c3cc75e7cc1d">llvm::sandboxir::Value::getType</a>.</p>

</div>
</div>

### getPointerOperand() {#a3f6bec606b3746e5df49ef03c5e89805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::AddrSpaceCastInst::getPointerOperand ()</td>
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

<p>\Returns the pointer operand.</p>

<p>Definition at line 2360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ac9a69bf52a5b93bb710536d9ae8245c6">llvm::sandboxir::getOperand</a>.</p>


<p>Referenced by <a href="#ac97c287e4292708a851eba745cf402fe">getPointerOperand</a> and <a href="#a088eb1bfed8c280333c53c97e981b4e0">getSrcAddressSpace</a>.</p>

</div>
</div>

### getPointerOperand() {#ac97c287e4292708a851eba745cf402fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::sandboxir::AddrSpaceCastInst::getPointerOperand ()</td>
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

<p>\Returns the pointer operand.</p>

<p>Definition at line 2362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#a3f6bec606b3746e5df49ef03c5e89805">getPointerOperand</a>.</p>

</div>
</div>

### getSrcAddressSpace() {#a088eb1bfed8c280333c53c97e981b4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::AddrSpaceCastInst::getSrcAddressSpace ()</td>
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

<p>\Returns the address space of the pointer operand.</p>

<p>Definition at line 2368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a636cb45b78340dd800a37d42120f52cc">llvm::sandboxir::Type::getPointerAddressSpace</a>, <a href="#a3f6bec606b3746e5df49ef03c5e89805">getPointerOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a5f93ad2195368bba2202c3cc75e7cc1d">llvm::sandboxir::Value::getType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getPointerOperandIndex() {#ad44fc9801a4bafb7bcbe2dd4128de018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::AddrSpaceCastInst::getPointerOperandIndex ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns the operand index of the pointer operand.</p>

<p>Definition at line 2366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
