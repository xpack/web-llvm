---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/armselectiondaginfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARMSelectionDAGInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-h">ARMTargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">llvm/CodeGen/SelectionDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0558cf546b4384bd63343c79e8b9f198">shouldGenerateInlineTPLoop</a> (const ARMSubtarget &amp;Subtarget, const SelectionDAG &amp;DAG, ConstantSDNode *ConstantSize, Align Alignment, bool IsMemcpy)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/tploop/#aec6cc0f26afef38af689286c2a436277">TPLoop::MemTransfer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37f8fc364f1b4eafbfe8d02dbd4f9607">EnableMemtransferTPLoop</a>("arm-memtransfer-tploop", cl::Hidden, cl::desc("Control conversion of memcpy to " "Tail predicated loops (WLSTP)"), cl::init(TPLoop::ForceDisabled), cl::values(clEnumValN(TPLoop::ForceDisabled, "force-disabled", "Don't convert memcpy to TP loop."), clEnumValN(TPLoop::ForceEnabled, "force-enabled", "Always convert memcpy to TP loop."), clEnumValN(TPLoop::Allow, "allow", "Allow (may be subject to certain conditions) " "conversion of memcpy to TP loop.")))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"arm-selectiondag-info"</td>
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


<div class="doxySectionDef">

## Functions

### shouldGenerateInlineTPLoop() {#a0558cf546b4384bd63343c79e8b9f198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldGenerateInlineTPLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> * ConstantSize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool IsMemcpy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armselectiondaginfo-cpp">ARMSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="#a37f8fc364f1b4eafbfe8d02dbd4f9607">EnableMemtransferTPLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tploop/#aec6cc0f26afef38af689286c2a436277a878012c51c8edbf0f3040dea615a7fbd">llvm::TPLoop::ForceEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a819d13e401dbf1301acb495576c812c3">llvm::ARMSubtarget::getMaxInlineSizeThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a77f8d562867710b25b1202aa703ad2ce">llvm::ARMSubtarget::getMaxMemcpyTPInlineSizeThreshold</a> and <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a5cb49674ec65724b4d9aecb48588a13a">llvm::ConstantSDNode::getZExtValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a4d3a29c0e2103ce92ec80ac1f6eee78a">llvm::ARMSelectionDAGInfo::EmitTargetCodeForMemcpy</a> and <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a452e4db911448c4d2180e4535b03d8fe">llvm::ARMSelectionDAGInfo::EmitTargetCodeForMemset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnableMemtransferTPLoop {#a37f8fc364f1b4eafbfe8d02dbd4f9607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; TPLoop::MemTransfer &gt; EnableMemtransferTPLoop("arm-memtransfer-tploop", cl::Hidden, cl::desc("Control conversion of memcpy to " "Tail predicated loops (WLSTP)"), cl::init(TPLoop::ForceDisabled), cl::values(clEnumValN(TPLoop::ForceDisabled, "force-disabled", "Don't convert memcpy to TP loop."), clEnumValN(TPLoop::ForceEnabled, "force-enabled", "Always convert memcpy to TP loop."), clEnumValN(TPLoop::Allow, "allow", "Allow (may be subject to certain conditions) " "conversion of memcpy to TP loop.")))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armselectiondaginfo-cpp">ARMSelectionDAGInfo.cpp</a>.</p>


<p>Referenced by <a href="#a0558cf546b4384bd63343c79e8b9f198">shouldGenerateInlineTPLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"arm-selectiondag-info"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armselectiondaginfo-cpp">ARMSelectionDAGInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
