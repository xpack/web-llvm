---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/pdb/modinfoflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ModInfoFlags` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::pdb::ModInfoFlags { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawtypes-h">llvm/DebugInfo/PDB/Native/RawTypes.h</a>"
</div>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fdaf72e309f7927e697f9312a275357">HasECFlagMask</a> = 0x2</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>uint16_t fWritten : 1; // True if <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor">DbiModuleDescriptor</a> is dirty uint16_t fECEnabled : 1; // Is EC symbolic info present? <a href="#a3fdaf72e309f7927e697f9312a275357">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dfb2b6b52f2a2f20f0534a8798f68c2">TypeServerIndexMask</a> = 0xFF00</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a4c462e1a3d6da2a58c49ee03adb45">TypeServerIndexShift</a> = 8</td>
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


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawtypes-h">RawTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Static Attributes

### HasECFlagMask {#a3fdaf72e309f7927e697f9312a275357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t llvm::pdb::ModInfoFlags::HasECFlagMask = 0x2</td>
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

<p>uint16_t fWritten : 1; // True if <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor">DbiModuleDescriptor</a> is dirty uint16_t fECEnabled : 1; // Is EC symbolic info present?</p>


<p>(What is EC?) uint16_t unused : 6; // Reserved uint16_t iTSM : 8; // <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Server Index for this module</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawtypes-h">RawTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor/#a79418db2c549655ab1552df2578076c3">llvm::pdb::DbiModuleDescriptor::hasECInfo</a>.</p>

</div>
</div>

### TypeServerIndexMask {#a5dfb2b6b52f2a2f20f0534a8798f68c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t llvm::pdb::ModInfoFlags::TypeServerIndexMask = 0xFF00</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawtypes-h">RawTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor/#a59bf0870cb6099a8726bb74d638f5045">llvm::pdb::DbiModuleDescriptor::getTypeServerIndex</a>.</p>

</div>
</div>

### TypeServerIndexShift {#a38a4c462e1a3d6da2a58c49ee03adb45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t llvm::pdb::ModInfoFlags::TypeServerIndexShift = 8</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawtypes-h">RawTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor/#a59bf0870cb6099a8726bb74d638f5045">llvm::pdb::DbiModuleDescriptor::getTypeServerIndex</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/rawtypes-h">RawTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
