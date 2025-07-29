---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/riscvop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `RISCVOp` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::RISCVOp { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandType : unsigned { <a href="#a197c4d1114fb917fac0dc1744172f9ce">...</a> }</td>
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

## Enumerations

### OperandType {#a197c4d1114fb917fac0dc1744172f9ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RISCVOp::OperandType : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_FIRST_RISCV_IMM<a id="a197c4d1114fb917fac0dc1744172f9cea3ff6efde85807af813317be766ea9551"></a></td>
<td class="doxyEnumItemDescription"> (= MCOI::OPERAND_FIRST_TARGET)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM1<a id="a197c4d1114fb917fac0dc1744172f9cea1562292e5add692ff0829e678f739865"></a></td>
<td class="doxyEnumItemDescription"> (= OPERAND_FIRST_RISCV_IMM)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM2<a id="a197c4d1114fb917fac0dc1744172f9ceafd4cee3ab8669d61fc71d6a60a1680b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM2_LSB0<a id="a197c4d1114fb917fac0dc1744172f9cea66542584f2145c86bf80a0887c5cdd63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM3<a id="a197c4d1114fb917fac0dc1744172f9cea11e90dac384d2eb23da2b939adf366c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM4<a id="a197c4d1114fb917fac0dc1744172f9cea186948149907e484e864ef25dc283fac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM5<a id="a197c4d1114fb917fac0dc1744172f9ceaec2550ca566a41a44997005f7bf156cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM5_NONZERO<a id="a197c4d1114fb917fac0dc1744172f9cea518a06314bf2893ab4fcd9c35bef0f8f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM5_GT3<a id="a197c4d1114fb917fac0dc1744172f9ceadfb1b04138fa2fe68b1db24ac76abba1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM5_LSB0<a id="a197c4d1114fb917fac0dc1744172f9cea1cac2933ce03fe1100daf84714858546"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM6<a id="a197c4d1114fb917fac0dc1744172f9cea47314ce23772996818e93ebceb19f7df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM6_LSB0<a id="a197c4d1114fb917fac0dc1744172f9ceaeba5620b9c179151a47c322685980be4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM7<a id="a197c4d1114fb917fac0dc1744172f9ceafa9486c71079df186dc8826092a1361d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM7_LSB00<a id="a197c4d1114fb917fac0dc1744172f9cea7d72d631d00b79d9466807ace7eee72c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM7_LSB000<a id="a197c4d1114fb917fac0dc1744172f9cea74e10dea9b29a27cad711851249bd0c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM8_LSB00<a id="a197c4d1114fb917fac0dc1744172f9cead65a6374741b77c79ae7e8c2ea2652bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM8<a id="a197c4d1114fb917fac0dc1744172f9cea345b6ba3a765c7d9737263c349d5ab46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM8_LSB000<a id="a197c4d1114fb917fac0dc1744172f9cea14956341af1f1d58c7b32adb2b600f6e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM8_GE32<a id="a197c4d1114fb917fac0dc1744172f9cea8500b92a361637d8a0455f28733e7b9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM9_LSB000<a id="a197c4d1114fb917fac0dc1744172f9cea8268729e5603e7325c18871475c9b90f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM10<a id="a197c4d1114fb917fac0dc1744172f9cea90210b80cd1e0743903d2611bdae27e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM10_LSB00_NONZERO<a id="a197c4d1114fb917fac0dc1744172f9ceaa624cbaacf34f8da09c2a497c23feb02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM11<a id="a197c4d1114fb917fac0dc1744172f9cea6c5215be7e9cc62025942ca97d52f935"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM12<a id="a197c4d1114fb917fac0dc1744172f9ceab84a7ee66834e108f7aff7ed264a3653"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM16<a id="a197c4d1114fb917fac0dc1744172f9ceac18a38f00b113f6caa2827096aad7895"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM20<a id="a197c4d1114fb917fac0dc1744172f9cea466ba6f1df284bcaacfcc8a29539689c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMMLOG2XLEN<a id="a197c4d1114fb917fac0dc1744172f9cea73a3c2d12a4837c231484f7ec1abbe98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMMLOG2XLEN_NONZERO<a id="a197c4d1114fb917fac0dc1744172f9cea0457b33205b9cb5eac17e0e538558605"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM32<a id="a197c4d1114fb917fac0dc1744172f9cea32635550351d896980542b709cf7df56"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM48<a id="a197c4d1114fb917fac0dc1744172f9cea49ca493b2f395965856b78a646b0c834"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_UIMM64<a id="a197c4d1114fb917fac0dc1744172f9ceaae4e305c6ddf75f7c8af3a70e162db1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_ZERO<a id="a197c4d1114fb917fac0dc1744172f9cea4d00abd02a7dc4f859c36e6614bd8814"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SIMM5<a id="a197c4d1114fb917fac0dc1744172f9cea235e6241367a2c7a2538a36337b33092"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SIMM5_PLUS1<a id="a197c4d1114fb917fac0dc1744172f9cea0d6b5afa2f1bf4f31f350625d3e06a7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SIMM6<a id="a197c4d1114fb917fac0dc1744172f9cea8afda83225269c68cc8d7c3bb17ff111"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SIMM6_NONZERO<a id="a197c4d1114fb917fac0dc1744172f9cea584709273720399fb300bf3db40d586d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SIMM10_LSB0000_NONZERO<a id="a197c4d1114fb917fac0dc1744172f9cead2f4fdc4a016edf2e5703c5e4c57c689"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SIMM12<a id="a197c4d1114fb917fac0dc1744172f9cead70e59382ef7ae79d423e0754aa32eae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SIMM12_LSB00000<a id="a197c4d1114fb917fac0dc1744172f9cea107c7db3a243b5d8cc1a31f45b5cd411"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SIMM26<a id="a197c4d1114fb917fac0dc1744172f9cea34efacaf451c83252053ce090bf8d5df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_CLUI_IMM<a id="a197c4d1114fb917fac0dc1744172f9cea4db158e80f8710efed328918005bc35b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_VTYPEI10<a id="a197c4d1114fb917fac0dc1744172f9ceae4a409e70dfe1084d180a2b24d778d31"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_VTYPEI11<a id="a197c4d1114fb917fac0dc1744172f9cea13db1806d50017277068356b507e4589"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_RVKRNUM<a id="a197c4d1114fb917fac0dc1744172f9cea049fc54505396e7452725a30c8f57e8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_RVKRNUM_0_7<a id="a197c4d1114fb917fac0dc1744172f9ceac3174d7c3cf71e17e1f54380d09d7bcc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_RVKRNUM_1_10<a id="a197c4d1114fb917fac0dc1744172f9ceab7fbc78f118359b4405e35a8f2de2665"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_RVKRNUM_2_14<a id="a197c4d1114fb917fac0dc1744172f9ceae8de9a8500e46884df317fb3f9ae0add"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SPIMM<a id="a197c4d1114fb917fac0dc1744172f9ceaa8cef4cfeea4b3ae543a5c3ef7f7a0bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_FRMARG<a id="a197c4d1114fb917fac0dc1744172f9cea17afb74d764deccf75051dacae954a2f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_RTZARG<a id="a197c4d1114fb917fac0dc1744172f9cea90d074c4324aea985b01f004fe24fb5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_COND_CODE<a id="a197c4d1114fb917fac0dc1744172f9cea695d30f50f574052b8cd4cebbd193334"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_VEC_POLICY<a id="a197c4d1114fb917fac0dc1744172f9cea306c98721f4580b719410b99e97f72f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SEW<a id="a197c4d1114fb917fac0dc1744172f9ceab96b995fbd6a26ba18f20dcdd64d8f9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_SEW_MASK<a id="a197c4d1114fb917fac0dc1744172f9cea08cd335c321880a781d295c290093e84"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_VEC_RM<a id="a197c4d1114fb917fac0dc1744172f9cea7cbfdd1597f1d30500e332e41781c5a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_LAST_RISCV_IMM<a id="a197c4d1114fb917fac0dc1744172f9cea56f2d8495ffe6c5bd5a115e21f9d8b7c"></a></td>
<td class="doxyEnumItemDescription"> (= OPERAND_VEC_RM)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_AVL<a id="a197c4d1114fb917fac0dc1744172f9ceac22e98c1a337c558bb21a4edd9479549"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">RISCVBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
