---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SUnit` Class

<p>Scheduling unit. This is a node in the scheduling DAG. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">llvm/CodeGen/ScheduleDAG.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &gt;::iterator <a href="#a735fa1e85ee5c8bf992e3e4d27e3d4fe">pred_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &gt;::iterator <a href="#ae97304820cc2fa8743419e91fe326834">succ_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &gt;::const_iterator <a href="#a52b60ed5d8a25d285a41b00544b4047c">const_pred_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &gt;::const_iterator <a href="#a2ac314ec22050f2240611f9150e5bf25">const_succ_iterator</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#a8f6439710f1a1ed00cd98bd9f7809b30">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f654823b1290408013a587551746aa">SUnit</a> (SDNode *node, unsigned nodenum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> for pre-regalloc scheduling to represent an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> and any nodes flagged to it. <a href="#ab6f654823b1290408013a587551746aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> (MachineInstr *instr, unsigned nodenum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> for post-regalloc scheduling to represent a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#a516a65564958ed71cc1e66256604ae44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a placeholder <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#adaadb44f4bcc6e1726089e9862f566c6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7406c398c67e53ee3937bf2b6df1c64e">isBoundaryNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Boundary nodes are placeholders for the boundary of the scheduling region. <a href="#a7406c398c67e53ee3937bf2b6df1c64e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e76b6a72bd49c97aaf9fe170fb829bd">setNode</a> (SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assigns the representative <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> for this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#a1e76b6a72bd49c97aaf9fe170fb829bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac42c5c2e2899b5e891477e415a045503">getNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the representative <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> for this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#ac42c5c2e2899b5e891477e415a045503">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274909b1f31ad2d3d3379de55467d377">isInstr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> refers to a machine instruction as opposed to an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. <a href="#a274909b1f31ad2d3d3379de55467d377">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a869f04a623443a4cf2d2857f9cd085">setInstr</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assigns the instruction for the <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#a5a869f04a623443a4cf2d2857f9cd085">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc98c2c5417cad1a90fc4fe241fe8ba4">getInstr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the representative <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> for this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#afc98c2c5417cad1a90fc4fe241fe8ba4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a> (const SDep &amp;D, bool Required=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the specified edge as a pred of the current node if not already. <a href="#af92bf49ed4846e026e68c380d74d7b15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a10e6734329db955a53b95fcc193cd3">addPredBarrier</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a barrier edge to SU by calling <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred()</a>, with latency 0 generally or latency 1 for a store followed by a load. <a href="#a1a10e6734329db955a53b95fcc193cd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d3233165db1e6be5c44060cd4a95461">removePred</a> (const SDep &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the specified edge as a pred of the current node if it exists. <a href="#a6d3233165db1e6be5c44060cd4a95461">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8926b25df7254ba2730fa5d7ec139862">getDepth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the depth of this node, which is the length of the maximum path up to any node which has no predecessors. <a href="#a8926b25df7254ba2730fa5d7ec139862">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582da862b28b876ef2235781392cffa6">getHeight</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the height of this node, which is the length of the maximum path down to any node which has no successors. <a href="#a582da862b28b876ef2235781392cffa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af14dce27a63c0eb062c23c0ba436249c">setDepthToAtLeast</a> (unsigned NewDepth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If NewDepth is greater than this node's depth value, sets it to be the new depth value. <a href="#af14dce27a63c0eb062c23c0ba436249c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e90fb55a364cbeedab55c95824668bd">setHeightToAtLeast</a> (unsigned NewHeight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If NewHeight is greater than this node's height value, set it to be the new height value. <a href="#a0e90fb55a364cbeedab55c95824668bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb1364902bd813841491d91970ce02b">setDepthDirty</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets a flag in this node to indicate that its stored Depth value will require recomputation the next time <a href="#a8926b25df7254ba2730fa5d7ec139862">getDepth()</a> is called. <a href="#addb1364902bd813841491d91970ce02b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba3791568e29a8d9214ec7dad855a56">setHeightDirty</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets a flag in this node to indicate that its stored Height value will require recomputation the next time <a href="#a582da862b28b876ef2235781392cffa6">getHeight()</a> is called. <a href="#a5ba3791568e29a8d9214ec7dad855a56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe37a9ed7e3ddc88a91b16aa3f83d14">isPred</a> (const SUnit *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if node N is a predecessor of this node. <a href="#a6fe37a9ed7e3ddc88a91b16aa3f83d14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e96694f0d2eef93a9653beba7d12dc">isSucc</a> (const SUnit *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if node N is a successor of this node. <a href="#a65e96694f0d2eef93a9653beba7d12dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0b8da4dfde85d4ddc32359ca52dc493">isTopReady</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac198a5fb130b4c09836ba20e01b4290d">isBottomReady</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa947b755365817fa095e581752a8ae">biasCriticalPath</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Orders this node's predecessor edges such that the critical path edge occurs first. <a href="#a4aa947b755365817fa095e581752a8ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab2e2064b4bde0d5487ddc0d0982f5b9">dumpAttributes</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79335765be06173e9420149dec02b040">ComputeDepth</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates the maximal path from the node to the exit. <a href="#a79335765be06173e9420149dec02b040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e8309c8afd4d77246954d6956082b88">ComputeHeight</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates the maximal path from the node to the entry. <a href="#a2e8309c8afd4d77246954d6956082b88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf66a730d8451aed520907432c069b0">Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Representative node. <a href="#adbf66a730d8451aed520907432c069b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec769bdf426421d19448208e1d1d2e0">Instr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Alternatively, a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#adec769bdf426421d19448208e1d1d2e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46433c376061aaf79670805e7843be0">OrigNode</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If not this, the node from which this node was cloned. <a href="#af46433c376061aaf79670805e7843be0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b2c6049e5141829267f4f9193b475d4">SchedClass</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>nullptr or resolved SchedClass. <a href="#a2b2c6049e5141829267f4f9193b475d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f21db7c66af06c7473b77fd4395b92e">CopyDstRC</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is a special copy node if != nullptr. <a href="#a4f21db7c66af06c7473b77fd4395b92e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6086d9aae5e2c749134b47be689d78">CopySrcRC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b43854b542de66eec6475adc48f56c">Preds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All sunit predecessors. <a href="#ae2b43854b542de66eec6475adc48f56c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab4a86c51e6b126c9c6ef58dbb574431">Succs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All sunit successors. <a href="#aab4a86c51e6b126c9c6ef58dbb574431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f708b119627541f144d703a1d183202">NodeNum</a> = BoundaryID</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Entry # of node in the node vector. <a href="#a3f708b119627541f144d703a1d183202">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a3c0b6567d1e8cf9ac8492e6e5f62f">NodeQueueId</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Queue id of node. <a href="#a26a3c0b6567d1e8cf9ac8492e6e5f62f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25329a072c76c185b8c5ff530c632762">NumPreds</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a6c1a29019b8f3fd988359ec5dd3d2f">NumSuccs</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f78042fbba3ea4cd1004353daa46aa">NumPredsLeft</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c2dfbd170941dd4d20ee9b60c9d49d">NumSuccsLeft</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e02660290b9557b547b57870133467">WeakPredsLeft</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae75d620ee809eaf50970a833f4a3ace9">WeakSuccsLeft</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6f92b9c5aba34d3b07f3ebe229ccff">TopReadyCycle</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> relative to start when node is ready. <a href="#a2a6f92b9c5aba34d3b07f3ebe229ccff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1dfdcdc657e12c47e72d9dbe251ac85">BotReadyCycle</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> relative to end when node is ready. <a href="#aa1dfdcdc657e12c47e72d9dbe251ac85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad11870c750d0016478df39175d3088a1">isVRegCycle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>May use and def the same vreg. <a href="#ad11870c750d0016478df39175d3088a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be1f84d53e90c247d75f2ed63636761">isCall</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is a function call. <a href="#a0be1f84d53e90c247d75f2ed63636761">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ed9422117c4ca9e274a032428a6b8ac">isCallOp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is a function call operand. <a href="#a4ed9422117c4ca9e274a032428a6b8ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8cc028950511d3ae611681975c7831e">isTwoAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is a two-address instruction. <a href="#ac8cc028950511d3ae611681975c7831e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace667b502d54c947cf2f3a4c5d60f734">isCommutable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is a commutable instruction. <a href="#ace667b502d54c947cf2f3a4c5d60f734">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc4d8df3725fd70ffbaffeead756025c">hasPhysRegUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has physreg uses. <a href="#adc4d8df3725fd70ffbaffeead756025c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d9a8b8d5225f85cecbbada4ce4406b0">hasPhysRegDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has physreg defs that are being used. <a href="#a9d9a8b8d5225f85cecbbada4ce4406b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a497fa3b21a696c8abd87e1be3e24229f">hasPhysRegClobbers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has any physreg defs, used or not. <a href="#a497fa3b21a696c8abd87e1be3e24229f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87f2a48b0ca074c06735b969c534349a">isPending</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True once pending. <a href="#a87f2a48b0ca074c06735b969c534349a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90272947a7dad8b452be533c490a5e89">isAvailable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True once available. <a href="#a90272947a7dad8b452be533c490a5e89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c201d7a769bda1cd75d8d6788123068">isScheduled</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True once scheduled. <a href="#a8c201d7a769bda1cd75d8d6788123068">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7faf5b0345dd1c2fd4b60d7f5108f3b5">isScheduleHigh</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if preferable to schedule high. <a href="#a7faf5b0345dd1c2fd4b60d7f5108f3b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95e0c4bc075b7e8974dd9dcc80609487">isScheduleLow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if preferable to schedule low. <a href="#a95e0c4bc075b7e8974dd9dcc80609487">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06b34dc1630e6e1ac6b9336bca455b0e">isCloned</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this node has been cloned. <a href="#a06b34dc1630e6e1ac6b9336bca455b0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac4d36cb59a4bbf5d93513dad0ff0e9">isUnbuffered</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Uses an unbuffered resource. <a href="#a4ac4d36cb59a4bbf5d93513dad0ff0e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76e4a602699ddc57019efaba62a92b6">hasReservedResource</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Uses a reserved resource. <a href="#ab76e4a602699ddc57019efaba62a92b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f8123e14985c7599ffca039e80b70a">NumRegDefsLeft</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e0568b7bf0e9a97260c34264a549a0">Latency</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/node">Node</a> latency. <a href="#a72e0568b7bf0e9a97260c34264a549a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sched/#ab8d854a5ce2331586bcc6830cca52f0f">Sched::Preference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5ecf23b4e7641cbd378b0a2e03e77fd">SchedulingPref</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scheduling preference. <a href="#ab5ecf23b4e7641cbd378b0a2e03e77fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/sunit">llvm::SUnit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace2f273db456493e39f5fbe86123eb8f"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd58dead84edf5d9793b55c28ea51255">Depth</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/node">Node</a> depth. <a href="#abd58dead84edf5d9793b55c28ea51255">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f0207f07d8d6dc6d2cc243d8a6f93dd">Height</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/node">Node</a> height. <a href="#a5f0207f07d8d6dc6d2cc243d8a6f93dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6d5b61ebee8292e9b637ea1fa43b826">isDepthCurrent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if Depth is current. <a href="#ae6d5b61ebee8292e9b637ea1fa43b826">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c632657097cf88ba672bb05da5b0ef7">isHeightCurrent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if Height is current. <a href="#a9c632657097cf88ba672bb05da5b0ef7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048e8567377d69a5e087545d6994c445">isNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the representative is an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. <a href="#a048e8567377d69a5e087545d6994c445">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b2154a3870a53132310f0b001f051c">isInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the representative is a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#ae9b2154a3870a53132310f0b001f051c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Scheduling unit. This is a node in the scheduling DAG.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_pred\_iterator {#a52b60ed5d8a25d285a41b00544b4047c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVectorImpl&lt;SDep&gt;::const_iterator llvm::SUnit::const_pred_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### const\_succ\_iterator {#a2ac314ec22050f2240611f9150e5bf25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVectorImpl&lt;SDep&gt;::const_iterator llvm::SUnit::const_succ_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### pred\_iterator {#a735fa1e85ee5c8bf992e3e4d27e3d4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVectorImpl&lt;SDep&gt;::iterator llvm::SUnit::pred_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### succ\_iterator {#ae97304820cc2fa8743419e91fe326834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVectorImpl&lt;SDep&gt;::iterator llvm::SUnit::succ_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a8f6439710f1a1ed00cd98bd9f7809b30}

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
<td class="doxyEnumItemName">BoundaryID<a id="a8f6439710f1a1ed00cd98bd9f7809b30aff076210765f44b165d39b3f5b8f5a11"></a></td>
<td class="doxyEnumItemDescription"> (= ~0u)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SUnit() {#ab6f654823b1290408013a587551746aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SUnit::SUnit (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * node, unsigned nodenum)</td>
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

<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> for pre-regalloc scheduling to represent an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> and any nodes flagged to it.</p>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a497fa3b21a696c8abd87e1be3e24229f">hasPhysRegClobbers</a>, <a href="#a9d9a8b8d5225f85cecbbada4ce4406b0">hasPhysRegDefs</a>, <a href="#adc4d8df3725fd70ffbaffeead756025c">hasPhysRegUses</a>, <a href="#ab76e4a602699ddc57019efaba62a92b6">hasReservedResource</a>, <a href="#a90272947a7dad8b452be533c490a5e89">isAvailable</a>, <a href="#a0be1f84d53e90c247d75f2ed63636761">isCall</a>, <a href="#a4ed9422117c4ca9e274a032428a6b8ac">isCallOp</a>, <a href="#a06b34dc1630e6e1ac6b9336bca455b0e">isCloned</a>, <a href="#ace667b502d54c947cf2f3a4c5d60f734">isCommutable</a>, <a href="#a87f2a48b0ca074c06735b969c534349a">isPending</a>, <a href="#a8c201d7a769bda1cd75d8d6788123068">isScheduled</a>, <a href="#a7faf5b0345dd1c2fd4b60d7f5108f3b5">isScheduleHigh</a>, <a href="#a95e0c4bc075b7e8974dd9dcc80609487">isScheduleLow</a>, <a href="#ac8cc028950511d3ae611681975c7831e">isTwoAddress</a>, <a href="#a4ac4d36cb59a4bbf5d93513dad0ff0e9">isUnbuffered</a>, <a href="#ad11870c750d0016478df39175d3088a1">isVRegCycle</a>, <a href="#adbf66a730d8451aed520907432c069b0">Node</a>, <a href="#a3f708b119627541f144d703a1d183202">NodeNum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7a116ebf2078ffd98178ffbdd2f544ebb7">llvm::None</a>, <a href="#ab5ecf23b4e7641cbd378b0a2e03e77fd">SchedulingPref</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="#a1a10e6734329db955a53b95fcc193cd3">addPredBarrier</a>, <a href="#a8926b25df7254ba2730fa5d7ec139862">getDepth</a>, <a href="#a582da862b28b876ef2235781392cffa6">getHeight</a>, <a href="#a6fe37a9ed7e3ddc88a91b16aa3f83d14">isPred</a>, <a href="#a65e96694f0d2eef93a9653beba7d12dc">isSucc</a>, <a href="#a6d3233165db1e6be5c44060cd4a95461">removePred</a>, <a href="#addb1364902bd813841491d91970ce02b">setDepthDirty</a> and <a href="#a5ba3791568e29a8d9214ec7dad855a56">setHeightDirty</a>.</p>

</div>
</div>

### SUnit() {#a516a65564958ed71cc1e66256604ae44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SUnit::SUnit (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * instr, unsigned nodenum)</td>
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

<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> for post-regalloc scheduling to represent a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a497fa3b21a696c8abd87e1be3e24229f">hasPhysRegClobbers</a>, <a href="#a9d9a8b8d5225f85cecbbada4ce4406b0">hasPhysRegDefs</a>, <a href="#adc4d8df3725fd70ffbaffeead756025c">hasPhysRegUses</a>, <a href="#ab76e4a602699ddc57019efaba62a92b6">hasReservedResource</a>, <a href="#adec769bdf426421d19448208e1d1d2e0">Instr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktagging-cpp/#a8e818224d2d1de9b995783ff897b0083af12bc59169afda2918e9f23e3501c2b6">instr</a>, <a href="#a90272947a7dad8b452be533c490a5e89">isAvailable</a>, <a href="#a0be1f84d53e90c247d75f2ed63636761">isCall</a>, <a href="#a4ed9422117c4ca9e274a032428a6b8ac">isCallOp</a>, <a href="#a06b34dc1630e6e1ac6b9336bca455b0e">isCloned</a>, <a href="#ace667b502d54c947cf2f3a4c5d60f734">isCommutable</a>, <a href="#a87f2a48b0ca074c06735b969c534349a">isPending</a>, <a href="#a8c201d7a769bda1cd75d8d6788123068">isScheduled</a>, <a href="#a7faf5b0345dd1c2fd4b60d7f5108f3b5">isScheduleHigh</a>, <a href="#a95e0c4bc075b7e8974dd9dcc80609487">isScheduleLow</a>, <a href="#ac8cc028950511d3ae611681975c7831e">isTwoAddress</a>, <a href="#a4ac4d36cb59a4bbf5d93513dad0ff0e9">isUnbuffered</a>, <a href="#ad11870c750d0016478df39175d3088a1">isVRegCycle</a>, <a href="#a3f708b119627541f144d703a1d183202">NodeNum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7a116ebf2078ffd98178ffbdd2f544ebb7">llvm::None</a>, <a href="#ab5ecf23b4e7641cbd378b0a2e03e77fd">SchedulingPref</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

### SUnit() {#adaadb44f4bcc6e1726089e9862f566c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SUnit::SUnit ()</td>
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

<p>Constructs a placeholder <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#a497fa3b21a696c8abd87e1be3e24229f">hasPhysRegClobbers</a>, <a href="#a9d9a8b8d5225f85cecbbada4ce4406b0">hasPhysRegDefs</a>, <a href="#adc4d8df3725fd70ffbaffeead756025c">hasPhysRegUses</a>, <a href="#ab76e4a602699ddc57019efaba62a92b6">hasReservedResource</a>, <a href="#a90272947a7dad8b452be533c490a5e89">isAvailable</a>, <a href="#a0be1f84d53e90c247d75f2ed63636761">isCall</a>, <a href="#a4ed9422117c4ca9e274a032428a6b8ac">isCallOp</a>, <a href="#a06b34dc1630e6e1ac6b9336bca455b0e">isCloned</a>, <a href="#ace667b502d54c947cf2f3a4c5d60f734">isCommutable</a>, <a href="#a87f2a48b0ca074c06735b969c534349a">isPending</a>, <a href="#a8c201d7a769bda1cd75d8d6788123068">isScheduled</a>, <a href="#a7faf5b0345dd1c2fd4b60d7f5108f3b5">isScheduleHigh</a>, <a href="#a95e0c4bc075b7e8974dd9dcc80609487">isScheduleLow</a>, <a href="#ac8cc028950511d3ae611681975c7831e">isTwoAddress</a>, <a href="#a4ac4d36cb59a4bbf5d93513dad0ff0e9">isUnbuffered</a>, <a href="#ad11870c750d0016478df39175d3088a1">isVRegCycle</a>, <a href="#adbf66a730d8451aed520907432c069b0">Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a24c2247bd546fc56e2de6cfd04a3d7a116ebf2078ffd98178ffbdd2f544ebb7">llvm::None</a> and <a href="#ab5ecf23b4e7641cbd378b0a2e03e77fd">SchedulingPref</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPred() {#af92bf49ed4846e026e68c380d74d7b15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SUnit::addPred (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; D, bool Required=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds the specified edge as a pred of the current node if not already.</p>


<p>It also adds the current node as a successor of the specified node.</p>


<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="#a8c201d7a769bda1cd75d8d6788123068">isScheduled</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a25329a072c76c185b8c5ff530c632762">NumPreds</a>, <a href="#a94f78042fbba3ea4cd1004353daa46aa">NumPredsLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#ae2b43854b542de66eec6475adc48f56c">Preds</a>, <a href="#addb1364902bd813841491d91970ce02b">setDepthDirty</a>, <a href="#a5ba3791568e29a8d9214ec7dad855a56">setHeightDirty</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#aaa4f7e2f3f5a23ecf19b98acd3c05593">llvm::SDep::setSUnit</a>, <a href="#aab4a86c51e6b126c9c6ef58dbb574431">Succs</a>, <a href="#ab6f654823b1290408013a587551746aa">SUnit</a> and <a href="#ab9e02660290b9557b547b57870133467">WeakPredsLeft</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aee33e06ea8865a2fb2bf229325c07194">llvm::ScheduleDAGInstrs::addChainDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a86bfa4838cb7e42648615d27c94c8017">llvm::ScheduleDAGInstrs::addEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledagfast/#a92723fbc9b5347da67a06b63043fcff9">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::AddPred</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist/#a81edbd7ea9536622badd16797bb7fb9c">anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::AddPred</a>, <a href="#a1a10e6734329db955a53b95fcc193cd3">addPredBarrier</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist/#ab0b0b9b17a48e53bd335408d459656f9">anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::AddPredQueued</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>.</p>

</div>
</div>

### addPredBarrier() {#a1a10e6734329db955a53b95fcc193cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::addPredBarrier (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Adds a barrier edge to SU by calling <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred()</a>, with latency 0 generally or latency 1 for a store followed by a load.</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a551060cb0333d9d0cfdacd2576d817b9a3d026b42ef4cc00c58dd954b3c5eda65">llvm::SDep::Barrier</a>, <a href="#afc98c2c5417cad1a90fc4fe241fe8ba4">getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### biasCriticalPath() {#a4aa947b755365817fa095e581752a8ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SUnit::biasCriticalPath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Orders this node's predecessor edges such that the critical path edge occurs first.</p>

<p>Declaration at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a25329a072c76c185b8c5ff530c632762">NumPreds</a>, <a href="#ae2b43854b542de66eec6475adc48f56c">Preds</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### dumpAttributes() {#aab2e2064b4bde0d5487ddc0d0982f5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SUnit::dumpAttributes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8926b25df7254ba2730fa5d7ec139862">getDepth</a>, <a href="#a582da862b28b876ef2235781392cffa6">getHeight</a>, <a href="#a72e0568b7bf0e9a97260c34264a549a0">Latency</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="#a94f78042fbba3ea4cd1004353daa46aa">NumPredsLeft</a>, <a href="#a74f8123e14985c7599ffca039e80b70a">NumRegDefsLeft</a>, <a href="#a40c2dfbd170941dd4d20ee9b60c9d49d">NumSuccsLeft</a>, <a href="#ab9e02660290b9557b547b57870133467">WeakPredsLeft</a> and <a href="#ae75d620ee809eaf50970a833f4a3ace9">WeakSuccsLeft</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a917f4d40ed0bbdaf4ab50e5df4de067b">llvm::ScheduleDAG::dumpNodeAll</a>.</p>

</div>
</div>

### getDepth() {#a8926b25df7254ba2730fa5d7ec139862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::getDepth ()</td>
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

<p>Returns the depth of this node, which is the length of the maximum path up to any node which has no predecessors.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#ab7263c22653c86a22ff72bc5385e8835">llvm::AggressiveAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#a9724d87887d705995d775dfec0402648">BUCompareLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af872650583e3ccb09205d6a9832026b2">BUCompareLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp/#a4bfac8dc3460d1e7628eba4c5d6e4a12">CriticalPathStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp/#a4fcfebf71584254d08e964c5964ccf7e">CriticalPathStep</a>, <a href="#aab2e2064b4bde0d5487ddc0d0982f5b9">dumpAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult/#a5269b7fe10c17e55d827eaf49ab3f2c8">llvm::SchedDFSResult::getILP</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#af7a9c62acba4010b5c47f12f458eaf00">llvm::SchedBoundary::getUnscheduledLatency</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#a22fcbadc45fff4fab6990448ae152ee9">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::isLatencyBound</a>, <a href="/web-llvm/docs/api/structs/anonymous-scheduledagrrlist-cpp-/ilp-ls-rr-sort/#a79b85bbc0a0fbf047dcef83891e4b9e4">anonymous{ScheduleDAGRRList.cpp}::ilp_ls_rr_sort::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ac047246e76df6b86564a6b62c2403aef">llvm::GenericScheduler::registerRoots</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#aee5ca47cbb46d1237ce496179411b03e">llvm::PostGenericScheduler::registerRoots</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="#af14dce27a63c0eb062c23c0ba436249c">setDepthToAtLeast</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9a83bf7b5f6e85f215ff07a31e0fbe">llvm::tryLatency</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ab464241184b77be167ff521aa2552e29">llvm::ScheduleDAG::VerifyScheduledDAG</a>.</p>

</div>
</div>

### getHeight() {#a582da862b28b876ef2235781392cffa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::getHeight ()</td>
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

<p>Returns the height of this node, which is the length of the maximum path down to any node which has no successors.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#a9724d87887d705995d775dfec0402648">BUCompareLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af872650583e3ccb09205d6a9832026b2">BUCompareLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpriorityqueue/#ac71475df20b58e4c313134e73ed1ddad">anonymous{ScheduleDAGRRList.cpp}::RegReductionPriorityQueue&lt; bu_ls_rr_sort &gt;::dump</a>, <a href="#aab2e2064b4bde0d5487ddc0d0982f5b9">dumpAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#af7a9c62acba4010b5c47f12f458eaf00">llvm::SchedBoundary::getUnscheduledLatency</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#a22fcbadc45fff4fab6990448ae152ee9">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::isLatencyBound</a>, <a href="/web-llvm/docs/api/structs/anonymous-scheduledagrrlist-cpp-/hybrid-ls-rr-sort/#aa5ca882e6890a39e19f858e25d32e49c">anonymous{ScheduleDAGRRList.cpp}::hybrid_ls_rr_sort::isReady</a>, <a href="/web-llvm/docs/api/structs/anonymous-scheduledagrrlist-cpp-/ilp-ls-rr-sort/#a6e62f12a56efd07685870a1acd81af4a">anonymous{ScheduleDAGRRList.cpp}::ilp_ls_rr_sort::isReady</a>, <a href="/web-llvm/docs/api/structs/anonymous-scheduledagrrlist-cpp-/ilp-ls-rr-sort/#a79b85bbc0a0fbf047dcef83891e4b9e4">anonymous{ScheduleDAGRRList.cpp}::ilp_ls_rr_sort::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzpostraschedstrategy/#a0e0a14434477222a57a6e5e09b1f0f2f">llvm::SystemZPostRASchedStrategy::pickNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnilpsched-cpp-/gcnilpscheduler/#a701a79471c4c9a778d88f103f3bfdcbf">anonymous{GCNILPSched.cpp}::GCNILPScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="#a0e90fb55a364cbeedab55c95824668bd">setHeightToAtLeast</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9a83bf7b5f6e85f215ff07a31e0fbe">llvm::tryLatency</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ab464241184b77be167ff521aa2552e29">llvm::ScheduleDAG::VerifyScheduledDAG</a>.</p>

</div>
</div>

### getInstr() {#afc98c2c5417cad1a90fc4fe241fe8ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::SUnit::getInstr ()</td>
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

<p>Returns the representative <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> for this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>


<p>This may be used during post-regalloc scheduling.</p>


<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adec769bdf426421d19448208e1d1d2e0">Instr</a> and <a href="#adbf66a730d8451aed520907432c069b0">Node</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a3fc9d4b37a6b504d811aef63bef4a80c">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::add</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aee33e06ea8865a2fb2bf229325c07194">llvm::ScheduleDAGInstrs::addChainDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="#a1a10e6734329db955a53b95fcc193cd3">addPredBarrier</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a0f958ee7dc9902af4093fe8fabbabd6e">llvm::ScheduleDAGInstrs::addVRegUseDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#af6b0c8c54226e0aafa107e5e92c813a2">anonymous{MachineScheduler.cpp}::CopyConstrain::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-macrofusion-cpp-/macrofusion/#a0118b89885857d60368b7bdfe36f268d">anonymous{MacroFusion.cpp}::MacroFusion::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad05686602c5ba519cd9fdaf2dad9bed8">llvm::ARMOverrideBypasses::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/hvxmemlatencymutation/#a9c1fcebee584af05ce009b20aeab417b">llvm::HexagonSubtarget::HVXMemLatencyMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvvectormaskdagmutation/#aefb8f35660662022da36962fb6655058">llvm::RISCVVectorMaskDAGMutation::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb4b9423201406d79ba16481c90cb6cb">llvm::biasPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#ab7263c22653c86a22ff72bc5385e8835">llvm::AggressiveAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#a5a71ccecb00de06004fb421a568dd7b4">llvm::CriticalAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#a5049c1efdcf61c9406251e4c41db15e0">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#a13a8c4d3fbc72e8e2f7080411e2ea9cf">llvm::ResourceManager::calculateResMII</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a421fd1809b1aac21f487386d00e89294">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::canAddSU</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a284b9287f16ce98d3063620d92f54700">llvm::HexagonPacketizerList::canPromoteToDotCur</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a87edaaaaa788f8bc30dfad90aecdb343">llvm::HexagonPacketizerList::canPromoteToDotNew</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a9085e6f205a2f9604a6458faa9a18d49">llvm::HexagonPacketizerList::canPromoteToNewValue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#adfd05fb40b63f3fde78a81e119ed89e3">llvm::ResourceManager::canReserveResources</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#aba393b0035b052e3477fc32a72643750">canUsePressureDiffs</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#af46e7864fe409ea4ae6b1b56e8baa9a1">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::checkHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#adb8558f52662b83fe081b34b1f31fb20">llvm::SchedBoundary::checkHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a920652e64042f72e913f81f9660b4f2f">llvm::ScheduleDAGMILive::collectVRegUses</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a3fb8c57a2275283cbb376004421318da">computeLiveOuts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a4923617d2f897074725d389de4f450de">computeScheduledInsts</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#acfd4efd1c9f1a0174bd6f3942238c51b">llvm::SMSchedule::computeStart</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aa5f22315c4064579fca6cd88fb36ea5a">llvm::ScheduleDAGInstrs::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a8a2ae56dfdc087ade919e8712369134a">llvm::SystemZHazardRecognizer::dumpSU</a>, <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#a4a4c40e81d31e50617db9eb227bc1707">llvm::ARMBankConflictHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armhazardrecognizerfpmlx/#a02020976b23770cda65006bf01ea5e41">llvm::ARMHazardRecognizerFPMLx::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#a7752890a080ddcf0671bdab4a9e3241e">llvm::GCNHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aafc82eb49e1de126caa8907eaca9f46e">llvm::HexagonHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#afe71af95c1e795a56d13e488898d58f5">llvm::PPCHazardRecognizer970::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#ae8b6eb92a49f95a3bc79199f0768de4a">llvm::SystemZHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#ab9c7e76fda2b142c09da3ca892884acd">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#aff7649124c08f77b72e5d539f2f8afdf">llvm::SMSchedule::finalizeSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#afbb37cc24abd3ed381b0fd496351bd17">llvm::ScheduleDAGInstrs::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#abd3b799a5199979babb67c1211b73c7c">llvm::ARMBankConflictHazardRecognizer::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/armhazardrecognizerfpmlx/#af1064d4637b93e114f1d15631abdc03f">llvm::ARMHazardRecognizerFPMLx::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#ad798e3928656e87abcacbf5f7dd47dbe">llvm::GCNHazardRecognizer::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aab1697feb9d87e4e53478bb751de708e">llvm::HexagonHazardRecognizer::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#a930f5688f2bff088096f72a68000c94e">llvm::PPCHazardRecognizer970::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a100d476a583a34879b296908da01fdac">llvm::ScheduleDAG::getInstrDesc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#ad44f2f8547867c4e68c4476168d030a5">getMachineInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcniterativescheduler-cpp/#a0fa0483da536791ba511c116dc3f06fa">getMachineInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#ad8dc903ae7dd7695e082f3d3fb80be92">getRegisterPressures</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4bf5573660c55924d68b517a0e9b4554">llvm::ScheduleDAGInstrs::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a4a0f2858cdd379056abfa2531e7da961">llvm::SystemZHazardRecognizer::getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a35ad2560fecc16262b15e21c9375cf3d">llvm::GCNSchedStage::getScheduleMetrics</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a0fdaca7e15aaaa6d903d0498220b8cc1">llvm::SystemZHazardRecognizer::groupingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonvliwresourcemodel/#aa66dd2a7692adf3c952cd70ea8a43641">llvm::HexagonVLIWResourceModel::hasDependence</a>, <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a705a0975de8335b0b6bdbbae165e8f5c">llvm::ScheduleDAGInstrs::initSUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a2eff58d9105525f19d5cbe2fa6969d6e">llvm::SMSchedule::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp/#a39cb081a14bceac85a10e7a987109c1f">isADDIInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#a0a4dd89f625a6f7a354c0a5994114d1a">anonymous{AMDGPUExportClustering.cpp}::isExport</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ae14c145aa6237db91a7bca044488de25">anonymous{R600Packetizer.cpp}::R600PacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a49f30830f4e853ee33ad7b021d0f5403">llvm::HexagonPacketizerList::isLegalToPruneDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae6911f11b05121e2c0deb7e45a6de110">llvm::SMSchedule::isLoopCarried</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#a50ac9b7a39c6896200c312ccd78206bc">anonymous{AMDGPUExportClustering.cpp}::isPositionExport</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel/#afa113683bb9cebc99c2711ac4a4c36dd">llvm::VLIWResourceModel::isResourceAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad1ced720461881db2f1371e0f30ff744">llvm::ARMOverrideBypasses::makeBundleAssumptions</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a120fc86306882eb2bd3c27c9f4063fd6">llvm::ARMOverrideBypasses::memoryRAWHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#a6c67a87b5b8b7338e197f5bb29767019">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae26138aceef07cf5465c2840b437e1d8">llvm::SMSchedule::normalizeNonPipelinedInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a70c8219e8d9627e2373f281be45f96ae">llvm::SMSchedule::orderDependence</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#acfb2315913d694fb3f1144279ab75a85">llvm::VLIWPacketizerList::PacketizeMIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/ilpscheduler/#a636abcad4364da7508f5fdce3bbf40e7">anonymous{MachineScheduler.cpp}::ILPScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad4cc558b6cbcc4e9cea5df915c197e14">llvm::GenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#af8a37b0efa51cfd3f6b4729e3298de7f">llvm::PostGenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a3460671809bfea01d71388f2e45c3c50">llvm::SMSchedule::print</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a241c866b4c0500ad383acfd1d87d3983">llvm::ConvergingVLIWScheduler::releaseBottomNode</a>, <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#a4ae49efe3ba813f5cb7a746245b9b0e1">llvm::R600SchedStrategy::releaseBottomNode</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a751090565ab555f2738aec07bc1a350c">llvm::SchedBoundary::releaseNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a02320b2fe86927bf0dc6486f7c7faffa">llvm::SMSchedule::reorderInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad04f609cdff2331741525e5328836598">llvm::GenericScheduler::reschedulePhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#a66b0369aaa8c87a6969ec5b56700d0d8">llvm::ResourceManager::reserveResources</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel/#a6641c29e6f96fdf149d7f9f5dddec48f">llvm::VLIWResourceModel::reserveResources</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a886677d13d24c974e4cb3086df524e7b">llvm::GCNSchedStrategy::schedNode</a>, <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#abe1c22281512c39286cbb9bca97ae7b8">llvm::R600SchedStrategy::schedNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a5d7e71cf32573e6b1762b5a1d82a1cf5">llvm::ScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduleblock/#ad90a3deb55c0f82327a4ef72bd874948">llvm::SIScheduleBlock::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a5b1da83188ad8ac357edfd719ce2680f">llvm::HexagonConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#accfcd00e03bf4fddc4d3b32657c3e291">llvm::GCNHazardRecognizer::ShouldPreferAnother</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aa7aeeaeea47cbad621b11556e9b19839">llvm::HexagonHazardRecognizer::ShouldPreferAnother</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64postraschedstrategy/#a13b69f0a0d56eb5e0802e40b938136a6">llvm::AArch64PostRASchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a062ea093e135121a384a1c6c4cd3d96c">llvm::HexagonPacketizerList::updateOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a19e83509e45ee65e4495de5a3ed3d44a">llvm::SchedDFSImpl::visitPostorderNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#aee17a5350fad1c56abf6f425ef4f6e92">llvm::SchedDFSImpl::visitPreorder</a>.</p>

</div>
</div>

### getNode() {#ac42c5c2e2899b5e891477e415a045503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * llvm::SUnit::getNode ()</td>
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

<p>Returns the representative <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> for this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>


<p>This may be used during pre-regalloc scheduling.</p>


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adec769bdf426421d19448208e1d1d2e0">Instr</a> and <a href="#adbf66a730d8451aed520907432c069b0">Node</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a4ba2ac7568356ddd4b07a7f1718c8d6a">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::canClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a6a91ff524836d3fca6cabe37c8fb7dc5">canClobberPhysRegDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a07e9d7ff453553fd3e5e64c9d93d5d07">canEnableCoalescing</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6ab45d1027ab01be9c371634c49d077b">llvm::ScheduleDAGSDNodes::computeLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ab34667f1d218ea0b6566dd8f861dfe93">llvm::ScheduleDAGSDNodes::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a8cbdb500ba4abd11fd23de4e7a020a2d">llvm::ScheduleDAGSDNodes::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a100d476a583a34879b296908da01fdac">llvm::ScheduleDAG::getInstrDesc</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a2b381affe49c1a381183698a2a69aec9">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::getNodeOrdering</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a9ae4cee3cd6aafb475565cb82d033b40">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::getNodePriority</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a16fdb3e37daf197199709a37540402d0">hasOnlyLiveInOpers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a22c99596004378b139e9ab48fae048dc">hasOnlyLiveOutUses</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae40b5614303ad840c02bf2923d5f4305">llvm::ResourcePriorityQueue::initNumRegDefsLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#aa405be8f26bc0ffcd089589d15327400">isOperandOf</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#afba9f58251019a23a1d7f60d6c958071">llvm::ResourcePriorityQueue::isResourceAvailable</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#aaae720d8a55a2ddf5a3b795d2a82805a">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::MayReduceRegPressure</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a7be640126e3f1024b18981f1de2de20f">llvm::ResourcePriorityQueue::rawRegPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a810f1b98c4887804780355393149e783">llvm::ResourcePriorityQueue::regPressureDelta</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a1b480aa4515358bac44d9281c7f74471">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::RegPressureDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae30e9e0cfb98797266d9fc1226cf467d">llvm::ResourcePriorityQueue::reserveResources</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a420129a3b8db368bc6768ddb7293255d">resetVRegCycle</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6ccdfe5633d79d327d704b14f7b83235">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>.</p>

</div>
</div>

### isBottomReady() {#ac198a5fb130b4c09836ba20e01b4290d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isBottomReady ()</td>
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



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#a40c2dfbd170941dd4d20ee9b60c9d49d">NumSuccsLeft</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a3bee087d8d270d2eb8823dc5b9dd4e0e">llvm::ConvergingVLIWScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad4cc558b6cbcc4e9cea5df915c197e14">llvm::GenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#af8a37b0efa51cfd3f6b4729e3298de7f">llvm::PostGenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a5d7e71cf32573e6b1762b5a1d82a1cf5">llvm::ScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>.</p>

</div>
</div>

### isBoundaryNode() {#a7406c398c67e53ee3937bf2b6df1c64e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isBoundaryNode ()</td>
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

<p>Boundary nodes are placeholders for the boundary of the scheduling region.</p>


<p>BoundaryNodes can have DAG edges, including Data edges, but they do not correspond to schedulable entities (e.g. instructions) and do not have a valid <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. Consequently, always check for boundary nodes before accessing an associative data structure keyed on node <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#a3f708b119627541f144d703a1d183202">NodeNum</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad05686602c5ba519cd9fdaf2dad9bed8">llvm::ARMOverrideBypasses::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult/#a788b324b6deb10dfbafa68a351b11c79">llvm::SchedDFSResult::compute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#acdcfdf9ee94eb9275888de3e3dec1a77">computePath</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a346955acdf30b0ecf7f58b3ba9e32129">llvm::ScheduleDAGTopologicalSort::GetSubGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a26aca145a8f6953152a566a143c6ec8f">hasDataSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae7d28b348c77e17419b65d3f3d7d55a4">llvm::SMSchedule::latestCycleInChain</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#a6c67a87b5b8b7338e197f5bb29767019">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>.</p>

</div>
</div>

### isInstr() {#a274909b1f31ad2d3d3379de55467d377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isInstr ()</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> refers to a machine instruction as opposed to an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>.</p>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#adec769bdf426421d19448208e1d1d2e0">Instr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/usroverflowmutation/#af2918620aeda858e99c7fac5f1e9eb16">llvm::HexagonSubtarget::UsrOverflowMutation::apply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#aba393b0035b052e3477fc32a72643750">canUsePressureDiffs</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a100d476a583a34879b296908da01fdac">llvm::ScheduleDAG::getInstrDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae26138aceef07cf5465c2840b437e1d8">llvm::SMSchedule::normalizeNonPipelinedInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a5b1da83188ad8ac357edfd719ce2680f">llvm::HexagonConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnhazardrecognizer/#accfcd00e03bf4fddc4d3b32657c3e291">llvm::GCNHazardRecognizer::ShouldPreferAnother</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aa7aeeaeea47cbad621b11556e9b19839">llvm::HexagonHazardRecognizer::ShouldPreferAnother</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### isPred() {#a6fe37a9ed7e3ddc88a91b16aa3f83d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isPred (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * N)</td>
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

<p>Tests if node N is a predecessor of this node.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ae2b43854b542de66eec6475adc48f56c">Preds</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smschedule/#acfd4efd1c9f1a0174bd6f3942238c51b">llvm::SMSchedule::computeStart</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>.</p>

</div>
</div>

### isSucc() {#a65e96694f0d2eef93a9653beba7d12dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isSucc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * N)</td>
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

<p>Tests if node N is a successor of this node.</p>

<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#aab4a86c51e6b126c9c6ef58dbb574431">Succs</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0256920aada1bf35dc3c90cbfba10e5d">llvm::HexagonPacketizerList::arePredicatesComplements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ae14c145aa6237db91a7bca044488de25">anonymous{R600Packetizer.cpp}::R600PacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a642903485b484d638fafe7da8142cdd8">llvm::HexagonPacketizerList::restrictingDepExistInPacket</a>.</p>

</div>
</div>

### isTopReady() {#ae0b8da4dfde85d4ddc32359ca52dc493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isTopReady ()</td>
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



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#a94f78042fbba3ea4cd1004353daa46aa">NumPredsLeft</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a3bee087d8d270d2eb8823dc5b9dd4e0e">llvm::ConvergingVLIWScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad4cc558b6cbcc4e9cea5df915c197e14">llvm::GenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#af8a37b0efa51cfd3f6b4729e3298de7f">llvm::PostGenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a5d7e71cf32573e6b1762b5a1d82a1cf5">llvm::ScheduleDAGMI::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>.</p>

</div>
</div>

### removePred() {#a6d3233165db1e6be5c44060cd4a95461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SUnit::removePred (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes the specified edge as a pred of the current node if it exists.</p>


<p>It also removes the current node as a successor of the specified node.</p>


<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a8c201d7a769bda1cd75d8d6788123068">isScheduled</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a25329a072c76c185b8c5ff530c632762">NumPreds</a>, <a href="#a94f78042fbba3ea4cd1004353daa46aa">NumPredsLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#ae2b43854b542de66eec6475adc48f56c">Preds</a>, <a href="#addb1364902bd813841491d91970ce02b">setDepthDirty</a>, <a href="#a5ba3791568e29a8d9214ec7dad855a56">setHeightDirty</a>, <a href="#ab6f654823b1290408013a587551746aa">SUnit</a> and <a href="#ab9e02660290b9557b547b57870133467">WeakPredsLeft</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/usroverflowmutation/#af2918620aeda858e99c7fac5f1e9eb16">llvm::HexagonSubtarget::UsrOverflowMutation::apply</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#ac88025eb8866478014f41b34cd29b593">anonymous{AMDGPUExportClustering.cpp}::removeExportDependencies</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledagfast/#ae0a1220d91f44079aa52746ac160c2e4">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::RemovePred</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist/#a3a3d1204e84d95a7bf978e1f3bc1debe">anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::RemovePred</a>.</p>

</div>
</div>

### setDepthDirty() {#addb1364902bd813841491d91970ce02b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SUnit::setDepthDirty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets a flag in this node to indicate that its stored Depth value will require recomputation the next time <a href="#a8926b25df7254ba2730fa5d7ec139862">getDepth()</a> is called.</p>

<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#aab4a86c51e6b126c9c6ef58dbb574431">Succs</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>


<p>Referenced by <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="#a6d3233165db1e6be5c44060cd4a95461">removePred</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a252bd3038d4cc84ade6e24b656bd4655">llvm::ARMOverrideBypasses::setBidirLatencies</a> and <a href="#af14dce27a63c0eb062c23c0ba436249c">setDepthToAtLeast</a>.</p>

</div>
</div>

### setDepthToAtLeast() {#af14dce27a63c0eb062c23c0ba436249c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SUnit::setDepthToAtLeast (unsigned NewDepth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If NewDepth is greater than this node's depth value, sets it to be the new depth value.</p>


<p>This also recursively marks successor nodes dirty.</p>


<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="#a8926b25df7254ba2730fa5d7ec139862">getDepth</a> and <a href="#addb1364902bd813841491d91970ce02b">setDepthDirty</a>.</p>

</div>
</div>

### setHeightDirty() {#a5ba3791568e29a8d9214ec7dad855a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SUnit::setHeightDirty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets a flag in this node to indicate that its stored Height value will require recomputation the next time <a href="#a582da862b28b876ef2235781392cffa6">getHeight()</a> is called.</p>

<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="#ae2b43854b542de66eec6475adc48f56c">Preds</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>


<p>Referenced by <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/hvxmemlatencymutation/#a9c1fcebee584af05ce009b20aeab417b">llvm::HexagonSubtarget::HVXMemLatencyMutation::apply</a>, <a href="#a6d3233165db1e6be5c44060cd4a95461">removePred</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a252bd3038d4cc84ade6e24b656bd4655">llvm::ARMOverrideBypasses::setBidirLatencies</a> and <a href="#a0e90fb55a364cbeedab55c95824668bd">setHeightToAtLeast</a>.</p>

</div>
</div>

### setHeightToAtLeast() {#a0e90fb55a364cbeedab55c95824668bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SUnit::setHeightToAtLeast (unsigned NewHeight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If NewHeight is greater than this node's height value, set it to be the new height value.</p>


<p>This also recursively marks predecessor nodes dirty.</p>


<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="#a582da862b28b876ef2235781392cffa6">getHeight</a> and <a href="#a5ba3791568e29a8d9214ec7dad855a56">setHeightDirty</a>.</p>

</div>
</div>

### setInstr() {#a5a869f04a623443a4cf2d2857f9cd085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SUnit::setInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Assigns the instruction for the <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>


<p>This may be used during post-regalloc scheduling.</p>


<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adec769bdf426421d19448208e1d1d2e0">Instr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>.</p>

</div>
</div>

### setNode() {#a1e76b6a72bd49c97aaf9fe170fb829bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SUnit::setNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Assigns the representative <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> for this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>


<p>This may be used during pre-regalloc scheduling.</p>


<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#adbf66a730d8451aed520907432c069b0">Node</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ComputeDepth() {#a79335765be06173e9420149dec02b040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SUnit::ComputeDepth ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculates the maximal path from the node to the exit.</p>

<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>

</div>
</div>

### ComputeHeight() {#a2e8309c8afd4d77246954d6956082b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SUnit::ComputeHeight ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculates the maximal path from the node to the entry.</p>

<p>Declaration at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BotReadyCycle {#aa1dfdcdc657e12c47e72d9dbe251ac85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::BotReadyCycle = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> relative to end when node is ready.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aa5f22315c4064579fca6cd88fb36ea5a">llvm::ScheduleDAGInstrs::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a942d716003056c037d46a4144e9cf885">llvm::ScheduleDAGMI::dumpScheduleTraceBottomUp</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a4a674627365b72b17a9b2e0a99d40ce1">llvm::SchedBoundary::getLatencyStallCycles</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a241c866b4c0500ad383acfd1d87d3983">llvm::ConvergingVLIWScheduler::releaseBottomNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a779430fb54fa19f8bf9d94d1618bf7f5">llvm::GenericScheduler::releaseBottomNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ac32bc6bea26f0dc3cc421145f6c41af6">llvm::PostGenericScheduler::releaseBottomNode</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#a7f64e612634009b7ced96fbf06f6b445">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::releasePending</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a155166a788cfe0d992af6f2e21e6118e">llvm::SchedBoundary::releasePending</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1c51776d4e512a7f24d5b5d601c31016">llvm::ScheduleDAGMI::releasePred</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#ab76f5e165cdf261f940b854e739a789b">llvm::ConvergingVLIWScheduler::schedNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#adf574ab3455d7292bed998d8ba50bfeb">llvm::GenericScheduler::schedNode</a> and <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a19c13266ab002ad2ce608573c4d2c98e">llvm::PostGenericScheduler::schedNode</a>.</p>

</div>
</div>

### CopyDstRC {#a4f21db7c66af06c7473b77fd4395b92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass* llvm::SUnit::CopyDstRC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is a special copy node if != nullptr.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
        nullptr
</div>
</dd>
</dl>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### CopySrcRC {#abc6086d9aae5e2c749134b47be689d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass* llvm::SUnit::CopySrcRC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### hasPhysRegClobbers {#a497fa3b21a696c8abd87e1be3e24229f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::hasPhysRegClobbers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has any physreg defs, used or not.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### hasPhysRegDefs {#a9d9a8b8d5225f85cecbbada4ce4406b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::hasPhysRegDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has physreg defs that are being used.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a7c7d5ab8d9814b721a1844a867ef948a">llvm::SMSchedule::isValidSchedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#adf574ab3455d7292bed998d8ba50bfeb">llvm::GenericScheduler::schedNode</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### hasPhysRegUses {#adc4d8df3725fd70ffbaffeead756025c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::hasPhysRegUses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has physreg uses.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#adf574ab3455d7292bed998d8ba50bfeb">llvm::GenericScheduler::schedNode</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### hasReservedResource {#ab76e4a602699ddc57019efaba62a92b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::hasReservedResource</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Uses a reserved resource.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#adb8558f52662b83fe081b34b1f31fb20">llvm::SchedBoundary::checkHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a47377e7e9aaf5a00affe4f4d8ec61f3e">llvm::SystemZHazardRecognizer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a705a0975de8335b0b6bdbbae165e8f5c">llvm::ScheduleDAGInstrs::initSUnits</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### Instr {#adec769bdf426421d19448208e1d1d2e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::SUnit::Instr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Alternatively, a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#afc98c2c5417cad1a90fc4fe241fe8ba4">getInstr</a>, <a href="#ac42c5c2e2899b5e891477e415a045503">getNode</a>, <a href="#a274909b1f31ad2d3d3379de55467d377">isInstr</a>, <a href="#a5a869f04a623443a4cf2d2857f9cd085">setInstr</a> and <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a>.</p>

</div>
</div>

### isAvailable {#a90272947a7dad8b452be533c490a5e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isAvailable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True once available.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### isCall {#a0be1f84d53e90c247d75f2ed63636761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isCall</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is a function call.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#a5049c1efdcf61c9406251e4c41db15e0">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#ae8b6eb92a49f95a3bc79199f0768de4a">llvm::SystemZHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a47377e7e9aaf5a00affe4f4d8ec61f3e">llvm::SystemZHazardRecognizer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a705a0975de8335b0b6bdbbae165e8f5c">llvm::ScheduleDAGInstrs::initSUnits</a>, <a href="/web-llvm/docs/api/structs/anonymous-scheduledagrrlist-cpp-/hybrid-ls-rr-sort/#a6c60423438d42b5bf6f8bbe15b7c5a91">anonymous{ScheduleDAGRRList.cpp}::hybrid_ls_rr_sort::operator()</a>, <a href="/web-llvm/docs/api/structs/anonymous-scheduledagrrlist-cpp-/ilp-ls-rr-sort/#a79b85bbc0a0fbf047dcef83891e4b9e4">anonymous{ScheduleDAGRRList.cpp}::ilp_ls_rr_sort::operator()</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### isCallOp {#a4ed9422117c4ca9e274a032428a6b8ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isCallOp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is a function call operand.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a9ae4cee3cd6aafb475565cb82d033b40">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::getNodePriority</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### isCloned {#a06b34dc1630e6e1ac6b9336bca455b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isCloned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this node has been cloned.</p>

<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### isCommutable {#ace667b502d54c947cf2f3a4c5d60f734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isCommutable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is a commutable instruction.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a705a0975de8335b0b6bdbbae165e8f5c">llvm::ScheduleDAGInstrs::initSUnits</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### isPending {#a87f2a48b0ca074c06735b969c534349a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isPending</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True once pending.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### isScheduled {#a8c201d7a769bda1cd75d8d6788123068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isScheduled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True once scheduled.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/instructionshuffler/#ab2f0461b159b9b2dc36f1ce07ef8f360">anonymous{MachineScheduler.cpp}::InstructionShuffler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad4cc558b6cbcc4e9cea5df915c197e14">llvm::GenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#af8a37b0efa51cfd3f6b4729e3298de7f">llvm::PostGenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#a3351536ef89bb6fe156f754d2ee7c24c">llvm::R600SchedStrategy::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a241c866b4c0500ad383acfd1d87d3983">llvm::ConvergingVLIWScheduler::releaseBottomNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a779430fb54fa19f8bf9d94d1618bf7f5">llvm::GenericScheduler::releaseBottomNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#ac32bc6bea26f0dc3cc421145f6c41af6">llvm::PostGenericScheduler::releaseBottomNode</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#ad8c1e5b05c8d75032ef68b1282aef2b2">llvm::ConvergingVLIWScheduler::releaseTopNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#acc4369e500d02fac8e313e69947b2611">llvm::GenericScheduler::releaseTopNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a7b2207fcd69085e114fe45fb49276ff2">llvm::PostGenericScheduler::releaseTopNode</a>, <a href="#a6d3233165db1e6be5c44060cd4a95461">removePred</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnilpsched-cpp-/gcnilpscheduler/#a701a79471c4c9a778d88f103f3bfdcbf">anonymous{GCNILPSched.cpp}::GCNILPScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a5d7e71cf32573e6b1762b5a1d82a1cf5">llvm::ScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a1583ce23a69e8a1b4af8065e2019c75f">llvm::ScheduleDAGMILive::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a5b1da83188ad8ac357edfd719ce2680f">llvm::HexagonConvergingVLIWScheduler::SchedulingCost</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a>, <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#abfdd9a95217810c69b2557060a130318">llvm::ScheduleDAGMI::updateQueues</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ab464241184b77be167ff521aa2552e29">llvm::ScheduleDAG::VerifyScheduledDAG</a>.</p>

</div>
</div>

### isScheduleHigh {#a7faf5b0345dd1c2fd4b60d7f5108f3b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isScheduleHigh</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if preferable to schedule high.</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzpostraschedstrategy/#afe13e1e8b6cdaa6f0cd3a91d16a302f8">llvm::SystemZPostRASchedStrategy::releaseTopNode</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a>, <a href="#ab6f654823b1290408013a587551746aa">SUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>.</p>

</div>
</div>

### isScheduleLow {#a95e0c4bc075b7e8974dd9dcc80609487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isScheduleLow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if preferable to schedule low.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#ac49ea8879ebf41e521f4f48838e17b6c">checkSpecialNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### isTwoAddress {#ac8cc028950511d3ae611681975c7831e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isTwoAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is a two-address instruction.</p>

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a4ba2ac7568356ddd4b07a7f1718c8d6a">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::canClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### isUnbuffered {#a4ac4d36cb59a4bbf5d93513dad0ff0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isUnbuffered</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Uses an unbuffered resource.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a8a2ae56dfdc087ade919e8712369134a">llvm::SystemZHazardRecognizer::dumpSU</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#ae8b6eb92a49f95a3bc79199f0768de4a">llvm::SystemZHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a47377e7e9aaf5a00affe4f4d8ec61f3e">llvm::SystemZHazardRecognizer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a4a674627365b72b17a9b2e0a99d40ce1">llvm::SchedBoundary::getLatencyStallCycles</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a705a0975de8335b0b6bdbbae165e8f5c">llvm::ScheduleDAGInstrs::initSUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzpostraschedstrategy/#afe13e1e8b6cdaa6f0cd3a91d16a302f8">llvm::SystemZPostRASchedStrategy::releaseTopNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#ab727fc0077d4f6ff1ad7b34cc5d2f069">llvm::SystemZHazardRecognizer::resourcesCost</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### isVRegCycle {#ad11870c750d0016478df39175d3088a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isVRegCycle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>May use and def the same vreg.</p>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#ae9a23658447d6c412d2a47f78b465016">hasVRegCycleUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a91d04d52105b5c8ba8626a9a64bffc61">initVRegCycle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a420129a3b8db368bc6768ddb7293255d">resetVRegCycle</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### Latency {#a72e0568b7bf0e9a97260c34264a549a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::SUnit::Latency = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/node">Node</a> latency.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#ab7263c22653c86a22ff72bc5385e8835">llvm::AggressiveAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#a9724d87887d705995d775dfec0402648">BUCompareLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af872650583e3ccb09205d6a9832026b2">BUCompareLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6ab45d1027ab01be9c371634c49d077b">llvm::ScheduleDAGSDNodes::computeLatency</a>, <a href="#aab2e2064b4bde0d5487ddc0d0982f5b9">dumpAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a705a0975de8335b0b6bdbbae165e8f5c">llvm::ScheduleDAGInstrs::initSUnits</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### Node {#adbf66a730d8451aed520907432c069b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode* llvm::SUnit::Node</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Representative node.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#afc98c2c5417cad1a90fc4fe241fe8ba4">getInstr</a>, <a href="#ac42c5c2e2899b5e891477e415a045503">getNode</a>, <a href="#a1e76b6a72bd49c97aaf9fe170fb829bd">setNode</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### NodeNum {#a3f708b119627541f144d703a1d183202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::NodeNum = BoundaryID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Entry # of node in the node vector.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a16ad30e09da64d0cb08f5391b3d5c0f9">llvm::ScheduleDAGTopologicalSort::AddSUnitWithoutPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduleblock/#adc6369cdcf8df8db8d72b47972b2b481">llvm::SIScheduleBlock::addUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#a9724d87887d705995d775dfec0402648">BUCompareLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af872650583e3ccb09205d6a9832026b2">BUCompareLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af1dbaf0e42fc61259e10468caeb7f4b5">CalcNodeSethiUllmanNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#af1dbaf0e42fc61259e10468caeb7f4b5">CalcNodeSethiUllmanNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#adb8558f52662b83fe081b34b1f31fb20">llvm::SchedBoundary::checkHazard</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a54fbbf29fc459bb243a1a43fb2ab9c1a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::clusterNeighboringMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#aaea2f970a2bbb337f3098d43c1fdfb8c">llvm::GCNSchedStage::computeSUnitReadyCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ac464b0883162724583f0f124c8be8157">llvm::ScheduleDAG::dumpNodeName</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a942d716003056c037d46a4144e9cf885">llvm::ScheduleDAGMI::dumpScheduleTraceBottomUp</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a3010c4b89284791284aa6e2ec510501b">llvm::ScheduleDAGMI::dumpScheduleTraceTopDown</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a8a2ae56dfdc087ade919e8712369134a">llvm::SystemZHazardRecognizer::dumpSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduleblock/#afbf733ebc24b55f69910a8099e213a97">llvm::SIScheduleBlock::finalizeUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a4e57bf16f8ed97dbbdc4d48655455b3c">llvm::SchedBoundary::findMaxLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a8cbdb500ba4abd11fd23de4e7a020a2d">llvm::ScheduleDAGSDNodes::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult/#a5269b7fe10c17e55d827eaf49ab3f2c8">llvm::SchedDFSResult::getILP</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-3e4d2beef0711eb028dcc7799677e405/#a9e281d4b0718506e4ec5596a06ae36dd">llvm::DOTGraphTraits&lt; ScheduleDAGMI * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a9ae4cee3cd6aafb475565cb82d033b40">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::getNodePriority</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult/#a1bd5822bcf45690f998c2fd86a092ced">llvm::SchedDFSResult::getNumInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a24c23a8dc39475b1e913e41f1249c9f7">llvm::ScheduleDAGMILive::getPressureDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#aa80e188af21b1d7b6ada57dc03a2581e">llvm::ScheduleDAGMILive::getPressureDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a346955acdf30b0ecf7f58b3ba9e32129">llvm::ScheduleDAGTopologicalSort::GetSubGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult/#a2b2b597b59be28845565af32824bc8ed">llvm::SchedDFSResult::getSubtreeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#ae9a23658447d6c412d2a47f78b465016">hasVRegCycleUse</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a44c5faa549f250a26b1303eb1a3ebd47">llvm::ScheduleDAGTopologicalSort::InitDAGTopologicalSorting</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a91d04d52105b5c8ba8626a9a64bffc61">initVRegCycle</a>, <a href="#a7406c398c67e53ee3937bf2b6df1c64e">isBoundaryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#af5fef42e8e1d446cf5e185b14dd4b8af">llvm::ScheduleDAGTopologicalSort::IsReachable</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduleblockcreator/#a25695e02f3a68587c54629bda36cb5cb">llvm::SIScheduleBlockCreator::isSUInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#af9ab4e29b1b9ebb256c6ec991a487f25">llvm::SchedDFSImpl::isVisited</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a8a616fae155ac2f266346edbb5411470">llvm::SchedDFSImpl::joinPredSubtree</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae26138aceef07cf5465c2840b437e1d8">llvm::SMSchedule::normalizeNonPipelinedInstructions</a>, <a href="/web-llvm/docs/api/structs/anonymous-scheduledagrrlist-cpp-/hybrid-ls-rr-sort/#a6c60423438d42b5bf6f8bbe15b7c5a91">anonymous{ScheduleDAGRRList.cpp}::hybrid_ls_rr_sort::operator()</a>, <a href="/web-llvm/docs/api/structs/anonymous-scheduledagrrlist-cpp-/ilp-ls-rr-sort/#a79b85bbc0a0fbf047dcef83891e4b9e4">anonymous{ScheduleDAGRRList.cpp}::ilp_ls_rr_sort::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/ilpscheduler/#a636abcad4364da7508f5fdce3bbf40e7">anonymous{MachineScheduler.cpp}::ILPScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#af3f3a45f145bc8538e160bc3177ffc8f">llvm::GCNSchedStrategy::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad4cc558b6cbcc4e9cea5df915c197e14">llvm::GenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#af8a37b0efa51cfd3f6b4729e3298de7f">llvm::PostGenericScheduler::pickNode</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a3460671809bfea01d71388f2e45c3c50">llvm::SMSchedule::print</a>, <a href="/web-llvm/docs/api/classes/llvm/latencypriorityqueue/#a2e3b6da384da19b92dc290a8051194c6">llvm::LatencyPriorityQueue::push</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a068e19beaca7ce41347bb87946fbe2c9">llvm::ResourcePriorityQueue::push</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e28b826aaa73d2dacf89ba8f8c775d1">llvm::ScheduleDAGInstrs::reduceHugeMemNodeMaps</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzpostraschedstrategy/#a9ee4cac33c533fe9bc0b5b0147475c38">llvm::SystemZPostRASchedStrategy::schedNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnilpsched-cpp-/gcnilpscheduler/#a701a79471c4c9a778d88f103f3bfdcbf">anonymous{GCNILPSched.cpp}::GCNILPScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6ccdfe5633d79d327d704b14f7b83235">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduler/#a91522b1e12e9b5d9e9a05928732f15f9">llvm::SIScheduler::scheduleVariant</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a>, <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a0fc28b204833d49b88dbeceb366b7439">llvm::GenericSchedulerBase::traceCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxilpschedstrategy/#adaaa8b026820461823cf355979353b3a">llvm::GCNMaxILPSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a6ef23d22af6c895d9c255de3e940b8bf">llvm::GenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a09835bd12a7088d224f84e7899946040">llvm::PostGenericScheduler::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpostraschedstrategy/#aa6664186ee0da2c7355def751d53a653">llvm::PPCPostRASchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcpreraschedstrategy/#a4b73638109c4ea048c148a781996272d">llvm::PPCPreRASchedStrategy::tryCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a0e836cacd4de504f97f5bf21a6987c1a">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::updateNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#ae259d5b34969a9259dbc66324869c398">llvm::SchedDFSImpl::visitPostorderEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a19e83509e45ee65e4495de5a3ed3d44a">llvm::SchedDFSImpl::visitPostorderNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#aee17a5350fad1c56abf6f425ef4f6e92">llvm::SchedDFSImpl::visitPreorder</a>.</p>

</div>
</div>

### NodeQueueId {#a26a3c0b6567d1e8cf9ac8492e6e5f62f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::NodeQueueId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Queue id of node.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a22d5e4af25a96cf3a8b85aa7bb0a0912">llvm::ResourcePriorityQueue::initNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#ac25a58da20f4a6c1992ee2a0b135f13f">llvm::ReadyQueue::isInQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#a025211e06f54e0c9b9870b12e2b72494">llvm::ReadyQueue::push</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a2cca36eb6eaa100e41d95d8123eb21fb">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::remove</a>.</p>

</div>
</div>

### NumPreds {#a25329a072c76c185b8c5ff530c632762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::NumPreds = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




## of SDep::Data preds {#autotoc_md26}


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a16ad30e09da64d0cb08f5391b3d5c0f9">llvm::ScheduleDAGTopologicalSort::AddSUnitWithoutPredecessors</a>, <a href="#a4aa947b755365817fa095e581752a8ae">biasCriticalPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a07e9d7ff453553fd3e5e64c9d93d5d07">canEnableCoalescing</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a9ae4cee3cd6aafb475565cb82d033b40">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::getNodePriority</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="#a6d3233165db1e6be5c44060cd4a95461">removePred</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ab464241184b77be167ff521aa2552e29">llvm::ScheduleDAG::VerifyScheduledDAG</a>.</p>

</div>
</div>

### NumPredsLeft {#a94f78042fbba3ea4cd1004353daa46aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::NumPredsLeft = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




## of preds not scheduled {#autotoc_md28}


<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb4b9423201406d79ba16481c90cb6cb">llvm::biasPhysReg</a>, <a href="#aab2e2064b4bde0d5487ddc0d0982f5b9">dumpAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#a07cd4ba9b3cd1a7ff745d0238726dab6">isSingleUnscheduledPred</a>, <a href="#ae0b8da4dfde85d4ddc32359ca52dc493">isTopReady</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a90ffd918ef80c711049758b2064e15c4">llvm::ScheduleDAGMI::releaseSucc</a>, <a href="#a6d3233165db1e6be5c44060cd4a95461">removePred</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ab464241184b77be167ff521aa2552e29">llvm::ScheduleDAG::VerifyScheduledDAG</a>.</p>

</div>
</div>

### NumRegDefsLeft {#a74f8123e14985c7599ffca039e80b70a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::SUnit::NumRegDefsLeft = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




## of reg defs with no scheduled use {#autotoc_md32}


<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#aab2e2064b4bde0d5487ddc0d0982f5b9">dumpAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#aab14bf8331cae31c80d8cc29dff5e9bb">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::HighRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a9e19da5240e1c311814f574bb0c235a4">llvm::ScheduleDAGSDNodes::InitNumRegDefsLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae40b5614303ad840c02bf2923d5f4305">llvm::ResourcePriorityQueue::initNumRegDefsLeft</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a1b480aa4515358bac44d9281c7f74471">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::RegPressureDiff</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6ccdfe5633d79d327d704b14f7b83235">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::scheduledNode</a> and <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>.</p>

</div>
</div>

### NumSuccs {#a1a6c1a29019b8f3fd988359ec5dd3d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::NumSuccs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




## of SDep::Data sucss {#autotoc_md27}


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a07e9d7ff453553fd3e5e64c9d93d5d07">canEnableCoalescing</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a9ae4cee3cd6aafb475565cb82d033b40">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::getNodePriority</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#aaae720d8a55a2ddf5a3b795d2a82805a">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::MayReduceRegPressure</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a1b480aa4515358bac44d9281c7f74471">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::RegPressureDiff</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ab464241184b77be167ff521aa2552e29">llvm::ScheduleDAG::VerifyScheduledDAG</a>.</p>

</div>
</div>

### NumSuccsLeft {#a40c2dfbd170941dd4d20ee9b60c9d49d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::NumSuccsLeft = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




## of succs not scheduled {#autotoc_md29}


<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afb4b9423201406d79ba16481c90cb6cb">llvm::biasPhysReg</a>, <a href="#aab2e2064b4bde0d5487ddc0d0982f5b9">dumpAttributes</a>, <a href="#ac198a5fb130b4c09836ba20e01b4290d">isBottomReady</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#ad85e209f5c4b8b0b4f804222439bc5ee">isSingleUnscheduledSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1c51776d4e512a7f24d5b5d601c31016">llvm::ScheduleDAGMI::releasePred</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ab464241184b77be167ff521aa2552e29">llvm::ScheduleDAG::VerifyScheduledDAG</a>.</p>

</div>
</div>

### OrigNode {#af46433c376061aaf79670805e7843be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit* llvm::SUnit::OrigNode = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If not this, the node from which this node was cloned.</p>


<p>(SD scheduling only)</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>.</p>

</div>
</div>

### Preds {#ae2b43854b542de66eec6475adc48f56c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SDep, 4&gt; llvm::SUnit::Preds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All sunit predecessors.</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp/#a4a408b05eacd6ea605ddc856dcf57f11">AntiDepEdges</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/usroverflowmutation/#af2918620aeda858e99c7fac5f1e9eb16">llvm::HexagonSubtarget::UsrOverflowMutation::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="#a4aa947b755365817fa095e581752a8ae">biasCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#ab7263c22653c86a22ff72bc5385e8835">llvm::AggressiveAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#a5a71ccecb00de06004fb421a568dd7b4">llvm::CriticalAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#a07b42c1e90cefebe812ba65deb791e95">anonymous{AMDGPUExportClustering.cpp}::buildCluster</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af07e92d835d198619f6f5c1afd59bd8a">calcMaxScratches</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#af07e92d835d198619f6f5c1afd59bd8a">calcMaxScratches</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#af1dbaf0e42fc61259e10468caeb7f4b5">CalcNodeSethiUllmanNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a82b468a911dfb66ebd0e9dfafd6ec6a1">llvm::HexagonPacketizerList::calcStall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a54fbbf29fc459bb243a1a43fb2ab9c1a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::clusterNeighboringMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#acfd4efd1c9f1a0174bd6f3942238c51b">llvm::SMSchedule::computeStart</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#aaea2f970a2bbb337f3098d43c1fdfb8c">llvm::GCNSchedStage::computeSUnitReadyCycle</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp/#a4bfac8dc3460d1e7628eba4c5d6e4a12">CriticalPathStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp/#a4fcfebf71584254d08e964c5964ccf7e">CriticalPathStep</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a917f4d40ed0bbdaf4ab50e5df4de067b">llvm::ScheduleDAG::dumpNodeAll</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledaginstrs-cpp-/scheddagreversedfs/#a8f78fb81248e5bde31cca488cc52a33d">anonymous{ScheduleDAGInstrs.cpp}::SchedDAGReverseDFS::follow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/macrofusion-cpp/#a2ab06a9fb00594adf4a29f0184f723d9">getPredClusterSU</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a346955acdf30b0ecf7f58b3ba9e32129">llvm::ScheduleDAGTopologicalSort::GetSubGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp/#a628aa7dbdf88b477b398c62d1573d2e1">hasDataDependencyPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a16fdb3e37daf197199709a37540402d0">hasOnlyLiveInOpers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#ae9a23658447d6c412d2a47f78b465016">hasVRegCycleUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#aab14bf8331cae31c80d8cc29dff5e9bb">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::HighRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a44c5faa549f250a26b1303eb1a3ebd47">llvm::ScheduleDAGTopologicalSort::InitDAGTopologicalSorting</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a91d04d52105b5c8ba8626a9a64bffc61">initVRegCycle</a>, <a href="#a6fe37a9ed7e3ddc88a91b16aa3f83d14">isPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#a07cd4ba9b3cd1a7ff745d0238726dab6">isSingleUnscheduledPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#af6df1639af84a974f3bdcd4b93c32c2f">multipleIterations</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp/#a3ab96228908e98db52f1e1dd59bafbde">numberCtrlPredInSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sunititerator/#a1b4eb3f52afe6a3763a41b3e2ad65f2a">llvm::SUnitIterator::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a1b480aa4515358bac44d9281c7f74471">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::RegPressureDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a25f9975b56fe38f7a8bb4d10b7f6f5ea">llvm::ScheduleDAGMI::releasePredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#ad8c1e5b05c8d75032ef68b1282aef2b2">llvm::ConvergingVLIWScheduler::releaseTopNode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#ac88025eb8866478014f41b34cd29b593">anonymous{AMDGPUExportClustering.cpp}::removeExportDependencies</a>, <a href="#a6d3233165db1e6be5c44060cd4a95461">removePred</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad04f609cdff2331741525e5328836598">llvm::GenericScheduler::reschedulePhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a420129a3b8db368bc6768ddb7293255d">resetVRegCycle</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6ccdfe5633d79d327d704b14f7b83235">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a252bd3038d4cc84ade6e24b656bd4655">llvm::ARMOverrideBypasses::setBidirLatencies</a>, <a href="#a5ba3791568e29a8d9214ec7dad855a56">setHeightDirty</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a062ea093e135121a384a1c6c4cd3d96c">llvm::HexagonPacketizerList::updateOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a19e83509e45ee65e4495de5a3ed3d44a">llvm::SchedDFSImpl::visitPostorderNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a142388e1eb164f473d3c10b3c582d51b">llvm::ScheduleDAGTopologicalSort::WillCreateCycle</a>.</p>

</div>
</div>

### SchedClass {#a2b2c6049e5141829267f4f9193b475d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedClassDesc* llvm::SUnit::SchedClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>nullptr or resolved SchedClass.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
        nullptr
</div>
</dd>
</dl>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4bf5573660c55924d68b517a0e9b4554">llvm::ScheduleDAGInstrs::getSchedClass</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a4a0f2858cdd379056abfa2531e7da961">llvm::SystemZHazardRecognizer::getSchedClass</a>.</p>

</div>
</div>

### SchedulingPref {#ab5ecf23b4e7641cbd378b0a2e03e77fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Sched::Preference llvm::SUnit::SchedulingPref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scheduling preference.</p>

<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af872650583e3ccb09205d6a9832026b2">BUCompareLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#abb309c4ecf566e6daf86db0edbb0dbc5">llvm::ScheduleDAGSDNodes::Clone</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a15c0200b4b6e12b97d270fbea215443e">llvm::ScheduleDAGSDNodes::newSUnit</a>, <a href="#adaadb44f4bcc6e1726089e9862f566c6">SUnit</a>, <a href="#a516a65564958ed71cc1e66256604ae44">SUnit</a> and <a href="#ab6f654823b1290408013a587551746aa">SUnit</a>.</p>

</div>
</div>

### Succs {#aab4a86c51e6b126c9c6ef58dbb574431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SDep, 4&gt; llvm::SUnit::Succs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All sunit successors.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuexportclustering-cpp-/exportclustering/#a3432dbdb86f0a5f40c9d3bcfd8633b28">anonymous{AMDGPUExportClustering.cpp}::ExportClustering::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/hvxmemlatencymutation/#a9c1fcebee584af05ce009b20aeab417b">llvm::HexagonSubtarget::HVXMemLatencyMutation::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0256920aada1bf35dc3c90cbfba10e5d">llvm::HexagonPacketizerList::arePredicatesComplements</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnilpsched-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a54fbbf29fc459bb243a1a43fb2ab9c1a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::clusterNeighboringMemOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a917f4d40ed0bbdaf4ab50e5df4de067b">llvm::ScheduleDAG::dumpNodeAll</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aafc82eb49e1de126caa8907eaca9f46e">llvm::HexagonHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a346955acdf30b0ecf7f58b3ba9e32129">llvm::ScheduleDAGTopologicalSort::GetSubGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a26aca145a8f6953152a566a143c6ec8f">hasDataSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel/#a36231f2afc68d76cf54a3d4a8f87a70a">llvm::VLIWResourceModel::hasDependence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a22c99596004378b139e9ab48fae048dc">hasOnlyLiveOutUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ae14c145aa6237db91a7bca044488de25">anonymous{R600Packetizer.cpp}::R600PacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp/#ad85e209f5c4b8b0b4f804222439bc5ee">isSingleUnscheduledSucc</a>, <a href="#a65e96694f0d2eef93a9653beba7d12dc">isSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#aa1bdad6ac04deb5b4e5990a020b616c7">isSuccOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a8a616fae155ac2f266346edbb5411470">llvm::SchedDFSImpl::joinPredSubtree</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#a6c67a87b5b8b7338e197f5bb29767019">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp/#a4fd9efbedcbd8af579647f70a9c35f65">numberCtrlDepsInSU</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aa641d58b022e9702656e1a58369931e5">llvm::ConvergingVLIWScheduler::pickNodeFromQueue</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/latencypriorityqueue/#a2e3b6da384da19b92dc290a8051194c6">llvm::LatencyPriorityQueue::push</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a068e19beaca7ce41347bb87946fbe2c9">llvm::ResourcePriorityQueue::push</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#a241c866b4c0500ad383acfd1d87d3983">llvm::ConvergingVLIWScheduler::releaseBottomNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#acf56d667066b39177a3c0f134d759d98">llvm::ScheduleDAGMI::releaseSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ad04f609cdff2331741525e5328836598">llvm::GenericScheduler::reschedulePhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a642903485b484d638fafe7da8142cdd8">llvm::HexagonPacketizerList::restrictingDepExistInPacket</a>, <a href="/web-llvm/docs/api/classes/llvm/latencypriorityqueue/#a93f241795b5da8c207a88063862e2ea2">llvm::LatencyPriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>, <a href="#addb1364902bd813841491d91970ce02b">setDepthDirty</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>.</p>

</div>
</div>

### TopReadyCycle {#a2a6f92b9c5aba34d3b07f3ebe229ccff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::TopReadyCycle = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> relative to start when node is ready.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a6b1771cf492495f8f82727657c68e571">llvm::SchedBoundary::bumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aa5f22315c4064579fca6cd88fb36ea5a">llvm::ScheduleDAGInstrs::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a3010c4b89284791284aa6e2ec510501b">llvm::ScheduleDAGMI::dumpScheduleTraceTopDown</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a4a674627365b72b17a9b2e0a99d40ce1">llvm::SchedBoundary::getLatencyStallCycles</a>, <a href="/web-llvm/docs/api/structs/llvm/convergingvliwscheduler/vliwschedboundary/#a7f64e612634009b7ced96fbf06f6b445">llvm::ConvergingVLIWScheduler::VLIWSchedBoundary::releasePending</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a155166a788cfe0d992af6f2e21e6118e">llvm::SchedBoundary::releasePending</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a90ffd918ef80c711049758b2064e15c4">llvm::ScheduleDAGMI::releaseSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#ad8c1e5b05c8d75032ef68b1282aef2b2">llvm::ConvergingVLIWScheduler::releaseTopNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#acc4369e500d02fac8e313e69947b2611">llvm::GenericScheduler::releaseTopNode</a>, <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a7b2207fcd69085e114fe45fb49276ff2">llvm::PostGenericScheduler::releaseTopNode</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#ab76f5e165cdf261f940b854e739a789b">llvm::ConvergingVLIWScheduler::schedNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#adf574ab3455d7292bed998d8ba50bfeb">llvm::GenericScheduler::schedNode</a> and <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a19c13266ab002ad2ce608573c4d2c98e">llvm::PostGenericScheduler::schedNode</a>.</p>

</div>
</div>

### WeakPredsLeft {#ab9e02660290b9557b547b57870133467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::WeakPredsLeft = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




## of weak preds not scheduled {#autotoc_md30}


<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#af92bf49ed4846e026e68c380d74d7b15">addPred</a>, <a href="#aab2e2064b4bde0d5487ddc0d0982f5b9">dumpAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13933f8ac2f5e1a34cf53b2c1e1bdc5b">llvm::getWeakLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a90ffd918ef80c711049758b2064e15c4">llvm::ScheduleDAGMI::releaseSucc</a> and <a href="#a6d3233165db1e6be5c44060cd4a95461">removePred</a>.</p>

</div>
</div>

### WeakSuccsLeft {#ae75d620ee809eaf50970a833f4a3ace9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::WeakSuccsLeft = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




## of weak succs not scheduled {#autotoc_md31}


<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#aab2e2064b4bde0d5487ddc0d0982f5b9">dumpAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13933f8ac2f5e1a34cf53b2c1e1bdc5b">llvm::getWeakLeft</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1c51776d4e512a7f24d5b5d601c31016">llvm::ScheduleDAGMI::releasePred</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#ace2f273db456493e39f5fbe86123eb8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::SUnit llvm::SUnit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### Depth {#abd58dead84edf5d9793b55c28ea51255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::Depth = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/node">Node</a> depth.</p>

<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### Height {#a5f0207f07d8d6dc6d2cc243d8a6f93dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SUnit::Height = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/node">Node</a> height.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### isDepthCurrent {#ae6d5b61ebee8292e9b637ea1fa43b826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isDepthCurrent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if Depth is current.</p>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### isHeightCurrent {#a9c632657097cf88ba672bb05da5b0ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isHeightCurrent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if Height is current.</p>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### isInst {#ae9b2154a3870a53132310f0b001f051c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the representative is a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### isNode {#a048e8567377d69a5e087545d6994c445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SUnit::isNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the representative is an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
