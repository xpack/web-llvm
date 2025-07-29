---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeviewyaml/debughsection
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DebugHSection` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::CodeViewYAML::DebugHSection { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypehashing-h">llvm/ObjectYAML/CodeViewYAMLTypeHashing.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5573d7e4b8cd1fdb66455023c30e7e1">Magic</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987fed06b7cfb1095cd975117a2b6d65">Version</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656cb398ff8c7d0b041c9ed65e548c96">HashAlgorithm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/globalhash">GlobalHash</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d6ca4055e86103346b265346fd067a1">Hashes</a></td>
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


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypehashing-h">CodeViewYAMLTypeHashing.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### HashAlgorithm {#a656cb398ff8c7d0b041c9ed65e548c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::CodeViewYAML::DebugHSection::HashAlgorithm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypehashing-h">CodeViewYAMLTypeHashing.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae656922d1c902f1107654bd1ae01501a">llvm::CodeViewYAML::fromDebugH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ad026ca61ae553f5da149349b2662e425">llvm::CodeViewYAML::toDebugH</a>.</p>

</div>
</div>

### Hashes {#a1d6ca4055e86103346b265346fd067a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;GlobalHash&gt; llvm::CodeViewYAML::DebugHSection::Hashes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypehashing-h">CodeViewYAMLTypeHashing.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae656922d1c902f1107654bd1ae01501a">llvm::CodeViewYAML::fromDebugH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ad026ca61ae553f5da149349b2662e425">llvm::CodeViewYAML::toDebugH</a>.</p>

</div>
</div>

### Magic {#ac5573d7e4b8cd1fdb66455023c30e7e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::CodeViewYAML::DebugHSection::Magic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypehashing-h">CodeViewYAMLTypeHashing.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae656922d1c902f1107654bd1ae01501a">llvm::CodeViewYAML::fromDebugH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ad026ca61ae553f5da149349b2662e425">llvm::CodeViewYAML::toDebugH</a>.</p>

</div>
</div>

### Version {#a987fed06b7cfb1095cd975117a2b6d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::CodeViewYAML::DebugHSection::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypehashing-h">CodeViewYAMLTypeHashing.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae656922d1c902f1107654bd1ae01501a">llvm::CodeViewYAML::fromDebugH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ad026ca61ae553f5da149349b2662e425">llvm::CodeViewYAML::toDebugH</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypehashing-h">CodeViewYAMLTypeHashing.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
