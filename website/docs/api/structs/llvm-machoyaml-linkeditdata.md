---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machoyaml/linkeditdata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LinkEditData` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::MachOYAML::LinkEditData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">llvm/ObjectYAML/MachOYAML.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machoyaml/rebaseopcode">MachOYAML::RebaseOpcode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadab92b5ce3df4b0f366cd1ef5b091ae">RebaseOpcodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machoyaml/bindopcode">MachOYAML::BindOpcode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91e65585a009f3b3f93335bf6cee5e32">BindOpcodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machoyaml/bindopcode">MachOYAML::BindOpcode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09222d71153a9de2d30d507dca561fa5">WeakBindOpcodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machoyaml/bindopcode">MachOYAML::BindOpcode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a353bb0901c850effe97f12eb4e204e3a">LazyBindOpcodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machoyaml/exportentry">MachOYAML::ExportEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa28eedb4180cba48de2d7cf90a4b2fa">ExportTrie</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machoyaml/nlistentry">NListEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2829df52c5477e49cc7d62fb74fde5">NameList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad104df941ead6634db84cd8aa986be61">StringTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; yaml::Hex32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad22a4e43ccb25c771c96219fab847934">IndirectSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb6b4badb4c56c2d797486939be4654f">FunctionStarts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machoyaml/dataincodeentry">DataInCodeEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f889810ae3728f7e05a5d8d600807bd">DataInCode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; yaml::Hex8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a276546f32b96326d2ba332f6a6ae3065">ChainedFixups</a></td>
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


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### isEmpty() {#adb23ca348f8901b1a2e53cf9b25dcf3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachOYAML::LinkEditData::isEmpty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoyaml-cpp">MachOYAML.cpp</a>.</p>


<p>References <a href="#a91e65585a009f3b3f93335bf6cee5e32">BindOpcodes</a>, <a href="#a276546f32b96326d2ba332f6a6ae3065">ChainedFixups</a>, <a href="#a0f889810ae3728f7e05a5d8d600807bd">DataInCode</a>, <a href="#afa28eedb4180cba48de2d7cf90a4b2fa">ExportTrie</a>, <a href="#adb6b4badb4c56c2d797486939be4654f">FunctionStarts</a>, <a href="#a353bb0901c850effe97f12eb4e204e3a">LazyBindOpcodes</a>, <a href="#afd2829df52c5477e49cc7d62fb74fde5">NameList</a>, <a href="#aadab92b5ce3df4b0f366cd1ef5b091ae">RebaseOpcodes</a>, <a href="#ad104df941ead6634db84cd8aa986be61">StringTable</a> and <a href="#a09222d71153a9de2d30d507dca561fa5">WeakBindOpcodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BindOpcodes {#a91e65585a009f3b3f93335bf6cee5e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachOYAML::BindOpcode&gt; llvm::MachOYAML::LinkEditData::BindOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### ChainedFixups {#a276546f32b96326d2ba332f6a6ae3065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;yaml::Hex8&gt; llvm::MachOYAML::LinkEditData::ChainedFixups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### DataInCode {#a0f889810ae3728f7e05a5d8d600807bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DataInCodeEntry&gt; llvm::MachOYAML::LinkEditData::DataInCode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### ExportTrie {#afa28eedb4180cba48de2d7cf90a4b2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOYAML::ExportEntry llvm::MachOYAML::LinkEditData::ExportTrie</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### FunctionStarts {#adb6b4badb4c56c2d797486939be4654f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;yaml::Hex64&gt; llvm::MachOYAML::LinkEditData::FunctionStarts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### IndirectSymbols {#ad22a4e43ccb25c771c96219fab847934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;yaml::Hex32&gt; llvm::MachOYAML::LinkEditData::IndirectSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### LazyBindOpcodes {#a353bb0901c850effe97f12eb4e204e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachOYAML::BindOpcode&gt; llvm::MachOYAML::LinkEditData::LazyBindOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### NameList {#afd2829df52c5477e49cc7d62fb74fde5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;NListEntry&gt; llvm::MachOYAML::LinkEditData::NameList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### RebaseOpcodes {#aadab92b5ce3df4b0f366cd1ef5b091ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachOYAML::RebaseOpcode&gt; llvm::MachOYAML::LinkEditData::RebaseOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### StringTable {#ad104df941ead6634db84cd8aa986be61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StringRef&gt; llvm::MachOYAML::LinkEditData::StringTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

### WeakBindOpcodes {#a09222d71153a9de2d30d507dca561fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachOYAML::BindOpcode&gt; llvm::MachOYAML::LinkEditData::WeakBindOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="#adb23ca348f8901b1a2e53cf9b25dcf3e">isEmpty</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoyaml-cpp">MachOYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
