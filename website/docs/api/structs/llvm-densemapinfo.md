---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/densemapinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DenseMapInfo` Struct Template

<p>An information struct used to provide <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> with the various necessary components for a given value type <span class="doxyComputerOutput">T</span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename Enable = void&gt;
struct llvm::DenseMapInfo&lt;T, Enable&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemapinfo-h">llvm/ADT/DenseMapInfo.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/densemapinfo-7d3bcafc46d82ae4113aa2c8b1cf728e">DenseMapInfo&lt;AA::ValueScope&gt;</a></td>
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

<p>An information struct used to provide <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> with the various necessary components for a given value type <span class="doxyComputerOutput">T</span>.</p>


<p><span class="doxyComputerOutput">Enable</span> is an optional additional parameter that is used to support SFINAE (generally using std::enable_if_t) in derived <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a> specializations; in non-SFINAE use cases this should just be <span class="doxyComputerOutput">void</span>.</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemapinfo-h">DenseMapInfo.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
