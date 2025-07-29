---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DylibReader.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/dylibreader-h">llvm/TextAPI/DylibReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcompileunit-h">llvm/DebugInfo/DWARF/DWARFCompileUnit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">llvm/DebugInfo/DWARF/DWARFContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/binary-h">llvm/Object/Binary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/machouniversal-h">llvm/Object/MachOUniversal.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">llvm/TextAPI/InterfaceFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/recordsslice-h">llvm/TextAPI/RecordsSlice.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapierror-h">llvm/TextAPI/TextAPIError.h</a>"
#include &lt;iomanip&gt;
#include &lt;set&gt;
#include &lt;sstream&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0827719dc503c78d6b6e852dd79903">TripleVec</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static TripleVec::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e0861a16978fc748dd79c56e17e4f3">emplace</a> (TripleVec &amp;Container, Triple &amp;&amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#aec0827719dc503c78d6b6e852dd79903">TripleVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab42803a7054d1210223d0e72ec575d22">constructTriples</a> (MachOObjectFile *Obj, const Architecture ArchT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a> (MachOObjectFile *Obj, RecordsSlice &amp;Slice)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca546a54409cdfc98988096faaa1674">readSymbols</a> (MachOObjectFile *Obj, RecordsSlice &amp;Slice, const ParseOption &amp;Opt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e38c60d8641542f9d5e6fb9a282831">load</a> (MachOObjectFile *Obj, RecordsSlice &amp;Slice, const ParseOption &amp;Opt, const Architecture Arch)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68e7505088095ee20bd4523f7f562a7">DWARFErrorHandler</a> (Error Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a0f5e38d100628a2334de10c6afc491c2">SymbolToSourceLocMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf6fb10c8a68470e3b84ab25d8e5c59">accumulateLocs</a> (MachOObjectFile &amp;Obj, const std::unique_ptr&lt; DWARFContext &gt; &amp;DiCtx)</td>
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


<div class="doxySectionDef">

## Typedefs

### TripleVec {#aec0827719dc503c78d6b6e852dd79903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using TripleVec =  std::vector&lt;Triple&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### accumulateLocs() {#a0bf6fb10c8a68470e3b84ab25d8e5c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolToSourceLocMap accumulateLocs (<a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt; &amp; DiCtx)</td>
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



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3a7e2c85add6bbb98ae5b91471b11fd9a2">llvm::DILineInfoSpecifier::AbsoluteFilePath</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#a3416b4c43641068805c06a658a235f93">llvm::MachO::Symbol::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#ab8d607765ca383036fe04f640728be0f">llvm::MachO::Symbol::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ab0d2fab5845ea5a11a1a57775090aec7">llvm::MachO::parseSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a3936e16c4ba4b109e74006ad9bdc06f8">llvm::object::BasicSymbolRef::SF_Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa22a9825f4937b28269552f5b8db4a69">llvm::object::ObjectFile::symbols</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a1fbf6763e62eb4e5268f421eee37d6b1">llvm::MachO::DylibReader::accumulateSourceLocFromDSYM</a>.</p>

</div>
</div>

### constructTriples() {#ab42803a7054d1210223d0e72ec575d22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TripleVec constructTriples (<a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> ArchT)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>References <a href="#a01e0861a16978fc748dd79c56e17e4f3">emplace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a2a0395d53f0485827bc5782c0b64a4e8">llvm::MachO::getArchitectureName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a2576066f592129dbe8f9624c90bf19ef">llvm::object::MachOObjectFile::getBuildVersionLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9d29d7cb48a7f246f1c0f4507def2aa7">llvm::object::MachOObjectFile::getVersionMinLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset/#ac0dcd9160ac84c61caa4c5b4497f9fe4">llvm::MachO::ArchitectureSet::hasX86</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9397f336b10a2f4db6c6d5a8f9b49224">llvm::object::MachOObjectFile::load_commands</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/build-version-command/#a600ff720617da8e63e0187a692839a5e">llvm::MachO::build_version_command::minos</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/build-version-command/#add142f518b61fb586181c22bb0c79b3b">llvm::MachO::build_version_command::platform</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a1d593efec1083a71925949203aaf6d31">llvm::MachO::DylibReader::readFile</a>.</p>

</div>
</div>

### DWARFErrorHandler() {#af68e7505088095ee20bd4523f7f562a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFErrorHandler (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a1fbf6763e62eb4e5268f421eee37d6b1">llvm::MachO::DylibReader::accumulateSourceLocFromDSYM</a>.</p>

</div>
</div>

### emplace() {#a01e0861a16978fc748dd79c56e17e4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TripleVec::iterator emplace (<a href="#aec0827719dc503c78d6b6e852dd79903">TripleVec</a> &amp; Container, <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;&amp; T)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a6beb910ab0112de8679b6d2703351384">llvm::Triple::getEnvironment</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5a777de4cd152c5b22b9d28439326d50">llvm::Triple::getOS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a327a399b9f6ef414a29ddeffba934d26">llvm::partition_point</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ab42803a7054d1210223d0e72ec575d22">constructTriples</a> and <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a919be785fc4f5093b9b78eb157cc83b5">llvm::MaybeAlign::MaybeAlign</a>.</p>

</div>
</div>

### load() {#a29e38c60d8641542f9d5e6fb9a282831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error load (<a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * Obj, <a href="/web-llvm/docs/api/classes/llvm/macho/recordsslice">RecordsSlice</a> &amp; Slice, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/dylibreader/parseoption">ParseOption</a> &amp; Opt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> Arch)</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397a3a18faffa4e9a399fd8bb06731321c83">llvm::MachO::AK_unknown</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dylibreader/parseoption/#a216f4ce688097a72977f7b9facf69e20">llvm::MachO::DylibReader::ParseOption::MachOHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a4f3081cf8f364816d9a91b6e24d10fba">readMachOHeader</a>, <a href="#a2ca546a54409cdfc98988096faaa1674">readSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dylibreader/parseoption/#a5045d63368401005977181c0daa5057f">llvm::MachO::DylibReader::ParseOption::SymbolTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a915d40ccd86e41a5ffd31c941a9f566ba12ddb6a1a15e913daa50def1f393d1d7">llvm::MachO::UnsupportedTarget</a>.</p>

</div>
</div>

### readMachOHeader() {#a4f3081cf8f364816d9a91b6e24d10fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error readMachOHeader (<a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * Obj, <a href="/web-llvm/docs/api/classes/llvm/macho/recordsslice">RecordsSlice</a> &amp; Slice)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aeb9478037b0d4a28a04ad1d690e2f645">llvm::object::MachOObjectFile::getDylibIDLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a80dc9af48926f9c1b70075f71c6002a7">llvm::object::MachOObjectFile::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ae669e6342a3406842cda2714f1f143c9">llvm::object::MachOObjectFile::getLinkeditDataLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a66f24d7c05980ed733c32c31f099766d">llvm::object::MachOObjectFile::getRpathCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a023569a7035ef18e014f39cc2800ad07">llvm::object::MachOObjectFile::getSubClientCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6c0b621a228e683bf4590229691489aa">llvm::object::MachOObjectFile::getSubFrameworkCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a983feccca34dfdfebe0d79c35c166d7d">llvm::object::MachOObjectFile::getUuidCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9397f336b10a2f4db6c6d5a8f9b49224">llvm::object::MachOObjectFile::load_commands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7aaff029a6b6ab97a932159a93c6a0f8b3">llvm::MachO::MachO_Bundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a83b17e20682357d51cb1d5b73cbf179b">llvm::MachO::MachO_DynamicLibrary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a4900e36bf92d04bd5a750f966b8d38aa">llvm::MachO::MachO_DynamicLibrary_Stub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a56796c840e08337bb5693b43bf17360ca0f44d4fd890de3d897a1c748e5b26647">llvm::MachO::MH_APP_EXTENSION_SAFE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aaa74df7db16f2f62baf972f3ba0889ca1">llvm::MachO::MH_BUNDLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa61431e5ba87f234d7b1ffa7bfd12c98e">llvm::MachO::MH_DYLIB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa6885d2f4c415c3e66cb5b2a71b4d6e46">llvm::MachO::MH_DYLIB_STUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a56796c840e08337bb5693b43bf17360cada9b108f24a668805e4bfc6601bd4d75">llvm::MachO::MH_TWOLEVEL</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a29e38c60d8641542f9d5e6fb9a282831">load</a>.</p>

</div>
</div>

### readSymbols() {#a2ca546a54409cdfc98988096faaa1674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error readSymbols (<a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * Obj, <a href="/web-llvm/docs/api/classes/llvm/macho/recordsslice">RecordsSlice</a> &amp; Slice, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/dylibreader/parseoption">ParseOption</a> &amp; Opt)</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp">DylibReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4af6068daa29dbb05a7ead1e3b5a48bbee">llvm::MachO::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a260ec46f5a574a87a8354d4d69c6a32faf16dbf2ba1a8a6693330b41f84c3b539">llvm::MachO::EXPORT_SYMBOL_FLAGS_KIND_MASK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a16db63b01450278770fe448e7c4a3f58a6bdb5544bf045f0b3da9809acb23e909">llvm::MachO::EXPORT_SYMBOL_FLAGS_KIND_REGULAR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a16db63b01450278770fe448e7c4a3f58a6ad5d127f840b5645f0b6acd4f0e1b70">llvm::MachO::EXPORT_SYMBOL_FLAGS_KIND_THREAD_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a260ec46f5a574a87a8354d4d69c6a32fa4198b33ac527a29f5069a74e3c70d43a">llvm::MachO::EXPORT_SYMBOL_FLAGS_REEXPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a260ec46f5a574a87a8354d4d69c6a32fac211fe9ca3b2fbec0d400ef676bdfc34">llvm::MachO::EXPORT_SYMBOL_FLAGS_WEAK_DEFINITION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa0001316ad0c7eb0f1a8e298fd6e5d070">llvm::MachO::Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a24c45a64b8e2666c4706d4e0c2c1add4">llvm::object::MachOObjectFile::exports</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a86408593c34af77fdd90df932f8b5261">llvm::MachO::GlobalRecord::Function</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffaafbf0897a5a83fdd873dfb032ec695d3">llvm::MachO::Internal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilfinalizelinkage-cpp/#ae721973516c2b86042a5127b776e2806">Linkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a6adf97f83acf6453d4a6a4b1070f3754">llvm::MachO::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa6994917dfcfb9ef55fc6bce4b454f9a4">llvm::MachO::Rexported</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a3936e16c4ba4b109e74006ad9bdc06f8">llvm::object::BasicSymbolRef::SF_Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a204140e5ce85b4dc444bf37cb0d8e402">llvm::object::BasicSymbolRef::SF_Hidden</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa22a9825f4937b28269552f5b8db4a69">llvm::object::ObjectFile::symbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a9dffbf69ffba8bc38bc4e01abf4b1675">llvm::MachO::Text</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a4514e0ecc0bca43f5fa805abf7d7f1da">llvm::MachO::ThreadLocalValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffaec0fc0100c4fc1ce4eea230c3dc10360">llvm::MachO::Undefined</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/dylibreader/parseoption/#a09f7681b53e7be2dcee35a19f45b7b7b">llvm::MachO::DylibReader::ParseOption::Undefineds</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::MachO::GlobalRecord::Unknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::MachO::Unknown</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#ae65893a6685a0b1e5dbcdf5b0169d143a47c14840d8e15331fa420b9b2f757cd9">llvm::MachO::GlobalRecord::Variable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a97a89195303306e8a5bacadf960312a9">llvm::MachO::WeakDefined</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a7c73b1797e3f46eb2dcb9d8d2d75805b">llvm::MachO::WeakReferenced</a>.</p>


<p>Referenced by <a href="#a29e38c60d8641542f9d5e6fb9a282831">load</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
