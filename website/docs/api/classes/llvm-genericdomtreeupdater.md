---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/genericdomtreeupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GenericDomTreeUpdater` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;
class llvm::GenericDomTreeUpdater&lt;DerivedT, DomTreeT, PostDomTreeT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">llvm/Analysis/GenericDomTreeUpdater.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7962416c960380f3b76c88e536514a1a">BasicBlockT</a> = typename DomTreeT::NodeType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a733fd2d0da71dee3118ad3b03e4948ea">UpdateT</a> = typename DomTreeT::UpdateType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">UpdateStrategy : unsigned char { <a href="#a2655b89361decf2c1493792dc14e5a56">...</a> }</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#abd144d408e6269c2e616fc68d236d29f">GenericDomTreeUpdater</a> (UpdateStrategy Strategy_)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7c6eeddbc93b84b241dca92f95fcaba0">GenericDomTreeUpdater</a> (DomTreeT &amp;DT_, UpdateStrategy Strategy_)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af3ab357049d01bd9a5a15bfd081f595f">GenericDomTreeUpdater</a> (DomTreeT *DT_, UpdateStrategy Strategy_)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a309d97fda0728cd1eb7f4b714527ae6b">GenericDomTreeUpdater</a> (PostDomTreeT &amp;PDT_, UpdateStrategy Strategy_)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac49df693e127d23ca41786138439552c">GenericDomTreeUpdater</a> (PostDomTreeT *PDT_, UpdateStrategy Strategy_)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#abeaf079c958f70c8312e19660c105e0b">GenericDomTreeUpdater</a> (DomTreeT &amp;DT_, PostDomTreeT &amp;PDT_, UpdateStrategy Strategy_)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa43a8208260ffd505cbf8dc2402f6b1c">GenericDomTreeUpdater</a> (DomTreeT *DT_, PostDomTreeT *PDT_, UpdateStrategy Strategy_)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ae30a3a83acd5c1ea411e8bf1d6a95c26">~GenericDomTreeUpdater</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afce0c05f1246398130114d3744926871">isLazy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the current strategy is Lazy. <a href="#afce0c05f1246398130114d3744926871">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26011eedf1c9a04983e127f6d3f2699a">isEager</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the current strategy is Eager. <a href="#a26011eedf1c9a04983e127f6d3f2699a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5aeecafe7f5def8f5623f333db959b75">hasDomTree</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it holds a DomTreeT. <a href="#a5aeecafe7f5def8f5623f333db959b75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78e05b61b35c5a3d87eb22d50f56a00a">hasPostDomTree</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it holds a PostDomTreeT. <a href="#a78e05b61b35c5a3d87eb22d50f56a00a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9bd72b91681bfabb7ffe59e95f988d6">hasPendingDeletedBB</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there is <a href="#a7962416c960380f3b76c88e536514a1a">BasicBlockT</a> awaiting deletion. <a href="#ae9bd72b91681bfabb7ffe59e95f988d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8c21c6dda4c7cfb40fc54ff0fc7e5e3f">isBBPendingDeletion</a> (BasicBlockT *DelBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if DelBB is awaiting deletion. <a href="#a8c21c6dda4c7cfb40fc54ff0fc7e5e3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a49a3abb0b92111611d0d88de7105ef70">hasPendingUpdates</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if either of DT or PDT is valid and the tree has at least one update pending. <a href="#a49a3abb0b92111611d0d88de7105ef70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af23127149c201b9f52f10f70529d0e15">hasPendingDomTreeUpdates</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there are DomTreeT updates queued. <a href="#af23127149c201b9f52f10f70529d0e15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab0b15b0878dd25a9a4d8fde055027e31">hasPendingPostDomTreeUpdates</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there are PostDomTreeT updates queued. <a href="#ab0b15b0878dd25a9a4d8fde055027e31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aefa1d7d67dd758fb993876e62c56890d">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug method to help view the internal state of this class. <a href="#aefa1d7d67dd758fb993876e62c56890d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c325f9e45c085ee9757538409359e21">isSelfDominance</a> (UpdateT Update) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the update is self dominance. <a href="#a5c325f9e45c085ee9757538409359e21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abc26be7bd6050f81f1a42835451926f0">applyDomTreeUpdates</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to apply all pending DomTree updates. <a href="#abc26be7bd6050f81f1a42835451926f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26a51dd25592d4f008dd31fbe5161cfc">applyPostDomTreeUpdates</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to apply all pending PostDomTree updates. <a href="#a26a51dd25592d4f008dd31fbe5161cfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac69f0f33bd155d164f8f39c96647c413">isUpdateValid</a> (UpdateT Update) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the update appears in the LLVM IR. <a href="#ac69f0f33bd155d164f8f39c96647c413">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a42eae544363676292b0d6a03d06ba9df">eraseDelBBNode</a> (BasicBlockT *DelBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase Basic Block node before it is unlinked from <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> in the DomTree and PostDomTree. <a href="#a42eae544363676292b0d6a03d06ba9df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8badf1528ca212cd5f5e28afeb051244">tryFlushDeletedBB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to flush deleted BasicBlocks if all available trees are up-to-date. <a href="#a8badf1528ca212cd5f5e28afeb051244">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa7ab6accfde7220340d4862ff76bd9c0">dropOutOfDateUpdates</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop all updates applied by all available trees and delete BasicBlocks if all available trees are up-to-date. <a href="#aa7ab6accfde7220340d4862ff76bd9c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a92fe55f1356829d889fe13d8a633fd1f">derived</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DerivedT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade1504bc744162796172b4da85e546a7">derived</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2814ab18019ec0d1ad623a9d6afdc1e8">splitDTCriticalEdges</a> (ArrayRef&lt; CriticalEdge &gt; Updates)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab133eb7f4f405db5b6aa73c403c2ace">splitPDTCriticalEdges</a> (ArrayRef&lt; CriticalEdge &gt; Updates)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsForward&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28baaef0f2471806d49bcb17c5d19108">applyUpdatesImpl</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericdomtreeupdater/domtreeupdate">DomTreeUpdate</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad09768c934fd481e5a641cc327d1a5cb">PendUpdates</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf8853c7c430053f0789589d49755109">PendDTUpdateIndex</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4889b35d9c71f2a1cee818e1d32563b">PendPDTUpdateIndex</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DomTreeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1fa5651fae1f44c6ec195a819e343ee">DT</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">PostDomTreeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9703952a73adf5c6adb9a14cc3385c27">PDT</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c1229274a768152e5ed6af3872af602">Strategy</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="#a7962416c960380f3b76c88e536514a1a">BasicBlockT</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a03640c958debd0b9a525cff8fe5a11ed">DeletedBBs</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa959e1a9f7af4da4bd2af56964a3aa80">IsRecalculatingDomTree</a> = false</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c573f8f6a31e4c1d156a097f54e0485">IsRecalculatingPostDomTree</a> = false</td>
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

## Mutation APIs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">recalculate</a> (FuncT &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify DTU that the entry block was replaced. <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a363d442ff7f9a13eafaee275aad9f54c">applyUpdates</a> (ArrayRef&lt; UpdateT &gt; Updates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Submit updates to all available trees. <a href="#a363d442ff7f9a13eafaee275aad9f54c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb620d887e5e200028c5e0fb37f82592">splitCriticalEdge</a> (BasicBlockT *FromBB, BasicBlockT *ToBB, BasicBlockT *NewBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply updates that the critical edge (FromBB, ToBB) has been split with NewBB. <a href="#abb620d887e5e200028c5e0fb37f82592">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28512659006140e4ac78ee3a68043dd5">applyUpdatesPermissive</a> (ArrayRef&lt; UpdateT &gt; Updates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Submit updates to all available trees. <a href="#a28512659006140e4ac78ee3a68043dd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Flush APIs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DomTreeT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ec32b69ca3c12883ee03ad1c2bd92d9">getDomTree</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flush DomTree updates and return DomTree. <a href="#a0ec32b69ca3c12883ee03ad1c2bd92d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">PostDomTreeT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b9134f9520d0b3b4b807db72d540e25">getPostDomTree</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flush PostDomTree updates and return PostDomTree. <a href="#a1b9134f9520d0b3b4b807db72d540e25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a43c80a160270d75d99cfeb080c165694">flush</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply all pending updates to available trees and flush all BasicBlocks awaiting deletion. <a href="#a43c80a160270d75d99cfeb080c165694">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BasicBlockT {#a7962416c960380f3b76c88e536514a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::BasicBlockT =  typename DomTreeT::NodeType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### UpdateT {#a733fd2d0da71dee3118ad3b03e4948ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::UpdateT =  typename DomTreeT::UpdateType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### UpdateStrategy {#a2655b89361decf2c1493792dc14e5a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::GenericDomTreeUpdater::UpdateStrategy : unsigned char</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Eager<a id="a2655b89361decf2c1493792dc14e5a56a483c336d7d9fe614a8b5aae1e746e01f"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lazy<a id="a2655b89361decf2c1493792dc14e5a56a46a9ebdb80117bfa1f0cdea65438290a"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GenericDomTreeUpdater() {#abd144d408e6269c2e616fc68d236d29f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::GenericDomTreeUpdater (<a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> Strategy_)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### GenericDomTreeUpdater() {#a7c6eeddbc93b84b241dca92f95fcaba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::GenericDomTreeUpdater (DomTreeT &amp; DT_, <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> Strategy_)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### GenericDomTreeUpdater() {#af3ab357049d01bd9a5a15bfd081f595f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::GenericDomTreeUpdater (DomTreeT * DT_, <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> Strategy_)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### GenericDomTreeUpdater() {#a309d97fda0728cd1eb7f4b714527ae6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::GenericDomTreeUpdater (PostDomTreeT &amp; PDT_, <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> Strategy_)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### GenericDomTreeUpdater() {#ac49df693e127d23ca41786138439552c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::GenericDomTreeUpdater (PostDomTreeT * PDT_, <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> Strategy_)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### GenericDomTreeUpdater() {#abeaf079c958f70c8312e19660c105e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::GenericDomTreeUpdater (DomTreeT &amp; DT_, PostDomTreeT &amp; PDT_, <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> Strategy_)</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### GenericDomTreeUpdater() {#aa43a8208260ffd505cbf8dc2402f6b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::GenericDomTreeUpdater (DomTreeT * DT_, PostDomTreeT * PDT_, <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> Strategy_)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GenericDomTreeUpdater() {#ae30a3a83acd5c1ea411e8bf1d6a95c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::~GenericDomTreeUpdater ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#aefa1d7d67dd758fb993876e62c56890d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug method to help view the internal state of this class.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a03640c958debd0b9a525cff8fe5a11ed">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DeletedBBs</a>, <a href="#ad1fa5651fae1f44c6ec195a819e343ee">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DT</a>, <a href="#a2655b89361decf2c1493792dc14e5a56a483c336d7d9fe614a8b5aae1e746e01f">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Eager</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a9703952a73adf5c6adb9a14cc3385c27">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PDT</a>, <a href="#adf8853c7c430053f0789589d49755109">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendDTUpdateIndex</a>, <a href="#ab4889b35d9c71f2a1cee818e1d32563b">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendPDTUpdateIndex</a>, <a href="#ad09768c934fd481e5a641cc327d1a5cb">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendUpdates</a> and <a href="#a6c1229274a768152e5ed6af3872af602">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Strategy</a>.</p>

</div>
</div>

### hasDomTree() {#a5aeecafe7f5def8f5623f333db959b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::hasDomTree ()</td>
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

<p>Returns true if it holds a DomTreeT.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a6d3df5d0193e146b79c3c48601641c43">shouldSplitOnPredicatedArgument</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpchain/#a6bb3a89ac6216b60c21d8815fb2fa220">anonymous{MergeICmps.cpp}::BCECmpChain::simplify</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### hasPendingDeletedBB() {#ae9bd72b91681bfabb7ffe59e95f988d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::hasPendingDeletedBB ()</td>
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

<p>Returns true if there is <a href="#a7962416c960380f3b76c88e536514a1a">BasicBlockT</a> awaiting deletion.</p>


<p>The deletion will only happen until a flush event and all available trees are up-to-date. Returns false under Eager <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### hasPendingDomTreeUpdates() {#af23127149c201b9f52f10f70529d0e15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::hasPendingDomTreeUpdates ()</td>
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

<p>Returns true if there are DomTreeT updates queued.</p>


<p>Returns false under Eager <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> or DT is nullptr.</p>


<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a49a3abb0b92111611d0d88de7105ef70">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::hasPendingUpdates</a>.</p>

</div>
</div>

### hasPendingPostDomTreeUpdates() {#ab0b15b0878dd25a9a4d8fde055027e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::hasPendingPostDomTreeUpdates ()</td>
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

<p>Returns true if there are PostDomTreeT updates queued.</p>


<p>Returns false under Eager <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> or PDT is nullptr.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a49a3abb0b92111611d0d88de7105ef70">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::hasPendingUpdates</a>.</p>

</div>
</div>

### hasPendingUpdates() {#a49a3abb0b92111611d0d88de7105ef70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::hasPendingUpdates ()</td>
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

<p>Returns true if either of DT or PDT is valid and the tree has at least one update pending.</p>


<p>If DT or PDT is nullptr it is treated as having no pending updates. This function does not check whether there is <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> awaiting deletion. Returns false under Eager <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a8badf1528ca212cd5f5e28afeb051244">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::tryFlushDeletedBB</a> and <a href="#ae30a3a83acd5c1ea411e8bf1d6a95c26">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::~GenericDomTreeUpdater</a>.</p>

</div>
</div>

### hasPostDomTree() {#a78e05b61b35c5a3d87eb22d50f56a00a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::hasPostDomTree ()</td>
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

<p>Returns true if it holds a PostDomTreeT.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### isBBPendingDeletion() {#a8c21c6dda4c7cfb40fc54ff0fc7e5e3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::isBBPendingDeletion (<a href="#a7962416c960380f3b76c88e536514a1a">BasicBlockT</a> * DelBB)</td>
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

<p>Returns true if DelBB is awaiting deletion.</p>


<p>Returns false under Eager <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#a14e4d7c9d518e8103d75a938c0bdcd6c">iterativelySimplifyCFG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec88b7682025edff7984c3b6c8da8ac9">llvm::removeUnreachableBlocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#ab27929ee45b92ac2fbcce5282bf37fb1">tailMergeBlocksWithSimilarFunctionTerminators</a>.</p>

</div>
</div>

### isEager() {#a26011eedf1c9a04983e127f6d3f2699a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::isEager ()</td>
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

<p>Returns true if the current strategy is Eager.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### isLazy() {#afce0c05f1246398130114d3744926871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::isLazy ()</td>
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

<p>Returns true if the current strategy is Lazy.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### applyDomTreeUpdates() {#abc26be7bd6050f81f1a42835451926f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyDomTreeUpdates ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to apply all pending DomTree updates.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a43c80a160270d75d99cfeb080c165694">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::flush</a> and <a href="#a0ec32b69ca3c12883ee03ad1c2bd92d9">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::getDomTree</a>.</p>

</div>
</div>

### applyPostDomTreeUpdates() {#a26a51dd25592d4f008dd31fbe5161cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyPostDomTreeUpdates ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to apply all pending PostDomTree updates.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a43c80a160270d75d99cfeb080c165694">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::flush</a> and <a href="#a1b9134f9520d0b3b4b807db72d540e25">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::getPostDomTree</a>.</p>

</div>
</div>

### dropOutOfDateUpdates() {#aa7ab6accfde7220340d4862ff76bd9c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates ()</td>
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

<p>Drop all updates applied by all available trees and delete BasicBlocks if all available trees are up-to-date.</p>

<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a>, <a href="#ad1fa5651fae1f44c6ec195a819e343ee">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DT</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a2655b89361decf2c1493792dc14e5a56a483c336d7d9fe614a8b5aae1e746e01f">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Eager</a>, <a href="#a9703952a73adf5c6adb9a14cc3385c27">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PDT</a>, <a href="#adf8853c7c430053f0789589d49755109">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendDTUpdateIndex</a>, <a href="#ab4889b35d9c71f2a1cee818e1d32563b">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendPDTUpdateIndex</a>, <a href="#ad09768c934fd481e5a641cc327d1a5cb">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendUpdates</a>, <a href="#a6c1229274a768152e5ed6af3872af602">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Strategy</a> and <a href="#a8badf1528ca212cd5f5e28afeb051244">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::tryFlushDeletedBB</a>.</p>


<p>Referenced by <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a>, <a href="#a43c80a160270d75d99cfeb080c165694">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::flush</a>, <a href="#a0ec32b69ca3c12883ee03ad1c2bd92d9">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::getDomTree</a>, <a href="#a1b9134f9520d0b3b4b807db72d540e25">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::getPostDomTree</a> and <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate</a>.</p>

</div>
</div>

### eraseDelBBNode() {#a42eae544363676292b0d6a03d06ba9df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::eraseDelBBNode (<a href="#a7962416c960380f3b76c88e536514a1a">BasicBlockT</a> * DelBB)</td>
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

<p>Erase Basic Block node before it is unlinked from <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> in the DomTree and PostDomTree.</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="#ad1fa5651fae1f44c6ec195a819e343ee">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DT</a>, <a href="#aa959e1a9f7af4da4bd2af56964a3aa80">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::IsRecalculatingDomTree</a>, <a href="#a3c573f8f6a31e4c1d156a097f54e0485">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::IsRecalculatingPostDomTree</a> and <a href="#a9703952a73adf5c6adb9a14cc3385c27">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PDT</a>.</p>

</div>
</div>

### isSelfDominance() {#a5c325f9e45c085ee9757538409359e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::isSelfDominance (<a href="#a733fd2d0da71dee3118ad3b03e4948ea">UpdateT</a> Update)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the update is self dominance.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a363d442ff7f9a13eafaee275aad9f54c">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdates</a> and <a href="#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>.</p>

</div>
</div>

### isUpdateValid() {#ac69f0f33bd155d164f8f39c96647c413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::isUpdateValid (<a href="#a733fd2d0da71dee3118ad3b03e4948ea">UpdateT</a> Update)</td>
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

<p>Returns true if the update appears in the LLVM IR.</p>


<p>It is used to check whether an update is valid in insertEdge/deleteEdge or is unnecessary in the batch update.</p>


<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>.</p>

</div>
</div>

### tryFlushDeletedBB() {#a8badf1528ca212cd5f5e28afeb051244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::tryFlushDeletedBB ()</td>
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

<p>Helper function to flush deleted BasicBlocks if all available trees are up-to-date.</p>

<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="#a49a3abb0b92111611d0d88de7105ef70">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::hasPendingUpdates</a> and <a href="#a8badf1528ca212cd5f5e28afeb051244">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::tryFlushDeletedBB</a>.</p>


<p>Referenced by <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a> and <a href="#a8badf1528ca212cd5f5e28afeb051244">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::tryFlushDeletedBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyUpdatesImpl() {#a28baaef0f2471806d49bcb17c5d19108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsForward&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesImpl&lt; false &gt; ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>

</div>
</div>

### derived() {#a92fe55f1356829d889fe13d8a633fd1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedT &amp; llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::derived ()</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### derived() {#ade1504bc744162796172b4da85e546a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DerivedT &amp; llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::derived ()</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>

</div>
</div>

### splitDTCriticalEdges() {#a2814ab18019ec0d1ad623a9d6afdc1e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::splitDTCriticalEdges (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericdomtreeupdater/criticaledge">CriticalEdge</a> &gt; Updates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>

</div>
</div>

### splitPDTCriticalEdges() {#aab133eb7f4f405db5b6aa73c403c2ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::splitPDTCriticalEdges (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericdomtreeupdater/criticaledge">CriticalEdge</a> &gt; Updates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DeletedBBs {#a03640c958debd0b9a525cff8fe5a11ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;BasicBlockT *, 8&gt; llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DeletedBBs</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#aefa1d7d67dd758fb993876e62c56890d">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dump</a>.</p>

</div>
</div>

### DT {#ad1fa5651fae1f44c6ec195a819e343ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeT* llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DT = nullptr</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a363d442ff7f9a13eafaee275aad9f54c">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdates</a>, <a href="#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>, <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a>, <a href="#aefa1d7d67dd758fb993876e62c56890d">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dump</a>, <a href="#a42eae544363676292b0d6a03d06ba9df">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::eraseDelBBNode</a>, <a href="#a0ec32b69ca3c12883ee03ad1c2bd92d9">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::getDomTree</a>, <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate</a> and <a href="#abb620d887e5e200028c5e0fb37f82592">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::splitCriticalEdge</a>.</p>

</div>
</div>

### IsRecalculatingDomTree {#aa959e1a9f7af4da4bd2af56964a3aa80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::IsRecalculatingDomTree = false</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a42eae544363676292b0d6a03d06ba9df">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::eraseDelBBNode</a> and <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate</a>.</p>

</div>
</div>

### IsRecalculatingPostDomTree {#a3c573f8f6a31e4c1d156a097f54e0485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::IsRecalculatingPostDomTree = false</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a42eae544363676292b0d6a03d06ba9df">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::eraseDelBBNode</a> and <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate</a>.</p>

</div>
</div>

### PDT {#a9703952a73adf5c6adb9a14cc3385c27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDomTreeT* llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PDT = nullptr</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a363d442ff7f9a13eafaee275aad9f54c">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdates</a>, <a href="#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>, <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a>, <a href="#aefa1d7d67dd758fb993876e62c56890d">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dump</a>, <a href="#a42eae544363676292b0d6a03d06ba9df">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::eraseDelBBNode</a>, <a href="#a1b9134f9520d0b3b4b807db72d540e25">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::getPostDomTree</a>, <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate</a> and <a href="#abb620d887e5e200028c5e0fb37f82592">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::splitCriticalEdge</a>.</p>

</div>
</div>

### PendDTUpdateIndex {#adf8853c7c430053f0789589d49755109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendDTUpdateIndex = 0</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a>, <a href="#aefa1d7d67dd758fb993876e62c56890d">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dump</a> and <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate</a>.</p>

</div>
</div>

### PendPDTUpdateIndex {#ab4889b35d9c71f2a1cee818e1d32563b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendPDTUpdateIndex = 0</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a>, <a href="#aefa1d7d67dd758fb993876e62c56890d">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dump</a> and <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate</a>.</p>

</div>
</div>

### PendUpdates {#ad09768c934fd481e5a641cc327d1a5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DomTreeUpdate, 16&gt; llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendUpdates</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a363d442ff7f9a13eafaee275aad9f54c">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdates</a>, <a href="#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>, <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a>, <a href="#aefa1d7d67dd758fb993876e62c56890d">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dump</a>, <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate</a> and <a href="#abb620d887e5e200028c5e0fb37f82592">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::splitCriticalEdge</a>.</p>

</div>
</div>

### Strategy {#a6c1229274a768152e5ed6af3872af602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UpdateStrategy llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Strategy</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="#a363d442ff7f9a13eafaee275aad9f54c">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdates</a>, <a href="#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>, <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a>, <a href="#aefa1d7d67dd758fb993876e62c56890d">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dump</a>, <a href="#ab6ae3c90eff5a8a46fe9ed9909e7d3cd">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate</a> and <a href="#abb620d887e5e200028c5e0fb37f82592">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::splitCriticalEdge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Mutation APIs



<p>These methods provide APIs for submitting updates to the DomTreeT and the <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a>.</p>


<p>Note: There are two strategies to update the DomTreeT and the <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a>:</p>


<ol class="doxyList" type="1">
<li>Eager <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>: Updates are submitted and then flushed immediately.</li>
<li>Lazy <a href="#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>: Updates are submitted but only flushed when you explicitly call Flush APIs. It is recommended to use this update strategy when you submit a bunch of updates multiple times which can then add up to a large number of updates between two queries on the DomTreeT. The incremental updater can reschedule the updates or decide to recalculate the dominator tree in order to speedup the updating process depending on the number of updates.</li>
</ol>

<p>Although GenericDomTree provides several update primitives, it is not encouraged to use these APIs directly.</p>


### applyUpdates {#a363d442ff7f9a13eafaee275aad9f54c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdates (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#a733fd2d0da71dee3118ad3b03e4948ea">UpdateT</a> &gt; Updates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Submit updates to all available trees.</p>


<p>The Eager Strategy flushes updates immediately while the Lazy Strategy queues the updates.</p>


<p>Note: The "existence" of an edge in a CFG refers to the CFG which DTU is in sync with + all updates before that single update.</p>


<p>CAUTION!</p>


<ol class="doxyList" type="1">
<li>It is required for the state of the LLVM IR to be updated <em>before</em> submitting the updates because the internal update routine will analyze the current state of the CFG to determine whether an update is valid.</li>
<li>It is illegal to submit any update that has already been submitted, i.e., you are supposed not to insert an existent edge or delete a nonexistent edge.</li>
</ol>

<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="#ad1fa5651fae1f44c6ec195a819e343ee">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DT</a>, <a href="#a5c325f9e45c085ee9757538409359e21">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::isSelfDominance</a>, <a href="#a2655b89361decf2c1493792dc14e5a56a46a9ebdb80117bfa1f0cdea65438290a">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Lazy</a>, <a href="#a9703952a73adf5c6adb9a14cc3385c27">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PDT</a>, <a href="#ad09768c934fd481e5a641cc327d1a5cb">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="#a6c1229274a768152e5ed6af3872af602">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Strategy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9267cf9acba995fd1b10ae1015d048c8">llvm::breakLoopBackedge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b3fdb09b0789963c439d41fe91e44a1">llvm::changeToCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7aa8025f73f4e06135e6ba7083ad7aab">createUnreachableSwitchDefault</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addf42fea14164ec994d4d517eaa56688">llvm::DeleteDeadBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cd89ca702a817aac3a4521dd2462a2e">llvm::DuplicateInstructionsInSplitBetween</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/#a14e3b2ee272be893fb7d474a5530705c">llvm::ControlFlowHub::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e4b18daaf5f20f1ade3a9f66b86d843">llvm::FoldReturnIntoUncondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a2f68fd99d1f5c6c8326be57c2963306d">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::lowerKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad9d19d00519eec89a553d376d72c9520">mergeNestedCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ae1c543456cbefe674946cdb2e237ad14">processSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a0ceff22bcbbcc85abecced9a3a395ccf">removeSwitchAfterSelectFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cbd0aa1465957c50eaea8374875b27">llvm::removeUnwindEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerconstantintrinsics-cpp/#aa39118ddf6c73ece724a5c5e93d0db1e">replaceConditionalBranchesOnConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpchain/#a6bb3a89ac6216b60c21d8815fb2fa220">anonymous{MergeICmps.cpp}::BCECmpChain::simplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a3e8ca2c20b8c4c14c72c49d98f3801ed">simplifySwitchOfCmpIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac950ae90e1bea2697f515628f7704b2a">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#ab27929ee45b92ac2fbcce5282bf37fb1">tailMergeBlocksWithSimilarFunctionTerminators</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a428f7b53e32934ae46a9aa35d3028d87">tryToMergeLandingPad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad98f06eded5a01ee8704f7d7d9ca4c5b">tryWidenCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#adb133e739b469808feb3635786aeaa01">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::unifyReturnBlockSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### applyUpdatesPermissive {#a28512659006140e4ac78ee3a68043dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#a733fd2d0da71dee3118ad3b03e4948ea">UpdateT</a> &gt; Updates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Submit updates to all available trees.</p>


<p>It will also</p>


<ol class="doxyList" type="1">
<li>discard duplicated updates,</li>
<li>remove invalid updates. (Invalid updates means deletion of an edge that still exists or insertion of an edge that does not exist.) The Eager Strategy flushes updates immediately while the Lazy Strategy queues the updates.</li>
</ol>

<p>Note: The "existence" of an edge in a CFG refers to the CFG which DTU is in sync with + all updates before that single update.</p>


<p>CAUTION!</p>


<ol class="doxyList" type="1">
<li>It is required for the state of the LLVM IR to be updated <em>before</em> submitting the updates because the internal update routine will analyze the current state of the CFG to determine whether an update is valid.</li>
<li>It is illegal to submit any update that has already been submitted, i.e., you are supposed not to insert an existent edge or delete a nonexistent edge.</li>
<li>It is only legal to submit updates to an edge in the order CFG changes are made. The order you submit updates on different edges is not restricted.</li>
</ol>

<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="#ad1fa5651fae1f44c6ec195a819e343ee">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="#afce0c05f1246398130114d3744926871">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::isLazy</a>, <a href="#a5c325f9e45c085ee9757538409359e21">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::isSelfDominance</a>, <a href="#ac69f0f33bd155d164f8f39c96647c413">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::isUpdateValid</a>, <a href="#a2655b89361decf2c1493792dc14e5a56a46a9ebdb80117bfa1f0cdea65438290a">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Lazy</a>, <a href="#a9703952a73adf5c6adb9a14cc3385c27">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PDT</a>, <a href="#ad09768c934fd481e5a641cc327d1a5cb">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a6c1229274a768152e5ed6af3872af602">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Strategy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ae1c543456cbefe674946cdb2e237ad14">processSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>.</p>

</div>
</div>

### recalculate {#ab6ae3c90eff5a8a46fe9ed9909e7d3cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::recalculate (FuncT &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Notify DTU that the entry block was replaced.</p>


<p>Recalculate all available trees and flush all BasicBlocks awaiting deletion immediately.</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a>, <a href="#ad1fa5651fae1f44c6ec195a819e343ee">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DT</a>, <a href="#a2655b89361decf2c1493792dc14e5a56a483c336d7d9fe614a8b5aae1e746e01f">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Eager</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#aa959e1a9f7af4da4bd2af56964a3aa80">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::IsRecalculatingDomTree</a>, <a href="#a3c573f8f6a31e4c1d156a097f54e0485">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::IsRecalculatingPostDomTree</a>, <a href="#a9703952a73adf5c6adb9a14cc3385c27">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PDT</a>, <a href="#adf8853c7c430053f0789589d49755109">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendDTUpdateIndex</a>, <a href="#ab4889b35d9c71f2a1cee818e1d32563b">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendPDTUpdateIndex</a>, <a href="#ad09768c934fd481e5a641cc327d1a5cb">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendUpdates</a> and <a href="#a6c1229274a768152e5ed6af3872af602">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Strategy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### splitCriticalEdge {#abb620d887e5e200028c5e0fb37f82592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::splitCriticalEdge (<a href="#a7962416c960380f3b76c88e536514a1a">BasicBlockT</a> * FromBB, <a href="#a7962416c960380f3b76c88e536514a1a">BasicBlockT</a> * ToBB, <a href="#a7962416c960380f3b76c88e536514a1a">BasicBlockT</a> * NewBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply updates that the critical edge (FromBB, ToBB) has been split with NewBB.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="#ad1fa5651fae1f44c6ec195a819e343ee">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DT</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a2655b89361decf2c1493792dc14e5a56a46a9ebdb80117bfa1f0cdea65438290a">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Lazy</a>, <a href="#a9703952a73adf5c6adb9a14cc3385c27">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PDT</a>, <a href="#ad09768c934fd481e5a641cc327d1a5cb">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PendUpdates</a> and <a href="#a6c1229274a768152e5ed6af3872af602">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::Strategy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Flush APIs



<p>CAUTION! By the moment these flush APIs are called, the current CFG needs to be the same as the CFG which DTU is in sync with + all updates submitted.</p>


### flush {#a43c80a160270d75d99cfeb080c165694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::flush ()</td>
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

<p>Apply all pending updates to available trees and flush all BasicBlocks awaiting deletion.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a48dd43ef05b66261790497edbdac92d9">llvm::JumpThreadingPass::run</a>.</p>

</div>
</div>

### getDomTree {#a0ec32b69ca3c12883ee03ad1c2bd92d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeT &amp; llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::getDomTree ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flush DomTree updates and return DomTree.</p>


<p>It flushes Deleted BBs if both trees are up-to-date. It must only be called when it has a DomTree.</p>


<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="#abc26be7bd6050f81f1a42835451926f0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyDomTreeUpdates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a> and <a href="#ad1fa5651fae1f44c6ec195a819e343ee">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::DT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/libcallsshrinkwrap-cpp/#a9a73c0e2e52b5f57d74bf8c8321dde88">runImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#ad69716246dabb743839cafceb902ef46">llvm::RewriteStatepointsForGC::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a6d3df5d0193e146b79c3c48601641c43">shouldSplitOnPredicatedArgument</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpchain/#a6bb3a89ac6216b60c21d8815fb2fa220">anonymous{MergeICmps.cpp}::BCECmpChain::simplify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### getPostDomTree {#a1b9134f9520d0b3b4b807db72d540e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename DomTreeT, typename PostDomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDomTreeT &amp; llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::getPostDomTree ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flush PostDomTree updates and return PostDomTree.</p>


<p>It flushes Deleted BBs if both trees are up-to-date. It must only be called when it has a PostDomTree.</p>


<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a>.</p>


<p>References <a href="#a26a51dd25592d4f008dd31fbe5161cfc">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyPostDomTreeUpdates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa7ab6accfde7220340d4862ff76bd9c0">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::dropOutOfDateUpdates</a> and <a href="#a9703952a73adf5c6adb9a14cc3385c27">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::PDT</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdater-h">GenericDomTreeUpdater.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/genericdomtreeupdaterimpl-h">GenericDomTreeUpdaterImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
