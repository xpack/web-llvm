---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/armcc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `ARMCC` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::ARMCC { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CondCodes { <a href="#ac8391dd6b8083baa870dee5142ff22b6">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ac8391dd6b8083baa870dee5142ff22b6">CondCodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd63de978510703f28cd98ea7c0ffa5">getOppositeCondition</a> (CondCodes CC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ac8391dd6b8083baa870dee5142ff22b6">ARMCC::CondCodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61cfc597ed332871e150787939dd3923">getSwappedCondition</a> (ARMCC::CondCodes CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSwappedCondition - assume the flags are set by <a href="#ac8391dd6b8083baa870dee5142ff22b6af6284b830f5e4fe2a8ddb9ff1a25ee46">MI(a,b)</a>, return the condition code if we modify the instructions such that flags are set by <a href="#ac8391dd6b8083baa870dee5142ff22b6af6284b830f5e4fe2a8ddb9ff1a25ee46">MI(b,a)</a>. <a href="#a61cfc597ed332871e150787939dd3923">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### CondCodes {#ac8391dd6b8083baa870dee5142ff22b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMCC::CondCodes </td>
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
<td class="doxyEnumItemName">EQ<a id="ac8391dd6b8083baa870dee5142ff22b6a4f1d9a9a0660bc80837984980c7ba402"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NE<a id="ac8391dd6b8083baa870dee5142ff22b6ae08639a6e0f682daf9d9b4809ee0cf7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HS<a id="ac8391dd6b8083baa870dee5142ff22b6a038249ad0a9ef6d79cc3506c96dd3c1f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LO<a id="ac8391dd6b8083baa870dee5142ff22b6a85a7716b3a259c91702bce293fb923df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MI<a id="ac8391dd6b8083baa870dee5142ff22b6af6284b830f5e4fe2a8ddb9ff1a25ee46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PL<a id="ac8391dd6b8083baa870dee5142ff22b6a8a1e111b6a355c527c0e325a6492c1fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VS<a id="ac8391dd6b8083baa870dee5142ff22b6abe109952a13e776b7b978e02e4f33427"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VC<a id="ac8391dd6b8083baa870dee5142ff22b6ad2c4e3875c38c36df4848049d50cc28d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HI<a id="ac8391dd6b8083baa870dee5142ff22b6a7ed629585c923f434528020bd892bb97"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LS<a id="ac8391dd6b8083baa870dee5142ff22b6a5b518bf08cf352b115648f7719a7f610"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GE<a id="ac8391dd6b8083baa870dee5142ff22b6a802d63db44042a459a19b9f89b5b470c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LT<a id="ac8391dd6b8083baa870dee5142ff22b6a5f1f4297ecf2dafb48ff1cb0597faea8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GT<a id="ac8391dd6b8083baa870dee5142ff22b6ace020af050937ea3b758ed0f2c07af50"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LE<a id="ac8391dd6b8083baa870dee5142ff22b6a59df2d2242b1477e41d1d160980ed371"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AL<a id="ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/utils/armbaseinfo-h">ARMBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getOppositeCondition() {#a4bd63de978510703f28cd98ea7c0ffa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CondCodes llvm::ARMCC::getOppositeCondition (<a href="#ac8391dd6b8083baa870dee5142ff22b6">CondCodes</a> CC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/utils/armbaseinfo-h">ARMBaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a4f1d9a9a0660bc80837984980c7ba402">EQ</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a802d63db44042a459a19b9f89b5b470c">GE</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6ace020af050937ea3b758ed0f2c07af50">GT</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a7ed629585c923f434528020bd892bb97">HI</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a038249ad0a9ef6d79cc3506c96dd3c1f">HS</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a59df2d2242b1477e41d1d160980ed371">LE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a85a7716b3a259c91702bce293fb923df">LO</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a5b518bf08cf352b115648f7719a7f610">LS</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a5f1f4297ecf2dafb48ff1cb0597faea8">LT</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6af6284b830f5e4fe2a8ddb9ff1a25ee46">MI</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6ae08639a6e0f682daf9d9b4809ee0cf7c">NE</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a8a1e111b6a355c527c0e325a6492c1fe">PL</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6ad2c4e3875c38c36df4848049d50cc28d">VC</a> and <a href="#ac8391dd6b8083baa870dee5142ff22b6abe109952a13e776b7b978e02e4f33427">VS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad43d0a6a64bad5f305bb9ad845bd2096">anonymous{ARMAsmParser.cpp}::ARMOperand::addITCondCodeInvOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a36dd5a226839c6599dc871cafd02f716">CanInvertMVEVCMP</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#af76e71e7ea189719baa6f8819724fac5">llvm::ARMBaseInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4236a4880dff9f75230ffb9d581defaa">IsCMPZCSINC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a5cfcaf632d98be49b27f2ff3a3c8cbb1">IsVPNOTEquivalent</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#ab27e65f978739f8a4075962e72373af5">anonymous{ARMAsmParser.cpp}::ARMAsmParser::MatchInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a4ba6b9afcc5b700d4c09664b5fa009d9">llvm::ARMTargetLowering::PerformCMOVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aae8b403580f3136879e238457f94d7ba">PerformCSETCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aff356d07d12d1545af6081fff90c9d05">llvm::ARMInstPrinter::printMandatoryInvertedPredicateOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a1b0989b431ac4ebde3936d535004cb88">llvm::ARMBaseInstrInfo::reverseBranchCondition</a>.</p>

</div>
</div>

### getSwappedCondition() {#a61cfc597ed332871e150787939dd3923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMCC::CondCodes llvm::ARMCC::getSwappedCondition (<a href="#ac8391dd6b8083baa870dee5142ff22b6">ARMCC::CondCodes</a> CC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSwappedCondition - assume the flags are set by <a href="#ac8391dd6b8083baa870dee5142ff22b6af6284b830f5e4fe2a8ddb9ff1a25ee46">MI(a,b)</a>, return the condition code if we modify the instructions such that flags are set by <a href="#ac8391dd6b8083baa870dee5142ff22b6af6284b830f5e4fe2a8ddb9ff1a25ee46">MI(b,a)</a>.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/utils/armbaseinfo-h">ARMBaseInfo.h</a>.</p>


<p>References <a href="#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a4f1d9a9a0660bc80837984980c7ba402">EQ</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a802d63db44042a459a19b9f89b5b470c">GE</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6ace020af050937ea3b758ed0f2c07af50">GT</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a7ed629585c923f434528020bd892bb97">HI</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a038249ad0a9ef6d79cc3506c96dd3c1f">HS</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a59df2d2242b1477e41d1d160980ed371">LE</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a85a7716b3a259c91702bce293fb923df">LO</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a5b518bf08cf352b115648f7719a7f610">LS</a>, <a href="#ac8391dd6b8083baa870dee5142ff22b6a5f1f4297ecf2dafb48ff1cb0597faea8">LT</a> and <a href="#ac8391dd6b8083baa870dee5142ff22b6ae08639a6e0f682daf9d9b4809ee0cf7c">NE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a5cfcaf632d98be49b27f2ff3a3c8cbb1">IsVPNOTEquivalent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/utils/armbaseinfo-h">ARMBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
