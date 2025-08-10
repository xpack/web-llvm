---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/cskyattributes-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `CSKYAttributes.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cskyattributes-h">llvm/Support/CSKYAttributes.h</a>"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/tagnameitem">TagNameItem</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af47f6a0dfb24fbf1350fc0648b8aa2af">tagData</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/namespaces/llvm/#a8ba0ebd86185aea94f29ed853c4dd97f">TagNameMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b9593940606ebea1d82a92f9964381">CSKYAttributeTags</a> {<a href="/web-llvm/docs/api/files/lib/lib/support/armbuildattributes-cpp/#af47f6a0dfb24fbf1350fc0648b8aa2af">tagData</a>}</td>
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

## Variables

### CSKYAttributeTags {#ab6b9593940606ebea1d82a92f9964381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagNameMap CSKYAttributeTags {<a href="/web-llvm/docs/api/files/lib/lib/support/armbuildattributes-cpp/#af47f6a0dfb24fbf1350fc0648b8aa2af">tagData</a>}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/support/cskyattributes-cpp">CSKYAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cskyattrs/#afc0741b2ab947e59673ccb184fd7ae99">llvm::CSKYAttrs::getCSKYAttributeTags</a>.</p>

</div>
</div>

### tagData {#af47f6a0dfb24fbf1350fc0648b8aa2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagNameItem tagData[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {CSKY_ARCH_NAME, "Tag_CSKY_ARCH_NAME"},
    {<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/cskytargetparser-h/#a61531837590528687c017dd551fe8537">CSKY_CPU_NAME</a>, "Tag_CSKY_CPU_NAME"},
    {<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/cskytargetparser-h/#a61531837590528687c017dd551fe8537">CSKY_CPU_NAME</a>, "Tag_CSKY_CPU_NAME"},
    {CSKY_ISA_FLAGS, "Tag_CSKY_ISA_FLAGS"},
    {CSKY_ISA_EXT_FLAGS, "Tag_CSKY_ISA_EXT_FLAGS"},
    {CSKY_DSP_VERSION, "Tag_CSKY_DSP_VERSION"},
    {CSKY_VDSP_VERSION, "Tag_CSKY_VDSP_VERSION"},
    {CSKY_FPU_VERSION, "Tag_CSKY_FPU_VERSION"},
    {CSKY_FPU_ABI, "Tag_CSKY_FPU_ABI"},
    {CSKY_FPU_ROUNDING, "Tag_CSKY_FPU_ROUNDING"},
    {CSKY_FPU_DENORMAL, "Tag_CSKY_FPU_DENORMAL"},
    {CSKY_FPU_EXCEPTION, "Tag_CSKY_FPU_EXCEPTION"},
    {CSKY_FPU_NUMBER_MODULE, "Tag_CSKY_FPU_NUMBER_MODULE"},
    {CSKY_FPU_HARDFP, "Tag_CSKY_FPU_HARDFP"}}
</div>
</dd>
</dl>

<p>Definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/support/cskyattributes-cpp">CSKYAttributes.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
