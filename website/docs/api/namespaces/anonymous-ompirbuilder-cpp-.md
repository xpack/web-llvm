---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-ompirbuilder-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{OMPIRBuilder.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{OMPIRBuilder.cpp} { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OpenMPOffloadingRequiresDirFlags { <a href="#a6c4c036b1f33a03ce42152b5eb9c3f59">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values for bit flags for marking which requires clauses have been used. <a href="#a6c4c036b1f33a03ce42152b5eb9c3f59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b6a7e92a601fa5fffd86f5d29df35fa">LLVM_ENABLE_BITMASK_ENUMS_IN_NAMESPACE</a> ()</td>
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


<div class="doxySectionDef">

## Enumerations

### OpenMPOffloadingRequiresDirFlags {#a6c4c036b1f33a03ce42152b5eb9c3f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{OMPIRBuilder.cpp}::OpenMPOffloadingRequiresDirFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values for bit flags for marking which requires clauses have been used.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_REQ_UNDEFINED<a id="a6c4c036b1f33a03ce42152b5eb9c3f59a7972c62027157095f27334a175046ec8"></a></td>
<td class="doxyEnumItemDescription">flag undefined (= 0x000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_REQ_NONE<a id="a6c4c036b1f33a03ce42152b5eb9c3f59a133a116519cf4d083bd62fe903222233"></a></td>
<td class="doxyEnumItemDescription">no requires directive present (= 0x001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_REQ_REVERSE_OFFLOAD<a id="a6c4c036b1f33a03ce42152b5eb9c3f59a9fc383d39ee53daf5acd732e83f612ac"></a></td>
<td class="doxyEnumItemDescription">reverse_offload clause (= 0x002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_REQ_UNIFIED_ADDRESS<a id="a6c4c036b1f33a03ce42152b5eb9c3f59adea434f369cc7e932a9a8a6794cf4d30"></a></td>
<td class="doxyEnumItemDescription">unified_address clause (= 0x004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_REQ_UNIFIED_SHARED_MEMORY<a id="a6c4c036b1f33a03ce42152b5eb9c3f59a181e4e34f98a2ff557a47da8eba82652"></a></td>
<td class="doxyEnumItemDescription">unified_shared_memory clause (= 0x008)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMP_REQ_DYNAMIC_ALLOCATORS<a id="a6c4c036b1f33a03ce42152b5eb9c3f59ae27c8208560d202db5844b7de3667d76"></a></td>
<td class="doxyEnumItemDescription">dynamic_allocators clause (= 0x010)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVM\_ENABLE\_BITMASK\_ENUMS\_IN\_NAMESPACE() {#a5b6a7e92a601fa5fffd86f5d29df35fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{OMPIRBuilder.cpp}::LLVM_ENABLE_BITMASK_ENUMS_IN_NAMESPACE ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
