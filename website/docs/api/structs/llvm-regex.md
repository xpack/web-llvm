---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm-regex
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `llvm_regex` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm_regex { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">Support/regex_impl.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a96d03c57ddbbacd6bd4f5e587ce558">re_magic</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7b9279f0acdb26e438298369f121641">re_nsub</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5da3516ebe39b7fe40315175d49b55a">re_endp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21d425d48e65f2408ccadde7ec358bf7">re_g</a></td>
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


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### re\_endp {#af5da3516ebe39b7fe40315175d49b55a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm_regex::re_endp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c/#af481b7e4615b89b40883ff6f7f60bafd">regatoi</a>.</p>

</div>
</div>

### re\_g {#a21d425d48e65f2408ccadde7ec358bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct re_guts* llvm_regex::re_g</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5b067957e932003b295ff3a8bbffe882">llvm_regfree</a>.</p>

</div>
</div>

### re\_magic {#a1a96d03c57ddbbacd6bd4f5e587ce558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm_regex::re_magic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5b067957e932003b295ff3a8bbffe882">llvm_regfree</a>.</p>

</div>
</div>

### re\_nsub {#ab7b9279f0acdb26e438298369f121641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm_regex::re_nsub</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
