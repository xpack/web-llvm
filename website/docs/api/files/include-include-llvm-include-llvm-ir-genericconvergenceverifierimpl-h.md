---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/ir/genericconvergenceverifierimpl-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `GenericConvergenceVerifierImpl.h` File

<p>A verifier for the static rules of convergence control tokens that works with both LLVM IR and MIR. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericconvergenceverifier-h">llvm/ADT/GenericConvergenceVerifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb73b5d562083dde29e9091dd81bef3">Check</a>(C, ...)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fee20ad578f1c6d3061e37925fe7275">CheckOrNull</a>(C, ...)&nbsp;&nbsp;&nbsp;...</td>
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

<p>A verifier for the static rules of convergence control tokens that works with both LLVM IR and MIR.</p>


<p>This template implementation resides in a separate file so that it does not get injected into every .cpp file that includes the generic header.</p>


<p>DO NOT INCLUDE THIS FILE WHEN MERELY USING CYCLEINFO.</p>


<p>This file should only be included by files that implement a specialization of the relevant templates. Currently these are:</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp">llvm/lib/IR/Verifier.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">llvm/lib/CodeGen/MachineVerifier.cpp</a></li>
</ul>

<div class="doxySectionDef">

## Macro Definitions

### Check {#a2bb73b5d562083dde29e9091dd81bef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Check(C, ...)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>)) {                                                                \
      reportFailure(__VA_ARGS__);                                              \
      return;                                                                  \
    }                                                                          \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (false)
</div>
</dd>
</dl>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/genericconvergenceverifierimpl-h">GenericConvergenceVerifierImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmcinstrinfo-cpp-/#abda7c7a2d206ce064b97412b007ea5af">anonymous{HexagonMCInstrInfo.cpp}::canonicalizePacketImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#abc12092fd1db13a69edf142bcad15556">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::collectMemchecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a01159155e0e1288fdee10e8077d347e4">DecodeAddrMode2IdxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a748fded8b9c14e77783f32aa13b93af7">DecodeAddrMode3Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a1719003051d48a2e0a048a932e7ab2b1">DecodeAddrMode5FP16Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a674f8e4f3cc5c0f3c600feac22465ba6">DecodeAddrMode5Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a0d5ddcf46b56506e76a27912ea226388">DecodeAddrMode6Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#addca720009fe6ab83b7c148342b5f87b">DecodeAddrModeImm12Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2d3a2f957bed112cb510b5d278872555">DecodeArmMOVTWInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a27e9d06f7e445ced766e065dd4acc072">DecodeBitfieldMaskOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a36413fd3a08347a6defae0004efa31ba">DecodeBranchImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7b3ca5b536ce1c58a39b853ea79de51b">DecodeCopMemInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4144ff726054b8ab8750ac9b60da1979">DecodeDoubleRegLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a067843ccf524c115a5ce33144d3aace8">DecodeDoubleRegStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a248925af9b0eb0dce8470b478e4e2ca8">DecodeDPRRegListOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afe0a70f7662c3f654851dbf51ff0fa4a">DecodeForVMRSandVMSR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2c627ce5f7741d2d15897107b7ed70e8">DecodeGPRnopcRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af82605053349c55127574f989ce60019">DecodeGPRnospRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a3a72488c4dd03c87b64f1e0a25ff3ae9">DecodeGPRwithAPSRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa77d9c4a29c8077c49b1c2e0d0b4a684">DecodeGPRwithZRnospRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a786e03096ad3a3a0022c0aaadc909fd6">DecodeGPRwithZRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ae96b7f8b4b8e35d28617a90604289b0b">DecodeHINTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afbc53e43e60687c280c643165c8c8a16">DecodeLazyLoadStoreMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a592880402c3557e592fd617a6404807f">DecodeLDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ade3de8655e8cd7260d807f9cea0701b8">DecodeLDRPreImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a04f793a8e90b0d329fdea0bb8c1f2356">DecodeLDRPreReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afecebd0151d705a1f451129515690010">DecodeLOLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aee22f63177a59f1c073fc689b38933ae">DecodeMemMultipleWritebackInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#abce56c400103d42efc06f81d97ed979c">DecodeMVE_MEM_pre</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aaa973fa80051d521ca126e6baec9b849">DecodeMveAddrModeQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aba042b54f8c582939b1efa62e08000b3">DecodeMveAddrModeRQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa6165f97e90eaea7675b635e2d2a1a3a">DecodeMVEModImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ace68fb9d35b1e3f7c97175ebeb16e386">DecodeMVEOverlappingLongShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aec419b455f0b73caa44637f09817ec4f">DecodeMVEVADCInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a111ed526e6e5818e4bd6f7c459c883ab">DecodeMVEVCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ac31edd9f4eb883611f651f89005c8878">DecodeMveVCTP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ab201350cfc0d9d9353ffc3c7b4d99b5c">DecodeMVEVCVTt1fp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a1270d23ac4d95c35151585a99d022028">DecodeMVEVMOVDRegtoQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ab75960dda5858220e6442740cd47c020">DecodeMVEVMOVQtoDReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a03d54559851ae68e67660bdd39fc0f83">DecodeNEONComplexLane64Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a968efe31b652445ecd031c2d15a1ae31">DecodePostIdxReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad22d00715292f5cf5d09380b15cb6189">DecodePredicateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a46ace96c930c483858d57c90bbeaa257">DecodeQADDInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acde34c306f55bfc47634d259c0115e0d">DecodeRegListOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aedf86c5895d19485c6219652fdf5bd3d">DecodeRFEInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a27d5f895980d5049799b32f5d4161d4e">DecoderForMRRC2AndMCRR2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a310c5c1f640179ad5adadd0cdbad1b52">DecoderGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a75cd3f70d0beaa0d481f60be56a927cc">DecodeSMLAInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a1742de415bfaad8eb71b09f017c248a9">DecodeSORegImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a20e9fffc7ece71cc090e060083bba8a5">DecodeSORegMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af9c9828e7054789502f5b58a859a989e">DecodeSORegRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa01ca7ebcc611fac84d8164384f211df">DecodeSPRRegListOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aca8d5712120853edda117fb57ac24c00">DecodeSTRPreImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a496c8b0fe7b5fda345cc839544357d40">DecodeSTRPreReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a764505cabfd01c2f66766fa3549edbac">DecodeSwap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a01bd6143a4a986faffacd16015813009">DecodeT2AddrModeImm0_1020s4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a02d69d029e1221f31502f0ea27919fce">DecodeT2AddrModeImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad636ec05e3285addf901d9f89b7c13ed">DecodeT2AddrModeImm7</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a3679ed4fe7681519419e754f9cfeb4c0">DecodeT2AddrModeImm7s4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2eaef92ac016b6867cf2e684b5bb76c7">DecodeT2AddrModeImm8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#abeed7093071fc196970036b758eb3da3">DecodeT2AddrModeImm8s4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ad2d2ec79ae9dffdbfb48ad8d5127545e">DecodeT2AddrModeSOReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a5686943937ea2fcb33898d72abca31ef">DecodeT2AddSubSPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9ac46a3cd7dcc8838c2173bf507a330d">DecodeT2LDRDPreInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa0db3bd9104dd7f086c6f8686f59c288">DecodeT2LdStPre</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a57b019630c1fd92a4bf745e6639f344a">DecodeT2LoadImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa5cc177b319e4695ef7c2b627ed4a5e6">DecodeT2LoadImm8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a18ec82d05c3fecd8d313d76aa6cf4d88">DecodeT2LoadLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aaab47c414bc9052d5ae109a30036ae38">DecodeT2LoadShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a08bf371630cff66c49e3aaebc6b7337d">DecodeT2LoadT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a3d6b4d56448a550e780bcc286defca12">DecodeT2MOVTWInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a862021f0473d4d7455f3edfea8465b7d">DecodeT2STRDPreInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a349b2fdb6946ef7d50d2bf6116319d96">DecodeTAddrModeImm7</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ade174bb0481f851b34f77b9f83c5b7ae">DecodeTBLInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2c2187f74d4f13ec46f8bd522ab7f5e4">DecodeThumb2BCCInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a43c40604d096e3bab514a393fd825d5f">DecodeThumbAddrModeIS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af4d267889f25bc68fd5b84a102fec0e3">DecodeThumbAddrModeRR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9d49e57d960810a6cdebef656a7d12c1">DecodeThumbAddSpecialReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4ff9913a6a8ee09237b7bdb7350f8758">DecodeThumbAddSPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a23720a1f4582fe48cb949b1189f3d058">DecodeThumbTableBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#adc97046c80e5338d47c2e57439d3d58d">DecodeTSTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a78802c522ed764cedc1bafcf628dd154">DecodeVCVTD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9e5902642b306bad7e557cc0030a8c3b">DecodeVCVTQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4bc58a6a4cc485df54316ee63961494a">DecodeVLD1DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a88cfc4461fad680d4d3b2dca75c06462">DecodeVLD1LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#adbfb7c834c41c75925284ebcb3e30a43">DecodeVLD2DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a55963f98bd8421645c77a3bc2497015d">DecodeVLD2LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7bce2d579f601f86a9e4746623988063">DecodeVLD3DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a989cc7ee36e295c4132740950cd1aec8">DecodeVLD3LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a53b3d214dc2e26fcfb82d711dd7e897f">DecodeVLD4DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a241bba0734ea7a40a6fb2b7cfc63f72e">DecodeVLD4LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa46c26cc972273e7463a3ebe3a9cedad">DecodeVLDInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a41d6edfa220d2050c7c245dd1e5e5fec">DecodeVMOVModImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a67d16298e447dd109816c49a4d6b2de6">DecodeVMOVRRS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afa9ccba50c08dbd23c30037e0a0ee6f8">DecodeVMOVSRR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aea8ff3695bbef57d56a2d23873b029bf">DecodeVSCCLRM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a0d6877e515e068fc4847049790f9db94">DecodeVSHLMaxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a585fe45145ba2dfdfbddf6544fbcc853">DecodeVST1LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acc2c3a559d83ea0fc94b5cd90fa6b774">DecodeVST2LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a5bc2379dda1ba55eae95c132f3cc5e99">DecodeVST3LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ac5d71fed959a923e986adb309f260ea9">DecodeVST4LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a83aef7e6f90ca5e44f3927132a133315">DecodeVSTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a8ed86ab442732ed8bfdbb259af9edfc6">DecodeVSTRVLDR_SYSREG</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a63540fe3243b44a62cb656c73274f8ac">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::ensureType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a46dea09a63e3d20ae77323412310fcb1">expandBounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a566049e9c903d4e0067b8557d49c7d62">foldICmpWithLowBitMaskedVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac4c9e71398fa689dc9c87e16cf270e36">LowerBuildVectorOfFPExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a583aa87134828d834990a0ca12f8f44b">LowerBuildVectorOfFPTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/guardutils-cpp/#af7534ff6924d87e8750acd2d12a707c3">parseCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a1ee2ba5e7987e0dc7330c99ad35cdf88">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPPCtrlSel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0a920d221f6e65925d8b683836cebd03">reassociateCSELOperandsForCSE</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ad87f4b76b6846d029880d6b9012a7e69">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceInst</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a450c2f1a2d1c2e08bf66297247baa964">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceValue</a>.</p>

</div>
</div>

### CheckOrNull {#a2fee20ad578f1c6d3061e37925fe7275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CheckOrNull(C, ...)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>)) {                                                                \
      reportFailure(__VA_ARGS__);                                              \
      return {};                                                               \
    }                                                                          \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (false)
</div>
</dd>
</dl>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/genericconvergenceverifierimpl-h">GenericConvergenceVerifierImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
