---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/elf-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ELF.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elf-h">llvm/Object/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
#include "llvm/BinaryFormat/ELFRelocs/M68k.def"
#include "llvm/BinaryFormat/ELFRelocs/x86_64.def"
#include "llvm/BinaryFormat/ELFRelocs/i386.def"
#include "llvm/BinaryFormat/ELFRelocs/Mips.def"
#include "llvm/BinaryFormat/ELFRelocs/AArch64.def"
#include "llvm/BinaryFormat/ELFRelocs/ARM.def"
#include "llvm/BinaryFormat/ELFRelocs/ARC.def"
#include "llvm/BinaryFormat/ELFRelocs/AVR.def"
#include "llvm/BinaryFormat/ELFRelocs/Hexagon.def"
#include "llvm/BinaryFormat/ELFRelocs/Lanai.def"
#include "llvm/BinaryFormat/ELFRelocs/PowerPC.def"
#include "llvm/BinaryFormat/ELFRelocs/PowerPC64.def"
#include "llvm/BinaryFormat/ELFRelocs/RISCV.def"
#include "llvm/BinaryFormat/ELFRelocs/SystemZ.def"
#include "llvm/BinaryFormat/ELFRelocs/Sparc.def"
#include "llvm/BinaryFormat/ELFRelocs/AMDGPU.def"
#include "llvm/BinaryFormat/ELFRelocs/BPF.def"
#include "llvm/BinaryFormat/ELFRelocs/MSP430.def"
#include "llvm/BinaryFormat/ELFRelocs/VE.def"
#include "llvm/BinaryFormat/ELFRelocs/CSKY.def"
#include "llvm/BinaryFormat/ELFRelocs/LoongArch.def"
#include "llvm/BinaryFormat/ELFRelocs/Xtensa.def"
#include "llvm/BinaryFormat/DynamicTags.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static IntTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a817b6babbfd3e8ca145b869d93903f26">readULEB128As</a> (DataExtractor &amp;Data, DataExtractor::Cursor &amp;Cur, Error &amp;ULEBSizeErr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a> (const ELFFile&lt; ELFT &gt; &amp;EF, const typename ELFFile&lt; ELFT &gt;::Elf_Shdr &amp;Sec, const typename ELFFile&lt; ELFT &gt;::Elf_Shdr *RelaSec, std::vector&lt; PGOAnalysisMap &gt; *PGOAnalyses) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap">BBAddrMap</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab9fcd44b7b7a82fc9f30cae13adb8c">STRINGIFY_ENUM_CASE</a>(ns, name)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d37a8bc050b0c8cfc77bc4a89cd7ccd">ELF_RELOC</a>(name, value)&nbsp;&nbsp;&nbsp;<a href="#aaab9fcd44b7b7a82fc9f30cae13adb8c">STRINGIFY_ENUM_CASE</a>(ELF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(tag, value)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ec9caf0e98ad31eecc4708491d47f7">DYNAMIC_TAG</a>(n, v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae99c4380d0c079e2f454ddd2070292bc">AARCH64_DYNAMIC_TAG</a>(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa870e8200abcdab3b14e1de7281bfda4">HEXAGON_DYNAMIC_TAG</a>(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2fbf326289b07b73e3e5b2047895cf4">MIPS_DYNAMIC_TAG</a>(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30191f9a3670527e7fef6c7454221da1">PPC_DYNAMIC_TAG</a>(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd16aee48654f44dd2048897375604c">PPC64_DYNAMIC_TAG</a>(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4efcc0610e0df91a1779e6ff4cf98e45">RISCV_DYNAMIC_TAG</a>(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06508f52323d60af285f20f69354ec1d">AARCH64_DYNAMIC_TAG</a>(name, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed11a1e3ffb38335bb9065a1c7e699a">MIPS_DYNAMIC_TAG</a>(name, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a301ddcc88b4b3dbbfb0ab9f1741a96">HEXAGON_DYNAMIC_TAG</a>(name, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f34674f44430b770e4eaabb39fcb611">PPC_DYNAMIC_TAG</a>(name, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d3ad93888ad087d2352c15a91c680aa">PPC64_DYNAMIC_TAG</a>(name, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad109433c09169c2459e3525f388a462">RISCV_DYNAMIC_TAG</a>(name, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a471e66c9dd501f3daacbb526619a7b08">DYNAMIC_TAG_MARKER</a>(name, value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e46f460d9a3c9712a34d307b41a947">DYNAMIC_TAG</a>(name, value)&nbsp;&nbsp;&nbsp;case value: return #<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>;</td>
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

### decodeBBAddrMapImpl() {#ab230da2e143b2070f404fea9287e4ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; BBAddrMap &gt; &gt; decodeBBAddrMapImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a>&lt; ELFT &gt; &amp; EF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a>&lt; ELFT &gt;::Elf_Shdr &amp; Sec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename <a href="/web-llvm/docs/api/classes/llvm/object/elffile">ELFFile</a>&lt; ELFT &gt;::Elf_Shdr * RelaSec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/pgoanalysismap">PGOAnalysisMap</a> &gt; * PGOAnalyses)</td>
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



<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features/#a24efbea1211f48f81b01b2605459f264">llvm::object::BBAddrMap::Features::BBFreq</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features/#a650eb6981dfff7bc28bc72a8bf98596f">llvm::object::BBAddrMap::Features::BrProb</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9541bbf765f7db0b078a45d6f43c34b4adedd58c8e99e1d189b1480d7bee0cdbf">BrProb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/bbentry/metadata/#a0dc9fe3702b89ddd88d84587a59a7034">llvm::object::BBAddrMap::BBEntry::Metadata::decode</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features/#ada5237f92a42dcf07815d67e912fb9c9">llvm::object::BBAddrMap::Features::decode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a47b5436c5611f6605c7ea813253dac5a">llvm::object::describe</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aadbc5ef54c920f724d4e267f41d2c00aaba0cdd056685bc8fe4fab01da806afdc">llvm::ELF::ET_REL</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features/#abcce893abd5c350d05392295509ad360">llvm::object::BBAddrMap::Features::FuncEntryCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9541bbf765f7db0b078a45d6f43c34b4aa3669b238d31e98764ca5132de1f5a15">FuncEntryCount</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a02cea47a954fd499a8dc8d80b75935ee">llvm::object::ELFFile&lt; ELFT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a286629cb3167717b736d06f88c8f4817">llvm::BranchProbability::getRaw</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a5fd489ea4559343125c546221251b743">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContents</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features/#aef7bccc1db668aa9abb930f178a18b72">llvm::object::BBAddrMap::Features::hasPGOAnalysis</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features/#abaeb4229fc1216616fe0908396f99162">llvm::object::BBAddrMap::Features::hasPGOAnalysisBBData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ac9e50507b6d18dc2f18508ff067e140e">llvm::object::ELFFile&lt; ELFT &gt;::isLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features/#a4fe191b46a8e47bba3f14b26f6167f28">llvm::object::BBAddrMap::Features::MultiBBRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features/#a64366ab8032082e6fa7133e94a294013">llvm::object::BBAddrMap::Features::OmitBBEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a817b6babbfd3e8ca145b869d93903f26">readULEB128As</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a63434f54fe78bfe55d1c3de263359e6f">llvm::object::ELFFile&lt; ELFT &gt;::relas</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcabf9a9b472d62e43e5e49fc2f468abcce">llvm::ELF::SHT_LLVM_BB_ADDR_MAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a3453d69f4b4b74c0cf69808bc7d1c8b0">llvm::DataExtractor::Cursor::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a22c134bb6de5493faf9c7076ef4dfcac">llvm::DataExtractor::Cursor::tell</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a46e1bbe3fd829b216165917625cb142d">llvm::object::ELFFile&lt; ELFT &gt;::decodeBBAddrMap</a>.</p>

</div>
</div>

### readULEB128As() {#a817b6babbfd3e8ca145b869d93903f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IntTy, std::enable_if_t&lt; std::is_unsigned_v&lt; IntTy &gt;, int &gt; = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntTy readULEB128As (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">DataExtractor::Cursor</a> &amp; Cur, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; ULEBSizeErr)</td>
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



<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a22c134bb6de5493faf9c7076ef4dfcac">llvm::DataExtractor::Cursor::tell</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### AARCH64\_DYNAMIC\_TAG {#ae99c4380d0c079e2f454ddd2070292bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AARCH64_DYNAMIC_TAG(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### AARCH64\_DYNAMIC\_TAG {#a06508f52323d60af285f20f69354ec1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AARCH64_DYNAMIC_TAG(name, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### DYNAMIC\_STRINGIFY\_ENUM {#afc0ebfd42c190c21671637933ffadf88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DYNAMIC_STRINGIFY_ENUM(tag, value)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case value:                                                                  \
    return #tag;
</div>
</dd>
</dl>

<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### DYNAMIC\_TAG {#ad6ec9caf0e98ad31eecc4708491d47f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DYNAMIC_TAG(n, v)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### DYNAMIC\_TAG {#a80e46f460d9a3c9712a34d307b41a947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DYNAMIC_TAG(name, value)&nbsp;&nbsp;&nbsp;case value: return #<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### DYNAMIC\_TAG\_MARKER {#a471e66c9dd501f3daacbb526619a7b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DYNAMIC_TAG_MARKER(name, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### ELF\_RELOC {#a6d37a8bc050b0c8cfc77bc4a89cd7ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ELF_RELOC(name, value)&nbsp;&nbsp;&nbsp;<a href="#aaab9fcd44b7b7a82fc9f30cae13adb8c">STRINGIFY_ENUM_CASE</a>(ELF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### HEXAGON\_DYNAMIC\_TAG {#aa870e8200abcdab3b14e1de7281bfda4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_DYNAMIC_TAG(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### HEXAGON\_DYNAMIC\_TAG {#a8a301ddcc88b4b3dbbfb0ab9f1741a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEXAGON_DYNAMIC_TAG(name, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### MIPS\_DYNAMIC\_TAG {#af2fbf326289b07b73e3e5b2047895cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MIPS_DYNAMIC_TAG(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### MIPS\_DYNAMIC\_TAG {#a2ed11a1e3ffb38335bb9065a1c7e699a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MIPS_DYNAMIC_TAG(name, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### PPC\_DYNAMIC\_TAG {#a30191f9a3670527e7fef6c7454221da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PPC_DYNAMIC_TAG(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### PPC\_DYNAMIC\_TAG {#a9f34674f44430b770e4eaabb39fcb611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PPC_DYNAMIC_TAG(name, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### PPC64\_DYNAMIC\_TAG {#a6dd16aee48654f44dd2048897375604c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PPC64_DYNAMIC_TAG(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### PPC64\_DYNAMIC\_TAG {#a0d3ad93888ad087d2352c15a91c680aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PPC64_DYNAMIC_TAG(name, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### RISCV\_DYNAMIC\_TAG {#a4efcc0610e0df91a1779e6ff4cf98e45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RISCV_DYNAMIC_TAG(name, value)&nbsp;&nbsp;&nbsp;<a href="#afc0ebfd42c190c21671637933ffadf88">DYNAMIC_STRINGIFY_ENUM</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### RISCV\_DYNAMIC\_TAG {#aad109433c09169c2459e3525f388a462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RISCV_DYNAMIC_TAG(name, value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

### STRINGIFY\_ENUM\_CASE {#aaab9fcd44b7b7a82fc9f30cae13adb8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STRINGIFY_ENUM_CASE(ns, name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case ns::name:                                                               \
    return #<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>;
</div>
</dd>
</dl>

<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp">ELF.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
