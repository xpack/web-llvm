---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MappingTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;const InterfaceFile *&gt; { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d0ea339f29629e3f0cc061fcbe7c186">SectionList</a> = std::vector&lt; SymbolSection &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2af5f0ae3f3bee5f2c87b4139c6111">setFileTypeForInput</a> (TextAPIContext *Ctx, IO &amp;IO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50f092a891c4873f55a91fc98c04e7b9">mapping</a> (IO &amp;IO, const InterfaceFile *&amp;File)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36b5d7a005d7098498bdaf44c8d66df">mapKeysToValues</a> (FileType FileKind, IO &amp;IO, const InterfaceFile *&amp;File)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2697a94da66ab22f86dc0d115073aaa2">mapKeysToValuesV4</a> (IO &amp;IO, const InterfaceFile *&amp;File)</td>
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


<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SectionList {#a4d0ea339f29629e3f0cc061fcbe7c186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::SectionList =  std::vector&lt;SymbolSection&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### mapKeysToValues() {#af36b5d7a005d7098498bdaf44c8d66df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapKeysToValues (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a> FileKind, <a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> *&amp; File)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a6ce55ac03358478c63eaefb8578a7a31a6adf97f83acf6453d4a6a4b1070f3754">llvm::MachO::None</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ac9d3e887722f2bc482bcca9d41c512af">None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a6ce55ac03358478c63eaefb8578a7a31ab99a64738d781d845448271643d5457a">llvm::MachO::Retain_Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a50e1b7d3e1ed10d92235a499b0a0322a">llvm::MachO::TBD_V1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3b3aa8ad245f6b7318bebf085418816">llvm::MachO::TBD_V3</a>.</p>


<p>Referenced by <a href="#a50f092a891c4873f55a91fc98c04e7b9">mapping</a>.</p>

</div>
</div>

### mapKeysToValuesV4() {#a2697a94da66ab22f86dc0d115073aaa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapKeysToValuesV4 (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> *&amp; File)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-textstub-cpp-/metadatasection/#aa40de9871d62ae4f79fcecb74df37feea0cf9cf59f5588aad95613e82ac18dffa">anonymous{TextStub.cpp}::MetadataSection::Clients</a>, <a href="/web-llvm/docs/api/structs/anonymous-textstub-cpp-/metadatasection/#aa40de9871d62ae4f79fcecb74df37feea7c9f32bd12949d621658b595fd33bcb3">anonymous{TextStub.cpp}::MetadataSection::Libraries</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a1407aaef6dfdc3eef37f9d9c4d5379f3">llvm::yaml::IO::mapOptionalWithContext</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a48aefe64f43e923bdcaddcc2ea3eaf0c">llvm::yaml::IO::mapTag</a> and <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ac9d3e887722f2bc482bcca9d41c512af">None</a>.</p>


<p>Referenced by <a href="#a50f092a891c4873f55a91fc98c04e7b9">mapping</a>.</p>

</div>
</div>

### mapping() {#a50f092a891c4873f55a91fc98c04e7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> *&amp; File)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a9602206972cc02cc749acfca45487271">llvm::yaml::IO::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a48d53340ae80e1c1862548611e92c864">llvm::MachO::Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#af36b5d7a005d7098498bdaf44c8d66df">mapKeysToValues</a>, <a href="#a2697a94da66ab22f86dc0d115073aaa2">mapKeysToValuesV4</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a48aefe64f43e923bdcaddcc2ea3eaf0c">llvm::yaml::IO::mapTag</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a3f9abe4cc7cc808cb6025ed882bcbb7d">llvm::yaml::IO::outputting</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a930906994b5dc96a35696936fe705c15">llvm::yaml::IO::setError</a>, <a href="#a3a2af5f0ae3f3bee5f2c87b4139c6111">setFileTypeForInput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a50e1b7d3e1ed10d92235a499b0a0322a">llvm::MachO::TBD_V1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7aca27acf08b2ba9723e508a1671c35f8b">llvm::MachO::TBD_V2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3b3aa8ad245f6b7318bebf085418816">llvm::MachO::TBD_V3</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7abeff4de6e3db063aac951727cf4d7c2b">llvm::MachO::TBD_V4</a>.</p>

</div>
</div>

### setFileTypeForInput() {#a3a2af5f0ae3f3bee5f2c87b4139c6111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::setFileTypeForInput (<a href="/web-llvm/docs/api/structs/llvm/macho/textapicontext">TextAPIContext</a> * Ctx, <a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a48d53340ae80e1c1862548611e92c864">llvm::MachO::Invalid</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a48aefe64f43e923bdcaddcc2ea3eaf0c">llvm::yaml::IO::mapTag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a50e1b7d3e1ed10d92235a499b0a0322a">llvm::MachO::TBD_V1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7aca27acf08b2ba9723e508a1671c35f8b">llvm::MachO::TBD_V2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3b3aa8ad245f6b7318bebf085418816">llvm::MachO::TBD_V3</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7abeff4de6e3db063aac951727cf4d7c2b">llvm::MachO::TBD_V4</a>.</p>


<p>Referenced by <a href="#a50f092a891c4873f55a91fc98c04e7b9">mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
