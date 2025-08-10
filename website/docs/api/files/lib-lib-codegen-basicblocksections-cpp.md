---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/basicblocksections-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `BasicBlockSections.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionutils-h">llvm/CodeGen/BasicBlockSectionUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">llvm/CodeGen/BasicBlockSectionsProfileReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">llvm/CodeGen/MachinePostDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-basicblocksections-cpp-">anonymous{BasicBlockSections.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-basicblocksections-cpp-/basicblocksections">BasicBlockSections</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a302780ed34373cb384b67a94940f5">INITIALIZE_PASS_BEGIN</a> (BasicBlockSections, "bbsections-prepare", "Prepares for basic block sections, by splitting functions " "into clusters of basic blocks.", false, false) INITIALIZE_PASS_END(BasicBlockSections</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bbsections Prepares <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> basic <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> by splitting <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> into clusters of basic static false void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927aecb431f82466a89596d4ef11608e">updateBranches</a> (MachineFunction &amp;MF, const SmallVector&lt; MachineBasicBlock * &gt; &amp;PreLayoutFallThroughs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59db5d89fd98ad566ef2159ec3450f0d">assignSections</a> (MachineFunction &amp;MF, const DenseMap&lt; UniqueBBID, BBClusterInfo &gt; &amp;FuncClusterInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60aabc0aa9efc24ce6aa1ae42f363804">BBSectionsDetectSourceDrift</a>("bbsections-detect-source-drift", cl::desc("This checks if there is a fdo instr. profile hash " "mismatch for this function"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bbsections</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc01b07763ec8c4b7acd6ffaa69b1c0c">prepare</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bbsections Prepares <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> basic <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9bfff4f6c093ce614da964288d832c9">sections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bbsections Prepares <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> basic <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> by splitting <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> into clusters of basic</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b480a971048f2d9cc342c18046d7774">blocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bbsections Prepares <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> basic <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> by splitting <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> into clusters of basic</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add7ead10074b888229a003a53aca643e">false</a></td>
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

### assignSections() {#a59db5d89fd98ad566ef2159ec3450f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void assignSections (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/uniquebbid">UniqueBBID</a>, <a href="/web-llvm/docs/api/structs/llvm/bbclusterinfo">BBClusterInfo</a> &gt; &amp; FuncClusterInfo)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp">BasicBlockSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8ab1c94ca2fbc3e78fc30069c8d0f01680">llvm::All</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#a2cbbe04f568b5890eeb2b58c0cbf6d71">llvm::MBBSectionID::ColdSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#a27940a53407c67036b8292fa9bf4721d">llvm::MBBSectionID::ExceptionSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afab3c5f91842d5dd9f6aaf78a1ff34a9">llvm::TargetMachine::getBBSectionsType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a74e97fc3012191edf10e8c51291da4a7">llvm::MachineFunction::hasBBSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#ae6a302780ed34373cb384b67a94940f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (BasicBlockSections, "bbsections-prepare", "Prepares <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> basic <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> sections, by splitting <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> " "into clusters of basic blocks.", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp">BasicBlockSections.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### updateBranches() {#a927aecb431f82466a89596d4ef11608e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bbsections Prepares for basic block by splitting functions into clusters of basic static false void updateBranches (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; PreLayoutFallThroughs)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp">BasicBlockSections.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="#a927aecb431f82466a89596d4ef11608e">updateBranches</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afad2bbe677ba3de73946c95070c7cdb1">llvm::sortBasicBlocksAndUpdateBranches</a> and <a href="#a927aecb431f82466a89596d4ef11608e">updateBranches</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BBSectionsDetectSourceDrift {#a60aabc0aa9efc24ce6aa1ae42f363804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; BBSectionsDetectSourceDrift("bbsections-detect-source-drift", cl::desc("This checks if there is a fdo instr. profile hash " "mismatch for this function"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp">BasicBlockSections.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9758dcba3499ba13d2756537ffe9474b">llvm::hasInstrProfHashMismatch</a>.</p>

</div>
</div>

### blocks {#a6b480a971048f2d9cc342c18046d7774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">split region exit SPIRV split region exit blocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp">BasicBlockSections.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c/#ab9db1c5b05bdca5437891512850ef529">blake3_hash4_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#aa719af4ac5bfa12c07fce4e03d654400">blake3_hash_many</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#afafeb9e2f3c47a85a3455aba2ee5f454">blake3_hash_many_avx2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#aa6adfc4c100ace1a487ade1cc7923fdb">blake3_hash_many_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a6445e4f293da8868e140464290107427">blake3_hash_many_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#aa113f171b931c01e1d430d100cbaa9a5">blake3_hash_many_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#ad5daae07b2a1b3bcad41ad58c9cb4e85">blake3_hash_many_sse41</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovblock/#a1676ff1758dd5d5b69de46336cc186b0">llvm::GCOVBlock::getCyclesCount</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a9e635b2c582b6500e2c79faf06360ca2">llvm::GenericCycle&lt; ContextT &gt;::getExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1d9238c61483c12dce660bae4c8cc2d2">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#aad953b1e46f8bd2ca82b9cb7285a66a7">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#adf6f53d7652b471c995b7d10f3dd2729">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a408a62c86ed1c263bb09c6d2b7ec09d2">llvm::GenericCycle&lt; ContextT &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a46880fab7a9d5bd439725f2acc59b80d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a37c7357e371a02d89d2bc73d8749e6e4">hash_one_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ac500a9f4a684624f44bfa36853747379">hash_one_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a1e88636b91a8b17c44084bc2d93c5ef2">hash_one_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c/#ae4d3e60989e66a9a539f56f81426ca8a">hash_one_sse41</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinetracemetrics-cpp-/loopbounds/#a76153337eb4653e0590753dc7c09d0ab">anonymous{MachineTraceMetrics.cpp}::LoopBounds::LoopBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#aed7eee2aa41a7b67f3cfc9a6bc1f991a">llvm::RegionBase&lt; Tr &gt;::print</a> and <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a4cc24eca5caee29bd57f43e84c285ee3">llvm::GenericCycle&lt; ContextT &gt;::verifyCycle</a>.</p>

</div>
</div>

### false {#add7ead10074b888229a003a53aca643e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bbsections Prepares for basic block by splitting functions into clusters of basic false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp">BasicBlockSections.cpp</a>.</p>

</div>
</div>

### prepare {#acc01b07763ec8c4b7acd6ffaa69b1c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bbsections prepare</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp">BasicBlockSections.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a59a33017f4335b8fe1884ac2b18f2660">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::buildGraph</a> and <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a18192ed7893e8738ddd38e7f75bb3bf7">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::runOnMachineFunction</a>.</p>

</div>
</div>

### sections {#ad9bfff4f6c093ce614da964288d832c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bbsections Prepares for basic block sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp">BasicBlockSections.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a8e0db63318e9923b354d95e0391c05db">llvm::object::ELFFile&lt; ELFT &gt;::getDynSymtabSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a14680087ccae0d9f57cda7380290b23d">llvm::object::ELFFile&lt; ELFT &gt;::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ac224640f48ef4ce451d49bbb1b68e9ca">llvm::object::ELFFile&lt; ELFT &gt;::getSectionAndRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ad1657b415560e76194871821263f1273">llvm::object::ELFFile&lt; ELFT &gt;::getSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a26eb5a3830fae63f1263c58b0fb79621">llvm::object::ELFFile&lt; ELFT &gt;::getSHNDXTable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a6a6612a17f1ed83c751bab1ed91ce355">llvm::object::ELFFile&lt; ELFT &gt;::getStringTableForSymtab</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/inputfile/#ae28e8accd8d7e3b0572dc324db8116c7">llvm::pdb::InputFile::hasTypes</a> and <a href="/web-llvm/docs/api/groups/llvmcobject/#gabb7cdf8752b1939d369936207f9b25c1">LLVMObjectFileCopySectionIterator</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
