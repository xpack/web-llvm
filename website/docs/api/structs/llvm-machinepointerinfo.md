---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machinepointerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MachinePointerInfo` Struct Reference

<p>This class contains a discriminated union of information about pointers in memory operands, relating them back to LLVM IR or to virtual locations (such as frame indices) that are exposed during codegen. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MachinePointerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a> (const Value *v, int64_t offset=0, uint8_t ID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263049021e376918c67633a70417163c">MachinePointerInfo</a> (const PseudoSourceValue *v, int64_t offset=0, uint8_t ID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9c8da99e854c59b91a4c6237f6b85b">MachinePointerInfo</a> (unsigned AddressSpace=0, int64_t offset=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62afda4d0b9ae1a4d9f0bd4e4824e652">MachinePointerInfo</a> (PointerUnion&lt; const Value *, const PseudoSourceValue * &gt; v, int64_t offset=0, uint8_t ID=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9459055a98e20980521289e8d20fcc7e">getWithOffset</a> (int64_t O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2081649e4ddbd0af720509a9ddf47b74">isDereferenceable</a> (unsigned Size, LLVMContext &amp;C, const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if memory region [V, V+Offset+Size) is known to be dereferenceable. <a href="#a2081649e4ddbd0af720509a9ddf47b74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2788ec4ff3130471e24ab77dc08f7c50">getAddrSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the LLVM IR address space number that this pointer points into. <a href="#a2788ec4ff3130471e24ab77dc08f7c50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f65d6bf5e507ea21658108377b48e0">V</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the IR pointer value for the access, or it is null if unknown. <a href="#a80f65d6bf5e507ea21658108377b48e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">Offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset - This is an offset from the base Value*. <a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f25dc7e503484ef92edf4406724e3ce">AddrSpace</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd6ffebfe96c8efceb9e7997c1d7951">StackID</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b1a64bd0c1be7a99998055c78d1312b">getConstantPool</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to the constant pool. <a href="#a8b1a64bd0c1be7a99998055c78d1312b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ce1aee13dbdcc05d20284a30e83170">getFixedStack</a> (MachineFunction &amp;MF, int FI, int64_t Offset=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to the specified FrameIndex. <a href="#ad8ce1aee13dbdcc05d20284a30e83170">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15667eb123c1638704fe9cb7b2ac208b">getJumpTable</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to a jump table entry. <a href="#a15667eb123c1638704fe9cb7b2ac208b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70144cee705b3f0db7f53ff3bf004e9">getGOT</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to a GOT entry. <a href="#aa70144cee705b3f0db7f53ff3bf004e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f877286c09d06ac6b9c5534736433d9">getStack</a> (MachineFunction &amp;MF, int64_t Offset, uint8_t ID=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stack pointer relative access. <a href="#a2f877286c09d06ac6b9c5534736433d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f0f4a7de5def1c9d9f6a750a9b1aa1">getUnknownStack</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stack memory without other information. <a href="#aa5f0f4a7de5def1c9d9f6a750a9b1aa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class contains a discriminated union of information about pointers in memory operands, relating them back to LLVM IR or to virtual locations (such as frame indices) that are exposed during codegen.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachinePointerInfo() {#aca22932a7bffa6ad74c744573d38b3b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachinePointerInfo::MachinePointerInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * v, int64_t offset=0, uint8_t ID=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="#a4f25dc7e503484ef92edf4406724e3ce">AddrSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21b1f2d0effa0506f01cb146823de6a2">llvm::getPointerAddressSpace</a>, <a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">Offset</a>, <a href="#a3bd6ffebfe96c8efceb9e7997c1d7951">StackID</a> and <a href="#a80f65d6bf5e507ea21658108377b48e0">V</a>.</p>


<p>Referenced by <a href="#a8b1a64bd0c1be7a99998055c78d1312b">getConstantPool</a>, <a href="#ad8ce1aee13dbdcc05d20284a30e83170">getFixedStack</a>, <a href="#aa70144cee705b3f0db7f53ff3bf004e9">getGOT</a>, <a href="#a15667eb123c1638704fe9cb7b2ac208b">getJumpTable</a>, <a href="#a2f877286c09d06ac6b9c5534736433d9">getStack</a>, <a href="#aa5f0f4a7de5def1c9d9f6a750a9b1aa1">getUnknownStack</a> and <a href="#a9459055a98e20980521289e8d20fcc7e">getWithOffset</a>.</p>

</div>
</div>

### MachinePointerInfo() {#a263049021e376918c67633a70417163c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachinePointerInfo::MachinePointerInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> * v, int64_t offset=0, uint8_t ID=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="#a4f25dc7e503484ef92edf4406724e3ce">AddrSpace</a>, <a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">Offset</a>, <a href="#a3bd6ffebfe96c8efceb9e7997c1d7951">StackID</a> and <a href="#a80f65d6bf5e507ea21658108377b48e0">V</a>.</p>

</div>
</div>

### MachinePointerInfo() {#a3f9c8da99e854c59b91a4c6237f6b85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachinePointerInfo::MachinePointerInfo (unsigned AddressSpace=0, int64_t offset=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="#a4f25dc7e503484ef92edf4406724e3ce">AddrSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">Offset</a>, <a href="#a3bd6ffebfe96c8efceb9e7997c1d7951">StackID</a> and <a href="#a80f65d6bf5e507ea21658108377b48e0">V</a>.</p>

</div>
</div>

### MachinePointerInfo() {#a62afda4d0b9ae1a4d9f0bd4e4824e652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachinePointerInfo::MachinePointerInfo (<a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> * &gt; v, int64_t offset=0, uint8_t ID=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="#a4f25dc7e503484ef92edf4406724e3ce">AddrSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">Offset</a>, <a href="#a3bd6ffebfe96c8efceb9e7997c1d7951">StackID</a> and <a href="#a80f65d6bf5e507ea21658108377b48e0">V</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddrSpace() {#a2788ec4ff3130471e24ab77dc08f7c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachinePointerInfo::getAddrSpace ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the LLVM IR address space number that this pointer points into.</p>


<p>getAddrSpace - Return the LLVM IR address space number that this pointer points into.</p>


<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>Reference <a href="#a4f25dc7e503484ef92edf4406724e3ce">AddrSpace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/x86selectiondaginfo/#a96fa506e62ed4b22ab4e9eaac0edaf61">llvm::X86SelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86selectiondaginfo/#aa0597706526940b36ec2a6e5fb1e41d7">llvm::X86SelectionDAGInfo::EmitTargetCodeForMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a2e10f29264df67a4564d4230bf8e98c7">llvm::MemSDNode::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a1f2f01c1eb849390f448f90643c6ff">llvm::SelectionDAG::getAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5bd5e426c197fd66ec0ac6f088d51185">llvm::SelectionDAG::getGatherVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af6334751e0a4eaf2b2a253f545a861">llvm::SelectionDAG::getGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab517db4292565daf5cea12e127f9db87">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0bc0f0450beae61b3c7c3f110d3b7c5c">llvm::SelectionDAG::getMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a77eef56a45fec10f706e25be688f3beb">llvm::SelectionDAG::getMaskedHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af2a48350a921ca25a0939a82228555f4">llvm::SelectionDAG::getMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aff2202a13bbfad20f9b5156fd930cf01">llvm::SelectionDAG::getMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa83e0455dcd3f0feb08e08ebb0a18db0">llvm::SelectionDAG::getMaskedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6fc57a7458164a2086dfee32a82530db">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac3f766fb181e521628094d9a9e461606">llvm::SelectionDAG::getMemmove</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2150ad6f255dd827e24a5b76ec58d802">llvm::SelectionDAG::getMemset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8b2b591dc9b054d04368b7d069fb76c">llvm::SelectionDAG::getScatterVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa7cfce69eeecdf585f55b39efbdff6ba">llvm::SelectionDAG::getSetFPEnv</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#ab81aa7a77f61bbabb3f265712cd8ad53">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a211f6d3863ce35b5a5893032fe0449cc">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bebd21fcb08b6b7288fee3de1246c52">llvm::SelectionDAG::getStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2319cb3270540dfd23ffd53d5a9bd8aa">llvm::SelectionDAG::getStridedLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4eeee43813ecf8dee2c4ccb837ec33b5">llvm::SelectionDAG::getStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ace48e423cac6b59de28c739fbe31c34d">llvm::SelectionDAG::getTruncStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a28a0f1422b780a83a9632e5d46993dfc">llvm::CombinerHelper::matchCombineExtractedVectorLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>.</p>

</div>
</div>

### getWithOffset() {#a9459055a98e20980521289e8d20fcc7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePointerInfo llvm::MachinePointerInfo::getWithOffset (int64_t O)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="#a4f25dc7e503484ef92edf4406724e3ce">AddrSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a>, <a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">Offset</a>, <a href="#a3bd6ffebfe96c8efceb9e7997c1d7951">StackID</a> and <a href="#a80f65d6bf5e507ea21658108377b48e0">V</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa9fca969da56000134dc248f8d676e3a">combineExtractFromVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#a6d50362e845dcbafcf632cb5b98b240f">emitConstantSizeRepmov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#ac6a86b853c0a0262731e7e8b084c0980">emitConstantSizeRepstos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaf673a1e44074d7088008437112159fa">emitSplitF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a4d3a29c0e2103ce92ec80ac1f6eee78a">llvm::ARMSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzselectiondaginfo/#a13c6fa8f5d32e17789ce621593b356e0">llvm::SystemZSelectionDAGInfo::EmitTargetCodeForMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1aeb03a2dac908dce3ff3979e298fb21">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2fdcff9cc28cfffa71717b8d3c32c781">llvm::LegalizerHelper::lowerExtractInsertVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#af5649d870c8560e39b54f41b8f5997fd">LowerF128Load</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a30ec39aa33314bba87f6f8d0eded2df8">LowerF128Store</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a28a0f1422b780a83a9632e5d46993dfc">llvm::CombinerHelper::matchCombineExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a6aa2c4df9fd69696ef41afd841661bb7">llvm::RISCVDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa649493d03967e1898ad4354759d89f7">reduceMaskedStoreToScalarStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a347a0b15c11be2a5567e53730e0fb1b2">ShrinkLoadReplaceStoreWithStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6a7f067c980840336e15888700870c6a">splitStoreSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a0bd751c4c85d494e52e578b6bc10f8bc">llvm::AMDGPUTargetLowering::SplitVectorLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aad3b6954334c350e17f08d707e1f102f">llvm::AMDGPUTargetLowering::SplitVectorStore</a>.</p>

</div>
</div>

### isDereferenceable() {#a2081649e4ddbd0af720509a9ddf47b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachinePointerInfo::isDereferenceable (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if memory region [V, V+Offset+Size) is known to be dereferenceable.</p>


<p>isDereferenceable - Return true if V is always dereferenceable for Offset + Size byte.</p>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1050 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2da012cb3e5534bbee33563d309bc354">llvm::isDereferenceableAndAlignedPointer</a>, <a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a80f65d6bf5e507ea21658108377b48e0">V</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aeca06367a5dacb988586dfa1b94fa0c1">llvm::AMDGPUTargetLowering::WidenOrSplitVectorLoad</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddrSpace {#a4f25dc7e503484ef92edf4406724e3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachinePointerInfo::AddrSpace = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="#a2788ec4ff3130471e24ab77dc08f7c50">getAddrSpace</a>, <a href="#a9459055a98e20980521289e8d20fcc7e">getWithOffset</a>, <a href="#a263049021e376918c67633a70417163c">MachinePointerInfo</a>, <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a>, <a href="#a62afda4d0b9ae1a4d9f0bd4e4824e652">MachinePointerInfo</a> and <a href="#a3f9c8da99e854c59b91a4c6237f6b85b">MachinePointerInfo</a>.</p>

</div>
</div>

### Offset {#a40c024ae6ff6ee0ba90c9105c3d55ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachinePointerInfo::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset - This is an offset from the base Value*.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="#ad8ce1aee13dbdcc05d20284a30e83170">getFixedStack</a>, <a href="#a2f877286c09d06ac6b9c5534736433d9">getStack</a>, <a href="#a9459055a98e20980521289e8d20fcc7e">getWithOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff719a7221f395b1b3849c9675ca32dd">llvm::inferAlignFromPtrInfo</a>, <a href="#a2081649e4ddbd0af720509a9ddf47b74">isDereferenceable</a>, <a href="#a263049021e376918c67633a70417163c">MachinePointerInfo</a>, <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a>, <a href="#a62afda4d0b9ae1a4d9f0bd4e4824e652">MachinePointerInfo</a> and <a href="#a3f9c8da99e854c59b91a4c6237f6b85b">MachinePointerInfo</a>.</p>

</div>
</div>

### StackID {#a3bd6ffebfe96c8efceb9e7997c1d7951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MachinePointerInfo::StackID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="#a9459055a98e20980521289e8d20fcc7e">getWithOffset</a>, <a href="#a263049021e376918c67633a70417163c">MachinePointerInfo</a>, <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a>, <a href="#a62afda4d0b9ae1a4d9f0bd4e4824e652">MachinePointerInfo</a> and <a href="#a3f9c8da99e854c59b91a4c6237f6b85b">MachinePointerInfo</a>.</p>

</div>
</div>

### V {#a80f65d6bf5e507ea21658108377b48e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerUnion&lt;const Value *, const PseudoSourceValue *&gt; llvm::MachinePointerInfo::V</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the IR pointer value for the access, or it is null if unknown.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a564ffef4d327c872fe912322813e6a2f">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab847f1d70cf17cd2250d78d4bb19ec4e">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1aeb03a2dac908dce3ff3979e298fb21">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8063c77c39146c0790e66f5e0679475c">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf715e866131db937a292ab35643ca0c">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="#a9459055a98e20980521289e8d20fcc7e">getWithOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff719a7221f395b1b3849c9675ca32dd">llvm::inferAlignFromPtrInfo</a>, <a href="#a2081649e4ddbd0af720509a9ddf47b74">isDereferenceable</a>, <a href="#a263049021e376918c67633a70417163c">MachinePointerInfo</a>, <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a>, <a href="#a62afda4d0b9ae1a4d9f0bd4e4824e652">MachinePointerInfo</a> and <a href="#a3f9c8da99e854c59b91a4c6237f6b85b">MachinePointerInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getConstantPool() {#a8b1a64bd0c1be7a99998055c78d1312b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePointerInfo MachinePointerInfo::getConstantPool (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to the constant pool.</p>


<p>getConstantPool - Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to the constant pool.</p>


<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1066 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevaluemanager/#a6a4c66e2326c94e5d10c96b46a09ab63">llvm::PseudoSourceValueManager::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2c02512ed96f8cf038a8254f5956ad04">llvm::MachineFunction::getPSVManager</a> and <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9fa574f4bc0ad6d1cd8335fdf7aba857">llvm::CSKYInstrInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a93143c7c98a98f3712301e2d749e8205">getLargeExternalSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae1b012e1db529fbfbeee6e863dfef7cc">getLargeGlobalAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1d727a45696ad380a24b7fd8445182d8">LowerUINT_TO_FP_i64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adbf830c60a50ca49ef14e5cb8750244e">lowerUINT_TO_FP_vXi32</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreiseldagtodag-cpp-/xcoredagtodagisel/#a4b1c5b30230a9be2aa310c91d8dccf20">anonymous{XCoreISelDAGToDAG.cpp}::XCoreDAGToDAGISel::Select</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>.</p>

</div>
</div>

### getFixedStack() {#ad8ce1aee13dbdcc05d20284a30e83170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePointerInfo MachinePointerInfo::getFixedStack (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int FI, int64_t Offset=0)</td>
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

<p>Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to the specified FrameIndex.</p>


<p>getFixedStack - Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to the the specified FrameIndex.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevaluemanager/#a2909d8f067ac86f7e34f4318f972e447">llvm::PseudoSourceValueManager::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2c02512ed96f8cf038a8254f5956ad04">llvm::MachineFunction::getPSVManager</a>, <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a> and <a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensainstrinfo-cpp/#afb2753bad8eb2a132f72925416a0ac4c">addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24df964fef5537043b85294a38037ca1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb2d11e8b17ef23a86d57b4105fba8e1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a67931ef18efe0f1710e3f2e39ddfb8f6">llvm::M68k::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a40fe21a4879ff8f132c4fb676738c5b1">llvm::M68k::addMemOperand</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a122720c6c9f5c3fd65169c6d123d2516">buildEpilogRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a168f3532cb1605bbc91fcc079892e357">llvm::X86TargetLowering::BuildFILD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a4e6b353116922112b1b470ce15adb2fd">buildPrologSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aee68072e1038a895a2998d78395db856">llvm::SIRegisterInfo::buildVGPRSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a576b964fe2d7d8750601681e04f05a9c">llvm::LegalizerHelper::createStackTemporary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaf673a1e44074d7088008437112159fa">emitSplitF64Pseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#acca11c9d64a646da497e82dcf6e9636e">EmitTailCallStoreFPAndRetAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aa3e32d9a4b0cb160ffd67dfdf53f7fa6">EmitTailCallStoreRetAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a94b8d8925deffd735f51d36b77d3f9ca">getAddressForMemoryInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a1d4b2effd4fbebb40f0d10cb1ed6c577">getFrameIndexMMO</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#aec1de11231135901271d92c7d90dae60">getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a3f25c09896b601cbe577cc8a814ac748">llvm::MipsInstrInfo::GetMemOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a18bab7a0c4783a00f51d05cae58ee7da">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a11c07e0125e7cd5df9cd7747977f9638">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuincomingarghandler/#a84d626ad52140616b26b997d67d2c7b1">anonymous{AMDGPUCallLowering.cpp}::AMDGPUIncomingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a6901759e2aab843e39497ccb23a0c3cd">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#ab81aa7a77f61bbabb3f265712cd8ad53">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a2cc4d384d22ddae8f252b9cbb9313949">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86incomingvaluehandler/#a1ebcdacc79bcbbbb515e69090df3ea18">anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizedag-cpp/#a845c5871499188129bc91bba5e1f03bf">getStackAlignedMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aaebdecc6b4a89094d56ba277ce310749">InferPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a33a30176a7fd636333a4e618ef109f57">llvm::CallLowering::insertSRetLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ad96e959009cbe91d2814bcdfe4fcd51c">llvm::ARCInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#aa3221ba2a1b01836c1f02c48d2bd2c4e">llvm::AVRInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a2c4630e6b74de7b52933845fe4f48f01">llvm::CSKYInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad3b3220844622daec97aeb14080a66e4">llvm::HexagonInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#afa83048a6e09247f7f6310ffc0681909">llvm::LoongArchInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a3a04d16772e68de8d911d305070f0e0b">llvm::MSP430InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abe4a49e8ceb6213fe44eb0ebc9869eb1">llvm::SIInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a38be8eeeb68d45e0a914cd8f3237ce83">llvm::SparcInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a6d4af3948133ad97770947f7d1242561">llvm::VEInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a541a292af69ae4be75a66b7994e89abb">llvm::XCoreInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a4f5aa6feffe52b80166f0d252cf354cb">llvm::PPCInstrInfo::loadRegFromStackSlotNoUpd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a62712c499928ed783ba6329269bbc8f9">LowerATOMIC_STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4e7be374a3346400a32967d91108c3e">llvm::LoongArchTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#abd42e7de94d28ca6667b61e1bcba6dce">llvm::VETargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ae87be78c50d3026c58e203aa8f0b9164">llvm::SparcTargetLowering::LowerFormalArguments_64</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a589928ae94c1e14b50e374c6a1146c60">llvm::ARMTargetLowering::PerformMVEExtCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a35a55a457bfc044d33bdeb4811532531">llvm::ARMTargetLowering::PerformMVETruncCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a621eb8645a9f80882b80ac3c6d4e0091">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a6aa2c4df9fd69696ef41afd841661bb7">llvm::RISCVDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aeba4e73d60d1b4cedc120d06114c0620">llvm::AArch64InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a687fecaf502080080ba5069e6b211a65">llvm::ARCInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8a7868df2562a3b48d08d24c9db87b98">llvm::ARMBaseInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a90829bf41a9e8e4c4e4ad59eab490719">llvm::AVRInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a647cde93263cdcab73a72f5e459041c6">llvm::CSKYInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a9644f3506784b55b500d2f73f94d79e0">llvm::HexagonInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aed611129b85082f7e6459907b50a8cd5">llvm::LoongArchInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#ae215353a37be6d2f533a4858bd96be74">llvm::MSP430InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ec207a1c12adfc61c6566436e5a2cd7">llvm::SIInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#abc124725b4afa4a9d9449c6e2cfb3d73">llvm::SparcInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a2132749e515b00c60255bdb4acfba223">llvm::VEInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a915259afe54d2619524ed03c9c273c57">llvm::XCoreInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a97de15cd29255b90b2ce510e967340bf">llvm::PPCInstrInfo::storeRegToStackSlotNoUpd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a7fcdf2ea020f761f9857bebbc35a2ca3">StoreTailCallArgumentsToStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a4fe763745add3c357f272b8f41264d6a">unpack64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae3c73a05257120f8a564e40826d20ace">unpackF64OnRV32DSoftABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### getGOT() {#aa70144cee705b3f0db7f53ff3bf004e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePointerInfo MachinePointerInfo::getGOT (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to a GOT entry.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevaluemanager/#a364a4f44b8f382dad30d424633b973f3">llvm::PseudoSourceValueManager::getGOT</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2c02512ed96f8cf038a8254f5956ad04">llvm::MachineFunction::getPSVManager</a> and <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a83de3f9ab24662688a50952de742a4dd">llvm::ARMBaseInstrInfo::expandLoadStackGuardBase</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#aa5e1d1788ef2fee23b0f9542eda5c1b6">llvm::MipsTargetLowering::getAddrLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a62884fc221d7c7a50e498b054c1542ca">getzOSCalleeAndADA</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7092b8371f80f3acf826e7bfc1e00d92">LowerToTLSExecModel</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a8c1423d81607a5548a57bf11a3ab447c">llvm::SparcTargetLowering::makeAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa7a460999303677345922560c5db47e">llvm::VETargetLowering::makeAddress</a>.</p>

</div>
</div>

### getJumpTable() {#a15667eb123c1638704fe9cb7b2ac208b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePointerInfo MachinePointerInfo::getJumpTable (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Return a <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> record that refers to a jump table entry.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1077 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevaluemanager/#a0eb9e9d314956cdcfb85f33c863fbe92">llvm::PseudoSourceValueManager::getJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2c02512ed96f8cf038a8254f5956ad04">llvm::MachineFunction::getPSVManager</a> and <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a>.</p>

</div>
</div>

### getStack() {#a2f877286c09d06ac6b9c5534736433d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePointerInfo MachinePointerInfo::getStack (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int64_t Offset, uint8_t ID=0)</td>
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

<p>Stack pointer relative access.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2c02512ed96f8cf038a8254f5956ad04">llvm::MachineFunction::getPSVManager</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevaluemanager/#a50b8d7cb4795dfcfae3cbaca1968e66e">llvm::PseudoSourceValueManager::getStack</a>, <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a> and <a href="#a40c024ae6ff6ee0ba90c9105c3d55ca3">Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a11c07e0125e7cd5df9cd7747977f9638">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a6901759e2aab843e39497ccb23a0c3cd">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a1de30cc152058819888b9d02619f16ac">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a0256194175f52db6cc06eb379bd412dc">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#a059b61bb0bab07b3cf7da0e06f5893dd">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#a202a7e2a16e7921c97c6767cb68bdae9">M68kOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a9c10e3651139ad6ec8af95a7b7fb152d">llvm::AMDGPUTargetLowering::loadStackInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a1c9659f794755f065314788b9546ea82">llvm::AMDGPUTargetLowering::storeStackInputValue</a>.</p>

</div>
</div>

### getUnknownStack() {#aa5f0f4a7de5def1c9d9f6a750a9b1aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePointerInfo MachinePointerInfo::getUnknownStack (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Stack memory without other information.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1090 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a9748c769cedc926c41cd95183fd7abd4">llvm::DataLayout::getAllocaAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a> and <a href="#aca22932a7bffa6ad74c744573d38b3b5">MachinePointerInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac29774c06843a7c183ae3fd328d43bc8">llvm::LegalizerHelper::lowerVECTOR_COMPRESS</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
