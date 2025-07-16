---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/immutableset/factory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Factory` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ImmutableSet::Factory { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">llvm/ADT/ImmutableSet.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7c3f1fbf3b5b7f18eebea5efd90a1ef">Factory</a> (bool canonicalize=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab11838abd08ffa0a0fc64edded64981e">Factory</a> (BumpPtrAllocator &amp;Alloc, bool canonicalize=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a078de82c249187259375cf3c9f07905e">Factory</a> (const Factory &amp;RHS)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45158a210a9cfa80ac81487381804498">operator=</a> (const Factory &amp;RHS)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51e2cd257a3ee2c43a879fc311d621d">getEmptySet</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEmptySet - Returns an immutable set that contains no elements. <a href="#ad51e2cd257a3ee2c43a879fc311d621d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc2f64a137fe78f0be7a6b1254bd42d">add</a> (ImmutableSet Old, value_type_ref V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>add - Creates a new immutable set that contains all of the values of the original set with the addition of the specified value. <a href="#afbc2f64a137fe78f0be7a6b1254bd42d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1072e635625a2c8613ddb9610ee41d">remove</a> (ImmutableSet Old, value_type_ref V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>remove - Creates a new immutable set that contains all of the values of the original set with the exception of the specified value. <a href="#afb1072e635625a2c8613ddb9610ee41d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b378dcba3417899e29353b86991d2da">getAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a744e5bd7d0965b1bb1cbc5daa85263d7">TreeTy::Factory</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625bb9bffa428e2d0957e900872ad88b">getTreeFactory</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a744e5bd7d0965b1bb1cbc5daa85263d7">TreeTy::Factory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c146de6782af1908069a844e76e12d">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0257e7d2296c15c7b0e7bb7640b6c574">Canonicalize</a></td>
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


<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Factory() {#ae7c3f1fbf3b5b7f18eebea5efd90a1ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::Factory (bool canonicalize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Referenced by <a href="#a078de82c249187259375cf3c9f07905e">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::Factory</a> and <a href="#a45158a210a9cfa80ac81487381804498">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::operator=</a>.</p>

</div>
</div>

### Factory() {#ab11838abd08ffa0a0fc64edded64981e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::Factory (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc, bool canonicalize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>.</p>

</div>
</div>

### Factory() {#a078de82c249187259375cf3c9f07905e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::Factory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutableset/factory">Factory</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#ae7c3f1fbf3b5b7f18eebea5efd90a1ef">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::Factory</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a45158a210a9cfa80ac81487381804498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutableset/factory">Factory</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#ae7c3f1fbf3b5b7f18eebea5efd90a1ef">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::Factory</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#afbc2f64a137fe78f0be7a6b1254bd42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableSet llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::add (<a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a> Old, <a href="/web-llvm/docs/api/classes/llvm/immutableset/#af9d4d557fa1ad307d13311d54f960392">value_type_ref</a> V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>add - Creates a new immutable set that contains all of the values of the original set with the addition of the specified value.</p>


<p>If the original set already included the value, then the original set is returned and no memory is allocated. The time and space complexity of this operation is logarithmic in the size of the original set. The memory allocated to represent the set is released when the factory object that created the set is destroyed.</p>


<p>Definition at line 999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/immutableset/#a577937683fc13ab01a50897993da60af">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::ImmutableSet</a>.</p>

</div>
</div>

### getAllocator() {#a8b378dcba3417899e29353b86991d2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator &amp; llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::getAllocator ()</td>
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



<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### getEmptySet() {#ad51e2cd257a3ee2c43a879fc311d621d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableSet llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::getEmptySet ()</td>
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

<p>getEmptySet - Returns an immutable set that contains no elements.</p>

<p>Definition at line 988 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/immutableset/#a577937683fc13ab01a50897993da60af">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::ImmutableSet</a>.</p>

</div>
</div>

### getTreeFactory() {#a625bb9bffa428e2d0957e900872ad88b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy::Factory * llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::getTreeFactory ()</td>
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



<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### remove() {#afb1072e635625a2c8613ddb9610ee41d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableSet llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::remove (<a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a> Old, <a href="/web-llvm/docs/api/classes/llvm/immutableset/#af9d4d557fa1ad307d13311d54f960392">value_type_ref</a> V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>remove - Creates a new immutable set that contains all of the values of the original set with the exception of the specified value.</p>


<p>If the original set did not contain the value, the original set is returned and no memory is allocated. The time and space complexity of this operation is logarithmic in the size of the original set. The memory allocated to represent the set is released when the factory object that created the set is destroyed.</p>


<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/immutableset/#a577937683fc13ab01a50897993da60af">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::ImmutableSet</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Canonicalize {#a0257e7d2296c15c7b0e7bb7640b6c574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::Canonicalize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### F {#a36c146de6782af1908069a844e76e12d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy::Factory llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
