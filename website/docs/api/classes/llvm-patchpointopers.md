---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/patchpointopers
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PatchPointOpers` Class Reference

<p>MI-level patchpoint operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PatchPointOpers { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">llvm/CodeGen/StackMaps.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a6892641fbb4193030fe2ad0108407e06">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate the meta operands. <a href="#a6892641fbb4193030fe2ad0108407e06">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c909da0edfdf49c75cc43819f44bf7b">PatchPointOpers</a> (const MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2483e2d41750caf41e314334d91538b">isAnyReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55421adc5b3812f574f7dd5177899e5">hasDef</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a3543b67035589350015920ce01b489">getID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the given patchpoint. <a href="#a5a3543b67035589350015920ce01b489">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa319bb1da5a106c84bfa9a1fdca084bc">getNumPatchBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of patchable bytes the given patchpoint should emit. <a href="#aa319bb1da5a106c84bfa9a1fdca084bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86c02ad0c56344cf19e482d1924c9f6">getCallTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target of the underlying call. <a href="#ad86c02ad0c56344cf19e482d1924c9f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ababa24a89c7e88924f1028d6d8fb9cd2">getCallingConv</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the calling convention. <a href="#ababa24a89c7e88924f1028d6d8fb9cd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582a0ad937e482a52c1d3302e12a3003">getArgIdx</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a261d8b16e91a9c713a7679ba25f99dff">getNumCallArgs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of call arguments. <a href="#a261d8b16e91a9c713a7679ba25f99dff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae18aba1f392b005742fcc93f93ee022b">getVarIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the operand index of the variable list of non-argument operands. <a href="#ae18aba1f392b005742fcc93f93ee022b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf81f2558ea3364922ba63cb46e09ca4">getStackMapStartIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the index at which stack map locations will be recorded. <a href="#adf81f2558ea3364922ba63cb46e09ca4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ecfe362fe15df202b5605e5378eca1b">getNextScratchIdx</a> (unsigned StartIdx=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next scratch register operand index. <a href="#a4ecfe362fe15df202b5605e5378eca1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a709925e70c0d82c94a1cab2a53eb73fc">getMetaIdx</a> (unsigned Pos=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8241e306bacb3465542fda3a20b0490d">getMetaOper</a> (unsigned Pos) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae876702346d0979de688ce4aab64fadc">MI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb23eecbe5b6af5d670fb512cd5f3fa">HasDef</a></td>
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

<p>MI-level patchpoint operands.</p>


<p>MI patchpoint operations take the form: [&lt;def&gt;], &lt;id&gt;, &lt;numBytes&gt;, &lt;target&gt;, &lt;numArgs&gt;, &lt;cc&gt;, ...</p>


<p>IR patchpoint intrinsics do not have the &lt;cc&gt; operand because calling convention is part of the subclass data.</p>


<p>SD patchpoint nodes do not have a def operand because it is part of the <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>.</p>


<p>Patchpoints following the anyregcc convention are handled specially. For these, the stack map also records the location of the return value and arguments.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a6892641fbb4193030fe2ad0108407e06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enumerate the meta operands.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IDPos<a id="a6892641fbb4193030fe2ad0108407e06a08353423e1d98722d846a7c35ac15dc5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NBytesPos<a id="a6892641fbb4193030fe2ad0108407e06a67a19d60d058a368934cc4e9a9df8121"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetPos<a id="a6892641fbb4193030fe2ad0108407e06a7c453e33050b23cf322d4c17b8912088"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NArgPos<a id="a6892641fbb4193030fe2ad0108407e06ae275100bf95af7c46359bfe61ba14152"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CCPos<a id="a6892641fbb4193030fe2ad0108407e06a324a51adc0452a062355eff454118979"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MetaEnd<a id="a6892641fbb4193030fe2ad0108407e06a5dab820d4f492625bb59c6b902be42b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PatchPointOpers() {#a2c909da0edfdf49c75cc43819f44bf7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PatchPointOpers::PatchPointOpers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getArgIdx() {#a582a0ad937e482a52c1d3302e12a3003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PatchPointOpers::getArgIdx ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#a6892641fbb4193030fe2ad0108407e06a5dab820d4f492625bb59c6b902be42b3">MetaEnd</a>.</p>


<p>Referenced by <a href="#adf81f2558ea3364922ba63cb46e09ca4">getStackMapStartIdx</a>.</p>

</div>
</div>

### getCallingConv() {#ababa24a89c7e88924f1028d6d8fb9cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv::ID llvm::PatchPointOpers::getCallingConv ()</td>
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

<p>Returns the calling convention.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#a6892641fbb4193030fe2ad0108407e06a324a51adc0452a062355eff454118979">CCPos</a>.</p>


<p>Referenced by <a href="#aa2483e2d41750caf41e314334d91538b">isAnyReg</a>.</p>

</div>
</div>

### getCallTarget() {#ad86c02ad0c56344cf19e482d1924c9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand &amp; llvm::PatchPointOpers::getCallTarget ()</td>
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

<p>Returns the target of the underlying call.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#a6892641fbb4193030fe2ad0108407e06a7c453e33050b23cf322d4c17b8912088">TargetPos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#af3ec8e57004a88ea5cb892311c3c81ff">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a3cf266e359a05a56bd9533dff30b3e12">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::LowerPATCHPOINT</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a175c0b6f2f4c39ae659845dcef17f71b">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerPATCHPOINT</a>.</p>

</div>
</div>

### getID() {#a5a3543b67035589350015920ce01b489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::PatchPointOpers::getID ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the given patchpoint.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#a6892641fbb4193030fe2ad0108407e06a08353423e1d98722d846a7c35ac15dc5">IDPos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#ac29d96c130705fae151f95b1215e7ea2">llvm::StackMaps::recordPatchPoint</a>.</p>

</div>
</div>

### getNextScratchIdx() {#a4ecfe362fe15df202b5605e5378eca1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PatchPointOpers::getNextScratchIdx (unsigned StartIdx=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the next scratch register operand index.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae18aba1f392b005742fcc93f93ee022b">getVarIdx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#af3ec8e57004a88ea5cb892311c3c81ff">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerPATCHPOINT</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a3cf266e359a05a56bd9533dff30b3e12">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::LowerPATCHPOINT</a>.</p>

</div>
</div>

### getNumCallArgs() {#a261d8b16e91a9c713a7679ba25f99dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::PatchPointOpers::getNumCallArgs ()</td>
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

<p>Return the number of call arguments.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#a6892641fbb4193030fe2ad0108407e06ae275100bf95af7c46359bfe61ba14152">NArgPos</a>.</p>


<p>Referenced by <a href="#ae18aba1f392b005742fcc93f93ee022b">getVarIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#ac29d96c130705fae151f95b1215e7ea2">llvm::StackMaps::recordPatchPoint</a>.</p>

</div>
</div>

### getNumPatchBytes() {#aa319bb1da5a106c84bfa9a1fdca084bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::PatchPointOpers::getNumPatchBytes ()</td>
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

<p>Return the number of patchable bytes the given patchpoint should emit.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Reference <a href="#a6892641fbb4193030fe2ad0108407e06a67a19d60d058a368934cc4e9a9df8121">NBytesPos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a1bf38b3bbe867377cde6e530a0256b29">llvm::AArch64InstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adaba46ae7351c9a651fc32fae020cb0d">llvm::PPCInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a8424c147a24cf4d707de1b7392597e48">llvm::RISCVInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a4c2125b3c274c53648d92976315fb9e1">llvm::SystemZInstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#af3ec8e57004a88ea5cb892311c3c81ff">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a3cf266e359a05a56bd9533dff30b3e12">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::LowerPATCHPOINT</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a175c0b6f2f4c39ae659845dcef17f71b">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerPATCHPOINT</a>.</p>

</div>
</div>

### getStackMapStartIdx() {#adf81f2558ea3364922ba63cb46e09ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PatchPointOpers::getStackMapStartIdx ()</td>
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

<p>Get the index at which stack map locations will be recorded.</p>


<p>Arguments are not recorded unless the anyregcc convention is used.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>References <a href="#a582a0ad937e482a52c1d3302e12a3003">getArgIdx</a>, <a href="#ae18aba1f392b005742fcc93f93ee022b">getVarIdx</a> and <a href="#aa2483e2d41750caf41e314334d91538b">isAnyReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#ac29d96c130705fae151f95b1215e7ea2">llvm::StackMaps::recordPatchPoint</a>.</p>

</div>
</div>

### getVarIdx() {#ae18aba1f392b005742fcc93f93ee022b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PatchPointOpers::getVarIdx ()</td>
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

<p>Get the operand index of the variable list of non-argument operands.</p>


<p>These hold the "live state".</p>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>References <a href="#a261d8b16e91a9c713a7679ba25f99dff">getNumCallArgs</a> and <a href="#a6892641fbb4193030fe2ad0108407e06a5dab820d4f492625bb59c6b902be42b3">MetaEnd</a>.</p>


<p>Referenced by <a href="#a4ecfe362fe15df202b5605e5378eca1b">getNextScratchIdx</a> and <a href="#adf81f2558ea3364922ba63cb46e09ca4">getStackMapStartIdx</a>.</p>

</div>
</div>

### hasDef() {#af55421adc5b3812f574f7dd5177899e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatchPointOpers::hasDef ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#ac29d96c130705fae151f95b1215e7ea2">llvm::StackMaps::recordPatchPoint</a>.</p>

</div>
</div>

### isAnyReg() {#aa2483e2d41750caf41e314334d91538b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatchPointOpers::isAnyReg ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f42667edde6e9cb80cfae6361e5e76a">llvm::CallingConv::AnyReg</a> and <a href="#ababa24a89c7e88924f1028d6d8fb9cd2">getCallingConv</a>.</p>


<p>Referenced by <a href="#adf81f2558ea3364922ba63cb46e09ca4">getStackMapStartIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#ac29d96c130705fae151f95b1215e7ea2">llvm::StackMaps::recordPatchPoint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getMetaIdx() {#a709925e70c0d82c94a1cab2a53eb73fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PatchPointOpers::getMetaIdx (unsigned Pos=0)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### getMetaOper() {#a8241e306bacb3465542fda3a20b0490d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand &amp; llvm::PatchPointOpers::getMetaOper (unsigned Pos)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasDef {#aacb23eecbe5b6af5d670fb512cd5f3fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PatchPointOpers::HasDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

### MI {#ae876702346d0979de688ce4aab64fadc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* llvm::PatchPointOpers::MI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">StackMaps.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp">StackMaps.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
