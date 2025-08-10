---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-genericerror-cpp-/pdberrorcategory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PDBErrorCategory` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{GenericError.cpp}::PDBErrorCategory { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::error_category</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e2b8b7e31b2a0ed195fd951c9c6175d">name</a> () const noexcept override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec857bb82a7e18827753055ca38d31c">message</a> (int Condition) const override</td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/genericerror-cpp">GenericError.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### message() {#a3ec857bb82a7e18827753055ca38d31c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{GenericError.cpp}::PDBErrorCategory::message (int Condition)</td>
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



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/genericerror-cpp">GenericError.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aef1d501dfe72c1eac4158fc2bcbe53e7a0dd27af0aeccac00157ef6768de27e76">llvm::pdb::dia_failed_loading</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aef1d501dfe72c1eac4158fc2bcbe53e7a02081b2087ce20eacc13ba757d240b2f">llvm::pdb::dia_sdk_not_present</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aef1d501dfe72c1eac4158fc2bcbe53e7a1591cf6ace8d620ef23d39d0db80fdea">llvm::pdb::invalid_utf8_path</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aef1d501dfe72c1eac4158fc2bcbe53e7af44d87e33d47902c5193e0d6f808b60b">llvm::pdb::no_matching_pch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aef1d501dfe72c1eac4158fc2bcbe53e7a62cee3a8dd3d870ddac3629f5b026b73">llvm::pdb::signature_out_of_date</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aef1d501dfe72c1eac4158fc2bcbe53e7ad415f0e30c471dfdd9bc4f827329ef48">llvm::pdb::unspecified</a>.</p>

</div>
</div>

### name() {#a8e2b8b7e31b2a0ed195fd951c9c6175d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{GenericError.cpp}::PDBErrorCategory::name ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/genericerror-cpp">GenericError.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/genericerror-cpp">GenericError.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
