---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/anonymous-elfyaml-cpp-/normalizedother
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NormalizedOther` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78f50f86593e46ab248cdc48e3b1e95">NormalizedOther</a> (IO &amp;IO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2713b0aecf2732a7d6ffb601b9c51ba">NormalizedOther</a> (IO &amp;IO, std::optional&lt; uint8_t &gt; Original)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bd8dea70f65afd2d7e5f4fc90b2d99">toValue</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819d4923618533869325f9cda1087fca">denormalize</a> (IO &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7563421760d17889591028c0c53e79f6">getFlags</a> (unsigned EMachine)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43cf0b87d97e2b1ffd8f74b8a25cc999">YamlIO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::vector&lt; StOtherPiece &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67803ce33c7c1dc4af12776b16cc458c">Other</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa23826e254de05452848c5c2d6824b9">UnknownFlagsHolder</a></td>
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


<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NormalizedOther() {#ad78f50f86593e46ab248cdc48e3b1e95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::NormalizedOther (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1226 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<p>Reference <a href="#a43cf0b87d97e2b1ffd8f74b8a25cc999">YamlIO</a>.</p>

</div>
</div>

### NormalizedOther() {#ac2713b0aecf2732a7d6ffb601b9c51ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::NormalizedOther (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, std::optional&lt; uint8_t &gt; Original)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1227 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a7a3ba7cd94762ae7f243367830320ca2">getFlags</a>, <a href="#a67803ce33c7c1dc4af12776b16cc458c">Other</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#aaa23826e254de05452848c5c2d6824b9">UnknownFlagsHolder</a> and <a href="#a43cf0b87d97e2b1ffd8f74b8a25cc999">YamlIO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### denormalize() {#a819d4923618533869325f9cda1087fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint8_t &gt; llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::denormalize (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1267 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<p>References <a href="#a67803ce33c7c1dc4af12776b16cc458c">Other</a> and <a href="#af3bd8dea70f65afd2d7e5f4fc90b2d99">toValue</a>.</p>

</div>
</div>

### getFlags() {#a7563421760d17889591028c0c53e79f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt; StringRef, uint8_t &gt; llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::getFlags (unsigned EMachine)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1279 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dace9c7753eed878839a8fb04768d1436c">llvm::ELF::EM_AARCH64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daaf29cd80fceba94e4f48b143fcf354c6">llvm::ELF::EM_MIPS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030dad426ff446687588ec3a40dee3f6b3598">llvm::ELF::EM_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a388c981224806a01d8de4172d5322d3da46f3ea056caa3126b91f3f70beea068c">llvm::yaml::Map</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a47fe0c0beacf5f9bea73537794c38905a3b2d4e047e328943e0773957ce7ebd0c">llvm::ELF::STO_AARCH64_VARIANT_PCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a29b00051aee706fc5bbc604742a66f55a920f3ac6d4e61d6e58a5377436c31587">llvm::ELF::STO_MIPS_MICROMIPS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a29b00051aee706fc5bbc604742a66f55aaf9327f798d1a2ebf7f89f2485f1ca17">llvm::ELF::STO_MIPS_MIPS16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a29b00051aee706fc5bbc604742a66f55a85dd51420413d244b4fb7c4c66b19e95">llvm::ELF::STO_MIPS_OPTIONAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a29b00051aee706fc5bbc604742a66f55a7ad41e365dbab386b84e7400fcd6e2e7">llvm::ELF::STO_MIPS_PIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a29b00051aee706fc5bbc604742a66f55ae2e157e162036a50f6b4790e8f86cb0d">llvm::ELF::STO_MIPS_PLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac5a4ed49dd3f7e20277324fc912f5726acabf5d88bf0c9a9fb2fdbebd5ecc99c9">llvm::ELF::STO_RISCV_VARIANT_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5af3e7284f94dabe52ad31412ab70c15f4">llvm::ELF::STV_DEFAULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5ab38517de2fd6c124c49e40bc25c25c0c">llvm::ELF::STV_HIDDEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5a443262fcc164a05e17cef6868ab529d3">llvm::ELF::STV_INTERNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5aec3ecfdbfbbe90889a70c56df29b263a">llvm::ELF::STV_PROTECTED</a> and <a href="#a43cf0b87d97e2b1ffd8f74b8a25cc999">YamlIO</a>.</p>

</div>
</div>

### toValue() {#af3bd8dea70f65afd2d7e5f4fc90b2d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::toValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1250 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a7a3ba7cd94762ae7f243367830320ca2">getFlags</a> and <a href="#a43cf0b87d97e2b1ffd8f74b8a25cc999">YamlIO</a>.</p>


<p>Referenced by <a href="#a819d4923618533869325f9cda1087fca">denormalize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Other {#a67803ce33c7c1dc4af12776b16cc458c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::vector&lt;StOtherPiece&gt; &gt; llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::Other</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<p>Referenced by <a href="#a819d4923618533869325f9cda1087fca">denormalize</a> and <a href="#ac2713b0aecf2732a7d6ffb601b9c51ba">NormalizedOther</a>.</p>

</div>
</div>

### UnknownFlagsHolder {#aaa23826e254de05452848c5c2d6824b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::UnknownFlagsHolder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<p>Referenced by <a href="#ac2713b0aecf2732a7d6ffb601b9c51ba">NormalizedOther</a>.</p>

</div>
</div>

### YamlIO {#a43cf0b87d97e2b1ffd8f74b8a25cc999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IO&amp; llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::YamlIO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1314 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<p>Referenced by <a href="#a7563421760d17889591028c0c53e79f6">getFlags</a>, <a href="#ad78f50f86593e46ab248cdc48e3b1e95">NormalizedOther</a>, <a href="#ac2713b0aecf2732a7d6ffb601b9c51ba">NormalizedOther</a> and <a href="#af3bd8dea70f65afd2d7e5f4fc90b2d99">toValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
