---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-autoupgrade-cpp-/amdgpuunsafefpatomicsupgradevisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AMDGPUUnsafeFPAtomicsUpgradeVisitor` Struct Reference

<p>Replace "amdgpu-unsafe-fp-atomics" metadata with atomicrmw metadata. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{AutoUpgrade.cpp}::AMDGPUUnsafeFPAtomicsUpgradeVisitor { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor&lt;SubClass, RetTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for instruction visitors. <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4faddcd270ba6cd3786e3bab427093b">AMDGPUUnsafeFPAtomicsUpgradeVisitor</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5a373065be6eabfcc9eeb46018af87c">visitAtomicRMWInst</a> (AtomicRMWInst &amp;RMW)</td>
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

<p>Replace "amdgpu-unsafe-fp-atomics" metadata with atomicrmw metadata.</p>

<p>Definition at line 5370 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp">AutoUpgrade.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUUnsafeFPAtomicsUpgradeVisitor() {#ad4faddcd270ba6cd3786e3bab427093b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AutoUpgrade.cpp}::AMDGPUUnsafeFPAtomicsUpgradeVisitor::AMDGPUUnsafeFPAtomicsUpgradeVisitor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5372 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp">AutoUpgrade.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad73f9adce7cce90507a082ae3b30eb36">llvm::UpgradeFunctionAttributes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitAtomicRMWInst() {#aa5a373065be6eabfcc9eeb46018af87c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AutoUpgrade.cpp}::AMDGPUUnsafeFPAtomicsUpgradeVisitor::visitAtomicRMWInst (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> &amp; RMW)</td>
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



<p>Definition at line 5374 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp">AutoUpgrade.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a066f917f4a73ce07260b0e4262be92ba">DenseMapInfo&lt; LocallyHashedType &gt;::Empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a667d327df48643f4d2111a0065b192f2">llvm::AtomicRMWInst::isFloatingPointOperation</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp">AutoUpgrade.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
