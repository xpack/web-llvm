---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objectyaml/elfemitter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ELFEmitter.cpp` File Reference

<p>The <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> component of yaml2obj. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">llvm/ADT/StringSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">llvm/MC/StringTableBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">llvm/Object/ELFTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfemitter-h">llvm/ObjectYAML/DWARFEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">llvm/ObjectYAML/DWARFYAML.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">llvm/ObjectYAML/ELFYAML.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/yaml2obj-h">llvm/ObjectYAML/yaml2obj.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">llvm/Support/WithColor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-elfemitter-cpp-">anonymous{ELFEmitter.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-elfemitter-cpp-/anonymous-elfemitter-cpp-">anonymous{ELFEmitter.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/yaml">yaml</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/nametoidxmap">NameToIdxMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-elfemitter-cpp-/anonymous-elfemitter-cpp-/fragment">Fragment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/elfstate">ELFState&lt;ELFT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"Single point of truth" for the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> file construction. <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/elfstate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75a18d9ff9b3f58ba08445f3189bb4cc">arrayDataSize</a> (ArrayRef&lt; T &gt; A)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a241b7950718c3fe88ea2248850b7b928">writeArrayData</a> (raw_ostream &amp;OS, ArrayRef&lt; T &gt; A)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa15f84f0499130c4cec8c17e7f7376ce">zero</a> (T &amp;Obj)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1684e6ee559b03b5e8ed8b1c0ebcaf8b">overrideFields</a> (ELFYAML::Section *From, typename ELFT::Shdr &amp;To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb98ca088637f91ee8a088d0066c29d5">writeContent</a> (ContiguousBlobAccumulator &amp;CBA, const std::optional&lt; yaml::BinaryRef &gt; &amp;Content, const std::optional&lt; llvm::yaml::Hex64 &gt; &amp;Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a073ff687330020a1f28e8e5f4e762e56">getDefaultLinkSec</a> (unsigned SecType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af89b37ec511b5a775018e866a6ba89dd">findFirstNonGlobal</a> (ArrayRef&lt; ELFYAML::Symbol &gt; Symbols)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab26e08b9fdcb1680fe057c2fac9d09c1">shouldEmitDWARF</a> (DWARFYAML::Data &amp;DWARF, StringRef Name)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aecbaa749a0f6fef87a9b62c6be065c2d">emitDWARF</a> (typename ELFT::Shdr &amp;SHeader, StringRef Name, const DWARFYAML::Data &amp;DWARF, ContiguousBlobAccumulator &amp;CBA) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69558ca9802bcb2fcbbd69e73baedc5d">isMips64EL</a> (const ELFYAML::Object &amp;Obj)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8da6ba33ef60fa9bf423a8181807ff3b">SuffixStart</a> = '('</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa22faf4ed48ffe86c92bcafa5d8d49">SuffixEnd</a> = ')'</td>
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

## Description {#details}

<p>The <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> component of yaml2obj.</p>

<div class="doxySectionDef">

## Functions

### arrayDataSize() {#a75a18d9ff9b3f58ba08445f3189bb4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t arrayDataSize (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; A)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a241b7950718c3fe88ea2248850b7b928">writeArrayData</a>.</p>

</div>
</div>

### emitDWARF() {#aecbaa749a0f6fef87a9b62c6be065c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; emitDWARF (typename ELFT::Shdr &amp; SHeader, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data">DWARFYAML::Data</a> &amp; DWARF, ContiguousBlobAccumulator &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9bde8a0a70fe79e96ac7232738deabff">llvm::DWARFYAML::getDWARFEmitterByName</a>.</p>

</div>
</div>

### findFirstNonGlobal() {#af89b37ec511b5a775018e866a6ba89dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t findFirstNonGlobal (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/elfyaml/symbol">ELFYAML::Symbol</a> &gt; Symbols)</td>
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



<p>Definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>.</p>

</div>
</div>

### getDefaultLinkSec() {#a073ff687330020a1f28e8e5f4e762e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getDefaultLinkSec (unsigned SecType)</td>
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



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcadb5044a1bd05d2a84193fb0eb9b9df12">llvm::ELF::SHT_DYNSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcac2c78c65695652b4455792ce6266592e">llvm::ELF::SHT_GNU_HASH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca7f79ace8b8c08efee9e59f22611a756b">llvm::ELF::SHT_GNU_verdef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca5b0b7716581822df1746031fd693badd">llvm::ELF::SHT_GNU_verneed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcaea24f2f22c3a68c4f9b8c97672bdc4a3">llvm::ELF::SHT_GNU_versym</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1771b2365460420ea3aee1fa4c324c99">llvm::ELF::SHT_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcaeca3b227f9d5502c4fa845113e73b7e9">llvm::ELF::SHT_HASH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca9d2a9add5afe20c3d863e720a8864898">llvm::ELF::SHT_LLVM_ADDRSIG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca3b34c61cc0e95c91405e13c12da52925">llvm::ELF::SHT_LLVM_CALL_GRAPH_PROFILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca4f0cd819b71791cb5a1945952dbc9166">llvm::ELF::SHT_SYMTAB</a>.</p>

</div>
</div>

### isMips64EL() {#a69558ca9802bcb2fcbbd69e73baedc5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isMips64EL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/object">ELFYAML::Object</a> &amp; Obj)</td>
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



<p>Definition at line 1260 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/elfyaml/fileheader/#a4129f5ae59881eb1a672badc3a934cb3">llvm::ELFYAML::FileHeader::Class</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/fileheader/#a3f9051459825607c9a1325560f21f75b">llvm::ELFYAML::FileHeader::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5a54b4da97cdda07031363b240c26c9794">llvm::ELF::ELFCLASS64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a868a39064cf90c55a5a8b267d8018c2bafedc8af0121f7104ef49a576b30865de">llvm::ELF::ELFDATA2LSB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daaf29cd80fceba94e4f48b143fcf354c6">llvm::ELF::EM_MIPS</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/object/#a24c63d8b289a61f9ebdb6eb7044b941b">llvm::ELFYAML::Object::getMachine</a> and <a href="/web-llvm/docs/api/structs/llvm/elfyaml/object/#a4d50f276f5d3fba9c7c67cfe709bb0d0">llvm::ELFYAML::Object::Header</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a815105a2af24d7dffc158173b5324272">llvm::object::ELFFile&lt; ELFT &gt;::getRelocationSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl-441322f49503dee2ae87a34528a5e21a/#adf248d06b3dfd783b3891502983beeef">llvm::object::Elf_Rel_Impl&lt; ELFType&lt; Endianness, false &gt;, false &gt;::getRInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl-9e9bb875b5b3f76ac1dc313ded5403d0/#af4960d319f38fd616421253153883bd3">llvm::object::Elf_Rel_Impl&lt; ELFType&lt; Endianness, true &gt;, false &gt;::getRInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl-441322f49503dee2ae87a34528a5e21a/#a498236b9e871eb3e6186f629ec0e78a1">llvm::object::Elf_Rel_Impl&lt; ELFType&lt; Endianness, false &gt;, false &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl-9e9bb875b5b3f76ac1dc313ded5403d0/#aaaa3d7bcf7f2bb9f1cc94c6c953c9139">llvm::object::Elf_Rel_Impl&lt; ELFType&lt; Endianness, true &gt;, false &gt;::getSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl-441322f49503dee2ae87a34528a5e21a/#a1d67d57ea7aa53bea0476b71d0943264">llvm::object::Elf_Rel_Impl&lt; ELFType&lt; Endianness, false &gt;, false &gt;::getType</a> and <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl-9e9bb875b5b3f76ac1dc313ded5403d0/#addaec1001eac4ac9d7e3712aa46d9c07">llvm::object::Elf_Rel_Impl&lt; ELFType&lt; Endianness, true &gt;, false &gt;::getType</a>.</p>

</div>
</div>

### overrideFields() {#a1684e6ee559b03b5e8ed8b1c0ebcaf8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void overrideFields (<a href="/web-llvm/docs/api/structs/llvm/elfyaml/section">ELFYAML::Section</a> * From, typename ELFT::Shdr &amp; To)</td>
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



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#a56a3276132bd9066303a211c43099832">llvm::ELFYAML::Section::ShAddrAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#a97bd324cffdeb0edb5f3ad5dc3b1b2fd">llvm::ELFYAML::Section::ShFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#ace01a4b3f4bf401d48d2803dc3d2dbe9">llvm::ELFYAML::Section::ShName</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#a84eb0eea2c6b3a7d7ac2b9dad144e30e">llvm::ELFYAML::Section::ShOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#aea2b587e90665bd15efed99bdf677aee">llvm::ELFYAML::Section::ShSize</a> and <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#a81553c73c55878900fbbff6809b38000">llvm::ELFYAML::Section::ShType</a>.</p>

</div>
</div>

### shouldEmitDWARF() {#ab26e08b9fdcb1680fe057c2fac9d09c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldEmitDWARF (<a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data">DWARFYAML::Data</a> &amp; DWARF, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data/#a887ba011291edccdab6965f72b24578e">llvm::DWARFYAML::Data::getNonEmptySectionNames</a>.</p>

</div>
</div>

### writeArrayData() {#a241b7950718c3fe88ea2248850b7b928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeArrayData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; A)</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a75a18d9ff9b3f58ba08445f3189bb4cc">arrayDataSize</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/elfstate/#ae52777d0974a0686586c0e6c8087e084">anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::writeELF</a>.</p>

</div>
</div>

### writeContent() {#adb98ca088637f91ee8a088d0066c29d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t writeContent (ContiguousBlobAccumulator &amp; CBA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref">yaml::BinaryRef</a> &gt; &amp; Content, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; llvm::yaml::Hex64 &gt; &amp; Size)</td>
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



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### zero() {#aa15f84f0499130c4cec8c17e7f7376ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void zero (T &amp; Obj)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### SuffixEnd {#a0fa22faf4ed48ffe86c92bcafa5d8d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char SuffixEnd = ')'</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/elfyaml/#a082bb27a910a4bd0b379e3f31844678f">llvm::ELFYAML::appendUniqueSuffix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfyaml/#ac84f1cd7e37d227e700d6a69398fd3c1">llvm::ELFYAML::dropUniqueSuffix</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#ad81a87b3f8bbc548c08e343f068aab79">parseRD</a>.</p>

</div>
</div>

### SuffixStart {#a8da6ba33ef60fa9bf423a8181807ff3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char SuffixStart = '('</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/elfyaml/#a082bb27a910a4bd0b379e3f31844678f">llvm::ELFYAML::appendUniqueSuffix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elfyaml/#ac84f1cd7e37d227e700d6a69398fd3c1">llvm::ELFYAML::dropUniqueSuffix</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
