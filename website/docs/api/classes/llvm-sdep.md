---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sdep
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SDep` Class

<p>Scheduling dependency. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SDep { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">llvm/CodeGen/ScheduleDAG.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#a07333f8ba53e0454b7ec6365860c0732">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are the different kinds of scheduling dependencies. <a href="#a07333f8ba53e0454b7ec6365860c0732">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OrderKind { <a href="#a551060cb0333d9d0cfdacd2576d817b9">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b446ad86ee3581e0273ef2200d2585">SDep</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a null <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a>. <a href="#a98b446ad86ee3581e0273ef2200d2585">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdd24e7642b757dd8b2ec8345bd9bda3">SDep</a> (SUnit *S, Kind kind, unsigned Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> with the specified values. <a href="#afdd24e7642b757dd8b2ec8345bd9bda3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958610bfb8db5e45be0eb3a6d894f627">SDep</a> (SUnit *S, OrderKind kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7720d990f2e6a3baa82f1b33dfa6ea3f">operator==</a> (const SDep &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c65136860d5e2699a42e5da78cf16f">operator!=</a> (const SDep &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041210155b5dca8af4a22885222229ae">overlaps</a> (const SDep &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> is equivalent except for latency. <a href="#a041210155b5dca8af4a22885222229ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eca2019521fd47b79fe5ef66d02fd43">getLatency</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the latency value for this edge, which roughly means the minimum number of cycles that must elapse between the predecessor and the successor, given that they have this edge between them. <a href="#a5eca2019521fd47b79fe5ef66d02fd43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a148b76c8f993d4a3d95ac19c60e2ebe0">setLatency</a> (unsigned Lat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the latency for this edge. <a href="#a148b76c8f993d4a3d95ac19c60e2ebe0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03a2dc5f9f321a2ce28f5c641dfe5455">getSUnit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa4f7e2f3f5a23ecf19b98acd3c05593">setSUnit</a> (SUnit *SU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a07333f8ba53e0454b7ec6365860c0732">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an enum value representing the kind of the dependence. <a href="#a055c65558a3e0f7d48f1ed3dde061199">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4768ef4b1a0a2e8d50714b07465075">isCtrl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shorthand for <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind()</a> != <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">SDep::Data</a>. <a href="#a8b4768ef4b1a0a2e8d50714b07465075">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e4e5c8f7ea14d79ea03006d33dc393">isNormalMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this is an Order dependence between two memory accesses where both sides of the dependence access memory in non-volatile and fully modeled ways. <a href="#a74e4e5c8f7ea14d79ea03006d33dc393">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5c4f1ea353d427a527f548d6bae4593">isBarrier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this is an Order dependence that is marked as a barrier. <a href="#af5c4f1ea353d427a527f548d6bae4593">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ba62471316bc18e72fcab395fc7d71">isNormalMemoryOrBarrier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this is could be any kind of memory dependence. <a href="#af9ba62471316bc18e72fcab395fc7d71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3277eb7a4827c6a650eb49ea97796c">isMustAlias</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this is an Order dependence that is marked as "must alias", meaning that the SUnits at either end of the edge have a memory dependence on a known memory location. <a href="#aff3277eb7a4827c6a650eb49ea97796c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e3367f21a2b07ce6e344fc6a2ed078">isWeak</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this a weak dependence. <a href="#a21e3367f21a2b07ce6e344fc6a2ed078">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b245e9ae0e3d67d8485468580f360f">isArtificial</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this is an Order dependence that is marked as "artificial", meaning it isn't necessary for correctness. <a href="#a75b245e9ae0e3d67d8485468580f360f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a5a158ff2d2bbbadae7accc72e7c51">isCluster</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this is an Order dependence that is marked as "cluster", meaning it is artificial and wants to be adjacent. <a href="#ac2a5a158ff2d2bbbadae7accc72e7c51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c89ab9b69b3bcaa536702845fd9542d">isAssignedRegDep</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this is a Data dependence that is associated with a register. <a href="#a6c89ab9b69b3bcaa536702845fd9542d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b51361656ac436c2c02a20e6196cff1">getReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the register associated with this edge. <a href="#a8b51361656ac436c2c02a20e6196cff1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2e01668fae870af7bc0679edd4335c5">setReg</a> (unsigned Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assigns the associated register for this edge. <a href="#ad2e01668fae870af7bc0679edd4335c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace1019e8cefb80490348369f12fe0a44">dump</a> (const TargetRegisterInfo *TRI=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a6528b6785d72ed8ec4a8f486ee78d">Reg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For Data, Anti, and Output dependencies, the associated register. <a href="#ab0a6528b6785d72ed8ec4a8f486ee78d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad1b55cd1da72f5229dd7a0378ca99e">OrdKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Additional information about Order dependencies. <a href="#a5ad1b55cd1da72f5229dd7a0378ca99e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, 2, <a href="#a07333f8ba53e0454b7ec6365860c0732">Kind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e12919ba475b02a0df53607999a6827">Dep</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pointer to the depending/depended-on <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>, and an enum indicating the kind of the dependency. <a href="#a5e12919ba475b02a0df53607999a6827">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/sdep">llvm::SDep</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7172b55fe082aa0f99d5ff30ed65065">Contents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A union discriminated by the dependence kind. <a href="#ad7172b55fe082aa0f99d5ff30ed65065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d4d94718345301a04e931f1b156cf7c">Latency</a> = 0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The time associated with this edge. <a href="#a6d4d94718345301a04e931f1b156cf7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Scheduling dependency.</p>


<p>This represents one direction of an edge in the scheduling DAG.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#a07333f8ba53e0454b7ec6365860c0732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SDep::Kind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These are the different kinds of scheduling dependencies.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Data<a id="a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26"></a></td>
<td class="doxyEnumItemDescription">Regular data dependence (aka true-dependence)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Anti<a id="a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e"></a></td>
<td class="doxyEnumItemDescription">A register anti-dependence (aka WAR)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Output<a id="a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36"></a></td>
<td class="doxyEnumItemDescription">A register output-dependence (aka WAW)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Order<a id="a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> other ordering dependency</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### OrderKind {#a551060cb0333d9d0cfdacd2576d817b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SDep::OrderKind </td>
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
<td class="doxyEnumItemName">Barrier<a id="a551060cb0333d9d0cfdacd2576d817b9a3d026b42ef4cc00c58dd954b3c5eda65"></a></td>
<td class="doxyEnumItemDescription">An unknown scheduling barrier</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MayAliasMem<a id="a551060cb0333d9d0cfdacd2576d817b9aa34e7b539ffb2975952fd58cbb2b75c2"></a></td>
<td class="doxyEnumItemDescription">Nonvolatile load/Store instructions that may alias</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MustAliasMem<a id="a551060cb0333d9d0cfdacd2576d817b9af1f76321cbfa20244f78ab9f7a40900c"></a></td>
<td class="doxyEnumItemDescription">Nonvolatile load/Store instructions that must alias</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Artificial<a id="a551060cb0333d9d0cfdacd2576d817b9a8afafe9e6f4c2fb9744242a6b369a0f1"></a></td>
<td class="doxyEnumItemDescription">Arbitrary strong DAG edge (no real dependence)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Weak<a id="a551060cb0333d9d0cfdacd2576d817b9ac698747d5c996ab4f760518f55be1346"></a></td>
<td class="doxyEnumItemDescription">Arbitrary weak DAG edge</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cluster<a id="a551060cb0333d9d0cfdacd2576d817b9a04d28e273cd30fa75243240b15d08352"></a></td>
<td class="doxyEnumItemDescription">Weak DAG edge linking a chain of clustered instrs</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SDep() {#a98b446ad86ee3581e0273ef2200d2585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDep::SDep ()</td>
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

<p>Constructs a null <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a>.</p>


<p>This is only for use by container classes which require default constructors. SUnits may not/ have null <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> edges.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">Data</a>.</p>


<p>Referenced by <a href="#aa4c65136860d5e2699a42e5da78cf16f">operator!=</a>, <a href="#a7720d990f2e6a3baa82f1b33dfa6ea3f">operator==</a> and <a href="#a041210155b5dca8af4a22885222229ae">overlaps</a>.</p>

</div>
</div>

### SDep() {#afdd24e7642b757dd8b2ec8345bd9bda3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDep::SDep (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * S, <a href="#a07333f8ba53e0454b7ec6365860c0732">Kind</a> kind, unsigned Reg)</td>
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

<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> with the specified values.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">Anti</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">Data</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">Output</a> and <a href="#ab0a6528b6785d72ed8ec4a8f486ee78d">Reg</a>.</p>

</div>
</div>

### SDep() {#a958610bfb8db5e45be0eb3a6d894f627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDep::SDep (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * S, <a href="#a551060cb0333d9d0cfdacd2576d817b9">OrderKind</a> kind)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">Order</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#aa4c65136860d5e2699a42e5da78cf16f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Other)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a7720d990f2e6a3baa82f1b33dfa6ea3f">operator==</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a98b446ad86ee3581e0273ef2200d2585">SDep</a>.</p>

</div>
</div>

### operator==() {#a7720d990f2e6a3baa82f1b33dfa6ea3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Other)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a041210155b5dca8af4a22885222229ae">overlaps</a> and <a href="#a98b446ad86ee3581e0273ef2200d2585">SDep</a>.</p>


<p>Referenced by <a href="#aa4c65136860d5e2699a42e5da78cf16f">operator!=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ace1019e8cefb80490348369f12fe0a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDep::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">Anti</a>, <a href="#a551060cb0333d9d0cfdacd2576d817b9a8afafe9e6f4c2fb9744242a6b369a0f1">Artificial</a>, <a href="#a551060cb0333d9d0cfdacd2576d817b9a3d026b42ef4cc00c58dd954b3c5eda65">Barrier</a>, <a href="#a551060cb0333d9d0cfdacd2576d817b9a04d28e273cd30fa75243240b15d08352">Cluster</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a>, <a href="#a5eca2019521fd47b79fe5ef66d02fd43">getLatency</a>, <a href="#a8b51361656ac436c2c02a20e6196cff1">getReg</a>, <a href="#a6c89ab9b69b3bcaa536702845fd9542d">isAssignedRegDep</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="#a551060cb0333d9d0cfdacd2576d817b9aa34e7b539ffb2975952fd58cbb2b75c2">MayAliasMem</a>, <a href="#a551060cb0333d9d0cfdacd2576d817b9af1f76321cbfa20244f78ab9f7a40900c">MustAliasMem</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">Order</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">Output</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="#a551060cb0333d9d0cfdacd2576d817b9ac698747d5c996ab4f760518f55be1346">Weak</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a917f4d40ed0bbdaf4ab50e5df4de067b">llvm::ScheduleDAG::dumpNodeAll</a>.</p>

</div>
</div>

### getKind() {#a055c65558a3e0f7d48f1ed3dde061199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDep::Kind llvm::SDep::getKind ()</td>
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

<p>Returns an enum value representing the kind of the dependence.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a9027a59d16b066e9f8549b9a9c50b60b">llvm::AArch64Subtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a38ff3df1feb7915dfda6303a34484534">llvm::GCNSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult/#a788b324b6deb10dfbafa68a351b11c79">llvm::SchedDFSResult::compute</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ae7e825d2af275c631d66e063c4eff615">llvm::ScheduleDAGSDNodes::computeOperandLatency</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="#ace1019e8cefb80490348369f12fe0a44">dump</a>, <a href="#a8b51361656ac436c2c02a20e6196cff1">getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a26aca145a8f6953152a566a143c6ec8f">hasDataSucc</a>, <a href="#a75b245e9ae0e3d67d8485468580f360f">isArtificial</a>, <a href="#a6c89ab9b69b3bcaa536702845fd9542d">isAssignedRegDep</a>, <a href="#af5c4f1ea353d427a527f548d6bae4593">isBarrier</a>, <a href="#ac2a5a158ff2d2bbbadae7accc72e7c51">isCluster</a>, <a href="#a8b4768ef4b1a0a2e8d50714b07465075">isCtrl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/macrofusion-cpp/#a3e7cb00140c9de8721cfb8313b58d9ac">isHazard</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ae14c145aa6237db91a7bca044488de25">anonymous{R600Packetizer.cpp}::R600PacketizerList::isLegalToPacketizeTogether</a>, <a href="#aff3277eb7a4827c6a650eb49ea97796c">isMustAlias</a>, <a href="#a74e4e5c8f7ea14d79ea03006d33dc393">isNormalMemory</a>, <a href="#a21e3367f21a2b07ce6e344fc6a2ed078">isWeak</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a8a616fae155ac2f266346edbb5411470">llvm::SchedDFSImpl::joinPredSubtree</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#a6c67a87b5b8b7338e197f5bb29767019">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="#ad2e01668fae870af7bc0679edd4335c5">setReg</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a19e83509e45ee65e4495de5a3ed3d44a">llvm::SchedDFSImpl::visitPostorderNode</a> and <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ab897f62e9a1641091f3bc53d82883440">llvm::ARMOverrideBypasses::zeroOutputDependences</a>.</p>

</div>
</div>

### getLatency() {#a5eca2019521fd47b79fe5ef66d02fd43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDep::getLatency ()</td>
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

<p>Returns the latency value for this edge, which roughly means the minimum number of cycles that must elapse between the predecessor and the successor, given that they have this edge between them.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a38ff3df1feb7915dfda6303a34484534">llvm::GCNSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="#ace1019e8cefb80490348369f12fe0a44">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1c51776d4e512a7f24d5b5d601c31016">llvm::ScheduleDAGMI::releasePred</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a90ffd918ef80c711049758b2064e15c4">llvm::ScheduleDAGMI::releaseSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#ad8c1e5b05c8d75032ef68b1282aef2b2">llvm::ConvergingVLIWScheduler::releaseTopNode</a> and <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

### getReg() {#a8b51361656ac436c2c02a20e6196cff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDep::getReg ()</td>
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

<p>Returns the register associated with this edge.</p>


<p>This is only valid on Data, Anti, and Output edges. On Data edges, this value may be zero, meaning there is no associated register.</p>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">Anti</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">Data</a>, <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a> and <a href="#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">Output</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a9027a59d16b066e9f8549b9a9c50b60b">llvm::AArch64Subtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a38ff3df1feb7915dfda6303a34484534">llvm::GCNSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="#ace1019e8cefb80490348369f12fe0a44">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad1ced720461881db2f1371e0f30ff744">llvm::ARMOverrideBypasses::makeBundleAssumptions</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>.</p>

</div>
</div>

### getSUnit() {#a03a2dc5f9f321a2ce28f5c641dfe5455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * llvm::SDep::getSUnit ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a86bfa4838cb7e42648615d27c94c8017">llvm::ScheduleDAGInstrs::addEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a54fbbf29fc459bb243a1a43fb2ab9c1a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::clusterNeighboringMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult/#a788b324b6deb10dfbafa68a351b11c79">llvm::SchedDFSResult::compute</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a917f4d40ed0bbdaf4ab50e5df4de067b">llvm::ScheduleDAG::dumpNodeAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a26aca145a8f6953152a566a143c6ec8f">hasDataSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a22c99596004378b139e9ab48fae048dc">hasOnlyLiveOutUses</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a44c5faa549f250a26b1303eb1a3ebd47">llvm::ScheduleDAGTopologicalSort::InitDAGTopologicalSorting</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ae14c145aa6237db91a7bca044488de25">anonymous{R600Packetizer.cpp}::R600PacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#afba9f58251019a23a1d7f60d6c958071">llvm::ResourcePriorityQueue::isResourceAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a8a616fae155ac2f266346edbb5411470">llvm::SchedDFSImpl::joinPredSubtree</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad1ced720461881db2f1371e0f30ff744">llvm::ARMOverrideBypasses::makeBundleAssumptions</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a120fc86306882eb2bd3c27c9f4063fd6">llvm::ARMOverrideBypasses::memoryRAWHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#a6c67a87b5b8b7338e197f5bb29767019">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/latencypriorityqueue/#a2e3b6da384da19b92dc290a8051194c6">llvm::LatencyPriorityQueue::push</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a068e19beaca7ce41347bb87946fbe2c9">llvm::ResourcePriorityQueue::push</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1c51776d4e512a7f24d5b5d601c31016">llvm::ScheduleDAGMI::releasePred</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a90ffd918ef80c711049758b2064e15c4">llvm::ScheduleDAGMI::releaseSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#ad8c1e5b05c8d75032ef68b1282aef2b2">llvm::ConvergingVLIWScheduler::releaseTopNode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#ac88025eb8866478014f41b34cd29b593">anonymous{AMDGPUExportClustering.cpp}::removeExportDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/latencypriorityqueue/#a93f241795b5da8c207a88063862e2ea2">llvm::LatencyPriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a252bd3038d4cc84ade6e24b656bd4655">llvm::ARMOverrideBypasses::setBidirLatencies</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#addb1364902bd813841491d91970ce02b">llvm::SUnit::setDepthDirty</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a5ba3791568e29a8d9214ec7dad855a56">llvm::SUnit::setHeightDirty</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddgedge/#afb31935c5b586aefe79b47d172a5746c">llvm::SwingSchedulerDDGEdge::SwingSchedulerDDGEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#abd2c96b0f28a1d6e444286a24bdf48f7">llvm::SchedDFSImpl::visitCrossEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#ae259d5b34969a9259dbc66324869c398">llvm::SchedDFSImpl::visitPostorderEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a19e83509e45ee65e4495de5a3ed3d44a">llvm::SchedDFSImpl::visitPostorderNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a142388e1eb164f473d3c10b3c582d51b">llvm::ScheduleDAGTopologicalSort::WillCreateCycle</a>.</p>

</div>
</div>

### isArtificial() {#a75b245e9ae0e3d67d8485468580f360f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::isArtificial ()</td>
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

<p>Tests if this is an Order dependence that is marked as "artificial", meaning it isn't necessary for correctness.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a551060cb0333d9d0cfdacd2576d817b9a8afafe9e6f4c2fb9744242a6b369a0f1">Artificial</a>, <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a> and <a href="#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">Order</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a86bfa4838cb7e42648615d27c94c8017">llvm::ScheduleDAGInstrs::addEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a> and <a href="/web-llvm/docs/api/classes/llvm/sunititerator/#ad21c405410acc1224a0c595dfee78db3">llvm::SUnitIterator::isArtificialDep</a>.</p>

</div>
</div>

### isAssignedRegDep() {#a6c89ab9b69b3bcaa536702845fd9542d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::isAssignedRegDep ()</td>
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

<p>Tests if this is a Data dependence that is associated with a register.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">Data</a> and <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="#ace1019e8cefb80490348369f12fe0a44">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad1ced720461881db2f1371e0f30ff744">llvm::ARMOverrideBypasses::makeBundleAssumptions</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a142388e1eb164f473d3c10b3c582d51b">llvm::ScheduleDAGTopologicalSort::WillCreateCycle</a>.</p>

</div>
</div>

### isBarrier() {#af5c4f1ea353d427a527f548d6bae4593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::isBarrier ()</td>
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

<p>Tests if this is an Order dependence that is marked as a barrier.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a551060cb0333d9d0cfdacd2576d817b9a3d026b42ef4cc00c58dd954b3c5eda65">Barrier</a>, <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a> and <a href="#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">Order</a>.</p>


<p>Referenced by <a href="#af9ba62471316bc18e72fcab395fc7d71">isNormalMemoryOrBarrier</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#ac88025eb8866478014f41b34cd29b593">anonymous{AMDGPUExportClustering.cpp}::removeExportDependencies</a>.</p>

</div>
</div>

### isCluster() {#ac2a5a158ff2d2bbbadae7accc72e7c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::isCluster ()</td>
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

<p>Tests if this is an Order dependence that is marked as "cluster", meaning it is artificial and wants to be adjacent.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a551060cb0333d9d0cfdacd2576d817b9a04d28e273cd30fa75243240b15d08352">Cluster</a>, <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a> and <a href="#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">Order</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1c51776d4e512a7f24d5b5d601c31016">llvm::ScheduleDAGMI::releasePred</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a90ffd918ef80c711049758b2064e15c4">llvm::ScheduleDAGMI::releaseSucc</a>.</p>

</div>
</div>

### isCtrl() {#a8b4768ef4b1a0a2e8d50714b07465075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::isCtrl ()</td>
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

<p>Shorthand for <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind()</a> != <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">SDep::Data</a>.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">Data</a> and <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a22c99596004378b139e9ab48fae048dc">hasOnlyLiveOutUses</a>, <a href="/web-llvm/docs/api/classes/llvm/sunititerator/#ad6eeca3c40d9ebbab3bde59949fc3c13">llvm::SUnitIterator::isCtrlDep</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#afba9f58251019a23a1d7f60d6c958071">llvm::ResourcePriorityQueue::isResourceAvailable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp/#a4fd9efbedcbd8af579647f70a9c35f65">numberCtrlDepsInSU</a> and <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>.</p>

</div>
</div>

### isMustAlias() {#aff3277eb7a4827c6a650eb49ea97796c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::isMustAlias ()</td>
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

<p>Tests if this is an Order dependence that is marked as "must alias", meaning that the SUnits at either end of the edge have a memory dependence on a known memory location.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a>, <a href="#a551060cb0333d9d0cfdacd2576d817b9af1f76321cbfa20244f78ab9f7a40900c">MustAliasMem</a> and <a href="#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">Order</a>.</p>

</div>
</div>

### isNormalMemory() {#a74e4e5c8f7ea14d79ea03006d33dc393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::isNormalMemory ()</td>
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

<p>Tests if this is an Order dependence between two memory accesses where both sides of the dependence access memory in non-volatile and fully modeled ways.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a>, <a href="#a551060cb0333d9d0cfdacd2576d817b9aa34e7b539ffb2975952fd58cbb2b75c2">MayAliasMem</a>, <a href="#a551060cb0333d9d0cfdacd2576d817b9af1f76321cbfa20244f78ab9f7a40900c">MustAliasMem</a> and <a href="#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">Order</a>.</p>


<p>Referenced by <a href="#af9ba62471316bc18e72fcab395fc7d71">isNormalMemoryOrBarrier</a> and <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a120fc86306882eb2bd3c27c9f4063fd6">llvm::ARMOverrideBypasses::memoryRAWHazard</a>.</p>

</div>
</div>

### isNormalMemoryOrBarrier() {#af9ba62471316bc18e72fcab395fc7d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::isNormalMemoryOrBarrier ()</td>
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

<p>Tests if this is could be any kind of memory dependence.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#af5c4f1ea353d427a527f548d6bae4593">isBarrier</a> and <a href="#a74e4e5c8f7ea14d79ea03006d33dc393">isNormalMemory</a>.</p>

</div>
</div>

### isWeak() {#a21e3367f21a2b07ce6e344fc6a2ed078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::isWeak ()</td>
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

<p>Tests if this a weak dependence.</p>


<p>Weak dependencies are considered DAG edges for height computation and other heuristics, but do not force ordering. Breaking a weak edge may require the scheduler to compensate, for example by inserting a copy.</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">Order</a> and <a href="#a551060cb0333d9d0cfdacd2576d817b9ac698747d5c996ab4f760518f55be1346">Weak</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1c51776d4e512a7f24d5b5d601c31016">llvm::ScheduleDAGMI::releasePred</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a90ffd918ef80c711049758b2064e15c4">llvm::ScheduleDAGMI::releaseSucc</a>.</p>

</div>
</div>

### overlaps() {#a041210155b5dca8af4a22885222229ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDep::overlaps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Other)</td>
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

<p>Returns true if the specified <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> is equivalent except for latency.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">Anti</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">Data</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">Order</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">Output</a> and <a href="#a98b446ad86ee3581e0273ef2200d2585">SDep</a>.</p>


<p>Referenced by <a href="#a7720d990f2e6a3baa82f1b33dfa6ea3f">operator==</a>.</p>

</div>
</div>

### setLatency() {#a148b76c8f993d4a3d95ac19c60e2ebe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDep::setLatency (unsigned Lat)</td>
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

<p>Sets the latency for this edge.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aee33e06ea8865a2fb2bf229325c07194">llvm::ScheduleDAGInstrs::addChainDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a1a10e6734329db955a53b95fcc193cd3">llvm::SUnit::addPredBarrier</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a9027a59d16b066e9f8549b9a9c50b60b">llvm::AArch64Subtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a38ff3df1feb7915dfda6303a34484534">llvm::GCNSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ae7e825d2af275c631d66e063c4eff615">llvm::ScheduleDAGSDNodes::computeOperandLatency</a> and <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a252bd3038d4cc84ade6e24b656bd4655">llvm::ARMOverrideBypasses::setBidirLatencies</a>.</p>

</div>
</div>

### setReg() {#ad2e01668fae870af7bc0679edd4335c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDep::setReg (unsigned Reg)</td>
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

<p>Assigns the associated register for this edge.</p>


<p>This is only valid on Data, Anti, and Output edges. On Anti and Output edges, this value must not be zero. On Data edges, the value may be zero, which would mean that no specific register is associated with this edge.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">Anti</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">Data</a>, <a href="#a055c65558a3e0f7d48f1ed3dde061199">getKind</a>, <a href="#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">Output</a> and <a href="#ab0a6528b6785d72ed8ec4a8f486ee78d">Reg</a>.</p>

</div>
</div>

### setSUnit() {#aaa4f7e2f3f5a23ecf19b98acd3c05593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDep::setSUnit (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### OrdKind {#a5ad1b55cd1da72f5229dd7a0378ca99e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDep::OrdKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Additional information about Order dependencies.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### Reg {#ab0a6528b6785d72ed8ec4a8f486ee78d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDep::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For Data, Anti, and Output dependencies, the associated register.</p>


<p>For Data dependencies that don't currently have a register/ assigned, this is set to zero.</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#afdd24e7642b757dd8b2ec8345bd9bda3">SDep</a> and <a href="#ad2e01668fae870af7bc0679edd4335c5">setReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Contents {#ad7172b55fe082aa0f99d5ff30ed65065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::SDep llvm::SDep::Contents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A union discriminated by the dependence kind.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### Dep {#a5e12919ba475b02a0df53607999a6827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;SUnit *, 2, Kind&gt; llvm::SDep::Dep</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A pointer to the depending/depended-on <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>, and an enum indicating the kind of the dependency.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### Latency {#a6d4d94718345301a04e931f1b156cf7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDep::Latency = 0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The time associated with this edge.</p>


<p>Often this is just the value of the Latency field of the predecessor, however advanced models may provide additional information about specific edges.</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
