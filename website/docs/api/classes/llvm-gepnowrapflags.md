---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gepnowrapflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GEPNoWrapFlags` Class Reference

<p>Represents flags for the getelementptr instruction/expression. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GEPNoWrapFlags { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">llvm/IR/GEPNoWrapFlags.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#a64337223d549f6f23153faab7bf361fe">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965f8330743b3590e87497e02eb8d6da">GEPNoWrapFlags</a> (bool IsInBounds)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0e7dd3c9738f2d95448ba31c0219b30">GEPNoWrapFlags</a> (unsigned Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a002b2c935af62773d5da076bdffba7">operator==</a> (GEPNoWrapFlags Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9efdba9eb893aef23cf024f51a66968a">operator!=</a> (GEPNoWrapFlags Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab36532925b4a4fbf2c5688ddbc99257f">operator&amp;</a> (GEPNoWrapFlags Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac14e5a20580c88c7e575c7fa93800557">operator|</a> (GEPNoWrapFlags Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3da5c90b40bd4d438301a4ed36de9797">operator&amp;=</a> (GEPNoWrapFlags Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ce31d89fcaefbd46aedb64c94af93c">operator|=</a> (GEPNoWrapFlags Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20bc6c8c590c7a5e6eb9c9b1a64a0a9">getRaw</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaba6873d157dbd7f5f02da723e6ca78f">isInBounds</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992b9efb797f896ae2cc7f1d043eb68f">hasNoUnsignedSignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f5326edaaa9f5ad4e786d473b7c000a">hasNoUnsignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e10b257a139f9c78a04c3d7fb2f73e">withoutInBounds</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c93f80ea8da60e454d7596737b5c88">withoutNoUnsignedSignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd0ff795c450e59448a23dc04afdf3c8">withoutNoUnsignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca022065bc2e60a2b5d4d968ae400b8b">intersectForOffsetAdd</a> (GEPNoWrapFlags Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given (gep (gep p, x), y), determine the nowrap flags for (gep p, x+y). <a href="#aca022065bc2e60a2b5d4d968ae400b8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d571ae7b3f0737c7dac3f0e7405f52a">Flags</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad41d3c975038ec4a4fc791601729124e">none</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c411a616301bb93b1b04327a0c3123">all</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c32878bcc6e7bc1ac1e5fbcb1707591">inBounds</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a794ead7ef727f6a684c5695b27040c67">noUnsignedSignedWrap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bfde791508b16caf8509e95a8fdf7b9">noUnsignedWrap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a37d9e499f35c62e13457d1755eebf0">fromRaw</a> (unsigned Flags)</td>
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

<p>Represents flags for the getelementptr instruction/expression.</p>


<p>The following flags are supported:</p>


<ul class="doxyList ">
<li>inbounds (implies nusw)</li>
<li>nusw (no unsigned signed wrap)</li>
<li>nuw (no unsigned wrap) See LangRef for a description of their semantics.</li>
</ul>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a64337223d549f6f23153faab7bf361fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InBoundsFlag<a id="a64337223d549f6f23153faab7bf361feadc98421ad13522597af2bdc8a560b3ba"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NUSWFlag<a id="a64337223d549f6f23153faab7bf361feaab6147f715a9f51de384e1476c0b4ac1"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NUWFlag<a id="a64337223d549f6f23153faab7bf361fea0309d520e51283f4bf039d04b9d996ed"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 2))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GEPNoWrapFlags() {#a94d3a4101bfedbaaa645efa6ea06a189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GEPNoWrapFlags::GEPNoWrapFlags ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Referenced by <a href="#a54c411a616301bb93b1b04327a0c3123">all</a>, <a href="#a4a37d9e499f35c62e13457d1755eebf0">fromRaw</a>, <a href="#a0c32878bcc6e7bc1ac1e5fbcb1707591">inBounds</a>, <a href="#ad41d3c975038ec4a4fc791601729124e">none</a>, <a href="#a794ead7ef727f6a684c5695b27040c67">noUnsignedSignedWrap</a>, <a href="#a5bfde791508b16caf8509e95a8fdf7b9">noUnsignedWrap</a>, <a href="#ab36532925b4a4fbf2c5688ddbc99257f">operator&amp;</a>, <a href="#ac14e5a20580c88c7e575c7fa93800557">operator|</a>, <a href="#a43e10b257a139f9c78a04c3d7fb2f73e">withoutInBounds</a>, <a href="#a20c93f80ea8da60e454d7596737b5c88">withoutNoUnsignedSignedWrap</a> and <a href="#acd0ff795c450e59448a23dc04afdf3c8">withoutNoUnsignedWrap</a>.</p>

</div>
</div>

### GEPNoWrapFlags() {#a965f8330743b3590e87497e02eb8d6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GEPNoWrapFlags::GEPNoWrapFlags (bool IsInBounds)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### GEPNoWrapFlags() {#ab0e7dd3c9738f2d95448ba31c0219b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GEPNoWrapFlags::GEPNoWrapFlags (unsigned Flags)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a9efdba9eb893aef23cf024f51a66968a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPNoWrapFlags::operator!= (<a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> Other)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator&amp;() {#ab36532925b4a4fbf2c5688ddbc99257f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::operator&amp; (<a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> Other)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>References <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator&amp;=() {#a3da5c90b40bd4d438301a4ed36de9797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags &amp; llvm::GEPNoWrapFlags::operator&amp;= (<a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> Other)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a2a002b2c935af62773d5da076bdffba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPNoWrapFlags::operator== (<a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> Other)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator|() {#ac14e5a20580c88c7e575c7fa93800557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::operator| (<a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> Other)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>References <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator|=() {#a03ce31d89fcaefbd46aedb64c94af93c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags &amp; llvm::GEPNoWrapFlags::operator|= (<a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> Other)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRaw() {#af20bc6c8c590c7a5e6eb9c9b1a64a0a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GEPNoWrapFlags::getRaw ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aa0e2f7f2755f0a5cb30f1cc35957cb27">llvm::ConstantExpr::getGetElementPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#ae01c55fd5d6f0acb9228179a698c3cb3">llvm::GetElementPtrInst::setNoWrapFlags</a>.</p>

</div>
</div>

### hasNoUnsignedSignedWrap() {#a992b9efb797f896ae2cc7f1d043eb68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPNoWrapFlags::hasNoUnsignedSignedWrap ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a0f3039f831c483956c153ed9dee23dba">llvm::ScalarEvolution::getGEPExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a02a7ce64ac78b2de107d6726b64b71a0">llvm::GEPOperator::hasNoUnsignedSignedWrap</a>, <a href="#aca022065bc2e60a2b5d4d968ae400b8b">intersectForOffsetAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#ae8091058e59c9f50ccc4e482d112a808">mapToLLVMGEPNoWrapFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0aa7c68d8c3095ffc271ecceab16c86e">rewriteGEPAsOffset</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4fc5dce2b300d02414f7b8a99d93d300">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP</a>.</p>

</div>
</div>

### hasNoUnsignedWrap() {#a9f5326edaaa9f5ad4e786d473b7c000a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPNoWrapFlags::hasNoUnsignedWrap ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a0f3039f831c483956c153ed9dee23dba">llvm::ScalarEvolution::getGEPExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a5efdc1f8478ba644e2413b9c143dd46c">llvm::GEPOperator::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#ae8091058e59c9f50ccc4e482d112a808">mapToLLVMGEPNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a884253dce055eb76863ec81c061aef33">llvm::InstCombinerImpl::OptimizePointerDifference</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0aa7c68d8c3095ffc271ecceab16c86e">rewriteGEPAsOffset</a>.</p>

</div>
</div>

### intersectForOffsetAdd() {#aca022065bc2e60a2b5d4d968ae400b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::intersectForOffsetAdd (<a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a> Other)</td>
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

<p>Given (gep (gep p, x), y), determine the nowrap flags for (gep p, x+y).</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>References <a href="#a992b9efb797f896ae2cc7f1d043eb68f">hasNoUnsignedSignedWrap</a>, <a href="#aaba6873d157dbd7f5f02da723e6ca78f">isInBounds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a20c93f80ea8da60e454d7596737b5c88">withoutNoUnsignedSignedWrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9e6b15b1005dd460a35359f104cb06fe">canRewriteGEPAsOffset</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#afef6fefdb447008608fc826b31a49d28">getMergedGEPNoWrapFlags</a>.</p>

</div>
</div>

### isInBounds() {#aaba6873d157dbd7f5f02da723e6ca78f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPNoWrapFlags::isInBounds ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Referenced by <a href="#aca022065bc2e60a2b5d4d968ae400b8b">intersectForOffsetAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a3783a9756e9b9a1fe124622d27522713">llvm::GEPOperator::isInBounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#ae8091058e59c9f50ccc4e482d112a808">mapToLLVMGEPNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a884253dce055eb76863ec81c061aef33">llvm::InstCombinerImpl::OptimizePointerDifference</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4fc5dce2b300d02414f7b8a99d93d300">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP</a>.</p>

</div>
</div>

### withoutInBounds() {#a43e10b257a139f9c78a04c3d7fb2f73e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::withoutInBounds ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a837e9f272fd070a5f8fc79c07a951106">llvm::GetElementPtrInst::setIsInBounds</a>.</p>

</div>
</div>

### withoutNoUnsignedSignedWrap() {#a20c93f80ea8da60e454d7596737b5c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::withoutNoUnsignedSignedWrap ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a>.</p>


<p>Referenced by <a href="#aca022065bc2e60a2b5d4d968ae400b8b">intersectForOffsetAdd</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4fc5dce2b300d02414f7b8a99d93d300">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>.</p>

</div>
</div>

### withoutNoUnsignedWrap() {#acd0ff795c450e59448a23dc04afdf3c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::withoutNoUnsignedWrap ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Flags {#a3d571ae7b3f0737c7dac3f0e7405f52a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GEPNoWrapFlags::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### all() {#a54c411a616301bb93b1b04327a0c3123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::all ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a>.</p>

</div>
</div>

### fromRaw() {#a4a37d9e499f35c62e13457d1755eebf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::fromRaw (unsigned Flags)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a9f19d28f31c79215e0e0190115b0373d">llvm::GEPOperator::getNoWrapFlags</a>.</p>

</div>
</div>

### inBounds() {#a0c32878bcc6e7bc1ac1e5fbcb1707591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::inBounds ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5945995573939aabe8aa3ccea099b219">llvm::IRBuilderBase::CreateConstInBoundsGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abe7ccc68b743707443a07e60aedb2ba7">llvm::IRBuilderBase::CreateConstInBoundsGEP1_64</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa85037712ab4c5044582974769aa4b62">llvm::IRBuilderBase::CreateConstInBoundsGEP2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa8ee5dc4e4a1b26c4bdf1a574eefe2fc">llvm::IRBuilderBase::CreateConstInBoundsGEP2_64</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#aa1d295f380f20e10c5554de9307b681a">llvm::GetElementPtrInst::CreateInBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64b6c97b8faad5ec83f37d906fca7bc4">llvm::IRBuilderBase::CreateInBoundsGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad9b7f1f880f1c88e6856df87189d50f4">llvm::IRBuilderBase::CreateInBoundsPtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e95ff363c20e1f51b673230538e10fd">llvm::IRBuilderBase::CreateStructGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0fbdc8f9ebcc506b52a9f5c82feb363e">llvm::ConstantExpr::getInBoundsGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aa44c858fa0fa5820b7f47d0b3b31e422">llvm::ConstantExpr::getInBoundsGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ab908f67575336091b5a9d099ddf483bb">llvm::ConstantExpr::getInBoundsGetElementPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a25955c6933d48ad3e42ab747a1371aa8">mapFromLLVMGEPNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a837e9f272fd070a5f8fc79c07a951106">llvm::GetElementPtrInst::setIsInBounds</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4fc5dce2b300d02414f7b8a99d93d300">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a66c221eaf3589701aa0fa16c6cd61407">toGEPNoWrapFlags</a>.</p>

</div>
</div>

### none() {#ad41d3c975038ec4a4fc791601729124e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::none ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0ac085386a38b408b6ac75b1255aeb22">llvm::IRBuilderBase::CreateConstGEP1_64</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad36ec66444a025ac9f91b7f2e055f7e2">llvm::IRBuilderBase::CreateConstGEP2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e329d0cf4b01beeb722cae4ed919a83">llvm::IRBuilderBase::CreateConstGEP2_64</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5b416a8603ccb844165c8df22454ac05">llvm::IRBuilderBase::CreatePtrAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a3a288d8153f8bd74315b59636438d6e2">decomposeGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#a632a4f81f86235824e44d9a175d7c42d">llvm::VPRecipeWithIRFlags::dropPoisonGeneratingFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a0f3039f831c483956c153ed9dee23dba">llvm::ScalarEvolution::getGEPExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a938a05853c0079b8a3134e86433146b2">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/operator/#a7fe2763bf9a8bee996a114f061736dc7">llvm::Operator::hasPoisonGeneratingFlags</a> and <a href="/web-llvm/docs/api/structs/llvm/poisonflags/#a9bafefee99bbf3320fd4e5af1e487149">llvm::PoisonFlags::PoisonFlags</a>.</p>

</div>
</div>

### noUnsignedSignedWrap() {#a794ead7ef727f6a684c5695b27040c67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::noUnsignedSignedWrap ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a25955c6933d48ad3e42ab747a1371aa8">mapFromLLVMGEPNoWrapFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a66c221eaf3589701aa0fa16c6cd61407">toGEPNoWrapFlags</a>.</p>

</div>
</div>

### noUnsignedWrap() {#a5bfde791508b16caf8509e95a8fdf7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPNoWrapFlags::noUnsignedWrap ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a>.</p>


<p>Reference <a href="#a94d3a4101bfedbaaa645efa6ea06a189">GEPNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e95ff363c20e1f51b673230538e10fd">llvm::IRBuilderBase::CreateStructGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a25955c6933d48ad3e42ab747a1371aa8">mapFromLLVMGEPNoWrapFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4fc5dce2b300d02414f7b8a99d93d300">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a66c221eaf3589701aa0fa16c6cd61407">toGEPNoWrapFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gepnowrapflags-h">GEPNoWrapFlags.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
