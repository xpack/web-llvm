---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/macho/symtab-command
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `symtab_command` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::MachO::symtab_command { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73d1a8cae2f0eb315e69c92f67fde5f">cmd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a6ee3c99c53b7173818e4ed375276f">cmdsize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c74170eea156826ddfb4b61bd5d043">symoff</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fe8ad1b38dc828beefc5757d7dc1a3a">nsyms</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad664b3b2032af10912280b74303ee21d">stroff</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1459968fe2ad55b364958070dde70c6e">strsize</a></td>
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


<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### cmd {#ac73d1a8cae2f0eb315e69c92f67fde5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::symtab_command::cmd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9451d5e767c3b97403785baaff3c6a44">llvm::object::MachOObjectFile::getSymtabLoadCommand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#afacaf9cfb208cb0914f70e534a469790">llvm::MachO::swapStruct</a>.</p>

</div>
</div>

### cmdsize {#a97a6ee3c99c53b7173818e4ed375276f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::symtab_command::cmdsize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9451d5e767c3b97403785baaff3c6a44">llvm::object::MachOObjectFile::getSymtabLoadCommand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#afacaf9cfb208cb0914f70e534a469790">llvm::MachO::swapStruct</a>.</p>

</div>
</div>

### nsyms {#a1fe8ad1b38dc828beefc5757d7dc1a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::symtab_command::nsyms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7d7c96e485022e0023e9b8eec0257f0e">llvm::object::MachOObjectFile::getSymbolByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9451d5e767c3b97403785baaff3c6a44">llvm::object::MachOObjectFile::getSymtabLoadCommand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#afacaf9cfb208cb0914f70e534a469790">llvm::MachO::swapStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a21f780beb96b3c8859b9f75422e2c4f9">llvm::object::MachOObjectFile::symbol_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aabf498b6cb34cb967c73e3c0c51baee2">llvm::object::MachOObjectFile::symbol_end</a>.</p>

</div>
</div>

### stroff {#ad664b3b2032af10912280b74303ee21d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::symtab_command::stroff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad451ffea9d6ef1b5ec634f176bf6dcad">llvm::object::MachOObjectFile::getStringTableData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9451d5e767c3b97403785baaff3c6a44">llvm::object::MachOObjectFile::getSymtabLoadCommand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#afacaf9cfb208cb0914f70e534a469790">llvm::MachO::swapStruct</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#ace4d95a09224c0956cada6a3a7319e3a">llvm::objcopy::macho::MachOWriter::totalSize</a>.</p>

</div>
</div>

### strsize {#a1459968fe2ad55b364958070dde70c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::symtab_command::strsize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a58bd45157985a622dba76ecef6375f4d">llvm::object::MachOObjectFile::checkSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad451ffea9d6ef1b5ec634f176bf6dcad">llvm::object::MachOObjectFile::getStringTableData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9451d5e767c3b97403785baaff3c6a44">llvm::object::MachOObjectFile::getSymtabLoadCommand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#afacaf9cfb208cb0914f70e534a469790">llvm::MachO::swapStruct</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#ace4d95a09224c0956cada6a3a7319e3a">llvm::objcopy::macho::MachOWriter::totalSize</a>.</p>

</div>
</div>

### symoff {#ae6c74170eea156826ddfb4b61bd5d043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::symtab_command::symoff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a19321b2c5a24656fe59c193ae2892453">llvm::object::MachOObjectFile::getRelocationSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7d7c96e485022e0023e9b8eec0257f0e">llvm::object::MachOObjectFile::getSymbolByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a24c6aaf027b70314a4e7cb05b34ab302">llvm::object::MachOObjectFile::getSymbolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9451d5e767c3b97403785baaff3c6a44">llvm::object::MachOObjectFile::getSymtabLoadCommand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#afacaf9cfb208cb0914f70e534a469790">llvm::MachO::swapStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aabf498b6cb34cb967c73e3c0c51baee2">llvm::object::MachOObjectFile::symbol_end</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#ace4d95a09224c0956cada6a3a7319e3a">llvm::objcopy::macho::MachOWriter::totalSize</a>.</p>

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
