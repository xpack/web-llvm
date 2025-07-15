---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegisterSubReg` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{HexagonConstPropagation.cpp}::RegisterSubReg { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5228a0271e8f0e88df0aa449fcf81c5b">RegisterSubReg</a> (unsigned R, unsigned SR=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8613449b5b6c5d95d101c614332ef89d">RegisterSubReg</a> (const MachineOperand &amp;MO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab10b3889207b3d3fdc8bcada6ea566cf">operator==</a> (const RegisterSubReg &amp;R) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd4439229542e32709e4d80db8449df8">print</a> (const TargetRegisterInfo *TRI=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70736188b24e0c19b8840c503758ab0c">Reg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0cde6a2675d991140fbe6de6287ef43">SubReg</a></td>
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


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegisterSubReg() {#a5228a0271e8f0e88df0aa449fcf81c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::RegisterSubReg (unsigned R, unsigned SR=0)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="#a70736188b24e0c19b8840c503758ab0c">Reg</a> and <a href="#ab0cde6a2675d991140fbe6de6287ef43">SubReg</a>.</p>


<p>Referenced by <a href="#ab10b3889207b3d3fdc8bcada6ea566cf">operator==</a>.</p>

</div>
</div>

### RegisterSubReg() {#a8613449b5b6c5d95d101c614332ef89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::RegisterSubReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="#a70736188b24e0c19b8840c503758ab0c">Reg</a> and <a href="#ab0cde6a2675d991140fbe6de6287ef43">SubReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#ab10b3889207b3d3fdc8bcada6ea566cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="#a70736188b24e0c19b8840c503758ab0c">Reg</a>, <a href="#a5228a0271e8f0e88df0aa449fcf81c5b">RegisterSubReg</a> and <a href="#ab0cde6a2675d991140fbe6de6287ef43">SubReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### print() {#abd4439229542e32709e4d80db8449df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI=nullptr)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="#a70736188b24e0c19b8840c503758ab0c">Reg</a>, <a href="#ab0cde6a2675d991140fbe6de6287ef43">SubReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Reg {#a70736188b24e0c19b8840c503758ab0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#a561e8197481b2a01d7f75fd567c7801e">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a3e49cc0a8c1be83f39602a85c288835f">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateANDri</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#afbb80dd4d686b8eda7304201f49f48e9">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateANDrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ac4917e6688b786a03dc01c382e1d9da3">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCLBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a46ce255d2c91bc39276b3abf153b1e58">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPri</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a069e11f50fb0348dacac4b0ad2715bbe">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPrp</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a3a175283278a754c84b75df5e20c5796">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2fb4263d9f6453677dfd6fc3e72ed999">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCTBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a342ccbdb8062b6646c20282b1367d686">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateEXTRACTr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a7ab7f3071651b3a1f99deea3408edd6e">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateORri</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a5c9526b09e12ac8a17ba2ab79aeff1c5">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateORrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a1254219a658c0740a16c1461cbb81e49">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateSEXTr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a992c70a7697deaf90987fc37148fc211">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateSplatr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a40b8bf88c0e4f03f5dfdcd1a34610530">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateXORri</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a812ba4120e868c63ef47c07d4963ec29">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateXORrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a9f45763d26a7cd4e3f11ebde35694017">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateZEXTr</a>, <a href="#ab10b3889207b3d3fdc8bcada6ea566cf">operator==</a>, <a href="#abd4439229542e32709e4d80db8449df8">print</a>, <a href="#a8613449b5b6c5d95d101c614332ef89d">RegisterSubReg</a> and <a href="#a5228a0271e8f0e88df0aa449fcf81c5b">RegisterSubReg</a>.</p>

</div>
</div>

### SubReg {#ab0cde6a2675d991140fbe6de6287ef43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::SubReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#a561e8197481b2a01d7f75fd567c7801e">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="#ab10b3889207b3d3fdc8bcada6ea566cf">operator==</a>, <a href="#abd4439229542e32709e4d80db8449df8">print</a>, <a href="#a8613449b5b6c5d95d101c614332ef89d">RegisterSubReg</a> and <a href="#a5228a0271e8f0e88df0aa449fcf81c5b">RegisterSubReg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
