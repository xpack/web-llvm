---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/castinfo-db4f59cb616dd1b49786c906cf5bbd9b
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CastInfo` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename To, typename... PTs&gt;
struct llvm::CastInfo&lt;To, PointerUnion&lt; PTs... &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">llvm/ADT/PointerUnion.h</a>"
</div>

## Base structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/castispossible">CastIsPossible&lt;To, From, Enable&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This struct provides a way to check if a given cast is possible. <a href="/web-llvm/docs/api/structs/llvm/castispossible/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/defaultdocastifpossible">DefaultDoCastIfPossible&lt;To, From, Derived&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This cast trait just provides the default implementation of doCastIfPossible to make <a href="/web-llvm/docs/api/structs/llvm/castinfo">CastInfo</a> specializations more declarative. <a href="/web-llvm/docs/api/structs/llvm/defaultdocastifpossible/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5ecd3ed35a6e3ce312ba5ba932b78ee6">From</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; PTs... &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae276181390e997262e925095a6bd9406">Impl</a> = <a href="/web-llvm/docs/api/structs/llvm/castinfopointerunionimpl">CastInfoPointerUnionImpl</a>&lt; PTs... &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/castinfo/#a694f5e7233cf55082a0ac75f3e0eabaf">Self</a> = <a href="/web-llvm/docs/api/structs/llvm/castinfo">CastInfo</a>&lt; To, <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; PTs... &gt;, void &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/castinfo/#a93bebb67e4960a08613dff9ecc05962c">CastReturnType</a> = typename <a href="/web-llvm/docs/api/structs/llvm/cast-retty">cast_retty</a>&lt; To, <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; PTs... &gt; &gt;::ret_type</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e8ae4ed18f91e78f9d002e4e86c6e72">isPossible</a> (From &amp;f)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static To</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd426648e3e22b14d4cc95d354e3b1aa">doCast</a> (From &amp;f)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static To</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c6fd508f53dbe616e1863a9cd08145c">castFailed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To, typename... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/castinfo/#a93bebb67e4960a08613dff9ecc05962c">CastReturnType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/castinfo/#a83d4b9f9263ad371a544f013ec863569">doCastIfPossible</a> (const PointerUnion&lt; PTs... &gt; &amp;f)</td>
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


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CastReturnType {#a93bebb67e4960a08613dff9ecc05962c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CastInfo&lt; To, PointerUnion&lt; PTs... &gt;, void &gt;::CastReturnType = </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>

</div>
</div>

### From {#a5ecd3ed35a6e3ce312ba5ba932b78ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CastInfo&lt; To, PointerUnion&lt; PTs... &gt; &gt;::From =  PointerUnion&lt;PTs...&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>

</div>
</div>

### Impl {#ae276181390e997262e925095a6bd9406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CastInfo&lt; To, PointerUnion&lt; PTs... &gt; &gt;::Impl =  CastInfoPointerUnionImpl&lt;PTs...&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>

</div>
</div>

### Self {#a694f5e7233cf55082a0ac75f3e0eabaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CastInfo&lt; To, PointerUnion&lt; PTs... &gt;, void &gt;::Self = </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### castFailed() {#a0c6fd508f53dbe616e1863a9cd08145c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">To llvm::CastInfo&lt; To, PointerUnion&lt; PTs... &gt; &gt;::castFailed ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>

</div>
</div>

### doCast() {#abd426648e3e22b14d4cc95d354e3b1aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">To llvm::CastInfo&lt; To, PointerUnion&lt; PTs... &gt; &gt;::doCast (<a href="#a5ecd3ed35a6e3ce312ba5ba932b78ee6">From</a> &amp; f)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/castinfo/#a143f6f757917e1245aed3882209b466f">llvm::CastInfo&lt; To, From, Enable &gt;::doCast</a>.</p>

</div>
</div>

### doCastIfPossible() {#a83d4b9f9263ad371a544f013ec863569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastReturnType llvm::CastInfo&lt; To, PointerUnion&lt; PTs... &gt;, void &gt;::doCastIfPossible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; PTs... &gt; &amp; f)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>

</div>
</div>

### isPossible() {#a2e8ae4ed18f91e78f9d002e4e86c6e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To, typename... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CastInfo&lt; To, PointerUnion&lt; PTs... &gt; &gt;::isPossible (<a href="#a5ecd3ed35a6e3ce312ba5ba932b78ee6">From</a> &amp; f)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/castispossible/#a44e6fa462c45ccec1dcb2e52901e055d">llvm::CastIsPossible&lt; To, From, Enable &gt;::isPossible</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
