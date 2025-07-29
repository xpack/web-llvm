---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/systemz
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `SystemZ` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::SystemZ { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/systemz/gprregs">GPRRegs</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FixupKind { <a href="#acdd1cc3b030808a5dfb5391dd85c9c1f">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1eeff3b678159f6f48d637f751190f">isImmLL</a> (uint64_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd6d77b3825963e249e2ab55a4391ad">isImmLH</a> (uint64_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352bda2d94f28fc61b2e20e81596d42a">isImmHL</a> (uint64_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0515f68f4986435d7959f0f675004699">isImmHH</a> (uint64_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04536b57e902c1325e42672d3446d9f">isImmLF</a> (uint64_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a784733db49f741774a8d9dc6e29376a7">isImmHF</a> (uint64_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6b3ab021f60b6ac03c231bb3898193b">getTwoOperandOpcode</a> (uint16_t Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2614812ff7afa915f6bb8531d99d9504">getTargetMemOpcode</a> (uint16_t Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66e6ac173792fcc77b6d3ef9bba5cd8c">reverseCCMask</a> (unsigned CCMask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643c44e66aa189f635b59361c6e80179">emitBlockAfter</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f28b32cebb99746b65b07147c24d6cf">splitBlockAfter</a> (MachineBasicBlock::iterator MI, MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a175299250e6f7f5542fb5474ff0c9c6a">splitBlockBefore</a> (MachineBasicBlock::iterator MI, MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c753ea2aeb0c5e11f7fead28faadca">even128</a> (bool Is32bit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02cb8b8ba65c748e6794306363b3cd94">odd128</a> (bool Is32bit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9944e1adfb7c602c387d072a76d174">isHighReg</a> (unsigned int Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae012bef1e76a0eada343c213f7794dd3">MCFixupKindInfos</a>[SystemZ::NumTargetFixupKinds] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> = 1 &lt;&lt; 3</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> = 1 &lt;&lt; 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a> = 1 &lt;&lt; 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a> = 1 &lt;&lt; 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b7b2d0aec8aef3f4e20e1ac4a7ea9c0">CCMASK_CMP_EQ</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16fd1071e402b10701ff234436a9054">CCMASK_CMP_LT</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47bab903d4239eca9c0ad8b19126a3d8">CCMASK_CMP_GT</a> = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3393456d140e6fdf882fb8020470559">CCMASK_CMP_NE</a> = <a href="#ac16fd1071e402b10701ff234436a9054">CCMASK_CMP_LT</a> | <a href="#a47bab903d4239eca9c0ad8b19126a3d8">CCMASK_CMP_GT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7688fc241dcfa055b72c7c5f53e59ebe">CCMASK_CMP_LE</a> = <a href="#a7b7b2d0aec8aef3f4e20e1ac4a7ea9c0">CCMASK_CMP_EQ</a> | <a href="#ac16fd1071e402b10701ff234436a9054">CCMASK_CMP_LT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f861bbe2487d9db7376af85935d577">CCMASK_CMP_GE</a> = <a href="#a7b7b2d0aec8aef3f4e20e1ac4a7ea9c0">CCMASK_CMP_EQ</a> | <a href="#a47bab903d4239eca9c0ad8b19126a3d8">CCMASK_CMP_GT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7beaaa9f7b990110ddc4447f79e7f75">CCMASK_CMP_UO</a> = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a791c0332209047df92d8cca72f02d4d6">CCMASK_CMP_O</a> = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a> ^ <a href="#af7beaaa9f7b990110ddc4447f79e7f75">CCMASK_CMP_UO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85e05170e3e584f721ea86c6b04edaba">CCMASK_ICMP</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26577621fc2dfc9c5914848e96ed561b">CCMASK_FCMP</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02524db11131e9c6d35a4d5c12377ab5">CCMASK_ARITH_EQ</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48bb27b139c89e514374ca2d27faf0bf">CCMASK_ARITH_LT</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a493c45d2e3c3566a957c43893ee11a85">CCMASK_ARITH_GT</a> = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1b65a23b9d15b3e33d48dc0d0cd03fa">CCMASK_ARITH_OVERFLOW</a> = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b1771e684fb33863dca4fb1a340a998">CCMASK_ARITH</a> = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b97e5dbaccf2d8c9921f723f13a919">CCMASK_LOGICAL_ZERO</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b8ce409263fdfdd705d2761333bee7">CCMASK_LOGICAL_NONZERO</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2053474c1636d4f1cb6546c27b5a6c86">CCMASK_LOGICAL_CARRY</a> = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b46573a1a5ea03d37a953fb59b7fb8a">CCMASK_LOGICAL_NOCARRY</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d3599e94ab9faee33d0c836d6b3eec">CCMASK_LOGICAL_BORROW</a> = <a href="#a0b46573a1a5ea03d37a953fb59b7fb8a">CCMASK_LOGICAL_NOCARRY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abddf408a72acc49a2bf5f4e9e3576009">CCMASK_LOGICAL_NOBORROW</a> = <a href="#a2053474c1636d4f1cb6546c27b5a6c86">CCMASK_LOGICAL_CARRY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af880698e310f60da291891652b202243">CCMASK_LOGICAL</a> = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3be9a8b8ae565e100dbed2b82f7b83">CCMASK_CS_EQ</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab403139e328d7009a132de101d0f83d6">CCMASK_CS_NE</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4803f64355f5391993846b686567e6">CCMASK_CS</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bdd1364943002f89453bf957b7ec5da">CCMASK_SRST_FOUND</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04fc78028c662e728797fcef714d6571">CCMASK_SRST_NOTFOUND</a> = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1255c0721c391f699043d377fad5f385">CCMASK_SRST</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a699d3b4e6df58702662a551f057d5b7d">CCMASK_TM_ALL_0</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bbd3d7ea24fd9daa28adf150c298230">CCMASK_TM_MIXED_MSB_0</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01e00083927442effc2fc0e69c3266c">CCMASK_TM_MIXED_MSB_1</a> = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2859cce510e0f827fad9b930db4e33">CCMASK_TM_ALL_1</a> = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e293fb47ef784f0daaf05f29112fae">CCMASK_TM_SOME_0</a> = <a href="#adb2859cce510e0f827fad9b930db4e33">CCMASK_TM_ALL_1</a> ^ <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b845955a6b886984987461764d38a24">CCMASK_TM_SOME_1</a> = <a href="#a699d3b4e6df58702662a551f057d5b7d">CCMASK_TM_ALL_0</a> ^ <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab19b53413e71bb3bbe62b7a56eec0c31">CCMASK_TM_MSB_0</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9fcd11e3eaad13e9ff97ae9fadcbdd1">CCMASK_TM_MSB_1</a> = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec4fb698c5d43de6d9ae76ca73c8567">CCMASK_TM</a> = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a0613b17288cbaf52e44d9c5957620">CCMASK_TBEGIN_STARTED</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b4e14880baa3290c611f04c485500b">CCMASK_TBEGIN_INDETERMINATE</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb3cabecd21ffae286bf96b4d65ba77">CCMASK_TBEGIN_TRANSIENT</a> = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e1db577554fb37cb6249e975d8c83c3">CCMASK_TBEGIN_PERSISTENT</a> = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10264f2b67d2489c38a5acaefc35bcf9">CCMASK_TBEGIN</a> = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f373c21809a44e48b9980a2eb625976">CCMASK_TEND_TX</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12e4171dfe9a07f55efe667c4a532da8">CCMASK_TEND_NOTX</a> = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a59ee43810b1853e8155f59ef234138">CCMASK_TEND</a> = <a href="#a5f373c21809a44e48b9980a2eb625976">CCMASK_TEND_TX</a> | <a href="#a12e4171dfe9a07f55efe667c4a532da8">CCMASK_TEND_NOTX</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8820fe17e5318116093b3df3a06cfc29">CCMASK_VCMP_ALL</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fec827d2e63a7b71dc25b2aa402223c">CCMASK_VCMP_MIXED</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf367a88651521ca2060ab85d3adc22">CCMASK_VCMP_NONE</a> = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa079cd5c3e36179473b7cd34f6bab1b">CCMASK_VCMP</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f4f9f4cb43d7f7c80ee7368ddf7d9a">CCMASK_TDC_NOMATCH</a> = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab3f4c18e00736ab2ecdf2dc8996739c">CCMASK_TDC_MATCH</a> = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f9d9fcc1d3d15be2fabe0e1a76e998">CCMASK_TDC</a> = <a href="#a86f4f9f4cb43d7f7c80ee7368ddf7d9a">CCMASK_TDC_NOMATCH</a> | <a href="#aab3f4c18e00736ab2ecdf2dc8996739c">CCMASK_TDC_MATCH</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a739201f9c14177326c5b3dd889dc51a5">IPM_CC</a> = 28</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e142d77640c7a070a63fd1bb039c9b4">PFD_READ</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b28944cf9ea0544e947a78b17a97d2">PFD_WRITE</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbbdfbfe148fc33cb4e346afe41bc227">TDCMASK_ZERO_PLUS</a> = 0x800</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c071354267a0dd9edc213f8075003f">TDCMASK_ZERO_MINUS</a> = 0x400</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479ce3d3ec70c69c25bc29f6c6c4779a">TDCMASK_NORMAL_PLUS</a> = 0x200</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2411f0aafb9c6976e0576f4436028b11">TDCMASK_NORMAL_MINUS</a> = 0x100</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0630cb0205321fdab03973e313a7e5">TDCMASK_SUBNORMAL_PLUS</a> = 0x080</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ace169b9f73f479ff985e6bb66fdf9a">TDCMASK_SUBNORMAL_MINUS</a> = 0x040</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65213203a61a63b48c9c8f7b3df4e4bf">TDCMASK_INFINITY_PLUS</a> = 0x020</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833c07068bfc5e817fa44b7a21d263ad">TDCMASK_INFINITY_MINUS</a> = 0x010</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad119089dab3a062202613393618950c6">TDCMASK_QNAN_PLUS</a> = 0x008</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4acbd58350f3a992b4c4db44f3b7402f">TDCMASK_QNAN_MINUS</a> = 0x004</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab66361196c50a1272a4f43f67724e47d">TDCMASK_SNAN_PLUS</a> = 0x002</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3c901268624324036a2fc2d044b6d6">TDCMASK_SNAN_MINUS</a> = 0x001</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc9e33baff99f198d767db21741dd89">TDCMASK_ZERO</a> = <a href="#acbbdfbfe148fc33cb4e346afe41bc227">TDCMASK_ZERO_PLUS</a> | <a href="#ad1c071354267a0dd9edc213f8075003f">TDCMASK_ZERO_MINUS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829200dd89fca8386542598e4c93568a">TDCMASK_POSITIVE</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ec9588d0d0b4a551951b4149f4c85c">TDCMASK_NEGATIVE</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa43b1c8cf2b8e3c65492d4e21831331b">TDCMASK_NAN</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae47feb84c571a5baf3d91b062bf3d1f3">TDCMASK_PLUS</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da0df1f710c171c3fb943d4cfab0ab3">TDCMASK_MINUS</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cbdca40acdaa745873e4ba59d77425c">TDCMASK_ALL</a> = <a href="#ae47feb84c571a5baf3d91b062bf3d1f3">TDCMASK_PLUS</a> | <a href="#a2da0df1f710c171c3fb943d4cfab0ab3">TDCMASK_MINUS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2f6288a79b32c4bc9f22fe3f3222b2">VectorBits</a> = 128</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8100b30b39f455a1b99d9d421a5b8f3b">VectorBytes</a> = <a href="#a5e2f6288a79b32c4bc9f22fe3f3222b2">VectorBits</a> / 8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbb3aafa6e9294472bd94ff65ccfa355">ELFNumArgGPRs</a> = 5</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58bf05e46b0dbaad61b7a7e66a73758">ELFArgGPRs</a>[ELFNumArgGPRs] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6601b43292876e92cb9891a8f0f97f1">ELFNumArgFPRs</a> = 4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1740d369e735cb5533fc7ab47c1b61a8">ELFArgFPRs</a>[ELFNumArgFPRs] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880191f32861e3017b27d79724a2f270">XPLINK64NumArgGPRs</a> = 3</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c04579e3a921c01f95cb27f2ab243e">XPLINK64ArgGPRs</a>[XPLINK64NumArgGPRs] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674b14434074a552490c065536d67242">XPLINK64NumArgFPRs</a> = 4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c0cc6320c12921a5214379d390875d">XPLINK64ArgFPRs</a>[XPLINK64NumArgFPRs] = ...</td>
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

### FixupKind {#acdd1cc3b030808a5dfb5391dd85c9c1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SystemZ::FixupKind </td>
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
<td class="doxyEnumItemName">FK_390_PC12DBL<a id="acdd1cc3b030808a5dfb5391dd85c9c1faba9cfa22a7020a21476cff5ab2f0fb10"></a></td>
<td class="doxyEnumItemDescription"> (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_PC16DBL<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa7d3a87e2217d3174daf923e3e9d22950"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_PC24DBL<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa81be4ca2ec8b11ae402b2e5d23fd2807"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_PC32DBL<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa5a1d88ad9be241f013a5ff3fee254aa3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_TLS_CALL<a id="acdd1cc3b030808a5dfb5391dd85c9c1fab7ecc8ff7e95f6afadd1e92b80f7910e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_S8Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fae1887e29eee4dcca67d9ef67f1e9f16f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_S16Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa38ee2bc508a03f304fe345c0ec73b49d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_S20Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa6a7e1d749e592d2f7472836b629ba6e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_S32Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fac9cd9d899f6c5542f640727a266a28d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_U1Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1faee7731e49a678c8cc74d0130cc15cb6a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_U2Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa69a869f7e5f4ce07ede4156252979df1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_U3Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa780a8e9dd0193e538dd218d07d1474af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_U4Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fadf56ccfe2b002a3ad2fda4c0480b63b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_U8Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa090768997a29e237dc6f8fc9f1897c8b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_U12Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa4e4c0e7e027d837898b944c120704e85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_U16Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa586fe3a11b9df944bcc112a6f714afe9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_U32Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa1e07df5fd3b4dfca3758016e9b8ab13e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FK_390_U48Imm<a id="acdd1cc3b030808a5dfb5391dd85c9c1faa746115cc0354ae7dbbc1cb36b5af6ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastTargetFixupKind<a id="acdd1cc3b030808a5dfb5391dd85c9c1fa9406d96962372bfbb654803801962650"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="acdd1cc3b030808a5dfb5391dd85c9c1faa5594219f25443beb78c43790b63e1ba"></a></td>
<td class="doxyEnumItemDescription"> (= LastTargetFixupKind - FirstTargetFixupKind)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcfixups-h">SystemZMCFixups.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### emitBlockAfter() {#a643c44e66aa189f635b59361c6e80179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::SystemZ::emitBlockAfter (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-h">SystemZInstrInfo.h</a>, definition at line 2169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp">SystemZInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="#a9f28b32cebb99746b65b07147c24d6cf">splitBlockAfter</a> and <a href="#a175299250e6f7f5542fb5474ff0c9c6a">splitBlockBefore</a>.</p>

</div>
</div>

### even128() {#ad1c753ea2aeb0c5e11f7fead28faadca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZ::even128 (bool Is32bit)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-h">SystemZRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a18ab090710e4d4e67339c31cd8d4bc8b">lowerGR128Binary</a>.</p>

</div>
</div>

### getTargetMemOpcode() {#a2614812ff7afa915f6bb8531d99d9504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SystemZ::getTargetMemOpcode (uint16_t Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-h">SystemZInstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>.</p>

</div>
</div>

### getTwoOperandOpcode() {#ac6b3ab021f60b6ac03c231bb3898193b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SystemZ::getTwoOperandOpcode (uint16_t Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-h">SystemZInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a> and <a href="/web-llvm/docs/api/classes/anonymous-systemzshorteninst-cpp-/systemzshorteninst/#a38b3d652a50cfafb01e63dca05a1f489">anonymous{SystemZShortenInst.cpp}::SystemZShortenInst::processBlock</a>.</p>

</div>
</div>

### isHighReg() {#ade9944e1adfb7c602c387d072a76d174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZ::isHighReg (unsigned int Reg)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-h">SystemZRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ac266bb55016e51ee04a40cd1ad762612">llvm::SystemZInstrInfo::expandPostRAPseudo</a>.</p>

</div>
</div>

### isImmHF() {#a784733db49f741774a8d9dc6e29376a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZ::isImmHF (uint64_t Val)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a977ad76f842f5addf1b023121d96465e">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::Select</a>.</p>

</div>
</div>

### isImmHH() {#a0515f68f4986435d7959f0f675004699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZ::isImmHH (uint64_t Val)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### isImmHL() {#a352bda2d94f28fc61b2e20e81596d42a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZ::isImmHL (uint64_t Val)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### isImmLF() {#ad04536b57e902c1325e42672d3446d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZ::isImmLF (uint64_t Val)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a977ad76f842f5addf1b023121d96465e">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::Select</a>.</p>

</div>
</div>

### isImmLH() {#a5fd6d77b3825963e249e2ab55a4391ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZ::isImmLH (uint64_t Val)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afc45f79c5209c1eb89dc79708ff46a6b">llvm::SystemZInstrInfo::loadImmediate</a>.</p>

</div>
</div>

### isImmLL() {#a5d1eeff3b678159f6f48d637f751190f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZ::isImmLL (uint64_t Val)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afc45f79c5209c1eb89dc79708ff46a6b">llvm::SystemZInstrInfo::loadImmediate</a>.</p>

</div>
</div>

### odd128() {#a02cb8b8ba65c748e6794306363b3cd94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZ::odd128 (bool Is32bit)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-h">SystemZRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a18ab090710e4d4e67339c31cd8d4bc8b">lowerGR128Binary</a>.</p>

</div>
</div>

### reverseCCMask() {#a66e6ac173792fcc77b6d3ef9bba5cd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZ::reverseCCMask (unsigned CCMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-h">SystemZInstrInfo.h</a>, definition at line 2162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp">SystemZInstrInfo.cpp</a>.</p>


<p>References <a href="#a7b7b2d0aec8aef3f4e20e1ac4a7ea9c0">CCMASK_CMP_EQ</a>, <a href="#a47bab903d4239eca9c0ad8b19126a3d8">CCMASK_CMP_GT</a>, <a href="#ac16fd1071e402b10701ff234436a9054">CCMASK_CMP_LT</a> and <a href="#af7beaaa9f7b990110ddc4447f79e7f75">CCMASK_CMP_UO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a4f999e29e1c7e89f1f87f7ff3f3fa379">adjustForFNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a62454aa5151d369549b3c0414bdf5646">combineCCMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac8e70a2e70e45733c882bb7b103a9c88">getCmp</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ae97bb6b91cff3e18475ab68012287cc2">llvm::SystemZInstrInfo::prepareCompareSwapOperands</a>.</p>

</div>
</div>

### splitBlockAfter() {#a9f28b32cebb99746b65b07147c24d6cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::SystemZ::splitBlockAfter (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-h">SystemZInstrInfo.h</a>, definition at line 2176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp">SystemZInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="#a643c44e66aa189f635b59361c6e80179">emitBlockAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>

</div>
</div>

### splitBlockBefore() {#a175299250e6f7f5542fb5474ff0c9c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::SystemZ::splitBlockBefore (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-h">SystemZInstrInfo.h</a>, definition at line 2185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp">SystemZInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="#a643c44e66aa189f635b59361c6e80179">emitBlockAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CCMASK\_0 {#a14b31497ae4b898370352164acc3b5f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_0 = 1 &lt;&lt; 3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a28e0a0edbf89edb6e77b86a94974848d">getIPMConversion</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac7a6aa45c36b2dbf876de7b60408a7de">isIntrinsicWithCC</a>.</p>

</div>
</div>

### CCMASK\_1 {#a3e4f7a3f70ff22719bebc0dedfa6f5d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_1 = 1 &lt;&lt; 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a28e0a0edbf89edb6e77b86a94974848d">getIPMConversion</a>.</p>

</div>
</div>

### CCMASK\_2 {#aedfe0ac9b427e32574e7eafa44518c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_2 = 1 &lt;&lt; 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a28e0a0edbf89edb6e77b86a94974848d">getIPMConversion</a>.</p>

</div>
</div>

### CCMASK\_3 {#abfe77bb849cf01dbc4b6fc10e091395e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_3 = 1 &lt;&lt; 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a28e0a0edbf89edb6e77b86a94974848d">getIPMConversion</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac7a6aa45c36b2dbf876de7b60408a7de">isIntrinsicWithCC</a>.</p>

</div>
</div>

### CCMASK\_ANY {#a56f5d98f2d53e513dc3f8833d4dd4b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_ANY = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afa68867e0d5d04298782e0548047244d">llvm::SystemZInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#aabf36691d1f42a89ca0b9d26e1d8eddd">llvm::SystemZInstrInfo::getBranchInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac7a6aa45c36b2dbf876de7b60408a7de">isIntrinsicWithCC</a>.</p>

</div>
</div>

### CCMASK\_ARITH {#a5b1771e684fb33863dca4fb1a340a998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_ARITH = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_ARITH\_EQ {#a02524db11131e9c6d35a4d5c12377ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_ARITH_EQ = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_ARITH\_GT {#a493c45d2e3c3566a957c43893ee11a85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_ARITH_GT = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_ARITH\_LT {#a48bb27b139c89e514374ca2d27faf0bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_ARITH_LT = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_ARITH\_OVERFLOW {#ab1b65a23b9d15b3e33d48dc0d0cd03fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_ARITH_OVERFLOW = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_CMP\_EQ {#a7b7b2d0aec8aef3f4e20e1ac4a7ea9c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CMP_EQ = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6d8c34094b346eb0009cabb44bf3eaf7">adjustForSubtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a053ae5bd3db78d3dbd72262ff102989e">adjustForTestUnderMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afeb29018dafc8208209fb0b0e5f1326f">adjustZeroCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a62454aa5151d369549b3c0414bdf5646">combineCCMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac8e70a2e70e45733c882bb7b103a9c88">getCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a03052d442eb8ffe6a37d2b416d1933b2">getI128Select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a> and <a href="#a66e6ac173792fcc77b6d3ef9bba5cd8c">reverseCCMask</a>.</p>

</div>
</div>

### CCMASK\_CMP\_GE {#a03f861bbe2487d9db7376af85935d577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CMP_GE = <a href="#a7b7b2d0aec8aef3f4e20e1ac4a7ea9c0">CCMASK_CMP_EQ</a> | <a href="#a47bab903d4239eca9c0ad8b19126a3d8">CCMASK_CMP_GT</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a0f156137ff6b38d69f721b8ecf164d93">adjustSubwordCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afeb29018dafc8208209fb0b0e5f1326f">adjustZeroCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a218617188d9cc853082ada63dadf38d1">llvm::SystemZTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a03052d442eb8ffe6a37d2b416d1933b2">getI128Select</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_CMP\_GT {#a47bab903d4239eca9c0ad8b19126a3d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CMP_GT = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a053ae5bd3db78d3dbd72262ff102989e">adjustForTestUnderMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a0f156137ff6b38d69f721b8ecf164d93">adjustSubwordCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afeb29018dafc8208209fb0b0e5f1326f">adjustZeroCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a03052d442eb8ffe6a37d2b416d1933b2">getI128Select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a> and <a href="#a66e6ac173792fcc77b6d3ef9bba5cd8c">reverseCCMask</a>.</p>

</div>
</div>

### CCMASK\_CMP\_LE {#a7688fc241dcfa055b72c7c5f53e59ebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CMP_LE = <a href="#a7b7b2d0aec8aef3f4e20e1ac4a7ea9c0">CCMASK_CMP_EQ</a> | <a href="#ac16fd1071e402b10701ff234436a9054">CCMASK_CMP_LT</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a053ae5bd3db78d3dbd72262ff102989e">adjustForTestUnderMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afeb29018dafc8208209fb0b0e5f1326f">adjustZeroCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a218617188d9cc853082ada63dadf38d1">llvm::SystemZTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a03052d442eb8ffe6a37d2b416d1933b2">getI128Select</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_CMP\_LT {#ac16fd1071e402b10701ff234436a9054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CMP_LT = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a0f156137ff6b38d69f721b8ecf164d93">adjustSubwordCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afeb29018dafc8208209fb0b0e5f1326f">adjustZeroCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a03052d442eb8ffe6a37d2b416d1933b2">getI128Select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a> and <a href="#a66e6ac173792fcc77b6d3ef9bba5cd8c">reverseCCMask</a>.</p>

</div>
</div>

### CCMASK\_CMP\_NE {#ac3393456d140e6fdf882fb8020470559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CMP_NE = <a href="#ac16fd1071e402b10701ff234436a9054">CCMASK_CMP_LT</a> | <a href="#a47bab903d4239eca9c0ad8b19126a3d8">CCMASK_CMP_GT</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6d8c34094b346eb0009cabb44bf3eaf7">adjustForSubtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a053ae5bd3db78d3dbd72262ff102989e">adjustForTestUnderMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a62454aa5151d369549b3c0414bdf5646">combineCCMask</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#aabf36691d1f42a89ca0b9d26e1d8eddd">llvm::SystemZInstrInfo::getBranchInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac8e70a2e70e45733c882bb7b103a9c88">getCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a03052d442eb8ffe6a37d2b416d1933b2">getI128Select</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_CMP\_O {#a791c0332209047df92d8cca72f02d4d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CMP_O = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a> ^ <a href="#af7beaaa9f7b990110ddc4447f79e7f75">CCMASK_CMP_UO</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a4407efa7c48f4c4931c04855996069c3">CCMaskForCondCode</a>.</p>

</div>
</div>

### CCMASK\_CMP\_UO {#af7beaaa9f7b990110ddc4447f79e7f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CMP_UO = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a4407efa7c48f4c4931c04855996069c3">CCMaskForCondCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac8e70a2e70e45733c882bb7b103a9c88">getCmp</a> and <a href="#a66e6ac173792fcc77b6d3ef9bba5cd8c">reverseCCMask</a>.</p>

</div>
</div>

### CCMASK\_CS {#a4f4803f64355f5391993846b686567e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CS = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aaa6982f8a2f398fab0881b8806c3ce3f">llvm::SystemZTargetLowering::LowerOperationWrapper</a>.</p>

</div>
</div>

### CCMASK\_CS\_EQ {#a0f3be9a8b8ae565e100dbed2b82f7b83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CS_EQ = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aaa6982f8a2f398fab0881b8806c3ce3f">llvm::SystemZTargetLowering::LowerOperationWrapper</a>.</p>

</div>
</div>

### CCMASK\_CS\_NE {#ab403139e328d7009a132de101d0f83d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_CS_NE = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_FCMP {#a26577621fc2dfc9c5914848e96ed561b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_FCMP = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac8e70a2e70e45733c882bb7b103a9c88">getCmp</a>.</p>

</div>
</div>

### CCMASK\_ICMP {#a85e05170e3e584f721ea86c6b04edaba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_ICMP = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a62454aa5151d369549b3c0414bdf5646">combineCCMask</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#aabf36691d1f42a89ca0b9d26e1d8eddd">llvm::SystemZInstrInfo::getBranchInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac8e70a2e70e45733c882bb7b103a9c88">getCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a>.</p>

</div>
</div>

### CCMASK\_LOGICAL {#af880698e310f60da291891652b202243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_LOGICAL = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_LOGICAL\_BORROW {#af3d3599e94ab9faee33d0c836d6b3eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_LOGICAL_BORROW = <a href="#a0b46573a1a5ea03d37a953fb59b7fb8a">CCMASK_LOGICAL_NOCARRY</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_LOGICAL\_CARRY {#a2053474c1636d4f1cb6546c27b5a6c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_LOGICAL_CARRY = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_LOGICAL\_NOBORROW {#abddf408a72acc49a2bf5f4e9e3576009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_LOGICAL_NOBORROW = <a href="#a2053474c1636d4f1cb6546c27b5a6c86">CCMASK_LOGICAL_CARRY</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_LOGICAL\_NOCARRY {#a0b46573a1a5ea03d37a953fb59b7fb8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_LOGICAL_NOCARRY = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_LOGICAL\_NONZERO {#ac8b8ce409263fdfdd705d2761333bee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_LOGICAL_NONZERO = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_LOGICAL\_ZERO {#a04b97e5dbaccf2d8c9921f723f13a919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_LOGICAL_ZERO = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_SRST {#a1255c0721c391f699043d377fad5f385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_SRST = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzselectiondaginfo/#a1451ff2e7eeaaf042e0e2b557bcaf242">llvm::SystemZSelectionDAGInfo::EmitTargetCodeForMemchr</a>.</p>

</div>
</div>

### CCMASK\_SRST\_FOUND {#a4bdd1364943002f89453bf957b7ec5da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_SRST_FOUND = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzselectiondaginfo/#a1451ff2e7eeaaf042e0e2b557bcaf242">llvm::SystemZSelectionDAGInfo::EmitTargetCodeForMemchr</a>.</p>

</div>
</div>

### CCMASK\_SRST\_NOTFOUND {#a04fc78028c662e728797fcef714d6571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_SRST_NOTFOUND = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_TBEGIN {#a10264f2b67d2489c38a5acaefc35bcf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TBEGIN = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3a3042f33574c00a701a7a1494e79dc5">isIntrinsicWithCCAndChain</a>.</p>

</div>
</div>

### CCMASK\_TBEGIN\_INDETERMINATE {#ac4b4e14880baa3290c611f04c485500b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TBEGIN_INDETERMINATE = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_TBEGIN\_PERSISTENT {#a3e1db577554fb37cb6249e975d8c83c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TBEGIN_PERSISTENT = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_TBEGIN\_STARTED {#aa9a0613b17288cbaf52e44d9c5957620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TBEGIN_STARTED = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_TBEGIN\_TRANSIENT {#a5cb3cabecd21ffae286bf96b4d65ba77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TBEGIN_TRANSIENT = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_TDC {#a24f9d9fcc1d3d15be2fabe0e1a76e998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TDC = <a href="#a86f4f9f4cb43d7f7c80ee7368ddf7d9a">CCMASK_TDC_NOMATCH</a> | <a href="#aab3f4c18e00736ab2ecdf2dc8996739c">CCMASK_TDC_MATCH</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac7a6aa45c36b2dbf876de7b60408a7de">isIntrinsicWithCC</a>.</p>

</div>
</div>

### CCMASK\_TDC\_MATCH {#aab3f4c18e00736ab2ecdf2dc8996739c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TDC_MATCH = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_TDC\_NOMATCH {#a86f4f9f4cb43d7f7c80ee7368ddf7d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TDC_NOMATCH = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_TEND {#a0a59ee43810b1853e8155f59ef234138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TEND = <a href="#a5f373c21809a44e48b9980a2eb625976">CCMASK_TEND_TX</a> | <a href="#a12e4171dfe9a07f55efe667c4a532da8">CCMASK_TEND_NOTX</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3a3042f33574c00a701a7a1494e79dc5">isIntrinsicWithCCAndChain</a>.</p>

</div>
</div>

### CCMASK\_TEND\_NOTX {#a12e4171dfe9a07f55efe667c4a532da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TEND_NOTX = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_TEND\_TX {#a5f373c21809a44e48b9980a2eb625976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TEND_TX = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_TM {#abec4fb698c5d43de6d9ae76ca73c8567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TM = <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a053ae5bd3db78d3dbd72262ff102989e">adjustForTestUnderMask</a>.</p>

</div>
</div>

### CCMASK\_TM\_ALL\_0 {#a699d3b4e6df58702662a551f057d5b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TM_ALL_0 = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_TM\_ALL\_1 {#adb2859cce510e0f827fad9b930db4e33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TM_ALL_1 = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_TM\_MIXED\_MSB\_0 {#a5bbd3d7ea24fd9daa28adf150c298230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TM_MIXED_MSB_0 = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a5b78defab0d2a61959c51c9b9db6ad3e">emitCmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_TM\_MIXED\_MSB\_1 {#ab01e00083927442effc2fc0e69c3266c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TM_MIXED_MSB_1 = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a5b78defab0d2a61959c51c9b9db6ad3e">emitCmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_TM\_MSB\_0 {#ab19b53413e71bb3bbe62b7a56eec0c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TM_MSB_0 = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_TM\_MSB\_1 {#af9fcd11e3eaad13e9ff97ae9fadcbdd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TM_MSB_1 = <a href="#aedfe0ac9b427e32574e7eafa44518c95">CCMASK_2</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_TM\_SOME\_0 {#a27e293fb47ef784f0daaf05f29112fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TM_SOME_0 = <a href="#adb2859cce510e0f827fad9b930db4e33">CCMASK_TM_ALL_1</a> ^ <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_TM\_SOME\_1 {#a1b845955a6b886984987461764d38a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_TM_SOME_1 = <a href="#a699d3b4e6df58702662a551f057d5b7d">CCMASK_TM_ALL_0</a> ^ <a href="#a56f5d98f2d53e513dc3f8833d4dd4b39">CCMASK_ANY</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac64827bbb31c0892fbcae2ed5e439522">getTestUnderMaskCond</a>.</p>

</div>
</div>

### CCMASK\_VCMP {#aaa079cd5c3e36179473b7cd34f6bab1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_VCMP = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a> | <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a> | <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a053ae5bd3db78d3dbd72262ff102989e">adjustForTestUnderMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac7a6aa45c36b2dbf876de7b60408a7de">isIntrinsicWithCC</a>.</p>

</div>
</div>

### CCMASK\_VCMP\_ALL {#a8820fe17e5318116093b3df3a06cfc29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_VCMP_ALL = <a href="#a14b31497ae4b898370352164acc3b5f8">CCMASK_0</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a053ae5bd3db78d3dbd72262ff102989e">adjustForTestUnderMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a873e94810e7f562792b29f5bda7557df">adjustICmp128</a>.</p>

</div>
</div>

### CCMASK\_VCMP\_MIXED {#a7fec827d2e63a7b71dc25b2aa402223c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_VCMP_MIXED = <a href="#a3e4f7a3f70ff22719bebc0dedfa6f5d4">CCMASK_1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### CCMASK\_VCMP\_NONE {#a8bf367a88651521ca2060ab85d3adc22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::CCMASK_VCMP_NONE = <a href="#abfe77bb849cf01dbc4b6fc10e091395e">CCMASK_3</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### ELFArgFPRs {#a1740d369e735cb5533fc7ab47c1b61a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg llvm::SystemZ::ELFArgFPRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  SystemZ::F0D, SystemZ::F2D, SystemZ::F4D, SystemZ::F6D
}
</div>
</dd>
</dl>

<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-h">SystemZCallingConv.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-cpp">SystemZCallingConv.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>.</p>

</div>
</div>

### ELFArgGPRs {#ab58bf05e46b0dbaad61b7a7e66a73758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg llvm::SystemZ::ELFArgGPRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  SystemZ::R2D, SystemZ::R3D, SystemZ::R4D, SystemZ::R5D, SystemZ::R6D
}
</div>
</dd>
</dl>

<p>Declaration at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-h">SystemZCallingConv.h</a>, definition at line 13 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-cpp">SystemZCallingConv.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a4554341b316dd0b06a915ec883f4f74a">llvm::SystemZELFFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3624679803f9a11d8362aca440f744a6">llvm::CC_SystemZ_I128Indirect</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9eb6f3247260b906218068229b8d5b67">llvm::SystemZELFFrameLowering::determineCalleeSaves</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### ELFNumArgFPRs {#af6601b43292876e92cb9891a8f0f97f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::ELFNumArgFPRs = 4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-h">SystemZCallingConv.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>.</p>

</div>
</div>

### ELFNumArgGPRs {#adbb3aafa6e9294472bd94ff65ccfa355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::ELFNumArgGPRs = 5</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-h">SystemZCallingConv.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a4554341b316dd0b06a915ec883f4f74a">llvm::SystemZELFFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9eb6f3247260b906218068229b8d5b67">llvm::SystemZELFFrameLowering::determineCalleeSaves</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### IPM\_CC {#a739201f9c14177326c5b3dd889dc51a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::IPM_CC = 28</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzselectiondaginfo-cpp/#ab7e94059fa0b2ff2d378604a55e4f893">addIPMSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a62454aa5151d369549b3c0414bdf5646">combineCCMask</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afbb3d2344086d40fa845201e37538d85">llvm::SystemZInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a34ac8cc885ac11a3c2e4a3773a37c09c">getCCResult</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a28e0a0edbf89edb6e77b86a94974848d">getIPMConversion</a>.</p>

</div>
</div>

### MCFixupKindInfos {#ae012bef1e76a0eada343c213f7794dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCFixupKindInfo llvm::SystemZ::MCFixupKindInfos[SystemZ::NumTargetFixupKinds]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {"FK_390_PC12DBL", 4, 12, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">MCFixupKindInfo::FKF_IsPCRel</a>},
    {"FK_390_PC16DBL", 0, 16, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">MCFixupKindInfo::FKF_IsPCRel</a>},
    {"FK_390_PC24DBL", 0, 24, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">MCFixupKindInfo::FKF_IsPCRel</a>},
    {"FK_390_PC32DBL", 0, 32, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">MCFixupKindInfo::FKF_IsPCRel</a>},
    {"FK_390_TLS_CALL", 0, 0, 0},
    {"FK_390_S8Imm", 0, 8, 0},
    {"FK_390_S16Imm", 0, 16, 0},
    {"FK_390_S20Imm", 4, 20, 0},
    {"FK_390_S32Imm", 0, 32, 0},
    {"FK_390_U1Imm", 0, 1, 0},
    {"FK_390_U2Imm", 0, 2, 0},
    {"FK_390_U3Imm", 0, 3, 0},
    {"FK_390_U4Imm", 0, 4, 0},
    {"FK_390_U8Imm", 0, 8, 0},
    {"FK_390_U12Imm", 4, 12, 0},
    {"FK_390_U16Imm", 0, 16, 0},
    {"FK_390_U32Imm", 0, 32, 0},
    {"FK_390_U48Imm", 0, 48, 0},
}
</div>
</dd>
</dl>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcfixups-h">SystemZMCFixups.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/systemzmcasmbackend/#a80b61bcacc2111cec923eb2b879db606">anonymous{SystemZMCAsmBackend.cpp}::SystemZMCAsmBackend::getFixupKindInfo</a> and <a href="/web-llvm/docs/api/classes/anonymous-systemzmccodeemitter-cpp-/systemzmccodeemitter/#a52a49374d3b99fe9ff49126a83e41af5">anonymous{SystemZMCCodeEmitter.cpp}::SystemZMCCodeEmitter::getImmOpValue</a>.</p>

</div>
</div>

### PFD\_READ {#a3e142d77640c7a070a63fd1bb039c9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::PFD_READ = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### PFD\_WRITE {#a47b28944cf9ea0544e947a78b17a97d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::PFD_WRITE = 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_ALL {#a4cbdca40acdaa745873e4ba59d77425c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_ALL = <a href="#ae47feb84c571a5baf3d91b062bf3d1f3">TDCMASK_PLUS</a> | <a href="#a2da0df1f710c171c3fb943d4cfab0ab3">TDCMASK_MINUS</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_INFINITY\_MINUS {#a833c07068bfc5e817fa44b7a21d263ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_INFINITY_MINUS = 0x010</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_INFINITY\_PLUS {#a65213203a61a63b48c9c8f7b3df4e4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_INFINITY_PLUS = 0x020</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_MINUS {#a2da0df1f710c171c3fb943d4cfab0ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_MINUS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= <a href="#a10ec9588d0d0b4a551951b4149f4c85c">TDCMASK_NEGATIVE</a> |
                                         <a href="#ad1c071354267a0dd9edc213f8075003f">TDCMASK_ZERO_MINUS</a> |
                                         <a href="#a4acbd58350f3a992b4c4db44f3b7402f">TDCMASK_QNAN_MINUS</a> |
                                         <a href="#aff3c901268624324036a2fc2d044b6d6">TDCMASK_SNAN_MINUS</a>
</div>
</dd>
</dl>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_NAN {#aa43b1c8cf2b8e3c65492d4e21831331b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_NAN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= <a href="#ad119089dab3a062202613393618950c6">TDCMASK_QNAN_PLUS</a> |
                                         <a href="#a4acbd58350f3a992b4c4db44f3b7402f">TDCMASK_QNAN_MINUS</a> |
                                         <a href="#ab66361196c50a1272a4f43f67724e47d">TDCMASK_SNAN_PLUS</a> |
                                         <a href="#aff3c901268624324036a2fc2d044b6d6">TDCMASK_SNAN_MINUS</a>
</div>
</dd>
</dl>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_NEGATIVE {#a10ec9588d0d0b4a551951b4149f4c85c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_NEGATIVE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= <a href="#a2411f0aafb9c6976e0576f4436028b11">TDCMASK_NORMAL_MINUS</a> |
                                         <a href="#a3ace169b9f73f479ff985e6bb66fdf9a">TDCMASK_SUBNORMAL_MINUS</a> |
                                         <a href="#a833c07068bfc5e817fa44b7a21d263ad">TDCMASK_INFINITY_MINUS</a>
</div>
</dd>
</dl>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_NORMAL\_MINUS {#a2411f0aafb9c6976e0576f4436028b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_NORMAL_MINUS = 0x100</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_NORMAL\_PLUS {#a479ce3d3ec70c69c25bc29f6c6c4779a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_NORMAL_PLUS = 0x200</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_PLUS {#ae47feb84c571a5baf3d91b062bf3d1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_PLUS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= <a href="#a829200dd89fca8386542598e4c93568a">TDCMASK_POSITIVE</a> |
                                         <a href="#acbbdfbfe148fc33cb4e346afe41bc227">TDCMASK_ZERO_PLUS</a> |
                                         <a href="#ad119089dab3a062202613393618950c6">TDCMASK_QNAN_PLUS</a> |
                                         <a href="#ab66361196c50a1272a4f43f67724e47d">TDCMASK_SNAN_PLUS</a>
</div>
</dd>
</dl>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_POSITIVE {#a829200dd89fca8386542598e4c93568a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_POSITIVE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= <a href="#a479ce3d3ec70c69c25bc29f6c6c4779a">TDCMASK_NORMAL_PLUS</a> |
                                         <a href="#a5c0630cb0205321fdab03973e313a7e5">TDCMASK_SUBNORMAL_PLUS</a> |
                                         <a href="#a65213203a61a63b48c9c8f7b3df4e4bf">TDCMASK_INFINITY_PLUS</a>
</div>
</dd>
</dl>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_QNAN\_MINUS {#a4acbd58350f3a992b4c4db44f3b7402f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_QNAN_MINUS = 0x004</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_QNAN\_PLUS {#ad119089dab3a062202613393618950c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_QNAN_PLUS = 0x008</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_SNAN\_MINUS {#aff3c901268624324036a2fc2d044b6d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_SNAN_MINUS = 0x001</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_SNAN\_PLUS {#ab66361196c50a1272a4f43f67724e47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_SNAN_PLUS = 0x002</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_SUBNORMAL\_MINUS {#a3ace169b9f73f479ff985e6bb66fdf9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_SUBNORMAL_MINUS = 0x040</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_SUBNORMAL\_PLUS {#a5c0630cb0205321fdab03973e313a7e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_SUBNORMAL_PLUS = 0x080</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_ZERO {#a3dc9e33baff99f198d767db21741dd89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_ZERO = <a href="#acbbdfbfe148fc33cb4e346afe41bc227">TDCMASK_ZERO_PLUS</a> | <a href="#ad1c071354267a0dd9edc213f8075003f">TDCMASK_ZERO_MINUS</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_ZERO\_MINUS {#ad1c071354267a0dd9edc213f8075003f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_ZERO_MINUS = 0x400</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### TDCMASK\_ZERO\_PLUS {#acbbdfbfe148fc33cb4e346afe41bc227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::TDCMASK_ZERO_PLUS = 0x800</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>

</div>
</div>

### VectorBits {#a5e2f6288a79b32c4bc9f22fe3f3222b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::VectorBits = 128</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#acbad6d70dd3351b812d5b74353574207">llvm::SystemZTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#adc334ed6d48bd887ada88cfdc2190ae5">getFastReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#acafd771f9c54c189a2cdec8c6fda24d2">llvm::SystemZTTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemzisellowering-cpp-/generalshuffle/#a7e4169d05285368e8908c5f7bc86c87b">anonymous{SystemZISelLowering.cpp}::GeneralShuffle::insertUnpackIfPrepared</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#ad6ba63ef6a9e69ae5ae03797b21964fd">llvm::SystemZVectorConstantInfo::isVectorConstantLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a20633bb313b81aa7bccb990719706d82">llvm::SystemZTTIImpl::shouldExpandReduction</a> and <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#a7da80f756644226c925de9aa4bf77d94">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a>.</p>

</div>
</div>

### VectorBytes {#a8100b30b39f455a1b99d9d421a5b8f3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::VectorBytes = <a href="#a5e2f6288a79b32c4bc9f22fe3f3222b2">VectorBits</a> / 8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-systemzisellowering-cpp-/generalshuffle/#aae881b014fee000d713159f7464f860e">anonymous{SystemZISelLowering.cpp}::GeneralShuffle::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3f608529746b57d9dfbb1a3f5fa3dd6c">getGeneralPermuteNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemzisellowering-cpp-/generalshuffle/#ab94f3858d30f3e1f5259e94182ed196d">anonymous{SystemZISelLowering.cpp}::GeneralShuffle::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a2f58e015c7d03ed60ac5170bcf8aced9">getPermuteNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a2b6d81ca6f536418386601acda3e1ad5">isShlDoublePermute</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#ad6ba63ef6a9e69ae5ae03797b21964fd">llvm::SystemZVectorConstantInfo::isVectorConstantLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad7c9b7d5d48d1e1960fd813e6820ab9c">matchDoublePermute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a57d318b65d3aefdda0babe2508402d55">matchPermute</a> and <a href="/web-llvm/docs/api/structs/anonymous-systemzisellowering-cpp-/generalshuffle/#a00bde9b9e580aea387c2e0456964dbbf">anonymous{SystemZISelLowering.cpp}::GeneralShuffle::tryPrepareForUnpack</a>.</p>

</div>
</div>

### XPLINK64ArgFPRs {#a07c0cc6320c12921a5214379d390875d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg llvm::SystemZ::XPLINK64ArgFPRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    SystemZ::F0D, SystemZ::F2D, SystemZ::F4D, SystemZ::F6D
}
</div>
</dd>
</dl>

<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-h">SystemZCallingConv.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-cpp">SystemZCallingConv.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd16252e979949f539c50a1d3b80bb76">llvm::CC_XPLINK64_Shadow_Reg</a>.</p>

</div>
</div>

### XPLINK64ArgGPRs {#af7c04579e3a921c01f95cb27f2ab243e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg llvm::SystemZ::XPLINK64ArgGPRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    SystemZ::R1D, SystemZ::R2D, SystemZ::R3D
}
</div>
</dd>
</dl>

<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-h">SystemZCallingConv.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-cpp">SystemZCallingConv.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3624679803f9a11d8362aca440f744a6">llvm::CC_SystemZ_I128Indirect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd16252e979949f539c50a1d3b80bb76">llvm::CC_XPLINK64_Shadow_Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a58cebd1e96489b04d18f2a7c39c250f8">llvm::SystemZXPLINKFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### XPLINK64NumArgFPRs {#a674b14434074a552490c065536d67242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::XPLINK64NumArgFPRs = 4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-h">SystemZCallingConv.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd16252e979949f539c50a1d3b80bb76">llvm::CC_XPLINK64_Shadow_Reg</a>.</p>

</div>
</div>

### XPLINK64NumArgGPRs {#a880191f32861e3017b27d79724a2f270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SystemZ::XPLINK64NumArgGPRs = 3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-h">SystemZCallingConv.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a58cebd1e96489b04d18f2a7c39c250f8">llvm::SystemZXPLINKFrameLowering::emitPrologue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcfixups-h">SystemZMCFixups.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemz-h">SystemZ.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-cpp">SystemZCallingConv.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzcallingconv-h">SystemZCallingConv.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp">SystemZInstrInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-h">SystemZInstrInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-h">SystemZRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
