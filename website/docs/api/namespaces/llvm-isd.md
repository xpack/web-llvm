---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/isd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `ISD` Namespace

<p><a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a> namespace - This namespace contains an enum which represents all of the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> node types and value types. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::ISD { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/isd/globalisel">GlobalISel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ArgFlagsTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">InputArg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">InputArg</a> - This struct carries flags and type information about a single incoming (formal) argument or incoming (from the perspective of the caller) return value virtual register. <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">OutputArg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">OutputArg</a> - This struct carries flags and a value for a single outgoing (actual) argument or outgoing (from the perspective of the caller) return value virtual register. <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType { <a href="#a22ea9cec080dd5f4f47ba234c2f59110">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a> enum - This enum defines the target-independent operators for a <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>. <a href="#a22ea9cec080dd5f4f47ba234c2f59110">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MemIndexedMode { <a href="#abee7ecb577fcade34eb16ccb7f503e31">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#abee7ecb577fcade34eb16ccb7f503e31">MemIndexedMode</a> enum - This enum defines the load / store indexed addressing modes. <a href="#abee7ecb577fcade34eb16ccb7f503e31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MemIndexType { <a href="#aa30bf48cd2a89f80c9c608adcabc53e3">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#aa30bf48cd2a89f80c9c608adcabc53e3">MemIndexType</a> enum - This enum defines how to interpret MGATHER/SCATTER's index parameter when calculating addresses. <a href="#aa30bf48cd2a89f80c9c608adcabc53e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LoadExtType { <a href="#ad4d48171b87ca51ff54c10a436bac4d7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ad4d48171b87ca51ff54c10a436bac4d7">LoadExtType</a> enum - This enum defines the three variants of LOADEXT (load with extension). <a href="#ad4d48171b87ca51ff54c10a436bac4d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CondCode { <a href="#ac3c3cf58d6d631af6a172457304d3d07">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> enum - These are ordered carefully to make the bitfields below work out, when considering SETFALSE (something that never exists dynamically) as 0. <a href="#ac3c3cf58d6d631af6a172457304d3d07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b220b2107d211a5db501de58981e214">isBitwiseLogicOp</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this is bitwise logic opcode. <a href="#a6b220b2107d211a5db501de58981e214">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a22ea9cec080dd5f4f47ba234c2f59110">NodeType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0dd9a8bb9b1e116d0a0c3c63a92c64c">getInverseMinMaxOpcode</a> (unsigned MinMaxOpc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a <span class="doxyComputerOutput">MinMaxOpc</span> of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::(U|S)MIN or <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::(U|S)MAX, returns <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::(U|S)MAX and <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::(U|S)MIN, respectively. <a href="#ab0dd9a8bb9b1e116d0a0c3c63a92c64c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a22ea9cec080dd5f4f47ba234c2f59110">NodeType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace75a0fc6736a8bf8b8187083078354d">getVecReduceBaseOpcode</a> (unsigned VecReduceOpcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get underlying scalar opcode for VECREDUCE opcode. <a href="#ace75a0fc6736a8bf8b8187083078354d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed1c239da7e4526d3140443b3bf6f8d7">isVPOpcode</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this is a vector-predicated Opcode. <a href="#aed1c239da7e4526d3140443b3bf6f8d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec28aae630b390b75abfebf79bce788">isVPBinaryOp</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this is a vector-predicated binary operation opcode. <a href="#a5ec28aae630b390b75abfebf79bce788">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d0f87095c6d1ece5c444d0e030083d">isVPReduction</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this is a vector-predicated reduction opcode. <a href="#ab7d0f87095c6d1ece5c444d0e030083d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7437e83b31f58ab47107029f63bd70b0">getVPMaskIdx</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The operand position of the vector mask. <a href="#a7437e83b31f58ab47107029f63bd70b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d086c45b7e89dc21157d97b9fc150a5">getVPExplicitVectorLengthIdx</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The operand position of the explicit vector length parameter. <a href="#a8d086c45b7e89dc21157d97b9fc150a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67022d78a6d8ee4377558da9ff259b8b">getBaseOpcodeForVP</a> (unsigned Opcode, bool hasFPExcept)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Translate this VP Opcode to its corresponding non-VP Opcode. <a href="#a67022d78a6d8ee4377558da9ff259b8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d44a0b302d0ccccb3aef22380071bc6">getVPForBaseOpcode</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Translate this non-VP Opcode to its corresponding VP Opcode. <a href="#a9d44a0b302d0ccccb3aef22380071bc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247f22e450c54c4a1c680641cb7546e7">isIndexTypeSigned</a> (MemIndexType IndexType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a22ea9cec080dd5f4f47ba234c2f59110">NodeType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdb5c9abf8403d4dbf0d8ae59d89916">getExtForLoadExtType</a> (bool IsFP, LoadExtType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae86ddfa346964171caa61f29d46294b">isSignedIntSetCC</a> (CondCode Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a setcc instruction that performs a signed comparison when used with integer operands. <a href="#aae86ddfa346964171caa61f29d46294b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb237925346ec53b00d3c82a42311318">isUnsignedIntSetCC</a> (CondCode Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a setcc instruction that performs an unsigned comparison when used with integer operands. <a href="#adb237925346ec53b00d3c82a42311318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda64d97fb7fe554744b7a68c304c224">isIntEqualitySetCC</a> (CondCode Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a setcc instruction that performs an equality comparison when used with integer operands. <a href="#afda64d97fb7fe554744b7a68c304c224">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47810790d5bd808946ba55b160e513e7">isFPEqualitySetCC</a> (CondCode Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a setcc instruction that performs an equality comparison when used with floating point operands. <a href="#a47810790d5bd808946ba55b160e513e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eaea873272c138c801dae8542b1be46">isTrueWhenEqual</a> (CondCode Cond)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified condition returns true if the two operands to the condition are equal. <a href="#a6eaea873272c138c801dae8542b1be46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cfab76369f71a9f62a02815c5aa0777">getUnorderedFlavor</a> (CondCode Cond)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function returns 0 if the condition is always false if an operand is a NaN, 1 if the condition is always true if the operand is a NaN, and 2 if the condition is undefined if the operand is a NaN. <a href="#a7cfab76369f71a9f62a02815c5aa0777">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fbc38db5c4f3ef878ab19245d3f381d">getSetCCInverse</a> (CondCode Operation, EVT Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operation corresponding to !(X op Y), where 'op' is a valid SetCC operation. <a href="#a5fbc38db5c4f3ef878ab19245d3f381d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a72af46491472b765d836f2b5b62592">isExtOpcode</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256306086883f189bdc13ed15c2f7800">isExtVecInRegOpcode</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc23aed232ccdeadbd8648c349236a6">getSetCCSwappedOperands</a> (CondCode Operation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operation corresponding to (Y op X) when given the operation for (X op Y). <a href="#a9cc23aed232ccdeadbd8648c349236a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1bf9aaeb72d421a1ef57a1a1e6fac92">getSetCCOrOperation</a> (CondCode Op1, CondCode Op2, EVT Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the result of a logical OR between different comparisons of identical values: ((X op1 Y) | (X op2 Y)). <a href="#af1bf9aaeb72d421a1ef57a1a1e6fac92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06081b690c5f0c0be1e6c520585c2b5c">getSetCCAndOperation</a> (CondCode Op1, CondCode Op2, EVT Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the result of a logical AND between different comparisons of identical values: ((X op1 Y) &amp; (X op2 Y)). <a href="#a06081b690c5f0c0be1e6c520585c2b5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb64237a88493be2c913b0a51630a0f">isConstantSplatVector</a> (const SDNode *N, APInt &amp;SplatValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/node">Node</a> predicates. <a href="#aafb64237a88493be2c913b0a51630a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b1839785665aed1d6e91dd72764713">isConstantSplatVectorAllOnes</a> (const SDNode *N, bool BuildVectorOnly=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified node is a BUILD_VECTOR or SPLAT_VECTOR where all of the elements are ~0 or undef. <a href="#a08b1839785665aed1d6e91dd72764713">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a531723c97a9c44056fc4996bde57229e">isConstantSplatVectorAllZeros</a> (const SDNode *N, bool BuildVectorOnly=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified node is a BUILD_VECTOR or SPLAT_VECTOR where all of the elements are 0 or undef. <a href="#a531723c97a9c44056fc4996bde57229e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78d4df51ca05e4fb1630a01e07de434">isBuildVectorAllOnes</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified node is a BUILD_VECTOR where all of the elements are ~0 or undef. <a href="#ac78d4df51ca05e4fb1630a01e07de434">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac3e239cbdfe15a8e9bad4f8e1e3a95">isBuildVectorAllZeros</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified node is a BUILD_VECTOR where all of the elements are 0 or undef. <a href="#aaac3e239cbdfe15a8e9bad4f8e1e3a95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f37af786c5ba90887c1b4ec137a066c">isBuildVectorOfConstantSDNodes</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified node is a BUILD_VECTOR node of all <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> or undef. <a href="#a2f37af786c5ba90887c1b4ec137a066c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf3a86e6cdc4fe3dbd4e618c2f7a64c2">isBuildVectorOfConstantFPSDNodes</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified node is a BUILD_VECTOR node of all <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode">ConstantFPSDNode</a> or undef. <a href="#abf3a86e6cdc4fe3dbd4e618c2f7a64c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a570c0c51d118ee761eb55fc0d2d910f4">isVectorShrinkable</a> (const SDNode *N, unsigned NewEltSize, bool Signed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified node is a vector where all elements can be truncated to the specified element size without a loss in meaning. <a href="#a570c0c51d118ee761eb55fc0d2d910f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a933d79e63e855d7c90bf161355c008ec">allOperandsUndef</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the node has at least one operand and all operands of the specified node are <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7c6d8f265e9e16e5debdb9a536b55d3d">ISD::UNDEF</a>. <a href="#a933d79e63e855d7c90bf161355c008ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a938294d45605337641e10c207def0988">isFreezeUndef</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified node is <a href="#a22ea9cec080dd5f4f47ba234c2f59110ad3b50b6d74957b19afb85ac29f66afef">FREEZE(UNDEF)</a>. <a href="#a938294d45605337641e10c207def0988">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaaeadcd82b42fc0d385a6247bf7bb52">isNormalLoad</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified node is a non-extending and unindexed load. <a href="#afaaeadcd82b42fc0d385a6247bf7bb52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15623094a1ed0cd7163dc786e44c87c9">isNON_EXTLoad</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified node is a non-extending load. <a href="#a15623094a1ed0cd7163dc786e44c87c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a910795e8d77c1545da0683c0e1cb81ee">isEXTLoad</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified node is a EXTLOAD. <a href="#a910795e8d77c1545da0683c0e1cb81ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac174dc465cbe0e04a0f5e41c0a422124">isSEXTLoad</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified node is a SEXTLOAD. <a href="#ac174dc465cbe0e04a0f5e41c0a422124">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35edacef22fcaed7a8681fa573476131">isZEXTLoad</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified node is a ZEXTLOAD. <a href="#a35edacef22fcaed7a8681fa573476131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da84980dd2ee06405d74303cfb90485">isUNINDEXEDLoad</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified node is an unindexed load. <a href="#a7da84980dd2ee06405d74303cfb90485">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308088c2d65f8f3955f5fb0f6aca7ccc">isNormalStore</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified node is a non-truncating and unindexed store. <a href="#a308088c2d65f8f3955f5fb0f6aca7ccc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c74add1b228292dae9d97d63b6f27b">isUNINDEXEDStore</a> (const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified node is an unindexed store. <a href="#ab5c74add1b228292dae9d97d63b6f27b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ConstNodeType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5bffdefad1ad0a43b40eaa2a2cded351">matchUnaryPredicateImpl</a> (SDValue Op, std::function&lt; bool(ConstNodeType *)&gt; Match, bool AllowUndefs=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to match a unary predicate against a scalar/splat constant or every element of a constant BUILD_VECTOR. <a href="#a5bffdefad1ad0a43b40eaa2a2cded351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309c11edf22da984f95cf9ba7a699c11">matchUnaryPredicate</a> (SDValue Op, std::function&lt; bool(ConstantSDNode *)&gt; Match, bool AllowUndefs=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook for matching <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> predicate. <a href="#a309c11edf22da984f95cf9ba7a699c11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425d6f0e5036ca26fdd80efcaae21589">matchUnaryFpPredicate</a> (SDValue Op, std::function&lt; bool(ConstantFPSDNode *)&gt; Match, bool AllowUndefs=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook for matching <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode">ConstantFPSDNode</a> predicate. <a href="#a425d6f0e5036ca26fdd80efcaae21589">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab283a383171c46fb4445cb64eb6b687a">matchBinaryPredicate</a> (SDValue LHS, SDValue RHS, std::function&lt; bool(ConstantSDNode *, ConstantSDNode *)&gt; Match, bool AllowUndefs=false, bool AllowTypeMismatch=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to match a binary predicate against a pair of scalar/splat constants or every element of a pair of constant BUILD_VECTORs. <a href="#ab283a383171c46fb4445cb64eb6b687a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d58a0ced655af200989177b8e029f2d">isOverflowIntrOpRes</a> (SDValue Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified value is the overflow result from one of the overflow intrinsic nodes. <a href="#a2d58a0ced655af200989177b8e029f2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0010333b4e1424ce473b508d802bbbd">LAST_INDEXED_MODE</a> = <a href="#abee7ecb577fcade34eb16ccb7f503e31a10a4094c81c0b9cd5e82e53b48932203">POST_DEC</a> + 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a769bfb423d42986a688a04035ce40cf7">LAST_MEM_INDEX_TYPE</a> = <a href="#aa30bf48cd2a89f80c9c608adcabc53e3af3218635b665db9e7e1d97e015f14e3a">UNSIGNED_SCALED</a> + 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53490a5ced1d50808fe962a298c315cd">LAST_LOADEXT_TYPE</a> = <a href="#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">ZEXTLOAD</a> + 1</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a> namespace - This namespace contains an enum which represents all of the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> node types and value types.</p>

<div class="doxySectionDef">

## Enumerations

### CondCode {#ac3c3cf58d6d631af6a172457304d3d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ISD::CondCode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> enum - These are ordered carefully to make the bitfields below work out, when considering SETFALSE (something that never exists dynamically) as 0.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETFALSE<a id="ac3c3cf58d6d631af6a172457304d3d07ae258b87332b47d96bdf47e4cd915f9ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETOEQ<a id="ac3c3cf58d6d631af6a172457304d3d07a08c31033acfb9d6f0bc4a8a82cc26862"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETOGT<a id="ac3c3cf58d6d631af6a172457304d3d07a31d1e24e08b255d6aa290d67d16ce2c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETOGE<a id="ac3c3cf58d6d631af6a172457304d3d07ac7bb30d4918c1ee9dd208083154e109f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETOLT<a id="ac3c3cf58d6d631af6a172457304d3d07a20257a4d3833cf88afd42caeaed70dde"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETOLE<a id="ac3c3cf58d6d631af6a172457304d3d07a1febf3bac2f3d7d98ec19f1ff5c385ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETONE<a id="ac3c3cf58d6d631af6a172457304d3d07a57c68bf7ef20bd558854a24d5b0c1e72"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETO<a id="ac3c3cf58d6d631af6a172457304d3d07a71f916390487bb109d9968c72553eaf4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETUO<a id="ac3c3cf58d6d631af6a172457304d3d07a48a334bbe606d5e82c9cd84eaa127b50"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETUEQ<a id="ac3c3cf58d6d631af6a172457304d3d07a0deb50cd2f3f8e4a94eef4cdf769b848"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETUGT<a id="ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETUGE<a id="ac3c3cf58d6d631af6a172457304d3d07a9dff1dcbac65852b71473818c11869b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETULT<a id="ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETULE<a id="ac3c3cf58d6d631af6a172457304d3d07ac538f0b432df970cbaaf6b81d777c6a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETUNE<a id="ac3c3cf58d6d631af6a172457304d3d07a0d1546187d4d526fcbdd43183689075e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETTRUE<a id="ac3c3cf58d6d631af6a172457304d3d07a8e273eab0623ea5713aa5bcbdac2b16b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETFALSE2<a id="ac3c3cf58d6d631af6a172457304d3d07a66792a566255872c951cb6b8f9cb0541"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETEQ<a id="ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETGT<a id="ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETGE<a id="ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETLT<a id="ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETLE<a id="ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETNE<a id="ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETTRUE2<a id="ac3c3cf58d6d631af6a172457304d3d07a1a575d029fd38d929229ac39e573e8fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC_INVALID<a id="ac3c3cf58d6d631af6a172457304d3d07aeded54fe1be320194e9ff0f5825df0e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>"U" -&gt; Unsigned (for integer operands) or Unordered (for floating point), "L" -&gt; Less than, "G" -&gt; Greater than, "E" -&gt; Equal to. If the "N" column is 1, the result of the comparison is undefined if the input is a NAN.</p>


<p>All of these (except for the 'always folded ops') should be handled for floating point. For integer, only the SETEQ,SETNE,SETLT,SETLE,SETGT, SETGE,SETULT,SETULE,SETUGT, and SETUGE opcodes are used.</p>


<p>Note that these are laid out in a specific order to allow bit-twiddling to transform conditions.</p>


<p>Definition at line 1610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>

</div>
</div>

### LoadExtType {#ad4d48171b87ca51ff54c10a436bac4d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ISD::LoadExtType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#ad4d48171b87ca51ff54c10a436bac4d7">LoadExtType</a> enum - This enum defines the three variants of LOADEXT (load with extension).</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NON_EXTLOAD<a id="ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTLOAD<a id="ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEXTLOAD<a id="ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZEXTLOAD<a id="ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>SEXTLOAD loads the integer operand and sign extends it to a larger integer result type. ZEXTLOAD loads the integer operand and zero extends it to a larger integer result type. EXTLOAD is used for two things: floating point extending loads and integer extending loads [the top bits are undefined].</p>


<p>Definition at line 1590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>

</div>
</div>

### MemIndexedMode {#abee7ecb577fcade34eb16ccb7f503e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ISD::MemIndexedMode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#abee7ecb577fcade34eb16ccb7f503e31">MemIndexedMode</a> enum - This enum defines the load / store indexed addressing modes.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNINDEXED<a id="abee7ecb577fcade34eb16ccb7f503e31ade1c53e7b8a373e22ec53ff7bcbace9f"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRE_INC<a id="abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRE_DEC<a id="abee7ecb577fcade34eb16ccb7f503e31a57c3822f99653c422d5a21206adc6e42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">POST_INC<a id="abee7ecb577fcade34eb16ccb7f503e31a866c29237765ff291c9503abbdca60e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">POST_DEC<a id="abee7ecb577fcade34eb16ccb7f503e31a10a4094c81c0b9cd5e82e53b48932203"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>UNINDEXED "Normal" load / store. The effective address is already computed and is available in the base pointer. The offset operand is always undefined. In addition to producing a chain, an unindexed load produces one value (result of the load); an unindexed store does not produce a value.</p>


<p>PRE_INC Similar to the unindexed mode where the effective address is PRE_DEC the value of the base pointer add / subtract the offset. It considers the computation as being folded into the load / store operation (i.e. the load / store does the address computation as well as performing the memory transaction). The base operand is always undefined. In addition to producing a chain, pre-indexed load produces two values (result of the load and the result of the address computation); a pre-indexed store produces one value (result of the address computation).</p>


<p>POST_INC The effective address is the value of the base pointer. The POST_DEC value of the offset operand is then added to / subtracted from the base after memory transaction. In addition to producing a chain, post-indexed load produces two values (the result of the load and the result of the base +/- offset computation); a post-indexed store produces one value (the the result of the base +/- offset computation).</p>


<p>Definition at line 1559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>

</div>
</div>

### MemIndexType {#aa30bf48cd2a89f80c9c608adcabc53e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ISD::MemIndexType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#aa30bf48cd2a89f80c9c608adcabc53e3">MemIndexType</a> enum - This enum defines how to interpret MGATHER/SCATTER's index parameter when calculating addresses.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIGNED_SCALED<a id="aa30bf48cd2a89f80c9c608adcabc53e3a0173acb50fe8c4337c23a98baab3f4db"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNSIGNED_SCALED<a id="aa30bf48cd2a89f80c9c608adcabc53e3af3218635b665db9e7e1d97e015f14e3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>SIGNED_SCALED Addr = Base + ((signed)Index * Scale) UNSIGNED_SCALED Addr = Base + ((unsigned)Index * Scale)</p>


<p>NOTE: The value of Scale is typically only known to the node owning the IndexType, with a value of 1 the equivalent of being unscaled.</p>


<p>Definition at line 1572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>

</div>
</div>

### NodeType {#a22ea9cec080dd5f4f47ba234c2f59110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ISD::NodeType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a> enum - This enum defines the target-independent operators for a <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DELETED_NODE<a id="a22ea9cec080dd5f4f47ba234c2f59110a062083eb3ff8c441c73d3bf42ca09bba"></a></td>
<td class="doxyEnumItemDescription">DELETED_NODE - This is an illegal value that is used to catch errors</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EntryToken<a id="a22ea9cec080dd5f4f47ba234c2f59110a926013f6dca240eca95aca66c8d3e74b"></a></td>
<td class="doxyEnumItemDescription">EntryToken - This is the marker used to indicate the start of a region</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TokenFactor<a id="a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8"></a></td>
<td class="doxyEnumItemDescription">TokenFactor - This node takes multiple tokens as input and produces a single token result</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AssertSext<a id="a22ea9cec080dd5f4f47ba234c2f59110aee4f13218bdbb5c5697f7e786618ecb2"></a></td>
<td class="doxyEnumItemDescription">AssertSext, AssertZext - These nodes record if a register contains a value that has already been zero or sign extended from a narrower type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AssertZext<a id="a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AssertAlign<a id="a22ea9cec080dd5f4f47ba234c2f59110a8005dc9efe12e770682b4b5200dad30b"></a></td>
<td class="doxyEnumItemDescription">AssertAlign - These nodes record if a register contains a value that has a known alignment and the trailing bits are known to be zero</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BasicBlock<a id="a22ea9cec080dd5f4f47ba234c2f59110a8472e46f9e4db168c5610ecdfb05dbaf"></a></td>
<td class="doxyEnumItemDescription">Various leaf nodes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALUETYPE<a id="a22ea9cec080dd5f4f47ba234c2f59110a40d4f41a75df8e16bc5dbe62d62465b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONDCODE<a id="a22ea9cec080dd5f4f47ba234c2f59110aa366e6b1653ab1cedbeeaef9afecedd7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="a22ea9cec080dd5f4f47ba234c2f59110a419e8283a58d2b1b86591fa7f18ccfd9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegisterMask<a id="a22ea9cec080dd5f4f47ba234c2f59110a7e54881d7b0838c37485e4c79d215d07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Constant<a id="a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ConstantFP<a id="a22ea9cec080dd5f4f47ba234c2f59110a1be4c8da7c68a4c683de1a98b5cc5b9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GlobalAddress<a id="a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GlobalTLSAddress<a id="a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrameIndex<a id="a22ea9cec080dd5f4f47ba234c2f59110a4b437632fd9b97dd36010d85eb363efe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JumpTable<a id="a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ConstantPool<a id="a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExternalSymbol<a id="a22ea9cec080dd5f4f47ba234c2f59110ad88f843bce966361c7fd2cd022e6528a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BlockAddress<a id="a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PtrAuthGlobalAddress<a id="a22ea9cec080dd5f4f47ba234c2f59110a8df1b84ea64ad5048f27873205c8ab89"></a></td>
<td class="doxyEnumItemDescription">A ptrauth constant</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GLOBAL_OFFSET_TABLE<a id="a22ea9cec080dd5f4f47ba234c2f59110aaef4ead62e1835b863820f6c818c36ac"></a></td>
<td class="doxyEnumItemDescription">The address of the GOT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRAMEADDR<a id="a22ea9cec080dd5f4f47ba234c2f59110abdb38c8daa8c1ab881007062d113cef3"></a></td>
<td class="doxyEnumItemDescription">FRAMEADDR, RETURNADDR - These nodes represent llvm.frameaddress and llvm.returnaddress on the DAG</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RETURNADDR<a id="a22ea9cec080dd5f4f47ba234c2f59110a2dfacb29792dd59f2cfbe529206265bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDROFRETURNADDR<a id="a22ea9cec080dd5f4f47ba234c2f59110a591c03cc284124ff624856ce485ebc17"></a></td>
<td class="doxyEnumItemDescription">ADDROFRETURNADDR - Represents the llvm.addressofreturnaddress intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPONENTRY<a id="a22ea9cec080dd5f4f47ba234c2f59110add9a41fa65a9675200d73710a82b880e"></a></td>
<td class="doxyEnumItemDescription">SPONENTRY - Represents the llvm.sponentry intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOCAL_RECOVER<a id="a22ea9cec080dd5f4f47ba234c2f59110a9d483820471b07a73225bf33986fd110"></a></td>
<td class="doxyEnumItemDescription">LOCAL_RECOVER - Represents the llvm.localrecover intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READ_REGISTER<a id="a22ea9cec080dd5f4f47ba234c2f59110a92fceabd268d62ef2c95799a102b8abf"></a></td>
<td class="doxyEnumItemDescription">READ_REGISTER, WRITE_REGISTER - This node represents llvm.register on the DAG, which implements the named register global variables extension</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WRITE_REGISTER<a id="a22ea9cec080dd5f4f47ba234c2f59110a61a1595d03afe86764ad7625d358608e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRAME_TO_ARGS_OFFSET<a id="a22ea9cec080dd5f4f47ba234c2f59110a228deacdfba1bd2d5a3663b19609f945"></a></td>
<td class="doxyEnumItemDescription">FRAME_TO_ARGS_OFFSET - This node represents offset from frame pointer to first (possible) on-stack argument</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_DWARF_CFA<a id="a22ea9cec080dd5f4f47ba234c2f59110abad932e63381a4671b5db19a3404c82e"></a></td>
<td class="doxyEnumItemDescription">EH_DWARF_CFA - This node represents the pointer to the DWARF Canonical Frame Address (CFA), generally the value of the stack pointer at the call site in the previous frame</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_RETURN<a id="a22ea9cec080dd5f4f47ba234c2f59110a4edf35e2383003ff20057e5a45012a55"></a></td>
<td class="doxyEnumItemDescription">OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a4edf35e2383003ff20057e5a45012a55">EH_RETURN(INCHAIN, OFFSET, HANDLER)</a> - This node represents 'eh_return' gcc dwarf builtin, which is used to return from exception</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_SETJMP<a id="a22ea9cec080dd5f4f47ba234c2f59110ae5a57fe9fd413df909ab121ca1a813c7"></a></td>
<td class="doxyEnumItemDescription">RESULT, OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110ae5a57fe9fd413df909ab121ca1a813c7">EH_SJLJ_SETJMP(INCHAIN, buffer)</a> This corresponds to the eh.sjlj.setjmp intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_LONGJMP<a id="a22ea9cec080dd5f4f47ba234c2f59110a122a450e069003dc86859ef47ab6e278"></a></td>
<td class="doxyEnumItemDescription">OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a122a450e069003dc86859ef47ab6e278">EH_SJLJ_LONGJMP(INCHAIN, buffer)</a> This corresponds to the eh.sjlj.longjmp intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_SETUP_DISPATCH<a id="a22ea9cec080dd5f4f47ba234c2f59110a2e0f3a93e85a46b2ebac7330c2a0c581"></a></td>
<td class="doxyEnumItemDescription">OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a2e0f3a93e85a46b2ebac7330c2a0c581">EH_SJLJ_SETUP_DISPATCH(INCHAIN)</a> The target initializes the dispatch table here</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetConstant<a id="a22ea9cec080dd5f4f47ba234c2f59110ac479e53ca98903b1028ec80e12fb0af8"></a></td>
<td class="doxyEnumItemDescription">TargetConstant* - Like Constant*, but the DAG does not do any folding, simplification, or lowering of the constant</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetConstantFP<a id="a22ea9cec080dd5f4f47ba234c2f59110a95cd714ab601765342e2ec9f6ba2cb34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetGlobalAddress<a id="a22ea9cec080dd5f4f47ba234c2f59110a87b8176af163ee944af127081d24f4a2"></a></td>
<td class="doxyEnumItemDescription">TargetGlobalAddress - Like GlobalAddress, but the DAG does no folding or anything else with this node, and this is valid in the target-specific dag, turning into a GlobalAddress operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetGlobalTLSAddress<a id="a22ea9cec080dd5f4f47ba234c2f59110afc9ad7857b7faf49dcde3dcf434e22a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetFrameIndex<a id="a22ea9cec080dd5f4f47ba234c2f59110aa84894f4966964ef9fc79f9515a6c875"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetJumpTable<a id="a22ea9cec080dd5f4f47ba234c2f59110a603c0651ff8c3a929c5e1d8b9a8f14cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetConstantPool<a id="a22ea9cec080dd5f4f47ba234c2f59110a038a7f124b4118456a27a739c03650bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetExternalSymbol<a id="a22ea9cec080dd5f4f47ba234c2f59110a59b314018a929255951f01f8daaae72f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetBlockAddress<a id="a22ea9cec080dd5f4f47ba234c2f59110a1b7eba375863a0e80549eb1a782c5683"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MCSymbol<a id="a22ea9cec080dd5f4f47ba234c2f59110aabb68e91001557f73ff8af63eb8d5883"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TargetIndex<a id="a22ea9cec080dd5f4f47ba234c2f59110a606393d2a8329de83a61d6f6447d1035"></a></td>
<td class="doxyEnumItemDescription">TargetIndex - Like a constant pool entry, but with completely target-dependent semantics</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INTRINSIC_WO_CHAIN<a id="a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c"></a></td>
<td class="doxyEnumItemDescription">RESULT = <a href="#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">INTRINSIC_WO_CHAIN(INTRINSICID, arg1, arg2, ...)</a> This node represents a target intrinsic function with no side effects</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INTRINSIC_W_CHAIN<a id="a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9"></a></td>
<td class="doxyEnumItemDescription">RESULT,OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">INTRINSIC_W_CHAIN(INCHAIN, INTRINSICID, arg1, ...)</a> This node represents a target intrinsic function with side effects that returns a result</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INTRINSIC_VOID<a id="a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140"></a></td>
<td class="doxyEnumItemDescription">OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">INTRINSIC_VOID(INCHAIN, INTRINSICID, arg1, arg2, ...)</a> This node represents a target intrinsic function with side effects that does not return a result</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CopyToReg<a id="a22ea9cec080dd5f4f47ba234c2f59110a93bc27ca4d9e211c54b0d9efb660f080"></a></td>
<td class="doxyEnumItemDescription">CopyToReg - This node has three operands: a chain, a register number to set to this value, and a value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CopyFromReg<a id="a22ea9cec080dd5f4f47ba234c2f59110a84c47705bcf7271413738ae8bf3871e6"></a></td>
<td class="doxyEnumItemDescription">CopyFromReg - This node indicates that the input value is a virtual or physical register that is defined outside of the scope of this <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNDEF<a id="a22ea9cec080dd5f4f47ba234c2f59110a7c6d8f265e9e16e5debdb9a536b55d3d"></a></td>
<td class="doxyEnumItemDescription">UNDEF - An undefined node</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FREEZE<a id="a22ea9cec080dd5f4f47ba234c2f59110ad3b50b6d74957b19afb85ac29f66afef"></a></td>
<td class="doxyEnumItemDescription">FREEZE - <a href="#a22ea9cec080dd5f4f47ba234c2f59110ad3b50b6d74957b19afb85ac29f66afef">FREEZE(VAL)</a> returns an arbitrary value if VAL is UNDEF (or is evaluated to UNDEF), or returns VAL otherwise</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTRACT_ELEMENT<a id="a22ea9cec080dd5f4f47ba234c2f59110a7e6dca8262a3de788d1bab4ba184d675"></a></td>
<td class="doxyEnumItemDescription">EXTRACT_ELEMENT - This is used to get the lower or upper (determined by a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>, which is required to be operand #1) half of the integer or float value specified as operand #0</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUILD_PAIR<a id="a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf"></a></td>
<td class="doxyEnumItemDescription">BUILD_PAIR - This is the opposite of EXTRACT_ELEMENT in some ways</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MERGE_VALUES<a id="a22ea9cec080dd5f4f47ba234c2f59110a01c94937492f3ac3fb1e0be8eb0b9ef1"></a></td>
<td class="doxyEnumItemDescription">MERGE_VALUES - This node takes multiple discrete operands and returns them all as its individual results</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADD<a id="a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535"></a></td>
<td class="doxyEnumItemDescription">Simple integer binary arithmetic operators</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUB<a id="a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUL<a id="a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDIV<a id="a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UDIV<a id="a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SREM<a id="a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UREM<a id="a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMUL_LOHI<a id="a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd"></a></td>
<td class="doxyEnumItemDescription">SMUL_LOHI/UMUL_LOHI - Multiply two integers of type iN, producing a signed/unsigned value of type i[2*N], and return the full value as two results, each of type iN</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMUL_LOHI<a id="a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDIVREM<a id="a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a"></a></td>
<td class="doxyEnumItemDescription">SDIVREM/UDIVREM - Divide two integers and produce both a quotient and remainder result</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UDIVREM<a id="a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CARRY_FALSE<a id="a22ea9cec080dd5f4f47ba234c2f59110acc20c926003b2af97ba08689176e7130"></a></td>
<td class="doxyEnumItemDescription">CARRY_FALSE - This node is used when folding other nodes, like ADDC/SUBC, which indicate the carry result is always false</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDC<a id="a22ea9cec080dd5f4f47ba234c2f59110a20084f62caecb0db80ad71bdabda73c2"></a></td>
<td class="doxyEnumItemDescription">Carry-setting nodes for multiple precision addition and subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBC<a id="a22ea9cec080dd5f4f47ba234c2f59110a2ab6db512a611d1ef4ff8069e2bbfd0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDE<a id="a22ea9cec080dd5f4f47ba234c2f59110ad116e32876f2275acf60ffb1651c9256"></a></td>
<td class="doxyEnumItemDescription">Carry-using nodes for multiple precision addition and subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBE<a id="a22ea9cec080dd5f4f47ba234c2f59110ac9246c101c0cc9232e37b3941194bb13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDO_CARRY<a id="a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf"></a></td>
<td class="doxyEnumItemDescription">Carry-using nodes for multiple precision addition and subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USUBO_CARRY<a id="a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDO_CARRY<a id="a22ea9cec080dd5f4f47ba234c2f59110af9eda6a77c3228cd36537469a7425133"></a></td>
<td class="doxyEnumItemDescription">Carry-using overflow-aware nodes for multiple precision addition and subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBO_CARRY<a id="a22ea9cec080dd5f4f47ba234c2f59110a139dc5419039d94496e69dbb264251b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDO<a id="a22ea9cec080dd5f4f47ba234c2f59110a863ec6ebb75bf89cfea14da646d77e92"></a></td>
<td class="doxyEnumItemDescription">RESULT, BOOL = [SU]ADDO(LHS, RHS) - Overflow-aware nodes for addition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDO<a id="a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBO<a id="a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7"></a></td>
<td class="doxyEnumItemDescription">Same for subtraction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USUBO<a id="a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMULO<a id="a22ea9cec080dd5f4f47ba234c2f59110aa35d0a58fdded3d225d512a60aea0951"></a></td>
<td class="doxyEnumItemDescription">Same for multiplication</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMULO<a id="a22ea9cec080dd5f4f47ba234c2f59110a7800622851751b8ae318b41f4096830e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SADDSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110af1b946afff631cee7aa6de570bef7785"></a></td>
<td class="doxyEnumItemDescription">RESULT = [US]ADDSAT(LHS, RHS) - Perform saturation addition on 2 integers with the same bit width (W)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UADDSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110a5e433873c201ad85c30e42da1ae05977"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSUBSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110a77984d86d70df1f3229da7a5119652a9"></a></td>
<td class="doxyEnumItemDescription">RESULT = [US]SUBSAT(LHS, RHS) - Perform saturation subtraction on 2 integers with the same bit width (W)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USUBSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110a89166b38f12c0bd3e8a61d8f1a5a8bc8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSHLSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110aa30a145a99902daca036d039378abca2"></a></td>
<td class="doxyEnumItemDescription">RESULT = [US]SHLSAT(LHS, RHS) - Perform saturation left shift</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USHLSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110a5ae4b108d3f627b66f3b1e5da51f4587"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMULFIX<a id="a22ea9cec080dd5f4f47ba234c2f59110a1a7f3f523e22ac3df6332e625289a7e6"></a></td>
<td class="doxyEnumItemDescription">RESULT = [US]MULFIX(LHS, RHS, SCALE) - Perform fixed point multiplication on 2 integers with the same width and scale</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMULFIX<a id="a22ea9cec080dd5f4f47ba234c2f59110a293cdca810c396f99a2bd63b017dd943"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMULFIXSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110a26a7dd56cd899cec0a1f6d2443f91db4"></a></td>
<td class="doxyEnumItemDescription">Same as the corresponding unsaturated fixed point instructions, but the result is clamped between the min and max values representable by the bits of the first 2 operands</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMULFIXSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110aaab3219acc86e3b3a199effbb69aa07a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDIVFIX<a id="a22ea9cec080dd5f4f47ba234c2f59110a470242ff0d0c1f979101aa369a3a410e"></a></td>
<td class="doxyEnumItemDescription">RESULT = [US]DIVFIX(LHS, RHS, SCALE) - Perform fixed point division on 2 integers with the same width and scale</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UDIVFIX<a id="a22ea9cec080dd5f4f47ba234c2f59110aaa5af2aa3cc2e31b44b69d43e13235be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDIVFIXSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110aadc85d973be8149bbaa5f372aa1faf3e"></a></td>
<td class="doxyEnumItemDescription">Same as the corresponding unsaturated fixed point instructions, but the result is clamped between the min and max values representable by the bits of the first 2 operands</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UDIVFIXSAT<a id="a22ea9cec080dd5f4f47ba234c2f59110a5c5ebc516cae422508ee0c062ef6b593"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FADD<a id="a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf"></a></td>
<td class="doxyEnumItemDescription">Simple binary floating point operators</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSUB<a id="a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMUL<a id="a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FDIV<a id="a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FREM<a id="a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FADD<a id="a22ea9cec080dd5f4f47ba234c2f59110ad11fa7fd2a91d210ecbdf09d56cd9f42"></a></td>
<td class="doxyEnumItemDescription">Constrained versions of the binary floating point operators</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSUB<a id="a22ea9cec080dd5f4f47ba234c2f59110ad6192a54cb1dfeca8173749cc735269a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMUL<a id="a22ea9cec080dd5f4f47ba234c2f59110a4b912b6be299d30d75b876e939d16fd6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FDIV<a id="a22ea9cec080dd5f4f47ba234c2f59110a4151e13f7626f6d790d58c0fa444f32e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FREM<a id="a22ea9cec080dd5f4f47ba234c2f59110aacf4034f48b7e32a9e20bfedbb5502bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMA<a id="a22ea9cec080dd5f4f47ba234c2f59110a26ff7f7547f66e1a4f6d5e7efe4b2f59"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSQRT<a id="a22ea9cec080dd5f4f47ba234c2f59110a476844aad24870fab3d132b5fe6b1f37"></a></td>
<td class="doxyEnumItemDescription">Constrained versions of libm-equivalent floating point intrinsics</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FPOW<a id="a22ea9cec080dd5f4f47ba234c2f59110a65a342694a17f4a1db771dbc36d31cc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FPOWI<a id="a22ea9cec080dd5f4f47ba234c2f59110a7acf26c84b90a50efe9898bc9bcd8d18"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FLDEXP<a id="a22ea9cec080dd5f4f47ba234c2f59110addd63c6d866c8a8020a0cc4de467b285"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSIN<a id="a22ea9cec080dd5f4f47ba234c2f59110a06c721642eadaa31c37384b39fe11387"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCOS<a id="a22ea9cec080dd5f4f47ba234c2f59110ae2047d551dd66943aa285b4c7eab0766"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FTAN<a id="a22ea9cec080dd5f4f47ba234c2f59110ad8ae8131038d9b94abd2880812bf5b0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FASIN<a id="a22ea9cec080dd5f4f47ba234c2f59110a548c5ee9bfffd516c18b0844d8916d98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FACOS<a id="a22ea9cec080dd5f4f47ba234c2f59110afc1699b53cce73a1a89fa9190db8f2f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FATAN<a id="a22ea9cec080dd5f4f47ba234c2f59110a5fc35989024437e6878d228dce85b34d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FATAN2<a id="a22ea9cec080dd5f4f47ba234c2f59110a1c24a514835d74a2a0b441825a622cef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSINH<a id="a22ea9cec080dd5f4f47ba234c2f59110a9b07fb8cd5a1230b0f736489ddd9eebc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCOSH<a id="a22ea9cec080dd5f4f47ba234c2f59110ac9090021eb9a063125475a3d2f380af2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FTANH<a id="a22ea9cec080dd5f4f47ba234c2f59110a244401fe9aee94da72b7f0fb6b095a45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FEXP<a id="a22ea9cec080dd5f4f47ba234c2f59110aba2dfbb2100ec6aee6e5b52bc713c26a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FEXP2<a id="a22ea9cec080dd5f4f47ba234c2f59110ad5d3bf9997ecfea792abc058e7d39e72"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FLOG<a id="a22ea9cec080dd5f4f47ba234c2f59110ad795680a8d2d37bdede6696d72f41c35"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FLOG10<a id="a22ea9cec080dd5f4f47ba234c2f59110ad227f160898f13eeb05150f03de8d40b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FLOG2<a id="a22ea9cec080dd5f4f47ba234c2f59110a409f18d3c3acb29ab844e9942441cc4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FRINT<a id="a22ea9cec080dd5f4f47ba234c2f59110af57a22f2843a1c3a79d17350945ede58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FNEARBYINT<a id="a22ea9cec080dd5f4f47ba234c2f59110ae463c3e40819d6e9de30d7d858867ef4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMAXNUM<a id="a22ea9cec080dd5f4f47ba234c2f59110a92f7a0e4dfe860ff938d463d84270ba3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMINNUM<a id="a22ea9cec080dd5f4f47ba234c2f59110a98f18e85e4e6421f5c859680602a4c1f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FCEIL<a id="a22ea9cec080dd5f4f47ba234c2f59110a1fb1e48394636004fd75f5916f0d730f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FFLOOR<a id="a22ea9cec080dd5f4f47ba234c2f59110ab74cbb3933c5f5d2cc90d299836c05cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FROUND<a id="a22ea9cec080dd5f4f47ba234c2f59110ab0953e80e4e94f6ded9680e64c5df5cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FROUNDEVEN<a id="a22ea9cec080dd5f4f47ba234c2f59110ab7d5c27c800b79a02a1492f1965af72f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FTRUNC<a id="a22ea9cec080dd5f4f47ba234c2f59110a883c1084962f12018ca0fe3e1222fa7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_LROUND<a id="a22ea9cec080dd5f4f47ba234c2f59110a6bd04c8da718875a071107ede0f362d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_LLROUND<a id="a22ea9cec080dd5f4f47ba234c2f59110adef1eba7d8c2a0db4a94d7327d217c90"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_LRINT<a id="a22ea9cec080dd5f4f47ba234c2f59110aa7fc883444df66de315a684ecf5f5e2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_LLRINT<a id="a22ea9cec080dd5f4f47ba234c2f59110ad4892124e4817d9807dcf39808016bc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMAXIMUM<a id="a22ea9cec080dd5f4f47ba234c2f59110a917038ef7ae3264e336457da0f75e95b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FMINIMUM<a id="a22ea9cec080dd5f4f47ba234c2f59110a3093a04e2918e155f32d435e2f974e88"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP_TO_SINT<a id="a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed"></a></td>
<td class="doxyEnumItemDescription">STRICT_FP_TO_[US]INT - Convert a floating point value to a signed or unsigned integer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP_TO_UINT<a id="a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_SINT_TO_FP<a id="a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6"></a></td>
<td class="doxyEnumItemDescription">STRICT_[US]INT_TO_FP - Convert a signed or unsigned integer to a floating point value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_UINT_TO_FP<a id="a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP_ROUND<a id="a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba"></a></td>
<td class="doxyEnumItemDescription">X = <a href="#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">STRICT_FP_ROUND(Y, TRUNC)</a> - Rounding 'Y' from a larger floating point type down to the precision of the destination VT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP_EXTEND<a id="a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6"></a></td>
<td class="doxyEnumItemDescription">X = <a href="#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">STRICT_FP_EXTEND(Y)</a> - Extend a smaller FP type into a larger FP type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSETCC<a id="a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f"></a></td>
<td class="doxyEnumItemDescription">STRICT_FSETCC/STRICT_FSETCCS - Constrained versions of SETCC, used for floating-point operands only</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FSETCCS<a id="a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPTRUNC_ROUND<a id="a22ea9cec080dd5f4f47ba234c2f59110a40b296b7db128b2d63f81a95efc5a311"></a></td>
<td class="doxyEnumItemDescription">FPTRUNC_ROUND - This corresponds to the fptrunc_round intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMA<a id="a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254"></a></td>
<td class="doxyEnumItemDescription">FMA - Perform a * b + c with no intermediate rounding step</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAD<a id="a22ea9cec080dd5f4f47ba234c2f59110a2415bea72c995bb9cf9f85bbbf90bcd7"></a></td>
<td class="doxyEnumItemDescription">FMAD - Perform a * b + c, while getting the same result as the separately rounded operations</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCOPYSIGN<a id="a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">FCOPYSIGN(X, Y)</a> - Return the value of X with the sign of Y</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FGETSIGN<a id="a22ea9cec080dd5f4f47ba234c2f59110a130b6a6d409367c8a61dd14dfa39785c"></a></td>
<td class="doxyEnumItemDescription">INT = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a130b6a6d409367c8a61dd14dfa39785c">FGETSIGN(FP)</a> - Return the sign bit of the specified floating point value as an integer 0/1 value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCANONICALIZE<a id="a22ea9cec080dd5f4f47ba234c2f59110a74a787311d3ab9a17ee0acde7b6a6b14"></a></td>
<td class="doxyEnumItemDescription">Returns platform specific canonical encoding of a floating point number</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IS_FPCLASS<a id="a22ea9cec080dd5f4f47ba234c2f59110a76b6d3008e806ea613323ff316ef72c3"></a></td>
<td class="doxyEnumItemDescription">Performs a check of floating point class property, defined by IEEE-754</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUILD_VECTOR<a id="a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">BUILD_VECTOR(ELT0, ELT1, ELT2, ELT3,...)</a> - Return a fixed-width vector with the specified, possibly variable, elements</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INSERT_VECTOR_ELT<a id="a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">INSERT_VECTOR_ELT(VECTOR, VAL, IDX)</a> - Returns VECTOR with the element at IDX replaced with VAL</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTRACT_VECTOR_ELT<a id="a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">EXTRACT_VECTOR_ELT(VECTOR, IDX)</a> - Returns a single element from VECTOR identified by the (potentially variable) element number IDX</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONCAT_VECTORS<a id="a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">CONCAT_VECTORS(VECTOR0, VECTOR1, ...)</a> - Given a number of values of vector type with the same length and element type, this produces a concatenated vector result value, with length equal to the sum of the lengths of the input vectors</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INSERT_SUBVECTOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">INSERT_SUBVECTOR(VECTOR1, VECTOR2, IDX)</a> - Returns a vector with VECTOR2 inserted into VECTOR1</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTRACT_SUBVECTOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">EXTRACT_SUBVECTOR(VECTOR, IDX)</a> - Returns a subvector from VECTOR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECTOR_DEINTERLEAVE<a id="a22ea9cec080dd5f4f47ba234c2f59110af5b978686fa3409a40ce3abe447db653"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110af5b978686fa3409a40ce3abe447db653">VECTOR_DEINTERLEAVE(VEC1, VEC2)</a> - Returns two vectors with all input and output vectors having the same type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECTOR_INTERLEAVE<a id="a22ea9cec080dd5f4f47ba234c2f59110a7314e9c42c2c93e3786adfd12aee39d7"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a7314e9c42c2c93e3786adfd12aee39d7">VECTOR_INTERLEAVE(VEC1, VEC2)</a> - Returns two vectors with all input and output vectors having the same type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECTOR_REVERSE<a id="a22ea9cec080dd5f4f47ba234c2f59110aad7728df1343db6f976857aaa2e945ee"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110aad7728df1343db6f976857aaa2e945ee">VECTOR_REVERSE(VECTOR)</a> - Returns a vector, of the same type as VECTOR, whose elements are shuffled using the following algorithm: RESULT[i] = VECTOR[VECTOR.ElementCount - 1 - i]</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECTOR_SHUFFLE<a id="a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">VECTOR_SHUFFLE(VEC1, VEC2)</a> - Returns a vector, of the same type as VEC1/VEC2</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECTOR_SPLICE<a id="a22ea9cec080dd5f4f47ba234c2f59110ad55a17543ef86f6d46aebb45028a9067"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110ad55a17543ef86f6d46aebb45028a9067">VECTOR_SPLICE(VEC1, VEC2, IMM)</a> - Returns a subvector of the same type as VEC1/VEC2 from <a href="#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">CONCAT_VECTORS(VEC1, VEC2)</a>, based on the IMM in two ways</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALAR_TO_VECTOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">SCALAR_TO_VECTOR(VAL)</a> - This represents the operation of loading a scalar value into element 0 of the resultant vector type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPLAT_VECTOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">SPLAT_VECTOR(VAL)</a> - Returns a vector with the scalar value VAL duplicated in all lanes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPLAT_VECTOR_PARTS<a id="a22ea9cec080dd5f4f47ba234c2f59110ad358f0823a936bde7edd419ab1058bd4"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110ad358f0823a936bde7edd419ab1058bd4">SPLAT_VECTOR_PARTS(SCALAR1, SCALAR2, ...)</a> - Returns a vector with the scalar values joined together and then duplicated in all lanes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STEP_VECTOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a73ec2109e5056d5cb07dad24ddd848c3"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a73ec2109e5056d5cb07dad24ddd848c3">STEP_VECTOR(IMM)</a> - Returns a scalable vector whose lanes are comprised of a linear sequence of unsigned values starting from 0 with a step of IMM, where IMM must be a TargetConstant with type equal to the vector element type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECTOR_COMPRESS<a id="a22ea9cec080dd5f4f47ba234c2f59110adb06c311948bd9fb944ab3c433138181"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110adb06c311948bd9fb944ab3c433138181">VECTOR_COMPRESS(Vec, Mask, Passthru)</a> consecutively place vector elements based on mask e.g., vec = {A, B, C, D} and mask = {1, 0, 1, 0} --&gt; {A, C, ?</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHU<a id="a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5"></a></td>
<td class="doxyEnumItemDescription">MULHU/MULHS - Multiply high - Multiply two integers of type iN, producing an unsigned/signed value of type i[2*N], then return the top part</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULHS<a id="a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVGFLOORS<a id="a22ea9cec080dd5f4f47ba234c2f59110acc5444f2e2933b551e3afbdd93a9bfc8"></a></td>
<td class="doxyEnumItemDescription">AVGFLOORS/AVGFLOORU - Averaging add - Add two integers using an integer of type i[N+1], halving the result by shifting it one bit right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVGFLOORU<a id="a22ea9cec080dd5f4f47ba234c2f59110a5096628a43b16ff34ace64193ded1c93"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVGCEILS<a id="a22ea9cec080dd5f4f47ba234c2f59110a55a4b1d94ca6176bcb5449196d67e798"></a></td>
<td class="doxyEnumItemDescription">AVGCEILS/AVGCEILU - Rounding averaging add - Add two integers using an integer of type i[N+2], add 1 and halve the result by shifting it one bit right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVGCEILU<a id="a22ea9cec080dd5f4f47ba234c2f59110a8489c40b1b3f92b0c4fc98d06099c441"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABDS<a id="a22ea9cec080dd5f4f47ba234c2f59110af798622367e75c5536666dbfec5d5ea3"></a></td>
<td class="doxyEnumItemDescription">ABDS/ABDU - Absolute difference - Return the absolute difference between two numbers interpreted as signed/unsigned</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABDU<a id="a22ea9cec080dd5f4f47ba234c2f59110aff129f5ab4fbc8279e7aaacb45f840b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMIN<a id="a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70"></a></td>
<td class="doxyEnumItemDescription">[US]{MIN/MAX} - Binary minimum or maximum of signed or unsigned integers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMAX<a id="a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMIN<a id="a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMAX<a id="a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCMP<a id="a22ea9cec080dd5f4f47ba234c2f59110ac9cda41d5b1ac3a0babb77b881b506eb"></a></td>
<td class="doxyEnumItemDescription">[US]CMP - 3-way comparison of signed or unsigned integers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UCMP<a id="a22ea9cec080dd5f4f47ba234c2f59110a482ae65625bd4d6059f7259b88ac4dbc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AND<a id="a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2"></a></td>
<td class="doxyEnumItemDescription">Bitwise operators - logical and, logical or, logical xor</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OR<a id="a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ABS<a id="a22ea9cec080dd5f4f47ba234c2f59110a35c1cf0dd553444732dba8e8b9be0f6b"></a></td>
<td class="doxyEnumItemDescription">ABS - Determine the unsigned absolute value of a signed integer value of the same bitwidth</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHL<a id="a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997"></a></td>
<td class="doxyEnumItemDescription">Shift and rotation operations</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRA<a id="a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRL<a id="a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTL<a id="a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTR<a id="a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSHL<a id="a22ea9cec080dd5f4f47ba234c2f59110a822b0d02b601898e2d6db5b39e12cc8a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSHR<a id="a22ea9cec080dd5f4f47ba234c2f59110a874350de5b4f6b8f4db13940e17ed81b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSWAP<a id="a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994"></a></td>
<td class="doxyEnumItemDescription">Byte Swap and Counting operators</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTTZ<a id="a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTLZ<a id="a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTPOP<a id="a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITREVERSE<a id="a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARITY<a id="a22ea9cec080dd5f4f47ba234c2f59110aa47439d20ce0879ea68ca293e018b4f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTTZ_ZERO_UNDEF<a id="a22ea9cec080dd5f4f47ba234c2f59110a601e66a26efd05520f7cb26aef3af340"></a></td>
<td class="doxyEnumItemDescription">Bit counting operators with an undefined result for zero inputs</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTLZ_ZERO_UNDEF<a id="a22ea9cec080dd5f4f47ba234c2f59110a0340c8d57d1dcebc43a00412989583d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SELECT<a id="a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(COND, TRUEVAL, FALSEVAL)</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSELECT<a id="a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c"></a></td>
<td class="doxyEnumItemDescription">Select with a vector condition (op #0) and two vector operands (ops #1 and #2), returning a vector result</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SELECT_CC<a id="a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3"></a></td>
<td class="doxyEnumItemDescription">Select with condition operator - This selects between a true value and a false value (ops #2 and #3) based on the boolean result of comparing the lhs and rhs (ops #0 and #1) of a conditional expression with the condition code in op #4, a <a href="/web-llvm/docs/api/classes/llvm/condcodesdnode">CondCodeSDNode</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC<a id="a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0"></a></td>
<td class="doxyEnumItemDescription">SetCC operator - This evaluates to a true value iff the condition is true</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCCCARRY<a id="a22ea9cec080dd5f4f47ba234c2f59110a6bb33e400f29724907dc27ced04e9038"></a></td>
<td class="doxyEnumItemDescription">Like SetCC, ops #0 and #1 are the LHS and RHS operands to compare, but op #2 is a boolean indicating if there is an incoming carry</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHL_PARTS<a id="a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f"></a></td>
<td class="doxyEnumItemDescription">SHL_PARTS/SRA_PARTS/SRL_PARTS - These operators are used for expanded integer shift operations</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRA_PARTS<a id="a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRL_PARTS<a id="a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIGN_EXTEND<a id="a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602"></a></td>
<td class="doxyEnumItemDescription">Conversion operators</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZERO_EXTEND<a id="a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e"></a></td>
<td class="doxyEnumItemDescription">ZERO_EXTEND - Used for integer types, zeroing the new bits</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANY_EXTEND<a id="a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d"></a></td>
<td class="doxyEnumItemDescription">ANY_EXTEND - Used for integer types. The high bits are undefined</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRUNCATE<a id="a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3"></a></td>
<td class="doxyEnumItemDescription">TRUNCATE - Completely drop the high bits</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRUNCATE_SSAT_S<a id="a22ea9cec080dd5f4f47ba234c2f59110af78365e835dbc10df18c1cd5d8853fd0"></a></td>
<td class="doxyEnumItemDescription">TRUNCATE_[SU]SAT_[SU] - Truncate for saturated operand [SU] located in middle, prefix for <span class="doxyComputerOutput">SAT</span> means indicates whether existing truncate target was a signed operation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRUNCATE_SSAT_U<a id="a22ea9cec080dd5f4f47ba234c2f59110a694c9a71596643f6ddd4ee767666cf43"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRUNCATE_USAT_U<a id="a22ea9cec080dd5f4f47ba234c2f59110af81ec85e716e986c5555135612f62b29"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SINT_TO_FP<a id="a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2"></a></td>
<td class="doxyEnumItemDescription">[SU]INT_TO_FP - These operators convert integers (whose interpreted sign depends on the first letter) to floating point</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UINT_TO_FP<a id="a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIGN_EXTEND_INREG<a id="a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e"></a></td>
<td class="doxyEnumItemDescription">SIGN_EXTEND_INREG - This operator atomically performs a SHL/SRA pair to sign extend a small value in a large integer register (e.g</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANY_EXTEND_VECTOR_INREG<a id="a22ea9cec080dd5f4f47ba234c2f59110aaa275bf149ab5df1067cfb721936ecbc"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110aaa275bf149ab5df1067cfb721936ecbc">ANY_EXTEND_VECTOR_INREG(Vector)</a> - This operator represents an in-register any-extension of the low lanes of an integer vector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIGN_EXTEND_VECTOR_INREG<a id="a22ea9cec080dd5f4f47ba234c2f59110a3893859b5caa079593b9bf91b96e05fb"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a3893859b5caa079593b9bf91b96e05fb">SIGN_EXTEND_VECTOR_INREG(Vector)</a> - This operator represents an in-register sign-extension of the low lanes of an integer vector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZERO_EXTEND_VECTOR_INREG<a id="a22ea9cec080dd5f4f47ba234c2f59110adf7f4fc30c272a1987e075d7470df84c"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110adf7f4fc30c272a1987e075d7470df84c">ZERO_EXTEND_VECTOR_INREG(Vector)</a> - This operator represents an in-register zero-extension of the low lanes of an integer vector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_SINT<a id="a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210"></a></td>
<td class="doxyEnumItemDescription">FP_TO_[US]INT - Convert a floating point value to a signed or unsigned integer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_UINT<a id="a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_SINT_SAT<a id="a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee"></a></td>
<td class="doxyEnumItemDescription">FP_TO_[US]INT_SAT - Convert floating point value in operand 0 to a signed or unsigned scalar integer type given in operand 1 with the following semantics:</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_UINT_SAT<a id="a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_ROUND<a id="a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb"></a></td>
<td class="doxyEnumItemDescription">X = <a href="#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">FP_ROUND(Y, TRUNC)</a> - Rounding 'Y' from a larger floating point type down to the precision of the destination VT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_ROUNDING<a id="a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973"></a></td>
<td class="doxyEnumItemDescription">Returns current rounding mode: -1 Undefined 0 Round to 0 1 Round to nearest, ties to even 2 Round to +inf 3 Round to -inf 4 Round to nearest, ties to zero Other values are target dependent</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SET_ROUNDING<a id="a22ea9cec080dd5f4f47ba234c2f59110a4fe6c878350458de2c3182392f830988"></a></td>
<td class="doxyEnumItemDescription">Set rounding mode</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_EXTEND<a id="a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d"></a></td>
<td class="doxyEnumItemDescription">X = <a href="#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">FP_EXTEND(Y)</a> - Extend a smaller FP type into a larger FP type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITCAST<a id="a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7"></a></td>
<td class="doxyEnumItemDescription">BITCAST - This operator converts between integer, vector and FP values, as if the value was stored to memory with one type and loaded from the same address with the other type (or equivalently for vector format conversions, etc)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDRSPACECAST<a id="a22ea9cec080dd5f4f47ba234c2f59110ae221016e72ad6632377ef55f9e0e4f61"></a></td>
<td class="doxyEnumItemDescription">ADDRSPACECAST - This operator converts between pointers of different address spaces</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP16_TO_FP<a id="a22ea9cec080dd5f4f47ba234c2f59110a3e12fcc9960ef3bf0ae5876382d4c66f"></a></td>
<td class="doxyEnumItemDescription">FP16_TO_FP, FP_TO_FP16 - These operators are used to perform promotions and truncation for half-precision (16 bit) floating numbers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_FP16<a id="a22ea9cec080dd5f4f47ba234c2f59110a38f379e4fddf750c36f1323a04d12171"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP16_TO_FP<a id="a22ea9cec080dd5f4f47ba234c2f59110a8be8417e323644ecd854ce67c362a850"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP_TO_FP16<a id="a22ea9cec080dd5f4f47ba234c2f59110a8a54f717e10fab9c9821196fc882cc11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BF16_TO_FP<a id="a22ea9cec080dd5f4f47ba234c2f59110abdae7178e801a788f47e55ad3db3ee6a"></a></td>
<td class="doxyEnumItemDescription">BF16_TO_FP, FP_TO_BF16 - These operators are used to perform promotions and truncation for bfloat16</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_TO_BF16<a id="a22ea9cec080dd5f4f47ba234c2f59110a0bb173b5a879225092abdeaba1394839"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_BF16_TO_FP<a id="a22ea9cec080dd5f4f47ba234c2f59110ab60b57f9ecb68fa5f4445ec18e835a64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRICT_FP_TO_BF16<a id="a22ea9cec080dd5f4f47ba234c2f59110ac98e3abb765d6786634ba0656ae83e17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNEG<a id="a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a"></a></td>
<td class="doxyEnumItemDescription">Perform various unary floating-point operations inspired by libm</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FABS<a id="a22ea9cec080dd5f4f47ba234c2f59110a2b4d07600495a563319d6a3dda8dc44d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSQRT<a id="a22ea9cec080dd5f4f47ba234c2f59110ae1118ddac1ce0af8e9f7cc16c9e94fc0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCBRT<a id="a22ea9cec080dd5f4f47ba234c2f59110a85c9608f4afa54b644dc76228a8f7261"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSIN<a id="a22ea9cec080dd5f4f47ba234c2f59110ad46ae9fdfe20cd04f7fda7ccbb937543"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCOS<a id="a22ea9cec080dd5f4f47ba234c2f59110a9133d7cfb6a66404ff7757b699bc3941"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FTAN<a id="a22ea9cec080dd5f4f47ba234c2f59110a9edaaccfce9ddf3113d737686f0a019e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FASIN<a id="a22ea9cec080dd5f4f47ba234c2f59110a62bcf7e98c551eddfe028e6ad6565215"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FACOS<a id="a22ea9cec080dd5f4f47ba234c2f59110a3bd30fa450385ee74c9b275ba5f8d1c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FATAN<a id="a22ea9cec080dd5f4f47ba234c2f59110a3ec6f3b872819089911699ea156e6fc7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSINH<a id="a22ea9cec080dd5f4f47ba234c2f59110ad8c5012dcc326bb95fc45b1f2e80dbda"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCOSH<a id="a22ea9cec080dd5f4f47ba234c2f59110a30da9fef8027cdf8a719bdacb5300df8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FTANH<a id="a22ea9cec080dd5f4f47ba234c2f59110a7d675a8da9b3fa2ee3a15b3932eef38a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPOW<a id="a22ea9cec080dd5f4f47ba234c2f59110a1a6952b1572a4ce241cc3cf45a9ab071"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPOWI<a id="a22ea9cec080dd5f4f47ba234c2f59110a66b7368b776f6aff492cf970db3df548"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLDEXP<a id="a22ea9cec080dd5f4f47ba234c2f59110a455f49e18d470b97cd293acd7fbdf169"></a></td>
<td class="doxyEnumItemDescription">FLDEXP - ldexp, inspired by libm (op0 * 2**op1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FATAN2<a id="a22ea9cec080dd5f4f47ba234c2f59110a2a69cbb602c143642c1fe014bce6d44d"></a></td>
<td class="doxyEnumItemDescription">FATAN2 - atan2, inspired by libm</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFREXP<a id="a22ea9cec080dd5f4f47ba234c2f59110ad9e6c8353bc9d023077590083cfce89c"></a></td>
<td class="doxyEnumItemDescription">FFREXP - frexp, extract fractional and exponent component of a floating-point value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLOG<a id="a22ea9cec080dd5f4f47ba234c2f59110ac82d37f93ae4420659acdd03f79b15e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLOG2<a id="a22ea9cec080dd5f4f47ba234c2f59110a558dc710055f9d60cc3c0893bc29a72d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLOG10<a id="a22ea9cec080dd5f4f47ba234c2f59110a0d05d4a5cd10a46f69f9e62d49d275bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FEXP<a id="a22ea9cec080dd5f4f47ba234c2f59110ad49a46d391f73aa96002adbdd0cf03f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FEXP2<a id="a22ea9cec080dd5f4f47ba234c2f59110af3542a99501ffb93cee4aae9d1ec2d05"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FEXP10<a id="a22ea9cec080dd5f4f47ba234c2f59110a37c80ce3312d3fc5b925e326a16fff20"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCEIL<a id="a22ea9cec080dd5f4f47ba234c2f59110ad56e9199ae3993a09af36ff41d327a11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FTRUNC<a id="a22ea9cec080dd5f4f47ba234c2f59110a1e92ea554489509b0ad970901bcc715b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRINT<a id="a22ea9cec080dd5f4f47ba234c2f59110a68014623710f7a44c808cd412236d6a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FNEARBYINT<a id="a22ea9cec080dd5f4f47ba234c2f59110a2dc876d6cc16ac04376483552292f9f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FROUND<a id="a22ea9cec080dd5f4f47ba234c2f59110a87b7dd3d6a9b68d1558fc6b4706708b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FROUNDEVEN<a id="a22ea9cec080dd5f4f47ba234c2f59110ab3cb85375f983765b93341d57a2f3838"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFLOOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a4336c27826676e1ef61383cafa999219"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LROUND<a id="a22ea9cec080dd5f4f47ba234c2f59110adb1de74d602ef905e06785e0052b55bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLROUND<a id="a22ea9cec080dd5f4f47ba234c2f59110a4e2fdf7d4dbc04469cf6a920262c82c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LRINT<a id="a22ea9cec080dd5f4f47ba234c2f59110a05f23e2cd900dc8f1dbf6702ab12423b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLRINT<a id="a22ea9cec080dd5f4f47ba234c2f59110a25eed965b36ce43fc8b9daa2774dfad8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINNUM<a id="a22ea9cec080dd5f4f47ba234c2f59110a9f59cc264907eb86e29564d5f6a5b213"></a></td>
<td class="doxyEnumItemDescription">FMINNUM/FMAXNUM - Perform floating-point minimum or maximum on two values</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXNUM<a id="a22ea9cec080dd5f4f47ba234c2f59110a632dd4bb044d5cd11f671d176ef495f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINNUM_IEEE<a id="a22ea9cec080dd5f4f47ba234c2f59110a907932b29f929b1827b1b93171dcaa3c"></a></td>
<td class="doxyEnumItemDescription">FMINNUM_IEEE/FMAXNUM_IEEE - Perform floating-point minimumNumber or maximumNumber on two values, following IEEE-754 definitions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXNUM_IEEE<a id="a22ea9cec080dd5f4f47ba234c2f59110a25e670389809910f59726e8a11fa82e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINIMUM<a id="a22ea9cec080dd5f4f47ba234c2f59110ac27a43f98abb2d1ee2f2ce99a0b34b36"></a></td>
<td class="doxyEnumItemDescription">FMINIMUM/FMAXIMUM - NaN-propagating minimum/maximum that also treat -0.0 as less than 0.0</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXIMUM<a id="a22ea9cec080dd5f4f47ba234c2f59110a3dfd1b187d121c0e214698eef1c20f53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMINIMUMNUM<a id="a22ea9cec080dd5f4f47ba234c2f59110af7691f41e448fefca844f687edabfb69"></a></td>
<td class="doxyEnumItemDescription">FMINIMUMNUM/FMAXIMUMNUM - minimumnum/maximumnum that is same with FMINNUM_IEEE and FMAXNUM_IEEE besides if either operand is sNaN</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMAXIMUMNUM<a id="a22ea9cec080dd5f4f47ba234c2f59110add34b1738b7bb2c298f92f1b7b62ce0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSINCOS<a id="a22ea9cec080dd5f4f47ba234c2f59110a6ba8fc92ee5081d3e533cb5322f74f29"></a></td>
<td class="doxyEnumItemDescription">FSINCOS - Compute both fsin and fcos as a single operation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_FPENV<a id="a22ea9cec080dd5f4f47ba234c2f59110a8ca22b32a18bb7959b6f6f9b18d14ec0"></a></td>
<td class="doxyEnumItemDescription">Gets the current floating-point environment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SET_FPENV<a id="a22ea9cec080dd5f4f47ba234c2f59110a07fcb2d341fc6f3db309618b30e358a8"></a></td>
<td class="doxyEnumItemDescription">Sets the current floating-point environment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RESET_FPENV<a id="a22ea9cec080dd5f4f47ba234c2f59110a23914569caa5dbe0d340c3fbfc277efc"></a></td>
<td class="doxyEnumItemDescription">Set floating-point environment to default state</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_FPENV_MEM<a id="a22ea9cec080dd5f4f47ba234c2f59110ac7e6de3a23c50c3f48e30e3a644a16aa"></a></td>
<td class="doxyEnumItemDescription">Gets the current floating-point environment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SET_FPENV_MEM<a id="a22ea9cec080dd5f4f47ba234c2f59110af695708f70bdd710c8fda5c4570711d7"></a></td>
<td class="doxyEnumItemDescription">Sets the current floating point environment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_FPMODE<a id="a22ea9cec080dd5f4f47ba234c2f59110a8ba51b127e01a9e6412e7629c70ec4a1"></a></td>
<td class="doxyEnumItemDescription">Reads the current dynamic floating-point control modes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SET_FPMODE<a id="a22ea9cec080dd5f4f47ba234c2f59110a26b34eddab8969a79fd3cda432471809"></a></td>
<td class="doxyEnumItemDescription">Sets the current dynamic floating-point control modes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RESET_FPMODE<a id="a22ea9cec080dd5f4f47ba234c2f59110a386314479bc7963a544ed142866e7ece"></a></td>
<td class="doxyEnumItemDescription">Sets default dynamic floating-point control modes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOAD<a id="a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159"></a></td>
<td class="doxyEnumItemDescription">LOAD and STORE have token chains as their first operand, then the same operands as an LLVM load/store instruction, then an offset node that is added / subtracted from the base pointer to form the address (for indexed memory ops)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STORE<a id="a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DYNAMIC_STACKALLOC<a id="a22ea9cec080dd5f4f47ba234c2f59110aa71ac22470bf853868fe6b39a25bac72"></a></td>
<td class="doxyEnumItemDescription">DYNAMIC_STACKALLOC - Allocate some number of bytes on the stack aligned to a specified boundary</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR<a id="a22ea9cec080dd5f4f47ba234c2f59110a5be7fb35e0f523af6c939fba303403df"></a></td>
<td class="doxyEnumItemDescription">Control flow instructions. These all have token chains</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRIND<a id="a22ea9cec080dd5f4f47ba234c2f59110a716765ad6ce5be71f987cd2097b1cdbf"></a></td>
<td class="doxyEnumItemDescription">BRIND - Indirect branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_JT<a id="a22ea9cec080dd5f4f47ba234c2f59110a716d19ebad1927a2e8dd5fe3f951f882"></a></td>
<td class="doxyEnumItemDescription">BR_JT - Jumptable branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JUMP_TABLE_DEBUG_INFO<a id="a22ea9cec080dd5f4f47ba234c2f59110a18e14419991d3b0ace7690a67c564192"></a></td>
<td class="doxyEnumItemDescription">JUMP_TABLE_DEBUG_INFO - Jumptable debug info</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRCOND<a id="a22ea9cec080dd5f4f47ba234c2f59110ae8167e4f6fa1bfb30f074ba620b81782"></a></td>
<td class="doxyEnumItemDescription">BRCOND - Conditional branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_CC<a id="a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb"></a></td>
<td class="doxyEnumItemDescription">BR_CC - Conditional branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INLINEASM<a id="a22ea9cec080dd5f4f47ba234c2f59110ae35d57f3c020672748fcc95607348986"></a></td>
<td class="doxyEnumItemDescription">INLINEASM - Represents an inline asm block</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INLINEASM_BR<a id="a22ea9cec080dd5f4f47ba234c2f59110ab969e7d43eb37a0398b5ded23bccc136"></a></td>
<td class="doxyEnumItemDescription">INLINEASM_BR - Branching version of inline asm. Used by asm-goto</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_LABEL<a id="a22ea9cec080dd5f4f47ba234c2f59110a4c1f7e0dc3af92b9cfd0d5d11231ddc1"></a></td>
<td class="doxyEnumItemDescription">EH_LABEL - Represents a label in mid basic block used to track locations needed for debug and exception handling tables</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ANNOTATION_LABEL<a id="a22ea9cec080dd5f4f47ba234c2f59110a4f51e138b5e660cb9cce3ae4352c5f16"></a></td>
<td class="doxyEnumItemDescription">ANNOTATION_LABEL - Represents a mid basic block label used by annotations</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CATCHRET<a id="a22ea9cec080dd5f4f47ba234c2f59110aec1078d911aabd272954b9125eaee6df"></a></td>
<td class="doxyEnumItemDescription">CATCHRET - Represents a return from a catch block funclet</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLEANUPRET<a id="a22ea9cec080dd5f4f47ba234c2f59110a8b3de6401453f275f010559d01834826"></a></td>
<td class="doxyEnumItemDescription">CLEANUPRET - Represents a return from a cleanup block funclet</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STACKSAVE<a id="a22ea9cec080dd5f4f47ba234c2f59110a031ce694e40832d40a163d7254a8df14"></a></td>
<td class="doxyEnumItemDescription">STACKSAVE - STACKSAVE has one operand, an input chain</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STACKRESTORE<a id="a22ea9cec080dd5f4f47ba234c2f59110a023a9de787026fe61b024476bf9c32cb"></a></td>
<td class="doxyEnumItemDescription">STACKRESTORE has two operands, an input chain and a pointer to restore to it returns an output chain</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALLSEQ_START<a id="a22ea9cec080dd5f4f47ba234c2f59110af423387cec5c9f7be16028b25a0dcfe7"></a></td>
<td class="doxyEnumItemDescription">CALLSEQ_START/CALLSEQ_END - These operators mark the beginning and end of a call sequence, and carry arbitrary information that target might want to know</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALLSEQ_END<a id="a22ea9cec080dd5f4f47ba234c2f59110a6feb9a82882ea426db5b62f3f69f63a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VAARG<a id="a22ea9cec080dd5f4f47ba234c2f59110ae77d03846b31c41c4860bcd96d780a78"></a></td>
<td class="doxyEnumItemDescription">VAARG - VAARG has four operands: an input chain, a pointer, a SRCVALUE, and the alignment</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VACOPY<a id="a22ea9cec080dd5f4f47ba234c2f59110a804c1960ac64628cdd1f74d7de885284"></a></td>
<td class="doxyEnumItemDescription">VACOPY - VACOPY has 5 operands: an input chain, a destination pointer, a source pointer, a SRCVALUE for the destination, and a SRCVALUE for the source</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VAEND<a id="a22ea9cec080dd5f4f47ba234c2f59110a1aadbb14ab26b74d841ac003363e3a5d"></a></td>
<td class="doxyEnumItemDescription">VAEND, VASTART - VAEND and VASTART have three operands: an input chain, pointer, and a SRCVALUE</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VASTART<a id="a22ea9cec080dd5f4f47ba234c2f59110adfe32beaa596a1512b17e66b46e773ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PREALLOCATED_SETUP<a id="a22ea9cec080dd5f4f47ba234c2f59110a57cfe3bac8296e41e04ea4d072f0f33f"></a></td>
<td class="doxyEnumItemDescription">PREALLOCATED_SETUP - This has 2 operands: an input chain and a SRCVALUE with the preallocated call <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PREALLOCATED_ARG<a id="a22ea9cec080dd5f4f47ba234c2f59110a706221302cd12c7a44b7e122e57002a1"></a></td>
<td class="doxyEnumItemDescription">PREALLOCATED_ARG - This has 3 operands: an input chain, a SRCVALUE with the preallocated call <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, and a constant int</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRCVALUE<a id="a22ea9cec080dd5f4f47ba234c2f59110a4ade56991bf359914e6d59693d9526cc"></a></td>
<td class="doxyEnumItemDescription">SRCVALUE - This is a node type that holds a Value* that is used to make reference to a value in the LLVM IR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MDNODE_SDNODE<a id="a22ea9cec080dd5f4f47ba234c2f59110a0420c9663564b439d19509ff77eb6845"></a></td>
<td class="doxyEnumItemDescription">MDNODE_SDNODE - This is a node that holdes an MDNode*, which is used to reference metadata in the IR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCMARKER<a id="a22ea9cec080dd5f4f47ba234c2f59110ab69fa9bf3bc67ac80d433dff2765e415"></a></td>
<td class="doxyEnumItemDescription">PCMARKER - This corresponds to the pcmarker intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READCYCLECOUNTER<a id="a22ea9cec080dd5f4f47ba234c2f59110ac43f9bea13e29622bbf18c861b52144d"></a></td>
<td class="doxyEnumItemDescription">READCYCLECOUNTER - This corresponds to the readcyclecounter intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READSTEADYCOUNTER<a id="a22ea9cec080dd5f4f47ba234c2f59110a59117a4be6a5e335b41aecda777fd679"></a></td>
<td class="doxyEnumItemDescription">READSTEADYCOUNTER - This corresponds to the readfixedcounter intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HANDLENODE<a id="a22ea9cec080dd5f4f47ba234c2f59110ab508f11d38b4596451c6333f7510daa3"></a></td>
<td class="doxyEnumItemDescription">HANDLENODE node - Used as a handle for various purposes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INIT_TRAMPOLINE<a id="a22ea9cec080dd5f4f47ba234c2f59110a4534a6db2862a28324932a8ea1cb54d6"></a></td>
<td class="doxyEnumItemDescription">INIT_TRAMPOLINE - This corresponds to the init_trampoline intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADJUST_TRAMPOLINE<a id="a22ea9cec080dd5f4f47ba234c2f59110af7bfad446dfd85837fe7ff904ebb1aff"></a></td>
<td class="doxyEnumItemDescription">ADJUST_TRAMPOLINE - This corresponds to the adjust_trampoline intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRAP<a id="a22ea9cec080dd5f4f47ba234c2f59110ac5fb8808f3dcb9f0a83f1fc2e7747485"></a></td>
<td class="doxyEnumItemDescription">TRAP - Trapping instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DEBUGTRAP<a id="a22ea9cec080dd5f4f47ba234c2f59110a967fcb624e84458e135a763d1c11346a"></a></td>
<td class="doxyEnumItemDescription">DEBUGTRAP - Trap intended to get the attention of a debugger</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UBSANTRAP<a id="a22ea9cec080dd5f4f47ba234c2f59110aa110c932d4027fe4043cceb7a579e5ee"></a></td>
<td class="doxyEnumItemDescription">UBSANTRAP - Trap with an immediate describing the kind of sanitizer failure</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PREFETCH<a id="a22ea9cec080dd5f4f47ba234c2f59110a691a4c9004e9bd04d1c0bebc5df57443"></a></td>
<td class="doxyEnumItemDescription">PREFETCH - This corresponds to a prefetch intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARITH_FENCE<a id="a22ea9cec080dd5f4f47ba234c2f59110a88ce5ee637738fa2a879acebc2d3794c"></a></td>
<td class="doxyEnumItemDescription">ARITH_FENCE - This corresponds to a arithmetic fence intrinsic</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMBARRIER<a id="a22ea9cec080dd5f4f47ba234c2f59110a369074e730a24fabb4216cd37e789e35"></a></td>
<td class="doxyEnumItemDescription">MEMBARRIER - Compiler barrier only; generate a no-op</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_FENCE<a id="a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8"></a></td>
<td class="doxyEnumItemDescription">OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">ATOMIC_FENCE(INCHAIN, ordering, scope)</a> This corresponds to the fence instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD<a id="a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109"></a></td>
<td class="doxyEnumItemDescription">Val, OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7c47226f266248f4b8c155b83601b109">ATOMIC_LOAD(INCHAIN, ptr)</a> This corresponds to "load atomic" instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_STORE<a id="a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8"></a></td>
<td class="doxyEnumItemDescription">OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a1db943abc1bf78a911daeb7b03d81de8">ATOMIC_STORE(INCHAIN, val, ptr)</a> This corresponds to "store atomic" instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_CMP_SWAP<a id="a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67"></a></td>
<td class="doxyEnumItemDescription">
Val, OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">ATOMIC_CMP_SWAP(INCHAIN, ptr, cmp, swap)</a> For double-word atomic operations: ValLo, ValHi, OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">ATOMIC_CMP_SWAP(INCHAIN, ptr, cmpLo, cmpHi,
                                         swapLo, swapHi)</a> This corresponds to the cmpxchg instruction
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_CMP_SWAP_WITH_SUCCESS<a id="a22ea9cec080dd5f4f47ba234c2f59110a30649569b517a279a32fb3b48cc154e0"></a></td>
<td class="doxyEnumItemDescription">Val, Success, OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110a30649569b517a279a32fb3b48cc154e0">ATOMIC_CMP_SWAP_WITH_SUCCESS(INCHAIN, ptr, cmp, swap)</a> N.b</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_SWAP<a id="a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d"></a></td>
<td class="doxyEnumItemDescription">Val, OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">ATOMIC_SWAP(INCHAIN, ptr, amt)</a> Val, OUTCHAIN = ATOMIC_LOAD_[<a href="/web-llvm/docs/api/namespaces/opname">OpName</a>](INCHAIN, ptr, amt) For double-word atomic operations: ValLo, ValHi, OUTCHAIN = <a href="#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">ATOMIC_SWAP(INCHAIN, ptr, amtLo, amtHi)</a> ValLo, ValHi, OUTCHAIN = ATOMIC_LOAD_[<a href="/web-llvm/docs/api/namespaces/opname">OpName</a>](INCHAIN, ptr, amtLo, amtHi) These correspond to the atomicrmw instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_ADD<a id="a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_SUB<a id="a22ea9cec080dd5f4f47ba234c2f59110ac3d12dbff6e50803982d0e92768a1479"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_AND<a id="a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_CLR<a id="a22ea9cec080dd5f4f47ba234c2f59110a8ceaa81a8088781e5efec0886ffe86be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_OR<a id="a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_XOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_NAND<a id="a22ea9cec080dd5f4f47ba234c2f59110a13a3e6402abf972278c6a7d5ee509f9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_MIN<a id="a22ea9cec080dd5f4f47ba234c2f59110a7049708cb0e0703a467b95a506293aec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_MAX<a id="a22ea9cec080dd5f4f47ba234c2f59110a1cf8547d612d954d34aab1d4f78e7fa1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_UMIN<a id="a22ea9cec080dd5f4f47ba234c2f59110a1ff6f20a9255f7a333f4c9d25393674c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_UMAX<a id="a22ea9cec080dd5f4f47ba234c2f59110a9ca44a643714809ef384e7494604db14"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_FADD<a id="a22ea9cec080dd5f4f47ba234c2f59110a48287dae990aa9e29a458373ccd0eadb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_FSUB<a id="a22ea9cec080dd5f4f47ba234c2f59110a6d539343b461a07dde64956266ba808c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_FMAX<a id="a22ea9cec080dd5f4f47ba234c2f59110a05e4a09b0b7a2ec7e9f5e77c8e8153bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_FMIN<a id="a22ea9cec080dd5f4f47ba234c2f59110a830f68bd84f119afe6033acbe7223dfe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_UINC_WRAP<a id="a22ea9cec080dd5f4f47ba234c2f59110aef57c4139e116c75edbe082d40423abc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_UDEC_WRAP<a id="a22ea9cec080dd5f4f47ba234c2f59110abf2a0866e4c386567698502774972acd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_USUB_COND<a id="a22ea9cec080dd5f4f47ba234c2f59110a28a36ed3d71dc4a053f03a5ddb828cb1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATOMIC_LOAD_USUB_SAT<a id="a22ea9cec080dd5f4f47ba234c2f59110a4d8796a5190b7ec09695c9769b2cd4be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MLOAD<a id="a22ea9cec080dd5f4f47ba234c2f59110a112324db3910fea5895514851c387442"></a></td>
<td class="doxyEnumItemDescription">Masked load and store - consecutive vector load and store operations with additional mask operand that prevents memory accesses to the masked-off lanes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSTORE<a id="a22ea9cec080dd5f4f47ba234c2f59110a9add598de9e0a49cbb8fb19adf495051"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MGATHER<a id="a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8"></a></td>
<td class="doxyEnumItemDescription">Masked gather and scatter - load and store operations for a vector of random addresses with additional mask operand that prevents memory accesses to the masked-off lanes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSCATTER<a id="a22ea9cec080dd5f4f47ba234c2f59110ab179d7f42562bbb315a6b0589a25f733"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LIFETIME_START<a id="a22ea9cec080dd5f4f47ba234c2f59110aada0b926e7ebc2bc55d158d4c37bdcca"></a></td>
<td class="doxyEnumItemDescription">This corresponds to the llvm.lifetime</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LIFETIME_END<a id="a22ea9cec080dd5f4f47ba234c2f59110ab49301b20458a7f312a0919e3c8abdb2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FAKE_USE<a id="a22ea9cec080dd5f4f47ba234c2f59110a40c488fd3348cbcfd577368fe96d5c9b"></a></td>
<td class="doxyEnumItemDescription">FAKE_USE represents a use of the operand but does not do anything</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GC_TRANSITION_START<a id="a22ea9cec080dd5f4f47ba234c2f59110a71d133366c40437e06936626b32ba6d8"></a></td>
<td class="doxyEnumItemDescription">GC_TRANSITION_START/GC_TRANSITION_END - These operators mark the beginning and end of GC transition sequence, and carry arbitrary information that target might need for lowering</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GC_TRANSITION_END<a id="a22ea9cec080dd5f4f47ba234c2f59110aee46c58568939eaeaa37ea6001bf432e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GET_DYNAMIC_AREA_OFFSET<a id="a22ea9cec080dd5f4f47ba234c2f59110af5caa395d199fab7e52a63feb73dcb10"></a></td>
<td class="doxyEnumItemDescription">GET_DYNAMIC_AREA_OFFSET - get offset from native SP to the address of the most recent dynamic alloca</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PSEUDO_PROBE<a id="a22ea9cec080dd5f4f47ba234c2f59110ac89c00e941b666bc6ac4ba73713db047"></a></td>
<td class="doxyEnumItemDescription">Pseudo probe for AutoFDO, as a place holder in a basic block to improve the sample counts quality</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSCALE<a id="a22ea9cec080dd5f4f47ba234c2f59110a9b2378721f79f5b72a6398dce97b3a42"></a></td>
<td class="doxyEnumItemDescription"><a href="#a22ea9cec080dd5f4f47ba234c2f59110a9b2378721f79f5b72a6398dce97b3a42">VSCALE(IMM)</a> - Returns the runtime scaling factor used to calculate the number of elements within a scalable vector</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_SEQ_FADD<a id="a22ea9cec080dd5f4f47ba234c2f59110a0b3085a54414d7e8ae7c13f5aeadb9da"></a></td>
<td class="doxyEnumItemDescription">Generic reduction nodes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_SEQ_FMUL<a id="a22ea9cec080dd5f4f47ba234c2f59110aea5fa717771f0a710ecf267df41df98a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_FADD<a id="a22ea9cec080dd5f4f47ba234c2f59110a5e28372b4a60bf792da88d9bc8a8d0bf"></a></td>
<td class="doxyEnumItemDescription">These reductions have relaxed evaluation order semantics, and have a single vector operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_FMUL<a id="a22ea9cec080dd5f4f47ba234c2f59110acf12a2d8b57207c69f92973a1fad520a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_FMAX<a id="a22ea9cec080dd5f4f47ba234c2f59110a323856d66e2d8b1f74e528e3f9fe804d"></a></td>
<td class="doxyEnumItemDescription">FMIN/FMAX nodes can have flags, for NaN/NoNaN variants</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_FMIN<a id="a22ea9cec080dd5f4f47ba234c2f59110a6a8980cf09891ec57cbce010ba119f79"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_FMAXIMUM<a id="a22ea9cec080dd5f4f47ba234c2f59110a355892ae7349b089e0bd24b3087d9c75"></a></td>
<td class="doxyEnumItemDescription">FMINIMUM/FMAXIMUM nodes propatate NaNs and signed zeroes using the <a href="/web-llvm/docs/api/namespaces/llvm/#ae2f7e8a5325f48bbbdaec78e5d6c320c">llvm.minimum</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a38dcdde63d81fbda1d22dffd1a27b343">llvm.maximum</a> semantics</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_FMINIMUM<a id="a22ea9cec080dd5f4f47ba234c2f59110ae526df97bcbda2419acf8cf105c95e8e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_ADD<a id="a22ea9cec080dd5f4f47ba234c2f59110a89a8ec08f6908a989c2d0198ae8851f9"></a></td>
<td class="doxyEnumItemDescription">Integer reductions may have a result type larger than the vector element type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_MUL<a id="a22ea9cec080dd5f4f47ba234c2f59110ab4411563ed11f8df0c6ce7af48ee386f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_AND<a id="a22ea9cec080dd5f4f47ba234c2f59110aa58fe501d4e4fa1b4d19e0ed6b8ee6bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_OR<a id="a22ea9cec080dd5f4f47ba234c2f59110aafd45b465ac59a1a57b8b9862aef6bed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_XOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a9b59fad28698a46c33285083818f6b87"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_SMAX<a id="a22ea9cec080dd5f4f47ba234c2f59110a3c057571f4591494880ec0bba023e0c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_SMIN<a id="a22ea9cec080dd5f4f47ba234c2f59110a11825b59a52b4f5a73c0b877e1ba0e70"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_UMAX<a id="a22ea9cec080dd5f4f47ba234c2f59110a7ce9f75eaf17256deb960b11d1930040"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECREDUCE_UMIN<a id="a22ea9cec080dd5f4f47ba234c2f59110ab67678c3310e505df1a3f7677b14cfb0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STACKMAP<a id="a22ea9cec080dd5f4f47ba234c2f59110ad2904b2502547c3f3d390774f8f548c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PATCHPOINT<a id="a22ea9cec080dd5f4f47ba234c2f59110aa31dda85603496c333a105d53ce62150"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONVERGENCECTRL_ANCHOR<a id="a22ea9cec080dd5f4f47ba234c2f59110a041c4b27006496ee8d8bcdf72e248632"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONVERGENCECTRL_ENTRY<a id="a22ea9cec080dd5f4f47ba234c2f59110a5a787d44a3bcbc803d314896056d9569"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONVERGENCECTRL_LOOP<a id="a22ea9cec080dd5f4f47ba234c2f59110adef60c4df07ee437cd2714f7b18f93f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONVERGENCECTRL_GLUE<a id="a22ea9cec080dd5f4f47ba234c2f59110a509e81081ec1935d3f4f0df758c60e0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXPERIMENTAL_VECTOR_HISTOGRAM<a id="a22ea9cec080dd5f4f47ba234c2f59110ae243ce466d350b1aca774a6ae9aea81c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECTOR_FIND_LAST_ACTIVE<a id="a22ea9cec080dd5f4f47ba234c2f59110a29b106f7933f1b79281c4964bcbee807"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLEAR_CACHE<a id="a22ea9cec080dd5f4f47ba234c2f59110addc63b0e91a7c2b397e7908052d8caf9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUILTIN_OP_END<a id="a22ea9cec080dd5f4f47ba234c2f59110a477ef80c70c7359199eace0e5d3133b1"></a></td>
<td class="doxyEnumItemDescription">BUILTIN_OP_END - This must be the last enum value in this list</td>
</tr>

</table>
</dd>
</dl>


<p>Targets may also define target-dependent operator codes for SDNodes. For example, on x86, these are the enum values in the <a href="/web-llvm/docs/api/namespaces/llvm/x86isd">X86ISD</a> namespace. Targets should aim to use target-independent operators to model their instruction sets as much as possible, and only use target-dependent operators when they have special requirements.</p>


<p>Finally, during and after selection proper, SNodes may use special operator codes that correspond directly with <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> opcodes. These are used to represent selected instructions. See the isMachineOpcode() and getMachineOpcode() member functions of <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### allOperandsUndef() {#a933d79e63e855d7c90bf161355c008ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::allOperandsUndef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the node has at least one operand and all operands of the specified node are <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7c6d8f265e9e16e5debdb9a536b55d3d">ISD::UNDEF</a>.</p>

<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>.</p>

</div>
</div>

### getBaseOpcodeForVP() {#a67022d78a6d8ee4377558da9ff259b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::ISD::getBaseOpcodeForVP (unsigned Opcode, bool hasFPExcept)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Translate this VP Opcode to its corresponding non-VP Opcode.</p>

<p>Declaration at line 1526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa6d0d760dd7360d7039c76c59f96000e">llvm::VPMatchContext::getRootBaseOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa5e728389b60e4210dc8e60dc114ee56">llvm::VPMatchContext::match</a>.</p>

</div>
</div>

### getExtForLoadExtType() {#a2fdb5c9abf8403d4dbf0d8ae59d89916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::NodeType llvm::ISD::getExtForLoadExtType (bool IsFP, <a href="#ad4d48171b87ca51ff54c10a436bac4d7">LoadExtType</a> ExtType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">ANY_EXTEND</a>, <a href="#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">EXTLOAD</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">FP_EXTEND</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">SEXTLOAD</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">SIGN_EXTEND</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">ZERO_EXTEND</a> and <a href="#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">ZEXTLOAD</a>.</p>

</div>
</div>

### getInverseMinMaxOpcode() {#ab0dd9a8bb9b1e116d0a0c3c63a92c64c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::NodeType llvm::ISD::getInverseMinMaxOpcode (unsigned MinMaxOpc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a <span class="doxyComputerOutput">MinMaxOpc</span> of <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::(U|S)MIN or <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::(U|S)MAX, returns <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::(U|S)MAX and <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a>::(U|S)MIN, respectively.</p>

<p>Declaration at line 1504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">SMAX</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">SMIN</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">UMAX</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">UMIN</a>.</p>

</div>
</div>

### getSetCCAndOperation() {#a06081b690c5f0c0be1e6c520585c2b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::CondCode llvm::ISD::getSetCCAndOperation (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Op1, <a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Op2, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the result of a logical AND between different comparisons of identical values: ((X op1 Y) &amp; (X op2 Y)).</p>


<p>This function returns SETCC_INVALID if it is not possible to represent the resultant comparison.</p>


<p>Declaration at line 1714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acfffc940cba73e9a61a83b6431d0a5f5">isSignedOp</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07aeded54fe1be320194e9ff0f5825df0e5">SETCC_INVALID</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">SETEQ</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07ae258b87332b47d96bdf47e4cd915f9ea">SETFALSE</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a08c31033acfb9d6f0bc4a8a82cc26862">SETOEQ</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a31d1e24e08b255d6aa290d67d16ce2c9">SETOGT</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a20257a4d3833cf88afd42caeaed70dde">SETOLT</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a0deb50cd2f3f8e4a94eef4cdf769b848">SETUEQ</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">SETUGT</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">SETULT</a> and <a href="#ac3c3cf58d6d631af6a172457304d3d07a48a334bbe606d5e82c9cd84eaa127b50">SETUO</a>.</p>

</div>
</div>

### getSetCCInverse() {#a5fbc38db5c4f3ef878ab19245d3f381d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::CondCode llvm::ISD::getSetCCInverse (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Op, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the operation corresponding to !(X op Y), where 'op' is a valid SetCC operation.</p>

<p>Declaration at line 1679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a75e7fd2ec2deeecb496f0ed8fb6fe462">getSetCCInverseImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad34d9541b1000d244dd78e0cf23b45ea">combine_CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad0f859410a5e693f74b9c87a59cb9b85">combineSubOfBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab64510f686ff5f453f55707cfd19b07d">combineVSelectWithAllOnesOrZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2126441a7eae0e240bca04767ea42e51">commuteSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a43c0c57ea81b6bb34fdaab6528e09b23">getVectorComparisonOrInvert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5f03e5e8300e8aee8c276ed87ea5cc3b">matchSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ade8c7b6c75d72baebf1ac6d244b9fca5">PerformHWLoopCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#add39487738bda59bdf85c85cb21b7e9a">performSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a434e132c04f973b024b815eaad19165f">performSetccAddFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5956dd38d2c4e11a90da91035b52096d">tryDemorganOfBooleanCondition</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a19494f628ff5bd818b43081b5615420e">trySwapVSelectOperands</a>.</p>

</div>
</div>

### getSetCCOrOperation() {#af1bf9aaeb72d421a1ef57a1a1e6fac92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::CondCode llvm::ISD::getSetCCOrOperation (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Op1, <a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Op2, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the result of a logical OR between different comparisons of identical values: ((X op1 Y) | (X op2 Y)).</p>


<p>This function returns SETCC_INVALID if it is not possible to represent the resultant comparison.</p>


<p>Declaration at line 1709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acfffc940cba73e9a61a83b6431d0a5f5">isSignedOp</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07aeded54fe1be320194e9ff0f5825df0e5">SETCC_INVALID</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">SETNE</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a1a575d029fd38d929229ac39e573e8fc">SETTRUE2</a> and <a href="#ac3c3cf58d6d631af6a172457304d3d07a0d1546187d4d526fcbdd43183689075e">SETUNE</a>.</p>

</div>
</div>

### getSetCCSwappedOperands() {#a9cc23aed232ccdeadbd8648c349236a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::CondCode llvm::ISD::getSetCCSwappedOperands (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Operation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the operation corresponding to (Y op X) when given the operation for (X op Y).</p>

<p>Declaration at line 1704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a5b2aa9d3f9f3a7b2d123fef7c5328b8f">Operation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1ae915deb8e22ab5d8617a090149d0e6">llvm::SelectionDAG::FoldSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af46d1ba5c3f2f00b06659c2ba7dc5c7c">getAArch64Cmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a941dd02b49258c871358410a43355d9f">LowerIntVSETCC_AVX512</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5f03e5e8300e8aee8c276ed87ea5cc3b">matchSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#afe5a99012f6bc8dc0089bfca05eb977a">NegateCC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#af53bcee1fde000ebbebb8fdd83ed6ac9">translateSetCCForBranch</a>.</p>

</div>
</div>

### getUnorderedFlavor() {#a7cfab76369f71a9f62a02815c5aa0777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ISD::getUnorderedFlavor (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Cond)</td>
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

<p>This function returns 0 if the condition is always false if an operand is a NaN, 1 if the condition is always true if the operand is a NaN, and 2 if the condition is undefined if the operand is a NaN.</p>

<p>Definition at line 1673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1ae915deb8e22ab5d8617a090149d0e6">llvm::SelectionDAG::FoldSetCC</a>.</p>

</div>
</div>

### getVecReduceBaseOpcode() {#ace75a0fc6736a8bf8b8187083078354d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::NodeType llvm::ISD::getVecReduceBaseOpcode (unsigned VecReduceOpcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get underlying scalar opcode for VECREDUCE opcode.</p>


<p>For example <a href="#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">ISD::AND</a> for <a href="#a22ea9cec080dd5f4f47ba234c2f59110aa58fe501d4e4fa1b4d19e0ed6b8ee6bd">ISD::VECREDUCE_AND</a>.</p>


<p>Declaration at line 1508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">ADD</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">AND</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">FADD</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a3dfd1b187d121c0e214698eef1c20f53">FMAXIMUM</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a632dd4bb044d5cd11f671d176ef495f2">FMAXNUM</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110ac27a43f98abb2d1ee2f2ce99a0b34b36">FMINIMUM</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a9f59cc264907eb86e29564d5f6a5b213">FMINNUM</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">FMUL</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">MUL</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">OR</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">SMAX</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">SMIN</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">UMAX</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">UMIN</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a89a8ec08f6908a989c2d0198ae8851f9">VECREDUCE_ADD</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aa58fe501d4e4fa1b4d19e0ed6b8ee6bd">VECREDUCE_AND</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a5e28372b4a60bf792da88d9bc8a8d0bf">VECREDUCE_FADD</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a323856d66e2d8b1f74e528e3f9fe804d">VECREDUCE_FMAX</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a355892ae7349b089e0bd24b3087d9c75">VECREDUCE_FMAXIMUM</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a6a8980cf09891ec57cbce010ba119f79">VECREDUCE_FMIN</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110ae526df97bcbda2419acf8cf105c95e8e">VECREDUCE_FMINIMUM</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110acf12a2d8b57207c69f92973a1fad520a">VECREDUCE_FMUL</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110ab4411563ed11f8df0c6ce7af48ee386f">VECREDUCE_MUL</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aafd45b465ac59a1a57b8b9862aef6bed">VECREDUCE_OR</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a0b3085a54414d7e8ae7c13f5aeadb9da">VECREDUCE_SEQ_FADD</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aea5fa717771f0a710ecf267df41df98a">VECREDUCE_SEQ_FMUL</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a3c057571f4591494880ec0bba023e0c2">VECREDUCE_SMAX</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a11825b59a52b4f5a73c0b877e1ba0e70">VECREDUCE_SMIN</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7ce9f75eaf17256deb960b11d1930040">VECREDUCE_UMAX</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110ab67678c3310e505df1a3f7677b14cfb0">VECREDUCE_UMIN</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a9b59fad28698a46c33285083818f6b87">VECREDUCE_XOR</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">XOR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>.</p>

</div>
</div>

### getVPExplicitVectorLengthIdx() {#a8d086c45b7e89dc21157d97b9fc150a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::ISD::getVPExplicitVectorLengthIdx (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The operand position of the explicit vector length parameter.</p>

<p>Declaration at line 1523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a14dbf0c55e1b78f05c19e973c5b54dcd">llvm::getAVLPos</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#add54e11ade7b89f177a92e0bdb7dfef0">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a143e8aaa96ce7a17369dcf210b571bb9">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a643df68d072020a2409e6b4c6ffa92ce">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a584096acdf04dc75f08874d08f65bc0d">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa7a5e0450ca0690222a8254d95021660">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a4488f1d748f9fdad23f89b02f75e2e1d">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa5e728389b60e4210dc8e60dc114ee56">llvm::VPMatchContext::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abbfdbb08e7363ae1a09f8f70c8708487">SplitVPOp</a> and <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#ac0cb159579a66c9f3b71d54e75411254">llvm::VPMatchContext::VPMatchContext</a>.</p>

</div>
</div>

### getVPForBaseOpcode() {#a9d44a0b302d0ccccb3aef22380071bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::ISD::getVPForBaseOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Translate this non-VP Opcode to its corresponding VP Opcode.</p>

<p>Declaration at line 1529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#add54e11ade7b89f177a92e0bdb7dfef0">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a143e8aaa96ce7a17369dcf210b571bb9">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a643df68d072020a2409e6b4c6ffa92ce">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a584096acdf04dc75f08874d08f65bc0d">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa7a5e0450ca0690222a8254d95021660">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a4488f1d748f9fdad23f89b02f75e2e1d">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a4a2592cb149a9c5d9aa7f6347e12419d">llvm::VPMatchContext::isOperationLegal</a> and <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a1746b90cd2a50955871260730a4ab400">llvm::VPMatchContext::isOperationLegalOrCustom</a>.</p>

</div>
</div>

### getVPMaskIdx() {#a7437e83b31f58ab47107029f63bd70b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::ISD::getVPMaskIdx (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The operand position of the vector mask.</p>

<p>Declaration at line 1520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab12a9d38978cd2f625970c4d24ba76d5">llvm::getMaskPos</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#add54e11ade7b89f177a92e0bdb7dfef0">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a143e8aaa96ce7a17369dcf210b571bb9">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a643df68d072020a2409e6b4c6ffa92ce">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a584096acdf04dc75f08874d08f65bc0d">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa7a5e0450ca0690222a8254d95021660">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#a4488f1d748f9fdad23f89b02f75e2e1d">llvm::VPMatchContext::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa5e728389b60e4210dc8e60dc114ee56">llvm::VPMatchContext::match</a> and <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#ac0cb159579a66c9f3b71d54e75411254">llvm::VPMatchContext::VPMatchContext</a>.</p>

</div>
</div>

### isBitwiseLogicOp() {#a6b220b2107d211a5db501de58981e214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isBitwiseLogicOp (unsigned Opcode)</td>
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

<p>Whether this is bitwise logic opcode.</p>

<p>Definition at line 1498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">AND</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">OR</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">XOR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-ppciseldagtodag-cpp-/#a286650a821f263cf20160f3c63e43910">anonymous{PPCISelDAGToDAG.cpp}::allUsesExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a14b615dc096b20886abef65f8491e1ed">foldBitOrderCrossLogicOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af911317e022ca63b9987c011c8e9a21b">foldLogicOfShifts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4641b5e45848c460382fd60729bb5fe5">foldLogicTreeOfShifts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aabf69f64aa91bf399d2230d62ef1493e">isLogicOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79a78596a7d54cb3e906428f79199e93">PromoteMaskArithmetic</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac399325c88de95b03c19e68e1229a8f7">llvm::FastISel::selectBinaryOp</a>.</p>

</div>
</div>

### isBuildVectorAllOnes() {#ac78d4df51ca05e4fb1630a01e07de434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isBuildVectorAllOnes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified node is a BUILD_VECTOR where all of the elements are ~0 or undef.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a08b1839785665aed1d6e91dd72764713">isConstantSplatVectorAllOnes</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad300ebbb9f1787468bee5209194857ef">canonicalizeShuffleWithOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7edcca585a58dc42ba5d68fcbc3e912e">checkBitcastSrcVectorSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a24d54706296d70148335f0f4ff621028">combineFAndFNotToFAndn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4b6e33228c180cdc5b3b927e63afcb92">combineOrXorWithSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a19158530c7e8bd08610180be814ec9b1">combinePTESTCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab64510f686ff5f453f55707cfd19b07d">combineVSelectWithAllOnesOrZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a321df2422ee45cfd96e738928fb178f7">combineXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a147fca66ac9f8b920b2a542b9c78a6ee">convertFixedMaskToScalableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa8e7d7856b86905a5ce055fb23d0c9b2">foldVectorXorShiftIntoCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f80d4b8b70f58b247193379a39d5541">foldVectorXorShiftIntoCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aee0563473c2eed4e233b639b9ae36911">getAVX2GatherNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a75c0a729d679d7c1b8504537fbec5840">getGatherNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81759e8ae2c9ab3b98619cce9995ad74">IsNOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a744d14408c0db57df812858803759ba1">LowerBUILD_VECTORvXi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c73954e103eaf84aceb7fc799f4c44a">lowerBuildVectorOfConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1c90d1a6b160241a7ba932f7e4e9aa2f">materializeVectorConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a14fe6050fa67f0e7b01314d5c7586b8e">performXORCombine</a>.</p>

</div>
</div>

### isBuildVectorAllZeros() {#aaac3e239cbdfe15a8e9bad4f8e1e3a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isBuildVectorAllZeros (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified node is a BUILD_VECTOR where all of the elements are 0 or undef.</p>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a531723c97a9c44056fc4996bde57229e">isConstantSplatVectorAllZeros</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac445550f60946bb0bcb26733d7bfbbf8">adjustBitcastSrcVectorSSE1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad300ebbb9f1787468bee5209194857ef">canonicalizeShuffleWithOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7edcca585a58dc42ba5d68fcbc3e912e">checkBitcastSrcVectorSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae222abd7ba47c29a86fc6be7f3dd02fb">combineFaddCFmul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ace3516d005e59a05c7b3ff975d063f23">combineINSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a886d3292e22e113b2f04c1c35811bd0c">combineKSHIFT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ada799c570dd41ead38f73ba71244c2b2">combineLogicBlendIntoConditionalNegate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2a2b06cd0043981c801d852ace83fded">combineMaskedLoadConstantMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4b6e33228c180cdc5b3b927e63afcb92">combineOrXorWithSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a92cb7f91737deedc3c70fb0ec0b70807">combinePMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a19158530c7e8bd08610180be814ec9b1">combinePTESTCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade03879f56390aad1613d54401f911a5">combineShuffleOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a66295c004fc51403028ea1933b66642a">combineVectorShiftVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c6a560bbaa7931f6375fd838fcfbaa8">combineVPMADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab64510f686ff5f453f55707cfd19b07d">combineVSelectWithAllOnesOrZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac21ca860de08b06c8c3d51c536ba0c90">computeZeroableShuffleElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8c5470848197ac902e80545f0d08aa1c">ExtendToType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1c34ea579237aedce7149724afc490ab">insert1BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81759e8ae2c9ab3b98619cce9995ad74">IsNOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac91b7f4570acc6bfdb6c81fd33d0c57a">isNullFPScalarOrVectorConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a6d5b4f84c3dda985bea36681d13bc55b">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9bcc716556b2a8d9c3f06c0a46c243f6">isZeroVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9bcc716556b2a8d9c3f06c0a46c243f6">isZeroVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac500e16c74b6cb60304069a03b41a946">LowerAVXCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a744d14408c0db57df812858803759ba1">LowerBUILD_VECTORvXi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c73954e103eaf84aceb7fc799f4c44a">lowerBuildVectorOfConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a20d2c4e634576e31a243b938a43112af">LowerCONCAT_VECTORSvXi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af682dbf33bab9c483fe52d9edd85422c">LowerMLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#add8099113c1625de3abb0a7cb0da3628">lowerShuffleAsPermuteAndUnpack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abf10af4763fc3f16c6e810e203b343ee">lowerV2X128Shuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab9c1fef093fb9dfcad2e86ddd0a2a4e6">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad0c1ef61c1fa5a02b8d6d66756b35d18">LowerVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac43e54f20b5c565358eec77519811795">matchShuffleAsBlend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1c90d1a6b160241a7ba932f7e4e9aa2f">materializeVectorConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>.</p>

</div>
</div>

### isBuildVectorOfConstantFPSDNodes() {#abf3a86e6cdc4fe3dbd4e618c2f7a64c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isBuildVectorOfConstantFPSDNodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified node is a BUILD_VECTOR node of all <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode">ConstantFPSDNode</a> or undef.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad300ebbb9f1787468bee5209194857ef">canonicalizeShuffleWithOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8dae5a29dc37de048a59e5bab5e30af2">combineFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8c5470848197ac902e80545f0d08aa1c">ExtendToType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a999f6375546ae5d8aeb9024493fc118c">getInvertedVectorForFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a017eaa85d3d8210f593c2c9449336914">isAnyConstantBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b1d42b296c7c720ed353ebe0cb22f38">llvm::SelectionDAG::isConstantFPBuildVectorOrConstantFP</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abce17120537283b4104f8e1a7cad02a2">lowerBUILD_VECTOR</a>.</p>

</div>
</div>

### isBuildVectorOfConstantSDNodes() {#a2f37af786c5ba90887c1b4ec137a066c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isBuildVectorOfConstantSDNodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified node is a BUILD_VECTOR node of all <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> or undef.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad300ebbb9f1787468bee5209194857ef">canonicalizeShuffleWithOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bd495ab23d43ebbe7e2d167103d8991">combineCastedMaskArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2a2b06cd0043981c801d852ace83fded">combineMaskedLoadConstantMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25809cd7dd1487d02672b4b834bf2ee2">combineMulToPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5aa226cd70fb4a0c7e597d6455601d5b">combinePMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a68b7af58bc3486a7e1a872337cee003f">combineTruncatedArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa51b13f3d4866613aac6907835f51f83">combinevXi1ConstantToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8c5470848197ac902e80545f0d08aa1c">ExtendToType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4cedb117165debe9de7d0a038f9da333">getTargetVShiftByConstNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a43be1b9abf919e872b51cfd766dbe8ed">getVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a25f268d098eb2425d10532c2184ee8b6">llvm::SelectionDAG::isConstantIntBuildVectorOrConstantInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81759e8ae2c9ab3b98619cce9995ad74">IsNOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#a7e6d0c1c367f6604bb0634e62131cbed">isSETCCorConvertedSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae7ed3fbc13ac6319f5437a7ebe61cd0b">llvm::SelectionDAG::isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abce17120537283b4104f8e1a7cad02a2">lowerBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c73954e103eaf84aceb7fc799f4c44a">lowerBuildVectorOfConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#af387d765ff63b855d2acab54f7ec7f47">lowerBuildVectorViaDominantValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1278833d086e5f200fcc7e576d2efa17">LowerFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae3b5afe10336a33630e00f86fab07c87">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4871d6290298d9eaae5b5da0160e5a21">LowerRotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac402e710afa6a0549f89ee90e9fa4cab">lowerVSELECTtoVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af501c536e39e504d53df2c0fa3d83f6d">LowervXi8MulWithUNPCK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab97e7bb67059e0b2b6b66c4a784b5106">matchIndexAsShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3de24662ee719e2c772575317d208116">matchIndexAsWiderOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4c4ced6d8064c639d791e53119774fcf">performINSERT_VECTOR_ELTCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>.</p>

</div>
</div>

### isConstantSplatVector() {#aafb64237a88493be2c913b0a51630a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isConstantSplatVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; SplatValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/node">Node</a> predicates.</p>


<p>If N is a BUILD_VECTOR or SPLAT_VECTOR node whose elements are all the same constant or undefined, return true and return the constant value in <span class="doxyComputerOutput">SplatValue</span>.</p>


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">SPLAT_VECTOR</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab73df8541f091c30ed34fd2c89c57746">combineShiftToPMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a143e143f8ee315e712138f13f3343cd5">combineTruncToVnclip</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b655bb8a3717c0d0114c94f731ca01a">combineVectorMulToSraBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aaef16aaed0ce790c381e75d7c9253f1e">llvm::X86TargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a5aaa4e25dcb7c49efaa3a2a5423a9416">llvm::XtensaTargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="#a08b1839785665aed1d6e91dd72764713">isConstantSplatVectorAllOnes</a>, <a href="#a531723c97a9c44056fc4996bde57229e">isConstantSplatVectorAllZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a607229211531af1259b2603df68033f0">isConstantSplatVectorMaskForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/constantint-match/#a5e7b0daf212c901784d8705f2cc506f8">llvm::SDPatternMatch::ConstantInt_match::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afe3fc9a96e843f0a30a80d4af77c1b26">PerformMinMaxCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a147c639e2ca29ad3a47362caa10562e8">performMulVectorCmpZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7da18013c41f68948709a964437238bf">performZExtUZPCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1e801ca0fc0ae63d482926b72ce3b45c">scalarizeExtractedBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a254b0db030fe653dbe78f9336bf97c39">tryLowerToSLI</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a1671cc3411876afb45d27eac3a048d4a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectXAR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07229844dfee2ef29637eec9717bede7">tryToWidenSetCCOperands</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### isConstantSplatVectorAllOnes() {#a08b1839785665aed1d6e91dd72764713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isConstantSplatVectorAllOnes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, bool BuildVectorOnly=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified node is a BUILD_VECTOR or SPLAT_VECTOR where all of the elements are ~0 or undef.</p>


<p>If <span class="doxyComputerOutput">BuildVectorOnly</span> is set to true, it only checks BUILD_VECTOR.</p>


<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">BITCAST</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a423e2c491de1408d54e35f0b47d076be">llvm::APInt::isAllOnes</a>, <a href="#aafb64237a88493be2c913b0a51630a0f">isConstantSplatVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">SPLAT_VECTOR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a33354bc388aab299f6dca5b75bbe2238">isAllActivePredicate</a>, <a href="#ac78d4df51ca05e4fb1630a01e07de434">isBuildVectorAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa5e728389b60e4210dc8e60dc114ee56">llvm::VPMatchContext::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab97e7bb67059e0b2b6b66c4a784b5106">matchIndexAsShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3de24662ee719e2c772575317d208116">matchIndexAsWiderOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>.</p>

</div>
</div>

### isConstantSplatVectorAllZeros() {#a531723c97a9c44056fc4996bde57229e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isConstantSplatVectorAllZeros (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, bool BuildVectorOnly=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified node is a BUILD_VECTOR or SPLAT_VECTOR where all of the elements are 0 or undef.</p>


<p>If <span class="doxyComputerOutput">BuildVectorOnly</span> is set to true, it only checks BUILD_VECTOR.</p>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">BITCAST</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aafb64237a88493be2c913b0a51630a0f">isConstantSplatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">SPLAT_VECTOR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7324b1333eec1b04ee358d58c42834ef">combineShiftLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b92776e41d73c3b5d4f1c5712f212c7">combineShiftRightLogical</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a491cbf5a685bf7c4455335bc9606ac49">combineVWADDSUBWSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af615c2897e116be598ef60e4bbdbdd52">isAllInactivePredicate</a>, <a href="#aaac3e239cbdfe15a8e9bad4f8e1e3a95">isBuildVectorAllZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3633803da2c1e9246eae907b238a0beb">isCheapToExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1ed5232dabde8c9cc04bfc41f179213a">isZerosVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a72e2201d5e251af1abbfb6fde00df1cb">removeRedundantInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>.</p>

</div>
</div>

### isEXTLoad() {#a910795e8d77c1545da0683c0e1cb81ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isEXTLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Returns true if the specified node is a EXTLOAD.</p>

<p>Definition at line 3221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">EXTLOAD</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af4674b301fdc98e0a729a8d4690e45f2">isFloatingPointZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af4674b301fdc98e0a729a8d4690e45f2">isFloatingPointZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aca34d64e6bca0d10314f1308d636ecf8">isValidSplatLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a>.</p>

</div>
</div>

### isExtOpcode() {#a4a72af46491472b765d836f2b5b62592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isExtOpcode (unsigned Opcode)</td>
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



<p>Definition at line 1681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">ANY_EXTEND</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">SIGN_EXTEND</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#ae4a5884857c776752f4195b769c3380f">combineBallotPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a41c7c45737725bfde12e18e00feae15a">isExtendOrShiftOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af27372c25a294d5d3b8ba864de3419b7">tryLowerPartialReductionToDot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a11ecac3a9729434713c118b4e1a6f52f">tryLowerPartialReductionToWideAdd</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>.</p>

</div>
</div>

### isExtVecInRegOpcode() {#a256306086883f189bdc13ed15c2f7800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isExtVecInRegOpcode (unsigned Opcode)</td>
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



<p>Definition at line 1686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110aaa275bf149ab5df1067cfb721936ecbc">ANY_EXTEND_VECTOR_INREG</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a3893859b5caa079593b9bf91b96e05fb">SIGN_EXTEND_VECTOR_INREG</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110adf7f4fc30c272a1987e075d7470df84c">ZERO_EXTEND_VECTOR_INREG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af01458f5f68de9153c5392eebedfa0f1">combineTruncationShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a41d90ad30eef03eda7c41e46c1839ded">foldExtendVectorInregToExtendOfSubvector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>.</p>

</div>
</div>

### isFPEqualitySetCC() {#a47810790d5bd808946ba55b160e513e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isFPEqualitySetCC (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Code)</td>
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

<p>Return true if this is a setcc instruction that performs an equality comparison when used with floating point operands.</p>

<p>Definition at line 1661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>References <a href="#ac3c3cf58d6d631af6a172457304d3d07a08c31033acfb9d6f0bc4a8a82cc26862">SETOEQ</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a57c68bf7ef20bd558854a24d5b0c1e72">SETONE</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a0deb50cd2f3f8e4a94eef4cdf769b848">SETUEQ</a> and <a href="#ac3c3cf58d6d631af6a172457304d3d07a0d1546187d4d526fcbdd43183689075e">SETUNE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>.</p>

</div>
</div>

### isFreezeUndef() {#a938294d45605337641e10c207def0988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isFreezeUndef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified node is <a href="#a22ea9cec080dd5f4f47ba234c2f59110ad3b50b6d74957b19afb85ac29f66afef">FREEZE(UNDEF)</a>.</p>

<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110ad3b50b6d74957b19afb85ac29f66afef">FREEZE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac500e16c74b6cb60304069a03b41a946">LowerAVXCONCAT_VECTORS</a>.</p>

</div>
</div>

### isIndexTypeSigned() {#a247f22e450c54c4a1c680641cb7546e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isIndexTypeSigned (<a href="#aa30bf48cd2a89f80c9c608adcabc53e3">MemIndexType</a> IndexType)</td>
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



<p>Definition at line 1576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>Reference <a href="#aa30bf48cd2a89f80c9c608adcabc53e3a0173acb50fe8c4337c23a98baab3f4db">SIGNED_SCALED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aaa474eeb44ead3ff4de31acddc8b0b22">refineIndexType</a>.</p>

</div>
</div>

### isIntEqualitySetCC() {#afda64d97fb7fe554744b7a68c304c224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isIntEqualitySetCC (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Code)</td>
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

<p>Return true if this is a setcc instruction that performs an equality comparison when used with integer operands.</p>

<p>Definition at line 1655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>References <a href="#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">SETEQ</a> and <a href="#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">SETNE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad34d9541b1000d244dd78e0cf23b45ea">combine_CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a007b16805afc4c07d06f494804c588a0">llvm::RISCVDAGToDAGISel::selectSETCC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5956dd38d2c4e11a90da91035b52096d">tryDemorganOfBooleanCondition</a>.</p>

</div>
</div>

### isNON\_EXTLoad() {#a15623094a1ed0cd7163dc786e44c87c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isNON_EXTLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Returns true if the specified node is a non-extending load.</p>

<p>Definition at line 3215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3">NON_EXTLOAD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9d13ace08d99a3db97ddf471924d6da5">findEltLoadSrc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af4674b301fdc98e0a729a8d4690e45f2">isFloatingPointZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af4674b301fdc98e0a729a8d4690e45f2">isFloatingPointZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a308a98eacddb4eaa55f1ab3723416253">isShuffleFoldableLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aca34d64e6bca0d10314f1308d636ecf8">isValidSplatLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#afa74b7294feb97757355ce013979b68e">TranslateM68kCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2e4cb621551faefc62d285fd35db6a8">TranslateX86CC</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a>.</p>

</div>
</div>

### isNormalLoad() {#afaaeadcd82b42fc0d385a6247bf7bb52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isNormalLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Returns true if the specified node is a non-extending and unindexed load.</p>

<p>Definition at line 3208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ad4d48171b87ca51ff54c10a436bac4d7a6aacde2c67988b43a261a7f7ceac4be3">NON_EXTLOAD</a> and <a href="#abee7ecb577fcade34eb16ccb7f503e31ade1c53e7b8a373e22ec53ff7bcbace9f">UNINDEXED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac445550f60946bb0bcb26733d7bfbbf8">adjustBitcastSrcVectorSSE1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aeff434dbdf596ee7867c4b817c57909f">canChangeToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a7eb6ba3743b9fcbc37cce6eaafec90c8">CheckForMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a69c29dade9c2c83e9928f92e0e6452f0">combineCVTP2I_CVTTP2I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a24cdc31f225e6b17b30c139085b064">combineCVTPH2PS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acfa813720f554bb68a6e8c5fdb870f4e">combineEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa9fca969da56000134dc248f8d676e3a">combineExtractFromVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0cccf679aa7f34055f858474bf8bdcdf">combineSignExtendInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0185d63d243a248f5bc69dfc943c88a">combineX86INT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ac5504ff57aff2070132ce601e1a25924">getNormalLoadInput</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a283338e41cb41bbe6a59285c019a0415">llvm::RISCVTargetLowering::getTargetConstantFromLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0bb270c4647dee5b3ba4ff11bf30016">getTargetConstantFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a573ab177e3dc7d27d8b2c6cb33544ab2">hasNormalLoadOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8679ab19e5fd70f2011394a4923d7c43">LowerAsSplatVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9cca449265297eb5a0bde5f0e48b7c22">lowerShuffleAsBlend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a699145421612880595f18dd1b31bf7cb">lowerShuffleAsBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a91771a953d65aeb837eecfef355de17f">lowerShuffleAsVTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#aafd16108bb2bfb19eed47e23dcbee3dd">llvm::X86::mayFoldLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57984ebd9271c38d02eb92b050f5bcee">PerformInsertEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4118089abb4cbadaf4b698cbbe05154f">PerformLOADCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a40eb7d32bd58dfbdde6c632446a56828">PerformVMOVrhCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a621eb8645a9f80882b80ac3c6d4e0091">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PreprocessISelDAG</a>.</p>

</div>
</div>

### isNormalStore() {#a308088c2d65f8f3955f5fb0f6aca7ccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isNormalStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Returns true if the specified node is a non-truncating and unindexed store.</p>

<p>Definition at line 3246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#abee7ecb577fcade34eb16ccb7f503e31ade1c53e7b8a373e22ec53ff7bcbace9f">UNINDEXED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae344bf38282de26bb4d5783114a65eaf">llvm::X86TargetLowering::IsDesirableToPromoteOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a670aa0012e26bf3d40dfa5068743ac48">llvm::X86::mayFoldIntoStore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>.</p>

</div>
</div>

### isOverflowIntrOpRes() {#a2d58a0ced655af200989177b8e029f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isOverflowIntrOpRes (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
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

<p>Returns true if the specified value is the overflow result from one of the overflow intrinsic nodes.</p>

<p>Definition at line 3292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110a863ec6ebb75bf89cfea14da646d77e92">SADDO</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aa35d0a58fdded3d225d512a60aea0951">SMULO</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">SSUBO</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">UADDO</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7800622851751b8ae318b41f4096830e">UMULO</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">USUBO</a>.</p>

</div>
</div>

### isSEXTLoad() {#ac174dc465cbe0e04a0f5e41c0a422124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isSEXTLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Returns true if the specified node is a SEXTLOAD.</p>

<p>Definition at line 3227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">SEXTLOAD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad5ca6ec71f3b7fbe0cdf298de7dea6f3">isSignExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aca34d64e6bca0d10314f1308d636ecf8">isValidSplatLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a>.</p>

</div>
</div>

### isSignedIntSetCC() {#aae86ddfa346964171caa61f29d46294b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isSignedIntSetCC (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Code)</td>
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

<p>Return true if this is a setcc instruction that performs a signed comparison when used with integer operands.</p>

<p>Definition at line 1643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>References <a href="#ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4">SETGE</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">SETGT</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">SETLE</a> and <a href="#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">SETLT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a021f42abfec39ba02f6b719a449b21db">ExtendUsesToFormExtLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#addb569dd78e703957469340fbfb3327e">getExtOpcodeForPromotedOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a>.</p>

</div>
</div>

### isTrueWhenEqual() {#a6eaea873272c138c801dae8542b1be46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isTrueWhenEqual (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Cond)</td>
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

<p>Return true if the specified condition returns true if the two operands to the condition are equal.</p>


<p>Note that if one of the two operands is a NaN, this value is meaningless.</p>


<p>Definition at line 1668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1ae915deb8e22ab5d8617a090149d0e6">llvm::SelectionDAG::FoldSetCC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>.</p>

</div>
</div>

### isUNINDEXEDLoad() {#a7da84980dd2ee06405d74303cfb90485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isUNINDEXEDLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Returns true if the specified node is an unindexed load.</p>

<p>Definition at line 3239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#abee7ecb577fcade34eb16ccb7f503e31ade1c53e7b8a373e22ec53ff7bcbace9f">UNINDEXED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aca34d64e6bca0d10314f1308d636ecf8">isValidSplatLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a>.</p>

</div>
</div>

### isUNINDEXEDStore() {#ab5c74add1b228292dae9d97d63b6f27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isUNINDEXEDStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Returns true if the specified node is an unindexed store.</p>

<p>Definition at line 3253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#abee7ecb577fcade34eb16ccb7f503e31ade1c53e7b8a373e22ec53ff7bcbace9f">UNINDEXED</a>.</p>

</div>
</div>

### isUnsignedIntSetCC() {#adb237925346ec53b00d3c82a42311318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isUnsignedIntSetCC (<a href="#ac3c3cf58d6d631af6a172457304d3d07">CondCode</a> Code)</td>
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

<p>Return true if this is a setcc instruction that performs an unsigned comparison when used with integer operands.</p>

<p>Definition at line 1649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>References <a href="#ac3c3cf58d6d631af6a172457304d3d07a9dff1dcbac65852b71473818c11869b1">SETUGE</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">SETUGT</a>, <a href="#ac3c3cf58d6d631af6a172457304d3d07ac538f0b432df970cbaaf6b81d777c6a7">SETULE</a> and <a href="#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">SETULT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad2800cb88996291ed1676f5899997ebe">combineExtSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aa4e01dc958f21a55df83d4fc9b811999">LowerBR_CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ad6539bf0f1a9d3264ca7797741a5fbe6">LowerSELECT_CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a481200c66d9f275e703dd248449186e4">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectCC</a>.</p>

</div>
</div>

### isVectorShrinkable() {#a570c0c51d118ee761eb55fc0d2d910f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isVectorShrinkable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned NewEltSize, bool Signed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the specified node is a vector where all elements can be truncated to the specified element size without a loss in meaning.</p>

<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64348c468485ac9fa8aaf382307061fb">findMoreOptimalIndexType</a>.</p>

</div>
</div>

### isVPBinaryOp() {#a5ec28aae630b390b75abfebf79bce788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isVPBinaryOp (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this is a vector-predicated binary operation opcode.</p>

<p>Declaration at line 1514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>

</div>
</div>

### isVPOpcode() {#aed1c239da7e4526d3140443b3bf6f8d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isVPOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this is a vector-predicated Opcode.</p>

<p>Declaration at line 1511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad85183a1e40f2a1dc0840c22484b8eec">llvm::SDNode::isVPOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a570c01f30a02464ded99189dae6f369d">llvm::VETargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abbfdbb08e7363ae1a09f8f70c8708487">SplitVPOp</a>.</p>

</div>
</div>

### isVPReduction() {#ab7d0f87095c6d1ece5c444d0e030083d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isVPReduction (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this is a vector-predicated reduction opcode.</p>

<p>Declaration at line 1517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac9aa93c5c44060d8bb0620dca40fd2cc">llvm::hasReductionStartParam</a>.</p>

</div>
</div>

### isZEXTLoad() {#a35edacef22fcaed7a8681fa573476131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::isZEXTLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Returns true if the specified node is a ZEXTLOAD.</p>

<p>Definition at line 3233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">ZEXTLOAD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aca34d64e6bca0d10314f1308d636ecf8">isValidSplatLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad72a699a06faa16c6e8dc15ed5ea2250">isZeroExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a>.</p>

</div>
</div>

### matchBinaryPredicate() {#ab283a383171c46fb4445cb64eb6b687a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::matchBinaryPredicate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> *)&gt; Match, bool AllowUndefs=false, bool AllowTypeMismatch=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to match a binary predicate against a pair of scalar/splat constants or every element of a pair of constant BUILD_VECTORs.</p>


<p>If AllowUndef is true, then UNDEF elements will pass nullptr to Match. If AllowTypeMismatch is true then RetType + ArgTypes don't need to match.</p>


<p>Declaration at line 3285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a1c861a21f795c3108ab690f3a45c881a">llvm::SDValue::isUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">SPLAT_VECTOR</a>.</p>

</div>
</div>

### matchUnaryFpPredicate() {#a425d6f0e5036ca26fdd80efcaae21589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::matchUnaryFpPredicate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode">ConstantFPSDNode</a> *)&gt; Match, bool AllowUndefs=false)</td>
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

<p>Hook for matching <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode">ConstantFPSDNode</a> predicate.</p>

<p>Definition at line 3275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a> and <a href="#a5bffdefad1ad0a43b40eaa2a2cded351">matchUnaryPredicateImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab5835737100eb8c242fbafada69bc19c">llvm::SelectionDAG::isKnownNeverZeroFloat</a>.</p>

</div>
</div>

### matchUnaryPredicate() {#a309c11edf22da984f95cf9ba7a699c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::matchUnaryPredicate (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> *)&gt; Match, bool AllowUndefs=false)</td>
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

<p>Hook for matching <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> predicate.</p>

<p>Definition at line 3267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a> and <a href="#a5bffdefad1ad0a43b40eaa2a2cded351">matchUnaryPredicateImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af1364d76011b791bbac39ca8470dd2bf">BuildExactSDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a1ca08074fa512b26eb7e8e88833892d9">BuildExactUDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a620a344f375b00f3fa82042e49157f39">isDivisorPowerOfTwo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9c9e38be1df7a70627fec8fa8a2eb42b">llvm::SelectionDAG::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a5bff9344010e6337ebead35d50f3cb28">isNonZeroModBitWidthOrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afc08a426e398925cd3ebdb7e422c89c3">llvm::SelectionDAG::simplifyShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4b538c66a1c14747f4194ba323cb7680">takeInexpensiveLog2</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### matchUnaryPredicateImpl() {#a5bffdefad1ad0a43b40eaa2a2cded351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ConstNodeType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ISD::matchUnaryPredicateImpl (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, std::function&lt; bool(ConstNodeType *)&gt; Match, bool AllowUndefs=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to match a unary predicate against a scalar/splat constant or every element of a constant BUILD_VECTOR.</p>


<p>If AllowUndef is true, then UNDEF elements will pass nullptr to Match.</p>


<p>Declaration at line 3262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a> and <a href="#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">SPLAT_VECTOR</a>.</p>


<p>Referenced by <a href="#a425d6f0e5036ca26fdd80efcaae21589">matchUnaryFpPredicate</a> and <a href="#a309c11edf22da984f95cf9ba7a699c11">matchUnaryPredicate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### LAST\_INDEXED\_MODE {#ae0010333b4e1424ce473b508d802bbbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::ISD::LAST_INDEXED_MODE = <a href="#abee7ecb577fcade34eb16ccb7f503e31a10a4094c81c0b9cd5e82e53b48932203">POST_DEC</a> + 1</td>
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



<p>Definition at line 1561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acf8f1219dc8b656e8e11c4b08edc8979">llvm::AArch64TargetLowering::AArch64TargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa782c58995f9a6e00cf5a8500a9a8508">llvm::ARMTargetLowering::ARMTargetLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0b793dc0bbf21627a4e8a2b4c7962c20">llvm::TargetLoweringBase::initActions</a>.</p>

</div>
</div>

### LAST\_LOADEXT\_TYPE {#a53490a5ced1d50808fe962a298c315cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::ISD::LAST_LOADEXT_TYPE = <a href="#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">ZEXTLOAD</a> + 1</td>
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



<p>Definition at line 1592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80ea223c590adb7c6fddc635804401c6">llvm::TargetLoweringBase::getAtomicLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9fd228909f3f1a59c6ef7d15c3547b61">llvm::TargetLoweringBase::getLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5a34f8f8354f91f84e864ae34c6cef90">llvm::TargetLoweringBase::setAtomicLoadExtAction</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad1d4d71bf37fea6a3170f27438d41e6d">llvm::TargetLoweringBase::setLoadExtAction</a>.</p>

</div>
</div>

### LAST\_MEM\_INDEX\_TYPE {#a769bfb423d42986a688a04035ce40cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::ISD::LAST_MEM_INDEX_TYPE = <a href="#aa30bf48cd2a89f80c9c608adcabc53e3af3218635b665db9e7e1d97e015f14e3a">UNSIGNED_SCALED</a> + 1</td>
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



<p>Definition at line 1574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">ISDOpcodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
