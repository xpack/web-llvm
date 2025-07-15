---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-scalarevolution-cpp-/binaryop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BinaryOp` Struct Reference

<p>Represents an abstract binary operation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ScalarEvolution.cpp}::BinaryOp { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad143f72265caa743fa9650499b48bca6">BinaryOp</a> (Operator *Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84a895de545b01b3ae407bc4c04b7b3d">BinaryOp</a> (unsigned Opcode, Value *LHS, Value *RHS, bool IsNSW=false, bool IsNUW=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a115fbfb2dad9b4272a9852722b5063d0">Opcode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b158d25af424d0e1b451a0c677520b4">LHS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a816564b852bb2e309585f2f96628c77a">RHS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a337c8ecbf1fb0ecadd3e4b8528e89918">IsNSW</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63355230591c958eb7f5f906f4878a0">IsNUW</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/operator">Operator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ffab7825ec2ae371c63c1e73e99c0d">Op</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Op is set if this <a href="/web-llvm/docs/api/structs/anonymous-scalarevolution-cpp-/binaryop">BinaryOp</a> corresponds to a concrete LLVM instruction or constant expression. <a href="#aa3ffab7825ec2ae371c63c1e73e99c0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents an abstract binary operation.</p>


<p>This may exist as a normal instruction or constant expression, or may have been derived from an expression tree.</p>


<p>Definition at line 5219 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BinaryOp() {#ad143f72265caa743fa9650499b48bca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScalarEvolution.cpp}::BinaryOp::BinaryOp (<a href="/web-llvm/docs/api/classes/llvm/operator">Operator</a> * Op)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5230 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>, <a href="#a337c8ecbf1fb0ecadd3e4b8528e89918">IsNSW</a>, <a href="#af63355230591c958eb7f5f906f4878a0">IsNUW</a>, <a href="#a6b158d25af424d0e1b451a0c677520b4">LHS</a>, <a href="#aa3ffab7825ec2ae371c63c1e73e99c0d">Op</a>, <a href="#a115fbfb2dad9b4272a9852722b5063d0">Opcode</a> and <a href="#a816564b852bb2e309585f2f96628c77a">RHS</a>.</p>

</div>
</div>

### BinaryOp() {#a84a895de545b01b3ae407bc4c04b7b3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScalarEvolution.cpp}::BinaryOp::BinaryOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, bool IsNSW=false, bool IsNUW=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5239 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a337c8ecbf1fb0ecadd3e4b8528e89918">IsNSW</a>, <a href="#af63355230591c958eb7f5f906f4878a0">IsNUW</a>, <a href="#a6b158d25af424d0e1b451a0c677520b4">LHS</a>, <a href="#a115fbfb2dad9b4272a9852722b5063d0">Opcode</a> and <a href="#a816564b852bb2e309585f2f96628c77a">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsNSW {#a337c8ecbf1fb0ecadd3e4b8528e89918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ScalarEvolution.cpp}::BinaryOp::IsNSW = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5223 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="#ad143f72265caa743fa9650499b48bca6">BinaryOp</a> and <a href="#a84a895de545b01b3ae407bc4c04b7b3d">BinaryOp</a>.</p>

</div>
</div>

### IsNUW {#af63355230591c958eb7f5f906f4878a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ScalarEvolution.cpp}::BinaryOp::IsNUW = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5224 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="#ad143f72265caa743fa9650499b48bca6">BinaryOp</a> and <a href="#a84a895de545b01b3ae407bc4c04b7b3d">BinaryOp</a>.</p>

</div>
</div>

### LHS {#a6b158d25af424d0e1b451a0c677520b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{ScalarEvolution.cpp}::BinaryOp::LHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5221 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="#ad143f72265caa743fa9650499b48bca6">BinaryOp</a> and <a href="#a84a895de545b01b3ae407bc4c04b7b3d">BinaryOp</a>.</p>

</div>
</div>

### Op {#aa3ffab7825ec2ae371c63c1e73e99c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Operator* anonymous{ScalarEvolution.cpp}::BinaryOp::Op = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Op is set if this <a href="/web-llvm/docs/api/structs/anonymous-scalarevolution-cpp-/binaryop">BinaryOp</a> corresponds to a concrete LLVM instruction or constant expression.</p>

<p>Definition at line 5228 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="#ad143f72265caa743fa9650499b48bca6">BinaryOp</a>.</p>

</div>
</div>

### Opcode {#a115fbfb2dad9b4272a9852722b5063d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ScalarEvolution.cpp}::BinaryOp::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5220 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="#ad143f72265caa743fa9650499b48bca6">BinaryOp</a> and <a href="#a84a895de545b01b3ae407bc4c04b7b3d">BinaryOp</a>.</p>

</div>
</div>

### RHS {#a816564b852bb2e309585f2f96628c77a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{ScalarEvolution.cpp}::BinaryOp::RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5222 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="#ad143f72265caa743fa9650499b48bca6">BinaryOp</a> and <a href="#a84a895de545b01b3ae407bc4c04b7b3d">BinaryOp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
