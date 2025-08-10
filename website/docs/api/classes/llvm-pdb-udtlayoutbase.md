---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/udtlayoutbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `UDTLayoutBase` Class



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::UDTLayoutBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">llvm/DebugInfo/PDB/UDTLayout.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase">LayoutItemBase</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout">BaseClassLayout</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/classlayout">ClassLayout</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab49982b3060eeec7578338d4825b5812">UniquePtrVector</a> = std::vector&lt; std::unique_ptr&lt; T &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea075f4ad0ba0b34107add3c46cf9664">UDTLayoutBase</a> (const UDTLayoutBase *Parent, const PDBSymbol &amp;Sym, const std::string &amp;Name, uint32_t OffsetInParent, uint32_t Size, bool IsElided)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6934c477e5a494595fc2c8673e3c079e">tailPadding</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase">LayoutItemBase</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f6057417e7e19058aeb83d7034185f">layout_items</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout">BaseClassLayout</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a205680dc619ec0105cd2318ea4eebe1d">bases</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout">BaseClassLayout</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22cd580369a004940519a7b7be7d7d15">regular_bases</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout">BaseClassLayout</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c265a8220ac43d769ef36f63e37c82">virtual_bases</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad541a6ee1f35e593fbaf50fa23285d4f">directVirtualBaseCount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolfunc">PDBSymbolFunc</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846d1e4a216d17a078dbc222ae2e2182">funcs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424ac1f50be7552ee87142bfbc9afb00">other_items</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22763a1e0237a92357300c0691d1c816">hasVBPtrAtOffset</a> (uint32_t Off) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a> (const PDBSymbol &amp;Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c4e1b8420517136bbb2f5d6a9af796">addChildToLayout</a> (std::unique_ptr&lt; LayoutItemBase &gt; Child)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3494c6cd742caabc3106830f57c7b117">DirectVBaseCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">UniquePtrVector&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6352455e1b59d422a185ddb04dd2ed87">Other</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">UniquePtrVector&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolfunc">PDBSymbolFunc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31330f2bead61a10072e12257f26538">Funcs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">UniquePtrVector&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase">LayoutItemBase</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5628bdc800f33c2d8383fefc6f2dfaf">ChildStorage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase">LayoutItemBase</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47316094be098cd74eb3e4b1504c4738">LayoutItems</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout">BaseClassLayout</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd663483b6074d59c2d75f982c104878">AllBases</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout">BaseClassLayout</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf0f38a76a1c0171e4ba01b1fe662d41">NonVirtualBases</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout">BaseClassLayout</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a85b428c9aa931c45df6423d74655da">VirtualBases</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/vtablelayoutitem">VTableLayoutItem</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3470c00f65da79d3681ca5f34b93e55">VTable</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/vbptrlayoutitem">VBPtrLayoutItem</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5d37f0553ed32d48eae43729b0974a">VBPtr</a> = nullptr</td>
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


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### UniquePtrVector {#ab49982b3060eeec7578338d4825b5812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::pdb::UDTLayoutBase::UniquePtrVector =  std::vector&lt;std::unique_ptr&lt;T&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### UDTLayoutBase() {#aea075f4ad0ba0b34107add3c46cf9664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UDTLayoutBase::UDTLayoutBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase">UDTLayoutBase</a> * Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &amp; Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Name, uint32_t OffsetInParent, uint32_t Size, bool IsElided)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>References <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#af036e1dfe92e3a19a805b255ac43848a">llvm::pdb::LayoutItemBase::IsElided</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#ad0e63790f73f9608f8ba426cb98178bc">llvm::pdb::LayoutItemBase::LayoutItemBase</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#af33f2369fa87c3fe25cce0a4c591e4a1">llvm::pdb::LayoutItemBase::LayoutSize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#ad10bda87163f7abb0fc4d862c66d8c06">llvm::pdb::LayoutItemBase::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#a1b003a2100c25845bfdb52de4700aed7">llvm::pdb::LayoutItemBase::OffsetInParent</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#aed9833844c86541361110c19424d8c2f">llvm::pdb::LayoutItemBase::Parent</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#aea075f4ad0ba0b34107add3c46cf9664">UDTLayoutBase</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#aa9133332d2b710957ef0836de8286073">llvm::pdb::LayoutItemBase::UsedBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/baseclasslayout/#a0af95a3e920db1df1dc61fb5685622be">llvm::pdb::BaseClassLayout::BaseClassLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/classlayout/#a7d3ca0c21b9d442d938cde435fb33cb0">llvm::pdb::ClassLayout::ClassLayout</a> and <a href="#aea075f4ad0ba0b34107add3c46cf9664">UDTLayoutBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### bases() {#a205680dc619ec0105cd2318ea4eebe1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; BaseClassLayout * &gt; llvm::pdb::UDTLayoutBase::bases ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#abd663483b6074d59c2d75f982c104878">AllBases</a>.</p>

</div>
</div>

### directVirtualBaseCount() {#ad541a6ee1f35e593fbaf50fa23285d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::UDTLayoutBase::directVirtualBaseCount ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#a3494c6cd742caabc3106830f57c7b117">DirectVBaseCount</a>.</p>

</div>
</div>

### funcs() {#a846d1e4a216d17a078dbc222ae2e2182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::unique_ptr&lt; PDBSymbolFunc &gt; &gt; llvm::pdb::UDTLayoutBase::funcs ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#ad31330f2bead61a10072e12257f26538">Funcs</a>.</p>

</div>
</div>

### layout\_items() {#a56f6057417e7e19058aeb83d7034185f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; LayoutItemBase * &gt; llvm::pdb::UDTLayoutBase::layout_items ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#a47316094be098cd74eb3e4b1504c4738">LayoutItems</a>.</p>

</div>
</div>

### other\_items() {#a424ac1f50be7552ee87142bfbc9afb00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::unique_ptr&lt; PDBSymbol &gt; &gt; llvm::pdb::UDTLayoutBase::other_items ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#a6352455e1b59d422a185ddb04dd2ed87">Other</a>.</p>

</div>
</div>

### regular\_bases() {#a22cd580369a004940519a7b7be7d7d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; BaseClassLayout * &gt; llvm::pdb::UDTLayoutBase::regular_bases ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#adf0f38a76a1c0171e4ba01b1fe662d41">NonVirtualBases</a>.</p>

</div>
</div>

### tailPadding() {#a6934c477e5a494595fc2c8673e3c079e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t UDTLayoutBase::tailPadding ()</td>
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



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#ad0e63790f73f9608f8ba426cb98178bc">llvm::pdb::LayoutItemBase::LayoutItemBase</a>, <a href="#a47316094be098cd74eb3e4b1504c4738">LayoutItems</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#a47cb3d653556d34f95405f1bdf9361b5">llvm::pdb::LayoutItemBase::tailPadding</a>.</p>

</div>
</div>

### virtual\_bases() {#a17c265a8220ac43d769ef36f63e37c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; BaseClassLayout * &gt; llvm::pdb::UDTLayoutBase::virtual_bases ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Reference <a href="#a0a85b428c9aa931c45df6423d74655da">VirtualBases</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addChildToLayout() {#a93c4e1b8420517136bbb2f5d6a9af796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UDTLayoutBase::addChildToLayout (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase">LayoutItemBase</a> &gt; Child)</td>
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



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>References <a href="#ad5628bdc800f33c2d8383fefc6f2dfaf">ChildStorage</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a568ff706b8c5991bd299c8c00b803897">llvm::BitVector::count</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#a650f01b775ec9ed10bb5f2e40196ba8d">llvm::pdb::LayoutItemBase::getOffsetInParent</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#ad0e63790f73f9608f8ba426cb98178bc">llvm::pdb::LayoutItemBase::LayoutItemBase</a>, <a href="#a47316094be098cd74eb3e4b1504c4738">LayoutItems</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a32859a24aa7a3be269855b989d92a4b4">llvm::BitVector::resize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b7d2ab11554bd10d15b6cb21b2c2787">llvm::upper_bound</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#aa9133332d2b710957ef0836de8286073">llvm::pdb::LayoutItemBase::UsedBytes</a>.</p>


<p>Referenced by <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a>.</p>

</div>
</div>

### hasVBPtrAtOffset() {#a22763a1e0237a92357300c0691d1c816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UDTLayoutBase::hasVBPtrAtOffset (uint32_t Off)</td>
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



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>References <a href="#abd663483b6074d59c2d75f982c104878">AllBases</a> and <a href="#aee5d37f0553ed32d48eae43729b0974a">VBPtr</a>.</p>


<p>Referenced by <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a>.</p>

</div>
</div>

### initializeChildren() {#ad34ca12f73439d9092237a6fc01fefa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UDTLayoutBase::initializeChildren (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &amp; Sym)</td>
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



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>References <a href="#a93c4e1b8420517136bbb2f5d6a9af796">addChildToLayout</a>, <a href="#abd663483b6074d59c2d75f982c104878">AllBases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30baf6068daa29dbb05a7ead1e3b5a48bbee">llvm::pdb::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#abbb93ba85eff4d25fd4c3919fddd779c">DM</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a84de898fb71434cbc866dde23a5b68f4">llvm::pdb::PDBSymbol::findAllChildren</a>, <a href="#ad31330f2bead61a10072e12257f26538">Funcs</a>, <a href="#a22763a1e0237a92357300c0691d1c816">hasVBPtrAtOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#af33f2369fa87c3fe25cce0a4c591e4a1">llvm::pdb::LayoutItemBase::LayoutSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a6bb7bf8c85135f7a1ff129776219989ea858ba4765e53c712ef672a9570474b1d">llvm::pdb::Member</a>, <a href="#adf0f38a76a1c0171e4ba01b1fe662d41">NonVirtualBases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>, <a href="#a6352455e1b59d422a185ddb04dd2ed87">Other</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#aed9833844c86541361110c19424d8c2f">llvm::pdb::LayoutItemBase::Parent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a185bf56567058b34163a0b8d156028e9">llvm::unique_dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/layoutitembase/#aa9133332d2b710957ef0836de8286073">llvm::pdb::LayoutItemBase::UsedBytes</a>, <a href="#aee5d37f0553ed32d48eae43729b0974a">VBPtr</a>, <a href="#a0a85b428c9aa931c45df6423d74655da">VirtualBases</a> and <a href="#ad3470c00f65da79d3681ca5f34b93e55">VTable</a>.</p>


<p>Referenced by <a href="#aea075f4ad0ba0b34107add3c46cf9664">UDTLayoutBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AllBases {#abd663483b6074d59c2d75f982c104878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BaseClassLayout *&gt; llvm::pdb::UDTLayoutBase::AllBases</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#a205680dc619ec0105cd2318ea4eebe1d">bases</a>, <a href="#a22763a1e0237a92357300c0691d1c816">hasVBPtrAtOffset</a> and <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a>.</p>

</div>
</div>

### ChildStorage {#ad5628bdc800f33c2d8383fefc6f2dfaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniquePtrVector&lt;LayoutItemBase&gt; llvm::pdb::UDTLayoutBase::ChildStorage</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#a93c4e1b8420517136bbb2f5d6a9af796">addChildToLayout</a>.</p>

</div>
</div>

### DirectVBaseCount {#a3494c6cd742caabc3106830f57c7b117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::pdb::UDTLayoutBase::DirectVBaseCount = 0</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#ad541a6ee1f35e593fbaf50fa23285d4f">directVirtualBaseCount</a>.</p>

</div>
</div>

### Funcs {#ad31330f2bead61a10072e12257f26538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniquePtrVector&lt;PDBSymbolFunc&gt; llvm::pdb::UDTLayoutBase::Funcs</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#a846d1e4a216d17a078dbc222ae2e2182">funcs</a> and <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a>.</p>

</div>
</div>

### LayoutItems {#a47316094be098cd74eb3e4b1504c4738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;LayoutItemBase *&gt; llvm::pdb::UDTLayoutBase::LayoutItems</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#a93c4e1b8420517136bbb2f5d6a9af796">addChildToLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/classlayout/#a7d3ca0c21b9d442d938cde435fb33cb0">llvm::pdb::ClassLayout::ClassLayout</a>, <a href="#a56f6057417e7e19058aeb83d7034185f">layout_items</a> and <a href="#a6934c477e5a494595fc2c8673e3c079e">tailPadding</a>.</p>

</div>
</div>

### NonVirtualBases {#adf0f38a76a1c0171e4ba01b1fe662d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;BaseClassLayout *&gt; llvm::pdb::UDTLayoutBase::NonVirtualBases</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a> and <a href="#a22cd580369a004940519a7b7be7d7d15">regular_bases</a>.</p>

</div>
</div>

### Other {#a6352455e1b59d422a185ddb04dd2ed87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniquePtrVector&lt;PDBSymbol&gt; llvm::pdb::UDTLayoutBase::Other</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/classlayout/#ad16fc5353124328a4185b59491fe0dfa">llvm::pdb::ClassLayout::ClassLayout</a>, <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a> and <a href="#a424ac1f50be7552ee87142bfbc9afb00">other_items</a>.</p>

</div>
</div>

### VBPtr {#aee5d37f0553ed32d48eae43729b0974a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VBPtrLayoutItem* llvm::pdb::UDTLayoutBase::VBPtr = nullptr</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#a22763a1e0237a92357300c0691d1c816">hasVBPtrAtOffset</a> and <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a>.</p>

</div>
</div>

### VirtualBases {#a0a85b428c9aa931c45df6423d74655da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;BaseClassLayout *&gt; llvm::pdb::UDTLayoutBase::VirtualBases</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a> and <a href="#a17c265a8220ac43d769ef36f63e37c82">virtual_bases</a>.</p>

</div>
</div>

### VTable {#ad3470c00f65da79d3681ca5f34b93e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VTableLayoutItem* llvm::pdb::UDTLayoutBase::VTable = nullptr</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">UDTLayout.h</a>.</p>


<p>Referenced by <a href="#ad34ca12f73439d9092237a6fc01fefa0">initializeChildren</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
