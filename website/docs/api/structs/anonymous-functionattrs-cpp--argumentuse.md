---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-functionattrs-cpp-/argumentuse
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ArgumentUse` Struct Reference

<p>A struct of argument use: a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> and the offset it accesses. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{FunctionAttrs.cpp}::ArgumentUse { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1eb309b149d0845b801d4afc737042">U</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81d6fcd911b20a4933f45bf6f318aea5">Offset</a></td>
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

<p>A struct of argument use: a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> and the offset it accesses.</p>


<p>This struct is to track uses inside function via GEP. If GEP has a non-constant index, the Offset field is nullopt.</p>


<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Offset {#a81d6fcd911b20a4933f45bf6f318aea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;int64_t&gt; anonymous{FunctionAttrs.cpp}::ArgumentUse::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#ab0236d3f5f443260abf1ccfb1e5cc5a6">anonymous{FunctionAttrs.cpp}::collectArgumentUsesPerBlock</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#aecfb2afc99cffa8880ec262d026a5038">anonymous{FunctionAttrs.cpp}::getArgmentAccessInfo</a>.</p>

</div>
</div>

### U {#aeb1eb309b149d0845b801d4afc737042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use* anonymous{FunctionAttrs.cpp}::ArgumentUse::U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#ab0236d3f5f443260abf1ccfb1e5cc5a6">anonymous{FunctionAttrs.cpp}::collectArgumentUsesPerBlock</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#aecfb2afc99cffa8880ec262d026a5038">anonymous{FunctionAttrs.cpp}::getArgmentAccessInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
