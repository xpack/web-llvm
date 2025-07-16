---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-35fb56b6eed5c6961763c71ac116b491
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MappingTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;SIArgument&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">Target/AMDGPU/SIMachineFunctionInfo.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6743f808968eb3d08882ac6956108e">mapping</a> (IO &amp;YamlIO, SIArgument &amp;A)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1916f0bbfbc97efdc0199b2eb8d4be5b">flow</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#afe6743f808968eb3d08882ac6956108e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; SIArgument &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; YamlIO, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargument">SIArgument</a> &amp; A)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/siargument/#ad8ac06219747f8ed558a3d748f604a9a">llvm::yaml::SIArgument::createArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#af1ca4f897adb4845e0f5456540bbdc7b">llvm::yaml::IO::keys</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a3f9abe4cc7cc808cb6025ed882bcbb7d">llvm::yaml::IO::outputting</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a930906994b5dc96a35696936fe705c15">llvm::yaml::IO::setError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### flow {#a1916f0bbfbc97efdc0199b2eb8d4be5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::yaml::MappingTraits&lt; SIArgument &gt;::flow = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
