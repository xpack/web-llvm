---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-systemztargetmachine-cpp-/systemzpassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SystemZPassConfig` Class

<p><a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SystemZTargetMachine.cpp}::SystemZPassConfig { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-Independent Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a691391ff8ce9720f6336d837a939be2f">SystemZPassConfig</a> (SystemZTargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine">SystemZTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad72edd4fc67f57e6bb8efd1c06065c90">getSystemZTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e3ce316d9615d839202f19508133fa">createPostMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to createMachineScheduler but used when postRA machine scheduling is enabled. <a href="#a77e3ce316d9615d839202f19508133fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82bc48e46fd5fd0e8ea10f606c53d612">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#a82bc48e46fd5fd0e8ea10f606c53d612">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af9c51262f60a40c964573cb830b293">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#a6af9c51262f60a40c964573cb830b293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b78c3bdd43cc4512ab6df70122f019">addILPOpts</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes that optimize instruction level parallelism for out-of-order targets. <a href="#a71b78c3bdd43cc4512ab6df70122f019">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc88ad748273dde5fb776729a09178b3">addPreRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before register allocation. <a href="#abc88ad748273dde5fb776729a09178b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaed8a18b9a4f84ccb3570af74d9058c">addPostRewrite</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes to be run immediately after virtual registers are rewritten to physical registers. <a href="#aaaed8a18b9a4f84ccb3570af74d9058c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669a86eba8b8ea36b6884a438d09d4a1">addPostRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#a669a86eba8b8ea36b6884a438d09d4a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aba6912339c79370b1d8037df0c9c6a">addPreSched2</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass. <a href="#a9aba6912339c79370b1d8037df0c9c6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec37fe0cba0b6b61f6d64e6cbb7a7304">addPreEmitPass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#aec37fe0cba0b6b61f6d64e6cbb7a7304">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SystemZPassConfig() {#a691391ff8ce9720f6336d837a939be2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SystemZTargetMachine.cpp}::SystemZPassConfig::SystemZPassConfig (<a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine">SystemZTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addILPOpts() {#a71b78c3bdd43cc4512ab6df70122f019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZPassConfig::addILPOpts ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add passes that optimize instruction level parallelism for out-of-order targets.</p>


<p>These passes are run while the machine code is still in SSA form, so they can use MachineTraceMetrics to control their heuristics.</p>


<p>All passes added here should preserve the MachineDominatorTree, MachineLoopInfo, and MachineTraceMetrics analyses.</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57e66365c51f9fe42173246196dc25f1">llvm::EarlyIfConverterLegacyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetmachine-cpp/#a0c4b282869e4cacc995ab58c138cc283">EnableMachineCombinerPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a62834da6fd24fb8766861fafa8c4049e">llvm::MachineCombinerID</a>.</p>

</div>
</div>

### addInstSelector() {#a6af9c51262f60a40c964573cb830b293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZPassConfig::addInstSelector ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16df370b61f497043d087ca81a0ae750">llvm::createSystemZISelDag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9431642067217dc8ccafb6fbaca3b2a7">llvm::createSystemZLDCleanupPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="#ad72edd4fc67f57e6bb8efd1c06065c90">getSystemZTargetMachine</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addIRPasses() {#a82bc48e46fd5fd0e8ea10f606c53d612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPassConfig::addIRPasses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adebabb5e491a19ce4466a326d41641e0">llvm::createAtomicExpandLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c077d5ecfb6be89f42babfdce5a71d3">llvm::createLoopDataPrefetchPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6703dc9d0852b1ea4f497ae9bf1fd">llvm::createSystemZTDCPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPostRegAlloc() {#a669a86eba8b8ea36b6884a438d09d4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPassConfig::addPostRegAlloc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acddb5eb680668bee7cb0ba5fb3417afe">llvm::createSystemZPostRewritePass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="#ad72edd4fc67f57e6bb8efd1c06065c90">getSystemZTargetMachine</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPostRewrite() {#aaaed8a18b9a4f84ccb3570af74d9058c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPassConfig::addPostRewrite ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add passes to be run immediately after virtual registers are rewritten to physical registers.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acddb5eb680668bee7cb0ba5fb3417afe">llvm::createSystemZPostRewritePass</a> and <a href="#ad72edd4fc67f57e6bb8efd1c06065c90">getSystemZTargetMachine</a>.</p>

</div>
</div>

### addPreEmitPass() {#aec37fe0cba0b6b61f6d64e6cbb7a7304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPassConfig::addPreEmitPass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4007a15bc63e3cf035a70d0a0324cfe7">llvm::createSystemZElimComparePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1386c7aa34a87794c0ef236de2102991">llvm::createSystemZLongBranchPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a88853c32c18b68474db3ce534a385c1e">llvm::createSystemZShortenInstPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="#ad72edd4fc67f57e6bb8efd1c06065c90">getSystemZTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a51a34bf4ca8119bdeb89ffc48c5d4783">llvm::PostMachineSchedulerID</a>.</p>

</div>
</div>

### addPreRegAlloc() {#abc88ad748273dde5fb776729a09178b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPassConfig::addPreRegAlloc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method may be implemented by targets that want to run passes immediately before register allocation.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3615e4ef0861cfe25b44dc72ca24d634">llvm::createSystemZCopyPhysRegsPass</a> and <a href="#ad72edd4fc67f57e6bb8efd1c06065c90">getSystemZTargetMachine</a>.</p>

</div>
</div>

### addPreSched2() {#a9aba6912339c79370b1d8037df0c9c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZPassConfig::addPreSched2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6820b1346e9140b1b40af95c5ec190a">llvm::IfConverterID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### createPostMachineScheduler() {#a77e3ce316d9615d839202f19508133fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * anonymous{SystemZTargetMachine.cpp}::SystemZPassConfig::createPostMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to createMachineScheduler but used when postRA machine scheduling is enabled.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### getSystemZTargetMachine() {#ad72edd4fc67f57e6bb8efd1c06065c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SystemZTargetMachine &amp; anonymous{SystemZTargetMachine.cpp}::SystemZPassConfig::getSystemZTargetMachine ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>


<p>Referenced by <a href="#a6af9c51262f60a40c964573cb830b293">addInstSelector</a>, <a href="#a669a86eba8b8ea36b6884a438d09d4a1">addPostRegAlloc</a>, <a href="#aaaed8a18b9a4f84ccb3570af74d9058c">addPostRewrite</a>, <a href="#aec37fe0cba0b6b61f6d64e6cbb7a7304">addPreEmitPass</a> and <a href="#abc88ad748273dde5fb776729a09178b3">addPreRegAlloc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp">SystemZTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
