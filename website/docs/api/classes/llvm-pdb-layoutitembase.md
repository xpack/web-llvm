---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/layoutitembase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LayoutItemBase` Class



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::LayoutItemBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">llvm/DebugInfo/PDB/UDTLayout.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/datamemberlayoutitem">DataMemberLayoutItem</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase">UDTLayoutBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/vbptrlayoutitem">VBPtrLayoutItem</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/vtablelayoutitem">VTableLayoutItem</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0e63790f73f9608f8ba426cb98178bc">LayoutItemBase</a> (const UDTLayoutBase *Parent, const PDBSymbol *Symbol, const std::string &amp;Name, uint32_t OffsetInParent, uint32_t Size, bool IsElided)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce1a2370856fd157314b71d2ba7ab7c">~LayoutItemBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a492f7b33957eb4402f058a6e90af346c">deepPaddingSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e549b6ff6558ad52e0f8e0289bf499">immediatePadding</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47cb3d653556d34f95405f1bdf9361b5">tailPadding</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase">UDTLayoutBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17df02fb67e74f3b29d21803b57ca6c">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f8076437782a6719e4c8eeadcb6c07">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a650f01b775ec9ed10bb5f2e40196ba8d">getOffsetInParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a31586f6cfca2197df724b439551b91">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0de0f4efe2019cf67ef2853e67fb2a">getLayoutSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a184c9e2209297e2453566e51ed35c26f">getSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc071fe28aaf963b93231e1ad87acd5">usedBytes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78b974c055ef8c95054bd02c9f016ef">isElided</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512ca6c2c3b257211ab6b775c891c5cc">isVBPtr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d76278f711394aad50f5590822df66c">containsOffset</a> (uint32_t Off) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09751a4aec4e5d3323d59b713c8ca4a">Symbol</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase">UDTLayoutBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed9833844c86541361110c19424d8c2f">Parent</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9133332d2b710957ef0836de8286073">UsedBytes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad10bda87163f7abb0fc4d862c66d8c06">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b003a2100c25845bfdb52de4700aed7">OffsetInParent</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219e1c40234502e0850ea8f378e2f192">SizeOf</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af33f2369fa87c3fe25cce0a4c591e4a1">LayoutSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af036e1dfe92e3a19a805b255ac43848a">IsElided</a> = false</td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LayoutItemBase() {#ad0e63790f73f9608f8ba426cb98178bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutItemBase::LayoutItemBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase">UDTLayoutBase</a> * Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, uint32_t OffsetInParent, uint32_t Size, bool IsElided)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>References <a href="#af036e1dfe92e3a19a805b255ac43848a">IsElided</a>, <a href="#af33f2369fa87c3fe25cce0a4c591e4a1">LayoutSize</a>, <a href="#ad10bda87163f7abb0fc4d862c66d8c06">Name</a>, <a href="#a1b003a2100c25845bfdb52de4700aed7">OffsetInParent</a>, <a href="#aed9833844c86541361110c19424d8c2f">Parent</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a219e1c40234502e0850ea8f378e2f192">SizeOf</a>, <a href="#af09751a4aec4e5d3323d59b713c8ca4a">Symbol</a> and <a href="#aa9133332d2b710957ef0836de8286073">UsedBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#a93c4e1b8420517136bbb2f5d6a9af796">llvm::pdb::UDTLayoutBase::addChildToLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/datamemberlayoutitem/#a178a9e728b70cd289c3f491283b3164b">llvm::pdb::DataMemberLayoutItem::DataMemberLayoutItem</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#a6934c477e5a494595fc2c8673e3c079e">llvm::pdb::UDTLayoutBase::tailPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#aea075f4ad0ba0b34107add3c46cf9664">llvm::pdb::UDTLayoutBase::UDTLayoutBase</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/vbptrlayoutitem/#a0113631d833f38b765ff515d11693ac4">llvm::pdb::VBPtrLayoutItem::VBPtrLayoutItem</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/vtablelayoutitem/#aa3300b9c44d96281bad0d1ca6659fe80">llvm::pdb::VTableLayoutItem::VTableLayoutItem</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LayoutItemBase() {#a2ce1a2370856fd157314b71d2ba7ab7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::pdb::LayoutItemBase::~LayoutItemBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### containsOffset() {#a6d76278f711394aad50f5590822df66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::LayoutItemBase::containsOffset (uint32_t Off)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>References <a href="#a650f01b775ec9ed10bb5f2e40196ba8d">getOffsetInParent</a> and <a href="#a3a31586f6cfca2197df724b439551b91">getSize</a>.</p>

</div>
</div>

### deepPaddingSize() {#a492f7b33957eb4402f058a6e90af346c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LayoutItemBase::deepPaddingSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>Reference <a href="#aa9133332d2b710957ef0836de8286073">UsedBytes</a>.</p>

</div>
</div>

### getLayoutSize() {#a8b0de0f4efe2019cf67ef2853e67fb2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::LayoutItemBase::getLayoutSize ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#af33f2369fa87c3fe25cce0a4c591e4a1">LayoutSize</a>.</p>

</div>
</div>

### getName() {#a35f8076437782a6719e4c8eeadcb6c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::pdb::LayoutItemBase::getName ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#ad10bda87163f7abb0fc4d862c66d8c06">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout/#a0af95a3e920db1df1dc61fb5685622be">llvm::pdb::BaseClassLayout::BaseClassLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/classlayout/#a7d3ca0c21b9d442d938cde435fb33cb0">llvm::pdb::ClassLayout::ClassLayout</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/datamemberlayoutitem/#a178a9e728b70cd289c3f491283b3164b">llvm::pdb::DataMemberLayoutItem::DataMemberLayoutItem</a>.</p>

</div>
</div>

### getOffsetInParent() {#a650f01b775ec9ed10bb5f2e40196ba8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::LayoutItemBase::getOffsetInParent ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#a1b003a2100c25845bfdb52de4700aed7">OffsetInParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#a93c4e1b8420517136bbb2f5d6a9af796">llvm::pdb::UDTLayoutBase::addChildToLayout</a> and <a href="#a6d76278f711394aad50f5590822df66c">containsOffset</a>.</p>

</div>
</div>

### getParent() {#ad17df02fb67e74f3b29d21803b57ca6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UDTLayoutBase * llvm::pdb::LayoutItemBase::getParent ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#aed9833844c86541361110c19424d8c2f">Parent</a>.</p>

</div>
</div>

### getSize() {#a3a31586f6cfca2197df724b439551b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::LayoutItemBase::getSize ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#a219e1c40234502e0850ea8f378e2f192">SizeOf</a>.</p>


<p>Referenced by <a href="#a6d76278f711394aad50f5590822df66c">containsOffset</a>.</p>

</div>
</div>

### getSymbol() {#a184c9e2209297e2453566e51ed35c26f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PDBSymbol * llvm::pdb::LayoutItemBase::getSymbol ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#af09751a4aec4e5d3323d59b713c8ca4a">Symbol</a>.</p>

</div>
</div>

### immediatePadding() {#ac4e549b6ff6558ad52e0f8e0289bf499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint32_t llvm::pdb::LayoutItemBase::immediatePadding ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>

</div>
</div>

### isElided() {#ad78b974c055ef8c95054bd02c9f016ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::pdb::LayoutItemBase::isElided ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#af036e1dfe92e3a19a805b255ac43848a">IsElided</a>.</p>

</div>
</div>

### isVBPtr() {#a512ca6c2c3b257211ab6b775c891c5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::pdb::LayoutItemBase::isVBPtr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>

</div>
</div>

### tailPadding() {#a47cb3d653556d34f95405f1bdf9361b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LayoutItemBase::tailPadding ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a> and <a href="#aa9133332d2b710957ef0836de8286073">UsedBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#a6934c477e5a494595fc2c8673e3c079e">llvm::pdb::UDTLayoutBase::tailPadding</a>.</p>

</div>
</div>

### usedBytes() {#a4bc071fe28aaf963b93231e1ad87acd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector &amp; llvm::pdb::LayoutItemBase::usedBytes ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#aa9133332d2b710957ef0836de8286073">UsedBytes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### IsElided {#af036e1dfe92e3a19a805b255ac43848a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::pdb::LayoutItemBase::IsElided = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#ad78b974c055ef8c95054bd02c9f016ef">isElided</a>, <a href="#ad0e63790f73f9608f8ba426cb98178bc">LayoutItemBase</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#aea075f4ad0ba0b34107add3c46cf9664">llvm::pdb::UDTLayoutBase::UDTLayoutBase</a>.</p>

</div>
</div>

### LayoutSize {#af33f2369fa87c3fe25cce0a4c591e4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::LayoutItemBase::LayoutSize = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#a8b0de0f4efe2019cf67ef2853e67fb2a">getLayoutSize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#ad34ca12f73439d9092237a6fc01fefa0">llvm::pdb::UDTLayoutBase::initializeChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout/#a06fc9cec87e8a2d0271aae057d20390d">llvm::pdb::BaseClassLayout::isEmptyBase</a>, <a href="#ad0e63790f73f9608f8ba426cb98178bc">LayoutItemBase</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#aea075f4ad0ba0b34107add3c46cf9664">llvm::pdb::UDTLayoutBase::UDTLayoutBase</a>.</p>

</div>
</div>

### Name {#ad10bda87163f7abb0fc4d862c66d8c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::pdb::LayoutItemBase::Name</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#a35f8076437782a6719e4c8eeadcb6c07">getName</a>, <a href="#ad0e63790f73f9608f8ba426cb98178bc">LayoutItemBase</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#aea075f4ad0ba0b34107add3c46cf9664">llvm::pdb::UDTLayoutBase::UDTLayoutBase</a>.</p>

</div>
</div>

### OffsetInParent {#a1b003a2100c25845bfdb52de4700aed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::LayoutItemBase::OffsetInParent = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout/#a0af95a3e920db1df1dc61fb5685622be">llvm::pdb::BaseClassLayout::BaseClassLayout</a>, <a href="#a650f01b775ec9ed10bb5f2e40196ba8d">getOffsetInParent</a>, <a href="#ad0e63790f73f9608f8ba426cb98178bc">LayoutItemBase</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#aea075f4ad0ba0b34107add3c46cf9664">llvm::pdb::UDTLayoutBase::UDTLayoutBase</a>.</p>

</div>
</div>

### Parent {#aed9833844c86541361110c19424d8c2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UDTLayoutBase* llvm::pdb::LayoutItemBase::Parent = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout/#a0af95a3e920db1df1dc61fb5685622be">llvm::pdb::BaseClassLayout::BaseClassLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/datamemberlayoutitem/#a178a9e728b70cd289c3f491283b3164b">llvm::pdb::DataMemberLayoutItem::DataMemberLayoutItem</a>, <a href="#ad17df02fb67e74f3b29d21803b57ca6c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#ad34ca12f73439d9092237a6fc01fefa0">llvm::pdb::UDTLayoutBase::initializeChildren</a>, <a href="#ad0e63790f73f9608f8ba426cb98178bc">LayoutItemBase</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#aea075f4ad0ba0b34107add3c46cf9664">llvm::pdb::UDTLayoutBase::UDTLayoutBase</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/vbptrlayoutitem/#a0113631d833f38b765ff515d11693ac4">llvm::pdb::VBPtrLayoutItem::VBPtrLayoutItem</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/vtablelayoutitem/#aa3300b9c44d96281bad0d1ca6659fe80">llvm::pdb::VTableLayoutItem::VTableLayoutItem</a>.</p>

</div>
</div>

### SizeOf {#a219e1c40234502e0850ea8f378e2f192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::LayoutItemBase::SizeOf = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/classlayout/#a7d3ca0c21b9d442d938cde435fb33cb0">llvm::pdb::ClassLayout::ClassLayout</a>, <a href="#a3a31586f6cfca2197df724b439551b91">getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/classlayout/#a3236487333ddd2215d1c696086115b16">llvm::pdb::ClassLayout::immediatePadding</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout/#a06fc9cec87e8a2d0271aae057d20390d">llvm::pdb::BaseClassLayout::isEmptyBase</a> and <a href="#ad0e63790f73f9608f8ba426cb98178bc">LayoutItemBase</a>.</p>

</div>
</div>

### Symbol {#af09751a4aec4e5d3323d59b713c8ca4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PDBSymbol* llvm::pdb::LayoutItemBase::Symbol = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/datamemberlayoutitem/#a091b96a1b8783652329a3925ef98fab6">llvm::pdb::DataMemberLayoutItem::getDataMember</a>, <a href="#a184c9e2209297e2453566e51ed35c26f">getSymbol</a> and <a href="#ad0e63790f73f9608f8ba426cb98178bc">LayoutItemBase</a>.</p>

</div>
</div>

### UsedBytes {#aa9133332d2b710957ef0836de8286073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::pdb::LayoutItemBase::UsedBytes</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#a93c4e1b8420517136bbb2f5d6a9af796">llvm::pdb::UDTLayoutBase::addChildToLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout/#a0af95a3e920db1df1dc61fb5685622be">llvm::pdb::BaseClassLayout::BaseClassLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/datamemberlayoutitem/#a178a9e728b70cd289c3f491283b3164b">llvm::pdb::DataMemberLayoutItem::DataMemberLayoutItem</a>, <a href="#a492f7b33957eb4402f058a6e90af346c">deepPaddingSize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#ad34ca12f73439d9092237a6fc01fefa0">llvm::pdb::UDTLayoutBase::initializeChildren</a>, <a href="#ad0e63790f73f9608f8ba426cb98178bc">LayoutItemBase</a>, <a href="#a47cb3d653556d34f95405f1bdf9361b5">tailPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#aea075f4ad0ba0b34107add3c46cf9664">llvm::pdb::UDTLayoutBase::UDTLayoutBase</a> and <a href="#a4bc071fe28aaf963b93231e1ad87acd5">usedBytes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
