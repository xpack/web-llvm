---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineconstantpoolentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineConstantPoolEntry` Class Reference

<p>This class is a data container for one entry in a <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineConstantPoolEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">llvm/CodeGen/MachineConstantPool.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a564e20362b45faa1cbb379ee0acfaf56">MachineConstantPoolEntry</a> (const Constant *V, Align A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad055d6c5c902869c04a999ccd3ed794f">MachineConstantPoolEntry</a> (MachineConstantPoolValue *V, Align A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9559c3abf75a6df6bd2abe7131f277">isMachineConstantPoolEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMachineConstantPoolEntry - Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry">MachineConstantPoolEntry</a> is indeed a target specific constantpool entry, not a wrapper over a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>. <a href="#a1c9559c3abf75a6df6bd2abe7131f277">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ad64ee7ca85832ea6a15eb96a993c1">getAlign</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ee6354426969c03c400e0458e8038b">getSizeInBytes</a> (const DataLayout &amp;DL) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022fed9cbfe76fd6c3b2a2358f8de17c">needsRelocation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method classifies the entry according to whether or not it may generate a relocation entry. <a href="#a022fed9cbfe76fd6c3b2a2358f8de17c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa50c9fb6d457212d9ab13ca370d0f24f">getSectionKind</a> (const DataLayout *DL) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa82b4be1aefa234c71323630c2e63f">ConstVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue">MachineConstantPoolValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4adcee15baa3809b6c4393307b10d7">MachineCPVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry">llvm::MachineConstantPoolEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a020d97c78e923fb96910f087012f9be5">Val</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The constant itself. <a href="#a020d97c78e923fb96910f087012f9be5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ee252b8d8e61290fcba4a7b7b46d58">Alignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The required alignment for this entry. <a href="#a74ee252b8d8e61290fcba4a7b7b46d58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad111db19720a77f310e76c0dbb7cb9b">IsMachineConstantPoolEntry</a></td>
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

<p>This class is a data container for one entry in a <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a>.</p>


<p>It contains a pointer to the value and an offset from the start of the constant pool. An entry in a <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a></p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineConstantPoolEntry() {#a564e20362b45faa1cbb379ee0acfaf56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineConstantPoolEntry::MachineConstantPoolEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * V, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> A)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a74ee252b8d8e61290fcba4a7b7b46d58">Alignment</a>, <a href="#aad111db19720a77f310e76c0dbb7cb9b">IsMachineConstantPoolEntry</a> and <a href="#a020d97c78e923fb96910f087012f9be5">Val</a>.</p>

</div>
</div>

### MachineConstantPoolEntry() {#ad055d6c5c902869c04a999ccd3ed794f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineConstantPoolEntry::MachineConstantPoolEntry (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue">MachineConstantPoolValue</a> * V, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> A)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a74ee252b8d8e61290fcba4a7b7b46d58">Alignment</a>, <a href="#aad111db19720a77f310e76c0dbb7cb9b">IsMachineConstantPoolEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> and <a href="#a020d97c78e923fb96910f087012f9be5">Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAlign() {#ad0ad64ee7ca85832ea6a15eb96a993c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineConstantPoolEntry::getAlign ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>Reference <a href="#a74ee252b8d8e61290fcba4a7b7b46d58">Alignment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a>.</p>

</div>
</div>

### getSectionKind() {#aa50c9fb6d457212d9ab13ca370d0f24f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind MachineConstantPoolEntry::getSectionKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> * DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>, definition at line 1464 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#aa7f2ce1ef7809115d038a2029fdffc2b">llvm::SectionKind::getMergeableConst16</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#afc5b59fd0fd4ca8acb949ebb61d79702">llvm::SectionKind::getMergeableConst32</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a2617c9278391cedbbf9588aa7496b6da">llvm::SectionKind::getMergeableConst4</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a696d509cf70352c7846d8e7102dd0e81">llvm::SectionKind::getMergeableConst8</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#af4b0b8bc19062c7b0195fc7239c4dbea">llvm::SectionKind::getReadOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a3d239dea51a80324a3ce44985ed41dd4">llvm::SectionKind::getReadOnlyWithRel</a>, <a href="#a83ee6354426969c03c400e0458e8038b">getSizeInBytes</a> and <a href="#a022fed9cbfe76fd6c3b2a2358f8de17c">needsRelocation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a344316dc056a6367fab14f5ce61b99f7">llvm::AsmPrinter::GetCPISymbol</a>.</p>

</div>
</div>

### getSizeInBytes() {#a83ee6354426969c03c400e0458e8038b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineConstantPoolEntry::getSizeInBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>, definition at line 1451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a1c9559c3abf75a6df6bd2abe7131f277">isMachineConstantPoolEntry</a> and <a href="#a020d97c78e923fb96910f087012f9be5">Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a> and <a href="#aa50c9fb6d457212d9ab13ca370d0f24f">getSectionKind</a>.</p>

</div>
</div>

### isMachineConstantPoolEntry() {#a1c9559c3abf75a6df6bd2abe7131f277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineConstantPoolEntry::isMachineConstantPoolEntry ()</td>
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

<p>isMachineConstantPoolEntry - Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry">MachineConstantPoolEntry</a> is indeed a target specific constantpool entry, not a wrapper over a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>Reference <a href="#aad111db19720a77f310e76c0dbb7cb9b">IsMachineConstantPoolEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ae22cc3a2a24f4a01d62f2d3806245f6a">llvm::MipsAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a2aca46ca706a8a857dc668e015740e53">llvm::XtensaAsmPrinter::emitMachineConstantPoolEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a344316dc056a6367fab14f5ce61b99f7">llvm::AsmPrinter::GetCPISymbol</a>, <a href="#a83ee6354426969c03c400e0458e8038b">getSizeInBytes</a>, <a href="#a022fed9cbfe76fd6c3b2a2358f8de17c">needsRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>.</p>

</div>
</div>

### needsRelocation() {#a022fed9cbfe76fd6c3b2a2358f8de17c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstantPoolEntry::needsRelocation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method classifies the entry according to whether or not it may generate a relocation entry.</p>


<p>This must be conservative, so if it might codegen to a relocatable entry, it should say so.</p>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>, definition at line 1457 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a>.</p>


<p>References <a href="#a1c9559c3abf75a6df6bd2abe7131f277">isMachineConstantPoolEntry</a> and <a href="#a020d97c78e923fb96910f087012f9be5">Val</a>.</p>


<p>Referenced by <a href="#aa50c9fb6d457212d9ab13ca370d0f24f">getSectionKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Alignment {#a74ee252b8d8e61290fcba4a7b7b46d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineConstantPoolEntry::Alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The required alignment for this entry.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>Referenced by <a href="#ad0ad64ee7ca85832ea6a15eb96a993c1">getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a344316dc056a6367fab14f5ce61b99f7">llvm::AsmPrinter::GetCPISymbol</a>, <a href="#a564e20362b45faa1cbb379ee0acfaf56">MachineConstantPoolEntry</a> and <a href="#ad055d6c5c902869c04a999ccd3ed794f">MachineConstantPoolEntry</a>.</p>

</div>
</div>

### ConstVal {#acaa82b4be1aefa234c71323630c2e63f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Constant* llvm::MachineConstantPoolEntry::ConstVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ae22cc3a2a24f4a01d62f2d3806245f6a">llvm::MipsAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a2aca46ca706a8a857dc668e015740e53">llvm::XtensaAsmPrinter::emitMachineConstantPoolEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a344316dc056a6367fab14f5ce61b99f7">llvm::AsmPrinter::GetCPISymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>.</p>

</div>
</div>

### IsMachineConstantPoolEntry {#aad111db19720a77f310e76c0dbb7cb9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineConstantPoolEntry::IsMachineConstantPoolEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>Referenced by <a href="#a1c9559c3abf75a6df6bd2abe7131f277">isMachineConstantPoolEntry</a>, <a href="#a564e20362b45faa1cbb379ee0acfaf56">MachineConstantPoolEntry</a> and <a href="#ad055d6c5c902869c04a999ccd3ed794f">MachineConstantPoolEntry</a>.</p>

</div>
</div>

### MachineCPVal {#a5c4adcee15baa3809b6c4393307b10d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineConstantPoolValue* llvm::MachineConstantPoolEntry::MachineCPVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ae22cc3a2a24f4a01d62f2d3806245f6a">llvm::MipsAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a2aca46ca706a8a857dc668e015740e53">llvm::XtensaAsmPrinter::emitMachineConstantPoolEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>.</p>

</div>
</div>

### Val {#a020d97c78e923fb96910f087012f9be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::MachineConstantPoolEntry llvm::MachineConstantPoolEntry::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The constant itself.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ae22cc3a2a24f4a01d62f2d3806245f6a">llvm::MipsAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a2aca46ca706a8a857dc668e015740e53">llvm::XtensaAsmPrinter::emitMachineConstantPoolEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a344316dc056a6367fab14f5ce61b99f7">llvm::AsmPrinter::GetCPISymbol</a>, <a href="#a83ee6354426969c03c400e0458e8038b">getSizeInBytes</a>, <a href="#a564e20362b45faa1cbb379ee0acfaf56">MachineConstantPoolEntry</a>, <a href="#ad055d6c5c902869c04a999ccd3ed794f">MachineConstantPoolEntry</a>, <a href="#a022fed9cbfe76fd6c3b2a2358f8de17c">needsRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">MachineConstantPool.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp">MachineFunction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
