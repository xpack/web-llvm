---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/fmtalign
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FmtAlign` Struct Reference

<p>Helper class to format to a <span class="doxyComputerOutput">Width</span> wide field, with alignment <span class="doxyComputerOutput">Where</span> within that field. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::FmtAlign { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">llvm/Support/FormatCommon.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f6b25c52e2d0d54c032f8654da81881">FmtAlign</a> (support::detail::format_adapter &amp;Adapter, AlignStyle Where, unsigned Width, char Fill=' ')</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06665722517b54511c786e23deb8ec81">format</a> (raw_ostream &amp;S, StringRef Options)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec9f38b20d81bba3bad3de466ddb37d">fill</a> (llvm::raw_ostream &amp;S, unsigned Count)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/support/detail/format-adapter">support::detail::format_adapter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa601e7de501140c8aa3c5328a268ec69">Adapter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0">AlignStyle</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa95a6f97b1f8ada98bd6582a3797bd6e">Where</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99886e361fe32568505d9cff62f7fe5">Width</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365e3980e8350c84aa415590d28806d7">Fill</a></td>
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

<p>Helper class to format to a <span class="doxyComputerOutput">Width</span> wide field, with alignment <span class="doxyComputerOutput">Where</span> within that field.</p>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">FormatCommon.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FmtAlign() {#a2f6b25c52e2d0d54c032f8654da81881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FmtAlign::FmtAlign (<a href="/web-llvm/docs/api/classes/llvm/support/detail/format-adapter">support::detail::format_adapter</a> &amp; Adapter, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0">AlignStyle</a> Where, unsigned Width, char Fill=' ')</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">FormatCommon.h</a>.</p>


<p>References <a href="#aa601e7de501140c8aa3c5328a268ec69">Adapter</a>, <a href="#a365e3980e8350c84aa415590d28806d7">Fill</a>, <a href="#aa95a6f97b1f8ada98bd6582a3797bd6e">Where</a> and <a href="#ab99886e361fe32568505d9cff62f7fe5">Width</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### format() {#a06665722517b54511c786e23deb8ec81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FmtAlign::format (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Options)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">FormatCommon.h</a>.</p>


<p>References <a href="#aa601e7de501140c8aa3c5328a268ec69">Adapter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a4f1f6016fc9f3f2353c0cc7c67b292bd">llvm::Center</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a945d5e233cf7d6240f6b783b36a374ff">llvm::Left</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#aa95a6f97b1f8ada98bd6582a3797bd6e">Where</a>, <a href="#ab99886e361fe32568505d9cff62f7fe5">Width</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/support/detail/alignadapter/#a5047d7fd2ee5e2242ec1b60b171462ba">llvm::support::detail::AlignAdapter&lt; T &gt;::format</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### fill() {#a9ec9f38b20d81bba3bad3de466ddb37d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FmtAlign::fill (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; S, unsigned Count)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">FormatCommon.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Adapter {#aa601e7de501140c8aa3c5328a268ec69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::detail::format_adapter&amp; llvm::FmtAlign::Adapter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">FormatCommon.h</a>.</p>


<p>Referenced by <a href="#a2f6b25c52e2d0d54c032f8654da81881">FmtAlign</a> and <a href="#a06665722517b54511c786e23deb8ec81">format</a>.</p>

</div>
</div>

### Fill {#a365e3980e8350c84aa415590d28806d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::FmtAlign::Fill</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">FormatCommon.h</a>.</p>


<p>Referenced by <a href="#a2f6b25c52e2d0d54c032f8654da81881">FmtAlign</a>.</p>

</div>
</div>

### Where {#aa95a6f97b1f8ada98bd6582a3797bd6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AlignStyle llvm::FmtAlign::Where</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">FormatCommon.h</a>.</p>


<p>Referenced by <a href="#a2f6b25c52e2d0d54c032f8654da81881">FmtAlign</a> and <a href="#a06665722517b54511c786e23deb8ec81">format</a>.</p>

</div>
</div>

### Width {#ab99886e361fe32568505d9cff62f7fe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FmtAlign::Width</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">FormatCommon.h</a>.</p>


<p>Referenced by <a href="#a2f6b25c52e2d0d54c032f8654da81881">FmtAlign</a> and <a href="#a06665722517b54511c786e23deb8ec81">format</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatcommon-h">FormatCommon.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
