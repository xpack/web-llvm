---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `StringViewExtras.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h">DemangleConfig.h</a>"
#include &lt;string_view&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h/#ad82d307eb10a0e447f4b254f0af7dde7">DEMANGLE_NAMESPACE_BEGIN</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5336c02c81ff675028496f2f2409d30a">starts_with</a> (std::string_view self, char C) noexcept</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48fd2c6ad5c5bec6104f1a7605ded4ce">starts_with</a> (std::string_view haystack, std::string_view needle) noexcept</td>
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

## Functions

### starts\_with() {#a5336c02c81ff675028496f2f2409d30a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEMANGLE_NAMESPACE_BEGIN bool starts_with (std::string_view self, char C)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h">StringViewExtras.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/classes/anonymous-rustdemangle-cpp-/demangler/#af3dbbb676ca9db03f2e91ba68cf0ade4">anonymous{RustDemangle.cpp}::Demangler::demangle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab996639d406a5466d5c8a1586fb4a9d8">llvm::demangle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f56cfd37698f599f5bee9bbf4015ca1">llvm::dlangDemangle</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#aebb9a5bb7299045f334f16d82f244ad0">llvm::opt::OptTable::findByPrefix</a>, <a href="/web-llvm/docs/api/classes/specialsubstitution/#a806f152c432d118d8063a6825a0e009e">SpecialSubstitution::getBaseName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a5cd7a516996539c18628e51d9f628e07">llvm::sys::detail::getHostCPUNameForARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a6c6d718154a7120db2e00cd7a1895aea">llvm::sys::detail::getHostCPUNameForRISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a3455f56c4a28156282d4f5cd6265e034">llvm::sys::detail::getHostCPUNameForS390x</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aeed1fbd4f82f1bc9c4ada7ce9835edb7">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/demangle-cpp/#a4cc51231e0b5af284aadea8db9856a66">isDLangEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/demangle-cpp/#a0449b898c4fc800bd0819b47e9e4c3d9">isRustEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#ab75e1a82e3ca70f21faf74933f2471b0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#ace6000853f038505e58f9c498b85d60b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSourceName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ba12f62b7c7aac2fe0d725965b597ec">llvm::rustDemangle</a>.</p>

</div>
</div>

### starts\_with() {#a48fd2c6ad5c5bec6104f1a7605ded4ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool starts_with (std::string_view haystack, std::string_view needle)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h">StringViewExtras.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
