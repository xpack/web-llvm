---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `WebAssemblyFixIrreducibleControlFlow.cpp` File Reference

<p>This file implements a pass that removes irreducible control flow. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">MCTargetDesc/WebAssemblyMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassembly-h">WebAssembly.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblysubtarget-h">WebAssemblySubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyfixirreduciblecontrolflow-cpp-">anonymous{WebAssemblyFixIrreducibleControlFlow.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-webassemblyfixirreduciblecontrolflow-cpp-/reachabilitygraph">ReachabilityGraph</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-webassemblyfixirreduciblecontrolflow-cpp-/loopblocks">LoopBlocks</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-webassemblyfixirreduciblecontrolflow-cpp-/webassemblyfixirreduciblecontrolflow">WebAssemblyFixIrreducibleControlFlow</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c2b0ae37197a8139ef3720fb1ca568">INITIALIZE_PASS</a> (WebAssemblyFixIrreducibleControlFlow, DEBUG_TYPE, "Removes irreducible control flow", false, false) FunctionPass *llvm</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b242745d9d1004fe6148b674533afb2">hasArgumentDef</a> (unsigned Reg, const MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cad575df04ef66a39c5d0d0501cf267">addImplicitDefs</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"wasm-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a86b29362e5d8fbb0d516610e4f988b5e">fix</a>-<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a5be285cef1cd1bde84856a9672ef48c0">irreducible</a>-control-flow"</td>
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

<p>This file implements a pass that removes irreducible control flow.</p>


<p>Irreducible control flow means multiple-entry loops, which this pass transforms to have a single entry.</p>


<p>Note that LLVM has a generic pass that lowers irreducible control flow, but it linearizes control flow, turning diamonds into two triangles, which is both unnecessary and undesirable for <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a>.</p>


<p>The big picture: We recursively process each "region", defined as a group of blocks with a single entry and no branches back to that entry. A region may be the entire function body, or the inner part of a loop, i.e., the loop's body without branches back to the loop entry. In each region we fix up multi-entry loops by adding a new block that can dispatch to each of the loop entries, based on the value of a label "helper" variable, and we replace direct branches to the entries with assignments to the label variable and a branch to the dispatch block. Then the dispatch block is the single entry in the loop containing the previous multiple entries. After ensuring all the loops in a region are reducible, we recurse into them. The total time complexity of this pass is:</p>


<p>O(NumBlocks * NumNestedLoops * NumIrreducibleLoops + NumLoops * NumLoops)</p>


<p>This pass is similar to what the Relooper [1] does. Both identify looping code that requires multiple entries, and resolve it in a similar way (in Relooper terminology, we implement a Multiple shape in a <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> shape). Note also that like the Relooper, we implement a "minimal" intervention: we only use the "label" helper for the blocks we absolutely must and no others. We also prioritize code size and do not duplicate code in order to resolve irreducibility. The graph algorithms for finding loops and entries and so forth are also similar to the Relooper. The main differences between this pass and the Relooper are:</p>


<ul class="doxyList ">
<li>We just care about irreducibility, so we just look at loops.</li>
<li>The Relooper emits structured control flow (with ifs etc.), while we emit a CFG.</li>
</ul>

<p>[1] Alon Zakai. 2011. Emscripten: an LLVM-to-JavaScript compiler. In Proceedings of the ACM international conference companion on Object oriented programming systems languages and applications companion (SPLASH '11). ACM, New York, NY, USA, 301-312. DOI=10.1145/2048147.2048224 <a href="http://doi.acm.org/10.1145/2048147.2048224">http://doi.acm.org/10.1145/2048147.2048224</a></p>


<div class="doxySectionDef">

## Functions

### addImplicitDefs() {#a0cad575df04ef66a39c5d0d0501cf267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addImplicitDefs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp">WebAssemblyFixIrreducibleControlFlow.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a0b242745d9d1004fe6148b674533afb2">hasArgumentDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a15296a1aa48a333f25583e31fd8f2a40">llvm::WebAssembly::isArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### hasArgumentDef() {#a0b242745d9d1004fe6148b674533afb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasArgumentDef (unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp">WebAssemblyFixIrreducibleControlFlow.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a15296a1aa48a333f25583e31fd8f2a40">llvm::WebAssembly::isArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a0cad575df04ef66a39c5d0d0501cf267">addImplicitDefs</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a43c2b0ae37197a8139ef3720fb1ca568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (WebAssemblyFixIrreducibleControlFlow, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Removes <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a5be285cef1cd1bde84856a9672ef48c0">irreducible</a> control flow", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp">WebAssemblyFixIrreducibleControlFlow.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab4082580a16cdd0171d1c17c3d03535f">llvm::createWebAssemblyFixIrreducibleControlFlow</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyfixirreduciblecontrolflow-cpp-/webassemblyfixirreduciblecontrolflow/#a00c9f9480368499900106a4afc135d3c">anonymous{WebAssemblyFixIrreducibleControlFlow.cpp}::WebAssemblyFixIrreducibleControlFlow::WebAssemblyFixIrreducibleControlFlow</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"wasm-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a86b29362e5d8fbb0d516610e4f988b5e">fix</a>-<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a5be285cef1cd1bde84856a9672ef48c0">irreducible</a>-control-flow"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp">WebAssemblyFixIrreducibleControlFlow.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
