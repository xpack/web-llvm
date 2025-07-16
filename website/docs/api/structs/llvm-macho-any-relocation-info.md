---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/macho/any-relocation-info
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `any_relocation_info` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MachO::any_relocation_info { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c1c46bbe4b0ef3065fe91d3e9ca806e">r_word0</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff97edf4109298178b12aca5621bd6ec">r_word1</a></td>
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


<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### r\_word0 {#a2c1c46bbe4b0ef3065fe91d3e9ca806e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::any_relocation_info::r_word0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a737f9117ad9ecb54eff89ae39cc5e0c1">getPlainRelocationAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/macholinkgraphbuilder/#ad63fca6e6e001f3e97eebaa2c397ffc9">llvm::jitlink::MachOLinkGraphBuilder::getRelocationInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a922ba9d09d115911235efb6e517b5ef9">getScatteredRelocationAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a53ac15ba730cd5a7e82f50b6bc1bf715">getScatteredRelocationLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ad6a5d311edf7adea28255db07dd3fc7d">getScatteredRelocationPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a77b819d412646ba61fca1a45e57a5a7c">llvm::object::MachOObjectFile::getScatteredRelocationScattered</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a17bc598aa230859797b75db2fe68ac4b">llvm::object::MachOObjectFile::getScatteredRelocationType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#add84f157f58d2607efb42b9723c3235a">anonymous{MachOEmitter.cpp}::makeRelocationInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#aed774ebd1348ca6144ae96c13de706c9">anonymous{MachOEmitter.cpp}::makeScatteredRelocationInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a49ae9aaf6cda4c28330c5915f8291d5e">llvm::MachObjectWriter::populateAddrSigSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad3926a98533b21466bcd03d5669fc642">llvm::MachO::swapStruct</a>.</p>

</div>
</div>

### r\_word1 {#aff97edf4109298178b12aca5621bd6ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::any_relocation_info::r_word1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7bec3ca52f60d7ca088f0634a2e8f779">llvm::object::MachOObjectFile::getPlainRelocationExternal</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a5bfc08d3a7440ea1dd3d51785b5d3667">getPlainRelocationLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a7c487242e400b912bb74ac8cdfc4b299">getPlainRelocationPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a99471e40aa719f7de1a81c38b8b129cc">llvm::object::MachOObjectFile::getPlainRelocationSymbolNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a20d9592bf3c885c6afab008b7bb1789e">getPlainRelocationType</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/macholinkgraphbuilder/#ad63fca6e6e001f3e97eebaa2c397ffc9">llvm::jitlink::MachOLinkGraphBuilder::getRelocationInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a3144dc7cc061533970cd9681fbbc907a">llvm::object::MachOObjectFile::getScatteredRelocationValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#add84f157f58d2607efb42b9723c3235a">anonymous{MachOEmitter.cpp}::makeRelocationInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#aed774ebd1348ca6144ae96c13de706c9">anonymous{MachOEmitter.cpp}::makeScatteredRelocationInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a49ae9aaf6cda4c28330c5915f8291d5e">llvm::MachObjectWriter::populateAddrSigSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad3926a98533b21466bcd03d5669fc642">llvm::MachO::swapStruct</a>.</p>

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
