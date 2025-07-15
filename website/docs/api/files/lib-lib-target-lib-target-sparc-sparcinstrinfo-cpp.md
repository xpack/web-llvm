---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SparcInstrInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-h">SparcInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparc-h">Sparc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmachinefunctioninfo-h">SparcMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcsubtarget-h">SparcSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "SparcGenInstrInfo.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9">SPCC::CondCodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37f317c48074b11fa501731852794c78">GetOppositeBranchCondition</a> (SPCC::CondCodes CC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc0df073e34014a2a8ad7f1919202d1">isUncondBranchOpcode</a> (int Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69c1954255ef4e2fb61894a76bed4a91">isI32CondBranchOpcode</a> (int Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3d106cae342c340b4da203093703cd0">isI64CondBranchOpcode</a> (int Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b54a8ba52f0bc16e948f2869e4f43d">isRegCondBranchOpcode</a> (int Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f962aa45f98e8a4007edec1998944b">isFCondBranchOpcode</a> (int Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c6eb198e4a6fb0f4eb4dc6341f5c4ad">isCondBranchOpcode</a> (int Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f8437408967fd6151fbedeb1fe6ee9">isIndirectBranchOpcode</a> (int Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a> (MachineInstr *LastInst, MachineBasicBlock *&amp;Target, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab606858f4b93e1e38af34241d0aa49e">BPccDisplacementBits</a>("sparc-bpcc-offset-bits", cl::Hidden, cl::init(19), cl::desc("Restrict range of BPcc/FBPfcc instructions (DEBUG)"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d37e5c3a001eaedd5e2747980f3fe9">BPrDisplacementBits</a>("sparc-bpr-offset-bits", cl::Hidden, cl::init(16), cl::desc("Restrict range of BPr instructions (DEBUG)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d99008fb7e5cdc4774786d0743a2c4f">GET_INSTRINFO_CTOR_DTOR</a></td>
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

### GetOppositeBranchCondition() {#a37f317c48074b11fa501731852794c78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPCC::CondCodes GetOppositeBranchCondition (<a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9">SPCC::CondCodes</a> CC)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a5e790cf356e7b5e064dd6ed341777ca1">llvm::SPCC::CPCC_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a49266215e6fa6d513faca31d468e550e">llvm::SPCC::CPCC_01</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a63050d6ee6bb9f16b534a27b86aed7bd">llvm::SPCC::CPCC_012</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a063209963122462fea6e9e782164a75a">llvm::SPCC::CPCC_013</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a86499919519df7b1c225f553d0ad8be7">llvm::SPCC::CPCC_02</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a786c9a95f3a7dfb962b7d9dab20bade3">llvm::SPCC::CPCC_023</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a03f335ab66f5ad6aff578dcc03db5a7e">llvm::SPCC::CPCC_03</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a5775a8b0a45b23552f61cc8230aa2a94">llvm::SPCC::CPCC_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a4998088f96b6dd907e3978f310514eec">llvm::SPCC::CPCC_12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a2e4791706cc46a23012847a51144b29f">llvm::SPCC::CPCC_123</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a78723f1fc56f0d30c56896fd36c67608">llvm::SPCC::CPCC_13</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a6c94e6e6f8a02c568f4e366929e71610">llvm::SPCC::CPCC_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a34865013450a9f70333f80e8026ff0c5">llvm::SPCC::CPCC_23</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ace7f6169293b587e4b19bfbddd78afe1">llvm::SPCC::CPCC_3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a5b7c965f084c605f82332728ea6fd695">llvm::SPCC::CPCC_A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9aed2a50a37010f4423ac39e3c9d70e0e9">llvm::SPCC::CPCC_N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a76a3c4ea83b85ce279ada63a0fe326ed">llvm::SPCC::FCC_A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a80f16f53e18c59ae3681b303cda7a308">llvm::SPCC::FCC_E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9aed8356273fdf3a0487c872cb3d085542">llvm::SPCC::FCC_G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ac202b4c5d9c55d73489b315c7e393836">llvm::SPCC::FCC_GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a965bae47c4fccd3973ecbf040869ff7f">llvm::SPCC::FCC_L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a607f8b24c191bb766a34c2eb1bfb63c4">llvm::SPCC::FCC_LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a53356323fdd97606927cec5c20cd6215">llvm::SPCC::FCC_LG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9afbc1ae5578e45f8001bbab0162a6fb19">llvm::SPCC::FCC_N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a488d679dc60c1f44701c9f0af8aa5d2c">llvm::SPCC::FCC_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ab6d11f42acc70a53b6bf5d36feb0f6e8">llvm::SPCC::FCC_O</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a6820b0c58a07365f1341ca30d64bd218">llvm::SPCC::FCC_U</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9abaea969a35799493146fdd78c36dfa4c">llvm::SPCC::FCC_UE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a2106f4522bd06f6daad2a8e8769a6270">llvm::SPCC::FCC_UG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ad38b12aa07c4354222b6b9422bbb90d6">llvm::SPCC::FCC_UGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9afbb30e35da42c9cac83731fe3709387b">llvm::SPCC::FCC_UL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a0823c4f36acc84808ba44f1f92fe58f2">llvm::SPCC::FCC_ULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ac6bf2d66149e547cd449757df4f610de">llvm::SPCC::ICC_A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9add11869e4071f1b4587c8f1a7f1f6191">llvm::SPCC::ICC_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a52da0658a7ccad50715ed99701281c5f">llvm::SPCC::ICC_CS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ac1dc27bfc24df99cd29246ec54419659">llvm::SPCC::ICC_E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a2e9b359e236c3f89d1cd1646419a0438">llvm::SPCC::ICC_G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a7b7a8837c5c902680ac8aec565079596">llvm::SPCC::ICC_GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9aad6b4c4abc1731149339bdcac755ee87">llvm::SPCC::ICC_GU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a3f6ef8aede46014a36966dc084d81087">llvm::SPCC::ICC_L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a639506be5285099011780c4a03c9b371">llvm::SPCC::ICC_LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a58fd730a813b831ee05050e63d30405c">llvm::SPCC::ICC_LEU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a22b9903f646ef973374e5d773a097546">llvm::SPCC::ICC_N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ab9a7855b45288146df6d3ab3e321c43b">llvm::SPCC::ICC_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9afcf61d074d6039adac588209f5d9d6ad">llvm::SPCC::ICC_NEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a1c26d5c90286fc0f30cb668a7a644ebc">llvm::SPCC::ICC_POS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9adc2b09c7d0c6869a1f05262717986737">llvm::SPCC::ICC_VC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a5553287ec99a6227069fca2f37a5b34b">llvm::SPCC::ICC_VS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a414e31a34535038b592022a494daeb6e">llvm::SPCC::REG_BEGIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9aea327767fe2941e4f37bfb726356b912">llvm::SPCC::REG_GEZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a3e94d4488061aab685d2595ed12acfba">llvm::SPCC::REG_GZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a3150ec423606b8a9d19bc6ecd5bdb396">llvm::SPCC::REG_LEZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9a8fb5d5567021136f9b9822819896ce07">llvm::SPCC::REG_LZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9abd1ee1cd883798adea0e15fd9d4805b0">llvm::SPCC::REG_NZ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spcc/#ab817ca090b73e64dc6c2a7dd705edda9ada70f03e921ff7893ac2ae0c4aa62fd3">llvm::SPCC::REG_Z</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a5fbf08fc2002106c8e39caa9c2c84cd8">llvm::M68kInstrInfo::AnalyzeBranchImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a6e398bb4a8389b3aefa2e57b9403c0b2">llvm::SparcInstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ac2dfd681e70905459fb735562be28b8c">llvm::VEInstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a9d0e9be1df5eea2fce3507a03ec42c79">llvm::X86InstrInfo::reverseBranchCondition</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a3f83e5a4514870f408c6080dda5f804c">llvm::XCoreInstrInfo::reverseBranchCondition</a>.</p>

</div>
</div>

### isCondBranchOpcode() {#a5c6eb198e4a6fb0f4eb4dc6341f5c4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCondBranchOpcode (int Opc)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>


<p>References <a href="#a16f962aa45f98e8a4007edec1998944b">isFCondBranchOpcode</a>, <a href="#a69c1954255ef4e2fb61894a76bed4a91">isI32CondBranchOpcode</a>, <a href="#ab3d106cae342c340b4da203093703cd0">isI64CondBranchOpcode</a> and <a href="#a34b54a8ba52f0bc16e948f2869e4f43d">isRegCondBranchOpcode</a>.</p>

</div>
</div>

### isFCondBranchOpcode() {#a16f962aa45f98e8a4007edec1998944b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFCondBranchOpcode (int Opc)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#a5c6eb198e4a6fb0f4eb4dc6341f5c4ad">isCondBranchOpcode</a>.</p>

</div>
</div>

### isI32CondBranchOpcode() {#a69c1954255ef4e2fb61894a76bed4a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isI32CondBranchOpcode (int Opc)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#a5c6eb198e4a6fb0f4eb4dc6341f5c4ad">isCondBranchOpcode</a>.</p>

</div>
</div>

### isI64CondBranchOpcode() {#ab3d106cae342c340b4da203093703cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isI64CondBranchOpcode (int Opc)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#a5c6eb198e4a6fb0f4eb4dc6341f5c4ad">isCondBranchOpcode</a>.</p>

</div>
</div>

### isIndirectBranchOpcode() {#a68f8437408967fd6151fbedeb1fe6ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIndirectBranchOpcode (int Opc)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>

</div>
</div>

### isRegCondBranchOpcode() {#a34b54a8ba52f0bc16e948f2869e4f43d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRegCondBranchOpcode (int Opc)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#afbb00c84e6a7ad45d3b6b3839ee51e6c">llvm::SparcInstrInfo::insertBranch</a>, <a href="#a5c6eb198e4a6fb0f4eb4dc6341f5c4ad">isCondBranchOpcode</a> and <a href="#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>.</p>

</div>
</div>

### isUncondBranchOpcode() {#a4cc0df073e34014a2a8ad7f1919202d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isUncondBranchOpcode (int Opc)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>

</div>
</div>

### parseCondBranch() {#aae34e9ed9446266fe2dcc421cc67093f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseCondBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * LastInst, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; Target, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a34b54a8ba52f0bc16e948f2869e4f43d">isRegCondBranchOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BPccDisplacementBits {#aab606858f4b93e1e38af34241d0aa49e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; BPccDisplacementBits("sparc-bpcc-offset-bits", cl::Hidden, cl::init(19), cl::desc("Restrict range of BPcc/FBPfcc instructions (DEBUG)"))</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a535896b8f0e27eabd1a545bc78ed5cce">llvm::SparcInstrInfo::isBranchOffsetInRange</a>.</p>

</div>
</div>

### BPrDisplacementBits {#a56d37e5c3a001eaedd5e2747980f3fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; BPrDisplacementBits("sparc-bpr-offset-bits", cl::Hidden, cl::init(16), cl::desc("Restrict range of BPr instructions (DEBUG)"))</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a535896b8f0e27eabd1a545bc78ed5cce">llvm::SparcInstrInfo::isBranchOffsetInRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### GET\_INSTRINFO\_CTOR\_DTOR {#a5d99008fb7e5cdc4774786d0743a2c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_CTOR_DTOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp">SparcInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
