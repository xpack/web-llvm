---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regionbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegionBase` Class Template

<p>A single entry single exit <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class Tr&gt;
class llvm::RegionBase&lt;Tr&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regionnodebase">RegionNodeBase&lt;Tr&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> represents a subregion or a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is part of a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="/web-llvm/docs/api/classes/llvm/regionnodebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad88331578ab0e600fac6955e5884f801">FuncT</a> = typename Tr::FuncT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa813ab1d7656cb451bd2eceb4a766b9b">BlockT</a> = typename Tr::BlockT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6dde96c3bc021ed35394a7e71726344f">RegionInfoT</a> = typename Tr::RegionInfoT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5ccc19b6b9a7400710533c8f525e0022">RegionT</a> = typename Tr::RegionT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91e9775df9716ba5aaed4e7f44d2fa77">RegionNodeT</a> = typename Tr::RegionNodeT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab2e68c2112a88057065ddcf57f656103">DomTreeT</a> = typename Tr::DomTreeT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a343477bde9b811cb2f7172f443259e61">LoopT</a> = typename Tr::LoopT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae3992ada645d9de46c87a83c91bc1f79">LoopInfoT</a> = typename Tr::LoopInfoT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf1212803cc86dce6d186b51f2cc8226">InstT</a> = typename Tr::InstT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7aa77dbd5cb2e7a1a8803b15b11ad44e">BlockTraits</a> = <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; BlockT * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa6de90c9b4cb6178ab748dc890ec5182">InvBlockTraits</a> = <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/inverse">Inverse</a>&lt; BlockT * &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9f7f0a7d1f0aac6ca348f51d22e2482">SuccIterTy</a> = typename BlockTraits::ChildIteratorType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c31e27223809551cda3acaaafe50dd5">PredIterTy</a> = typename InvBlockTraits::ChildIteratorType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2adcddcc48b2ba91aea18a762dff6ffe">RegionSet</a> = std::vector&lt; std::unique_ptr&lt; RegionT &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83bdc422d9d47ef09bfa591807407f5e">BBNodeMapT</a> = std::map&lt; BlockT *, std::unique_ptr&lt; RegionNodeT &gt; &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">PrintStyle { <a href="#ac5640c432bedfc5763ea727601a9b079">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ac5640c432bedfc5763ea727601a9b079">PrintStyle</a> - Print region in difference ways. <a href="#ac5640c432bedfc5763ea727601a9b079">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ae6e086e91c64070ec658d8f5f3abda">RegionInfoBase&lt; Tr &gt;</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aaeb673bce3fe39f6a04bcc5cb93c83c8">RegionBase</a> (BlockT *Entry, BlockT *Exit, RegionInfoT *RI, DomTreeT *DT, RegionT *Parent=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new region. <a href="#aaeb673bce3fe39f6a04bcc5cb93c83c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8f73c8a4eac044449e94be127a3169b2">RegionBase</a> (const RegionBase &amp;)=delete</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab72207db1cba4f159dc41719b73df32c">~RegionBase</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> and all its subregions. <a href="#ab72207db1cba4f159dc41719b73df32c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regionbase">RegionBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7e7ea75a8b70631d5da7dca49918a59c">operator=</a> (const RegionBase &amp;)=delete</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88f49bb38a082837dd19ff5b4a062045">getEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a88f49bb38a082837dd19ff5b4a062045">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a646366819dcfeb8a7d533ebd78b43eaf">replaceEntry</a> (BlockT *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the entry basic block of the region with the new basic block. <a href="#a646366819dcfeb8a7d533ebd78b43eaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a03bb82a7322410a03468d0963ab845e4">replaceExit</a> (BlockT *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the exit basic block of the region with the new basic block. <a href="#a03bb82a7322410a03468d0963ab845e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a736d34433c1ecf86e5649d44ea701ad5">replaceEntryRecursive</a> (BlockT *NewEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively replace the entry basic block of the region. <a href="#a736d34433c1ecf86e5649d44ea701ad5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75b4520327daf138bdcd27dbec548df9">replaceExitRecursive</a> (BlockT *NewExit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively replace the exit basic block of the region. <a href="#a75b4520327daf138bdcd27dbec548df9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">getExit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the exit <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ed9c79ac80ed5996c7e241814302eab">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the parent of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a7ed9c79ac80ed5996c7e241814302eab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionNodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b74b9579c8b6c97d503c39d036c6e2d">getNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> representing the current <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a2b74b9579c8b6c97d503c39d036c6e2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5fca772610b91c67ec95e34b91c87d7f">getDepth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the nesting level of this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a5fca772610b91c67ec95e34b91c87d7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac2cecbc33894bd4b64953bc10521fca">isTopLevelRegion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> is the TopLevel region. <a href="#aac2cecbc33894bd4b64953bc10521fca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7b9de5df77062658127528fa16b314e">getExpandedRegion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a new (non-canonical) region, that is obtained by joining this region with its predecessors. <a href="#ae7b9de5df77062658127528fa16b314e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae5afd077192d75cf02f21fb8899a2e7b">getEnteringBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first block of this region's single entry edge, if existing. <a href="#ae5afd077192d75cf02f21fb8899a2e7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab3909bedb90883a3cf8b51b54c837980">getExitingBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first block of this region's single exit edge, if existing. <a href="#ab3909bedb90883a3cf8b51b54c837980">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2afc539a04a12d833eecbf55239b77cd">getExitingBlocks</a> (SmallVectorImpl&lt; BlockT * &gt; &amp;Exitings) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all blocks of this region's single exit edge, if existing. <a href="#a2afc539a04a12d833eecbf55239b77cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa851b865b7287deb0645ea32bc7c7754">isSimple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a simple region? <a href="#aa851b865b7287deb0645ea32bc7c7754">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1021f58f09c63db71a8b20b187d9d1c3">getNameStr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the name of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a1021f58f09c63db71a8b20b187d9d1c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionInfoT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a811f31afccd1675e128fe4933d5525e0">getRegionInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> object, that belongs to this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a811f31afccd1675e128fe4933d5525e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed7eee2aa41a7b67f3cfc9a6bc1f991a">print</a> (raw_ostream &amp;OS, bool printTree=true, unsigned level=0, PrintStyle Style=PrintNone) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the region. <a href="#aed7eee2aa41a7b67f3cfc9a6bc1f991a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6e21f6830dcb7fd5e3388ff8d510cb27">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the region to stderr. <a href="#a6e21f6830dcb7fd5e3388ff8d510cb27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75479f44e7157d1a8592231addb67c9c">contains</a> (const BlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the region contains a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. <a href="#a75479f44e7157d1a8592231addb67c9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab2dcc65dde60dfa6b685778b00983211">contains</a> (const RegionT *SubRegion) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the region contains another region. <a href="#ab2dcc65dde60dfa6b685778b00983211">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9bd43d6ea7f582bba3e11f91feb1b47f">contains</a> (const InstT *Inst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the region contains an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#a9bd43d6ea7f582bba3e11f91feb1b47f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a93378da7b054ace293c4598f52e7d3d2">contains</a> (const LoopT *L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the region contains a loop. <a href="#a93378da7b054ace293c4598f52e7d3d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LoopT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5dd8beec7af2e26f9b8bb9a7349897a7">outermostLoopInRegion</a> (LoopT *L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the outermost loop in the region that contains a loop. <a href="#a5dd8beec7af2e26f9b8bb9a7349897a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LoopT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0311f37a69cec2c19185230bcb99fbb1">outermostLoopInRegion</a> (LoopInfoT *LI, BlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the outermost loop in the region that contains a basic block. <a href="#a0311f37a69cec2c19185230bcb99fbb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aedf7b10f87dac6226e785d833b71ca36">getSubRegionNode</a> (BlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the subregion that starts at a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. <a href="#aedf7b10f87dac6226e785d833b71ca36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionNodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adca57ca819f2adadca5ef40b1948c97e">getNode</a> (BlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> for a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. <a href="#adca57ca819f2adadca5ef40b1948c97e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionNodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c5bfacbaceeadc12099696812305909">getBBNode</a> (BlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> for a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. <a href="#a1c5bfacbaceeadc12099696812305909">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8bbe38529ea4e2d7e880f970801d41db">addSubRegion</a> (RegionT *SubRegion, bool moveChildren=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new subregion to this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a8bbe38529ea4e2d7e880f970801d41db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad36101746b53c291564922a3d9f6a70c">removeSubRegion</a> (RegionT *SubRegion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a subregion from this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#ad36101746b53c291564922a3d9f6a70c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15baa4d8e2e6cf8a5afac640d48507f9">transferChildrenTo</a> (RegionT *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move all direct child nodes of this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> to another <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a15baa4d8e2e6cf8a5afac640d48507f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a8db54ec1fd5d420e3957b184546603">verifyRegion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify if the region is a correct region. <a href="#a7a8db54ec1fd5d420e3957b184546603">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b14400bd55c60e1954249c86edabfd3">clearNodeCache</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the cache for BB RegionNodes. <a href="#a0b14400bd55c60e1954249c86edabfd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a736fbd16ec917ebd9031cff3ef147de1">verifyBBInRegion</a> (BlockT *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a BB is in this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#a736fbd16ec917ebd9031cff3ef147de1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac179f48b7b6b186eccac044851d88160">verifyWalk</a> (BlockT *BB, std::set&lt; BlockT * &gt; *visitedBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk over all the BBs of the region starting from BB and verify that all reachable basic blocks are elements of the region. <a href="#ac179f48b7b6b186eccac044851d88160">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af3f064a299c87ef8808ad2f3bf0253a9">verifyRegionNest</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify if the region and its children are valid regions (EXPENSIVE!) <a href="#af3f064a299c87ef8808ad2f3bf0253a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionInfoT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6356578da555adfa014d62f639bc3e7f">RI</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DomTreeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7582976640b922fe316a67069392bb3">DT</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BlockT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b573d190986926312a8eaebd8742c22">exit</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RegionSet</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8612c05bdb6d3b5423daa857cf648f70">children</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BBNodeMapT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5941695d13c846e6245fbd4e6db3a185">BBNodeMap</a></td>
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

## Subregion Iterators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c2ad7012687bc9372618f66ed1351bf">iterator</a> = typename RegionSet::iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae06ff5284821a8c4d03727c5b60ae75f">const_iterator</a> = typename RegionSet::const_iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9c2ad7012687bc9372618f66ed1351bf">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1aa6c7717f84c6970e22a0938660047f">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9c2ad7012687bc9372618f66ed1351bf">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b0ebfeb3f47f1ad763e5b184dcb4e03">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae06ff5284821a8c4d03727c5b60ae75f">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a92045e5d807790d65784a07078184b9f">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae06ff5284821a8c4d03727c5b60ae75f">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d036694b1086ef4e12edb8f899f2401">end</a> () const</td>
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

## BasicBlock Iterators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b2b06ba71b877dbf048a5d420283a1e">block_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/regionbase/block-iterator-wrapper">block_iterator_wrapper</a>&lt; false &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27f8c46773a5cb2edcc711561a3f67ee">const_block_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/regionbase/block-iterator-wrapper">block_iterator_wrapper</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa2cb8d8dbe54ef35e05b388436d117f">block_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a4b2b06ba71b877dbf048a5d420283a1e">block_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7f0345715ae74b3d770738855613766">const_block_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a27f8c46773a5cb2edcc711561a3f67ee">const_block_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a4b2b06ba71b877dbf048a5d420283a1e">block_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2965af4fdecf688d02a2122bb05b17fc">block_begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a4b2b06ba71b877dbf048a5d420283a1e">block_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a70cc4b7f17a217d97a003872127d853d">block_end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a27f8c46773a5cb2edcc711561a3f67ee">const_block_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a62dcc232f047e179a515f4098b0ec464">block_begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a27f8c46773a5cb2edcc711561a3f67ee">const_block_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a508e8cd1e68c93ddba90107780ff9ec1">block_end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#afa2cb8d8dbe54ef35e05b388436d117f">block_range</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a10ba1eb8cf2fd3581b7929c2eac028b3">blocks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range view of the basic blocks in the region. <a href="#a10ba1eb8cf2fd3581b7929c2eac028b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab7f0345715ae74b3d770738855613766">const_block_range</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acf20cff9317179b36941ff93204bab9a">blocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range view of the basic blocks in the region. <a href="#acf20cff9317179b36941ff93204bab9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Element Iterators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8a8955d6e57f6e93c53f9bb960932b8">element_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/df-iterator">df_iterator</a>&lt; RegionNodeT *, <a href="/web-llvm/docs/api/structs/llvm/df-iterator-default-set">df_iterator_default_set</a>&lt; RegionNodeT * &gt;, false, <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; RegionNodeT * &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab87b21ed68f58c30e978c21ae59531f5">const_element_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/df-iterator">df_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RegionNodeT *, <a href="/web-llvm/docs/api/structs/llvm/df-iterator-default-set">df_iterator_default_set</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RegionNodeT * &gt;, false, <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RegionNodeT * &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#af8a8955d6e57f6e93c53f9bb960932b8">element_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a759f2fd9985046a0d875e07ad76298ae">element_begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#af8a8955d6e57f6e93c53f9bb960932b8">element_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c6031461953ce56150c9a85fd6be6be">element_end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e0ae9dbd8657e0c34fe587f0cc8839d">elements</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#af8a8955d6e57f6e93c53f9bb960932b8">element_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab87b21ed68f58c30e978c21ae59531f5">const_element_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30c8872fe89f8fb983e5e9ced62b5f2a">element_begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab87b21ed68f58c30e978c21ae59531f5">const_element_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada245e688bd8c27080a5174130c51ac7">element_end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab89fb69d866b9f6e558d0082dc2aae1e">elements</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab87b21ed68f58c30e978c21ae59531f5">const_element_iterator</a> &gt;</td>
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

<p>A single entry single exit <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<p>A <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> is a connected subgraph of a control flow graph that has exactly two connections to the remaining graph. It can be used to analyze or optimize parts of the control flow graph.</p>


<p>A <em> simple <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> </em> is connected to the remaining graph by just two edges. One edge entering the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> and another one leaving the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<p>An <em> extended <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> </em> (or just <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>) is a subgraph that can be transform into a simple <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. The transformation is done by adding BasicBlocks that merge several entry or exit edges so that after the merge just one entry and one exit edge exists.</p>


<p>The <em>Entry</em> of a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> is the first <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is passed after entering the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. It is an element of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. The entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> dominates all BasicBlocks in the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<p>The <em>Exit</em> of a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> is the first <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is passed after leaving the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. It is not an element of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. The exit <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, postdominates all BasicBlocks in the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<p>A <em> canonical <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> </em> cannot be constructed by combining smaller Regions.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/region">Region</a> A is the <em>parent</em> of <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> B, if B is completely contained in A.</p>


<p>Two canonical Regions either do not intersect at all or one is the parent of the other.</p>


<p>The <em> Program Structure Tree</em> is a graph (V, E) where V is the set of Regions in the control flow graph and E is the <em>parent</em> relation of these Regions.</p>


<p>Example:</p>



<pre><code>/// A simple control flow graph, that contains two regions.
 * 
 *         1
 *        / |
 *       2   |
 *      / \   3
 *     4   5  |
 *     |   |  |
 *     6   7  8
 *      \  | /
 *       \ |/       Region A: 1 -&gt; 9 {1,2,3,4,5,6,7,8}
 *         9        Region B: 2 -&gt; 9 {2,4,5,6,7}
 *
</code></pre>


<p>You can obtain more examples by either calling</p>


<p><span class="doxyComputerOutput"> "opt -passes='print&lt;regions&gt;' anyprogram.ll" </span> or <span class="doxyComputerOutput"> "opt -view-regions-only anyprogram.ll" </span></p>


<p>on any LLVM file you are interested in.</p>


<p>The first call returns a textual representation of the program structure tree, the second one creates a graphical representation using graphviz.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BBNodeMapT {#a83bdc422d9d47ef09bfa591807407f5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::BBNodeMapT =  std::map&lt;BlockT *, std::unique_ptr&lt;RegionNodeT&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### BlockT {#aa813ab1d7656cb451bd2eceb4a766b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::BlockT =  typename Tr::BlockT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### BlockTraits {#a7aa77dbd5cb2e7a1a8803b15b11ad44e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::BlockTraits =  GraphTraits&lt;BlockT *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### DomTreeT {#ab2e68c2112a88057065ddcf57f656103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::DomTreeT =  typename Tr::DomTreeT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### FuncT {#ad88331578ab0e600fac6955e5884f801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::FuncT =  typename Tr::FuncT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### InstT {#adf1212803cc86dce6d186b51f2cc8226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::InstT =  typename Tr::InstT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### InvBlockTraits {#aa6de90c9b4cb6178ab748dc890ec5182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::InvBlockTraits =  GraphTraits&lt;Inverse&lt;BlockT *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### LoopInfoT {#ae3992ada645d9de46c87a83c91bc1f79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::LoopInfoT =  typename Tr::LoopInfoT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### LoopT {#a343477bde9b811cb2f7172f443259e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::LoopT =  typename Tr::LoopT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### PredIterTy {#a1c31e27223809551cda3acaaafe50dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::PredIterTy =  typename InvBlockTraits::ChildIteratorType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### RegionInfoT {#a6dde96c3bc021ed35394a7e71726344f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::RegionInfoT =  typename Tr::RegionInfoT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### RegionNodeT {#a91e9775df9716ba5aaed4e7f44d2fa77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::RegionNodeT =  typename Tr::RegionNodeT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### RegionSet {#a2adcddcc48b2ba91aea18a762dff6ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::RegionSet =  std::vector&lt;std::unique_ptr&lt;RegionT&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### RegionT {#a5ccc19b6b9a7400710533c8f525e0022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::RegionT =  typename Tr::RegionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### SuccIterTy {#ab9f7f0a7d1f0aac6ca348f51d22e2482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::SuccIterTy =  typename BlockTraits::ChildIteratorType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### PrintStyle {#ac5640c432bedfc5763ea727601a9b079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RegionBase::PrintStyle </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#ac5640c432bedfc5763ea727601a9b079">PrintStyle</a> - Print region in difference ways.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrintNone<a id="ac5640c432bedfc5763ea727601a9b079aa66ae581c3941a803f2920632d415d33"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrintBB<a id="ac5640c432bedfc5763ea727601a9b079a351d783e505a4f673f331cb273de30b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrintRN<a id="ac5640c432bedfc5763ea727601a9b079a2c9d04d49db2ad7f38a0c09ea9fb8ef9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### RegionInfoBase&lt; Tr &gt; {#a0ae6e086e91c64070ec658d8f5f3abda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/regioninfobase">RegionInfoBase</a>&lt; Tr &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegionBase() {#aaeb673bce3fe39f6a04bcc5cb93c83c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegionBase&lt; Tr &gt;::RegionBase (BlockT * Entry, BlockT * Exit, RegionInfoT * RInfo, DomTreeT * DT, RegionT * Parent=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new region.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/regionbase">RegionBase</a> Implementation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Entry</td>
<td class="doxyParamItemDescription"><p>The entry basic block of the region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Exit</td>
<td class="doxyParamItemDescription"><p>The exit basic block of the region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RI</td>
<td class="doxyParamItemDescription"><p>The region info object that is managing this region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DT</td>
<td class="doxyParamItemDescription"><p>The dominator tree of the current function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parent</td>
<td class="doxyParamItemDescription"><p>The surrounding region or NULL if this is a top level region.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/regionnodebase/#a1aeba8f7fe748620d637ae2c1352b91c">llvm::RegionNodeBase&lt; Tr &gt;::RegionNodeBase</a>.</p>


<p>Referenced by <a href="#a7e7ea75a8b70631d5da7dca49918a59c">llvm::RegionBase&lt; Tr &gt;::operator=</a> and <a href="#a8f73c8a4eac044449e94be127a3169b2">llvm::RegionBase&lt; Tr &gt;::RegionBase</a>.</p>

</div>
</div>

### RegionBase() {#a8f73c8a4eac044449e94be127a3169b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegionBase&lt; Tr &gt;::RegionBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regionbase">RegionBase</a> &amp;)</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="#aaeb673bce3fe39f6a04bcc5cb93c83c8">llvm::RegionBase&lt; Tr &gt;::RegionBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RegionBase() {#ab72207db1cba4f159dc41719b73df32c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegionBase&lt; Tr &gt;::~RegionBase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> and all its subregions.</p>

<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a7e7ea75a8b70631d5da7dca49918a59c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionBase &amp; llvm::RegionBase&lt; Tr &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regionbase">RegionBase</a> &amp;)</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="#aaeb673bce3fe39f6a04bcc5cb93c83c8">llvm::RegionBase&lt; Tr &gt;::RegionBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSubRegion() {#a8bbe38529ea4e2d7e880f970801d41db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::addSubRegion (RegionT * SubRegion, bool moveChildren=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new subregion to this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SubRegion</td>
<td class="doxyParamItemDescription"><p>The new subregion that will be added.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">moveChildren</td>
<td class="doxyParamItemDescription"><p>Move the children of this region, that are also contained in SubRegion into SubRegion.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>.</p>

</div>
</div>

### clearNodeCache() {#a0b14400bd55c60e1954249c86edabfd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::clearNodeCache ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear the cache for BB RegionNodes.</p>


<p>After calling this function the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> RegionNodes will be stored at different memory locations. RegionNodes obtained before this function is called are therefore not comparable to RegionNodes abtained afterwords.</p>


<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

### contains() {#a75479f44e7157d1a8592231addb67c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegionBase&lt; Tr &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockT * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the region contains a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that might be contained in this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the block is contained in the region otherwise false.</p></dd>
</dl>


<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a> and <a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">llvm::RegionBase&lt; Tr &gt;::getExit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-controlheightreduction-cpp-/chrscope/#ade8f7c0d7ab85793236f27f66aa592d4">anonymous{ControlHeightReduction.cpp}::CHRScope::appendable</a>, <a href="#ab2dcc65dde60dfa6b685778b00983211">llvm::RegionBase&lt; Tr &gt;::contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp/#ab52c873c8169af2a8b1256ace3fe7a7c">sortBlocks</a>.</p>

</div>
</div>

### contains() {#ab2dcc65dde60dfa6b685778b00983211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegionBase&lt; Tr &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RegionT * SubRegion)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the region contains another region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SubRegion</td>
<td class="doxyParamItemDescription"><p>The region that might be contained in this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if SubRegion is contained in the region otherwise false.</p></dd>
</dl>


<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="#a75479f44e7157d1a8592231addb67c9c">llvm::RegionBase&lt; Tr &gt;::contains</a> and <a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">llvm::RegionBase&lt; Tr &gt;::getExit</a>.</p>

</div>
</div>

### contains() {#a9bd43d6ea7f582bba3e11f91feb1b47f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegionBase&lt; Tr &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InstT * Inst)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the region contains an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inst</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> that might be contained in this region.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is contained in the region otherwise false.</p></dd>
</dl>


<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="#a9bd43d6ea7f582bba3e11f91feb1b47f">llvm::RegionBase&lt; Tr &gt;::contains</a>.</p>


<p>Referenced by <a href="#a9bd43d6ea7f582bba3e11f91feb1b47f">llvm::RegionBase&lt; Tr &gt;::contains</a>.</p>

</div>
</div>

### contains() {#a93378da7b054ace293c4598f52e7d3d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegionBase&lt; Tr &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoopT * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the region contains a loop.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">L</td>
<td class="doxyParamItemDescription"><p>The loop that might be contained in this region.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the loop is contained in the region otherwise false. In case a NULL pointer is passed to this function the result is false, except for the region that describes the whole function. In that case true is returned.</p></dd>
</dl>


<p>Declaration at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a> and <a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">llvm::RegionBase&lt; Tr &gt;::getExit</a>.</p>

</div>
</div>

### dump() {#a6e21f6830dcb7fd5e3388ff8d510cb27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the region to stderr.</p>

<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a5fca772610b91c67ec95e34b91c87d7f">llvm::RegionBase&lt; Tr &gt;::getDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a> and <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#af0e039c6150609a69acba4d3fbe2c048">llvm::RegionInfoBase&lt; Tr &gt;::printStyle</a>.</p>

</div>
</div>

### getBBNode() {#a1c5bfacbaceeadc12099696812305909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tr::RegionNodeT * llvm::RegionBase&lt; Tr &gt;::getBBNode (BlockT * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> for a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> for which the <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> is requested.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> representing the BB.</p></dd>
</dl>


<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>.</p>

</div>
</div>

### getDepth() {#a5fca772610b91c67ec95e34b91c87d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegionBase&lt; Tr &gt;::getDepth ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the nesting level of this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<p>An toplevel <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> has depth 0.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The depth of the region.</p></dd>
</dl>


<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>.</p>


<p>Referenced by <a href="#a6e21f6830dcb7fd5e3388ff8d510cb27">llvm::RegionBase&lt; Tr &gt;::dump</a>.</p>

</div>
</div>

### getEnteringBlock() {#ae5afd077192d75cf02f21fb8899a2e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionBase&lt; Tr &gt;::BlockT * llvm::RegionBase&lt; Tr &gt;::getEnteringBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the first block of this region's single entry edge, if existing.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> starting this region's single entry edge, else NULL.</p></dd>
</dl>


<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6975e193997c4e0183e96774a7cb39">llvm::find_singleton</a>, <a href="#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a>.</p>


<p>Referenced by <a href="#aa851b865b7287deb0645ea32bc7c7754">llvm::RegionBase&lt; Tr &gt;::isSimple</a>.</p>

</div>
</div>

### getEntry() {#a88f49bb38a082837dd19ff5b4a062045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::RegionBase&lt; Tr &gt;::getEntry ()</td>
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

<p>Get the entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of the region.</p></dd>
</dl>


<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/regionnodebase/#ac5e41c46fb95e445164aae977ba0f911">llvm::RegionNodeBase&lt; Tr &gt;::getEntry</a>.</p>


<p>Referenced by <a href="#a2965af4fdecf688d02a2122bb05b17fc">llvm::RegionBase&lt; Tr &gt;::block_begin</a>, <a href="#a62dcc232f047e179a515f4098b0ec464">llvm::RegionBase&lt; Tr &gt;::block_begin</a>, <a href="#a75479f44e7157d1a8592231addb67c9c">llvm::RegionBase&lt; Tr &gt;::contains</a>, <a href="#ae5afd077192d75cf02f21fb8899a2e7b">llvm::RegionBase&lt; Tr &gt;::getEnteringBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a3dd35a887b6f48b00ca1d5e91e76c61b">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="#a1021f58f09c63db71a8b20b187d9d1c3">llvm::RegionBase&lt; Tr &gt;::getNameStr</a>, <a href="#a736d34433c1ecf86e5649d44ea701ad5">llvm::RegionBase&lt; Tr &gt;::replaceEntryRecursive</a> and <a href="#a7a8db54ec1fd5d420e3957b184546603">llvm::RegionBase&lt; Tr &gt;::verifyRegion</a>.</p>

</div>
</div>

### getExit() {#a1492fb7cbe1f1fbc16c92b9aa9ad9c00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::RegionBase&lt; Tr &gt;::getExit ()</td>
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

<p>Get the exit <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The exit <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>, NULL if this is the TopLevel <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p></dd>
</dl>


<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="#a2965af4fdecf688d02a2122bb05b17fc">llvm::RegionBase&lt; Tr &gt;::block_begin</a>, <a href="#a62dcc232f047e179a515f4098b0ec464">llvm::RegionBase&lt; Tr &gt;::block_begin</a>, <a href="#a75479f44e7157d1a8592231addb67c9c">llvm::RegionBase&lt; Tr &gt;::contains</a>, <a href="#a93378da7b054ace293c4598f52e7d3d2">llvm::RegionBase&lt; Tr &gt;::contains</a>, <a href="#ab2dcc65dde60dfa6b685778b00983211">llvm::RegionBase&lt; Tr &gt;::contains</a>, <a href="#ab3909bedb90883a3cf8b51b54c837980">llvm::RegionBase&lt; Tr &gt;::getExitingBlock</a>, <a href="#a1021f58f09c63db71a8b20b187d9d1c3">llvm::RegionBase&lt; Tr &gt;::getNameStr</a> and <a href="#a75b4520327daf138bdcd27dbec548df9">llvm::RegionBase&lt; Tr &gt;::replaceExitRecursive</a>.</p>

</div>
</div>

### getExitingBlock() {#ab3909bedb90883a3cf8b51b54c837980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionBase&lt; Tr &gt;::BlockT * llvm::RegionBase&lt; Tr &gt;::getExitingBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the first block of this region's single exit edge, if existing.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> starting this region's single exit edge, else NULL.</p></dd>
</dl>


<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6975e193997c4e0183e96774a7cb39">llvm::find_singleton</a>, <a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">llvm::RegionBase&lt; Tr &gt;::getExit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a>.</p>


<p>Referenced by <a href="#aa851b865b7287deb0645ea32bc7c7754">llvm::RegionBase&lt; Tr &gt;::isSimple</a>.</p>

</div>
</div>

### getExitingBlocks() {#a2afc539a04a12d833eecbf55239b77cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegionBase&lt; Tr &gt;::getExitingBlocks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; BlockT * &gt; &amp; Exitings)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect all blocks of this region's single exit edge, if existing.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if this region contains all the predecessors of the exit.</p></dd>
</dl>


<p>Declaration at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadc93e5b694cde77f4a8a3695372b990">llvm::inverse_children</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getExpandedRegion() {#ae7b9de5df77062658127528fa16b314e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tr::RegionT * llvm::RegionBase&lt; Tr &gt;::getExpandedRegion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a new (non-canonical) region, that is obtained by joining this region with its predecessors.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A region also starting at <a href="#a88f49bb38a082837dd19ff5b4a062045">getEntry()</a>, but reaching to the next basic block that forms with <a href="#a88f49bb38a082837dd19ff5b4a062045">getEntry()</a> a (non-canonical) region. NULL if such a basic block does not exist.</p></dd>
</dl>


<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

### getNameStr() {#a1021f58f09c63db71a8b20b187d9d1c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::RegionBase&lt; Tr &gt;::getNameStr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the name of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The Name of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p></dd>
</dl>


<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a>, <a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">llvm::RegionBase&lt; Tr &gt;::getExit</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>.</p>


<p>Referenced by <a href="#aed7eee2aa41a7b67f3cfc9a6bc1f991a">llvm::RegionBase&lt; Tr &gt;::print</a>.</p>

</div>
</div>

### getNode() {#a2b74b9579c8b6c97d503c39d036c6e2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionNodeT * llvm::RegionBase&lt; Tr &gt;::getNode ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> representing the current <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> representing the current <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p></dd>
</dl>


<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### getNode() {#adca57ca819f2adadca5ef40b1948c97e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tr::RegionNodeT * llvm::RegionBase&lt; Tr &gt;::getNode (BlockT * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> for a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> at which the <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> should start.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>If available, the <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> that represents the subregion starting at BB. If no subregion starts at BB, the <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> representing BB.</p></dd>
</dl>


<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

### getParent() {#a7ed9c79ac80ed5996c7e241814302eab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionT * llvm::RegionBase&lt; Tr &gt;::getParent ()</td>
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

<p>Get the parent of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The parent of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> or NULL if this is a top level <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p></dd>
</dl>


<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/regionnodebase/#a79b09475f3753504a26dc312d572112e">llvm::RegionNodeBase&lt; Tr &gt;::getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a48d81e3f58b8db143bc85763d25dbc7a">getCodeExtractorArguments</a>.</p>

</div>
</div>

### getRegionInfo() {#a811f31afccd1675e128fe4933d5525e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfoT * llvm::RegionBase&lt; Tr &gt;::getRegionInfo ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> object, that belongs to this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### getSubRegionNode() {#aedf7b10f87dac6226e785d833b71ca36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tr::RegionT * llvm::RegionBase&lt; Tr &gt;::getSubRegionNode (BlockT * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the subregion that starts at a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> the subregion should start.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The Subregion if available, otherwise NULL.</p></dd>
</dl>


<p>Declaration at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>.</p>

</div>
</div>

### isSimple() {#aa851b865b7287deb0645ea32bc7c7754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegionBase&lt; Tr &gt;::isSimple ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is this a simple region?</p>


<p>A region is simple if it has exactly one exit and one entry edge.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> is simple.</p></dd>
</dl>


<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="#ae5afd077192d75cf02f21fb8899a2e7b">llvm::RegionBase&lt; Tr &gt;::getEnteringBlock</a>, <a href="#ab3909bedb90883a3cf8b51b54c837980">llvm::RegionBase&lt; Tr &gt;::getExitingBlock</a> and <a href="#aac2cecbc33894bd4b64953bc10521fca">llvm::RegionBase&lt; Tr &gt;::isTopLevelRegion</a>.</p>

</div>
</div>

### isTopLevelRegion() {#aac2cecbc33894bd4b64953bc10521fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegionBase&lt; Tr &gt;::isTopLevelRegion ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> is the TopLevel region.</p>


<p>The toplevel region represents the whole function.</p>


<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="#aa851b865b7287deb0645ea32bc7c7754">llvm::RegionBase&lt; Tr &gt;::isSimple</a>.</p>

</div>
</div>

### outermostLoopInRegion() {#a5dd8beec7af2e26f9b8bb9a7349897a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tr::LoopT * llvm::RegionBase&lt; Tr &gt;::outermostLoopInRegion (LoopT * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the outermost loop in the region that contains a loop.</p>


<p>Find for a <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> L the outermost loop OuterL that is a parent loop of L and is itself contained in the region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">L</td>
<td class="doxyParamItemDescription"><p>The loop the lookup is started.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The outermost loop in the region, NULL if such a loop does not exist or if the region describes the whole function.</p></dd>
</dl>


<p>Declaration at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>.</p>


<p>Referenced by <a href="#a0311f37a69cec2c19185230bcb99fbb1">llvm::RegionBase&lt; Tr &gt;::outermostLoopInRegion</a>.</p>

</div>
</div>

### outermostLoopInRegion() {#a0311f37a69cec2c19185230bcb99fbb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tr::LoopT * llvm::RegionBase&lt; Tr &gt;::outermostLoopInRegion (LoopInfoT * LI, BlockT * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the outermost loop in the region that contains a basic block.</p>


<p>Find for a basic block BB the outermost loop L that contains BB and is itself contained in the region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LI</td>
<td class="doxyParamItemDescription"><p>A pointer to a <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> analysis.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The basic block surrounded by the loop.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The outermost loop in the region, NULL if such a loop does not exist or if the region describes the whole function.</p></dd>
</dl>


<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5dd8beec7af2e26f9b8bb9a7349897a7">llvm::RegionBase&lt; Tr &gt;::outermostLoopInRegion</a>.</p>

</div>
</div>

### print() {#aed7eee2aa41a7b67f3cfc9a6bc1f991a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool printTree=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, unsigned level=0, <a href="#ac5640c432bedfc5763ea727601a9b079">PrintStyle</a> Style=<a href="#ac5640c432bedfc5763ea727601a9b079aa66ae581c3941a803f2920632d415d33">PrintNone</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> is printed to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">printTree</td>
<td class="doxyParamItemDescription"><p>Print also the tree of subregions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">level</td>
<td class="doxyParamItemDescription"><p>The indentation level used for printing.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="#a3e0ae9dbd8657e0c34fe587f0cc8839d">llvm::RegionBase&lt; Tr &gt;::elements</a>, <a href="#a1021f58f09c63db71a8b20b187d9d1c3">llvm::RegionBase&lt; Tr &gt;::getNameStr</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="#ac5640c432bedfc5763ea727601a9b079a351d783e505a4f673f331cb273de30b3">llvm::RegionBase&lt; Tr &gt;::PrintBB</a>, <a href="#ac5640c432bedfc5763ea727601a9b079aa66ae581c3941a803f2920632d415d33">llvm::RegionBase&lt; Tr &gt;::PrintNone</a> and <a href="#ac5640c432bedfc5763ea727601a9b079a2c9d04d49db2ad7f38a0c09ea9fb8ef9">llvm::RegionBase&lt; Tr &gt;::PrintRN</a>.</p>

</div>
</div>

### removeSubRegion() {#ad36101746b53c291564922a3d9f6a70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tr::RegionT * llvm::RegionBase&lt; Tr &gt;::removeSubRegion (RegionT * SubRegion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove a subregion from this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<p>The subregion is not deleted, as it will probably be inserted into another region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SubRegion</td>
<td class="doxyParamItemDescription"><p>The SubRegion that will be removed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### replaceEntry() {#a646366819dcfeb8a7d533ebd78b43eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::replaceEntry (BlockT * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the entry basic block of the region with the new basic block.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The new entry basic block of the region.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

### replaceEntryRecursive() {#a736d34433c1ecf86e5649d44ea701ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::replaceEntryRecursive (BlockT * NewEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively replace the entry basic block of the region.</p>


<p>This function replaces the entry basic block with a new basic block. It also updates all child regions that have the same entry basic block as this region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewEntry</td>
<td class="doxyParamItemDescription"><p>The new entry basic block.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>Reference <a href="#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a>.</p>

</div>
</div>

### replaceExit() {#a03bb82a7322410a03468d0963ab845e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::replaceExit (BlockT * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the exit basic block of the region with the new basic block.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The new exit basic block of the region.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### replaceExitRecursive() {#a75b4520327daf138bdcd27dbec548df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::replaceExitRecursive (BlockT * NewExit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively replace the exit basic block of the region.</p>


<p>This function replaces the exit basic block with a new basic block. It also updates all child regions that have the same exit basic block as this region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewExit</td>
<td class="doxyParamItemDescription"><p>The new exit basic block.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>Reference <a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">llvm::RegionBase&lt; Tr &gt;::getExit</a>.</p>

</div>
</div>

### transferChildrenTo() {#a15baa4d8e2e6cf8a5afac640d48507f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::transferChildrenTo (RegionT * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move all direct child nodes of this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> to another <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">To</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> the child nodes will be transferred to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

### verifyRegion() {#a7a8db54ec1fd5d420e3957b184546603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::verifyRegion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify if the region is a correct region.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a correctly build <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. This is an expensive check, as the complete CFG of the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> will be walked.</p>


<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>References <a href="#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a2fa54fd5d688c50b33085362590f56b3">llvm::RegionInfoBase&lt; Tr &gt;::VerifyRegionInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### verifyBBInRegion() {#a736fbd16ec917ebd9031cff3ef147de1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::verifyBBInRegion (BlockT * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a BB is in this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<p>This check also works if the region is incorrectly built. (EXPENSIVE!)</p>


<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

### verifyRegionNest() {#af3f064a299c87ef8808ad2f3bf0253a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::verifyRegionNest ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify if the region and its children are valid regions (EXPENSIVE!)</p>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

### verifyWalk() {#ac179f48b7b6b186eccac044851d88160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegionBase&lt; Tr &gt;::verifyWalk (BlockT * BB, std::set&lt; BlockT * &gt; * visitedBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walk over all the BBs of the region starting from BB and verify that all reachable basic blocks are elements of the region.</p>


<p>(EXPENSIVE!)</p>


<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BBNodeMap {#a5941695d13c846e6245fbd4e6db3a185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBNodeMapT llvm::RegionBase&lt; Tr &gt;::BBNodeMap</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### children {#a8612c05bdb6d3b5423daa857cf648f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionSet llvm::RegionBase&lt; Tr &gt;::children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### DT {#ab7582976640b922fe316a67069392bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeT* llvm::RegionBase&lt; Tr &gt;::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### exit {#a0b573d190986926312a8eaebd8742c22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT* llvm::RegionBase&lt; Tr &gt;::exit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### RI {#a6356578da555adfa014d62f639bc3e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfoT* llvm::RegionBase&lt; Tr &gt;::RI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Subregion Iterators



<p>These iterators iterator over all subregions of this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


### begin {#a1aa6c7717f84c6970e22a0938660047f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::RegionBase&lt; Tr &gt;::begin ()</td>
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



<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### begin {#a92045e5d807790d65784a07078184b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::RegionBase&lt; Tr &gt;::begin ()</td>
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



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### const\_iterator {#ae06ff5284821a8c4d03727c5b60ae75f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::const_iterator =  typename RegionSet::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### end {#a9b0ebfeb3f47f1ad763e5b184dcb4e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::RegionBase&lt; Tr &gt;::end ()</td>
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



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a>.</p>

</div>
</div>

### end {#a4d036694b1086ef4e12edb8f899f2401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::RegionBase&lt; Tr &gt;::end ()</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### iterator {#a9c2ad7012687bc9372618f66ed1351bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::iterator =  typename RegionSet::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## BasicBlock Iterators



<p>These iterators iterate over all BasicBlocks that are contained in this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<p>The iterator also iterates over BasicBlocks that are elements of a subregion of this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. It is therefore called a flat iterator.</p>


### block\_begin {#a2965af4fdecf688d02a2122bb05b17fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block_iterator llvm::RegionBase&lt; Tr &gt;::block_begin ()</td>
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



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a> and <a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">llvm::RegionBase&lt; Tr &gt;::getExit</a>.</p>


<p>Referenced by <a href="#a10ba1eb8cf2fd3581b7929c2eac028b3">llvm::RegionBase&lt; Tr &gt;::blocks</a> and <a href="#acf20cff9317179b36941ff93204bab9a">llvm::RegionBase&lt; Tr &gt;::blocks</a>.</p>

</div>
</div>

### block\_begin {#a62dcc232f047e179a515f4098b0ec464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_block_iterator llvm::RegionBase&lt; Tr &gt;::block_begin ()</td>
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



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a> and <a href="#a1492fb7cbe1f1fbc16c92b9aa9ad9c00">llvm::RegionBase&lt; Tr &gt;::getExit</a>.</p>

</div>
</div>

### block\_end {#a70cc4b7f17a217d97a003872127d853d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block_iterator llvm::RegionBase&lt; Tr &gt;::block_end ()</td>
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



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="#a10ba1eb8cf2fd3581b7929c2eac028b3">llvm::RegionBase&lt; Tr &gt;::blocks</a> and <a href="#acf20cff9317179b36941ff93204bab9a">llvm::RegionBase&lt; Tr &gt;::blocks</a>.</p>

</div>
</div>

### block\_end {#a508e8cd1e68c93ddba90107780ff9ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_block_iterator llvm::RegionBase&lt; Tr &gt;::block_end ()</td>
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



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### block\_iterator {#a4b2b06ba71b877dbf048a5d420283a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::block_iterator =  block_iterator_wrapper&lt;false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### block\_range {#afa2cb8d8dbe54ef35e05b388436d117f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::block_range =  iterator_range&lt;block_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### blocks {#a10ba1eb8cf2fd3581b7929c2eac028b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block_range llvm::RegionBase&lt; Tr &gt;::blocks ()</td>
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

<p>Returns a range view of the basic blocks in the region.</p>

<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="#a2965af4fdecf688d02a2122bb05b17fc">llvm::RegionBase&lt; Tr &gt;::block_begin</a> and <a href="#a70cc4b7f17a217d97a003872127d853d">llvm::RegionBase&lt; Tr &gt;::block_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp/#ad1d9e6fe4974ee0754beaf3d7756bf20">hasOnlyUniformBranches</a>.</p>

</div>
</div>

### blocks {#acf20cff9317179b36941ff93204bab9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_block_range llvm::RegionBase&lt; Tr &gt;::blocks ()</td>
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

<p>Returns a range view of the basic blocks in the region.</p>


<p>This is the 'const' version of the range view.</p>


<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="#a2965af4fdecf688d02a2122bb05b17fc">llvm::RegionBase&lt; Tr &gt;::block_begin</a> and <a href="#a70cc4b7f17a217d97a003872127d853d">llvm::RegionBase&lt; Tr &gt;::block_end</a>.</p>

</div>
</div>

### const\_block\_iterator {#a27f8c46773a5cb2edcc711561a3f67ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::const_block_iterator =  block_iterator_wrapper&lt;true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### const\_block\_range {#ab7f0345715ae74b3d770738855613766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::const_block_range =  iterator_range&lt;const_block_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Element Iterators



<p>These iterators iterate over all <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> and subregion RegionNodes that are direct children of this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


<p>It does not iterate over any RegionNodes that are also element of a subregion of this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


### const\_element\_iterator {#ab87b21ed68f58c30e978c21ae59531f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::const_element_iterator = 
      df_iterator&lt;const RegionNodeT *,
                  df_iterator_default_set&lt;const RegionNodeT *&gt;, false,
                  GraphTraits&lt;const RegionNodeT *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### element\_begin {#a759f2fd9985046a0d875e07ad76298ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionBase&lt; Tr &gt;::element_iterator llvm::RegionBase&lt; Tr &gt;::element_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>Referenced by <a href="#a3e0ae9dbd8657e0c34fe587f0cc8839d">llvm::RegionBase&lt; Tr &gt;::elements</a> and <a href="#ab89fb69d866b9f6e558d0082dc2aae1e">llvm::RegionBase&lt; Tr &gt;::elements</a>.</p>

</div>
</div>

### element\_begin {#a30c8872fe89f8fb983e5e9ced62b5f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionBase&lt; Tr &gt;::const_element_iterator llvm::RegionBase&lt; Tr &gt;::element_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

### element\_end {#a9c6031461953ce56150c9a85fd6be6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionBase&lt; Tr &gt;::element_iterator llvm::RegionBase&lt; Tr &gt;::element_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>


<p>Referenced by <a href="#a3e0ae9dbd8657e0c34fe587f0cc8839d">llvm::RegionBase&lt; Tr &gt;::elements</a> and <a href="#ab89fb69d866b9f6e558d0082dc2aae1e">llvm::RegionBase&lt; Tr &gt;::elements</a>.</p>

</div>
</div>

### element\_end {#ada245e688bd8c27080a5174130c51ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionBase&lt; Tr &gt;::const_element_iterator llvm::RegionBase&lt; Tr &gt;::element_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a>.</p>

</div>
</div>

### element\_iterator {#af8a8955d6e57f6e93c53f9bb960932b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionBase&lt; Tr &gt;::element_iterator = 
      df_iterator&lt;RegionNodeT *, df_iterator_default_set&lt;RegionNodeT *&gt;, false,
                  GraphTraits&lt;RegionNodeT *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### elements {#a3e0ae9dbd8657e0c34fe587f0cc8839d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; element_iterator &gt; llvm::RegionBase&lt; Tr &gt;::elements ()</td>
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



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="#a759f2fd9985046a0d875e07ad76298ae">llvm::RegionBase&lt; Tr &gt;::element_begin</a>, <a href="#a9c6031461953ce56150c9a85fd6be6be">llvm::RegionBase&lt; Tr &gt;::element_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#aed7eee2aa41a7b67f3cfc9a6bc1f991a">llvm::RegionBase&lt; Tr &gt;::print</a>.</p>

</div>
</div>

### elements {#ab89fb69d866b9f6e558d0082dc2aae1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_element_iterator &gt; llvm::RegionBase&lt; Tr &gt;::elements ()</td>
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



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="#a759f2fd9985046a0d875e07ad76298ae">llvm::RegionBase&lt; Tr &gt;::element_begin</a>, <a href="#a9c6031461953ce56150c9a85fd6be6be">llvm::RegionBase&lt; Tr &gt;::element_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfoimpl-h">RegionInfoImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
