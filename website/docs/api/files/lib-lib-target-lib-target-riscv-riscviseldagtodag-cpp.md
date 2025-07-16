---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RISCVISelDAGToDAG.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-h">RISCVISelDAGToDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">MCTargetDesc/RISCVBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-h">MCTargetDesc/RISCVMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmatint-h">MCTargetDesc/RISCVMatInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-h">RISCVISelLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-h">RISCVInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "llvm/IR/IntrinsicsRISCV.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">llvm/Support/Alignment.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "RISCVGenSearchableTables.inc"
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscv">RISCV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a41924e51804fff4d3c8394d3643541">selectImmSeq</a> (SelectionDAG *CurDAG, const SDLoc &amp;DL, const MVT VT, RISCVMatInt::InstSeq &amp;Seq)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b20fa727cb3be2d7338de943bc81490">selectImm</a> (SelectionDAG *CurDAG, const SDLoc &amp;DL, const MVT VT, int64_t Imm, const RISCVSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d21b6fd19243e696e086f5f4c5717f5">getSegInstNF</a> (unsigned Intrinsic)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bdacd126c6e2d17f0f5a195043c9aa3">selectConstantAddr</a> (SelectionDAG *CurDAG, const SDLoc &amp;DL, const MVT VT, const RISCVSubtarget *Subtarget, SDValue Addr, SDValue &amp;Base, SDValue &amp;Offset, bool IsPrefetch=false, bool IsRV32Zdinx=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641563566f08db6108848bf61de2f323">isWorthFoldingAdd</a> (SDValue Add)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadd8c5bb4ccd3134cdde19afc01eb291">vectorPseudoHasAllNBitUsers</a> (SDNode *User, unsigned UserOpNo, unsigned Bits, const TargetInstrInfo *TII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0bac4d8677c9b1ee6a8626a4eca85d0">findVSplat</a> (SDValue N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4864665b5082511864fa8b4ad9ea5f9">selectVSplatImmHelper</a> (SDValue N, SDValue &amp;SplatVal, SelectionDAG &amp;DAG, const RISCVSubtarget &amp;Subtarget, std::function&lt; bool(int64_t)&gt; ValidateImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2caf47c7fb0d8972d9c1f261beaf289">getMaskSetter</a> (SDValue MaskOp, SDValue GlueOp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cbc84894a200075ee84886cd3fa6549">usesAllOnesMask</a> (SDValue MaskOp, SDValue GlueOp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31ec69d2a56ad55ca97695260fd53ad7">usesAllOnesMask</a> (SDNode *N, unsigned MaskOpIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0bac69f0111d50105ccc5767454d64">isImplicitDef</a> (SDValue V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd31764bfbff74f9e25afb3878a1901b">IsVMerge</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf32787dafcb03442abba83b64b3b69">UsePseudoMovImm</a>("riscv-use-rematerializable-movimm", cl::Hidden, cl::desc("Use a rematerializable pseudoinstruction for 2 instruction " "constant materialization"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"riscv-isel"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>&nbsp;&nbsp;&nbsp;"RISC-V DAG-&gt;DAG <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Selection"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22dd03b1793fef85cb99659939dacf2c">GET_RISCVVSSEGTable_IMPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc5bff4a079dc48cdb99912faaf2bf7">GET_RISCVVLSEGTable_IMPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f238a60203ccf856cacbd832a854c89">GET_RISCVVLXSEGTable_IMPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30339dfff5cc759aa4e235a18b666e42">GET_RISCVVSXSEGTable_IMPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73840dfa43f7480d4da2e6bb859ee039">GET_RISCVVLETable_IMPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa04676ee749a6606c9accce8627a85bd">GET_RISCVVSETable_IMPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad54187d3429611e00f5b95d067fe4df8">GET_RISCVVLXTable_IMPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7123b12df93e95532ae6dd395b2be5b3">GET_RISCVVSXTable_IMPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d5e5c088a7035d6fd31f7d09e3a4b8">INST_NF_CASE</a>(NAME, NF)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5084ee9c9f6350a3f09429b8ea4c44f">INST_NF_CASE_MASK</a>(NAME, NF)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a012024c987cfaba0309e4604697693cc">INST_NF_CASE_FF</a>(NAME, NF)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42fedf22dac2af02c900b2bf17c38cba">INST_NF_CASE_FF_MASK</a>(NAME, NF)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99bd0fc1d9a81cefba8f1e9e1851b5b">INST_ALL_NF_CASE_BASE</a>(MACRO_NAME, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeab45015eb0b68505cc573b501b0cd5e">INST_ALL_NF_CASE</a>(NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ad323055d2f11bee3ffb9e2bc8aa6b">INST_ALL_NF_CASE_WITH_FF</a>(NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb63ad110da07deeee196ee737999d1">CASE_VMSLT_OPCODES</a>(lmulenum, suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f6c404da0aa484a98ff96ec0304125">CASE_VMNAND_VMSET_OPCODES</a>(lmulenum, suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add601aa316e9e588398fe4d028bb3f2c">CASE_VMSLT_OPCODES</a>(lmulenum, suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ba64312e06ecc1161e8da80e17fc4f5">CASE_VMXOR_VMANDN_VMOR_OPCODES</a>(lmulenum, suffix)&nbsp;&nbsp;&nbsp;...</td>
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

### findVSplat() {#ae0bac4d8677c9b1ee6a8626a4eca85d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue findVSplat (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 3514 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a55a5f5a5eb10f4ca81928a4cee11ab52">llvm::RISCVISD::VMV_S_X_VL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvisd/#ab68e2d65ea9915ffaac8334a3b8bf882a127afe58529ef366a343a51786dcc3d4">llvm::RISCVISD::VMV_V_X_VL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a81db6a638b456bb26ffa634a27e52798">llvm::RISCVDAGToDAGISel::selectVSplat</a> and <a href="#ae4864665b5082511864fa8b4ad9ea5f9">selectVSplatImmHelper</a>.</p>

</div>
</div>

### getMaskSetter() {#ae2caf47c7fb0d8972d9c1f261beaf289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue getMaskSetter (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> MaskOp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> GlueOp)</td>
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



<p>Definition at line 3745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93bc27ca4d9e211c54b0d9efb660f080">llvm::ISD::CopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f96a3399d86d6f136aaa121de4217a3">llvm::SDNode::getMachineOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1223d6e9a7dfb6e51299b894beccc679">llvm::SDNode::isMachineOpcode</a>.</p>


<p>Referenced by <a href="#a8cbc84894a200075ee84886cd3fa6549">usesAllOnesMask</a>.</p>

</div>
</div>

### getSegInstNF() {#a9d21b6fd19243e696e086f5f4c5717f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getSegInstNF (unsigned Intrinsic)</td>
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



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#aeab45015eb0b68505cc573b501b0cd5e">INST_ALL_NF_CASE</a>, <a href="#ab1ad323055d2f11bee3ffb9e2bc8aa6b">INST_ALL_NF_CASE_WITH_FF</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>.</p>

</div>
</div>

### isImplicitDef() {#a6b0bac69f0111d50105ccc5767454d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isImplicitDef (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> V)</td>
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



<p>Definition at line 3799 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a6b0bac69f0111d50105ccc5767454d64">isImplicitDef</a>.</p>


<p>Referenced by <a href="#a6b0bac69f0111d50105ccc5767454d64">isImplicitDef</a>.</p>

</div>
</div>

### IsVMerge() {#afd31764bfbff74f9e25afb3878a1901b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsVMerge (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 3870 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a90a55d922eac310187ebfcf9008525e5">llvm::RISCV::getRVVMCOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isWorthFoldingAdd() {#a641563566f08db6108848bf61de2f323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isWorthFoldingAdd (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Add)</td>
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



<p>Definition at line 2593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">llvm::ISD::ATOMIC_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">llvm::ISD::ATOMIC_STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a030eaafa553ffa2a996481cff1e7aaa8">llvm::RISCVDAGToDAGISel::SelectAddrRegImm</a>.</p>

</div>
</div>

### selectConstantAddr() {#a2bdacd126c6e2d17f0f5a195043c9aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool selectConstantAddr (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * CurDAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> * Subtarget, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Offset, bool IsPrefetch=false, bool IsRV32Zdinx=false)</td>
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



<p>Definition at line 2535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a163e06959afb15ae88efade9bb975e27">llvm::RISCVMatInt::generateInstSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c04c72abd24de2572a03ef686a36dd6">llvm::SelectionDAG::getMachineNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#afd9fbb2a5a666589b2843c496f3ae479">llvm::RISCVSubtarget::is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="#a6a41924e51804fff4d3c8394d3643541">selectImmSeq</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a030eaafa553ffa2a996481cff1e7aaa8">llvm::RISCVDAGToDAGISel::SelectAddrRegImm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a185b481cf26bfc5e6ed78a7d07519301">llvm::RISCVDAGToDAGISel::SelectAddrRegImmLsb00000</a>.</p>

</div>
</div>

### selectImm() {#a2b20fa727cb3be2d7338de943bc81490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue selectImm (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * CurDAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, int64_t Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a163e06959afb15ae88efade9bb975e27">llvm::RISCVMatInt::generateInstSeq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a6eff34ee491c7f6124b3f21768d8d79f">llvm::RISCVMatInt::generateTwoRegInstSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c04c72abd24de2572a03ef686a36dd6">llvm::SelectionDAG::getMachineNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="#a6a41924e51804fff4d3c8394d3643541">selectImmSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#adcf32787dafcb03442abba83b64b3b69">UsePseudoMovImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a6ed9eee21fb8cd7cc428eeafae6b28bc">llvm::RISCVDAGToDAGISel::selectInvLogicImm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a8414362458bfc0acef16b0440665faa1">llvm::RISCVDAGToDAGISel::selectScalarFPAsInt</a>.</p>

</div>
</div>

### selectImmSeq() {#a6a41924e51804fff4d3c8394d3643541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue selectImmSeq (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * CurDAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a6fa6ca43d5a47fb0edf6acd28aa85d87">RISCVMatInt::InstSeq</a> &amp; Seq)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c04c72abd24de2572a03ef686a36dd6">llvm::SelectionDAG::getMachineNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a3c9bceaea514f7c01e87dcb184d3c972a3b5b9d77cc1b7c08af3a3cdba0c6736c">llvm::RISCVMatInt::Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a3c9bceaea514f7c01e87dcb184d3c972affd2828f91e95f9731181bb5b8e4f9ac">llvm::RISCVMatInt::RegImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a3c9bceaea514f7c01e87dcb184d3c972ae68f4b6898bb293ac94508474ccd7265">llvm::RISCVMatInt::RegReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a3c9bceaea514f7c01e87dcb184d3c972ac5bc33378acb23e672b1eaf99faa99a0">llvm::RISCVMatInt::RegX0</a>.</p>


<p>Referenced by <a href="#a2bdacd126c6e2d17f0f5a195043c9aa3">selectConstantAddr</a> and <a href="#a2b20fa727cb3be2d7338de943bc81490">selectImm</a>.</p>

</div>
</div>

### selectVSplatImmHelper() {#ae4864665b5082511864fa8b4ad9ea5f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool selectVSplatImmHelper (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; SplatVal, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; bool(int64_t)&gt; ValidateImm)</td>
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



<p>Definition at line 3538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae0bac4d8677c9b1ee6a8626a4eca85d0">findVSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7fc96403de39ca28a30bf2a4a38b113f">llvm::SelectionDAG::getSignedTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a657dd2086f68037531f461853480fcf7">llvm::RISCVSubtarget::getXLenVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a60c150f4b46cf5dc8dd1af9653ddde43">llvm::RISCVDAGToDAGISel::selectVSplatSimm5</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#ab1135c7a8ff766bc0ec72c55e1049d87">llvm::RISCVDAGToDAGISel::selectVSplatSimm5Plus1</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#abfe913dce113bf8f5d20f5e1fe1966b2">llvm::RISCVDAGToDAGISel::selectVSplatSimm5Plus1NonZero</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#aff942d6f8939b769939917efd741bde5">llvm::RISCVDAGToDAGISel::selectVSplatUimm</a>.</p>

</div>
</div>

### usesAllOnesMask() {#a8cbc84894a200075ee84886cd3fa6549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool usesAllOnesMask (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> MaskOp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> GlueOp)</td>
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



<p>Definition at line 3773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#adef073885c881f48920ff6a8b4b36163">llvm::SDValue::getMachineOpcode</a>, <a href="#ae2caf47c7fb0d8972d9c1f261beaf289">getMaskSetter</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1223d6e9a7dfb6e51299b894beccc679">llvm::SDNode::isMachineOpcode</a>.</p>


<p>Referenced by <a href="#a31ec69d2a56ad55ca97695260fd53ad7">usesAllOnesMask</a>.</p>

</div>
</div>

### usesAllOnesMask() {#a31ec69d2a56ad55ca97695260fd53ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool usesAllOnesMask (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned MaskOpIdx)</td>
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



<p>Definition at line 3794 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a8cbc84894a200075ee84886cd3fa6549">usesAllOnesMask</a>.</p>

</div>
</div>

### vectorPseudoHasAllNBitUsers() {#aadd8c5bb4ccd3134cdde19afc01eb291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool vectorPseudoHasAllNBitUsers (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * User, unsigned UserOpNo, unsigned Bits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
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



<p>Definition at line 3263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a90a55d922eac310187ebfcf9008525e5">llvm::RISCV::getRVVMCOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a5295e5735dc2ca5bed83052effb51336">llvm::RISCV::getVectorLowDemandedScalarBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#afc858f8e35813be95df97504afd771ef">llvm::RISCVII::hasSEWOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ad330ee2b7583cf1bf0a79f69c23ce6fe">llvm::RISCVII::hasVecPolicyOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a81c11c8178c6df7f55ef0557daa54765">llvm::RISCVII::hasVLOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a0c47c47ebffcc56ccf426575cc7688f1">llvm::RISCVDAGToDAGISel::hasAllNBitUsers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### UsePseudoMovImm {#adcf32787dafcb03442abba83b64b3b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UsePseudoMovImm("riscv-use-rematerializable-movimm", cl::Hidden, cl::desc("Use a rematerializable pseudoinstruction for 2 instruction " "constant materialization"), cl::init(false))</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a2b20fa727cb3be2d7338de943bc81490">selectImm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CASE\_VMNAND\_VMSET\_OPCODES {#a59f6c404da0aa484a98ff96ec0304125}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMNAND_VMSET_OPCODES(lmulenum, suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case RISCVII::VLMUL::lmulenum:                                               \
    VMNANDOpcode = RISCV::PseudoVMNAND_MM_##suffix;                            \
    VMSetOpcode = RISCV::PseudoVMSET_M_##suffix;                               \
    break;
</div>
</dd>
</dl>

<p>Definition at line 1687 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>.</p>

</div>
</div>

### CASE\_VMSLT\_OPCODES {#abbb63ad110da07deeee196ee737999d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMSLT_OPCODES(lmulenum, suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case RISCVII::VLMUL::lmulenum:                                               \
    VMSLTOpcode = IsUnsigned ? RISCV::PseudoVMSLTU_VX_##suffix                 \
                             : RISCV::PseudoVMSLT_VX_##suffix;                 \
    VMSGTOpcode = IsUnsigned ? RISCV::PseudoVMSGTU_VX_##suffix                 \
                             : RISCV::PseudoVMSGT_VX_##suffix;                 \
    break;
</div>
</dd>
</dl>

<p>Definition at line 1667 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>.</p>

</div>
</div>

### CASE\_VMSLT\_OPCODES {#add601aa316e9e588398fe4d028bb3f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMSLT_OPCODES(lmulenum, suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case RISCVII::VLMUL::lmulenum:                                               \
    VMSLTOpcode = IsUnsigned ? RISCV::PseudoVMSLTU_VX_##suffix                 \
                             : RISCV::PseudoVMSLT_VX_##suffix;                 \
    VMSLTMaskOpcode = IsUnsigned ? RISCV::PseudoVMSLTU_VX_##suffix##_MASK      \
                                 : RISCV::PseudoVMSLT_VX_##suffix##_MASK;      \
    VMSGTMaskOpcode = IsUnsigned ? RISCV::PseudoVMSGTU_VX_##suffix##_MASK      \
                                 : RISCV::PseudoVMSGT_VX_##suffix##_MASK;      \
    break;
</div>
</dd>
</dl>

<p>Definition at line 1763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### CASE\_VMXOR\_VMANDN\_VMOR\_OPCODES {#a8ba64312e06ecc1161e8da80e17fc4f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMXOR_VMANDN_VMOR_OPCODES(lmulenum, suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case RISCVII::VLMUL::lmulenum:                                               \
    VMXOROpcode = RISCV::PseudoVMXOR_MM_##suffix;                              \
    VMANDNOpcode = RISCV::PseudoVMANDN_MM_##suffix;                            \
    VMOROpcode = RISCV::PseudoVMOR_MM_##suffix;                                \
    break;
</div>
</dd>
</dl>

<p>Definition at line 1785 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"riscv-isel"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### GET\_RISCVVLETable\_IMPL {#a73840dfa43f7480d4da2e6bb859ee039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVVLETable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### GET\_RISCVVLSEGTable\_IMPL {#a4bc5bff4a079dc48cdb99912faaf2bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVVLSEGTable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### GET\_RISCVVLXSEGTable\_IMPL {#a4f238a60203ccf856cacbd832a854c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVVLXSEGTable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### GET\_RISCVVLXTable\_IMPL {#ad54187d3429611e00f5b95d067fe4df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVVLXTable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### GET\_RISCVVSETable\_IMPL {#aa04676ee749a6606c9accce8627a85bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVVSETable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### GET\_RISCVVSSEGTable\_IMPL {#a22dd03b1793fef85cb99659939dacf2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVVSSEGTable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### GET\_RISCVVSXSEGTable\_IMPL {#a30339dfff5cc759aa4e235a18b666e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVVSXSEGTable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### GET\_RISCVVSXTable\_IMPL {#a7123b12df93e95532ae6dd395b2be5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVVSXTable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### INST\_ALL\_NF\_CASE {#aeab45015eb0b68505cc573b501b0cd5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INST_ALL_NF_CASE(NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#ab99bd0fc1d9a81cefba8f1e9e1851b5b">INST_ALL_NF_CASE_BASE</a>(<a href="#a05d5e5c088a7035d6fd31f7d09e3a4b8">INST_NF_CASE</a>, NAME)                                    \
  <a href="#ab99bd0fc1d9a81cefba8f1e9e1851b5b">INST_ALL_NF_CASE_BASE</a>(<a href="#ac5084ee9c9f6350a3f09429b8ea4c44f">INST_NF_CASE_MASK</a>, NAME)
</div>
</dd>
</dl>

<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a9d21b6fd19243e696e086f5f4c5717f5">getSegInstNF</a>.</p>

</div>
</div>

### INST\_ALL\_NF\_CASE\_BASE {#ab99bd0fc1d9a81cefba8f1e9e1851b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INST_ALL_NF_CASE_BASE(MACRO_NAME, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  MACRO_NAME(NAME, 2)                                                          \
  MACRO_NAME(NAME, 3)                                                          \
  MACRO_NAME(NAME, 4)                                                          \
  MACRO_NAME(NAME, 5)                                                          \
  MACRO_NAME(NAME, 6)                                                          \
  MACRO_NAME(NAME, 7)                                                          \
  MACRO_NAME(NAME, 8)
</div>
</dd>
</dl>

<p>Definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### INST\_ALL\_NF\_CASE\_WITH\_FF {#ab1ad323055d2f11bee3ffb9e2bc8aa6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INST_ALL_NF_CASE_WITH_FF(NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#aeab45015eb0b68505cc573b501b0cd5e">INST_ALL_NF_CASE</a>(NAME)                                                       \
  <a href="#ab99bd0fc1d9a81cefba8f1e9e1851b5b">INST_ALL_NF_CASE_BASE</a>(<a href="#a012024c987cfaba0309e4604697693cc">INST_NF_CASE_FF</a>, NAME)                                 \
  <a href="#ab99bd0fc1d9a81cefba8f1e9e1851b5b">INST_ALL_NF_CASE_BASE</a>(<a href="#a42fedf22dac2af02c900b2bf17c38cba">INST_NF_CASE_FF_MASK</a>, NAME)
</div>
</dd>
</dl>

<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a9d21b6fd19243e696e086f5f4c5717f5">getSegInstNF</a>.</p>

</div>
</div>

### INST\_NF\_CASE {#a05d5e5c088a7035d6fd31f7d09e3a4b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INST_NF_CASE(NAME, NF)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Intrinsic::riscv_##NAME##NF:                                            \
    return NF;
</div>
</dd>
</dl>

<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### INST\_NF\_CASE\_FF {#a012024c987cfaba0309e4604697693cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INST_NF_CASE_FF(NAME, NF)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Intrinsic::riscv_##NAME##NF##ff:                                        \
    return NF;
</div>
</dd>
</dl>

<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### INST\_NF\_CASE\_FF\_MASK {#a42fedf22dac2af02c900b2bf17c38cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INST_NF_CASE_FF_MASK(NAME, NF)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Intrinsic::riscv_##NAME##NF##ff_mask:                                   \
    return NF;
</div>
</dd>
</dl>

<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### INST\_NF\_CASE\_MASK {#ac5084ee9c9f6350a3f09429b8ea4c44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INST_NF_CASE_MASK(NAME, NF)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Intrinsic::riscv_##NAME##NF##_mask:                                     \
    return NF;
</div>
</dd>
</dl>

<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### PASS\_NAME {#acf9235cddac26ff3f81e8c56849bcaac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PASS_NAME&nbsp;&nbsp;&nbsp;"RISC-V DAG-&gt;DAG <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Selection"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp">RISCVISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
