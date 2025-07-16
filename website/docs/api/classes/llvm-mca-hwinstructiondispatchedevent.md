---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/hwinstructiondispatchedevent
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HWInstructionDispatchedEvent` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::mca::HWInstructionDispatchedEvent { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">llvm/MCA/HWEventListener.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionevent">HWInstructionEvent</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a25c436ad489dba4a1e2b008905cfa3">HWInstructionDispatchedEvent</a> (const InstRef &amp;IR, ArrayRef&lt; unsigned &gt; Regs, unsigned UOps)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a118e663189ddd1479a228ecf31a883">UsedPhysRegs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221e4b57bdb6000f98ebff74d1d073ba">MicroOpcodes</a></td>
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


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HWInstructionDispatchedEvent() {#a9a25c436ad489dba4a1e2b008905cfa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::HWInstructionDispatchedEvent::HWInstructionDispatchedEvent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Regs, unsigned UOps)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionevent/#a8169c917f54cc2624dd536acdc5c5e52a1bb71e665c2978dc4d3c02da2f9bcbc3">llvm::mca::HWInstructionEvent::Dispatched</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionevent/#a171b37ee53c5f563af010cdc3ebb47a3">llvm::mca::HWInstructionEvent::HWInstructionEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionevent/#a17c3610b731525a11cec3d4e9472291c">llvm::mca::HWInstructionEvent::IR</a>, <a href="#a221e4b57bdb6000f98ebff74d1d073ba">MicroOpcodes</a> and <a href="#a6a118e663189ddd1479a228ecf31a883">UsedPhysRegs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MicroOpcodes {#a221e4b57bdb6000f98ebff74d1d073ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::HWInstructionDispatchedEvent::MicroOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>Referenced by <a href="#a9a25c436ad489dba4a1e2b008905cfa3">HWInstructionDispatchedEvent</a>.</p>

</div>
</div>

### UsedPhysRegs {#a6a118e663189ddd1479a228ecf31a883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;unsigned&gt; llvm::mca::HWInstructionDispatchedEvent::UsedPhysRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>Referenced by <a href="#a9a25c436ad489dba4a1e2b008905cfa3">HWInstructionDispatchedEvent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
