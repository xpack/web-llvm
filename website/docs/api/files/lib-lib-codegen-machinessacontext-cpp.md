---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/machinessacontext-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MachineSSAContext.cpp` File

<p>This file defines a specialization of the <a href="/web-llvm/docs/api/classes/llvm/genericssacontext">GenericSSAContext&lt;X&gt;</a> template class for Machine IR. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinessacontext-h">llvm/CodeGen/MachineSSAContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">llvm/CodeGen/GlobalISel/GenericMachineInstrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d3975d3ebe3475aef26122625d5b59">isUndef</a> (const MachineInstr &amp;MI)</td>
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

<p>This file defines a specialization of the <a href="/web-llvm/docs/api/classes/llvm/genericssacontext">GenericSSAContext&lt;X&gt;</a> template class for Machine IR.</p>

<div class="doxySectionDef">

## Functions

### isUndef() {#a31d3975d3ebe3475aef26122625d5b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isUndef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessacontext-cpp">MachineSSAContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600isellowering-cpp/#ad9e1097d647444e0c961dcd323944ff9">CompactSwizzlableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3f608529746b57d9dfbb1a3f5fa3dd6c">getGeneralPermuteNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a17fca146e0dc0228bae32fe5548ab48a">getKnownUndefForVectorBinop</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemzisellowering-cpp-/generalshuffle/#ab94f3858d30f3e1f5259e94182ed196d">anonymous{SystemZISelLowering.cpp}::GeneralShuffle::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a39175b5c07832217f180032fdb30664e">llvm::HexagonInstrInfo::getPredReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a76f8dfae3796fd187aebe3f8f60643ec">llvm::HexagonInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad73e9b3e610bd8cac60e740a61fcf5bf">llvm::SIInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1e7c6d51f5fc88c995098264f649357b">lowerV4X128Shuffle</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a69ed119a74aa160e44fcd158476e353e">resolveTargetShuffleInputsAndMask</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
