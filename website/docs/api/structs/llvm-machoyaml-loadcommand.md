---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machoyaml/loadcommand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoadCommand` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MachOYAML::LoadCommand { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">llvm/ObjectYAML/MachOYAML.h</a>"
</div>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dcdc63834c68aa5a91713dbba0eaba5">~LoadCommand</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/macho/macho-load-command">llvm::MachO::macho_load_command</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a712b7aab94544ef011241b5319bc08e1">Data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section">Section</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779fd93978fe0bdbde03acf696a2e42c">Sections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/macho/build-tool-version">MachO::build_tool_version</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb414009afbdf8d402b752460dce9300">Tools</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; llvm::yaml::Hex8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaad205035ed1db5effe23ab49c8e8c8">PayloadBytes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f57d006721307993542e0b1369d12c">Content</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e92cdde5c91cb8dd41dd715f2be97c">ZeroPadBytes</a></td>
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


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~LoadCommand() {#a2dcdc63834c68aa5a91713dbba0eaba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachOYAML::LoadCommand::~LoadCommand ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Content {#a01f57d006721307993542e0b1369d12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MachOYAML::LoadCommand::Content</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a23f46d0a26e819554dc11cd876ae7585">llvm::yaml::mapLoadCommandData&lt; MachO::dylib_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a89177ee1b521d6f0d46774bdd45468c1">llvm::yaml::mapLoadCommandData&lt; MachO::dylinker_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2a96f3232d8c1fb48aa7ff6b6adb503a">llvm::yaml::mapLoadCommandData&lt; MachO::rpath_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a600e2473c4498418aa4cf64f292eceb4">llvm::yaml::mapLoadCommandData&lt; MachO::sub_client_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#afe633d1b6694f192485e34b94103039f">llvm::yaml::mapLoadCommandData&lt; MachO::sub_framework_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a251680a62d3832be4e53545b1d3eb804">llvm::yaml::mapLoadCommandData&lt; MachO::sub_library_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a0538fcaf6d6e95c13afc817d0ec2b83d">llvm::yaml::mapLoadCommandData&lt; MachO::sub_umbrella_command &gt;</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a3209e484dbc45751b9a056593f408e10">anonymous{MachOEmitter.cpp}::writePayloadString</a>.</p>

</div>
</div>

### Data {#a712b7aab94544ef011241b5319bc08e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::macho_load_command llvm::MachOYAML::LoadCommand::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-536762a2a2a330085e4350c4efc0f811/#a86a309d4a6b8f8cdc62f9b3fefe01ba5">llvm::yaml::MappingTraits&lt; MachOYAML::LoadCommand &gt;::mapping</a>.</p>

</div>
</div>

### PayloadBytes {#afaad205035ed1db5effe23ab49c8e8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;llvm::yaml::Hex8&gt; llvm::MachOYAML::LoadCommand::PayloadBytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-536762a2a2a330085e4350c4efc0f811/#a86a309d4a6b8f8cdc62f9b3fefe01ba5">llvm::yaml::MappingTraits&lt; MachOYAML::LoadCommand &gt;::mapping</a>.</p>

</div>
</div>

### Sections {#a779fd93978fe0bdbde03acf696a2e42c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Section&gt; llvm::MachOYAML::LoadCommand::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aac99fb9cd351c3277e29c808a54707ab">llvm::yaml::mapLoadCommandData&lt; MachO::segment_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a141797e2ace547979ea5798ffac93f34">llvm::yaml::mapLoadCommandData&lt; MachO::segment_command_64 &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a4526bc01726a48ab04a549eb59f98d82">anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::segment_command &gt;</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a218333fa07659a7328c0122fa819ed74">anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::segment_command_64 &gt;</a>.</p>

</div>
</div>

### Tools {#acb414009afbdf8d402b752460dce9300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachO::build_tool_version&gt; llvm::MachOYAML::LoadCommand::Tools</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a64e732b505355c4653160551165f32a9">llvm::yaml::mapLoadCommandData&lt; MachO::build_version_command &gt;</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#ab0452cfab8d631ffe612b7db3ca753f3">anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::build_version_command &gt;</a>.</p>

</div>
</div>

### ZeroPadBytes {#aa6e92cdde5c91cb8dd41dd715f2be97c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachOYAML::LoadCommand::ZeroPadBytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-536762a2a2a330085e4350c4efc0f811/#a86a309d4a6b8f8cdc62f9b3fefe01ba5">llvm::yaml::MappingTraits&lt; MachOYAML::LoadCommand &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
