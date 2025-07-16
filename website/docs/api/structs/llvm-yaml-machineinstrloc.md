---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/machineinstrloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MachineInstrLoc` Struct Reference

<p>Identifies call instruction location in machine function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MachineInstrLoc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">llvm/CodeGen/MIRYamlMapping.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcdaefbbd70d3d3ccf5faf8a679dc1c">operator==</a> (const MachineInstrLoc &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec118b50f06a567a4cd9c2672df78eca">BlockNum</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa0de3b3a876eac2d341f1c52478242">Offset</a></td>
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

<p>Identifies call instruction location in machine function.</p>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#a4fcdaefbbd70d3d3ccf5faf8a679dc1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineInstrLoc::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machineinstrloc">MachineInstrLoc</a> &amp; Other)</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>References <a href="#aec118b50f06a567a4cd9c2672df78eca">BlockNum</a>, <a href="#a2fa0de3b3a876eac2d341f1c52478242">Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BlockNum {#aec118b50f06a567a4cd9c2672df78eca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::MachineInstrLoc::BlockNum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aa43a432a700f337af56c8f2d1db9fe0b">llvm::MIRPrinter::convertCallSiteObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#aea53e647298055af644a50c3a29e1411">llvm::MIRParserImpl::initializeCallSiteInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3af05eceb84db8df1f34d5629071ce73/#a15007847e9928e403f5c8c4f538d6b4f">llvm::yaml::MappingTraits&lt; CalledGlobal &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-698d41c33e934b305ab621e594cd8f06/#a0ad0a9c3605a1677d2a8111d04449cdd">llvm::yaml::MappingTraits&lt; CallSiteInfo &gt;::mapping</a>, <a href="#a4fcdaefbbd70d3d3ccf5faf8a679dc1c">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a9d55670b674a7d3bc9f2df1668d63be8">llvm::MIRParserImpl::parseCalledGlobals</a>.</p>

</div>
</div>

### Offset {#a2fa0de3b3a876eac2d341f1c52478242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::MachineInstrLoc::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aa43a432a700f337af56c8f2d1db9fe0b">llvm::MIRPrinter::convertCallSiteObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#aea53e647298055af644a50c3a29e1411">llvm::MIRParserImpl::initializeCallSiteInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3af05eceb84db8df1f34d5629071ce73/#a15007847e9928e403f5c8c4f538d6b4f">llvm::yaml::MappingTraits&lt; CalledGlobal &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-698d41c33e934b305ab621e594cd8f06/#a0ad0a9c3605a1677d2a8111d04449cdd">llvm::yaml::MappingTraits&lt; CallSiteInfo &gt;::mapping</a>, <a href="#a4fcdaefbbd70d3d3ccf5faf8a679dc1c">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a9d55670b674a7d3bc9f2df1668d63be8">llvm::MIRParserImpl::parseCalledGlobals</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
