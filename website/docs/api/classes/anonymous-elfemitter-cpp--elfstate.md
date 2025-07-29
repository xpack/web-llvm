---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-elfemitter-cpp-/elfstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFState` Class Template

<p>"Single point of truth" for the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> file construction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class ELFT&gt;
class anonymous{ELFEmitter.cpp}::ELFState&lt;ELFT&gt; { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">SymtabType { <a href="#af3016af46b49204aa736e9d501814706">...</a> }</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a15a4ab025a44612e31c490f2bb247db2">ELFState</a> (ELFYAML::Object &amp;D, yaml::ErrorHandler EH)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0dc6892ef402ec364ec2fb3a7250008">reportError</a> (const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa1c05b0c07d97c2729590dfb08823ea1">reportError</a> (Error Err)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5c0e0e8e984d5ed8dc0f74adc748156">toELFSymbols</a> (ArrayRef&lt; ELFYAML::Symbol &gt; Symbols, const StringTableBuilder &amp;Strtab) -&gt; std::vector&lt; Elf_Sym &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e0974647327df54e7007fbeb434d94b">toSectionIndex</a> (StringRef S, StringRef LocSec, StringRef LocSym="")</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab0bcd09628d3f9487caccba400449ae2">toSymbolIndex</a> (StringRef S, StringRef LocSec, bool IsDynamic)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11855c1182ec5297579a7747be487848">buildSectionIndex</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e7f635a34f26ff5b0b28914a7843175">buildSymbolIndexes</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ffd6cd5349c07d2a30aac343941106c">initProgramHeaders</a> (std::vector&lt; Elf_Phdr &gt; &amp;PHeaders)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e9684a551a26a971a58f9e8d2c5390a">initImplicitHeader</a> (ContiguousBlobAccumulator &amp;CBA, Elf_Shdr &amp;Header, StringRef SecName, ELFYAML::Section *YAMLSec)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa9e40a327fe7964f15a3d096e33330fa">initSectionHeaders</a> (std::vector&lt; Elf_Shdr &gt; &amp;SHeaders, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a083a8bbca07939277052d0b6695787dc">initSymtabSectionHeader</a> (Elf_Shdr &amp;SHeader, SymtabType STType, ContiguousBlobAccumulator &amp;CBA, ELFYAML::Section *YAMLSec)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aea49874d372c9fb2ad17d2d2fc2b7d15">initStrtabSectionHeader</a> (Elf_Shdr &amp;SHeader, StringRef Name, StringTableBuilder &amp;STB, ContiguousBlobAccumulator &amp;CBA, ELFYAML::Section *YAMLSec)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a879d015c6dc68d82112e77964694f352">initDWARFSectionHeader</a> (Elf_Shdr &amp;SHeader, StringRef Name, ContiguousBlobAccumulator &amp;CBA, ELFYAML::Section *YAMLSec)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ea9b4bd7b5c729b8e6797d15c57b191">setProgramHeaderLayout</a> (std::vector&lt; Elf_Phdr &gt; &amp;PHeaders, std::vector&lt; Elf_Shdr &gt; &amp;SHeaders)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a094c9e0d6c19e122397eea0eadd71b66">getPhdrFragments</a> (const ELFYAML::ProgramHeader &amp;Phdr, ArrayRef&lt; typename ELFT::Shdr &gt; SHeaders) -&gt; std::vector&lt; Fragment &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf724b1157e0886c8ab31d682422ca40">finalizeStrings</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a56589ca014ff5ada247a4e6b7abf82b9">writeELFHeader</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab2ad2300855c18e5a2bcce5f62d14da7">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::NoBitsSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a527543f34d44d7587bdb044ba53beb38">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::RawContentSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a323ee8a5af8f96ac245eb65fd38f6892">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::RelocationSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e40beba75f55fc90a12214b77af2647">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::RelrSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a42ecffd329f7392b2fce1052cb0d424b">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::GroupSection &amp;Group, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e384054ef45fa9da3da7c197e507560">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::SymtabShndxSection &amp;Shndx, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac024fe148ba0c357fe667884ed683d6a">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::SymverSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abde3636b7c9d1efcc8a6f0b83ce5399a">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::VerneedSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e8ce39cc0cf360ac90d0ec8b19f6985">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::VerdefSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d7d7371e12bb1622dc0f6ce59a636c7">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::ARMIndexTableSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1300c4621287b6b60b7e12e8f6d36ec0">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::MipsABIFlags &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aecd29fa2f7d0fefe510218aa9b228aac">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::DynamicSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4f158f3246cc6e56e293b5f4d4b33a2f">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::StackSizesSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a24775e372e08a9040c65e950b9999a47">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::BBAddrMapSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a07d1bc39343dfb108cee5e58055f811e">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::HashSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a116e435609dabe7f8182fe95dfb34dea">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::AddrsigSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace1ff8302e79ec244010f6e4d8bd3348">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::NoteSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad3d66bed8fcb19c9bee8eb850c26a636">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::GnuHashSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd208e34e55e2da87eaba5844b567803">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::LinkerOptionsSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add52ff5c86a17d528c83ddd567fc9b29">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::DependentLibrariesSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed781255a51630c723a8c7d831e74bbb">writeSectionContent</a> (Elf_Shdr &amp;SHeader, const ELFYAML::CallGraphProfileSection &amp;Section, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aca1367d6374ba41d753b40bd512bb658">writeFill</a> (ELFYAML::Fill &amp;Fill, ContiguousBlobAccumulator &amp;CBA)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a72b9947cb6a7293759a39441d4fa7f99">assignSectionAddress</a> (Elf_Shdr &amp;SHeader, ELFYAML::Section *YAMLSec)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a796f584e76b7ffbc50781cc3b4453da0">buildSectionHeaderReorderMap</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, size_t &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2c126e2d730807ab60a5285f9e995396">alignToOffset</a> (ContiguousBlobAccumulator &amp;CBA, uint64_t Align, std::optional&lt; llvm::yaml::Hex64 &gt; Offset)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa7ea88af3c5df4cdc924074345330666">getSectionNameOffset</a> (StringRef Name)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aedf1c292ddedecf2acdfa3bce4f30fe4">DotStrtab</a> {StringTableBuilder::ELF}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The future symbol table string section. <a href="#aedf1c292ddedecf2acdfa3bce4f30fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5b6da7c584e975898c2c8776f683a21">DotShStrtab</a> {StringTableBuilder::ELF}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The future section header string table section, if a unique string table is needed. <a href="#af5b6da7c584e975898c2c8776f683a21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04d2bbf3a5e207b50b2c13741e9d6011">DotDynstr</a> {StringTableBuilder::ELF}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The future dynamic symbol string section. <a href="#a04d2bbf3a5e207b50b2c13741e9d6011">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbb3d266c3ecc8e8a50df80f312ac489">SectionHeaderStringTableName</a> = ".shstrtab"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The name of the section header string table section. <a href="#afbb3d266c3ecc8e8a50df80f312ac489">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b4032fc2f067567cdab15260d693745">ShStrtabStrings</a> = &amp;DotShStrtab</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/nametoidxmap">NameToIdxMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad51bd0e3296a3dc68e885fdd8abb78f">SN2I</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/nametoidxmap">NameToIdxMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fdabea979bbffe1555be9ff390749ba">SymN2I</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/nametoidxmap">NameToIdxMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad68986332763df6b01a240ff38c4e124">DynSymN2I</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/elfyaml/object">ELFYAML::Object</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada7e8578a8c546f38b7a23a8ab5495fb">Doc</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a570410a739732d3665d502f6ff335fa3">ExcludedSectionHeaders</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5208d01702b8430c23e93cc0cdb7a957">LocationCounter</a> = 0</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a827c2818b3d48d44cca8f71004d57f1b">HasError</a> = false</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4f9dfab3b02d41c6e26e306c90eab66b">yaml::ErrorHandler</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a07e9139e1d82b2e56232bf2e5db619e6">ErrHandler</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4ed1ccb9ca290e598ccbacdd0c63dcf2">StringAlloc</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae52777d0974a0686586c0e6c8087e084">writeELF</a> (raw_ostream &amp;OS, ELFYAML::Object &amp;Doc, yaml::ErrorHandler EH, uint64_t MaxSize)</td>
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

<p>"Single point of truth" for the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> file construction.</p>


<p>TODO: This class still has a ways to go before it is truly a "single
point of truth".</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SymtabType {#af3016af46b49204aa736e9d501814706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{ELFEmitter.cpp}::ELFState::SymtabType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Static<a id="af3016af46b49204aa736e9d501814706a84a8921b25f505d0d2077aeb5db4bc16"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dynamic<a id="af3016af46b49204aa736e9d501814706a971fd8cc345d8bd9f92e9f7d88fdf20c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ELFState() {#a15a4ab025a44612e31c490f2bb247db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFState::ELFState (<a href="/web-llvm/docs/api/structs/llvm/elfyaml/object">ELFYAML::Object</a> &amp; D, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4f9dfab3b02d41c6e26e306c90eab66b">yaml::ErrorHandler</a> EH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### alignToOffset() {#a2c126e2d730807ab60a5285f9e995396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ELFState::alignToOffset (<a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA, uint64_t Align, std::optional&lt; llvm::yaml::Hex64 &gt; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### assignSectionAddress() {#a72b9947cb6a7293759a39441d4fa7f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::assignSectionAddress (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section">ELFYAML::Section</a> * YAMLSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### buildSectionHeaderReorderMap() {#a796f584e76b7ffbc50781cc3b4453da0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; StringRef, size_t &gt; ELFState::buildSectionHeaderReorderMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### buildSectionIndex() {#a11855c1182ec5297579a7747be487848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::buildSectionIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### buildSymbolIndexes() {#a4e7f635a34f26ff5b0b28914a7843175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::buildSymbolIndexes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### finalizeStrings() {#aaf724b1157e0886c8ab31d682422ca40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::finalizeStrings ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### getPhdrFragments() {#a094c9e0d6c19e122397eea0eadd71b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Fragment &gt; ELFState::getPhdrFragments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/programheader">ELFYAML::ProgramHeader</a> &amp; Phdr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; typename ELFT::Shdr &gt; SHeaders)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### getSectionNameOffset() {#aa7ea88af3c5df4cdc924074345330666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ELFState::getSectionNameOffset (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### initDWARFSectionHeader() {#a879d015c6dc68d82112e77964694f352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::initDWARFSectionHeader (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section">ELFYAML::Section</a> * YAMLSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### initImplicitHeader() {#a8e9684a551a26a971a58f9e8d2c5390a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFState::initImplicitHeader (<a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA, Elf_Shdr &amp; Header, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecName, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section">ELFYAML::Section</a> * YAMLSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### initProgramHeaders() {#a2ffd6cd5349c07d2a30aac343941106c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::initProgramHeaders (std::vector&lt; Elf_Phdr &gt; &amp; PHeaders)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### initSectionHeaders() {#aa9e40a327fe7964f15a3d096e33330fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::initSectionHeaders (std::vector&lt; Elf_Shdr &gt; &amp; SHeaders, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### initStrtabSectionHeader() {#aea49874d372c9fb2ad17d2d2fc2b7d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::initStrtabSectionHeader (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; STB, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section">ELFYAML::Section</a> * YAMLSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### initSymtabSectionHeader() {#a083a8bbca07939277052d0b6695787dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::initSymtabSectionHeader (Elf_Shdr &amp; SHeader, SymtabType STType, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section">ELFYAML::Section</a> * YAMLSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### reportError() {#ad0dc6892ef402ec364ec2fb3a7250008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::reportError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### reportError() {#aa1c05b0c07d97c2729590dfb08823ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::reportError (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### setProgramHeaderLayout() {#a2ea9b4bd7b5c729b8e6797d15c57b191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::setProgramHeaderLayout (std::vector&lt; Elf_Phdr &gt; &amp; PHeaders, std::vector&lt; Elf_Shdr &gt; &amp; SHeaders)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### toELFSymbols() {#af5c0e0e8e984d5ed8dc0f74adc748156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; typename ELFT::Sym &gt; ELFState::toELFSymbols (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/elfyaml/symbol">ELFYAML::Symbol</a> &gt; Symbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; Strtab)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### toSectionIndex() {#a8e0974647327df54e7007fbeb434d94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ELFState::toSectionIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LocSec, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LocSym="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### toSymbolIndex() {#ab0bcd09628d3f9487caccba400449ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ELFState::toSymbolIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LocSec, bool IsDynamic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeELFHeader() {#a56589ca014ff5ada247a4e6b7abf82b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeELFHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeFill() {#aca1367d6374ba41d753b40bd512bb658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeFill (<a href="/web-llvm/docs/api/structs/llvm/elfyaml/fill">ELFYAML::Fill</a> &amp; Fill, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#ab2ad2300855c18e5a2bcce5f62d14da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/nobitssection">ELFYAML::NoBitsSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a527543f34d44d7587bdb044ba53beb38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/rawcontentsection">ELFYAML::RawContentSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a323ee8a5af8f96ac245eb65fd38f6892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/relocationsection">ELFYAML::RelocationSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a1e40beba75f55fc90a12214b77af2647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/relrsection">ELFYAML::RelrSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a42ecffd329f7392b2fce1052cb0d424b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/groupsection">ELFYAML::GroupSection</a> &amp; Group, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a3e384054ef45fa9da3da7c197e507560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/symtabshndxsection">ELFYAML::SymtabShndxSection</a> &amp; Shndx, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#ac024fe148ba0c357fe667884ed683d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/symversection">ELFYAML::SymverSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#abde3636b7c9d1efcc8a6f0b83ce5399a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/verneedsection">ELFYAML::VerneedSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a1e8ce39cc0cf360ac90d0ec8b19f6985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/verdefsection">ELFYAML::VerdefSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a8d7d7371e12bb1622dc0f6ce59a636c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/armindextablesection">ELFYAML::ARMIndexTableSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a1300c4621287b6b60b7e12e8f6d36ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/mipsabiflags">ELFYAML::MipsABIFlags</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#aecd29fa2f7d0fefe510218aa9b228aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/dynamicsection">ELFYAML::DynamicSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a4f158f3246cc6e56e293b5f4d4b33a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/stacksizessection">ELFYAML::StackSizesSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a24775e372e08a9040c65e950b9999a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/bbaddrmapsection">ELFYAML::BBAddrMapSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a07d1bc39343dfb108cee5e58055f811e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/hashsection">ELFYAML::HashSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#a116e435609dabe7f8182fe95dfb34dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/addrsigsection">ELFYAML::AddrsigSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#ace1ff8302e79ec244010f6e4d8bd3348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/notesection">ELFYAML::NoteSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#ad3d66bed8fcb19c9bee8eb850c26a636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/gnuhashsection">ELFYAML::GnuHashSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#acd208e34e55e2da87eaba5844b567803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/linkeroptionssection">ELFYAML::LinkerOptionsSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#add52ff5c86a17d528c83ddd567fc9b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/dependentlibrariessection">ELFYAML::DependentLibrariesSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### writeSectionContent() {#aed781255a51630c723a8c7d831e74bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFState::writeSectionContent (Elf_Shdr &amp; SHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/elfyaml/callgraphprofilesection">ELFYAML::CallGraphProfileSection</a> &amp; Section, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator">ContiguousBlobAccumulator</a> &amp; CBA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Doc {#ada7e8578a8c546f38b7a23a8ab5495fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFYAML::Object&amp; anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::Doc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### DotDynstr {#a04d2bbf3a5e207b50b2c13741e9d6011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::DotDynstr {StringTableBuilder::ELF}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The future dynamic symbol string section.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### DotShStrtab {#af5b6da7c584e975898c2c8776f683a21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::DotShStrtab {StringTableBuilder::ELF}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The future section header string table section, if a unique string table is needed.</p>


<p>Don't reference this variable direectly: use the ShStrtabStrings member instead.</p>


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### DotStrtab {#aedf1c292ddedecf2acdfa3bce4f30fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::DotStrtab {StringTableBuilder::ELF}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The future symbol table string section.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### DynSymN2I {#ad68986332763df6b01a240ff38c4e124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NameToIdxMap anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::DynSymN2I</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### ErrHandler {#a07e9139e1d82b2e56232bf2e5db619e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::ErrorHandler anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::ErrHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### ExcludedSectionHeaders {#a570410a739732d3665d502f6ff335fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::ExcludedSectionHeaders</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### HasError {#a827c2818b3d48d44cca8f71004d57f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::HasError = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### LocationCounter {#a5208d01702b8430c23e93cc0cdb7a957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::LocationCounter = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### SectionHeaderStringTableName {#afbb3d266c3ecc8e8a50df80f312ac489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::SectionHeaderStringTableName = ".shstrtab"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The name of the section header string table section.</p>


<p>If it is .strtab or .dynstr, the section header strings will be written to the same string table as the static/dynamic symbols respectively. Otherwise a dedicated section will be created with that name.</p>


<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### ShStrtabStrings {#a7b4032fc2f067567cdab15260d693745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder* anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::ShStrtabStrings = &amp;DotShStrtab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### SN2I {#aad51bd0e3296a3dc68e885fdd8abb78f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NameToIdxMap anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::SN2I</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### StringAlloc {#a4ed1ccb9ca290e598ccbacdd0c63dcf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::StringAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

### SymN2I {#a6fdabea979bbffe1555be9ff390749ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NameToIdxMap anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::SymN2I</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### writeELF() {#ae52777d0974a0686586c0e6c8087e084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFState::writeELF (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/object">ELFYAML::Object</a> &amp; Doc, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4f9dfab3b02d41c6e26e306c90eab66b">yaml::ErrorHandler</a> EH, uint64_t MaxSize)</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/sectionheadertable/#ad30ac3bac2ea38004c2c67d98e9b156e">llvm::ELFYAML::SectionHeaderTable::getNumHeaders</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator/#a282601a639e3b91e1ac5e8eb02e05d28">anonymous{ELFEmitter.cpp}::ContiguousBlobAccumulator::getOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/sectionheadertable/#a95ce13cea53615cb158fad166f0830b1">llvm::ELFYAML::SectionHeaderTable::NoHeaders</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/chunk/#a9fe341ccaf982d6148f10caaddd1e6bc">llvm::ELFYAML::Chunk::Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator/#a2f23ec9452daccea6871bbf24b1dc02e">anonymous{ELFEmitter.cpp}::ContiguousBlobAccumulator::takeLimitError</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator/#a459961f2dfb5093411633fb1f37ceea1">anonymous{ELFEmitter.cpp}::ContiguousBlobAccumulator::updateDataAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp/#a241b7950718c3fe88ea2248850b7b928">writeArrayData</a> and <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator/#aad1cc77474bbb79af33bbb5a3fb9f693">anonymous{ELFEmitter.cpp}::ContiguousBlobAccumulator::writeBlobToStream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a213b80c86e78b5996e10721b4e1fa60f">llvm::yaml::yaml2elf</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp">ELFEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
