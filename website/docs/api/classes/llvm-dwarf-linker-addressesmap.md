---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/addressesmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AddressesMap` Class

<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/addressesmap">AddressesMap</a> represents information about valid addresses used by debug information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::AddressesMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">llvm/DWARFLinker/AddressesMap.h</a>"
</div>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f8ce49f66144c4d333e491c915ea98">~AddressesMap</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18ef37da4a8994cd5174b53b7353d927">hasValidRelocs</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks that there are valid relocations in the .debug_info section. <a href="#a18ef37da4a8994cd5174b53b7353d927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3747d64ebd2ed13c010cfc3a5a1bc42">getExprOpAddressRelocAdjustment</a> (DWARFUnit &amp;U, const DWARFExpression::Operation &amp;Op, uint64_t StartOffset, uint64_t EndOffset, bool Verbose)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks that the specified DWARF expression operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> references live code section and returns the relocation adjustment value (to get the linked address this value might be added to the source expression operand address). <a href="#ad3747d64ebd2ed13c010cfc3a5a1bc42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8507c66ef225e656610e1d516b0abbd">getSubprogramRelocAdjustment</a> (const DWARFDie &amp;DIE, bool Verbose)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks that the specified subprogram <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> references the live code section and returns the relocation adjustment value (to get the linked address this value might be added to the source subprogram address). <a href="#af8507c66ef225e656610e1d516b0abbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e4cc0aea50ba2a134e3c877ed20b115">getLibraryInstallName</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab88057ef261bb17c59bb4f1074a99b10">applyValidRelocs</a> (MutableArrayRef&lt; char &gt; Data, uint64_t BaseOffset, bool IsLittleEndian)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the valid relocations to the buffer <span class="doxyComputerOutput">Data</span>, taking into account that Data is at <span class="doxyComputerOutput">BaseOffset</span> in the .debug_info section. <a href="#ab88057ef261bb17c59bb4f1074a99b10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7b7c125a5abb6f66257b2a61eacef5">needToSaveValidRelocs</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the linker needs to gather and save relocation info. <a href="#a6a7b7c125a5abb6f66257b2a61eacef5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40629084a0a03082e5f750951a35c4e1">updateAndSaveValidRelocs</a> (bool IsDWARF5, uint64_t OriginalUnitOffset, int64_t LinkedOffset, uint64_t StartOffset, uint64_t EndOffset)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update and save relocation values to be serialized. <a href="#a40629084a0a03082e5f750951a35c4e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b7f54d925314ab2396503239bae80e">updateRelocationsWithUnitOffset</a> (uint64_t OriginalUnitOffset, uint64_t OutputUnitOffset)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the valid relocations that used OriginalUnitOffset as the compile unit offset, and update their values to reflect OutputUnitOffset. <a href="#af1b7f54d925314ab2396503239bae80e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59abbc867fdf95ea0dba1b312b335cfc">clear</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erases all data. <a href="#a59abbc867fdf95ea0dba1b312b335cfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, std::optional&lt; int64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af518b8bb3f9740abb54f9aadf86d7344">getVariableRelocAdjustment</a> (const DWARFDie &amp;DIE, bool Verbose)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function checks whether variable has DWARF expression containing operation referencing live address(f.e. <a href="#af518b8bb3f9740abb54f9aadf86d7344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821aae4ef65c82cc46831aa9d212cc7f">isTlsAddressCode</a> (uint8_t DW_OP_Code)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/addressesmap">AddressesMap</a> represents information about valid addresses used by debug information.</p>


<p>Valid addresses are those which points to live code sections. i.e. relocations for these addresses point into sections which would be/are placed into resulting binary.</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~AddressesMap() {#a80f8ce49f66144c4d333e491c915ea98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::dwarf_linker::AddressesMap::~AddressesMap ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyValidRelocs() {#ab88057ef261bb17c59bb4f1074a99b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::dwarf_linker::AddressesMap::applyValidRelocs (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Data, uint64_t BaseOffset, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply the valid relocations to the buffer <span class="doxyComputerOutput">Data</span>, taking into account that Data is at <span class="doxyComputerOutput">BaseOffset</span> in the .debug_info section.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true whether any reloc has been applied.</p></dd>
</dl>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>

</div>
</div>

### clear() {#a59abbc867fdf95ea0dba1b312b335cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::AddressesMap::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erases all data.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>

</div>
</div>

### getExprOpAddressRelocAdjustment() {#ad3747d64ebd2ed13c010cfc3a5a1bc42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; int64_t &gt; llvm::dwarf_linker::AddressesMap::getExprOpAddressRelocAdjustment (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; U, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/operation">DWARFExpression::Operation</a> &amp; Op, uint64_t StartOffset, uint64_t EndOffset, bool Verbose)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks that the specified DWARF expression operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> references live code section and returns the relocation adjustment value (to get the linked address this value might be added to the source expression operand address).</p>


<p>Print debug output if <span class="doxyComputerOutput">Verbose</span> is true.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>relocation adjustment value or std::nullopt if there is no corresponding live address.</p></dd>
</dl>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>


<p>Referenced by <a href="#af518b8bb3f9740abb54f9aadf86d7344">getVariableRelocAdjustment</a>.</p>

</div>
</div>

### getLibraryInstallName() {#a7e4cc0aea50ba2a134e3c877ed20b115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; StringRef &gt; llvm::dwarf_linker::AddressesMap::getLibraryInstallName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>

</div>
</div>

### getSubprogramRelocAdjustment() {#af8507c66ef225e656610e1d516b0abbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; int64_t &gt; llvm::dwarf_linker::AddressesMap::getSubprogramRelocAdjustment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; DIE, bool Verbose)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks that the specified subprogram <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> references the live code section and returns the relocation adjustment value (to get the linked address this value might be added to the source subprogram address).</p>


<p>Allowed kinds of input <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>: DW_TAG_subprogram, DW_TAG_label. Print debug output if <span class="doxyComputerOutput">Verbose</span> is true.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>relocation adjustment value or std::nullopt if there is no corresponding live address.</p></dd>
</dl>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

### getVariableRelocAdjustment() {#af518b8bb3f9740abb54f9aadf86d7344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, std::optional&lt; int64_t &gt; &gt; llvm::dwarf_linker::AddressesMap::getVariableRelocAdjustment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; DIE, bool Verbose)</td>
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

<p>This function checks whether variable has DWARF expression containing operation referencing live address(f.e.</p>


<p>DW_OP_addr, DW_OP_addrx...).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>first is true if the expression has an operation referencing an address. second is the relocation adjustment value if the live address is referenced.</p></dd>
</dl>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#ad3747d64ebd2ed13c010cfc3a5a1bc42">getExprOpAddressRelocAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#ac44e64e0d814099105dde610b11c9914">llvm::DIE::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#aeac16c22ec5a0c13658381144c7e3439">llvm::DIE::getTag</a>, <a href="#a821aae4ef65c82cc46831aa9d212cc7f">isTlsAddressCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

### hasValidRelocs() {#a18ef37da4a8994cd5174b53b7353d927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::dwarf_linker::AddressesMap::hasValidRelocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks that there are valid relocations in the .debug_info section.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>

</div>
</div>

### needToSaveValidRelocs() {#a6a7b7c125a5abb6f66257b2a61eacef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::dwarf_linker::AddressesMap::needToSaveValidRelocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the linker needs to gather and save relocation info.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>

</div>
</div>

### updateAndSaveValidRelocs() {#a40629084a0a03082e5f750951a35c4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::AddressesMap::updateAndSaveValidRelocs (bool IsDWARF5, uint64_t OriginalUnitOffset, int64_t LinkedOffset, uint64_t StartOffset, uint64_t EndOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update and save relocation values to be serialized.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>

</div>
</div>

### updateRelocationsWithUnitOffset() {#af1b7f54d925314ab2396503239bae80e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::AddressesMap::updateRelocationsWithUnitOffset (uint64_t OriginalUnitOffset, uint64_t OutputUnitOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the valid relocations that used OriginalUnitOffset as the compile unit offset, and update their values to reflect OutputUnitOffset.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### isTlsAddressCode() {#a821aae4ef65c82cc46831aa9d212cc7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::AddressesMap::isTlsAddressCode (uint8_t DW_OP_Code)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a>.</p>


<p>Referenced by <a href="#af518b8bb3f9740abb54f9aadf86d7344">getVariableRelocAdjustment</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/addressesmap-h">AddressesMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
