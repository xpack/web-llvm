---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MachOReader.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-h">MachOReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-h">MachOObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">llvm/Object/MachO.h</a>"
#include "llvm/Support/SystemZ/zOSSupport.h"
#include &lt;memory&gt;
#include "llvm/BinaryFormat/MachO.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SectionType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section">Section</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26d6058a804305ab52216b2628ac0b92">constructSectionCommon</a> (const SectionType &amp;Sec, uint32_t Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section">Section</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e0e81f38805c2dac1e071cf14d4147d">constructSection</a> (const MachO::section &amp;Sec, uint32_t Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section">Section</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15644a8de365f1dd1de098f846895880">constructSection</a> (const MachO::section_64 &amp;Sec, uint32_t Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SectionType, typename SegmentType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a> (const object::MachOObjectFile::LoadCommandInfo &amp;LoadCmd, const object::MachOObjectFile &amp;MachOObj, uint32_t &amp;NextSectionIndex) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section">Section</a> &gt; &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename nlist_t&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry">SymbolEntry</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc82faca788f75fcf0a8f60a406342ba">constructSymbolEntry</a> (StringRef StrTable, const nlist_t &amp;nlist)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dab6874da96415aa59776844fcc8574">HANDLE_LOAD_COMMAND</a>(LCName, LCValue, LCStruct)&nbsp;&nbsp;&nbsp;...</td>
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

## Functions

### constructSection() {#a6e0e81f38805c2dac1e071cf14d4147d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section constructSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/section">MachO::section</a> &amp; Sec, uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp">MachOReader.cpp</a>.</p>


<p>Reference <a href="#a26d6058a804305ab52216b2628ac0b92">constructSectionCommon</a>.</p>


<p>Referenced by <a href="#a3ebc7dd21b6e9c9781e5ac3e5d9b604e">extractSections</a>.</p>

</div>
</div>

### constructSection() {#a15644a8de365f1dd1de098f846895880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section constructSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/section-64">MachO::section_64</a> &amp; Sec, uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp">MachOReader.cpp</a>.</p>


<p>References <a href="#a26d6058a804305ab52216b2628ac0b92">constructSectionCommon</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a5861a070a0e074cd2a7dab3522f1e978">llvm::objcopy::macho::Section::Reserved3</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/section-64/#ae790b702e12774f2d9d2bf4a33b18768">llvm::MachO::section_64::reserved3</a>.</p>

</div>
</div>

### constructSectionCommon() {#a26d6058a804305ab52216b2628ac0b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SectionType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section constructSectionCommon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SectionType &amp; Sec, uint32_t Index)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp">MachOReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a404d02440aba5444035d0612c0391813">llvm::objcopy::macho::Section::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a375cfd7c3e62becc668296169c3c392e">llvm::objcopy::macho::Section::Align</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a02c9f1cc75393379401a84b4b05c3b3f">llvm::objcopy::macho::Section::Flags</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#ad50516919117fc7df9746ecd9073607c">llvm::objcopy::macho::Section::Index</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a27a4c1eafb2565d3cdc1c98eb69b5c0f">llvm::objcopy::macho::Section::NReloc</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a89e7c8671479f4b082147d4237ae93dc">llvm::objcopy::macho::Section::OriginalOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a8d2487d67e6a62451524e2a7bf92d13b">llvm::objcopy::macho::Section::RelOff</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#aea6d2be893f93a3c5aecbb1cafd01d82">llvm::objcopy::macho::Section::Reserved1</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#accaa34bf0be3cde79224714f3944465c">llvm::objcopy::macho::Section::Reserved2</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a5861a070a0e074cd2a7dab3522f1e978">llvm::objcopy::macho::Section::Reserved3</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#af8518cb8fda5065b350c17c993b2f187">llvm::objcopy::macho::Section::Size</a>.</p>


<p>Referenced by <a href="#a6e0e81f38805c2dac1e071cf14d4147d">constructSection</a> and <a href="#a15644a8de365f1dd1de098f846895880">constructSection</a>.</p>

</div>
</div>

### constructSymbolEntry() {#afc82faca788f75fcf0a8f60a406342ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename nlist_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolEntry constructSymbolEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StrTable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> nlist_t &amp; nlist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp">MachOReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#ad93a3bb12765133a3ec10e11d7916657">llvm::objcopy::macho::SymbolEntry::n_desc</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a74f5e6f40870c2d8f759bfaa9893e134">llvm::objcopy::macho::SymbolEntry::n_sect</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a05de774a480bbfc1c398d279bbc85965">llvm::objcopy::macho::SymbolEntry::n_type</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#aa91e6d5d585bde132f3a3af577b6d3a5">llvm::objcopy::macho::SymbolEntry::n_value</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a614b7cc8bdf811b60786c0dba3214906">llvm::objcopy::macho::SymbolEntry::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

### extractSections() {#a3ebc7dd21b6e9c9781e5ac3e5d9b604e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SectionType, typename SegmentType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; std::unique_ptr&lt; Section &gt; &gt; &gt; extractSections (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo">object::MachOObjectFile::LoadCommandInfo</a> &amp; LoadCmd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">object::MachOObjectFile</a> &amp; MachOObj, uint32_t &amp; NextSectionIndex)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp">MachOReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa91ead49defe15a5f34e4e0f4a2365d09">llvm::MachO::ARM64_RELOC_ADDEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo/#acb4cbbe0217fc2dcd16a5dce705f168d">llvm::object::MachOObjectFile::LoadCommandInfo::C</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/load-command/#ada97fe33ad823a3200c0e7fe5777bae5">llvm::MachO::load_command::cmdsize</a>, <a href="#a6e0e81f38805c2dac1e071cf14d4147d">constructSection</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a6560167012e320de6291d4d2897cb26c">llvm::objcopy::macho::Section::Content</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a33fddb0190d728c25e266a22d64bd7ad">llvm::MachO::CPU_TYPE_ARM64</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/mach-header/#ae3e0555e7bec07523f8e72515d59d838">llvm::MachO::mach_header::cputype</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a653a63105b842dd49a3a0921ce6a6d66">llvm::object::MachOObjectFile::getAnyRelocationType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a80dc9af48926f9c1b70075f71c6002a7">llvm::object::MachOObjectFile::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a7bec3ca52f60d7ca088f0634a2e8f779">llvm::object::MachOObjectFile::getPlainRelocationExternal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#aaacf649b0759051f6c5327e44b82f8aa">llvm::object::MachOObjectFile::getRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a1a18707996459de69e40ab867eeee801">llvm::object::MachOObjectFile::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a541a23560ff0dfbe01c6c1c9e4d07801">llvm::object::MachOObjectFile::getSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad07c873a9197ed022e779129f28ca028">llvm::object::MachOObjectFile::isRelocationScattered</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#a27a4c1eafb2565d3cdc1c98eb69b5c0f">llvm::objcopy::macho::Section::NReloc</a>, <a href="/web-llvm/docs/api/structs/llvm/object/machoobjectfile/loadcommandinfo/#a33838c43c0c6af81bfcb023eeab2b9c9">llvm::object::MachOObjectFile::LoadCommandInfo::Ptr</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/section/#accdafc4380bd6163e7f9f26f607d25bc">llvm::objcopy::macho::Section::Relocations</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a4db2c6874a1695b79e947621f7bad0ad">llvm::object::MachOObjectFile::section_rel_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a5b4a2cfae548a9a5cf6228605d4c0e7d">llvm::object::MachOObjectFile::section_rel_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a754466f4b36d6a2365e56663e0d9de83">llvm::MachO::swapStruct</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### HANDLE\_LOAD\_COMMAND {#a2dab6874da96415aa59776844fcc8574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_LOAD_COMMAND(LCName, LCValue, LCStruct)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case MachO::LCName:                                                          \
    memcpy((void *)&amp;(LC.MachOLoadCommand.LCStruct##_data), <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">LoadCmd.Ptr</a>,        \
           sizeof(MachO::LCStruct));                                           \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (MachOObj.isLittleEndian() != sys::IsLittleEndianHost)                  \
      MachO::swapStruct(LC.MachOLoadCommand.LCStruct##_data);                  \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (LoadCmd.C.cmdsize &gt; sizeof(MachO::LCStruct))                           \
      LC.Payload = ArrayRef&lt;uint8_t&gt;(                                          \
          reinterpret_cast&lt;uint8_t *&gt;(const_cast&lt;char *&gt;(<a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">LoadCmd.Ptr</a>)) +       \
              sizeof(MachO::LCStruct),                                         \
          LoadCmd.C.cmdsize - sizeof(MachO::LCStruct));                        \
    break;
</div>
</dd>
</dl>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp">MachOReader.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
