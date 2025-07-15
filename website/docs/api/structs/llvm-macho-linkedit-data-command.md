---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/macho/linkedit-data-command
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `linkedit_data_command` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MachO::linkedit_data_command { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7baa889dc47e7c8ff2d07fa9240eaaf1">cmd</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1362ae4d0a99fed872ed4549adc95c4">cmdsize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a718c920e2473631759319ce93d069224">dataoff</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d4425eb797faa587c5634883588c45d">datasize</a></td>
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


<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### cmd {#a7baa889dc47e7c8ff2d07fa9240eaaf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::linkedit_data_command::cmd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2b03ad21c736b26f5396403bf49f2a59">llvm::object::MachOObjectFile::getDataInCodeLoadCommand</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a64bfe87a4a35f817e902fc4c3c50f5d2">llvm::object::MachOObjectFile::getLinkOptHintsLoadCommand</a>.</p>

</div>
</div>

### cmdsize {#ae1362ae4d0a99fed872ed4549adc95c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::linkedit_data_command::cmdsize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#abe7067ce0893d97940a85141e4c44776">checkLinkeditDataCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2b03ad21c736b26f5396403bf49f2a59">llvm::object::MachOObjectFile::getDataInCodeLoadCommand</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a64bfe87a4a35f817e902fc4c3c50f5d2">llvm::object::MachOObjectFile::getLinkOptHintsLoadCommand</a>.</p>

</div>
</div>

### dataoff {#a718c920e2473631759319ce93d069224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::linkedit_data_command::dataoff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a21eb1fb7d7f36d23fdd47f8e7ff0e2f1">llvm::object::MachOObjectFile::begin_dices</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#abe7067ce0893d97940a85141e4c44776">checkLinkeditDataCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a67ca29eb8dc5ee438d5cc11cf5a460d9">llvm::object::MachOObjectFile::end_dices</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad107a2e9bf01094f9564019267eace1d">llvm::object::MachOObjectFile::getChainedFixupsHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a226f358d6c1305cdba13949825b60b49">llvm::object::MachOObjectFile::getChainedFixupsLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a766c3350d64dde8af24ef7b600b11185">llvm::object::MachOObjectFile::getChainedFixupsSegments</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2b03ad21c736b26f5396403bf49f2a59">llvm::object::MachOObjectFile::getDataInCodeLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a11261ec56e31921149aa022482d80e7e">llvm::object::MachOObjectFile::getDyldChainedFixupTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7107ae3ee300f48f02997f50fe543c0f">llvm::object::MachOObjectFile::getDyldExportsTrie</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6e304ff95b5d1ea04529da35d5307d6f">llvm::object::MachOObjectFile::getFunctionStarts</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a64bfe87a4a35f817e902fc4c3c50f5d2">llvm::object::MachOObjectFile::getLinkOptHintsLoadCommand</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#ace4d95a09224c0956cada6a3a7319e3a">llvm::objcopy::macho::MachOWriter::totalSize</a>.</p>

</div>
</div>

### datasize {#a7d4425eb797faa587c5634883588c45d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::linkedit_data_command::datasize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#abe7067ce0893d97940a85141e4c44776">checkLinkeditDataCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a67ca29eb8dc5ee438d5cc11cf5a460d9">llvm::object::MachOObjectFile::end_dices</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad107a2e9bf01094f9564019267eace1d">llvm::object::MachOObjectFile::getChainedFixupsHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a766c3350d64dde8af24ef7b600b11185">llvm::object::MachOObjectFile::getChainedFixupsSegments</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2b03ad21c736b26f5396403bf49f2a59">llvm::object::MachOObjectFile::getDataInCodeLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a11261ec56e31921149aa022482d80e7e">llvm::object::MachOObjectFile::getDyldChainedFixupTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7107ae3ee300f48f02997f50fe543c0f">llvm::object::MachOObjectFile::getDyldExportsTrie</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a64bfe87a4a35f817e902fc4c3c50f5d2">llvm::object::MachOObjectFile::getLinkOptHintsLoadCommand</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#ace4d95a09224c0956cada6a3a7319e3a">llvm::objcopy::macho::MachOWriter::totalSize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
