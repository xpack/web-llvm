---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/machinejumptable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MachineJumpTable` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MachineJumpTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">llvm/CodeGen/MIRYamlMapping.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6486788768688e6d81bd1f4242130a65">operator==</a> (const MachineJumpTable &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3">MachineJumpTableInfo::JTEntryKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a93874ae04bba919a09c023a2170f0">Kind</a> = <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3a9e655fb625d744f96e03aed78ca85707">MachineJumpTableInfo::EK_Custom32</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable/entry">Entry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6986f1a514dddef9e9217329a45b54cc">Entries</a></td>
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


<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#a6486788768688e6d81bd1f4242130a65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineJumpTable::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable">MachineJumpTable</a> &amp; Other)</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>References <a href="#a6986f1a514dddef9e9217329a45b54cc">Entries</a>, <a href="#ac8a93874ae04bba919a09c023a2170f0">Kind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Entries {#a6986f1a514dddef9e9217329a45b54cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Entry&gt; llvm::yaml::MachineJumpTable::Entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a144cc64259d65d3f419f9d176fcf8078">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a4e8962fa2139c288809acff971691109">llvm::MIRParserImpl::initializeJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="#a6486788768688e6d81bd1f4242130a65">operator==</a>.</p>

</div>
</div>

### Kind {#ac8a93874ae04bba919a09c023a2170f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineJumpTableInfo::JTEntryKind llvm::yaml::MachineJumpTable::Kind = <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#aaa21facdbb167f7c33d21907b8e5b9d3a9e655fb625d744f96e03aed78ca85707">MachineJumpTableInfo::EK_Custom32</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a144cc64259d65d3f419f9d176fcf8078">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a4e8962fa2139c288809acff971691109">llvm::MIRParserImpl::initializeJumpTableInfo</a> and <a href="#a6486788768688e6d81bd1f4242130a65">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
