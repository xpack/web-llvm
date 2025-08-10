---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bitfields-details/resolveunderlyingtype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ResolveUnderlyingType` Struct Template

<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/bitfield">Bitfield</a></span> deals with the following type: <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, bool = std::is_enum&lt;T&gt;::value&gt;
struct llvm::bitfields_details::ResolveUnderlyingType&lt;T, bool&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">llvm/ADT/Bitfields.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, bool = std::is_enum&lt;T&gt;::value&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4c2aa122f10ecb5f1315d106a43da9aa">type</a> = std::underlying_type_t&lt; T &gt;</td>
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

<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/bitfield">Bitfield</a></span> deals with the following type:</p>


<ul class="doxyList ">
<li>unsigned enums</li>
<li>signed and unsigned integer</li>
<li><span class="doxyComputerOutput">bool</span> Internally though we only manipulate integer with well defined and consistent semantics, this excludes typed enums and <span class="doxyComputerOutput">bool</span> that are replaced with their unsigned counterparts. The correct type is restored in the public API.</li>
</ul>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### type {#a4c2aa122f10ecb5f1315d106a43da9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = std::is_enum&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::bitfields_details::ResolveUnderlyingType&lt; T, bool &gt;::type =  std::underlying_type_t&lt;T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
