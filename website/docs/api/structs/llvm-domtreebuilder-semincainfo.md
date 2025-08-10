---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/domtreebuilder/semincainfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SemiNCAInfo` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename DomTreeT&gt;
struct llvm::DomTreeBuilder::SemiNCAInfo&lt;DomTreeT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">llvm/Support/GenericDomTreeConstruction.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> = typename DomTreeT::NodePtr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a692ee4860e5f23b9dd332928d441f9b6">NodeT</a> = typename DomTreeT::NodeType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> = <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; <a href="#a692ee4860e5f23b9dd332928d441f9b6">NodeT</a> &gt; *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a49550ef5969f83dc768411af224afb54">RootsT</a> = decltype(DomTreeT::Roots)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a52e01727eaa01a6cef0a7c1105e41c12">GraphDiffT</a> = <a href="/web-llvm/docs/api/classes/llvm/graphdiff">GraphDiff</a>&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">IsPostDom</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b867e96ffbb0518682396282de702fb">UpdateT</a> = typename DomTreeT::UpdateType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f3d462f65787261079dbe8242e4a971">UpdateKind</a> = typename DomTreeT::UpdateKind</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> = <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo">BatchUpdateInfo</a> *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a20d658e22ed7aa44d0b57363dd8c006f">NodeOrderMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a>, unsigned &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a042afbdb3af77ca1c837f901040d8f7c">SemiNCAInfo</a> (BatchUpdatePtr BUI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a480cdda4e46458dbca790a5205b0fdcb">clear</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec">InfoRec</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16dc433ff2f74c51a76edbffbabdd5bd">getNodeInfo</a> (NodePtr BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09cf9d5143816f847afdde1cf03cebfe">getIDom</a> (NodePtr BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9462d0ddb43c60b0d0889e337f1781ea">getNodeForBlock</a> (NodePtr BB, DomTreeT &amp;DT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsReverse = false, typename DescendCondition&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82285f7a23214e4a8931017af62e2d24">runDFS</a> (NodePtr V, unsigned LastNum, DescendCondition Condition, unsigned AttachToNum, const NodeOrderMap *SuccOrder=nullptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d03a4fddccb0dc066cb7195003db24e">eval</a> (unsigned V, unsigned LastLinked, SmallVectorImpl&lt; InfoRec * &gt; &amp;Stack, ArrayRef&lt; InfoRec * &gt; NumToInfo)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6b01145051cf194d0efb2b7ae241f24c">runSemiNCA</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c2d1292cd98fa2c253a7f872adc6887">addVirtualRoot</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DescendCondition&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c0f3e4b99c65642beff237e454a74fe">doFullDFSWalk</a> (const DomTreeT &amp;DT, DescendCondition DC)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acf1f2289b1f5ffbdf55e3f5ac555fed8">attachNewSubtree</a> (DomTreeT &amp;DT, const TreeNodePtr AttachTo)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6ab30bb387a6e7086235e9ff7ad01941">reattachExistingSubtree</a> (DomTreeT &amp;DT, const TreeNodePtr AttachTo)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeff699bd020f8620eb57bc0ffd9ce847">verifyRoots</a> (const DomTreeT &amp;DT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4bed97020476a2d93eb433776597d3de">verifyReachability</a> (const DomTreeT &amp;DT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeeca9e1d5c151829946fa95f9b9b30c7">verifyParentProperty</a> (const DomTreeT &amp;DT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a647a59b37db18cd302d604f723ba2ec4">verifySiblingProperty</a> (const DomTreeT &amp;DT)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a>, 64 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a813e82e90438f456f15f75c367ac5b58">NumToNode</a> = {nullptr}</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::conditional_t&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a35a70f3171a1748822370ffb5f9324bf">GraphHasNodeNumbers</a>&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec">InfoRec</a>, 64 &gt;, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec">InfoRec</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6c4ae4c81905ba22d594f9e43aa5ee7">NodeInfos</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo">BatchUpdateInfo</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae4b78b1bb21ca0057e776215004a579d">BatchUpdates</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool Inversed&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3314013831ea1df71a5408ee6ac032e1">getChildren</a> (NodePtr N, BatchUpdatePtr BUI) -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a>, 8 &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool Inversed&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0451f2d011f81c6f8ca840004a66c3fd">getChildren</a> (NodePtr N) -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a>, 8 &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f4824267c307e103d9ef6c84fd8972f">AlwaysDescend</a> (NodePtr, NodePtr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa26a0ee0a9f0cd627c9a6dc712ae53cb">HasForwardSuccessors</a> (const NodePtr N, BatchUpdatePtr BUI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f0aaddef3961662a3796cd1afe79da8">GetEntryNode</a> (const DomTreeT &amp;DT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#a49550ef5969f83dc768411af224afb54">RootsT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2867e9240af1e5a7d2a7aabb385a661d">FindRoots</a> (const DomTreeT &amp;DT, BatchUpdatePtr BUI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a851b359886bf561fb0fde504c228ecea">RemoveRedundantRoots</a> (const DomTreeT &amp;DT, BatchUpdatePtr BUI, RootsT &amp;Roots)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91b2ad7a91962494b1608aa174ac8ff3">CalculateFromScratch</a> (DomTreeT &amp;DT, BatchUpdatePtr BUI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae13a8bd8e24f12a9040cbbc5407d4b87">InsertEdge</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const NodePtr From, const NodePtr To)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6196ab5eb2faa09361ac7e663765ac88">UpdateRootsBeforeInsertion</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const TreeNodePtr From, const TreeNodePtr To)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a883785e34f877df86f4408a3aa7f25aa">isPermutation</a> (const SmallVectorImpl&lt; NodePtr &gt; &amp;A, const SmallVectorImpl&lt; NodePtr &gt; &amp;B)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f940701e11629de07234b0d717f1e39">UpdateRootsAfterUpdate</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa1f63192a86614e73a03f83e46813bb8">InsertReachable</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const TreeNodePtr From, const TreeNodePtr To)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04bc1c8d9cc3496359247eb5f4fa71c4">UpdateInsertion</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const TreeNodePtr NCD, InsertionInfo &amp;II)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab24f1fc850ebb24591b52b6e467177a6">InsertUnreachable</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const TreeNodePtr From, const NodePtr To)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a364cbe6ed1971f1d63c28607d1731fe9">ComputeUnreachableDominators</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const NodePtr Root, const TreeNodePtr Incoming, SmallVectorImpl&lt; std::pair&lt; NodePtr, TreeNodePtr &gt; &gt; &amp;DiscoveredConnectingEdges)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0733c415f27a3fa6f962bb5d5353ec1b">DeleteEdge</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const NodePtr From, const NodePtr To)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82b22baa3199208282b8771c811301bf">DeleteReachable</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const TreeNodePtr FromTN, const TreeNodePtr ToTN)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8824d1bacc5dcc91688d442dce6822e0">HasProperSupport</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const TreeNodePtr TN)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac0c56f97d07cfa7188e654e794e5032e">DeleteUnreachable</a> (DomTreeT &amp;DT, const BatchUpdatePtr BUI, const TreeNodePtr ToTN)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a597a58e3cc8ada27fdd127488b9f6d46">ApplyUpdates</a> (DomTreeT &amp;DT, GraphDiffT &amp;PreViewCFG, GraphDiffT *PostViewCFG)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4a757a462794e729a37c4cb13278b4c">ApplyNextUpdate</a> (DomTreeT &amp;DT, BatchUpdateInfo &amp;BUI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4714e88fbf38f2aaf7fd427dfb17a3a0">VerifyLevels</a> (const DomTreeT &amp;DT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba197972422fd98e9318e22f0419e0a8">VerifyDFSNumbers</a> (const DomTreeT &amp;DT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4ea2d791b0cb2b452a1d9ccfaf181712">IsSameAsFreshTree</a> (const DomTreeT &amp;DT)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5614a7f13a1e9158a52c5469ae45e126">IsPostDom</a> = DomTreeT::IsPostDominator</td>
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


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BatchUpdatePtr {#a4447ba6022e287f5fbef082704f1e2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdatePtr =  BatchUpdateInfo *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### GraphDiffT {#a52e01727eaa01a6cef0a7c1105e41c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::GraphDiffT =  GraphDiff&lt;NodePtr, IsPostDom&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### NodeOrderMap {#a20d658e22ed7aa44d0b57363dd8c006f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NodeOrderMap =  DenseMap&lt;NodePtr, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### NodePtr {#a5669fb284cfbf3893c2be26690f5d383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NodePtr =  typename DomTreeT::NodePtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### NodeT {#a692ee4860e5f23b9dd332928d441f9b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NodeT =  typename DomTreeT::NodeType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### RootsT {#a49550ef5969f83dc768411af224afb54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RootsT =  decltype(DomTreeT::Roots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### TreeNodePtr {#ab841529e1d6fd801bdeb291409119aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::TreeNodePtr =  DomTreeNodeBase&lt;NodeT&gt; *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### UpdateKind {#a5f3d462f65787261079dbe8242e4a971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateKind =  typename DomTreeT::UpdateKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### UpdateT {#a9b867e96ffbb0518682396282de702fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateT =  typename DomTreeT::UpdateType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SemiNCAInfo() {#a042afbdb3af77ca1c837f901040d8f7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::SemiNCAInfo (<a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Reference <a href="#ae4b78b1bb21ca0057e776215004a579d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdates</a>.</p>


<p>Referenced by <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="#a364cbe6ed1971f1d63c28607d1731fe9">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ComputeUnreachableDominators</a>, <a href="#a82b22baa3199208282b8771c811301bf">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable</a>, <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a> and <a href="#a851b359886bf561fb0fde504c228ecea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addVirtualRoot() {#a5c2d1292cd98fa2c253a7f872adc6887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::addVirtualRoot ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a> and <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a>.</p>


<p>Referenced by <a href="#a1c0f3e4b99c65642beff237e454a74fe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::doFullDFSWalk</a> and <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>.</p>

</div>
</div>

### attachNewSubtree() {#acf1f2289b1f5ffbdf55e3f5ac555fed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::attachNewSubtree (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> AttachTo)</td>
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



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="#a09cf9d5143816f847afdde1cf03cebfe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getIDom</a>, <a href="#a9462d0ddb43c60b0d0889e337f1781ea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeForBlock</a>, <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#a6452d57b10c414e7bcc84418ce8fc609">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::IDom</a> and <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a>.</p>


<p>Referenced by <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a> and <a href="#a364cbe6ed1971f1d63c28607d1731fe9">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ComputeUnreachableDominators</a>.</p>

</div>
</div>

### clear() {#a480cdda4e46458dbca790a5205b0fdcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::clear ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#af6c4ae4c81905ba22d594f9e43aa5ee7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NodeInfos</a> and <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a>.</p>


<p>Referenced by <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="#a851b359886bf561fb0fde504c228ecea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots</a>, <a href="#aeeca9e1d5c151829946fa95f9b9b30c7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty</a>, <a href="#a4bed97020476a2d93eb433776597d3de">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability</a> and <a href="#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>.</p>

</div>
</div>

### doFullDFSWalk() {#a1c0f3e4b99c65642beff237e454a74fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DescendCondition&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::doFullDFSWalk (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT, DescendCondition DC)</td>
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



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#a5c2d1292cd98fa2c253a7f872adc6887">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::addVirtualRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a> and <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>.</p>


<p>Referenced by <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="#aeeca9e1d5c151829946fa95f9b9b30c7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty</a>, <a href="#a4bed97020476a2d93eb433776597d3de">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability</a> and <a href="#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>.</p>

</div>
</div>

### eval() {#a4d03a4fddccb0dc066cb7195003db24e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::eval (unsigned V, unsigned LastLinked, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec">InfoRec</a> * &gt; &amp; Stack, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec">InfoRec</a> * &gt; NumToInfo)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#a3b23e8ba215f9241cffa0f3c9c351c8b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::Label</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#a8e6152fd055f0d00d6d6c1386bf3fd92">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::Parent</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#a7cf7afef13861e3f6ce5dc5c4ba63d20">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::Semi</a>.</p>


<p>Referenced by <a href="#a6b01145051cf194d0efb2b7ae241f24c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA</a>.</p>

</div>
</div>

### getIDom() {#a09cf9d5143816f847afdde1cf03cebfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodePtr llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getIDom (<a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> BB)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#a6452d57b10c414e7bcc84418ce8fc609">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::IDom</a>.</p>


<p>Referenced by <a href="#acf1f2289b1f5ffbdf55e3f5ac555fed8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::attachNewSubtree</a> and <a href="#a9462d0ddb43c60b0d0889e337f1781ea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeForBlock</a>.</p>

</div>
</div>

### getNodeForBlock() {#a9462d0ddb43c60b0d0889e337f1781ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeNodePtr llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeForBlock (<a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> BB, DomTreeT &amp; DT)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a09cf9d5143816f847afdde1cf03cebfe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getIDom</a> and <a href="#a9462d0ddb43c60b0d0889e337f1781ea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeForBlock</a>.</p>


<p>Referenced by <a href="#acf1f2289b1f5ffbdf55e3f5ac555fed8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::attachNewSubtree</a> and <a href="#a9462d0ddb43c60b0d0889e337f1781ea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeForBlock</a>.</p>

</div>
</div>

### getNodeInfo() {#a16dc433ff2f74c51a76edbffbabdd5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InfoRec &amp; llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo (<a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> BB)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a35a70f3171a1748822370ffb5f9324bf">llvm::GraphHasNodeNumbers</a> and <a href="#af6c4ae4c81905ba22d594f9e43aa5ee7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NodeInfos</a>.</p>


<p>Referenced by <a href="#a5c2d1292cd98fa2c253a7f872adc6887">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::addVirtualRoot</a>, <a href="#acf1f2289b1f5ffbdf55e3f5ac555fed8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::attachNewSubtree</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="#a09cf9d5143816f847afdde1cf03cebfe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getIDom</a>, <a href="#a6ab30bb387a6e7086235e9ff7ad01941">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::reattachExistingSubtree</a>, <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="#a6b01145051cf194d0efb2b7ae241f24c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA</a>, <a href="#aeeca9e1d5c151829946fa95f9b9b30c7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty</a>, <a href="#a4bed97020476a2d93eb433776597d3de">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability</a> and <a href="#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>.</p>

</div>
</div>

### reattachExistingSubtree() {#a6ab30bb387a6e7086235e9ff7ad01941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::reattachExistingSubtree (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> AttachTo)</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#a6452d57b10c414e7bcc84418ce8fc609">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::IDom</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a> and <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a2d97875c33b38014d365da0193d8aa21">llvm::DomTreeNodeBase&lt; NodeT &gt;::setIDom</a>.</p>


<p>Referenced by <a href="#a82b22baa3199208282b8771c811301bf">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable</a> and <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>.</p>

</div>
</div>

### runDFS() {#a82285f7a23214e4a8931017af62e2d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsReverse = false, typename DescendCondition&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS (<a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> V, unsigned LastNum, DescendCondition Condition, unsigned AttachToNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a20d658e22ed7aa44d0b57363dd8c006f">NodeOrderMap</a> * SuccOrder=nullptr)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ae4b78b1bb21ca0057e776215004a579d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a3314013831ea1df71a5408ee6ac032e1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a>, <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a>, <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#a8e6152fd055f0d00d6d6c1386bf3fd92">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::Parent</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a364cbe6ed1971f1d63c28607d1731fe9">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ComputeUnreachableDominators</a>, <a href="#a82b22baa3199208282b8771c811301bf">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable</a>, <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="#a1c0f3e4b99c65642beff237e454a74fe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::doFullDFSWalk</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a> and <a href="#a851b359886bf561fb0fde504c228ecea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots</a>.</p>

</div>
</div>

### runSemiNCA() {#a6b01145051cf194d0efb2b7ae241f24c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA ()</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4d03a4fddccb0dc066cb7195003db24e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::eval</a>, <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>.</p>


<p>Referenced by <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="#a364cbe6ed1971f1d63c28607d1731fe9">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ComputeUnreachableDominators</a>, <a href="#a82b22baa3199208282b8771c811301bf">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable</a> and <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>.</p>

</div>
</div>

### verifyParentProperty() {#aeeca9e1d5c151829946fa95f9b9b30c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT)</td>
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



<p>Definition at line 1455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a06c288c533e6c4fc7def0945622b26f3">llvm::DomTreeNodeBase&lt; NodeT &gt;::children</a>, <a href="#a480cdda4e46458dbca790a5205b0fdcb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#aea3bfb4f61599f17708e91db1a0c2be6">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::DFSNum</a>, <a href="#a1c0f3e4b99c65642beff237e454a74fe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::doFullDFSWalk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a25b833c85afc5c3de7c2c4e38ac6b146">llvm::DomTreeNodeBase&lt; NodeT &gt;::isLeaf</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1348bf219185f1a9896e890ab4c2061d">llvm::DomTreeBuilder::Verify</a>.</p>

</div>
</div>

### verifyReachability() {#a4bed97020476a2d93eb433776597d3de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT)</td>
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



<p>Definition at line 1245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#a6f4824267c307e103d9ef6c84fd8972f">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::AlwaysDescend</a>, <a href="#a480cdda4e46458dbca790a5205b0fdcb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::clear</a>, <a href="#a1c0f3e4b99c65642beff237e454a74fe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::doFullDFSWalk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1348bf219185f1a9896e890ab4c2061d">llvm::DomTreeBuilder::Verify</a>.</p>

</div>
</div>

### verifyRoots() {#aeff699bd020f8620eb57bc0ffd9ce847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyRoots (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT)</td>
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



<p>Definition at line 1206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="#a6f0aaddef3961662a3796cd1afe79da8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::GetEntryNode</a>, <a href="#a883785e34f877df86f4408a3aa7f25aa">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::isPermutation</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1348bf219185f1a9896e890ab4c2061d">llvm::DomTreeBuilder::Verify</a>.</p>

</div>
</div>

### verifySiblingProperty() {#a647a59b37db18cd302d604f723ba2ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT)</td>
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



<p>Definition at line 1491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a06c288c533e6c4fc7def0945622b26f3">llvm::DomTreeNodeBase&lt; NodeT &gt;::children</a>, <a href="#a480cdda4e46458dbca790a5205b0fdcb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::clear</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#aea3bfb4f61599f17708e91db1a0c2be6">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::DFSNum</a>, <a href="#a1c0f3e4b99c65642beff237e454a74fe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::doFullDFSWalk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a25b833c85afc5c3de7c2c4e38ac6b146">llvm::DomTreeNodeBase&lt; NodeT &gt;::isLeaf</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1348bf219185f1a9896e890ab4c2061d">llvm::DomTreeBuilder::Verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BatchUpdates {#ae4b78b1bb21ca0057e776215004a579d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BatchUpdateInfo* llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a> and <a href="#a042afbdb3af77ca1c837f901040d8f7c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::SemiNCAInfo</a>.</p>

</div>
</div>

### NodeInfos {#af6c4ae4c81905ba22d594f9e43aa5ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::conditional_t&lt;GraphHasNodeNumbers&lt;NodePtr&gt;, SmallVector&lt;InfoRec, 64&gt;, DenseMap&lt;NodePtr, InfoRec&gt; &gt; llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NodeInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="#a480cdda4e46458dbca790a5205b0fdcb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::clear</a> and <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>.</p>

</div>
</div>

### NumToNode {#a813e82e90438f456f15f75c367ac5b58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;NodePtr, 64&gt; llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode = {nullptr}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="#a5c2d1292cd98fa2c253a7f872adc6887">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::addVirtualRoot</a>, <a href="#acf1f2289b1f5ffbdf55e3f5ac555fed8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::attachNewSubtree</a>, <a href="#a480cdda4e46458dbca790a5205b0fdcb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::clear</a>, <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="#a6ab30bb387a6e7086235e9ff7ad01941">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::reattachExistingSubtree</a>, <a href="#a851b359886bf561fb0fde504c228ecea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots</a>, <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="#a6b01145051cf194d0efb2b7ae241f24c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA</a> and <a href="#a4bed97020476a2d93eb433776597d3de">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### AlwaysDescend() {#a6f4824267c307e103d9ef6c84fd8972f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::AlwaysDescend (<a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a>, <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a>)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="#a851b359886bf561fb0fde504c228ecea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots</a> and <a href="#a4bed97020476a2d93eb433776597d3de">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability</a>.</p>

</div>
</div>

### ApplyNextUpdate() {#ab4a757a462794e729a37c4cb13278b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyNextUpdate (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo">BatchUpdateInfo</a> &amp; BUI)</td>
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



<p>Definition at line 1180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a>, <a href="#ae13a8bd8e24f12a9040cbbc5407d4b87">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertEdge</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/graphdiff/#ab2a3b8f6ebc0db2628ad35dc728fde42">llvm::GraphDiff&lt; NodePtr, InverseGraph &gt;::popUpdateForIncrementalUpdates</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo/#a406eae297a0eccbe8848b8d99232b213">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdateInfo::PreViewCFG</a>.</p>


<p>Referenced by <a href="#a597a58e3cc8ada27fdd127488b9f6d46">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyUpdates</a>.</p>

</div>
</div>

### ApplyUpdates() {#a597a58e3cc8ada27fdd127488b9f6d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyUpdates (DomTreeT &amp; DT, <a href="#a52e01727eaa01a6cef0a7c1105e41c12">GraphDiffT</a> &amp; PreViewCFG, <a href="#a52e01727eaa01a6cef0a7c1105e41c12">GraphDiffT</a> * PostViewCFG)</td>
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



<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#ab4a757a462794e729a37c4cb13278b4c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyNextUpdate</a>, <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/graphdiff/#abf8532d450c03fedf6af2f69f29388cf">llvm::GraphDiff&lt; NodePtr, InverseGraph &gt;::getNumLegalizedUpdates</a>, <a href="#ae13a8bd8e24f12a9040cbbc5407d4b87">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertEdge</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo/#a37e6111f7d67481244d8b4da72dd0ee1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdateInfo::IsRecalculated</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo/#aa1ceab925352791613e8dd137ee91d34">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdateInfo::NumLegalized</a> and <a href="/web-llvm/docs/api/classes/llvm/graphdiff/#ab2a3b8f6ebc0db2628ad35dc728fde42">llvm::GraphDiff&lt; NodePtr, InverseGraph &gt;::popUpdateForIncrementalUpdates</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a938230b97505e69266ab1f8ac0eb5db7">llvm::DomTreeBuilder::ApplyUpdates</a>.</p>

</div>
</div>

### CalculateFromScratch() {#a91b2ad7a91962494b1608aa174ac8ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch (DomTreeT &amp; DT, <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI)</td>
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



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#a6f4824267c307e103d9ef6c84fd8972f">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::AlwaysDescend</a>, <a href="#acf1f2289b1f5ffbdf55e3f5ac555fed8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::attachNewSubtree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a1c0f3e4b99c65642beff237e454a74fe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::doFullDFSWalk</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo/#a37e6111f7d67481244d8b4da72dd0ee1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdateInfo::IsRecalculated</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo/#a10e855f9a775ee8ec97a4ebf8d056413">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdateInfo::PostViewCFG</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo/#a406eae297a0eccbe8848b8d99232b213">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdateInfo::PreViewCFG</a>, <a href="#a6b01145051cf194d0efb2b7ae241f24c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA</a> and <a href="#a042afbdb3af77ca1c837f901040d8f7c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::SemiNCAInfo</a>.</p>


<p>Referenced by <a href="#a597a58e3cc8ada27fdd127488b9f6d46">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyUpdates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a73e198fec8305bc64938bc784a8f0d1c">llvm::DomTreeBuilder::Calculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a21425ba1759b3e091d72ce8333be2ff1">llvm::DomTreeBuilder::CalculateWithUpdates</a>, <a href="#a82b22baa3199208282b8771c811301bf">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable</a>, <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="#a7f940701e11629de07234b0d717f1e39">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsAfterUpdate</a> and <a href="#a6196ab5eb2faa09361ac7e663765ac88">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsBeforeInsertion</a>.</p>

</div>
</div>

### ComputeUnreachableDominators() {#a364cbe6ed1971f1d63c28607d1731fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ComputeUnreachableDominators (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> Incoming, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a>, <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> &gt; &gt; &amp; DiscoveredConnectingEdges)</td>
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



<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acf1f2289b1f5ffbdf55e3f5ac555fed8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::attachNewSubtree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="#a6b01145051cf194d0efb2b7ae241f24c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA</a> and <a href="#a042afbdb3af77ca1c837f901040d8f7c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::SemiNCAInfo</a>.</p>


<p>Referenced by <a href="#ab24f1fc850ebb24591b52b6e467177a6">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertUnreachable</a>.</p>

</div>
</div>

### DeleteEdge() {#a0733c415f27a3fa6f962bb5d5353ec1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> To)</td>
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



<p>Definition at line 912 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a82b22baa3199208282b8771c811301bf">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable</a>, <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="#a3314013831ea1df71a5408ee6ac032e1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a>, <a href="#a8824d1bacc5dcc91688d442dce6822e0">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasProperSupport</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a7f940701e11629de07234b0d717f1e39">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsAfterUpdate</a>.</p>


<p>Referenced by <a href="#ab4a757a462794e729a37c4cb13278b4c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyNextUpdate</a>, <a href="#a597a58e3cc8ada27fdd127488b9f6d46">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyUpdates</a> and <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a70aa6f22ccb403c6b716d03783275dfd">llvm::DomTreeBuilder::DeleteEdge</a>.</p>

</div>
</div>

### DeleteReachable() {#a82b22baa3199208282b8771c811301bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> FromTN, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> ToTN)</td>
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



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#ab73bfd7dc4d5a446db965380e340810e">llvm::DomTreeNodeBase&lt; NodeT &gt;::getLevel</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a6ab30bb387a6e7086235e9ff7ad01941">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::reattachExistingSubtree</a>, <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="#a6b01145051cf194d0efb2b7ae241f24c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA</a> and <a href="#a042afbdb3af77ca1c837f901040d8f7c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::SemiNCAInfo</a>.</p>


<p>Referenced by <a href="#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a>.</p>

</div>
</div>

### DeleteUnreachable() {#ac0c56f97d07cfa7188e654e794e5032e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> ToTN)</td>
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



<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="#a480cdda4e46458dbca790a5205b0fdcb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#ab73bfd7dc4d5a446db965380e340810e">llvm::DomTreeNodeBase&lt; NodeT &gt;::getLevel</a>, <a href="#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a6ab30bb387a6e7086235e9ff7ad01941">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::reattachExistingSubtree</a>, <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="#a6b01145051cf194d0efb2b7ae241f24c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA</a> and <a href="#a042afbdb3af77ca1c837f901040d8f7c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::SemiNCAInfo</a>.</p>


<p>Referenced by <a href="#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a>.</p>

</div>
</div>

### FindRoots() {#a2867e9240af1e5a7d2a7aabb385a661d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RootsT llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT, <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI)</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#a5c2d1292cd98fa2c253a7f872adc6887">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::addVirtualRoot</a>, <a href="#a6f4824267c307e103d9ef6c84fd8972f">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::AlwaysDescend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae4b78b1bb21ca0057e776215004a579d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/inforec/#aea3bfb4f61599f17708e91db1a0c2be6">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::DFSNum</a>, <a href="#a3314013831ea1df71a5408ee6ac032e1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a>, <a href="#a6f0aaddef3961662a3796cd1afe79da8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::GetEntryNode</a>, <a href="#a16dc433ff2f74c51a76edbffbabdd5bd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getNodeInfo</a>, <a href="#aa26a0ee0a9f0cd627c9a6dc712ae53cb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasForwardSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifydivergentexitnodes-cpp/#aaa253dd3e56c37edd403113782c0ef94">nodes</a>, <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="#a851b359886bf561fb0fde504c228ecea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots</a>, <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="#a042afbdb3af77ca1c837f901040d8f7c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::SemiNCAInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>


<p>Referenced by <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="#a7f940701e11629de07234b0d717f1e39">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsAfterUpdate</a> and <a href="#aeff699bd020f8620eb57bc0ffd9ce847">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyRoots</a>.</p>

</div>
</div>

### getChildren() {#a3314013831ea1df71a5408ee6ac032e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool Inversed&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; NodePtr, 8 &gt; llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren (<a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> N, <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#a3314013831ea1df71a5408ee6ac032e1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/batchupdateinfo/#a406eae297a0eccbe8848b8d99232b213">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::BatchUpdateInfo::PreViewCFG</a>.</p>


<p>Referenced by <a href="#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="#a3314013831ea1df71a5408ee6ac032e1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a>, <a href="#aa26a0ee0a9f0cd627c9a6dc712ae53cb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasForwardSuccessors</a>, <a href="#a8824d1bacc5dcc91688d442dce6822e0">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasProperSupport</a>, <a href="#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a> and <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>.</p>

</div>
</div>

### getChildren() {#a0451f2d011f81c6f8ca840004a66c3fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool Inversed&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; NodePtr, 8 &gt; llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren (<a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> N)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a1926e8e4789f0a0f89add386f65413d1">llvm::detail::reverse_if</a>.</p>

</div>
</div>

### GetEntryNode() {#a6f0aaddef3961662a3796cd1afe79da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodePtr llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::GetEntryNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT)</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a> and <a href="#aeff699bd020f8620eb57bc0ffd9ce847">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyRoots</a>.</p>

</div>
</div>

### HasForwardSuccessors() {#aa26a0ee0a9f0cd627c9a6dc712ae53cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasForwardSuccessors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> N, <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI)</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a3314013831ea1df71a5408ee6ac032e1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a> and <a href="#a851b359886bf561fb0fde504c228ecea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots</a>.</p>

</div>
</div>

### HasProperSupport() {#a8824d1bacc5dcc91688d442dce6822e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasProperSupport (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> TN)</td>
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



<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="#a3314013831ea1df71a5408ee6ac032e1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a>.</p>

</div>
</div>

### InsertEdge() {#ae13a8bd8e24f12a9040cbbc5407d4b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertEdge (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> To)</td>
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



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a>, <a href="#ab24f1fc850ebb24591b52b6e467177a6">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertUnreachable</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#ab4a757a462794e729a37c4cb13278b4c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyNextUpdate</a>, <a href="#a597a58e3cc8ada27fdd127488b9f6d46">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyUpdates</a> and <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#ab5e2b97e90221527d92449f4ac5159f6">llvm::DomTreeBuilder::InsertEdge</a>.</p>

</div>
</div>

### InsertReachable() {#aa1f63192a86614e73a03f83e46813bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> To)</td>
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



<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="#a3314013831ea1df71a5408ee6ac032e1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#ab73bfd7dc4d5a446db965380e340810e">llvm::DomTreeNodeBase&lt; NodeT &gt;::getLevel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a04bc1c8d9cc3496359247eb5f4fa71c4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateInsertion</a> and <a href="#a6196ab5eb2faa09361ac7e663765ac88">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsBeforeInsertion</a>.</p>


<p>Referenced by <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="#ae13a8bd8e24f12a9040cbbc5407d4b87">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertEdge</a> and <a href="#ab24f1fc850ebb24591b52b6e467177a6">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertUnreachable</a>.</p>

</div>
</div>

### InsertUnreachable() {#ab24f1fc850ebb24591b52b6e467177a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertUnreachable (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> To)</td>
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



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#a364cbe6ed1971f1d63c28607d1731fe9">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ComputeUnreachableDominators</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#ae13a8bd8e24f12a9040cbbc5407d4b87">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertEdge</a>.</p>

</div>
</div>

### isPermutation() {#a883785e34f877df86f4408a3aa7f25aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::isPermutation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> &gt; &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a> &gt; &amp; B)</td>
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



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a7f940701e11629de07234b0d717f1e39">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsAfterUpdate</a> and <a href="#aeff699bd020f8620eb57bc0ffd9ce847">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyRoots</a>.</p>

</div>
</div>

### IsSameAsFreshTree() {#a4ea2d791b0cb2b452a1d9ccfaf181712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsSameAsFreshTree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT)</td>
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



<p>Definition at line 1532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1348bf219185f1a9896e890ab4c2061d">llvm::DomTreeBuilder::Verify</a>.</p>

</div>
</div>

### RemoveRedundantRoots() {#a851b359886bf561fb0fde504c228ecea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT, <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="#a49550ef5969f83dc768411af224afb54">RootsT</a> &amp; Roots)</td>
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



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="#a6f4824267c307e103d9ef6c84fd8972f">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::AlwaysDescend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a480cdda4e46458dbca790a5205b0fdcb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa26a0ee0a9f0cd627c9a6dc712ae53cb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasForwardSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a813e82e90438f456f15f75c367ac5b58">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::NumToNode</a>, <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="#a042afbdb3af77ca1c837f901040d8f7c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::SemiNCAInfo</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>.</p>

</div>
</div>

### UpdateInsertion() {#a04bc1c8d9cc3496359247eb5f4fa71c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateInsertion (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> NCD, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/insertioninfo">InsertionInfo</a> &amp; II)</td>
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



<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#ab73bfd7dc4d5a446db965380e340810e">llvm::DomTreeNodeBase&lt; NodeT &gt;::getLevel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a2d97875c33b38014d365da0193d8aa21">llvm::DomTreeNodeBase&lt; NodeT &gt;::setIDom</a> and <a href="#a7f940701e11629de07234b0d717f1e39">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsAfterUpdate</a>.</p>


<p>Referenced by <a href="#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a>.</p>

</div>
</div>

### UpdateRootsAfterUpdate() {#a7f940701e11629de07234b0d717f1e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsAfterUpdate (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI)</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="#a883785e34f877df86f4408a3aa7f25aa">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::isPermutation</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>.</p>


<p>Referenced by <a href="#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a> and <a href="#a04bc1c8d9cc3496359247eb5f4fa71c4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateInsertion</a>.</p>

</div>
</div>

### UpdateRootsBeforeInsertion() {#a6196ab5eb2faa09361ac7e663765ac88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsBeforeInsertion (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4447ba6022e287f5fbef082704f1e2c2">BatchUpdatePtr</a> BUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a> To)</td>
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



<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a>.</p>

</div>
</div>

### VerifyDFSNumbers() {#aba197972422fd98e9318e22f0419e0a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyDFSNumbers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT)</td>
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



<p>Definition at line 1317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a718717ee958956ec34ed177ef0b7f2ba">llvm::DomTreeNodeBase&lt; NodeT &gt;::getDFSNumIn</a>, <a href="#a5614a7f13a1e9158a52c5469ae45e126">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1348bf219185f1a9896e890ab4c2061d">llvm::DomTreeBuilder::Verify</a>.</p>

</div>
</div>

### VerifyLevels() {#a4714e88fbf38f2aaf7fd427dfb17a3a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyLevels (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT)</td>
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



<p>Definition at line 1283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a> and <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#ab73bfd7dc4d5a446db965380e340810e">llvm::DomTreeNodeBase&lt; NodeT &gt;::getLevel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a1348bf219185f1a9896e890ab4c2061d">llvm::DomTreeBuilder::Verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### IsPostDom {#a5614a7f13a1e9158a52c5469ae45e126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsPostDom = DomTreeT::IsPostDominator</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="#a5c2d1292cd98fa2c253a7f872adc6887">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::addVirtualRoot</a>, <a href="#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>, <a href="#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a>, <a href="#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="#a1c0f3e4b99c65642beff237e454a74fe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::doFullDFSWalk</a>, <a href="#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="#ae13a8bd8e24f12a9040cbbc5407d4b87">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertEdge</a>, <a href="#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a>, <a href="#a851b359886bf561fb0fde504c228ecea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots</a>, <a href="#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="#a04bc1c8d9cc3496359247eb5f4fa71c4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateInsertion</a>, <a href="#a7f940701e11629de07234b0d717f1e39">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsAfterUpdate</a>, <a href="#a6196ab5eb2faa09361ac7e663765ac88">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsBeforeInsertion</a>, <a href="#aba197972422fd98e9318e22f0419e0a8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyDFSNumbers</a> and <a href="#aeff699bd020f8620eb57bc0ffd9ce847">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyRoots</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
