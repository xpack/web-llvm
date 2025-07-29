---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfdataextractor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFDataExtractor` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> (typically for an in-memory copy of an object-file section) plus a relocation map for that section, if there is one. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFDataExtractor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">llvm/DebugInfo/DWARF/DWARFDataExtractor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38eb941ecccfee736a78a034bf5b0832">DWARFDataExtractor</a> (const DWARFObject &amp;Obj, const DWARFSection &amp;Section, bool IsLittleEndian, uint8_t AddressSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor for the normal case of extracting data from a DWARF section. <a href="#a38eb941ecccfee736a78a034bf5b0832">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ecaa1a4ce76a3cb0a3b5f3b48ea587">DWARFDataExtractor</a> (StringRef Data, bool IsLittleEndian, uint8_t AddressSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor for cases when there are no relocations. <a href="#a45ecaa1a4ce76a3cb0a3b5f3b48ea587">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c4e8cde73237ab00ac91c380ff95f38">DWARFDataExtractor</a> (ArrayRef&lt; uint8_t &gt; Data, bool IsLittleEndian, uint8_t AddressSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a9a9bc490d816bb7e08cb0eca3b54ae">DWARFDataExtractor</a> (const DWARFDataExtractor &amp;Other, size_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Truncating constructor. <a href="#a7a9a9bc490d816bb7e08cb0eca3b54ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10e13073556511543a885ea96b61ff6c">getInitialLength</a> (uint64_t *Off, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts the DWARF "initial length" field, which can either be a 32-bit value smaller than 0xfffffff0, or the value 0xffffffff followed by a 64-bit length. <a href="#a10e13073556511543a885ea96b61ff6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a6679ff65d9ecce4d14d11f9d1ce175">getInitialLength</a> (Cursor &amp;C) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814a7655e692e4f880b38eed143052fb">getRelocatedValue</a> (uint32_t Size, uint64_t *Off, uint64_t *SectionIndex=nullptr, Error *Err=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts a value and applies a relocation to the result if one exists for the given offset. <a href="#a814a7655e692e4f880b38eed143052fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe60ab4756377888e3bf33351d77c4a">getRelocatedValue</a> (Cursor &amp;C, uint32_t Size, uint64_t *SectionIndex=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01887ce3b95212d5c5b89887c93ad662">getRelocatedAddress</a> (uint64_t *Off, uint64_t *SecIx=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts an address-sized value and applies a relocation to the result if one exists for the given offset. <a href="#a01887ce3b95212d5c5b89887c93ad662">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048e04c3ab40f799fd7e530b1be61f6a">getRelocatedAddress</a> (Cursor &amp;C, uint64_t *SecIx=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ceb7476c6b212e0f515e2a4cc9e551">getEncodedPointer</a> (uint64_t *Offset, uint8_t Encoding, uint64_t AbsPosOffset=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts a DWARF-encoded pointer in <span class="doxyComputerOutput">Offset</span> using <span class="doxyComputerOutput">Encoding</span>. <a href="#ab0ceb7476c6b212e0f515e2a4cc9e551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ef55600a6347ad0b1c84236c62011e">Obj</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27059f3382ec844617c705d366875918">Section</a> = nullptr</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> (typically for an in-memory copy of an object-file section) plus a relocation map for that section, if there is one.</p>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFDataExtractor() {#a38eb941ecccfee736a78a034bf5b0832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFDataExtractor::DWARFDataExtractor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; Section, bool IsLittleEndian, uint8_t AddressSize)</td>
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

<p>Constructor for the normal case of extracting data from a DWARF section.</p>


<p>The <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a>'s lifetime must be at least as long as the extractor's.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a46aa25f9df530608164c58934b2c5f01">llvm::DataExtractor::DataExtractor</a>.</p>


<p>Referenced by <a href="#a7a9a9bc490d816bb7e08cb0eca3b54ae">DWARFDataExtractor</a>.</p>

</div>
</div>

### DWARFDataExtractor() {#a45ecaa1a4ce76a3cb0a3b5f3b48ea587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFDataExtractor::DWARFDataExtractor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, bool IsLittleEndian, uint8_t AddressSize)</td>
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

<p>Constructor for cases when there are no relocations.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a46aa25f9df530608164c58934b2c5f01">llvm::DataExtractor::DataExtractor</a>.</p>

</div>
</div>

### DWARFDataExtractor() {#a9c4e8cde73237ab00ac91c380ff95f38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFDataExtractor::DWARFDataExtractor (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, bool IsLittleEndian, uint8_t AddressSize)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a46aa25f9df530608164c58934b2c5f01">llvm::DataExtractor::DataExtractor</a> and <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a13f08bc0715c6ccbe15c82f2fc9e61ca">llvm::DataExtractor::size</a>.</p>

</div>
</div>

### DWARFDataExtractor() {#a7a9a9bc490d816bb7e08cb0eca3b54ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFDataExtractor::DWARFDataExtractor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp; Other, size_t Length)</td>
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

<p>Truncating constructor.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a46aa25f9df530608164c58934b2c5f01">llvm::DataExtractor::DataExtractor</a>, <a href="#a38eb941ecccfee736a78a034bf5b0832">DWARFDataExtractor</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a727b157e8418a101ec69dcb2e9ceea39">llvm::DataExtractor::getAddressSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a882aa042b8549998c9ae43305a79d955">llvm::DataExtractor::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad9617bd42a629b75a6804af2cbcddddf">llvm::DataExtractor::isLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEncodedPointer() {#ab0ceb7476c6b212e0f515e2a4cc9e551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDataExtractor::getEncodedPointer (uint64_t * Offset, uint8_t Encoding, uint64_t AbsPosOffset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extracts a DWARF-encoded pointer in <span class="doxyComputerOutput">Offset</span> using <span class="doxyComputerOutput">Encoding</span>.</p>


<p>There is a DWARF encoding that uses a PC-relative adjustment. For these values, <span class="doxyComputerOutput">AbsPosOffset</span> is used to fix them, which should reflect the absolute address of this pointer.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdataextractor-cpp">DWARFDataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab8bb265a153372d87860f6a33d858f3e">llvm::dwarf::DW_EH_PE_absptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a9471abf8a810890073e81b0f37b42855">llvm::dwarf::DW_EH_PE_aligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a0e91cc214494d9c9f9c8adcf03be6e51">llvm::dwarf::DW_EH_PE_datarel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a93177d51171d5b5badb427f677058688">llvm::dwarf::DW_EH_PE_funcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255af88641d07cb5fdb688ad0d4e78314222">llvm::dwarf::DW_EH_PE_omit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a18cb02c6dc96569494f65b82ab70487b">llvm::dwarf::DW_EH_PE_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abf732c58551b977c2f830e8ddd06e64f">llvm::dwarf::DW_EH_PE_sdata2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a68bcc7d64ea60cf76503e913360e0b01">llvm::dwarf::DW_EH_PE_sdata4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab4f228eae8e91cb5eb218c4372d2cd75">llvm::dwarf::DW_EH_PE_sdata8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255acdcf9e337d25fb5063bf168d12c0e9fd">llvm::dwarf::DW_EH_PE_sleb128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a02f324799871fabe4675111245994c94">llvm::dwarf::DW_EH_PE_textrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab06941f802d97190e82e32018265b5f1">llvm::dwarf::DW_EH_PE_udata2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abfafdba601fd5cab55113f2cdb96c033">llvm::dwarf::DW_EH_PE_udata4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac75ce7ce2df1136a194d4cd1d889c06a">llvm::dwarf::DW_EH_PE_udata8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac78bfa2d0d61171586536bd55b3919f9">llvm::dwarf::DW_EH_PE_uleb128</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a727b157e8418a101ec69dcb2e9ceea39">llvm::DataExtractor::getAddressSize</a>, <a href="#a814a7655e692e4f880b38eed143052fb">getRelocatedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a5cc53bb122d7af1e40b77867d080114d">llvm::DataExtractor::getSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a88a902fb0c1d600e6b4fe880d770acdf">llvm::DataExtractor::getSLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a6f2f68613d44758a66e49320fb075a02">llvm::DataExtractor::getULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a091e3b172c8f532c021b21c90fd3d461">llvm::DataExtractor::getUnsigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>

</div>
</div>

### getInitialLength() {#a10e13073556511543a885ea96b61ff6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, dwarf::DwarfFormat &gt; DWARFDataExtractor::getInitialLength (uint64_t * Off, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extracts the DWARF "initial length" field, which can either be a 32-bit value smaller than 0xfffffff0, or the value 0xffffffff followed by a 64-bit length.</p>


<p>Returns the actual length, and the DWARF format which is encoded in the field. In case of errors, it returns {0, DWARF32} and leaves the offset unchanged.</p>


<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdataextractor-cpp">DWARFDataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4adc3aedef0caeccf6d845a430da6d3f8d">llvm::dwarf::DW_LENGTH_DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a8cff646c8838f1f3e3e948bd985ee5f4">llvm::dwarf::DW_LENGTH_lo_reserved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>, <a href="#a814a7655e692e4f880b38eed143052fb">getRelocatedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/header/#a7831179949c0d3906a51516d928473de">llvm::DWARFDebugNames::Header::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>, <a href="#a1a6679ff65d9ecce4d14d11f9d1ce175">getInitialLength</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#a615332b0161a87347eea3360a5d51410">llvm::DWARFVerifier::handleDebugStrOffsets</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a5d63a698aa61a9d04d1826b1f91a0b43">llvm::DWARFDebugLine::Prologue::parse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aca926e51a519a29293e7428001c79cef">llvm::parseInfoSectionUnitHeader</a>.</p>

</div>
</div>

### getInitialLength() {#a1a6679ff65d9ecce4d14d11f9d1ce175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, dwarf::DwarfFormat &gt; llvm::DWARFDataExtractor::getInitialLength (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad45d3690fa998e1a63931de09ff05bdc">llvm::DataExtractor::getError</a>, <a href="#a10e13073556511543a885ea96b61ff6c">getInitialLength</a> and <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a2f74888abb46158e0f6ddec827c36922">llvm::DataExtractor::getOffset</a>.</p>

</div>
</div>

### getRelocatedAddress() {#a01887ce3b95212d5c5b89887c93ad662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDataExtractor::getRelocatedAddress (uint64_t * Off, uint64_t * SecIx=nullptr)</td>
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

<p>Extracts an address-sized value and applies a relocation to the result if one exists for the given offset.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a727b157e8418a101ec69dcb2e9ceea39">llvm::DataExtractor::getAddressSize</a> and <a href="#a814a7655e692e4f880b38eed143052fb">getRelocatedValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>.</p>

</div>
</div>

### getRelocatedAddress() {#a048e04c3ab40f799fd7e530b1be61f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDataExtractor::getRelocatedAddress (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C, uint64_t * SecIx=nullptr)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a727b157e8418a101ec69dcb2e9ceea39">llvm::DataExtractor::getAddressSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad45d3690fa998e1a63931de09ff05bdc">llvm::DataExtractor::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a2f74888abb46158e0f6ddec827c36922">llvm::DataExtractor::getOffset</a> and <a href="#a814a7655e692e4f880b38eed143052fb">getRelocatedValue</a>.</p>

</div>
</div>

### getRelocatedValue() {#a814a7655e692e4f880b38eed143052fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DWARFDataExtractor::getRelocatedValue (uint32_t Size, uint64_t * Off, uint64_t * SectionIndex=nullptr, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extracts a value and applies a relocation to the result if one exists for the given offset.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdataextractor-cpp">DWARFDataExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a091e3b172c8f532c021b21c90fd3d461">llvm::DataExtractor::getUnsigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a3e56be036fa3e00298b097c1bb756643">llvm::object::resolveRelocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#afb874a51b13c3cdfa8011bbf866c3658">dumpStringOffsetsSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugpubtable/#a021fcf81d5e7d4534f0aaf4984381236">llvm::DWARFDebugPubTable::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>, <a href="#ab0ceb7476c6b212e0f515e2a4cc9e551">getEncodedPointer</a>, <a href="#a10e13073556511543a885ea96b61ff6c">getInitialLength</a>, <a href="#a048e04c3ab40f799fd7e530b1be61f6a">getRelocatedAddress</a>, <a href="#a01887ce3b95212d5c5b89887c93ad662">getRelocatedAddress</a>, <a href="#afbe60ab4756377888e3bf33351d77c4a">getRelocatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#a5d63a698aa61a9d04d1826b1f91a0b43">llvm::DWARFDebugLine::Prologue::parse</a>.</p>

</div>
</div>

### getRelocatedValue() {#afbe60ab4756377888e3bf33351d77c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDataExtractor::getRelocatedValue (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">Cursor</a> &amp; C, uint32_t Size, uint64_t * SectionIndex=nullptr)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad45d3690fa998e1a63931de09ff05bdc">llvm::DataExtractor::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a2f74888abb46158e0f6ddec827c36922">llvm::DataExtractor::getOffset</a>, <a href="#a814a7655e692e4f880b38eed143052fb">getRelocatedValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Obj {#ad8ef55600a6347ad0b1c84236c62011e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFObject* llvm::DWARFDataExtractor::Obj = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>

</div>
</div>

### Section {#a27059f3382ec844617c705d366875918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFSection* llvm::DWARFDataExtractor::Section = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdataextractor-h">DWARFDataExtractor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdataextractor-cpp">DWARFDataExtractor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
