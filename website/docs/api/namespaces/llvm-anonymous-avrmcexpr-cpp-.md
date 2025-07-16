---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/anonymous-avrmcexpr-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{AVRMCExpr.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::anonymous{AVRMCExpr.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/anonymous-avrmcexpr-cpp-/modifierentry">ModifierEntry</a></td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> struct llvm::anonymous_namespace{AVRMCExpr.cpp}::ModifierEntry</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c1b3b5870890c6d18408094e0cbbe7c">ModifierNames</a>[] = ...</td>
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

### ModifierNames {#a7c1b3b5870890c6d18408094e0cbbe7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const struct llvm::anonymous{AVRMCExpr.cpp}::ModifierEntry llvm::anonymous{AVRMCExpr.cpp}::ModifierNames[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {"lo8", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea17d68c3365d37bba98c265778c257de8">AVRMCExpr::VK_AVR_LO8</a>},       {"hi8", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ead983bf089910d03f38c6ecfd9895f40b">AVRMCExpr::VK_AVR_HI8</a>},
    {"hh8", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7eab5b06c1f5681eecbed057c4d595e74a1">AVRMCExpr::VK_AVR_HH8</a>}, 
    {"hlo8", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7eab5b06c1f5681eecbed057c4d595e74a1">AVRMCExpr::VK_AVR_HH8</a>},      {"hhi8", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea53c7ad4f7d81e5244496f4e27d984f82">AVRMCExpr::VK_AVR_HHI8</a>},
    {"pm", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea437c061b103c01b78c2d17eea54dc658">AVRMCExpr::VK_AVR_PM</a>},         {"pm_lo8", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea09e73cf360d6f7dded6a699c9d29a66f">AVRMCExpr::VK_AVR_PM_LO8</a>},
    {"pm_hi8", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea20904697ab7c0bfa532f2a5285321a82">AVRMCExpr::VK_AVR_PM_HI8</a>}, {"pm_hh8", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7eabf76baf9c9ef6feb676a09ff735c8918">AVRMCExpr::VK_AVR_PM_HH8</a>},
    {"lo8_gs", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7eabe72413cf67aa8fcadcf8f6944696211">AVRMCExpr::VK_AVR_LO8_GS</a>}, {"hi8_gs", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea842018630575f76fa01b12213e92e8a7">AVRMCExpr::VK_AVR_HI8_GS</a>},
    {"gs", <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7eabffd26c352f58776729a357e7e1bd290">AVRMCExpr::VK_AVR_GS</a>},
}
</div>
</dd>
</dl>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmcexpr-cpp">AVRMCExpr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
