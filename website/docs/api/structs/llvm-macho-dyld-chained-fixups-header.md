---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/macho/dyld-chained-fixups-header
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `dyld_chained_fixups_header` Struct Reference

<p>Structs for dyld chained fixups. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MachO::dyld_chained_fixups_header { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5495744412094d91b463b61fe6b442">fixups_version</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>0 <a href="#acb5495744412094d91b463b61fe6b442">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1d84db8570cf688b0f2554c7c832f9d">starts_offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset of <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-image">dyld_chained_starts_in_image</a>. <a href="#ab1d84db8570cf688b0f2554c7c832f9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba7f01fd5928a85ff8afad665d13c95">imports_offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset of imports table in chain_data. <a href="#a9ba7f01fd5928a85ff8afad665d13c95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ee0f53c430561d30e3b634d60591bd">symbols_offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset of symbol strings in chain_data. <a href="#ab8ee0f53c430561d30e3b634d60591bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ddef692d822a840c20000331df7cb47">imports_count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of imported symbol names. <a href="#a1ddef692d822a840c20000331df7cb47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267bb8c08a7c01b613017b6abbc4f5d8">imports_format</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DYLD_CHAINED_IMPORT*. <a href="#a267bb8c08a7c01b613017b6abbc4f5d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdbf2385f61597ac81981c9a07f1c2be">symbols_format</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>0 =&gt; uncompressed, 1 =&gt; zlib compressed <a href="#acdbf2385f61597ac81981c9a07f1c2be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Structs for dyld chained fixups.</p>


<p><a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-fixups-header">dyld_chained_fixups_header</a> is the data pointed to by LC_DYLD_CHAINED_FIXUPS load command.</p>


<p>Definition at line 1064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### fixups\_version {#acb5495744412094d91b463b61fe6b442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::dyld_chained_fixups_header::fixups_version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>0</p>

<p>Definition at line 1065 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad107a2e9bf01094f9564019267eace1d">llvm::object::MachOObjectFile::getChainedFixupsHeader</a>.</p>

</div>
</div>

### imports\_count {#a1ddef692d822a840c20000331df7cb47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::dyld_chained_fixups_header::imports_count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of imported symbol names.</p>

<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### imports\_format {#a267bb8c08a7c01b613017b6abbc4f5d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::dyld_chained_fixups_header::imports_format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DYLD_CHAINED_IMPORT*.</p>

<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad107a2e9bf01094f9564019267eace1d">llvm::object::MachOObjectFile::getChainedFixupsHeader</a>.</p>

</div>
</div>

### imports\_offset {#a9ba7f01fd5928a85ff8afad665d13c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::dyld_chained_fixups_header::imports_offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset of imports table in chain_data.</p>

<p>Definition at line 1067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### starts\_offset {#ab1d84db8570cf688b0f2554c7c832f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::dyld_chained_fixups_header::starts_offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset of <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-image">dyld_chained_starts_in_image</a>.</p>

<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad107a2e9bf01094f9564019267eace1d">llvm::object::MachOObjectFile::getChainedFixupsHeader</a>.</p>

</div>
</div>

### symbols\_format {#acdbf2385f61597ac81981c9a07f1c2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::dyld_chained_fixups_header::symbols_format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>0 =&gt; uncompressed, 1 =&gt; zlib compressed</p>

<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### symbols\_offset {#ab8ee0f53c430561d30e3b634d60591bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::dyld_chained_fixups_header::symbols_offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset of symbol strings in chain_data.</p>

<p>Definition at line 1068 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
