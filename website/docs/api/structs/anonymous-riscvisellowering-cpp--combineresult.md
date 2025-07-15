---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-riscvisellowering-cpp-/combineresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CombineResult` Struct Reference

<p>Helper structure that holds all the necessary information to materialize a combine that does some extension folding. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{RISCVISelLowering.cpp}::CombineResult { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dee54c7d68e1b150a0b76755e7f7737">CombineResult</a> (unsigned TargetOpcode, SDNode *Root, const NodeExtensionHelper &amp;LHS, std::optional&lt; ExtKind &gt; LHSExt, const NodeExtensionHelper &amp;RHS, std::optional&lt; ExtKind &gt; RHSExt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a29551e352719a5e4d927f1a5e0871b">materialize</a> (SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a value that uses TargetOpcode and that can be used to replace Root. <a href="#a6a29551e352719a5e4d927f1a5e0871b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8494be8ac4cbbeb2411783b3b3b78e">TargetOpcode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opcode to be generated when materializing the combine. <a href="#acd8494be8ac4cbbeb2411783b3b3b78e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7">ExtKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06233bd5826dbeaf55baccfae5bff593">LHSExt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7">ExtKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c23af45f42727ef440f6f91d6982dc">RHSExt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0658bfaf1c4ff505264ef125941058de">Root</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Root of the combine. <a href="#a0658bfaf1c4ff505264ef125941058de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ceacb927ae29acf59391a796c5af1b2">LHS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LHS of the TargetOpcode. <a href="#a6ceacb927ae29acf59391a796c5af1b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fabff40896c983796becad2c3cca0dc">RHS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RHS of the TargetOpcode. <a href="#a3fabff40896c983796becad2c3cca0dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper structure that holds all the necessary information to materialize a combine that does some extension folding.</p>

<p>Definition at line 15534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CombineResult() {#a8dee54c7d68e1b150a0b76755e7f7737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVISelLowering.cpp}::CombineResult::CombineResult (unsigned TargetOpcode, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; LHS, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7">ExtKind</a> &gt; LHSExt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper">NodeExtensionHelper</a> &amp; RHS, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a0fb45dddfe1615e320ac9ad137d634e7">ExtKind</a> &gt; RHSExt)</td>
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



<p>Definition at line 15547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="#a6ceacb927ae29acf59391a796c5af1b2">LHS</a>, <a href="#a06233bd5826dbeaf55baccfae5bff593">LHSExt</a>, <a href="#a3fabff40896c983796becad2c3cca0dc">RHS</a>, <a href="#a20c23af45f42727ef440f6f91d6982dc">RHSExt</a>, <a href="#a0658bfaf1c4ff505264ef125941058de">Root</a> and <a href="#acd8494be8ac4cbbeb2411783b3b3b78e">TargetOpcode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### materialize() {#a6a29551e352719a5e4d927f1a5e0871b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{RISCVISelLowering.cpp}::CombineResult::materialize (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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

<p>Return a value that uses TargetOpcode and that can be used to replace Root.</p>


<p>The actual replacement is <em>not</em> done in that method.</p>


<p>Definition at line 15556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a0aaa2e30b965ca8584badc25c324958d">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getMaskAndVL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="#a6ceacb927ae29acf59391a796c5af1b2">LHS</a>, <a href="#a06233bd5826dbeaf55baccfae5bff593">LHSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="#a3fabff40896c983796becad2c3cca0dc">RHS</a>, <a href="#a20c23af45f42727ef440f6f91d6982dc">RHSExt</a>, <a href="#a0658bfaf1c4ff505264ef125941058de">Root</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a> and <a href="#acd8494be8ac4cbbeb2411783b3b3b78e">TargetOpcode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LHS {#a6ceacb927ae29acf59391a796c5af1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeExtensionHelper anonymous{RISCVISelLowering.cpp}::CombineResult::LHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LHS of the TargetOpcode.</p>

<p>Definition at line 15543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a8dee54c7d68e1b150a0b76755e7f7737">CombineResult</a> and <a href="#a6a29551e352719a5e4d927f1a5e0871b">materialize</a>.</p>

</div>
</div>

### LHSExt {#a06233bd5826dbeaf55baccfae5bff593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;ExtKind&gt; anonymous{RISCVISelLowering.cpp}::CombineResult::LHSExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 15538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a8dee54c7d68e1b150a0b76755e7f7737">CombineResult</a> and <a href="#a6a29551e352719a5e4d927f1a5e0871b">materialize</a>.</p>

</div>
</div>

### RHS {#a3fabff40896c983796becad2c3cca0dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeExtensionHelper anonymous{RISCVISelLowering.cpp}::CombineResult::RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RHS of the TargetOpcode.</p>

<p>Definition at line 15545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a8dee54c7d68e1b150a0b76755e7f7737">CombineResult</a> and <a href="#a6a29551e352719a5e4d927f1a5e0871b">materialize</a>.</p>

</div>
</div>

### RHSExt {#a20c23af45f42727ef440f6f91d6982dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;ExtKind&gt; anonymous{RISCVISelLowering.cpp}::CombineResult::RHSExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 15539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a8dee54c7d68e1b150a0b76755e7f7737">CombineResult</a> and <a href="#a6a29551e352719a5e4d927f1a5e0871b">materialize</a>.</p>

</div>
</div>

### Root {#a0658bfaf1c4ff505264ef125941058de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode* anonymous{RISCVISelLowering.cpp}::CombineResult::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Root of the combine.</p>

<p>Definition at line 15541 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a8dee54c7d68e1b150a0b76755e7f7737">CombineResult</a> and <a href="#a6a29551e352719a5e4d927f1a5e0871b">materialize</a>.</p>

</div>
</div>

### TargetOpcode {#acd8494be8ac4cbbeb2411783b3b3b78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVISelLowering.cpp}::CombineResult::TargetOpcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Opcode to be generated when materializing the combine.</p>

<p>Definition at line 15536 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a8dee54c7d68e1b150a0b76755e7f7737">CombineResult</a> and <a href="#a6a29551e352719a5e4d927f1a5e0871b">materialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp">RISCVISelLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
