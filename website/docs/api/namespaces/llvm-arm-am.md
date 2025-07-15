---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/arm-am
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `ARM_AM` Namespace Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/arm-am">ARM_AM</a> - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Addressing Mode Stuff. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::ARM_AM { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ShiftOpc { <a href="#a76f5f9f36bbd9f03c844c5b565f239ef">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AddrOpc { <a href="#a5d0557608eaebed12bc00812724ba2cd">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AMSubMode { <a href="#a37ea08d6fc20eb1ef1bfb3ad008261a5">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a76f5f9f36bbd9f03c844c5b565f239ef">ShiftOpc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0e8b13220b4094b0eade6c4a691a68">getShiftOpcForNode</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ec5a84e85a22369494326910058643">getAddrOpcStr</a> (AddrOpc Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b3e65f8631804d09ab92645612a260">getShiftOpcStr</a> (ShiftOpc Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776a04107ee4560524fc5288af47c70e">getShiftOpcEncoding</a> (ShiftOpc Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3821ce1ee2c302ab18b25205a06ca327">getAMSubModeStr</a> (AMSubMode Mode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f904876469fc050db9a5723a79d1200">getSORegOpc</a> (ShiftOpc ShOp, unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d941a5b2ae5980beb76d03048a24eb3">getSORegOffset</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a76f5f9f36bbd9f03c844c5b565f239ef">ShiftOpc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a552f0f6a6cad1279707100bfe7fc3e97">getSORegShOp</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa28577d702e2a74b175b2eee75f7efc2">getSOImmValImm</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSOImmValImm - Given an encoded imm field for the reg/imm form, return the 8-bit imm value. <a href="#aa28577d702e2a74b175b2eee75f7efc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3066ac7186d7d02127d1073ca3e1cf">getSOImmValRot</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSOImmValRot - Given an encoded imm field for the reg/imm form, return the rotate amount. <a href="#a4c3066ac7186d7d02127d1073ca3e1cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c5994cbbea4a8c597898c689d92a5b1">getSOImmValRotate</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSOImmValRotate - Try to handle Imm with an immediate shifter operand, computing the rotate amount to use. <a href="#a2c5994cbbea4a8c597898c689d92a5b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3447f06da0010c13eeb865004f71ca">getSOImmVal</a> (unsigned Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSOImmVal - Given a 32-bit immediate, if it is something that can fit into an shifter_operand immediate operand, return the 12-bit encoding for it. <a href="#a0f3447f06da0010c13eeb865004f71ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6581a1f491b4f01c6b93d63ea095f5b6">isSOImmTwoPartVal</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSOImmTwoPartVal - Return true if the specified value can be obtained by or'ing together two SOImmVal's. <a href="#a6581a1f491b4f01c6b93d63ea095f5b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbbd359eefeb5aed59eecadddd4bf756">getSOImmTwoPartFirst</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSOImmTwoPartFirst - If V is a value that satisfies isSOImmTwoPartVal, return the first chunk of it. <a href="#abbbd359eefeb5aed59eecadddd4bf756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a605dd3e1bea15f2c42b7efa063273e1f">getSOImmTwoPartSecond</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSOImmTwoPartSecond - If V is a value that satisfies isSOImmTwoPartVal, return the second chunk of it. <a href="#a605dd3e1bea15f2c42b7efa063273e1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f539636d1f1c4e75b426059664fa022">isSOImmTwoPartValNeg</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSOImmTwoPartValNeg - Return true if the specified value can be obtained by two SOImmVal, that -V = First + Second. <a href="#a5f539636d1f1c4e75b426059664fa022">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecca4b0d3d0719e4b0eaf0fbe664b853">getThumbImmValShift</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getThumbImmValShift - Try to handle Imm with a 8-bit immediate followed by a left shift. <a href="#aecca4b0d3d0719e4b0eaf0fbe664b853">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd3a9f6f0047c1989e09ba2e317fe64">isThumbImmShiftedVal</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isThumbImmShiftedVal - Return true if the specified value can be obtained by left shifting a 8-bit immediate. <a href="#a2cd3a9f6f0047c1989e09ba2e317fe64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b588210115f426a0dc1a275bf2a882d">getThumbImm16ValShift</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getThumbImm16ValShift - Try to handle Imm with a 16-bit immediate followed by a left shift. <a href="#a6b588210115f426a0dc1a275bf2a882d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af77cc47d2681646373c08d84fb562197">isThumbImm16ShiftedVal</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isThumbImm16ShiftedVal - Return true if the specified value can be obtained by left shifting a 16-bit immediate. <a href="#af77cc47d2681646373c08d84fb562197">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b647b539d9f74cb48bbc53b2dac3e03">getThumbImmNonShiftedVal</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getThumbImmNonShiftedVal - If V is a value that satisfies isThumbImmShiftedVal, return the non-shiftd value. <a href="#a2b647b539d9f74cb48bbc53b2dac3e03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846cf4e09d203a53ff1639aee204c4bb">getT2SOImmValSplatVal</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getT2SOImmValSplat - Return the 12-bit encoded representation if the specified value can be obtained by splatting the low 8 bits into every other byte or every byte of a 32-bit value. <a href="#a846cf4e09d203a53ff1639aee204c4bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4287f784a134193f258e6709d8e6ed21">getT2SOImmValRotateVal</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getT2SOImmValRotateVal - Return the 12-bit encoded representation if the specified value is a rotated 8-bit value. <a href="#a4287f784a134193f258e6709d8e6ed21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d6b5f20dd274d971ef924f3e2a29d1a">getT2SOImmVal</a> (unsigned Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getT2SOImmVal - Given a 32-bit immediate, if it is something that can fit into a Thumb-2 shifter_operand immediate operand, return the 12-bit encoding for it. <a href="#a3d6b5f20dd274d971ef924f3e2a29d1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ebcc861ad7837c358e58dc41168798">getT2SOImmValRotate</a> (unsigned V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aace5db47fb82e762bb6ac3aef10716cb">isT2SOImmTwoPartVal</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9be15b1cfdccd1e45bcbec61d2f111a">getT2SOImmTwoPartFirst</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785452529e8d32f5611eea90afe4256a">getT2SOImmTwoPartSecond</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4164cc05e8f644c324b0ca06f0a3bf68">getAM2Opc</a> (AddrOpc Opc, unsigned Imm12, ShiftOpc SO, unsigned IdxMode=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a2545f60f5e7f7cffd5e66b0d4cf87">getAM2Offset</a> (unsigned AM2Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5d0557608eaebed12bc00812724ba2cd">AddrOpc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda0e957b0c23c9beaa0d98238e140f3">getAM2Op</a> (unsigned AM2Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a76f5f9f36bbd9f03c844c5b565f239ef">ShiftOpc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f978e0398d511ac5d13a41269b2f5fe">getAM2ShiftOpc</a> (unsigned AM2Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135fcd15fc43e5664e26f499e5c67b0c">getAM2IdxMode</a> (unsigned AM2Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6cb5fa43b996b6b5e9c15173a167b5">getAM3Opc</a> (AddrOpc Opc, unsigned char Offset, unsigned IdxMode=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAM3Opc - This function encodes the addrmode3 opc field. <a href="#a6a6cb5fa43b996b6b5e9c15173a167b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a5f8eaf559ab55d1c8f7f9a7826a87">getAM3Offset</a> (unsigned AM3Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5d0557608eaebed12bc00812724ba2cd">AddrOpc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf54dffc0ef46cbffcaace8bcf2a3758">getAM3Op</a> (unsigned AM3Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a222005ac2a7756f7bd651ca6f3d6d190">getAM3IdxMode</a> (unsigned AM3Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a37ea08d6fc20eb1ef1bfb3ad008261a5">AMSubMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e4646b896b1964b2964a1c10d01650">getAM4SubMode</a> (unsigned Mode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b437efaa9802bacd9bd431a4b19690a">getAM4ModeImm</a> (AMSubMode SubMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48da3fd9e35b4f6c6bd79cd18af31d3d">getAM5Opc</a> (AddrOpc Opc, unsigned char Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAM5Opc - This function encodes the addrmode5 opc field. <a href="#a48da3fd9e35b4f6c6bd79cd18af31d3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abba23061634d5885171053eadb065aab">getAM5Offset</a> (unsigned AM5Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5d0557608eaebed12bc00812724ba2cd">AddrOpc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55a750d304cec7fccaa832e298b0ea23">getAM5Op</a> (unsigned AM5Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621391aa9c7939d1fc79f943508171cb">getAM5FP16Opc</a> (AddrOpc Opc, unsigned char Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAM5FP16Opc - This function encodes the addrmode5fp16 opc field. <a href="#a621391aa9c7939d1fc79f943508171cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0962a941ae3989bd18da2b47b98cca85">getAM5FP16Offset</a> (unsigned AM5Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5d0557608eaebed12bc00812724ba2cd">AddrOpc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a71aa4bb4ce839e426870c61eb794c7">getAM5FP16Op</a> (unsigned AM5Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a586b8fb4f2945716775940f70cc15af1">createVMOVModImm</a> (unsigned OpCmode, unsigned Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60bd6c9116ccabdb6ec74c7708c47bf9">getVMOVModImmOpCmode</a> (unsigned ModImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b853e6b0e974e6683f9c88d7661879f">getVMOVModImmVal</a> (unsigned ModImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1142830159ad93c394b72a09905a51fd">decodeVMOVModImm</a> (unsigned ModImm, unsigned &amp;EltBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>decodeVMOVModImm - Decode a NEON/MVE modified immediate value into the element value and the element size in bits. <a href="#a1142830159ad93c394b72a09905a51fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a25efc8e931d4e989a4df264942e99">isNEONBytesplat</a> (unsigned Value, unsigned Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d0abf06ee7ecd205a1faea528698a78">isNEONi16splat</a> (unsigned Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is a correct immediate for instructions like VBIC/VORR. <a href="#a5d0abf06ee7ecd205a1faea528698a78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f85a007bf3e4a317a714e2e07680c47">encodeNEONi16splat</a> (unsigned Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bfe2dce3ac76bfe25bd3ec43de6da8f">isNEONi32splat</a> (unsigned Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is a correct immediate for instructions like VBIC/VORR. <a href="#a6bfe2dce3ac76bfe25bd3ec43de6da8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5a8f472308dc5564856a478b255df8">encodeNEONi32splat</a> (unsigned Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode NEON 32 bits Splat immediate for instructions like VBIC/VORR. <a href="#aab5a8f472308dc5564856a478b255df8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c2b7ef9a32efac90cfa7257fbb2ee52">getFPImmFloat</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d6612ebe88f532f464ff1275ed58d1b">getFP16Imm</a> (const APInt &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFP16Imm - Return an 8-bit floating-point version of the 16-bit floating-point value. <a href="#a6d6612ebe88f532f464ff1275ed58d1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a175cfb35ded324792e79b99f0f26788b">getFP16Imm</a> (const APFloat &amp;FPImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee19d38a1e1584e356c193d30417733">getFP32FP16Imm</a> (const APInt &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a FP16Imm encoded as a fp32 value, return the 8-bit encoding for it. <a href="#a9ee19d38a1e1584e356c193d30417733">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802e2c223f77ddcaa043fdb8aea8f0db">getFP32FP16Imm</a> (const APFloat &amp;FPImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff84c673da1cdc12d7061d663a686a5">getFP32Imm</a> (const APInt &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFP32Imm - Return an 8-bit floating-point version of the 32-bit floating-point value. <a href="#a0ff84c673da1cdc12d7061d663a686a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7216473d5bb804df4df6141438c8c5ce">getFP32Imm</a> (const APFloat &amp;FPImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b469aea8a344952b8effedd56336182">getFP64Imm</a> (const APInt &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFP64Imm - Return an 8-bit floating-point version of the 64-bit floating-point value. <a href="#a5b469aea8a344952b8effedd56336182">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39c2a3666c56528f1a3dd717634f4bd4">getFP64Imm</a> (const APFloat &amp;FPImm)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/arm-am">ARM_AM</a> - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Addressing Mode Stuff.</p>

<div class="doxySectionDef">

## Enumerations

### AddrOpc {#a5d0557608eaebed12bc00812724ba2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARM_AM::AddrOpc </td>
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
<td class="doxyEnumItemName">sub<a id="a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">add<a id="a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>

</div>
</div>

### AMSubMode {#a37ea08d6fc20eb1ef1bfb3ad008261a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARM_AM::AMSubMode </td>
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
<td class="doxyEnumItemName">bad_am_submode<a id="a37ea08d6fc20eb1ef1bfb3ad008261a5a1684f0ae691cbb9d0be78753ab3cdffe"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ia<a id="a37ea08d6fc20eb1ef1bfb3ad008261a5af0bccfa4a7bf9c0aaffaf57421effe3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ib<a id="a37ea08d6fc20eb1ef1bfb3ad008261a5a142f78f7efc65a4326e455faf26fd4cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">da<a id="a37ea08d6fc20eb1ef1bfb3ad008261a5a059d1070c4becc8b9584e5719ffd24b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">db<a id="a37ea08d6fc20eb1ef1bfb3ad008261a5a2613d8e3d6eaaa6285047725dcc7aa79"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>

</div>
</div>

### ShiftOpc {#a76f5f9f36bbd9f03c844c5b565f239ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARM_AM::ShiftOpc </td>
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
<td class="doxyEnumItemName">no_shift<a id="a76f5f9f36bbd9f03c844c5b565f239efa52ce105a97f77049ddfe808bbf0f3eac"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">asr<a id="a76f5f9f36bbd9f03c844c5b565f239efa325f4baf722ab35ea203950c4e3c5e5a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">lsl<a id="a76f5f9f36bbd9f03c844c5b565f239efaafeb1424944dafbde8a990bce1f5bd84"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">lsr<a id="a76f5f9f36bbd9f03c844c5b565f239efa25f26a9f4d00c9ac425953111519c041"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ror<a id="a76f5f9f36bbd9f03c844c5b565f239efaf9bc4030b576764b9de7211577c98460"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">rrx<a id="a76f5f9f36bbd9f03c844c5b565f239efabf251272bdeee23065eaf39227adfe88"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">uxtw<a id="a76f5f9f36bbd9f03c844c5b565f239efae26416607f674906665de5228b3cd381"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### createVMOVModImm() {#a586b8fb4f2945716775940f70cc15af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::createVMOVModImm (unsigned OpCmode, unsigned Val)</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac424ec93d0c7fd6666e2200a60cb20b9">isVMOVModifiedImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5feb45b04aa25eb71c544179e1af18d6">PromoteMVEPredVector</a>.</p>

</div>
</div>

### decodeVMOVModImm() {#a1142830159ad93c394b72a09905a51fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ARM_AM::decodeVMOVModImm (unsigned ModImm, unsigned &amp; EltBits)</td>
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

<p>decodeVMOVModImm - Decode a NEON/MVE modified immediate value into the element value and the element size in bits.</p>


<p>(If the element size is smaller than the vector, it is splatted into all the elements.)</p>


<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a60bd6c9116ccabdb6ec74c7708c47bf9">getVMOVModImmOpCmode</a>, <a href="#a3b853e6b0e974e6683f9c88d7661879f">getVMOVModImmVal</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57a099df9c79ef37ef7f89374247ac0e">PerformVDUPLANECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ae905b708b2b1677ea7ce953ed987cf23">llvm::ARMInstPrinter::printVMOVModImmOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a655de0b9ba51c463a01a23651abb0cf7">llvm::ARMTargetLowering::SimplifyDemandedBitsForTargetNode</a>.</p>

</div>
</div>

### encodeNEONi16splat() {#a1f85a007bf3e4a317a714e2e07680c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::encodeNEONi16splat (unsigned Value)</td>
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



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5d0abf06ee7ecd205a1faea528698a78">isNEONi16splat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a8d92ff1355dcb13d00196990471f9139">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi16splatNotOperands</a> and <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0940a9f22c8bd87b7fa0a45e012d0516">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi16splatOperands</a>.</p>

</div>
</div>

### encodeNEONi32splat() {#aab5a8f472308dc5564856a478b255df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::encodeNEONi32splat (unsigned Value)</td>
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

<p>Encode NEON 32 bits Splat immediate for instructions like VBIC/VORR.</p>

<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a6bfe2dce3ac76bfe25bd3ec43de6da8f">isNEONi32splat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4262ad98cb319bdaf2b640bdb0fbd6ff">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32splatNotOperands</a> and <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a36daafec1fff81a5867269e34313dc3d">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32splatOperands</a>.</p>

</div>
</div>

### getAddrOpcStr() {#a85ec5a84e85a22369494326910058643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::ARM_AM::getAddrOpcStr (<a href="#a5d0557608eaebed12bc00812724ba2cd">AddrOpc</a> Op)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ac5739a68abf105b4fee5ae4ed66b83c2">llvm::ARMInstPrinter::printAddrMode2OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a27ad0652b6099f891ab3329efe1ece6f">llvm::ARMInstPrinter::printAddrMode3OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#afdc2a24a421c911f502c96f9822ca0de">llvm::ARMInstPrinter::printAddrMode5FP16Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a5ce1d55f5ea53662c66eec4d08b34ea1">llvm::ARMInstPrinter::printAddrMode5Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1e026f7100c90a0382ba7c7290cefaa8">llvm::ARMInstPrinter::printAM2PreOrOffsetIndexOp</a> and <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af16346148e47bd920deff1ae577e52fc">llvm::ARMInstPrinter::printAM3PreOrOffsetIndexOp</a>.</p>

</div>
</div>

### getAM2IdxMode() {#a135fcd15fc43e5664e26f499e5c67b0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getAM2IdxMode (unsigned AM2Opc)</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a667919f34df462c691e5df9021da7a09">llvm::ARMInstPrinter::printAddrMode2Operand</a>.</p>

</div>
</div>

### getAM2Offset() {#a29a2545f60f5e7f7cffd5e66b0d4cf87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getAM2Offset (unsigned AM2Opc)</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ac39168a48563b3979effd5915975ebbf">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode2OffsetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a235a0e236caca418542d097c0f0fca9c">llvm::ARMBaseRegisterInfo::getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a8e1e721b16705bb865e497a522ae0399">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getLdStSORegOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a546b8cefb687c85f2a1383240bb5f4da">getNumMicroOpsSwiftLdSt</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ac5739a68abf105b4fee5ae4ed66b83c2">llvm::ARMInstPrinter::printAddrMode2OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1e026f7100c90a0382ba7c7290cefaa8">llvm::ARMInstPrinter::printAM2PreOrOffsetIndexOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a>.</p>

</div>
</div>

### getAM2Op() {#acda0e957b0c23c9beaa0d98238e140f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrOpc llvm::ARM_AM::getAM2Op (unsigned AM2Opc)</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> and <a href="#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ac39168a48563b3979effd5915975ebbf">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode2OffsetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a235a0e236caca418542d097c0f0fca9c">llvm::ARMBaseRegisterInfo::getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a8e1e721b16705bb865e497a522ae0399">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getLdStSORegOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a546b8cefb687c85f2a1383240bb5f4da">getNumMicroOpsSwiftLdSt</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ac5739a68abf105b4fee5ae4ed66b83c2">llvm::ARMInstPrinter::printAddrMode2OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1e026f7100c90a0382ba7c7290cefaa8">llvm::ARMInstPrinter::printAM2PreOrOffsetIndexOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a>.</p>

</div>
</div>

### getAM2Opc() {#a4164cc05e8f644c324b0ca06f0a3bf68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getAM2Opc (<a href="#a5d0557608eaebed12bc00812724ba2cd">AddrOpc</a> Opc, unsigned Imm12, <a href="#a76f5f9f36bbd9f03c844c5b565f239ef">ShiftOpc</a> SO, unsigned IdxMode=0)</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aff551f6c57e2bda70f7c58294b662d04">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab5034e33be4df547034085fd56f5ef7a">anonymous{ARMAsmParser.cpp}::ARMOperand::addAM2OffsetImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a97437a291cf5a4acb1a9459466af8637">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemRegOffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac6ffe44b8dc8406f9792b89635c955b1">anonymous{ARMAsmParser.cpp}::ARMOperand::addPostIdxRegShiftedOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a01159155e0e1288fdee10e8077d347e4">DecodeAddrMode2IdxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a20e9fffc7ece71cc090e060083bba8a5">DecodeSORegMemOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ac2a883d3da363288434a1110d9c275f0">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode2OffsetImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a54dfd9d8e05d4813fa85c9877c0e270a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode2OffsetReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a8485253be2e78195ae26f28df0dd41d4">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectLdStSOReg</a>.</p>

</div>
</div>

### getAM2ShiftOpc() {#a0f978e0398d511ac5d13a41269b2f5fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShiftOpc llvm::ARM_AM::getAM2ShiftOpc (unsigned AM2Opc)</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ac39168a48563b3979effd5915975ebbf">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode2OffsetOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a8e1e721b16705bb865e497a522ae0399">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getLdStSORegOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a546b8cefb687c85f2a1383240bb5f4da">getNumMicroOpsSwiftLdSt</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ac5739a68abf105b4fee5ae4ed66b83c2">llvm::ARMInstPrinter::printAddrMode2OffsetOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1e026f7100c90a0382ba7c7290cefaa8">llvm::ARMInstPrinter::printAM2PreOrOffsetIndexOp</a>.</p>

</div>
</div>

### getAM3IdxMode() {#a222005ac2a7756f7bd651ca6f3d6d190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getAM3IdxMode (unsigned AM3Opc)</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a3447052cf7fe3b2ef02ed56f332b65c9">llvm::ARMInstPrinter::printAddrMode3Operand</a>.</p>

</div>
</div>

### getAM3Offset() {#a05a5f8eaf559ab55d1c8f7f9a7826a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::ARM_AM::getAM3Offset (unsigned AM3Opc)</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3a10338918837225d81648bf78971876">evaluateMemOpAddrForAddrMode3</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ae68bfb13f71bdc4b9daceb16565d5764">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode3OffsetOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a2d0dda09f20d0ebce689e4a66fb95336">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode3OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a235a0e236caca418542d097c0f0fca9c">llvm::ARMBaseRegisterInfo::getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a8f37e6cea9ab3f9aa0aff88504d8702a">getMemoryOpOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a27ad0652b6099f891ab3329efe1ece6f">llvm::ARMInstPrinter::printAddrMode3OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af16346148e47bd920deff1ae577e52fc">llvm::ARMInstPrinter::printAM3PreOrOffsetIndexOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a>.</p>

</div>
</div>

### getAM3Op() {#acf54dffc0ef46cbffcaace8bcf2a3758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrOpc llvm::ARM_AM::getAM3Op (unsigned AM3Opc)</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> and <a href="#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3a10338918837225d81648bf78971876">evaluateMemOpAddrForAddrMode3</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ae68bfb13f71bdc4b9daceb16565d5764">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode3OffsetOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a2d0dda09f20d0ebce689e4a66fb95336">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode3OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a235a0e236caca418542d097c0f0fca9c">llvm::ARMBaseRegisterInfo::getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a8f37e6cea9ab3f9aa0aff88504d8702a">getMemoryOpOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a546b8cefb687c85f2a1383240bb5f4da">getNumMicroOpsSwiftLdSt</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a27ad0652b6099f891ab3329efe1ece6f">llvm::ARMInstPrinter::printAddrMode3OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af16346148e47bd920deff1ae577e52fc">llvm::ARMInstPrinter::printAM3PreOrOffsetIndexOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a>.</p>

</div>
</div>

### getAM3Opc() {#a6a6cb5fa43b996b6b5e9c15173a167b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getAM3Opc (<a href="#a5d0557608eaebed12bc00812724ba2cd">AddrOpc</a> Opc, unsigned char Offset, unsigned IdxMode=0)</td>
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

<p>getAM3Opc - This function encodes the addrmode3 opc field.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a29b2705aeee49d31d232c5ab440f7877">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode3Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9e51c04c7eea24160648528b9e2867c7">anonymous{ARMAsmParser.cpp}::ARMOperand::addAM3OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#abb5c2f66d44327ca2fceb3bf57801150">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode3</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a2831c4e1d62a6a8ebe8754d541736f1b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode3Offset</a>.</p>

</div>
</div>

### getAM4ModeImm() {#a6b437efaa9802bacd9bd431a4b19690a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getAM4ModeImm (<a href="#a37ea08d6fc20eb1ef1bfb3ad008261a5">AMSubMode</a> SubMode)</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>

</div>
</div>

### getAM4SubMode() {#ae0e4646b896b1964b2964a1c10d01650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMSubMode llvm::ARM_AM::getAM4SubMode (unsigned Mode)</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#afc390709bb8d86396c4292746dd43810">llvm::ARMInstPrinter::printLdStmModeOperand</a>.</p>

</div>
</div>

### getAM5FP16Offset() {#a0962a941ae3989bd18da2b47b98cca85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::ARM_AM::getAM5FP16Offset (unsigned AM5Opc)</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a4ffbbb48662d27de4440a7b157ee9c95">evaluateMemOpAddrForAddrMode5FP16</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#afdc2a24a421c911f502c96f9822ca0de">llvm::ARMInstPrinter::printAddrMode5FP16Operand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>.</p>

</div>
</div>

### getAM5FP16Op() {#a6a71aa4bb4ce839e426870c61eb794c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrOpc llvm::ARM_AM::getAM5FP16Op (unsigned AM5Opc)</td>
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



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> and <a href="#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a4ffbbb48662d27de4440a7b157ee9c95">evaluateMemOpAddrForAddrMode5FP16</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#afdc2a24a421c911f502c96f9822ca0de">llvm::ARMInstPrinter::printAddrMode5FP16Operand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>.</p>

</div>
</div>

### getAM5FP16Opc() {#a621391aa9c7939d1fc79f943508171cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getAM5FP16Opc (<a href="#a5d0557608eaebed12bc00812724ba2cd">AddrOpc</a> Opc, unsigned char Offset)</td>
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

<p>getAM5FP16Opc - This function encodes the addrmode5fp16 opc field.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aeca538a61ece736dfa6ca68bfcebb401">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode5FP16Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a1719003051d48a2e0a048a932e7ab2b1">DecodeAddrMode5FP16Operand</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a97fccf6d0a26eb7a492eeecb241a93d0">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::IsAddressingMode5</a>.</p>

</div>
</div>

### getAM5Offset() {#abba23061634d5885171053eadb065aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::ARM_AM::getAM5Offset (unsigned AM5Opc)</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a90ccaddf3b14b7a19c3174cd9e5651d9">evaluateMemOpAddrForAddrMode5</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ad8e82a3b2fdfbba528962f3c010088ac">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode5FP16OpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ac5de66a883970fc59be6f0673634a0f8">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode5OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a235a0e236caca418542d097c0f0fca9c">llvm::ARMBaseRegisterInfo::getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a8f37e6cea9ab3f9aa0aff88504d8702a">getMemoryOpOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a5ce1d55f5ea53662c66eec4d08b34ea1">llvm::ARMInstPrinter::printAddrMode5Operand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>.</p>

</div>
</div>

### getAM5Op() {#a55a750d304cec7fccaa832e298b0ea23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddrOpc llvm::ARM_AM::getAM5Op (unsigned AM5Opc)</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> and <a href="#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a90ccaddf3b14b7a19c3174cd9e5651d9">evaluateMemOpAddrForAddrMode5</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ad8e82a3b2fdfbba528962f3c010088ac">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode5FP16OpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ac5de66a883970fc59be6f0673634a0f8">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode5OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a235a0e236caca418542d097c0f0fca9c">llvm::ARMBaseRegisterInfo::getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a8f37e6cea9ab3f9aa0aff88504d8702a">getMemoryOpOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a5ce1d55f5ea53662c66eec4d08b34ea1">llvm::ARMInstPrinter::printAddrMode5Operand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>.</p>

</div>
</div>

### getAM5Opc() {#a48da3fd9e35b4f6c6bd79cd18af31d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getAM5Opc (<a href="#a5d0557608eaebed12bc00812724ba2cd">AddrOpc</a> Opc, unsigned char Offset)</td>
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

<p>getAM5Opc - This function encodes the addrmode5 opc field.</p>

<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a6b2100e3595ebc052f71501e05bf9ef4">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode5Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a674f8e4f3cc5c0f3c600feac22465ba6">DecodeAddrMode5Operand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7b3ca5b536ce1c58a39b853ea79de51b">DecodeCopMemInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a97fccf6d0a26eb7a492eeecb241a93d0">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::IsAddressingMode5</a>.</p>

</div>
</div>

### getAMSubModeStr() {#a3821ce1ee2c302ab18b25205a06ca327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::ARM_AM::getAMSubModeStr (<a href="#a37ea08d6fc20eb1ef1bfb3ad008261a5">AMSubMode</a> Mode)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a37ea08d6fc20eb1ef1bfb3ad008261a5a059d1070c4becc8b9584e5719ffd24b6">da</a>, <a href="#a37ea08d6fc20eb1ef1bfb3ad008261a5a2613d8e3d6eaaa6285047725dcc7aa79">db</a>, <a href="#a37ea08d6fc20eb1ef1bfb3ad008261a5af0bccfa4a7bf9c0aaffaf57421effe3f">ia</a>, <a href="#a37ea08d6fc20eb1ef1bfb3ad008261a5a142f78f7efc65a4326e455faf26fd4cc">ib</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#afc390709bb8d86396c4292746dd43810">llvm::ARMInstPrinter::printLdStmModeOperand</a>.</p>

</div>
</div>

### getFP16Imm() {#a6d6612ebe88f532f464ff1275ed58d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getFP16Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm)</td>
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

<p>getFP16Imm - Return an 8-bit floating-point version of the 16-bit floating-point value.</p>


<p>If the value cannot be represented as an 8-bit floating-point value, then return -1.</p>


<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="#a175cfb35ded324792e79b99f0f26788b">getFP16Imm</a>, <a href="#a9ee19d38a1e1584e356c193d30417733">getFP32FP16Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a361a22a9d4bb3a3812c85f56f6b04e08">llvm::ARMTargetLowering::isFPImmLegal</a>.</p>

</div>
</div>

### getFP16Imm() {#a175cfb35ded324792e79b99f0f26788b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getFP16Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; FPImm)</td>
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



<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a> and <a href="#a6d6612ebe88f532f464ff1275ed58d1b">getFP16Imm</a>.</p>

</div>
</div>

### getFP32FP16Imm() {#a9ee19d38a1e1584e356c193d30417733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getFP32FP16Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm)</td>
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

<p>If this is a FP16Imm encoded as a fp32 value, return the 8-bit encoding for it.</p>


<p>Otherwise return -1 like getFP16Imm.</p>


<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="#a6d6612ebe88f532f464ff1275ed58d1b">getFP16Imm</a>.</p>


<p>Referenced by <a href="#a802e2c223f77ddcaa043fdb8aea8f0db">getFP32FP16Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a361a22a9d4bb3a3812c85f56f6b04e08">llvm::ARMTargetLowering::isFPImmLegal</a>.</p>

</div>
</div>

### getFP32FP16Imm() {#a802e2c223f77ddcaa043fdb8aea8f0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getFP32FP16Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; FPImm)</td>
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



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a> and <a href="#a9ee19d38a1e1584e356c193d30417733">getFP32FP16Imm</a>.</p>

</div>
</div>

### getFP32Imm() {#a0ff84c673da1cdc12d7061d663a686a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getFP32Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm)</td>
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

<p>getFP32Imm - Return an 8-bit floating-point version of the 32-bit floating-point value.</p>


<p>If the value cannot be represented as an 8-bit floating-point value, then return -1.</p>


<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#abe2cc7744f5671009687f38923ffd49b">anonymous{ARMAsmParser.cpp}::ARMOperand::addFPImmOperands</a>, <a href="#a7216473d5bb804df4df6141438c8c5ce">getFP32Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae5c3939a86ea8f12a6f26bda5057bb17">anonymous{ARMAsmParser.cpp}::ARMOperand::isFPImm</a> and <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a361a22a9d4bb3a3812c85f56f6b04e08">llvm::ARMTargetLowering::isFPImmLegal</a>.</p>

</div>
</div>

### getFP32Imm() {#a7216473d5bb804df4df6141438c8c5ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getFP32Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; FPImm)</td>
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



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a> and <a href="#a0ff84c673da1cdc12d7061d663a686a5">getFP32Imm</a>.</p>

</div>
</div>

### getFP64Imm() {#a5b469aea8a344952b8effedd56336182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getFP64Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm)</td>
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

<p>getFP64Imm - Return an 8-bit floating-point version of the 64-bit floating-point value.</p>


<p>If the value cannot be represented as an 8-bit floating-point value, then return -1.</p>


<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="#a39c2a3666c56528f1a3dd717634f4bd4">getFP64Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a361a22a9d4bb3a3812c85f56f6b04e08">llvm::ARMTargetLowering::isFPImmLegal</a>.</p>

</div>
</div>

### getFP64Imm() {#a39c2a3666c56528f1a3dd717634f4bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getFP64Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; FPImm)</td>
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



<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a> and <a href="#a5b469aea8a344952b8effedd56336182">getFP64Imm</a>.</p>

</div>
</div>

### getFPImmFloat() {#a3c2b7ef9a32efac90cfa7257fbb2ee52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::ARM_AM::getFPImmFloat (unsigned Imm)</td>
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



<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aa012d06e92b0a7a5310d8639fc198096">llvm::ARMInstPrinter::printFPImmOperand</a>.</p>

</div>
</div>

### getShiftOpcEncoding() {#a776a04107ee4560524fc5288af47c70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getShiftOpcEncoding (<a href="#a76f5f9f36bbd9f03c844c5b565f239ef">ShiftOpc</a> Op)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a76f5f9f36bbd9f03c844c5b565f239efa325f4baf722ab35ea203950c4e3c5e5a">asr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efaafeb1424944dafbde8a990bce1f5bd84">lsl</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efa25f26a9f4d00c9ac425953111519c041">lsr</a> and <a href="#a76f5f9f36bbd9f03c844c5b565f239efaf9bc4030b576764b9de7211577c98460">ror</a>.</p>

</div>
</div>

### getShiftOpcForNode() {#a0f0e8b13220b4094b0eade6c4a691a68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShiftOpc llvm::ARM_AM::getShiftOpcForNode (unsigned Opcode)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armselectiondaginfo-h">ARMSelectionDAGInfo.h</a>.</p>


<p>References <a href="#a76f5f9f36bbd9f03c844c5b565f239efa325f4baf722ab35ea203950c4e3c5e5a">asr</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efaafeb1424944dafbde8a990bce1f5bd84">lsl</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efa25f26a9f4d00c9ac425953111519c041">lsr</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efa52ce105a97f77049ddfe808bbf0f3eac">no_shift</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efaf9bc4030b576764b9de7211577c98460">ror</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac7734fe83bba82dacf7ebb09a8376f17">getARMIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a54dfd9d8e05d4813fa85c9877c0e270a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode2OffsetReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a32d2decc2fbd86ebc9e635bc3aaf56d9">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectImmShifterOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a8485253be2e78195ae26f28df0dd41d4">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectLdStSOReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ab301fda1e7e3cd7b76586ed7233df73a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectRegShifterOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a727eda518f4ada7109bb391d66f576e9">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeSoReg</a>.</p>

</div>
</div>

### getShiftOpcStr() {#ac1b3e65f8631804d09ab92645612a260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringRef llvm::ARM_AM::getShiftOpcStr (<a href="#a76f5f9f36bbd9f03c844c5b565f239ef">ShiftOpc</a> Op)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a76f5f9f36bbd9f03c844c5b565f239efa325f4baf722ab35ea203950c4e3c5e5a">asr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efaafeb1424944dafbde8a990bce1f5bd84">lsl</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efa25f26a9f4d00c9ac425953111519c041">lsr</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efaf9bc4030b576764b9de7211577c98460">ror</a>, <a href="#a76f5f9f36bbd9f03c844c5b565f239efabf251272bdeee23065eaf39227adfe88">rrx</a> and <a href="#a76f5f9f36bbd9f03c844c5b565f239efae26416607f674906665de5228b3cd381">uxtw</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c87701e16414a07520790dfd88c52aa">anonymous{ARMAsmParser.cpp}::ARMOperand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a97d0066eae87ce228a58774409c88425">llvm::ARMInstPrinter::printInst</a> and <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a14ed66f2387fda436642c97dc961337e">llvm::ARMInstPrinter::printSORegRegOperand</a>.</p>

</div>
</div>

### getSOImmTwoPartFirst() {#abbbd359eefeb5aed59eecadddd4bf756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getSOImmTwoPartFirst (unsigned V)</td>
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

<p>getSOImmTwoPartFirst - If V is a value that satisfies isSOImmTwoPartVal, return the first chunk of it.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a2c5994cbbea4a8c597898c689d92a5b1">getSOImmValRotate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a> and <a href="#a5f539636d1f1c4e75b426059664fa022">isSOImmTwoPartValNeg</a>.</p>

</div>
</div>

### getSOImmTwoPartSecond() {#a605dd3e1bea15f2c42b7efa063273e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getSOImmTwoPartSecond (unsigned V)</td>
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

<p>getSOImmTwoPartSecond - If V is a value that satisfies isSOImmTwoPartVal, return the second chunk of it.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2c5994cbbea4a8c597898c689d92a5b1">getSOImmValRotate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>.</p>

</div>
</div>

### getSOImmVal() {#a0f3447f06da0010c13eeb865004f71ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getSOImmVal (unsigned Arg)</td>
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

<p>getSOImmVal - Given a 32-bit immediate, if it is something that can fit into an shifter_operand immediate operand, return the 12-bit encoding for it.</p>


<p>If not, return -1.</p>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a2c5994cbbea4a8c597898c689d92a5b1">getSOImmValRotate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef2599d8a5a682c348b25f74051cdb2d">llvm::rotl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a00f276d60b4213d06f10e1c6965e6982">anonymous{ARMAsmParser.cpp}::ARMOperand::addModImmNegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a25c3c5882ff6060ea26a9a2c6c96e4d9">anonymous{ARMAsmParser.cpp}::ARMOperand::addModImmNotOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acd2d48bd67d42ac499c2b0acdef4c2c3">llvm::ARMAsmBackend::adjustFixupValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabff304f51525ece8028bf8e9b1c3614">llvm::ConstantMaterializationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae917ff404aade469cb9d3780515660ad">llvm::emitARMRegPlusImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ac35137650a86a025428b42f45c7b6133">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAdrLabelOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a41c8a4fccc70b2cde9a38d48c5a6ba9d">llvm::ARMTTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a49b12bb20bfe83cd2dff540bdc513838">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::is_so_imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#abcdddd276cae51582daadc80979e23cb">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::is_so_imm_not</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a89dae2ca2d9a35776687bc7d8a49ce32">anonymous{ARMAsmParser.cpp}::ARMOperand::isAdrLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2dd0b703d836eccdef210b88ea83908b">llvm::ARMTargetLowering::isLegalAddImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#abb7f063013825d86c8d8d483e83d1123">llvm::ARMTargetLowering::isLegalICmpImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#af1478848ccc7623d55d4666d293bb6d5">llvm::ARMTargetLowering::isMaskAndCmp0FoldingBeneficial</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a451967ce905a75f6dab090fe57a854d7">anonymous{ARMAsmParser.cpp}::ARMOperand::isModImmNeg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a53ec133dbc14254b3990416b05e0e0a8">anonymous{ARMAsmParser.cpp}::ARMOperand::isModImmNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac026c42d33e80060e878a29358f2ed6a">IsSingleInstrConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f28245e9d46c733c5ac7db5a5fbe27e">llvm::LowerARMMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#adb4ff7051f9fd7cfa91a1b20be1ac880">llvm::ARMTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#abc5aa54b2e18ae6a32233d406f5e004d">llvm::ARMInstPrinter::printModImmOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a>.</p>

</div>
</div>

### getSOImmValImm() {#aa28577d702e2a74b175b2eee75f7efc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getSOImmValImm (unsigned Imm)</td>
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

<p>getSOImmValImm - Given an encoded imm field for the reg/imm form, return the 8-bit imm value.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>

</div>
</div>

### getSOImmValRot() {#a4c3066ac7186d7d02127d1073ca3e1cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getSOImmValRot (unsigned Imm)</td>
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

<p>getSOImmValRot - Given an encoded imm field for the reg/imm form, return the rotate amount.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>

</div>
</div>

### getSOImmValRotate() {#a2c5994cbbea4a8c597898c689d92a5b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getSOImmValRotate (unsigned Imm)</td>
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

<p>getSOImmValRotate - Try to handle Imm with an immediate shifter operand, computing the rotate amount to use.</p>


<p>If this immediate value cannot be handled with a single shifter-op, determine a good rotate amount that will take a maximal chunk of bits out of the immediate.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae917ff404aade469cb9d3780515660ad">llvm::emitARMRegPlusImmediate</a>, <a href="#abbbd359eefeb5aed59eecadddd4bf756">getSOImmTwoPartFirst</a>, <a href="#a605dd3e1bea15f2c42b7efa063273e1f">getSOImmTwoPartSecond</a>, <a href="#a0f3447f06da0010c13eeb865004f71ca">getSOImmVal</a>, <a href="#a6581a1f491b4f01c6b93d63ea095f5b6">isSOImmTwoPartVal</a>, <a href="#a5f539636d1f1c4e75b426059664fa022">isSOImmTwoPartValNeg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a>.</p>

</div>
</div>

### getSORegOffset() {#a0d941a5b2ae5980beb76d03048a24eb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getSORegOffset (unsigned Op)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#af8add502f893b4010205b17073765b2a">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getSORegImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a09fa22f02fc647788a789f02be74a675">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getSORegRegOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a1da732422b6fbb7d5cebd2be149c5928">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getT2SORegOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#adf279a75270e2561fb5ce6d4128ad4f4">llvm::ARMBaseInstrInfo::isSwiftFastImmShift</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a97d0066eae87ce228a58774409c88425">llvm::ARMInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ab73d074818c0d30f4ebbfe219bbab543">llvm::ARMInstPrinter::printSORegImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a14ed66f2387fda436642c97dc961337e">llvm::ARMInstPrinter::printSORegRegOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a4845c08d13cf2dcb721210018974029d">llvm::ARMInstPrinter::printT2SOOperand</a>.</p>

</div>
</div>

### getSORegOpc() {#a6f904876469fc050db9a5723a79d1200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getSORegOpc (<a href="#a76f5f9f36bbd9f03c844c5b565f239ef">ShiftOpc</a> ShOp, unsigned Imm)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c3ccc7ccc252771afe2c5992496a232">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegShiftedImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#acec3b6c59168a1ad077d5aeb5e00a83d">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegShiftedRegOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a0bd30ba570d7cadf1358f8054ffe4af3">emitAligningInstructions</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a32d2decc2fbd86ebc9e635bc3aaf56d9">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectImmShifterOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ab301fda1e7e3cd7b76586ed7233df73a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectRegShifterOperand</a>.</p>

</div>
</div>

### getSORegShOp() {#a552f0f6a6cad1279707100bfe7fc3e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShiftOpc llvm::ARM_AM::getSORegShOp (unsigned Op)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#af8add502f893b4010205b17073765b2a">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getSORegImmOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a09fa22f02fc647788a789f02be74a675">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getSORegRegOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a1da732422b6fbb7d5cebd2be149c5928">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getT2SORegOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#adf279a75270e2561fb5ce6d4128ad4f4">llvm::ARMBaseInstrInfo::isSwiftFastImmShift</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a97d0066eae87ce228a58774409c88425">llvm::ARMInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ab73d074818c0d30f4ebbfe219bbab543">llvm::ARMInstPrinter::printSORegImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a14ed66f2387fda436642c97dc961337e">llvm::ARMInstPrinter::printSORegRegOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a4845c08d13cf2dcb721210018974029d">llvm::ARMInstPrinter::printT2SOOperand</a>.</p>

</div>
</div>

### getT2SOImmTwoPartFirst() {#aa9be15b1cfdccd1e45bcbec61d2f111a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getT2SOImmTwoPartFirst (unsigned Imm)</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3d6b5f20dd274d971ef924f3e2a29d1a">getT2SOImmVal</a>, <a href="#a14ebcc861ad7837c358e58dc41168798">getT2SOImmValRotate</a>, <a href="#a846cf4e09d203a53ff1639aee204c4bb">getT2SOImmValSplatVal</a>, <a href="#aace5db47fb82e762bb6ac3aef10716cb">isT2SOImmTwoPartVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a> and <a href="#a785452529e8d32f5611eea90afe4256a">getT2SOImmTwoPartSecond</a>.</p>

</div>
</div>

### getT2SOImmTwoPartSecond() {#a785452529e8d32f5611eea90afe4256a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getT2SOImmTwoPartSecond (unsigned Imm)</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa9be15b1cfdccd1e45bcbec61d2f111a">getT2SOImmTwoPartFirst</a> and <a href="#a3d6b5f20dd274d971ef924f3e2a29d1a">getT2SOImmVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>.</p>

</div>
</div>

### getT2SOImmVal() {#a3d6b5f20dd274d971ef924f3e2a29d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getT2SOImmVal (unsigned Arg)</td>
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

<p>getT2SOImmVal - Given a 32-bit immediate, if it is something that can fit into a Thumb-2 shifter_operand immediate operand, return the 12-bit encoding for it.</p>


<p>If not, return -1. See <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Reference Manual A6.3.2.</p>


<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a4287f784a134193f258e6709d8e6ed21">getT2SOImmValRotateVal</a>, <a href="#a846cf4e09d203a53ff1639aee204c4bb">getT2SOImmValSplatVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acd2d48bd67d42ac499c2b0acdef4c2c3">llvm::ARMAsmBackend::adjustFixupValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabff304f51525ece8028bf8e9b1c3614">llvm::ConstantMaterializationCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaee29fd8c447694396529bd6a468a6f">llvm::emitT2RegPlusImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a41c8a4fccc70b2cde9a38d48c5a6ba9d">llvm::ARMTTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ab73e06d0bd809df774a1c115ccf6bb74">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getT2SOImmOpValue</a>, <a href="#aa9be15b1cfdccd1e45bcbec61d2f111a">getT2SOImmTwoPartFirst</a>, <a href="#a785452529e8d32f5611eea90afe4256a">getT2SOImmTwoPartSecond</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a4e5be3ed681d1e38a442c45e957c3269">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::is_t2_so_imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ad62b6e205d4853e3c486ccd93c456115">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::is_t2_so_imm_not</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2dd0b703d836eccdef210b88ea83908b">llvm::ARMTargetLowering::isLegalAddImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#abb7f063013825d86c8d8d483e83d1123">llvm::ARMTargetLowering::isLegalICmpImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#af1478848ccc7623d55d4666d293bb6d5">llvm::ARMTargetLowering::isMaskAndCmp0FoldingBeneficial</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af5ac50dd86f6113e4a16ebac72c0ddce">anonymous{ARMAsmParser.cpp}::ARMOperand::isT2SOImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aeaff465539f15d8e6657f5f424757374">anonymous{ARMAsmParser.cpp}::ARMOperand::isT2SOImmNeg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a92682818cd914de0ab159350d30ccc50">anonymous{ARMAsmParser.cpp}::ARMOperand::isT2SOImmNot</a>, <a href="#aace5db47fb82e762bb6ac3aef10716cb">isT2SOImmTwoPartVal</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#adb4ff7051f9fd7cfa91a1b20be1ac880">llvm::ARMTargetLowering::LowerAsmOperandForConstraint</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>.</p>

</div>
</div>

### getT2SOImmValRotate() {#a14ebcc861ad7837c358e58dc41168798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getT2SOImmValRotate (unsigned V)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>.</p>


<p>Referenced by <a href="#aa9be15b1cfdccd1e45bcbec61d2f111a">getT2SOImmTwoPartFirst</a> and <a href="#aace5db47fb82e762bb6ac3aef10716cb">isT2SOImmTwoPartVal</a>.</p>

</div>
</div>

### getT2SOImmValRotateVal() {#a4287f784a134193f258e6709d8e6ed21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getT2SOImmValRotateVal (unsigned V)</td>
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

<p>getT2SOImmValRotateVal - Return the 12-bit encoded representation if the specified value is a rotated 8-bit value.</p>


<p>Return -1 if no rotation encoding is possible. See <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Reference Manual A6.3.2.</p>


<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="#a3d6b5f20dd274d971ef924f3e2a29d1a">getT2SOImmVal</a>.</p>

</div>
</div>

### getT2SOImmValSplatVal() {#a846cf4e09d203a53ff1639aee204c4bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARM_AM::getT2SOImmValSplatVal (unsigned V)</td>
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

<p>getT2SOImmValSplat - Return the 12-bit encoded representation if the specified value can be obtained by splatting the low 8 bits into every other byte or every byte of a 32-bit value.</p>


<p>i.e., 00000000 00000000 00000000 abcdefgh control = 0 00000000 abcdefgh 00000000 abcdefgh control = 1 abcdefgh 00000000 abcdefgh 00000000 control = 2 abcdefgh abcdefgh abcdefgh abcdefgh control = 3 Return -1 if none of the above apply. See <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Reference Manual A6.3.2.</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="#aa9be15b1cfdccd1e45bcbec61d2f111a">getT2SOImmTwoPartFirst</a>, <a href="#a3d6b5f20dd274d971ef924f3e2a29d1a">getT2SOImmVal</a> and <a href="#aace5db47fb82e762bb6ac3aef10716cb">isT2SOImmTwoPartVal</a>.</p>

</div>
</div>

### getThumbImm16ValShift() {#a6b588210115f426a0dc1a275bf2a882d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getThumbImm16ValShift (unsigned Imm)</td>
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

<p>getThumbImm16ValShift - Try to handle Imm with a 16-bit immediate followed by a left shift.</p>


<p>Returns the shift amount to use.</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>.</p>


<p>Referenced by <a href="#af77cc47d2681646373c08d84fb562197">isThumbImm16ShiftedVal</a>.</p>

</div>
</div>

### getThumbImmNonShiftedVal() {#a2b647b539d9f74cb48bbc53b2dac3e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getThumbImmNonShiftedVal (unsigned V)</td>
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

<p>getThumbImmNonShiftedVal - If V is a value that satisfies isThumbImmShiftedVal, return the non-shiftd value.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="#aecca4b0d3d0719e4b0eaf0fbe664b853">getThumbImmValShift</a>.</p>

</div>
</div>

### getThumbImmValShift() {#aecca4b0d3d0719e4b0eaf0fbe664b853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getThumbImmValShift (unsigned Imm)</td>
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

<p>getThumbImmValShift - Try to handle Imm with a 8-bit immediate followed by a left shift.</p>


<p>Returns the shift amount to use.</p>


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>.</p>


<p>Referenced by <a href="#a2b647b539d9f74cb48bbc53b2dac3e03">getThumbImmNonShiftedVal</a> and <a href="#a2cd3a9f6f0047c1989e09ba2e317fe64">isThumbImmShiftedVal</a>.</p>

</div>
</div>

### getVMOVModImmOpCmode() {#a60bd6c9116ccabdb6ec74c7708c47bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getVMOVModImmOpCmode (unsigned ModImm)</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="#a1142830159ad93c394b72a09905a51fd">decodeVMOVModImm</a>.</p>

</div>
</div>

### getVMOVModImmVal() {#a3b853e6b0e974e6683f9c88d7661879f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARM_AM::getVMOVModImmVal (unsigned ModImm)</td>
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



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Referenced by <a href="#a1142830159ad93c394b72a09905a51fd">decodeVMOVModImm</a>.</p>

</div>
</div>

### isNEONBytesplat() {#ab8a25efc8e931d4e989a4df264942e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM_AM::isNEONBytesplat (unsigned Value, unsigned Size)</td>
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



<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a5d0abf06ee7ecd205a1faea528698a78">isNEONi16splat</a> and <a href="#a6bfe2dce3ac76bfe25bd3ec43de6da8f">isNEONi32splat</a>.</p>

</div>
</div>

### isNEONi16splat() {#a5d0abf06ee7ecd205a1faea528698a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM_AM::isNEONi16splat (unsigned Value)</td>
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

<p>Checks if <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is a correct immediate for instructions like VBIC/VORR.</p>

<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="#ab8a25efc8e931d4e989a4df264942e99">isNEONBytesplat</a>.</p>


<p>Referenced by <a href="#a1f85a007bf3e4a317a714e2e07680c47">encodeNEONi16splat</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa4fdbad91ab26ac2fd497f3be95650a6">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi16splat</a> and <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aabee712524ecfccb59100b57fe6983df">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi16splatNot</a>.</p>

</div>
</div>

### isNEONi32splat() {#a6bfe2dce3ac76bfe25bd3ec43de6da8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM_AM::isNEONi32splat (unsigned Value)</td>
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

<p>Checks if <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is a correct immediate for instructions like VBIC/VORR.</p>

<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="#ab8a25efc8e931d4e989a4df264942e99">isNEONBytesplat</a>.</p>


<p>Referenced by <a href="#aab5a8f472308dc5564856a478b255df8">encodeNEONi32splat</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae4541e80f428c954ad89047fec95437a">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi32splat</a> and <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a294a72efdd650ad80e5bb6eec16c8e86">anonymous{ARMAsmParser.cpp}::ARMOperand::isNEONi32splatNot</a>.</p>

</div>
</div>

### isSOImmTwoPartVal() {#a6581a1f491b4f01c6b93d63ea095f5b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM_AM::isSOImmTwoPartVal (unsigned V)</td>
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

<p>isSOImmTwoPartVal - Return true if the specified value can be obtained by or'ing together two SOImmVal's.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a2c5994cbbea4a8c597898c689d92a5b1">getSOImmValRotate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aabff304f51525ece8028bf8e9b1c3614">llvm::ConstantMaterializationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a> and <a href="#a5f539636d1f1c4e75b426059664fa022">isSOImmTwoPartValNeg</a>.</p>

</div>
</div>

### isSOImmTwoPartValNeg() {#a5f539636d1f1c4e75b426059664fa022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM_AM::isSOImmTwoPartValNeg (unsigned V)</td>
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

<p>isSOImmTwoPartValNeg - Return true if the specified value can be obtained by two SOImmVal, that -V = First + Second.</p>


<p>"R+V" can be optimized to (sub (sub R, First), Second). "R=V" can be optimized to (sub (mvn R, ~(-First)), Second).</p>


<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#abbbd359eefeb5aed59eecadddd4bf756">getSOImmTwoPartFirst</a>, <a href="#a2c5994cbbea4a8c597898c689d92a5b1">getSOImmValRotate</a>, <a href="#a6581a1f491b4f01c6b93d63ea095f5b6">isSOImmTwoPartVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aabff304f51525ece8028bf8e9b1c3614">llvm::ConstantMaterializationCost</a>.</p>

</div>
</div>

### isT2SOImmTwoPartVal() {#aace5db47fb82e762bb6ac3aef10716cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM_AM::isT2SOImmTwoPartVal (unsigned Imm)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>References <a href="#a3d6b5f20dd274d971ef924f3e2a29d1a">getT2SOImmVal</a>, <a href="#a14ebcc861ad7837c358e58dc41168798">getT2SOImmValRotate</a>, <a href="#a846cf4e09d203a53ff1639aee204c4bb">getT2SOImmValSplatVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a> and <a href="#aa9be15b1cfdccd1e45bcbec61d2f111a">getT2SOImmTwoPartFirst</a>.</p>

</div>
</div>

### isThumbImm16ShiftedVal() {#af77cc47d2681646373c08d84fb562197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM_AM::isThumbImm16ShiftedVal (unsigned V)</td>
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

<p>isThumbImm16ShiftedVal - Return true if the specified value can be obtained by left shifting a 16-bit immediate.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="#a6b588210115f426a0dc1a275bf2a882d">getThumbImm16ValShift</a>.</p>

</div>
</div>

### isThumbImmShiftedVal() {#a2cd3a9f6f0047c1989e09ba2e317fe64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM_AM::isThumbImmShiftedVal (unsigned V)</td>
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

<p>isThumbImmShiftedVal - Return true if the specified value can be obtained by left shifting a 8-bit immediate.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a>.</p>


<p>Reference <a href="#aecca4b0d3d0719e4b0eaf0fbe664b853">getThumbImmValShift</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aabff304f51525ece8028bf8e9b1c3614">llvm::ConstantMaterializationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a41c8a4fccc70b2cde9a38d48c5a6ba9d">llvm::ARMTTIImpl::getIntImmCost</a> and <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#adb4ff7051f9fd7cfa91a1b20be1ac880">llvm::ARMTargetLowering::LowerAsmOperandForConstraint</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armselectiondaginfo-h">ARMSelectionDAGInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">ARMAddressingModes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
