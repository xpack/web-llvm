---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/macho/dylibreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `DylibReader` Namespace Reference

<p>Defines the <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> Dynamic Library Reader. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::MachO::DylibReader { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/dylibreader/parseoption">ParseOption</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5e38d100628a2334de10c6afc491c2">SymbolToSourceLocMap</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">llvm::StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/macho/recordloc">RecordLoc</a> &gt;</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ab5b5510db9083f228e5929bf5ad0f717">Records</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d593efec1083a71925949203aaf6d31">readFile</a> (MemoryBufferRef Buffer, const ParseOption &amp;Opt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse Mach-O dynamic libraries to extract TAPI attributes. <a href="#a1d593efec1083a71925949203aaf6d31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb5091148492d06e7d5728aa5f827063">get</a> (MemoryBufferRef Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get TAPI file representation of binary dylib. <a href="#afb5091148492d06e7d5728aa5f827063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0f5e38d100628a2334de10c6afc491c2">SymbolToSourceLocMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fbf6763e62eb4e5268f421eee37d6b1">accumulateSourceLocFromDSYM</a> (const StringRef DSYM, const Target &amp;T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source location for each symbol from dylib. <a href="#a1fbf6763e62eb4e5268f421eee37d6b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Defines the <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> Dynamic Library Reader.</p>

<div class="doxySectionDef">

## Typedefs

### SymbolToSourceLocMap {#a0f5e38d100628a2334de10c6afc491c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::DylibReader::SymbolToSourceLocMap =  llvm::StringMap&lt;RecordLoc&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/dylibreader-h">DylibReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### accumulateSourceLocFromDSYM() {#a1fbf6763e62eb4e5268f421eee37d6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolToSourceLocMap llvm::MachO::DylibReader::accumulateSourceLocFromDSYM (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DSYM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/target">Target</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the source location for each symbol from dylib.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DSYM</td>
<td class="doxyParamItemDescription"><p>Path to DSYM file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>Requested target slice for dylib.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/dylibreader-h">DylibReader.h</a>, definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#a0bf6fb10c8a68470e3b84ab25d8e5c59">accumulateLocs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ad6f9fa82bb8b6a5dae98b9d9d346d913">llvm::DWARFContext::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#af68e7505088095ee20bd4523f7f562a7">DWARFErrorHandler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a301ba38f5a267f3cf123d6a9f551e3fd">llvm::object::MachOObjectFile::findDsymObjectMembers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a2a0395d53f0485827bc5782c0b64a4e8">llvm::MachO::getArchitectureName</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a6fbfbccaef05e07b2b1615224d5e20bdab6ec7abeb6ae29cc35a4b47475e12afe">llvm::DWARFContext::Process</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### get() {#afb5091148492d06e7d5728aa5f827063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; InterfaceFile &gt; &gt; llvm::MachO::DylibReader::get (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get TAPI file representation of binary dylib.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Buffer</td>
<td class="doxyParamItemDescription"><p>Data that points to dylib.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/dylibreader-h">DylibReader.h</a>, definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8a59001c151594d4ff93a12b10c8368f">llvm::MachO::convertToInterfaceFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="#a1d593efec1083a71925949203aaf6d31">readFile</a>.</p>

</div>
</div>

### readFile() {#a1d593efec1083a71925949203aaf6d31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Records &gt; llvm::MachO::DylibReader::readFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/dylibreader/parseoption">ParseOption</a> &amp; Opt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse Mach-O dynamic libraries to extract TAPI attributes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Buffer</td>
<td class="doxyParamItemDescription"><p>Data that points to dylib.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Options</td>
<td class="doxyParamItemDescription"><p>Determines which attributes to extract.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>List of record slices.</p></dd>
</dl>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/dylibreader-h">DylibReader.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397a3a18faffa4e9a399fd8bb06731321c83">llvm::MachO::AK_unknown</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dylibreader/parseoption/#aa36956139c4ba3be2282474bddfd6feb">llvm::MachO::DylibReader::ParseOption::Archs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da807dbe7d1c25a633894d4a231b1c76d3">llvm::Bin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#ab42803a7054d1210223d0e72ec575d22">constructTriples</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a915d40ccd86e41a5ffd31c941a9f566ba54a20ba047c364535e51890a7f67faee">llvm::MachO::EmptyResults</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad65abe44485788236a56a6781189f1eb">llvm::MachO::getArchitectureFromCpuType</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a3201ce149cba3920fc965378ceddbcb8">llvm::MemoryBufferRef::getBufferIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset/#a76b67e4256ae13907721adbb0762ab78">llvm::MachO::ArchitectureSet::has</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a74b6fee77fe76fef829c29a931a6bdca">llvm::MachO::mapToPlatformType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aaa74df7db16f2f62baf972f3ba0889ca1">llvm::MachO::MH_BUNDLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa61431e5ba87f234d7b1ffa7bfd12c98e">llvm::MachO::MH_DYLIB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa6885d2f4c415c3e66cb5b2a71b4d6e46">llvm::MachO::MH_DYLIB_STUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a915d40ccd86e41a5ffd31c941a9f566bad344345f7bda569a935ca90209857a5e">llvm::MachO::NoSuchArchitecture</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a915d40ccd86e41a5ffd31c941a9f566ba12ddb6a1a15e913daa50def1f393d1d7">llvm::MachO::UnsupportedTarget</a>.</p>


<p>Referenced by <a href="#afb5091148492d06e7d5728aa5f827063">get</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/dylibreader-h">DylibReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
