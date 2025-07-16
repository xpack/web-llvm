---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dstop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DstOp` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DstOp { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DstType { <a href="#a732f86a0e23a9a893ca2a2494a10756f">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1807fa09121892969d9a8987c0c0e573">DstOp</a> (unsigned R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26db21697dfb802939d62f71f4557d12">DstOp</a> (Register R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776a0f41b47f95d2aaebca0f3fe98689">DstOp</a> (const MachineOperand &amp;Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb4469f3052130d6a225326c9640608">DstOp</a> (const LLT T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8bb316ab259008b80eb865ab1526f01">DstOp</a> (const TargetRegisterClass *TRC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f57939ff908fc07a32f922177ff7720">DstOp</a> (MachineRegisterInfo::VRegAttrs Attrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e091fa8a92a54cb7441c89aac8bc37">DstOp</a> (RegClassOrRegBank RCOrRB, LLT Ty)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45141d649d02a2ed17b51b5419ee884d">addDefToMIB</a> (MachineRegisterInfo &amp;MRI, MachineInstrBuilder &amp;MIB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a5649c0de9dee3dacbab3019872923">getLLTTy</a> (const MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f891a5d9822c7aab1b8bb0190a522f">getReg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae9af24b12caa2fa81fd3e50626a82a2">getRegClass</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs">MachineRegisterInfo::VRegAttrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ec849d557c081023ecf482ab4ffda5">getVRegAttrs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a732f86a0e23a9a893ca2a2494a10756f">DstType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78f3ae890acfa055caae87c80d47a47">getDstOpKind</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a4084bcc4ac919ff716ea93e0fa9c8">LLTTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd879b719451232adfe0aa88f8a5d98">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8815e7112c1f6b325544e9da658c338">RC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs">MachineRegisterInfo::VRegAttrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682db75f94cdd9e8560ea736b239a537">Attrs</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/dstop">llvm::DstOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d0dae0079f2c9c50afd7d2915922b69"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a732f86a0e23a9a893ca2a2494a10756f">DstType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c1d311b61b87b71f5dd670d495e2c5">Ty</a></td>
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


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### DstType {#a732f86a0e23a9a893ca2a2494a10756f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DstOp::DstType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Ty_LLT<a id="a732f86a0e23a9a893ca2a2494a10756fa4f6880b78f7d19b441ef9f249508ca0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ty_Reg<a id="a732f86a0e23a9a893ca2a2494a10756faba90cf184fd0f4eddf476f0f1a18a680"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ty_RC<a id="a732f86a0e23a9a893ca2a2494a10756face1e43edc23a56a394a29f3aa6cc781d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ty_VRegAttrs<a id="a732f86a0e23a9a893ca2a2494a10756fa3fa6d03855a8dca1351a71629f5200f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DstOp() {#a1807fa09121892969d9a8987c0c0e573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DstOp::DstOp (unsigned R)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#aedd879b719451232adfe0aa88f8a5d98">Reg</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756faba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a>.</p>

</div>
</div>

### DstOp() {#a26db21697dfb802939d62f71f4557d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DstOp::DstOp (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#aedd879b719451232adfe0aa88f8a5d98">Reg</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756faba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a>.</p>

</div>
</div>

### DstOp() {#a776a0f41b47f95d2aaebca0f3fe98689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DstOp::DstOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#ad5f891a5d9822c7aab1b8bb0190a522f">getReg</a>, <a href="#aedd879b719451232adfe0aa88f8a5d98">Reg</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756faba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a>.</p>

</div>
</div>

### DstOp() {#a0bb4469f3052130d6a225326c9640608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DstOp::DstOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> T)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#a69a4084bcc4ac919ff716ea93e0fa9c8">LLTTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756fa4f6880b78f7d19b441ef9f249508ca0f">Ty_LLT</a>.</p>

</div>
</div>

### DstOp() {#ab8bb316ab259008b80eb865ab1526f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DstOp::DstOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * TRC)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#aa8815e7112c1f6b325544e9da658c338">RC</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756face1e43edc23a56a394a29f3aa6cc781d">Ty_RC</a>.</p>

</div>
</div>

### DstOp() {#a6f57939ff908fc07a32f922177ff7720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DstOp::DstOp (<a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs">MachineRegisterInfo::VRegAttrs</a> Attrs)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#a682db75f94cdd9e8560ea736b239a537">Attrs</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756fa3fa6d03855a8dca1351a71629f5200f0">Ty_VRegAttrs</a>.</p>

</div>
</div>

### DstOp() {#ac2e091fa8a92a54cb7441c89aac8bc37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DstOp::DstOp (<a href="/web-llvm/docs/api/namespaces/llvm/#a0f1def99add5e4273e839bf70f3e79ed">RegClassOrRegBank</a> RCOrRB, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Reference <a href="#a682db75f94cdd9e8560ea736b239a537">Attrs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDefToMIB() {#a45141d649d02a2ed17b51b5419ee884d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DstOp::addDefToMIB (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="#a682db75f94cdd9e8560ea736b239a537">Attrs</a>, <a href="#a69a4084bcc4ac919ff716ea93e0fa9c8">LLTTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#aa8815e7112c1f6b325544e9da658c338">RC</a>, <a href="#aedd879b719451232adfe0aa88f8a5d98">Reg</a>, <a href="#a732f86a0e23a9a893ca2a2494a10756fa4f6880b78f7d19b441ef9f249508ca0f">Ty_LLT</a>, <a href="#a732f86a0e23a9a893ca2a2494a10756face1e43edc23a56a394a29f3aa6cc781d">Ty_RC</a>, <a href="#a732f86a0e23a9a893ca2a2494a10756faba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756fa3fa6d03855a8dca1351a71629f5200f0">Ty_VRegAttrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adbf5d6125fa84e067907320d93e9fab5">llvm::MachineIRBuilder::buildAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acc22ffc46525708d66c036f878572523">llvm::MachineIRBuilder::buildAtomicCmpXchgWithSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a497e8884b8ae421c7dadff0f0eea5e3e">llvm::MachineIRBuilder::buildAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a1da8389b4eb951b11309c28ad492e8d4">llvm::MachineIRBuilder::buildConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aff3c145b6d12a00e7432953b1c454ebc">llvm::MachineIRBuilder::buildConstantPtrAuth</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ab00eba007903e9b4a69440782cd7c9c9">llvm::MachineIRBuilder::buildDynStackAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a81a7959d3e7f624343ecdf6905e251dd">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a92664cdbeb0b24030809439993ac271d">llvm::MachineIRBuilder::buildFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0ac2ceaa32ba0511bb9e14e6edfbc329">llvm::MachineIRBuilder::buildGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeede510b1aaac978daaba60dcc2817de">llvm::MachineIRBuilder::buildLoadInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af1b182c58ed8ff82a5958635de5ccb15">llvm::MachineIRBuilder::buildStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ab3480c1f40e51b1673754af7384a5078">llvm::MachineIRBuilder::buildVScale</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>.</p>

</div>
</div>

### getDstOpKind() {#aa78f3ae890acfa055caae87c80d47a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DstType llvm::DstOp::getDstOpKind ()</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### getLLTTy() {#a49a5649c0de9dee3dacbab3019872923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::DstOp::getLLTTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="#a682db75f94cdd9e8560ea736b239a537">Attrs</a>, <a href="#a69a4084bcc4ac919ff716ea93e0fa9c8">LLTTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#aedd879b719451232adfe0aa88f8a5d98">Reg</a>, <a href="#a732f86a0e23a9a893ca2a2494a10756fa4f6880b78f7d19b441ef9f249508ca0f">Ty_LLT</a>, <a href="#a732f86a0e23a9a893ca2a2494a10756face1e43edc23a56a394a29f3aa6cc781d">Ty_RC</a>, <a href="#a732f86a0e23a9a893ca2a2494a10756faba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756fa3fa6d03855a8dca1351a71629f5200f0">Ty_VRegAttrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adbf5d6125fa84e067907320d93e9fab5">llvm::MachineIRBuilder::buildAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acc22ffc46525708d66c036f878572523">llvm::MachineIRBuilder::buildAtomicCmpXchgWithSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a497e8884b8ae421c7dadff0f0eea5e3e">llvm::MachineIRBuilder::buildAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a96b7ed72c9782cd69b2b9b341cf73112">llvm::MachineIRBuilder::buildBuildVectorConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7acf8a5ebb4b351a451a2d63faf13294">llvm::MachineIRBuilder::buildBuildVectorTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#af20c06f6ef57cddf624f531efbaf69e7">llvm::CSEMIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#afdce4b9880a0aed02fe487da6a613cbd">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a1da8389b4eb951b11309c28ad492e8d4">llvm::MachineIRBuilder::buildConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">llvm::MachineIRBuilder::buildDeleteTrailingVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ab00eba007903e9b4a69440782cd7c9c9">llvm::MachineIRBuilder::buildDynStackAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ab8da4d08f2c0875e9623bb712aa64303">llvm::MachineIRBuilder::buildExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#ae1fe7f5085d203a5984b2450f907b239">llvm::CSEMIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a81a7959d3e7f624343ecdf6905e251dd">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a4265ff404073d12b765bc9fee4e7f186">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a92664cdbeb0b24030809439993ac271d">llvm::MachineIRBuilder::buildFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0ac2ceaa32ba0511bb9e14e6edfbc329">llvm::MachineIRBuilder::buildGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aaf34795e0fa82f3edac1a235f50da4c1">llvm::MachineIRBuilder::buildInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeede510b1aaac978daaba60dcc2817de">llvm::MachineIRBuilder::buildLoadInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af6aed1d3b2cf7133b73cf8bfa5122186">llvm::MachineIRBuilder::buildMaskLowPtrBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7aae2634e3c0980c4f68983738b90ff7">llvm::MachineIRBuilder::buildPtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a43b43271e5bcbbc5cc620b4dfa94937a">llvm::MachineIRBuilder::buildShuffleSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aded2b440bea348970816da1ecd40f2c1">llvm::MachineIRBuilder::buildShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a55bde2ba6aacac745a29a7e50c6be007">llvm::MachineIRBuilder::buildSplatBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeea5857133a04085b450948e90fdcd1e">llvm::MachineIRBuilder::buildSplatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af1b182c58ed8ff82a5958635de5ccb15">llvm::MachineIRBuilder::buildStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a50ec87d072ddb08830486e9fb31ca6de">llvm::MachineIRBuilder::buildVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a26edc3c3cae5a3f4d6ddd7f628b98c45">llvm::MachineIRBuilder::buildZExtInReg</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a92bad93a924413adf3652db02e467a21">llvm::LegalizerHelper::createStackStoreLoad</a>.</p>

</div>
</div>

### getReg() {#ad5f891a5d9822c7aab1b8bb0190a522f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::DstOp::getReg ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aedd879b719451232adfe0aa88f8a5d98">Reg</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756faba90cf184fd0f4eddf476f0f1a18a680">Ty_Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">llvm::MachineIRBuilder::buildDeleteTrailingVectorElements</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo/#a5132c278b17bb5c9fdf3f3af76250b2a">llvm::SPIRVInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ad3bff1e1b8f6b45aeb994f8ba063dd4e">cvtVOP3DstOpSelOnly</a>, <a href="#a776a0f41b47f95d2aaebca0f3fe98689">DstOp</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagoncp/#afbd23f1436bf2680a83324a63b37dbe4">anonymous{HexagonRDFOpt.cpp}::HexagonCP::interpretAsCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#aaa2bd04c34b59b5b2a2c0189c58bc55b">isCopyOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a55d78ed0d26d6a1cde6e30c6f43a5452">isCopyOfBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600expandspecialinstrs-cpp-/r600expandspecialinstrspass/#a38dc359e925f1a8fd75ba272f45b4736">anonymous{R600ExpandSpecialInstrs.cpp}::R600ExpandSpecialInstrsPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getRegClass() {#aae9af24b12caa2fa81fd3e50626a82a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * llvm::DstOp::getRegClass ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa8815e7112c1f6b325544e9da658c338">RC</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756face1e43edc23a56a394a29f3aa6cc781d">Ty_RC</a>.</p>

</div>
</div>

### getVRegAttrs() {#a96ec849d557c081023ecf482ab4ffda5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo::VRegAttrs llvm::DstOp::getVRegAttrs ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a682db75f94cdd9e8560ea736b239a537">Attrs</a> and <a href="#a732f86a0e23a9a893ca2a2494a10756fa3fa6d03855a8dca1351a71629f5200f0">Ty_VRegAttrs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Attrs {#a682db75f94cdd9e8560ea736b239a537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo::VRegAttrs llvm::DstOp::Attrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a45141d649d02a2ed17b51b5419ee884d">addDefToMIB</a>, <a href="#a6f57939ff908fc07a32f922177ff7720">DstOp</a>, <a href="#ac2e091fa8a92a54cb7441c89aac8bc37">DstOp</a>, <a href="#a49a5649c0de9dee3dacbab3019872923">getLLTTy</a> and <a href="#a96ec849d557c081023ecf482ab4ffda5">getVRegAttrs</a>.</p>

</div>
</div>

### LLTTy {#a69a4084bcc4ac919ff716ea93e0fa9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::DstOp::LLTTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a45141d649d02a2ed17b51b5419ee884d">addDefToMIB</a>, <a href="#a0bb4469f3052130d6a225326c9640608">DstOp</a> and <a href="#a49a5649c0de9dee3dacbab3019872923">getLLTTy</a>.</p>

</div>
</div>

### RC {#aa8815e7112c1f6b325544e9da658c338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass* llvm::DstOp::RC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a45141d649d02a2ed17b51b5419ee884d">addDefToMIB</a>, <a href="#ab8bb316ab259008b80eb865ab1526f01">DstOp</a> and <a href="#aae9af24b12caa2fa81fd3e50626a82a2">getRegClass</a>.</p>

</div>
</div>

### Reg {#aedd879b719451232adfe0aa88f8a5d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::DstOp::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a45141d649d02a2ed17b51b5419ee884d">addDefToMIB</a>, <a href="#a776a0f41b47f95d2aaebca0f3fe98689">DstOp</a>, <a href="#a26db21697dfb802939d62f71f4557d12">DstOp</a>, <a href="#a1807fa09121892969d9a8987c0c0e573">DstOp</a>, <a href="#a49a5649c0de9dee3dacbab3019872923">getLLTTy</a> and <a href="#ad5f891a5d9822c7aab1b8bb0190a522f">getReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a1d0dae0079f2c9c50afd7d2915922b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::DstOp llvm::DstOp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### Ty {#af8c1d311b61b87b71f5dd670d495e2c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DstType llvm::DstOp::Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
