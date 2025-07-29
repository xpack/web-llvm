---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ssplayoutinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SSPLayoutInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SSPLayoutInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">llvm/CodeGen/StackProtector.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cc5a1e59de3e5c2ce18d82ad08c068">SSPLayoutMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3df888d2d0447ad8ff7b616b080d9f13">MachineFrameInfo::SSPLayoutKind</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping of AllocaInsts to their required SSP layout. <a href="#a52cc5a1e59de3e5c2ce18d82ad08c068">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f0135e300b56f7db4aacce60c80d3c1">StackProtectorPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ceb9db4b8beac5e13e8c442ed675361">SSPLayoutAnalysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af85fe7fba38abff0ca451eded9075e13">StackProtector</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e112cf20dd9147017cd475f6f6cfd09">shouldEmitSDCheck</a> (const BasicBlock &amp;BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2068b15b4ae5d41ac05efbc9dd9dc48c">copyToMachineFrameInfo</a> (MachineFrameInfo &amp;MFI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">SSPLayoutMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0fbcd8c52e2d9e44def1a54e3e7db6e">Layout</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Layout - Mapping of allocations to the required SSPLayoutKind. <a href="#ab0fbcd8c52e2d9e44def1a54e3e7db6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107dd94d93c087392bb08a9c15faf31c">SSPBufferSize</a> = DefaultSSPBufferSize</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The minimum size of buffers that will receive stack smashing protection when -fstack-protection is used. <a href="#a107dd94d93c087392bb08a9c15faf31c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf60cf0af4549c790bf57b15791ea1b">RequireStackProtector</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d6d78fac7039390caf9df13d5ee790">HasPrologue</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe0b944306d43cf97c5b3c3e44babd42">HasIRCheck</a> = false</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac847298a9b214f1a54efc5f4748fa93c">DefaultSSPBufferSize</a> = 8</td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### SSPLayoutMap {#a52cc5a1e59de3e5c2ce18d82ad08c068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSPLayoutInfo::SSPLayoutMap = 
      DenseMap&lt;const AllocaInst *, MachineFrameInfo::SSPLayoutKind&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping of AllocaInsts to their required SSP layout.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### SSPLayoutAnalysis {#a8ceb9db4b8beac5e13e8c442ed675361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ssplayoutanalysis">SSPLayoutAnalysis</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>


<p>Reference <a href="#a8ceb9db4b8beac5e13e8c442ed675361">SSPLayoutAnalysis</a>.</p>


<p>Referenced by <a href="#a8ceb9db4b8beac5e13e8c442ed675361">SSPLayoutAnalysis</a>.</p>

</div>
</div>

### StackProtector {#af85fe7fba38abff0ca451eded9075e13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/stackprotector">StackProtector</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>


<p>Reference <a href="#af85fe7fba38abff0ca451eded9075e13">StackProtector</a>.</p>


<p>Referenced by <a href="#af85fe7fba38abff0ca451eded9075e13">StackProtector</a>.</p>

</div>
</div>

### StackProtectorPass {#a3f0135e300b56f7db4aacce60c80d3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/stackprotectorpass">StackProtectorPass</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>


<p>Reference <a href="#a3f0135e300b56f7db4aacce60c80d3c1">StackProtectorPass</a>.</p>


<p>Referenced by <a href="#a3f0135e300b56f7db4aacce60c80d3c1">StackProtectorPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyToMachineFrameInfo() {#a2068b15b4ae5d41ac05efbc9dd9dc48c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSPLayoutInfo::copyToMachineFrameInfo (<a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp; MFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp">StackProtector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a171600b1de399e1d60976508ffb38ea3">llvm::MachineFrameInfo::getObjectAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac51e2d34abb79b72afef355fac525c76">llvm::MachineFrameInfo::getObjectIndexEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af5302d38d9a16eee93f13a1579c8773d">llvm::MachineFrameInfo::isDeadObjectIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5938f9d0441c7b989d3e08e4dbd81ddf">llvm::MachineFrameInfo::setObjectSSPLayout</a>.</p>

</div>
</div>

### shouldEmitSDCheck() {#a6e112cf20dd9147017cd475f6f6cfd09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSPLayoutInfo::shouldEmitSDCheck (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp">StackProtector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasIRCheck {#afe0b944306d43cf97c5b3c3e44babd42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SSPLayoutInfo::HasIRCheck = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>

</div>
</div>

### HasPrologue {#a03d6d78fac7039390caf9df13d5ee790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SSPLayoutInfo::HasPrologue = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>

</div>
</div>

### Layout {#ab0fbcd8c52e2d9e44def1a54e3e7db6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SSPLayoutMap llvm::SSPLayoutInfo::Layout</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Layout - Mapping of allocations to the required SSPLayoutKind.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/stackprotector">StackProtector</a> analysis will update this map when determining if an <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> triggers a stack protector.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>

</div>
</div>

### RequireStackProtector {#a4bf60cf0af4549c790bf57b15791ea1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SSPLayoutInfo::RequireStackProtector = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>

</div>
</div>

### SSPBufferSize {#a107dd94d93c087392bb08a9c15faf31c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SSPLayoutInfo::SSPBufferSize = DefaultSSPBufferSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The minimum size of buffers that will receive stack smashing protection when -fstack-protection is used.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### DefaultSSPBufferSize {#ac847298a9b214f1a54efc5f4748fa93c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SSPLayoutInfo::DefaultSSPBufferSize = 8</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackprotector-h">StackProtector.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp">StackProtector.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
