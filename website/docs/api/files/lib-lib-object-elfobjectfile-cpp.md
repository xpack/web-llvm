---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/elfobjectfile-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ELFObjectFile.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">llvm/Object/ELFObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstranalysis-h">llvm/MC/MCInstrAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">llvm/Object/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">llvm/Object/ELFTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/error-h">llvm/Object/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">llvm/Support/ARMAttributeParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armbuildattributes-h">llvm/Support/ARMBuildAttributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributeparser-h">llvm/Support/HexagonAttributeParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributeparser-h">llvm/Support/RISCVAttributeParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvattributes-h">llvm/Support/RISCVAttributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">llvm/TargetParser/RISCVISAInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;algorithm&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;utility&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a595f1eb44be7dd8b0cad008384c9d721">createPtr</a> (MemoryBufferRef Object, bool InitContent) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile">ELFObjectFile</a>&lt; ELFT &gt; &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb66cabcc15247db4ebb87aafe4828dc">hexagonAttrToFeatureString</a> (unsigned Attr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6264f8eee9db96846bfe5119e1ceb4ab">readBBAddrMapImpl</a> (const ELFFile&lt; ELFT &gt; &amp;EF, std::optional&lt; unsigned &gt; TextSectionIndex, std::vector&lt; PGOAnalysisMap &gt; *PGOAnalyses) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap">BBAddrMap</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbf1738ff099ad1ac3079a05ae07ea35">readDynsymVersionsImpl</a> (const ELFFile&lt; ELFT &gt; &amp;EF, ELFObjectFileBase::elf_symbol_iterator_range Symbols) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/versionentry">VersionEntry</a> &gt; &gt;</td>
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

### createPtr() {#a595f1eb44be7dd8b0cad008384c9d721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ELFObjectFile&lt; ELFT &gt; &gt; &gt; createPtr (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, bool InitContent)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp">ELFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfile/#a65d9c3a1e8cb5fe3e06486957ea45fbb">llvm::object::ELFObjectFile&lt; ELFT &gt;::create</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a5ef8ed10341ed52e784b5408bac56424">llvm::object::ObjectFile::createELFObjectFile</a>.</p>

</div>
</div>

### hexagonAttrToFeatureString() {#adb66cabcc15247db4ebb87aafe4828dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; hexagonAttrToFeatureString (unsigned Attr)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp">ELFObjectFile.cpp</a>.</p>

</div>
</div>

### readBBAddrMapImpl() {#a6264f8eee9db96846bfe5119e1ceb4ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; BBAddrMap &gt; &gt; readBBAddrMapImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a>&lt; ELFT &gt; &amp; EF, std::optional&lt; unsigned &gt; TextSectionIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/pgoanalysismap">PGOAnalysisMap</a> &gt; * PGOAnalyses)</td>
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



<p>Definition at line 888 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp">ELFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a46e1bbe3fd829b216165917625cb142d">llvm::object::ELFFile&lt; ELFT &gt;::decodeBBAddrMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a47b5436c5611f6605c7ea813253dac5a">llvm::object::describe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aadbc5ef54c920f724d4e267f41d2c00aaba0cdd056685bc8fe4fab01da806afdc">llvm::ELF::ET_REL</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#af1e96fd6674f65a3dcc5c4f46a4112b6">llvm::object::ELFFile&lt; ELFT &gt;::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ac224640f48ef4ce451d49bbb1b68e9ca">llvm::object::ELFFile&lt; ELFT &gt;::getSectionAndRelocations</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ab64e03f049c8588f24e0ec69a568aef9">llvm::object::ELFFile&lt; ELFT &gt;::sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcabf9a9b472d62e43e5e49fc2f468abcce">llvm::ELF::SHT_LLVM_BB_ADDR_MAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca03c8a4c3f50ee83d855950bfa639eab4">llvm::ELF::SHT_LLVM_BB_ADDR_MAP_V0</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#afd20ce2ce3ff93c0b9e858b5bda86c85">llvm::object::ELFObjectFileBase::readBBAddrMap</a>.</p>

</div>
</div>

### readDynsymVersionsImpl() {#afbf1738ff099ad1ac3079a05ae07ea35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; VersionEntry &gt; &gt; readDynsymVersionsImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a>&lt; ELFT &gt; &amp; EF, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#acfa80c2a44dbec7ba7718d1be22fc9e3">ELFObjectFileBase::elf_symbol_iterator_range</a> Symbols)</td>
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



<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elfobjectfile-cpp">ELFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a47b5436c5611f6605c7ea813253dac5a">llvm::object::describe</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a56343d577008471112adcb121718f1b2">llvm::object::ELFFile&lt; ELFT &gt;::getSymbolVersionByIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aeb221ffeffa3ec7eaaa8eecf37b0146d">llvm::object::ELFFile&lt; ELFT &gt;::loadVersionMap</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ab64e03f049c8588f24e0ec69a568aef9">llvm::object::ELFFile&lt; ELFT &gt;::sections</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca7f79ace8b8c08efee9e59f22611a756b">llvm::ELF::SHT_GNU_verdef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca5b0b7716581822df1746031fd693badd">llvm::ELF::SHT_GNU_verneed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcaea24f2f22c3a68c4f9b8c97672bdc4a3">llvm::ELF::SHT_GNU_versym</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a7f69f112f4da4570c812a9a4c2de3aa1">llvm::object::ELFObjectFileBase::readDynsymVersions</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
