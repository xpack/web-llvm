---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/sys/detail/x86
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `x86` Namespace Reference

<p>Helper functions to extract CPU details from CPUID on <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/x86">x86</a>. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::sys::detail::x86 { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VendorSignatures { <a href="#acb4b733a1f49794a905f5735a30bf466">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acb4b733a1f49794a905f5735a30bf466">VendorSignatures</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6098093bce999858442cd6a17a299e9">getVendorSignature</a> (unsigned *MaxLeaf=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the host CPU's vendor. <a href="#af6098093bce999858442cd6a17a299e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper functions to extract CPU details from CPUID on <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/x86">x86</a>.</p>

<div class="doxySectionDef">

## Enumerations

### VendorSignatures {#acb4b733a1f49794a905f5735a30bf466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::sys::detail::x86::VendorSignatures </td>
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
<td class="doxyEnumItemName">UNKNOWN<a id="acb4b733a1f49794a905f5735a30bf466a696b031073e74bf2cb98e5ef201d4aa3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GENUINE_INTEL<a id="acb4b733a1f49794a905f5735a30bf466ac21b5352fdce8cbfdfab24a7f138d091"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUTHENTIC_AMD<a id="acb4b733a1f49794a905f5735a30bf466a2c333fca249d8d869bd42d141c055ab2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">Host.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getVendorSignature() {#af6098093bce999858442cd6a17a299e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VendorSignatures llvm::sys::detail::x86::getVendorSignature (unsigned * MaxLeaf=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the host CPU's vendor.</p>


<p>MaxLeaf: if a non-nullptr pointer is specified, the EAX value will be assigned to its pointee.</p>


<p>Definition at line 1799 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/host-cpp">Host.cpp</a>.</p>


<p>Reference <a href="#acb4b733a1f49794a905f5735a30bf466a696b031073e74bf2cb98e5ef201d4aa3">UNKNOWN</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">Host.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/host-cpp">Host.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
