---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-msferror-cpp-/msferrorcategory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MSFErrorCategory` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MSFError.cpp}::MSFErrorCategory { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2b768b75a1a749ad1a2bfd7381eb98">name</a> () const noexcept override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b5ea0490011abc462181dbcb6fc2dc8">message</a> (int Condition) const override</td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msferror-cpp">MSFError.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### message() {#a7b5ea0490011abc462181dbcb6fc2dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{MSFError.cpp}::MSFErrorCategory::message (int Condition)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msferror-cpp">MSFError.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa87c1c463ae3beee04ac2905a77fa425c">llvm::msf::block_in_use</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa30d5ef9a8eb9e9530b28192db6bd88b0">llvm::msf::insufficient_buffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa8e40c21d17487b141e798359ee241411">llvm::msf::invalid_format</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa881999a844c0bb1ee62b8bd1b29e60bb">llvm::msf::no_stream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873facec5971823d0dfd972069bf51c2f838f">llvm::msf::not_writable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa14762d2711ff5375899e75da45df68b4">llvm::msf::size_overflow_16384</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873facd7aa32ba229e33a15ddca2fede88071">llvm::msf::size_overflow_32768</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa9176c1a7eb168fb985b8d06a0b7e71d4">llvm::msf::size_overflow_4096</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fabbd9a1474b25700e3efa35ba7242b07a">llvm::msf::size_overflow_8192</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fa3192cccfba56c4afe73c51444ceb8432">llvm::msf::stream_directory_overflow</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msf/#a6dd094d4d36a053567100db04e6f873fad415f0e30c471dfdd9bc4f827329ef48">llvm::msf::unspecified</a>.</p>

</div>
</div>

### name() {#a7e2b768b75a1a749ad1a2bfd7381eb98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{MSFError.cpp}::MSFErrorCategory::name ()</td>
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



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msferror-cpp">MSFError.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msferror-cpp">MSFError.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
