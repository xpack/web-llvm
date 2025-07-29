---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-error-cpp-/-object-error-category
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `_object_error_category` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{Error.cpp}::_object_error_category { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63ed9b2ad8bdf72c0ae870d2262269f">name</a> () const noexcept override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1ff2db600ebb10c06787ee5391cace">message</a> (int ev) const override</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/object/error-cpp">Error.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### message() {#add1ff2db600ebb10c06787ee5391cace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string _object_error_category::message (int ev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/object/error-cpp">Error.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aa9d094e9a3b7763e4d2813ba8f450b21">llvm::object::arch_not_found</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20acf4e23aab5a1a4938f1a2cd521acf882">llvm::object::bitcode_section_not_found</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20ad5a8a27f4e310ea593b285615faaca35">llvm::object::invalid_file_type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20a0352e6404e8f88399d202d70b5bf34f9">llvm::object::invalid_section_index</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20a5bebdfcdc2e040554e436e976c420bc9">llvm::object::invalid_symbol_index</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20a224617ddd75966f4a2266795faa90b2f">llvm::object::section_stripped</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20a08ec16ece729e91b54f5b0f8b41c3af6">llvm::object::string_table_non_null_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20a1a5b101afc11147048312dd33b62e008">llvm::object::unexpected_eof</a>.</p>

</div>
</div>

### name() {#af63ed9b2ad8bdf72c0ae870d2262269f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * _object_error_category::name ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/object/error-cpp">Error.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/error-cpp">Error.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
