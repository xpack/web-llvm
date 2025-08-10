---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/intervalmap/iterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `iterator` Class



## Declaration

<div class="doxyDeclaration">
class llvm::IntervalMap::iterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">llvm/ADT/IntervalMap.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae32700b4ef1b6867a06493d02ece123a">IdxPair</a> = <a href="/web-llvm/docs/api/namespaces/llvm/intervalmapimpl/#ab92974e292699af764f4bd02d1f44448">IntervalMapImpl::IdxPair</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae974639f12394e77cf9c059c6b064499">IntervalMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17e9125dae40d5e746c486f524056c1f">iterator</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>iterator - Create null iterator. <a href="#a17e9125dae40d5e746c486f524056c1f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33d85553aaa6dd2f878f5c48aaee6490">iterator</a> (IntervalMap &amp;map)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ac5b936169badf0b703567eb960278648">iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d39e7b0ab77b166377686adae5ea4fe">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ac5b936169badf0b703567eb960278648">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac040a53c837ba881f9958c11354f7cb4">operator++</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ac5b936169badf0b703567eb960278648">iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd69cead0145a5c1e5696124b8caa16b">operator--</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ac5b936169badf0b703567eb960278648">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347a8aaf18227a5334501061b2aab694">operator--</a> (int)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26702c94eead6ac6eac6da14b653d824">setStart</a> (KeyT a)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setStart - Move the start of the current interval. <a href="#a26702c94eead6ac6eac6da14b653d824">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84496bee4aead957e3193cfbe5ce3e8">setStop</a> (KeyT b)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setStop - Move the end of the current interval. <a href="#ae84496bee4aead957e3193cfbe5ce3e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c05bf6b202a8fe6d84f071b3b10ef9d">setValue</a> (ValT x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setValue - Change the mapped value of the current interval. <a href="#a6c05bf6b202a8fe6d84f071b3b10ef9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a878452ac67d0cdcdc91fbfa0dfc22618">setStartUnchecked</a> (KeyT a)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setStartUnchecked - Move the start of the current interval without checking for coalescing or overlaps. <a href="#a878452ac67d0cdcdc91fbfa0dfc22618">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5cd42ac53ce755ea03dc133ff9909af">setStopUnchecked</a> (KeyT b)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setStopUnchecked - Move the end of the current interval without checking for coalescing or overlaps. <a href="#af5cd42ac53ce755ea03dc133ff9909af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb691bb38afbd8c0007a69409d6967f">setValueUnchecked</a> (ValT x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setValueUnchecked - Change the mapped value of the current interval without checking for coalescing. <a href="#a0cb691bb38afbd8c0007a69409d6967f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ac0e9b32e19c2ba444dacfe1725098">insert</a> (KeyT a, KeyT b, ValT y)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insert - Insert mapping [a;b] -&gt; y before the current position. <a href="#a00ac0e9b32e19c2ba444dacfe1725098">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b0dc2d50cb2de5563983618a99af467">erase</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>erase - Erase the current interval. <a href="#a3b0dc2d50cb2de5563983618a99af467">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d0cc4de9e881dee1af8df4815ad062">setNodeStop</a> (unsigned Level, KeyT Stop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setNodeStop - Update the stop key of the current node at level and above. <a href="#a15d0cc4de9e881dee1af8df4815ad062">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0073eb3a1d4198adfd09174ea52eaf2c">insertNode</a> (unsigned Level, IntervalMapImpl::NodeRef Node, KeyT Stop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insertNode - insert a node before the current path at level. <a href="#a0073eb3a1d4198adfd09174ea52eaf2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83466cb8e676730b81498c3f5a4be41b">overflow</a> (unsigned Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>overflow - Distribute entries of the current node evenly among its siblings and ensure that the current node is not full. <a href="#a83466cb8e676730b81498c3f5a4be41b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dcb9d948dcfcc0b35eed548cf987d1a">treeInsert</a> (KeyT a, KeyT b, ValT y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352c260233c139cf1f3f054149061051">eraseNode</a> (unsigned Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>eraseNode - Erase the current node at Level from its parent and move path to the first entry of the next sibling node. <a href="#a352c260233c139cf1f3f054149061051">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae160146928c60c45322a371d122bb2c0">treeErase</a> (bool UpdateRoot=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>treeErase - <a href="#a3b0dc2d50cb2de5563983618a99af467">erase()</a> for a branched tree. <a href="#ae160146928c60c45322a371d122bb2c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f24918a4e500cf9c1b66d99da8900a">canCoalesceLeft</a> (KeyT Start, ValT x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>canCoalesceLeft - Can the current interval coalesce to the left after changing start or value? <a href="#a49f24918a4e500cf9c1b66d99da8900a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf1427680a09029a1bfc8ea8f723eb9a">canCoalesceRight</a> (KeyT Stop, ValT x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>canCoalesceRight - Can the current interval coalesce to the right after changing stop or value? <a href="#acf1427680a09029a1bfc8ea8f723eb9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### IdxPair {#ae32700b4ef1b6867a06493d02ece123a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::IdxPair =  IntervalMapImpl::IdxPair</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### IntervalMap {#ae974639f12394e77cf9c059c6b064499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#ae974639f12394e77cf9c059c6b064499">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::IntervalMap</a>.</p>


<p>Referenced by <a href="#a3b0dc2d50cb2de5563983618a99af467">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::erase</a>, <a href="#a00ac0e9b32e19c2ba444dacfe1725098">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::insert</a> and <a href="#ae974639f12394e77cf9c059c6b064499">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::IntervalMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### iterator() {#a17e9125dae40d5e746c486f524056c1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::iterator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>iterator - Create null iterator.</p>

<p>Definition at line 1590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### iterator() {#a33d85553aaa6dd2f878f5c48aaee6490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::iterator (<a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> &amp; map)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator--() {#afd69cead0145a5c1e5696124b8caa16b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator-- ()</td>
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



<p>Definition at line 1646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator/#ace4989cb01faf6a4cde20e40d7df8c0c">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator--</a>.</p>


<p>Referenced by <a href="#a347a8aaf18227a5334501061b2aab694">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator--</a>.</p>

</div>
</div>

### operator--() {#a347a8aaf18227a5334501061b2aab694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator-- (int)</td>
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



<p>Definition at line 1651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#afd69cead0145a5c1e5696124b8caa16b">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator--</a>.</p>

</div>
</div>

### operator++() {#a7d39e7b0ab77b166377686adae5ea4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator++ ()</td>
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



<p>Definition at line 1635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator/#a4b8573afd2c65e3391bfdd92e5c42d8d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator++</a>.</p>


<p>Referenced by <a href="#ac040a53c837ba881f9958c11354f7cb4">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator++</a>.</p>

</div>
</div>

### operator++() {#ac040a53c837ba881f9958c11354f7cb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator++ (int)</td>
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



<p>Definition at line 1640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#a7d39e7b0ab77b166377686adae5ea4fe">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### erase() {#a3b0dc2d50cb2de5563983618a99af467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::erase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>erase - Erase the current interval.</p>


<p>erase - erase the current interval and move to the next position.</p>


<p>Definition at line 1633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase/#a01bdf3dc12c07694d5f64d8a83dc21f5">llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::erase</a>, <a href="#ae974639f12394e77cf9c059c6b064499">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::IntervalMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### insert() {#a00ac0e9b32e19c2ba444dacfe1725098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::insert (KeyT a, KeyT b, ValT y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>insert - Insert mapping [a;b] -&gt; y before the current position.</p>

<p>Definition at line 1630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase/#a3928712e3203651240c884c838274d16">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, N &gt;::Capacity</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode/#ab0bd3e9464208516b824137ed7c70644">llvm::IntervalMapImpl::LeafNode&lt; KeyT, ValT, N, Traits &gt;::insertFrom</a>, <a href="#ae974639f12394e77cf9c059c6b064499">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::IntervalMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a7b5a03b19133c790a4d6fff66a5d2135">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::Size</a>.</p>

</div>
</div>

### setStart() {#a26702c94eead6ac6eac6da14b653d824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStart (KeyT a)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setStart - Move the start of the current interval.</p>


<p>This may cause coalescing with the previous interval.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">a</td>
<td class="doxyParamItemDescription"><p>New start key, must not overlap the previous interval.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="#a878452ac67d0cdcdc91fbfa0dfc22618">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStartUnchecked</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#ad94606da831de9baa7df66b6c92953ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::start</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a43fd35cfdcd02e29805382e2d5dfedd3">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::stop</a>.</p>

</div>
</div>

### setStartUnchecked() {#a878452ac67d0cdcdc91fbfa0dfc22618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStartUnchecked (KeyT a)</td>
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

<p>setStartUnchecked - Move the start of the current interval without checking for coalescing or overlaps.</p>


<p>This should only be used when it is known that coalescing is not required.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">a</td>
<td class="doxyParamItemDescription"><p>New start key.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a26702c94eead6ac6eac6da14b653d824">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStart</a>, <a href="#ae84496bee4aead957e3193cfbe5ce3e8">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStop</a> and <a href="#a6c05bf6b202a8fe6d84f071b3b10ef9d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setValue</a>.</p>

</div>
</div>

### setStop() {#ae84496bee4aead957e3193cfbe5ce3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStop (KeyT b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setStop - Move the end of the current interval.</p>


<p>This may cause coalescing with the following interval.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">b</td>
<td class="doxyParamItemDescription"><p>New stop key, must not overlap the following interval.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="#a878452ac67d0cdcdc91fbfa0dfc22618">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStartUnchecked</a>, <a href="#af5cd42ac53ce755ea03dc133ff9909af">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStopUnchecked</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#ad94606da831de9baa7df66b6c92953ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::start</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a43fd35cfdcd02e29805382e2d5dfedd3">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::stop</a>.</p>

</div>
</div>

### setStopUnchecked() {#af5cd42ac53ce755ea03dc133ff9909af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStopUnchecked (KeyT b)</td>
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

<p>setStopUnchecked - Move the end of the current interval without checking for coalescing or overlaps.</p>


<p>This should only be used when it is known that coalescing is not required.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">b</td>
<td class="doxyParamItemDescription"><p>New stop key.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#ae84496bee4aead957e3193cfbe5ce3e8">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStop</a>.</p>

</div>
</div>

### setValue() {#a6c05bf6b202a8fe6d84f071b3b10ef9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setValue (ValT x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setValue - Change the mapped value of the current interval.</p>


<p>This may cause coalescing with the previous and following intervals.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">x</td>
<td class="doxyParamItemDescription"><p>New value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="#a878452ac67d0cdcdc91fbfa0dfc22618">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStartUnchecked</a>, <a href="#a0cb691bb38afbd8c0007a69409d6967f">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setValueUnchecked</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#ad94606da831de9baa7df66b6c92953ea">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::start</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a43fd35cfdcd02e29805382e2d5dfedd3">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::stop</a>.</p>

</div>
</div>

### setValueUnchecked() {#a0cb691bb38afbd8c0007a69409d6967f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setValueUnchecked (ValT x)</td>
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

<p>setValueUnchecked - Change the mapped value of the current interval without checking for coalescing.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">x</td>
<td class="doxyParamItemDescription"><p>New value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a6c05bf6b202a8fe6d84f071b3b10ef9d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canCoalesceLeft() {#a49f24918a4e500cf9c1b66d99da8900a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::canCoalesceLeft (KeyT Start, ValT Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>canCoalesceLeft - Can the current interval coalesce to the left after changing start or value?</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Start</td>
<td class="doxyParamItemDescription"><p>New start of current interval.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>New value for current interval.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True when updating the current interval would enable coalescing.</p></dd>
</dl>


<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### canCoalesceRight() {#acf1427680a09029a1bfc8ea8f723eb9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::canCoalesceRight (KeyT Stop, ValT Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>canCoalesceRight - Can the current interval coalesce to the right after changing stop or value?</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Stop</td>
<td class="doxyParamItemDescription"><p>New stop of current interval.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>New value for current interval.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True when updating the current interval would enable coalescing.</p></dd>
</dl>


<p>Definition at line 1586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### eraseNode() {#a352c260233c139cf1f3f054149061051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::eraseNode (unsigned Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>eraseNode - Erase the current node at Level from its parent and move path to the first entry of the next sibling node.</p>


<p>The node must be deallocated by the caller.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>1..height, the root node cannot be erased.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### insertNode() {#a0073eb3a1d4198adfd09174ea52eaf2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::insertNode (unsigned Level, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">IntervalMapImpl::NodeRef</a> Node, KeyT Stop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>insertNode - insert a node before the current path at level.</p>


<p>Leave the current path pointing at the new node.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>path index of the node to be inserted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/node"&gt;Node&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The node to be inserted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Stop</td>
<td class="doxyParamItemDescription"><p>The last index in the new node.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the tree height was increased.</p></dd>
</dl>


<p>Definition at line 1580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### overflow() {#a83466cb8e676730b81498c3f5a4be41b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::overflow (unsigned Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>overflow - Distribute entries of the current node evenly among its siblings and ensure that the current node is not full.</p>


<p>This may require allocating a new node.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Template Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NodeT</td>
<td class="doxyParamItemDescription"><p>The type of node at Level (Leaf or Branch).</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>path index of the overflowing node.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True when the tree height was changed.</p></dd>
</dl>


<p>Definition at line 1581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### setNodeStop() {#a15d0cc4de9e881dee1af8df4815ad062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setNodeStop (unsigned Level, KeyT Stop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setNodeStop - Update the stop key of the current node at level and above.</p>

<p>Definition at line 1579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### treeErase() {#ae160146928c60c45322a371d122bb2c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::treeErase (bool UpdateRoot=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>treeErase - <a href="#a3b0dc2d50cb2de5563983618a99af467">erase()</a> for a branched tree.</p>

<p>Definition at line 1584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### treeInsert() {#a8dcb9d948dcfcc0b35eed548cf987d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::treeInsert (KeyT a, KeyT b, ValT y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
