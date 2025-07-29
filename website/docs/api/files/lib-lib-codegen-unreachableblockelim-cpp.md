---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/unreachableblockelim-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `UnreachableBlockElim.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/unreachableblockelim-h">llvm/CodeGen/UnreachableBlockElim.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/depthfirstiterator-h">llvm/ADT/DepthFirstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-unreachableblockelim-cpp-">anonymous{UnreachableBlockElim.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-unreachableblockelim-cpp-/unreachableblockelimlegacypass">UnreachableBlockElimLegacyPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-unreachableblockelim-cpp-/unreachablemachineblockelim">UnreachableMachineBlockElim</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab28ca0716d1be6357a45d8a05df75970">INITIALIZE_PASS</a> (UnreachableBlockElimLegacyPass, "unreachableblockelim", "Remove unreachable blocks from the CFG", false, false) FunctionPass *llvm</td>
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

### INITIALIZE\_PASS() {#ab28ca0716d1be6357a45d8a05df75970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (UnreachableBlockElimLegacyPass, "unreachableblockelim", "Remove unreachable <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> from the CFG", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/unreachableblockelim-cpp">UnreachableBlockElim.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a12d11d4d4e6bb3d883283ad219cfe6d7">llvm::createUnreachableBlockEliminationPass</a> and <a href="/web-llvm/docs/api/classes/anonymous-unreachableblockelim-cpp-/unreachableblockelimlegacypass/#affc7d19bf24cecdba8f17f704746c159">anonymous{UnreachableBlockElim.cpp}::UnreachableBlockElimLegacyPass::UnreachableBlockElimLegacyPass</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
