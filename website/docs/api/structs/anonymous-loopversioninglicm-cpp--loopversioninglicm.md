---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoopVersioningLICM` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c56dcd1a62c59687720950119d2b7f4">LoopVersioningLICM</a> (AliasAnalysis *AA, ScalarEvolution *SE, OptimizationRemarkEmitter *ORE, LoopAccessInfoManager &amp;LAIs, LoopInfo &amp;LI, Loop *CurLoop)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a87ea3f5cfc5c16ffff0817a8067b1">run</a> (DominatorTree *DT)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a866d13516ceab27436e4374e5b952192">isLegalForVersioning</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks legality for <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm">LoopVersioningLICM</a> by considering following: a) loop structure legality b) loop instruction legality c) loop memory access legality. <a href="#a866d13516ceab27436e4374e5b952192">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf542dc26af5bf8b2b278cec0a93676">legalLoopStructure</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check loop structure and confirms it's good for <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm">LoopVersioningLICM</a>. <a href="#a5bf542dc26af5bf8b2b278cec0a93676">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58951aa459799666405bee8f592c4270">legalLoopInstructions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check loop instructions and confirms it's good for <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm">LoopVersioningLICM</a>. <a href="#a58951aa459799666405bee8f592c4270">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ad10ecfe362c9b65d77a756c0a4378">legalLoopMemoryAccesses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check memory accesses in loop and confirms it's good for <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm">LoopVersioningLICM</a>. <a href="#aa2ad10ecfe362c9b65d77a756c0a4378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bc8a1bb642c881cc70950e66becc0a6">isLoopAlreadyVisited</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It checks loop is already visited or not. <a href="#a0bc8a1bb642c881cc70950e66becc0a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ae2e8412241798cc6ddac82e13ea27">setNoAliasToLoop</a> (Loop *VerLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update loop with aggressive aliasing assumptions. <a href="#a53ae2e8412241798cc6ddac82e13ea27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25267de1eddeacc9d456248ecb143d99">instructionSafeForVersioning</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check loop instructions safe for <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> versioning. <a href="#a25267de1eddeacc9d456248ecb143d99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f7d2506aacc3b99d74723bfc8a66b3">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab864248a69c618d48aca45f3f691855c">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4247765edbb1131d66c2dca7cfe414fb">LAI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopaccessinfomanager">LoopAccessInfoManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70dcf616bb0572ac6399d08ff3c0831">LAIs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52107b6ffd6bda30bdfc0acca27a6342">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a9ae256c831b10e73d4740ea88096b">CurLoop</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9961d153e2387d95911ce45e4773f2">LoopDepthThreshold</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab185a845d09013845b321427864c6d">InvariantThreshold</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fb88ad28f856d722e3004a5b49e696">LoadAndStoreCounter</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a775c83d158a5a36ff0a6404505da4">InvariantCounter</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a21c06de8ef64829126143b0d1596a">IsReadOnlyLoop</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b20814dd828265f09cbcbef7d23de9">ORE</a></td>
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


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopVersioningLICM() {#a2c56dcd1a62c59687720950119d2b7f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::LoopVersioningLICM (<a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> * AA, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfomanager">LoopAccessInfoManager</a> &amp; LAIs, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurLoop)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp/#a55ae51707be8cdfb53a1e9385751f8ef">LVInvarThreshold</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp/#a42518b2ff57b4f9567d7c3d605adb86f">LVLoopDepthThreshold</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a24a87ea3f5cfc5c16ffff0817a8067b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVersioningLICM::run (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a55c9054d63d1c6a39e9c09ba13a482fa">llvm::addStringMetadataToLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#afc32c640645a5caeb9fe788699d4f75b">llvm::LoopVersioning::getNonVersionedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a296de170be5a983234de7d53da3c1635">llvm::LoopVersioning::getVersionedLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1a001d9051b71d83307766b1a96b7d3">llvm::hasLICMVersioningTransformation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp/#a05fae90ee62b36eb73e2b0f4e4626f3d">LICMVersioningMetaData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3e837c0d2a0521b4a4680071cac0dcbaa70bd8f3da4232ad809b2ffdcc1254bd">llvm::TM_Disable</a> and <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a65b5f9f4aa48ceb121d65679d8b1a689">llvm::LoopVersioning::versionLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### instructionSafeForVersioning() {#a25267de1eddeacc9d456248ecb143d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVersioningLICM::instructionSafeForVersioning (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check loop instructions safe for <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> versioning.</p>


<p>It returns true if it's safe else returns false. Consider following: 1) Check all load store in loop body are non atomic &amp; non volatile. 2) Check function call safety, by ensuring its not accessing memory. 3) <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> body shouldn't have any may throw instruction. 4) <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> body shouldn't have any convergent or noduplicate instructions.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### isLegalForVersioning() {#a866d13516ceab27436e4374e5b952192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVersioningLICM::isLegalForVersioning ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks legality for <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm">LoopVersioningLICM</a> by considering following: a) loop structure legality b) loop instruction legality c) loop memory access legality.</p>


<p>Return true if legal else returns false.</p>


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### isLoopAlreadyVisited() {#a0bc8a1bb642c881cc70950e66becc0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVersioningLICM::isLoopAlreadyVisited ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>It checks loop is already visited or not.</p>


<p>check loop meta data, if loop revisited return true else false.</p>


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### legalLoopInstructions() {#a58951aa459799666405bee8f592c4270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVersioningLICM::legalLoopInstructions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check loop instructions and confirms it's good for <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm">LoopVersioningLICM</a>.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### legalLoopMemoryAccesses() {#aa2ad10ecfe362c9b65d77a756c0a4378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVersioningLICM::legalLoopMemoryAccesses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check memory accesses in loop and confirms it's good for <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm">LoopVersioningLICM</a>.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### legalLoopStructure() {#a5bf542dc26af5bf8b2b278cec0a93676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVersioningLICM::legalLoopStructure ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check loop structure and confirms it's good for <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm">LoopVersioningLICM</a>.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### setNoAliasToLoop() {#a53ae2e8412241798cc6ddac82e13ea27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVersioningLICM::setNoAliasToLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * VerLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update loop with aggressive aliasing assumptions.</p>


<p>It marks no-alias to any pairs of memory operations by assuming loop should not have any must-alias memory accesses pairs. During <a href="/web-llvm/docs/api/structs/anonymous-loopversioninglicm-cpp-/loopversioninglicm">LoopVersioningLICM</a> legality we ignore loops having must aliasing memory accesses.</p>


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a74f7d2506aacc3b99d74723bfc8a66b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### CurLoop {#aa9a9ae256c831b10e73d4740ea88096b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::CurLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### InvariantCounter {#a31a775c83d158a5a36ff0a6404505da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::InvariantCounter = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### InvariantThreshold {#abab185a845d09013845b321427864c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::InvariantThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### IsReadOnlyLoop {#a19a21c06de8ef64829126143b0d1596a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::IsReadOnlyLoop = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### LAI {#a4247765edbb1131d66c2dca7cfe414fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopAccessInfo* anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::LAI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### LAIs {#ae70dcf616bb0572ac6399d08ff3c0831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopAccessInfoManager&amp; anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::LAIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### LI {#a52107b6ffd6bda30bdfc0acca27a6342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo&amp; anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### LoadAndStoreCounter {#ac3fb88ad28f856d722e3004a5b49e696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::LoadAndStoreCounter = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### LoopDepthThreshold {#acd9961d153e2387d95911ce45e4773f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::LoopDepthThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### ORE {#a85b20814dd828265f09cbcbef7d23de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

### SE {#ab864248a69c618d48aca45f3f691855c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* anonymous{LoopVersioningLICM.cpp}::LoopVersioningLICM::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopversioninglicm-cpp">LoopVersioningLICM.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
