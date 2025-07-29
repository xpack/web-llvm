---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memtag/stackinfobuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `StackInfoBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::memtag::StackInfoBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">llvm/Transforms/Utils/MemoryTaggingSupport.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfaf86a95c9f8f6e6d521006ad42e4c6">StackInfoBuilder</a> (const StackSafetyGlobalInfo *SSI, const char *DebugType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a198373b43abedb70ae454c1111cdc8">visit</a> (OptimizationRemarkEmitter &amp;ORE, Instruction &amp;Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a0eeeec0f9e1caa19ab33122b2b94cd99">AllocaInterestingness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcaea10733b9350e0f00307e44ef2b0b">getAllocaInterestingness</a> (const AllocaInst &amp;AI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memtag/stackinfo">StackInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48a750c879fa4758c10ed5249fddc615">get</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memtag/stackinfo">StackInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91898e10c34b4af69e5c6f55f86387ed">Info</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfo">StackSafetyGlobalInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a48651b8ac1382b5162de009442fb41">SSI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a083cb838879acbcc663a4013e54ab">DebugType</a></td>
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


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">MemoryTaggingSupport.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StackInfoBuilder() {#adfaf86a95c9f8f6e6d521006ad42e4c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memtag::StackInfoBuilder::StackInfoBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfo">StackSafetyGlobalInfo</a> * SSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * DebugType)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">MemoryTaggingSupport.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#a48a750c879fa4758c10ed5249fddc615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackInfo &amp; llvm::memtag::StackInfoBuilder::get ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">MemoryTaggingSupport.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>.</p>

</div>
</div>

### getAllocaInterestingness() {#adcaea10733b9350e0f00307e44ef2b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInterestingness llvm::memtag::StackInfoBuilder::getAllocaInterestingness (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">MemoryTaggingSupport.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/memorytaggingsupport-cpp">MemoryTaggingSupport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a892fff96fbddc1bc777dd9b3ca02b116">llvm::memtag::getAllocaSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5023b360abc7a5d1612061fba30003a6">llvm::isAllocaPromotable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2ff127c9924cd3337080c4445c324aea">llvm::Type::isScalableTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8ad67a33bae235fe3cca1c3e5a91ed2d">llvm::Type::isSized</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a36e31f42170be95fc392dad696d9ba19">llvm::AllocaInst::isStaticAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a3016b467a9ecb5506956f7d029509db5">llvm::AllocaInst::isSwiftError</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9bb98c4ac4cf77f5782e5e41f2c6f38a">llvm::AllocaInst::isUsedWithInAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a0eeeec0f9e1caa19ab33122b2b94cd99afce9de4960d37e196206b76155b0977e">llvm::memtag::kInteresting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a0eeeec0f9e1caa19ab33122b2b94cd99a649258ef12005bf365897a3edab60a5e">llvm::memtag::kSafe</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a0eeeec0f9e1caa19ab33122b2b94cd99abfc835e6d1e3d55e2c5823c3c3d0d8ac">llvm::memtag::kUninteresting</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a> and <a href="#a2a198373b43abedb70ae454c1111cdc8">visit</a>.</p>

</div>
</div>

### visit() {#a2a198373b43abedb70ae454c1111cdc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memtag::StackInfoBuilder::visit (<a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">MemoryTaggingSupport.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/memorytaggingsupport-cpp">MemoryTaggingSupport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/memtag/allocainfo/#a0f0dd903636186ae7d95bebbca079e23">llvm::memtag::AllocaInfo::DbgVariableIntrinsics</a>, <a href="/web-llvm/docs/api/structs/llvm/memtag/allocainfo/#a39c42607bd7ed65458b29601dfdcb821">llvm::memtag::AllocaInfo::DbgVariableRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#aae6a98aea85aa3af87357cc5448db499">llvm::OptimizationRemarkEmitter::emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae876eb96b89c1afcc3e9cd285cc3f08c">llvm::filterDbgVars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21fe87bf00db76089c043fed6a23fb76">llvm::findAllocaForValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b2a153b655ed78a07468297eb4c6256">llvm::for_each</a>, <a href="#adcaea10733b9350e0f00307e44ef2b0b">getAllocaInterestingness</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a431be97c0e4d03f713d927197cdcfff0">llvm::Instruction::getDbgRecordRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#abee458caddc02e76d51e08dcf299ff16">llvm::memtag::getUntagLocationIfFunctionExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a0eeeec0f9e1caa19ab33122b2b94cd99afce9de4960d37e196206b76155b0977e">llvm::memtag::kInteresting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a0eeeec0f9e1caa19ab33122b2b94cd99a649258ef12005bf365897a3edab60a5e">llvm::memtag::kSafe</a> and <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a0eeeec0f9e1caa19ab33122b2b94cd99abfc835e6d1e3d55e2c5823c3c3d0d8ac">llvm::memtag::kUninteresting</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DebugType {#a90a083cb838879acbcc663a4013e54ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::memtag::StackInfoBuilder::DebugType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">MemoryTaggingSupport.h</a>.</p>

</div>
</div>

### Info {#a91898e10c34b4af69e5c6f55f86387ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackInfo llvm::memtag::StackInfoBuilder::Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">MemoryTaggingSupport.h</a>.</p>

</div>
</div>

### SSI {#a4a48651b8ac1382b5162de009442fb41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StackSafetyGlobalInfo* llvm::memtag::StackInfoBuilder::SSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">MemoryTaggingSupport.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memorytaggingsupport-h">MemoryTaggingSupport.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/memorytaggingsupport-cpp">MemoryTaggingSupport.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
