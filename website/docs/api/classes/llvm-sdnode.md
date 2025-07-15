---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sdnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SDNode` Class Reference

<p>Represents one node in the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SDNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node">Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node">Node</a> - This class is used to maintain the singly linked bucket list in a folding set. <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/addrspacecastsdnode">AddrSpaceCastSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assertalignsdnode">AssertAlignSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> that records if a register contains a value that is guaranteed to be aligned accordingly. <a href="/web-llvm/docs/api/classes/llvm/assertalignsdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblocksdnode">BasicBlockSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockaddresssdnode">BlockAddressSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode">BuildVectorSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A "pseudo-class" with methods for operating on BUILD_VECTORs. <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/condcodesdnode">CondCodeSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode">ConstantFPSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantpoolsdnode">ConstantPoolSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/externalsymbolsdnode">ExternalSymbolSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/frameindexsdnode">FrameIndexSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/handlesdnode">HandleSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is used to form a handle around another node that is persistent and is updated across invocations of replaceAllUsesWith on its operand. <a href="/web-llvm/docs/api/classes/llvm/handlesdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jumptablesdnode">JumpTableSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/labelsdnode">LabelSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lifetimesdnode">LifetimeSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> is used for LIFETIME_START/LIFETIME_END values, which indicate the offet and size that are started/ended in the underlying FrameIndex. <a href="/web-llvm/docs/api/classes/llvm/lifetimesdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolsdnode">MCSymbolSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnodesdnode">MDNodeSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinesdnode">MachineSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> that represents everything that will be needed to construct a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="/web-llvm/docs/api/classes/llvm/machinesdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an abstract virtual class for memory operations. <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pseudoprobesdnode">PseudoProbeSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> is used for PSEUDO_PROBE values, which are the function guid and the index of the basic block being probed. <a href="/web-llvm/docs/api/classes/llvm/pseudoprobesdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registermasksdnode">RegisterMaskSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registersdnode">RegisterSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> is used to implement the code generator support for the llvm IR shufflevector instruction. <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/srcvaluesdnode">SrcValueSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> that holds an arbitrary LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="/web-llvm/docs/api/classes/llvm/srcvaluesdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetindexsdnode">TargetIndexSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Completely target-dependent object reference. <a href="/web-llvm/docs/api/classes/llvm/targetindexsdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vtsdnode">VTSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is used to represent <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>'s, which are used to parameterize some operations. <a href="/web-llvm/docs/api/classes/llvm/vtsdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423c330f7f1bd8f3510e2bb304435217">op_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/sduse">SDUse</a> *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da24f4af897a7ec4e4afcf5abf49bc0">value_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a241f78dc8dec652ff7cbdfba3523d909">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#af10ea0cefa5fe5d315b71f1c38617ee9">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a738d6a19c3422882f90fb4a42b9db297">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5fbf1cb74d1e5c2e40343877aa9a26">HandleSDNode</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a> (unsigned Opc, unsigned Order, DebugLoc dl, SDVTList VTs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. <a href="#af64f53af99d4ee7bbf57ea0aab719254">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f2f5947fc429aff1270651c6d019ea">getOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> opcode value for this node. <a href="#a23f2f5947fc429aff1270651c6d019ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2432058d52e384abd351a75adf27aee">isTargetOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this node has a target-specific opcode (in the &lt;target&gt;<a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a> namespace). <a href="#ae2432058d52e384abd351a75adf27aee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29680b0f3d0427cab5a32e727f9f11a">isUndef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the type of the node type undefined. <a href="#ad29680b0f3d0427cab5a32e727f9f11a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ea0c52aaedee23f6e0ef24a0373201">isMemIntrinsic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this node is a memory intrinsic (with valid pointer information). <a href="#a84ea0c52aaedee23f6e0ef24a0373201">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07f22269e73f15d1d993421c5e4a2f28">isStrictFPOpcode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this node is a strict floating point pseudo-op. <a href="#a07f22269e73f15d1d993421c5e4a2f28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85183a1e40f2a1dc0840c22484b8eec">isVPOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this node is a vector predication operation. <a href="#ad85183a1e40f2a1dc0840c22484b8eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1223d6e9a7dfb6e51299b894beccc679">isMachineOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this node has a post-isel opcode, directly corresponding to a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> opcode. <a href="#a1223d6e9a7dfb6e51299b894beccc679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f96a3399d86d6f136aaa121de4217a3">getMachineOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This may only be called if isMachineOpcode returns true. <a href="#a7f96a3399d86d6f136aaa121de4217a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a478a16ce230e9f3901fdc6847bc063b5">getHasDebugValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40063dd06404e7d8df5bc40a956ae433">setHasDebugValue</a> (bool b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28417243f8d25f74e598d78d7802c366">isDivergent</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d150e94e3cd7f6681fa07ea2b72da14">use_empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there are no uses of this node. <a href="#a7d150e94e3cd7f6681fa07ea2b72da14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a295d0b84f4e63438c0edb0021c41d47a">hasOneUse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is exactly one use of this node. <a href="#a295d0b84f4e63438c0edb0021c41d47a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6163a1abbdce6098d64026e3393ecca7">use_size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of uses of this node. <a href="#a6163a1abbdce6098d64026e3393ecca7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bdddc5f08b7b8b77e2518296dd4d84f">getNodeId</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the unique node id. <a href="#a1bdddc5f08b7b8b77e2518296dd4d84f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5689e9ae35c6ceb3b9377299c98e0e97">setNodeId</a> (int Id)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set unique node id. <a href="#a5689e9ae35c6ceb3b9377299c98e0e97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d8d21239b7e041fd6955bbbcf83551c">getCombinerWorklistIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get worklist index for DAGCombiner. <a href="#a3d8d21239b7e041fd6955bbbcf83551c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f3e50d50ee6c3dc75635b6219ca6c2b">setCombinerWorklistIndex</a> (int Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set worklist index for DAGCombiner. <a href="#a8f3e50d50ee6c3dc75635b6219ca6c2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c7563253850e555f36f44d91157e5bb">getIROrder</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the node ordering. <a href="#a2c7563253850e555f36f44d91157e5bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a079553cc2e662f6004719e3b52595a7e">setIROrder</a> (unsigned Order)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the node ordering. <a href="#a079553cc2e662f6004719e3b52595a7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999ec9d4610ecb7c24d399bbc447ed70">getDebugLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the source location info. <a href="#a999ec9d4610ecb7c24d399bbc447ed70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01dfe4f342c26108b177ff260ed81116">setDebugLoc</a> (DebugLoc dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set source location info. <a href="#a01dfe4f342c26108b177ff260ed81116">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/use-iterator">use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9450817c42562fe06198b67be72a24ac">use_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide iteration support to walk over all uses of an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. <a href="#a9450817c42562fe06198b67be72a24ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode/use-iterator">use_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42e9a628b333dddfcc9d5fb17824dc17">uses</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode/use-iterator">use_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d9b41775e14d6cf4cd11b33e2f05c8">uses</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/user-iterator">user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04dc684fcd3d20b890bbf44e4a28395">user_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide iteration support to walk over all users of an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. <a href="#ae04dc684fcd3d20b890bbf44e4a28395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode/user-iterator">user_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5596cf1822f4cc9e37fb75b6dff630f">users</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode/user-iterator">user_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6b0a2bca17658c77d292e8848ee7e3e">users</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad82ad170343d0b4fe88a5551ec43659d">hasNUsesOfValue</a> (unsigned NUses, unsigned Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there are exactly NUSES uses of the indicated value. <a href="#ad82ad170343d0b4fe88a5551ec43659d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6ea142f5ae930a660fbb4105ef42a98">hasAnyUseOfValue</a> (unsigned Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there are any use of the indicated value. <a href="#ab6ea142f5ae930a660fbb4105ef42a98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2998329e16665f7101fac0ae9faee5c7">isOnlyUserOf</a> (const SDNode *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this node is the only use of N. <a href="#a2998329e16665f7101fac0ae9faee5c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94aa946198a3279b30a6d3a943dede42">isOperandOf</a> (const SDNode *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this node is an operand of N. <a href="#a94aa946198a3279b30a6d3a943dede42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf99b3ee1d9577ac86d3bf072c7bc789">isPredecessorOf</a> (const SDNode *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this node is a predecessor of N. <a href="#aaf99b3ee1d9577ac86d3bf072c7bc789">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab250276b651715d29b3ed20467d5f0a0">hasPredecessor</a> (const SDNode *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if N is a predecessor of this node. <a href="#ab250276b651715d29b3ed20467d5f0a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f311fcc2415eee3cb3694013b985304">getNumOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of values used by this operation. <a href="#a7f311fcc2415eee3cb3694013b985304">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90cd0589eba5e5112a68717f122f1fbe">getConstantOperandVal</a> (unsigned Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method returns the integer value of a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> operand. <a href="#a90cd0589eba5e5112a68717f122f1fbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c6e64fef2ad2ba4052cd8365e97e8d2">getAsZExtVal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method returns the zero-extended integer value of a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a>. <a href="#a7c6e64fef2ad2ba4052cd8365e97e8d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dfad184e37d97a10814cdce3d46c072">getConstantOperandAPInt</a> (unsigned Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method returns the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> of a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> operand. <a href="#a9dfad184e37d97a10814cdce3d46c072">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c953187c10b57c4d91c7cb3cd877d5">getAsAPIntVal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method returns the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value of a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a>. <a href="#a10c953187c10b57c4d91c7cb3cd877d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8388f666d6e735f35837ad03ed1f7a7a">getOperand</a> (unsigned Num) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a423c330f7f1bd8f3510e2bb304435217">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6bd1fd282469b3476efce4b707f09a">op_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a423c330f7f1bd8f3510e2bb304435217">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae499cc99d4fe44d343ca9ac6a2ae8845">op_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sduse">SDUse</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cdd5176dc41b96586448ecc59770250">ops</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/sdnode/value-op-iterator">value_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb043b87aa8cdef6d1e9e14329aec6a">op_values</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sdvtlist">SDVTList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8353d97eb11578ab1ecb797200ca85c7">getVTList</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fa8ded9bce6f8321a69e99e41a473c">getGluedNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this node has a glue operand, return the node to which the glue operand points. <a href="#ae1fa8ded9bce6f8321a69e99e41a473c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2594280bfba5f9b0dff74cfb5b4f29d2">getGluedUser</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this node has a glue value with a user, return the user (there is at most one). <a href="#a2594280bfba5f9b0dff74cfb5b4f29d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5023bb0687db0b35d3b2d19327217ce5">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add49be7f78dace3e4363786d14d30899">setFlags</a> (SDNodeFlags NewFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36b7f42c61a6ad5abfb26642fde7e354">dropFlags</a> (unsigned Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6740680254c86d6fb43a3f8d88af9572">intersectFlagsWith</a> (const SDNodeFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear any flags in this node that aren't also set in Flags. <a href="#a6740680254c86d6fb43a3f8d88af9572">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad961d1de3aa88629112015651709de3e">hasPoisonGeneratingFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91f61940049e03836c7ba45f488c51f">setCFIType</a> (uint32_t Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02bd3912ea1a5ed151646c98aa65dacd">getCFIType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f06dbaee5fa2b239de548d0a775b25b">getNumValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of values defined/returned by this operator. <a href="#a7f06dbaee5fa2b239de548d0a775b25b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0a534d63ac5c5b87f36acdade953fbe">getValueType</a> (unsigned ResNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type of a specified result. <a href="#ac0a534d63ac5c5b87f36acdade953fbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a6096cff14db41b299758115c6e261c">getSimpleValueType</a> (unsigned ResNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type of a specified result as a simple type. <a href="#a7a6096cff14db41b299758115c6e261c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75de6a9cc37e7d0a70e488ad3c4159c7">getValueSizeInBits</a> (unsigned ResNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns MVT::getSizeInBits(getValueType(ResNo)). <a href="#a75de6a9cc37e7d0a70e488ad3c4159c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6da24f4af897a7ec4e4afcf5abf49bc0">value_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf9393b9b8bfef4019780f5cb4db651">value_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6da24f4af897a7ec4e4afcf5abf49bc0">value_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee68ee9398984fcd74e7cfcc3fb4ce0">value_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a6da24f4af897a7ec4e4afcf5abf49bc0">value_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a210b2e97bcab8e5cbab59a92fc3e1b70">values</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59192c42d4cbf804fbcc1deff8edb614">getOperationName</a> (const SelectionDAG *G=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the opcode of this operation for printing. <a href="#a59192c42d4cbf804fbcc1deff8edb614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4e2295ddf513d5a4898fa7b3f1c2121">print_types</a> (raw_ostream &amp;OS, const SelectionDAG *G) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac351340ed4428a1b6d69d303bcba86d9">print_details</a> (raw_ostream &amp;OS, const SelectionDAG *G) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a998e1d9da008364ea6a05c3a0c891b69">print</a> (raw_ostream &amp;OS, const SelectionDAG *G=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d72e52ee2c6a11256e6d04c8820e648">printr</a> (raw_ostream &amp;OS, const SelectionDAG *G=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db0a95c12b4b5ee310ea283172e3e49">printrFull</a> (raw_ostream &amp;O, const SelectionDAG *G=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> node and all children down to the leaves. <a href="#a5db0a95c12b4b5ee310ea283172e3e49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d07a0db71661297bf458ca459bfe448">printrWithDepth</a> (raw_ostream &amp;O, const SelectionDAG *G=nullptr, unsigned depth=100) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> node and children up to depth "depth." The given <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> allows target-specific nodes to be printed in human-readable form. <a href="#a9d07a0db71661297bf458ca459bfe448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4346248feeb9d5c83ce930555936d1">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump this node, for debugging. <a href="#a1f4346248feeb9d5c83ce930555936d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4efc0c778a7afdaf5b5a45594bc809a0">dumpr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump (recursively) this node and its use-def subgraph. <a href="#a4efc0c778a7afdaf5b5a45594bc809a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addc45c27e50b974d99ba074ebfc4930c">dump</a> (const SelectionDAG *G) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump this node, for debugging. <a href="#addc45c27e50b974d99ba074ebfc4930c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89206bcd1c676ffdbfe8a8494c187524">dumpr</a> (const SelectionDAG *G) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump (recursively) this node and its use-def subgraph. <a href="#a89206bcd1c676ffdbfe8a8494c187524">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b25769866228a5517d8e752fad14f10">dumprFull</a> (const SelectionDAG *G=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printrFull to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>. <a href="#a1b25769866228a5517d8e752fad14f10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4da658044d115b980e5c832fa25cdb">dumprWithDepth</a> (const SelectionDAG *G=nullptr, unsigned depth=100) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printrWithDepth to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>. <a href="#a9f4da658044d115b980e5c832fa25cdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4476e9669bf25c55cf7c5181dad8cd63">Profile</a> (FoldingSetNodeID &amp;ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather unique data for the node. <a href="#a4476e9669bf25c55cf7c5181dad8cd63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41099ecc9dbea4f74062c85c0a8c6af">addUse</a> (SDUse &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should only be used by the <a href="/web-llvm/docs/api/classes/llvm/sduse">SDUse</a> class. <a href="#ab41099ecc9dbea4f74062c85c0a8c6af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeffcf6f6a22d7591beed2f7a9d9fee20">DropOperands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release the operands and set this node to have zero operands. <a href="#aeffcf6f6a22d7591beed2f7a9d9fee20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e80b38dfd0d7e5a37e81b971d633a0f">RawSDNodeBits</a>[sizeof(uint16_t)]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/sdnodebitfields">SDNodeBitfields</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb910e6a374ba558af8571d2a0a095ed">SDNodeBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/constantsdnodebitfields">ConstantSDNodeBitfields</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72447d1a1b836c2f0e8b6ff423e3b0b">ConstantSDNodeBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/memsdnodebitfields">MemSDNodeBitfields</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434bf5710046ffbca878d6379c5a6be5">MemSDNodeBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/lsbasesdnodebitfields">LSBaseSDNodeBitfields</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4237d5ad92a3df47c762bdacb7b109e3">LSBaseSDNodeBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/loadsdnodebitfields">LoadSDNodeBitfields</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a305e5de87d3873ae5ae1b8de12b631f7">LoadSDNodeBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/storesdnodebitfields">StoreSDNodeBitfields</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ebb56a2ad697ea3d91bdddf419af1a">StoreSDNodeBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e75d949a65ef6909562f6439494ac06">PersistentId</a> = 0xffff</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique and persistent id per <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> in the DAG. <a href="#a9e75d949a65ef6909562f6439494ac06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/sdnode">llvm::SDNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03bbc707a0208f54539d04e1409394ae"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb08146a9ce597bbe0fe041688b3bc5">NodeType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The operation that this node performs. <a href="#a1cb08146a9ce597bbe0fe041688b3bc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef304988dcedfe2ebc817313643be37">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40398a7840619a7b5da46c6f5db238f6">NodeId</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique id per <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> in the DAG. <a href="#a40398a7840619a7b5da46c6f5db238f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sduse">SDUse</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7176483afc8e1542f045bfaf8b5e9a0">OperandList</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The values that are used by this operation. <a href="#aa7176483afc8e1542f045bfaf8b5e9a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55fc5cc51d97d619d16fcd99ae1f340a">ValueList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The types of the values this node defines. <a href="#a55fc5cc51d97d619d16fcd99ae1f340a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sduse">SDUse</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff2eb8ff3c1bbcfbd468555842d4c3e6">UseList</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of uses for this <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. <a href="#aff2eb8ff3c1bbcfbd468555842d4c3e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa90c58a600afe6f83489372f2af02492">NumOperands</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of entries in the Operand/Value list. <a href="#aa90c58a600afe6f83489372f2af02492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac307623c65c259fa04b58d17a6455fd">NumValues</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d759f51453759d2975f734dec314c9">IROrder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff203d6ee679a31b8a42dd5034151a1">debugLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source line information. <a href="#adff203d6ee679a31b8a42dd5034151a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2e332a415a60ff9a00abb3d402f1ea">CombinerWorklistIndex</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index in worklist of DAGCombiner, or negative if the node is not in the worklist. <a href="#a6a2e332a415a60ff9a00abb3d402f1ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad60e923c79b6c8955a62191bc8f1081">CFIType</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdnode/use-iterator">use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef02f2c1bd12936a80611b134b24a47d">use_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdnode/user-iterator">user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9d6f3ddac69a00594e8cc1510081e4">user_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c6beebf86835d6582b0550cd7731ee9">hasPredecessorHelper</a> (const SDNode *N, SmallPtrSetImpl&lt; const SDNode * &gt; &amp;Visited, SmallVectorImpl&lt; const SDNode * &gt; &amp;Worklist, unsigned int MaxSteps=0, bool TopologicalPrune=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if N is a predecessor of any node in Worklist. <a href="#a7c6beebf86835d6582b0550cd7731ee9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a921a083162ebeec8f46240c1a48fef7b">areOnlyUsersOf</a> (ArrayRef&lt; const SDNode * &gt; Nodes, const SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all the users of N are contained in Nodes. <a href="#a921a083162ebeec8f46240c1a48fef7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b45952f6124e0e70fed54f06c59a9b">getMaxNumOperands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum number of operands that a <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> can hold. <a href="#a37b45952f6124e0e70fed54f06c59a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ba18a788637b22646b09602bd5a50c8">getIndexedModeName</a> (ISD::MemIndexedMode AM)</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/sdvtlist">SDVTList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7154dd9788b4b7afed19471c3a7393f8">getSDVTList</a> (MVT VT)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009a116b8e60eed5f2174a2370db6357">getValueTypeList</a> (MVT VT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the specified value type. <a href="#a009a116b8e60eed5f2174a2370db6357">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents one node in the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>.</p>

<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### op\_iterator {#a423c330f7f1bd8f3510e2bb304435217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SDNode::op_iterator =  SDUse *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### value\_iterator {#a6da24f4af897a7ec4e4afcf5abf49bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SDNode::value_iterator =  const EVT *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a241f78dc8dec652ff7cbdfba3523d909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumSDNodeBits<a id="a241f78dc8dec652ff7cbdfba3523d909af99253d30ce7209aefa17b88419ead1a"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### anonymous enum  {#af10ea0cefa5fe5d315b71f1c38617ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumMemSDNodeBits<a id="af10ea0cefa5fe5d315b71f1c38617ee9a1cb0194ce297ca739380384decb93793"></a></td>
<td class="doxyEnumItemDescription"> (= NumSDNodeBits + 4)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### anonymous enum  {#a738d6a19c3422882f90fb4a42b9db297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumLSBaseSDNodeBits<a id="a738d6a19c3422882f90fb4a42b9db297a8548b8dad9b4968732c9d0713003a528"></a></td>
<td class="doxyEnumItemDescription"> (= NumMemSDNodeBits + 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### HandleSDNode {#a9b5fbf1cb74d1e5c2e40343877aa9a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/handlesdnode">HandleSDNode</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a9b5fbf1cb74d1e5c2e40343877aa9a26">HandleSDNode</a>.</p>


<p>Referenced by <a href="#a9b5fbf1cb74d1e5c2e40343877aa9a26">HandleSDNode</a>.</p>

</div>
</div>

### SelectionDAG {#a6398ba1604e154e21413ce15dd4a180e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>


<p>Referenced by <a href="#addc45c27e50b974d99ba074ebfc4930c">dump</a>, <a href="#a89206bcd1c676ffdbfe8a8494c187524">dumpr</a>, <a href="#a1b25769866228a5517d8e752fad14f10">dumprFull</a>, <a href="#a9f4da658044d115b980e5c832fa25cdb">dumprWithDepth</a>, <a href="#a59192c42d4cbf804fbcc1deff8edb614">getOperationName</a>, <a href="#a998e1d9da008364ea6a05c3a0c891b69">print</a>, <a href="#ac351340ed4428a1b6d69d303bcba86d9">print_details</a>, <a href="#ad4e2295ddf513d5a4898fa7b3f1c2121">print_types</a>, <a href="#a6d72e52ee2c6a11256e6d04c8820e648">printr</a>, <a href="#a5db0a95c12b4b5ee310ea283172e3e49">printrFull</a>, <a href="#a9d07a0db71661297bf458ca459bfe448">printrWithDepth</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### SDNode() {#af64f53af99d4ee7bbf57ea0aab719254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDNode::SDNode (unsigned Opc, unsigned Order, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> dl, <a href="/web-llvm/docs/api/structs/llvm/sdvtlist">SDVTList</a> VTs)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>.</p>


<p>SDNodes are created without any operands, and never own the operand storage. To add operands, see SelectionDAG::createOperands.</p>


<p>Definition at line 1160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/structs/llvm/sdvtlist/#a9acb0dfa28d030504ff28965e13cabc2">llvm::SDVTList::NumVTs</a> and <a href="#a0e80b38dfd0d7e5a37e81b971d633a0f">RawSDNodeBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/addrspacecastsdnode/#a42ceea84cf9570ba5a2b3a68fa1ccb9c">llvm::AddrSpaceCastSDNode::AddrSpaceCastSDNode</a>, <a href="#a921a083162ebeec8f46240c1a48fef7b">areOnlyUsersOf</a>, <a href="/web-llvm/docs/api/classes/llvm/assertalignsdnode/#ae90bc65d848fbc977a8fcf05ba1474bd">llvm::AssertAlignSDNode::AssertAlignSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastsdnode/#ab417937f7065fb8f2fd6509a2279a3f7">llvm::AddrSpaceCastSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/assertalignsdnode/#ad5625bdeff1e616c6921272ee0428d66">llvm::AssertAlignSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblocksdnode/#ad2c1d1d7e25eacb722ed594cbde6fd25">llvm::BasicBlockSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddresssdnode/#a7e1a594943e424bdf5808be7065c4901">llvm::BlockAddressSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#ad44d0f0f1fddc11c4cf8b7566fdd33fd">llvm::BuildVectorSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/condcodesdnode/#aa023aa408a7fb45b90f2a834b6cc6d03">llvm::CondCodeSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode/#ac850cec521b9efe4f9ba07140dc27aa7">llvm::ConstantFPSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpoolsdnode/#a3bb40b90b6a488d35fc9989d17997ad3">llvm::ConstantPoolSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a8a38bf53cfdddb11ff0013d1cd03d7a0">llvm::ConstantSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/externalsymbolsdnode/#aa2dff47aa3ff2713b537f82f5facf032">llvm::ExternalSymbolSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/frameindexsdnode/#a2595b3f94e347d81a2f1340a70e94476">llvm::FrameIndexSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#aaa61d0186a5eb8eb0bbcc5d1dd84faf5">llvm::GlobalAddressSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/jumptablesdnode/#a50f6f04e01fd573979edd2b80f963157">llvm::JumpTableSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/labelsdnode/#aee4e77e817660e229aef189c7744345e">llvm::LabelSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/lifetimesdnode/#a378685595d8e8e30c7a229380f891413">llvm::LifetimeSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/machinesdnode/#a82bc51b7e0e7b18ed0eeb4deb352d0d2">llvm::MachineSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolsdnode/#ad372994148634ada144d3e6f5141da00">llvm::MCSymbolSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnodesdnode/#a07e30c80d76b5be01f224385c1cecacc">llvm::MDNodeSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ad55691554da9be384e9393e8b42a431a">llvm::MemSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobesdnode/#a2232b705cb5b1647c8f02882ded6c240">llvm::PseudoProbeSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/registermasksdnode/#adb0df75116db86aa5f41990e9961c4fc">llvm::RegisterMaskSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/registersdnode/#a2b7677e3fe371ebe62c2aed17862f5c6">llvm::RegisterSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#ae7c77fc01f65af9d9ce0e35a266a2da5">llvm::ShuffleVectorSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/srcvaluesdnode/#a32b59c9133361163a2d1c4203d9bdf32">llvm::SrcValueSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/targetindexsdnode/#acc1bf32d5c273c2477089b2b7df3a24e">llvm::TargetIndexSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vtsdnode/#ae82a2be488a727c9f52c2122ba47159f">llvm::VTSDNode::classof</a>, <a href="#ae1fa8ded9bce6f8321a69e99e41a473c">getGluedNode</a>, <a href="#a2594280bfba5f9b0dff74cfb5b4f29d2">getGluedUser</a>, <a href="/web-llvm/docs/api/classes/llvm/handlesdnode/#a2321efb50c82783a57ab32a79830f213">llvm::HandleSDNode::HandleSDNode</a>, <a href="#ab250276b651715d29b3ed20467d5f0a0">hasPredecessor</a>, <a href="#a7c6beebf86835d6582b0550cd7731ee9">hasPredecessorHelper</a>, <a href="#a2998329e16665f7101fac0ae9faee5c7">isOnlyUserOf</a>, <a href="#a94aa946198a3279b30a6d3a943dede42">isOperandOf</a>, <a href="#aaf99b3ee1d9577ac86d3bf072c7bc789">isPredecessorOf</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a00a2cd9501aed5f7e8746c0458990503">llvm::MemSDNode::MemSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblocksdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::BasicBlockSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddresssdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::BlockAddressSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/condcodesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::CondCodeSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::ConstantFPSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::ConstantSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/externalsymbolsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::ExternalSymbolSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/frameindexsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::FrameIndexSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::GlobalAddressSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/jumptablesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::JumpTableSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/labelsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::LabelSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/lifetimesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::LifetimeSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/machinesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::MachineSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::MCSymbolSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnodesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::MDNodeSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::PseudoProbeSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/registermasksdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::RegisterMaskSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/registersdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::RegisterSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/srcvaluesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::SrcValueSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/vtsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::VTSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a8b709750f62542669404fdd83478fa70">llvm::ShuffleVectorSDNode::ShuffleVectorSDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/targetindexsdnode/#a2879c5ff3ec8e47fbe71c6ad2fb4346b">llvm::TargetIndexSDNode::TargetIndexSDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addUse() {#ab41099ecc9dbea4f74062c85c0a8c6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDNode::addUse (<a href="/web-llvm/docs/api/classes/llvm/sduse">SDUse</a> &amp; U)</td>
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

<p>This method should only be used by the <a href="/web-llvm/docs/api/classes/llvm/sduse">SDUse</a> class.</p>

<p>Definition at line 1148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### dropFlags() {#a36b7f42c61a6ad5abfb26642fde7e354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDNode::dropFlags (unsigned Mask)</td>
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



<p>Definition at line 1045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### dump() {#a1f4346248feeb9d5c83ce930555936d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDNode::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump this node, for debugging.</p>

<p>Declaration at line 1115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="#a1f4346248feeb9d5c83ce930555936d1">dump</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="#a1f4346248feeb9d5c83ce930555936d1">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ab34667f1d218ea0b6566dd8f861dfe93">llvm::ScheduleDAGSDNodes::dumpNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a734032526577f3bd7808bcc857f35537">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#aae5d1e82046f7e049df2177e29a9d6f7">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a75d2b594fff24fcfffe9a72415deddb4">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::ReplaceNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a323d195cf1866ae715c63c287fcbbac6">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::ReplaceNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#ad82aafc598baf7fa600ef818155a1b75">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::ReplaceNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a7417c14840fc003b216fdadb6b93e631">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::ReplaceNodeWithValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a254b0db030fe653dbe78f9336bf97c39">tryLowerToSLI</a>.</p>

</div>
</div>

### dump() {#addc45c27e50b974d99ba074ebfc4930c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDNode::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump this node, for debugging.</p>


<p>The given <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> allows target-specific nodes to be printed in human-readable form.</p>


<p>Declaration at line 1123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="#a998e1d9da008364ea6a05c3a0c891b69">print</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>

</div>
</div>

### dumpr() {#a4efc0c778a7afdaf5b5a45594bc809a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDNode::dumpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump (recursively) this node and its use-def subgraph.</p>

<p>Declaration at line 1118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 1121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#a8b40b63522fe1b491ba458feec392ea6">DumpNodesr</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### dumpr() {#a89206bcd1c676ffdbfe8a8494c187524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDNode::dumpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump (recursively) this node and its use-def subgraph.</p>


<p>The given <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> allows target-specific nodes to be printed in human-readable form.</p>


<p>Declaration at line 1128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 1126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#a8b40b63522fe1b491ba458feec392ea6">DumpNodesr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>

</div>
</div>

### dumprFull() {#a1b25769866228a5517d8e752fad14f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDNode::dumprFull (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>printrFull to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>.</p>


<p>The given <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> allows target-specific nodes to be printed in human-readable form. Unlike dumpr, this will print the whole DAG, including children that appear multiple times.</p>


<p>Declaration at line 1134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="#a9f4da658044d115b980e5c832fa25cdb">dumprWithDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abb8c86cb032981edbbf6bf507ba2aa32">llvm::SelectionDAG::AssignTopologicalOrder</a>.</p>

</div>
</div>

### dumprWithDepth() {#a9f4da658044d115b980e5c832fa25cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SDNode::dumprWithDepth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G=nullptr, unsigned depth=100)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>printrWithDepth to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>.</p>


<p>The given <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> allows target-specific nodes to be printed in human-readable form. Unlike dumpr, this will print children that appear multiple times wherever they are used.</p>


<p>Declaration at line 1141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a9d07a0db71661297bf458ca459bfe448">printrWithDepth</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>


<p>Referenced by <a href="#a1b25769866228a5517d8e752fad14f10">dumprFull</a>.</p>

</div>
</div>

### getAsAPIntVal() {#a10c953187c10b57c4d91c7cb3cd877d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APInt &amp; llvm::SDNode::getAsAPIntVal ()</td>
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

<p>Helper method returns the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value of a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a>.</p>

<p>Definition at line 990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#add97272311c92ae6e05533bf8718447f">combineAndOrForCcmpCtest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a72f1d6515236af504f465f5b35249e2b">combineSelectToBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a925ab60e01665e8956b384fb79d7491c">combineShiftRightArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f4cf2e3dcecef6763caca7fd8949d76">combineX86SubCmpForFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b307d4ad3f5e1ae0c9888b5d0cc6b54">foldBinOpIntoSelectIfProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### getAsZExtVal() {#a7c6e64fef2ad2ba4052cd8365e97e8d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SDNode::getAsZExtVal ()</td>
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

<p>Helper method returns the zero-extended integer value of a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a>.</p>

<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09ed4b8df3900d37518583f29bbb0144">llvm::SIInstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a69f0725f2fda3046317ef070e37e06ec">expandDivFix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a1a14301103c8d97e52ed0ca117ea6b65">llvm::PPC::get_VSPLTI_elt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac8e70a2e70e45733c882bb7b103a9c88">getCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="#a59192c42d4cbf804fbcc1deff8edb614">getOperationName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afaf1cbe4bd00ba18fb62321d5cbe4646">getUnderlyingExtractedFromVec</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afe52999c6dfc815ec8496f43626191eb">isF128MovedFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3d6a6ccf92180726bf08404b1e112fe3">LowerEXTRACT_VECTOR_ELT_SSE4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#aa0ab0addd3e58b6c75b6a27be6caf4b5">llvm::MSP430TargetLowering::LowerSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a95bb2318cffbd613f244603838b30094">lowerVectorIntrinsicScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab051a4c12430b297d1465afcb7cf8485">llvm::ARMTargetLowering::PerformBRCONDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2a5ac33b69bb7d7687d12dc0dffe9f08">performBRCONDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a4ba6b9afcc5b700d4c09664b5fa009d9">llvm::ARMTargetLowering::PerformCMOVCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a963a08f31bbf8cb9396ff5214bc7ae26">PerformORCombineToBFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">llvm::LoongArchTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a977ad76f842f5addf1b023121d96465e">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a075b3dafc91e9c39ed0f94ba7d604505">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrModePC</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ae058898e63ec72af7e4ed9b50ac8fbec">llvm::PPCTargetLowering::SelectOptimalAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a25c98938cd912093a0d041928ea746fc">splatPartsI64WithVL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ae3ce3a45a296052aac0a59f4cd475368">tryFoldMADwithSRL</a>.</p>

</div>
</div>

### getCFIType() {#a02bd3912ea1a5ed151646c98aa65dacd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SDNode::getCFIType ()</td>
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



<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### getCombinerWorklistIndex() {#a3d8d21239b7e041fd6955bbbcf83551c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SDNode::getCombinerWorklistIndex ()</td>
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

<p>Get worklist index for DAGCombiner.</p>

<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### getConstantOperandAPInt() {#a9dfad184e37d97a10814cdce3d46c072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APInt &amp; llvm::SDNode::getConstantOperandAPInt (unsigned Num)</td>
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

<p>Helper method returns the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> of a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> operand.</p>

<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a8388f666d6e735f35837ad03ed1f7a7a">getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a3ef62399dd4b7e5dbc8398704aaa79bc">llvm::BuildVectorSDNode::isConstantSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2ab3403403aae0dd2e28fd96af0e4c39">ParseBFI</a>.</p>

</div>
</div>

### getConstantOperandVal() {#a90cd0589eba5e5112a68717f122f1fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::SDNode::getConstantOperandVal (unsigned Num)</td>
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

<p>Helper method returns the integer value of a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a> operand.</p>

<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a8388f666d6e735f35837ad03ed1f7a7a">getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09ed4b8df3900d37518583f29bbb0144">llvm::SIInstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7877081a6d6934a224f09a048611ecf1">checkBoolTestAndOrSetCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f4cf2e3dcecef6763caca7fd8949d76">combineX86SubCmpForFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a44384f1a2c70a34d648ffb22d2c6bfb1">extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a44384f1a2c70a34d648ffb22d2c6bfb1">extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a54a58a0466a38d38cc1fc0c57513195f">foldCSELOfCSEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a61378df65052d091f64f8ac2657758b7">getMemVTFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a6df0bebd8a9245a944f0682ac1231a1b">llvm::HexagonDAGToDAGISel::LoadInstrForLoadIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6c02410f9bb19b5b6eb61c9711ae4156">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad6bb7ee72f79badd15b563bf112de6e5">performBuildVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7b5373efa0bde041422551595378b61">performSetCCPunpkCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0670f21ebeafbaab3f4b34c8140b8dc8">replaceZeroVectorStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ae29a60720e41fdf677935d16ad9d3b5b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a97ed12d88f268d0adc4202788727a7e7">llvm::HexagonDAGToDAGISel::SelectBrevLdIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a420a3a405f7aa80d6963eb2d9a2d641b">llvm::HexagonDAGToDAGISel::SelectNewCircIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#abbdb66ef7655ebae91e2bbfab4320f23">simplifyMul24</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreiseldagtodag-cpp-/xcoredagtodagisel/#af3ca2da669fcab80222c31e39e32287d">anonymous{XCoreISelDAGToDAG.cpp}::XCoreDAGToDAGISel::tryBRIND</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#afe51519b53f2da04c9a224a1da7bd2bc">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectStackSlotTagP</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>.</p>

</div>
</div>

### getDebugLoc() {#a999ec9d4610ecb7c24d399bbc447ed70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; llvm::SDNode::getDebugLoc ()</td>
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

<p>Return the source location info.</p>

<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="#a998e1d9da008364ea6a05c3a0c891b69">print</a>.</p>

</div>
</div>

### getFlags() {#a5023bb0687db0b35d3b2d19327217ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNodeFlags llvm::SDNode::getFlags ()</td>
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



<p>Definition at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acfa813720f554bb68a6e8c5fdb870f4e">combineEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae222abd7ba47c29a86fc6be7f3dd02fb">combineFaddCFmul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7a388b8e71542c8223c73a0d99691c71">combineFneg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab160c4766dfd9c2f981e092e730fd1b0">combineShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#abeb92f766ab3212ede2e5c3ddff2a1a6">isNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a95c8b57eb11e8d25decddd3c86c9703c">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isSupportedRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa5e728389b60e4210dc8e60dc114ee56">llvm::VPMatchContext::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a3ee9c785b2ee5b9c02f9caf6c76b271f">narrowInsertExtractVectorBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6913e341612419ecb5b860b6759b929c">llvm::AMDGPUTargetLowering::performFNegCombine</a>, <a href="#ac351340ed4428a1b6d69d303bcba86d9">print_details</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

### getGluedNode() {#ae1fa8ded9bce6f8321a69e99e41a473c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * llvm::SDNode::getGluedNode ()</td>
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

<p>If this node has a glue operand, return the node to which the glue operand points.</p>


<p>Otherwise return NULL.</p>


<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="#a7f311fcc2415eee3cb3694013b985304">getNumOperands</a>, <a href="#a8388f666d6e735f35837ad03ed1f7a7a">getOperand</a>, <a href="#ac0a534d63ac5c5b87f36acdade953fbe">getValueType</a> and <a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a6a91ff524836d3fca6cabe37c8fb7dc5">canClobberPhysRegDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ab34667f1d218ea0b6566dd8f861dfe93">llvm::ScheduleDAGSDNodes::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#aa405be8f26bc0ffcd089589d15327400">isOperandOf</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#afba9f58251019a23a1d7f60d6c958071">llvm::ResourcePriorityQueue::isResourceAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a> and <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae30e9e0cfb98797266d9fc1226cf467d">llvm::ResourcePriorityQueue::reserveResources</a>.</p>

</div>
</div>

### getGluedUser() {#a2594280bfba5f9b0dff74cfb5b4f29d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * llvm::SDNode::getGluedUser ()</td>
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

<p>If this node has a glue value with a user, return the user (there is at most one).</p>


<p>Otherwise return NULL.</p>


<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a> and <a href="#a42e9a628b333dddfcc9d5fb17824dc17">uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a98c172c9b66de1264ee2123e4f1a3df2">llvm::SelectionDAGISel::IsLegalToFold</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledaglinearize/#ac5dfad52f2ec0adbc920cf686c615e00">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::Schedule</a>.</p>

</div>
</div>

### getHasDebugValue() {#a478a16ce230e9f3901fdc6847bc063b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::getHasDebugValue ()</td>
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



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#afb910e6a374ba558af8571d2a0a095ed">SDNodeBits</a>.</p>


<p>Referenced by <a href="#ac351340ed4428a1b6d69d303bcba86d9">print_details</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afce558f34a90609d76e4c2f45ab5650c">llvm::SelectionDAG::transferDbgValues</a>.</p>

</div>
</div>

### getIROrder() {#a2c7563253850e555f36f44d91157e5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDNode::getIROrder ()</td>
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

<p>Return the node ordering.</p>

<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a2b381affe49c1a381183698a2a69aec9">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::getNodeOrdering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a5d3cc5ce2199f840a6a9273c2285746e">PerformFADDCombineWithOperands</a>, <a href="#ac351340ed4428a1b6d69d303bcba86d9">print_details</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ab898c0fc6a2159b032a398271add3927">llvm::SelectionDAGBuilder::resolveDanglingDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afce558f34a90609d76e4c2f45ab5650c">llvm::SelectionDAG::transferDbgValues</a>.</p>

</div>
</div>

### getMachineOpcode() {#a7f96a3399d86d6f136aaa121de4217a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDNode::getMachineOpcode ()</td>
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

<p>This may only be called if isMachineOpcode returns true.</p>


<p>It returns the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> opcode value that the node's opcode corresponds to.</p>


<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a1223d6e9a7dfb6e51299b894beccc679">isMachineOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab1ec5f3b915078525275298dc021f58c">llvm::ARMBaseInstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09ed4b8df3900d37518583f29bbb0144">llvm::SIInstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a2d2ea6e61626afee21fc7752c9affa05">llvm::X86InstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a4ba2ac7568356ddd4b07a7f1718c8d6a">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::canClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a0e8adf21ba4a3e746edcd3b9cf9c5d14">llvm::SITargetLowering::checkForPhysRegDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae2caf47c7fb0d8972d9c1f261beaf289">getMaskSetter</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa65c4a19ddc8ce7ddec084e5a1a4a62a">llvm::TargetInstrInfo::getOperandLatency</a>, <a href="#a59192c42d4cbf804fbcc1deff8edb614">getOperationName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#ab355b8de097910b27f8a8527f9d2e512">getUsefulBitsForUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a5c013753f05b14d6d638ffe65860c6f1">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#afba9f58251019a23a1d7f60d6c958071">llvm::ResourcePriorityQueue::isResourceAvailable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a99ae43a8879de19170e80277b5c54b88">nodesHaveSameOperandValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae30e9e0cfb98797266d9fc1226cf467d">llvm::ResourcePriorityQueue::reserveResources</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ac624f59926b6618a1da5645cae8bc2c5">llvm::ARMBaseInstrInfo::shouldScheduleLoadsNear</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a72ba34ed2a0e75181bfecf7d463156f8">llvm::X86InstrInfo::shouldScheduleLoadsNear</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ab58a68a9178bb332e0c3f5c19fd381ec">llvm::HexagonDAGToDAGISel::StoreInstrForLoadIntrinsic</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>.</p>

</div>
</div>

### getNodeId() {#a1bdddc5f08b7b8b77e2518296dd4d84f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SDNode::getNodeId ()</td>
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

<p>Return the unique node id.</p>

<p>Definition at line 746 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a4ba2ac7568356ddd4b07a7f1718c8d6a">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::canClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a7c404b9b284d7d53f3aec00e776cd5b7">insertDAGNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#ae61c505ef5dc38733d7b12b91e545a44">insertDAGNode</a>, <a href="#ac351340ed4428a1b6d69d303bcba86d9">print_details</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledaglinearize/#ac5dfad52f2ec0adbc920cf686c615e00">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::Schedule</a> and <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>.</p>

</div>
</div>

### getNumOperands() {#a7f311fcc2415eee3cb3694013b985304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDNode::getNumOperands ()</td>
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

<p>Return the number of values used by this operation.</p>

<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5425376fb8bb34c4f59a84a3ee70c790">AddCombineTo64bitMLAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#aff339c6bc38a08e357a06878c1ab11db">checkWMMAElementsModifiersF16</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae212b33ea9fc9947ff01a147fd5e8606">combineConcatVectorOfConcatVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a71a49469d7d437afe471a050139f094f">createMMXBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a1713768600a9f5a62eb74a616aa73428">llvm::BuildVectorSDNode::getConstantRawBits</a>, <a href="#ae1fa8ded9bce6f8321a69e99e41a473c">getGluedNode</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a28caa20d9fc8a395fd4253ccbfe7eb48">llvm::BuildVectorSDNode::getRepeatedSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#acf005731b7353e3224b7742a356ffb0e">llvm::BuildVectorSDNode::getRepeatedSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a1d322fa0d9ca562c6b20cac2d8a0a5dd">llvm::BuildVectorSDNode::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a66b06a3a00ea8358c447658d398dc3f8">llvm::BuildVectorSDNode::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a3ef62399dd4b7e5dbc8398704aaa79bc">llvm::BuildVectorSDNode::isConstantSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afe52999c6dfc815ec8496f43626191eb">isF128MovedFromParts</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6c02410f9bb19b5b6eb61c9711ae4156">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a56ba18b7bb062d32ea351c6349a415c6">performSRACombine</a>, <a href="#a998e1d9da008364ea6a05c3a0c891b69">print</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a7be640126e3f1024b18981f1de2de20f">llvm::ResourcePriorityQueue::rawRegPressureDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2c166ebb81953ce2aa531c18213e0011">reduceBuildVecToShuffleWithZero</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ae29a60720e41fdf677935d16ad9d3b5b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a420a3a405f7aa80d6963eb2d9a2d641b">llvm::HexagonDAGToDAGISel::SelectNewCircIntrinsic</a>.</p>

</div>
</div>

### getNumValues() {#a7f06dbaee5fa2b239de548d0a775b25b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDNode::getNumValues ()</td>
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

<p>Return the number of values defined/returned by this operator.</p>

<p>Definition at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5425376fb8bb34c4f59a84a3ee70c790">AddCombineTo64bitMLAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac8e70a2e70e45733c882bb7b103a9c88">getCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#af1e5625d39d26c7855682c2732c27ccf">getFPBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aec9cce3b9198ace9a6c61f1ad9280136">getFPTernOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a9ae4cee3cd6aafb475565cb82d033b40">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::getNodePriority</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aea5e8c9dbcb859012df08536bd29da15">getOutputChainFromCallSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe3b2bbac4396d088da5c91f77754843">llvm::SelectionDAGBuilder::getValueImpl</a>, <a href="#ab6ea142f5ae930a660fbb4105ef42a98">hasAnyUseOfValue</a>, <a href="#ad82ad170343d0b4fe88a5551ec43659d">hasNUsesOfValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a98c172c9b66de1264ee2123e4f1a3df2">llvm::SelectionDAGISel::IsLegalToFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp/#abd648b9bbf53e1b89e8e7e2695034268">isMemOPCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a203e9048ad3087cf61713d0d307a246c">llvm::SITargetLowering::legalizeTargetIndependentNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer/#a78a7f585aa9b0de8a1d509d616cc1b5e">llvm::DAGTypeLegalizer::NoteDeletion</a>, <a href="#ad4e2295ddf513d5a4898fa7b3f1c2121">print_types</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a7be640126e3f1024b18981f1de2de20f">llvm::ResourcePriorityQueue::rawRegPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac630ccda26fea2f45afa3fb89bc1a8f4">llvm::SelectionDAG::ReplaceAllUsesOfValueWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5da44486df08f753ea147fe04e86026f">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad09a0f9913dd2fad9b84458bdb263aaa">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8518c120f782df9e974c8b1b589feb40">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a75d2b594fff24fcfffe9a72415deddb4">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::ReplaceNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a323d195cf1866ae715c63c287fcbbac6">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::ReplaceNode</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a088c31366c990e0e055fbe65766e8d2e">llvm::AVRTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#ac8513ff0e5a1f54815ec2807648fe0f6">anonymous{DAGCombiner.cpp}::DAGCombiner::Run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1e801ca0fc0ae63d482926b72ce3b45c">scalarizeExtractedBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### getOpcode() {#a23f2f5947fc429aff1270651c6d019ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDNode::getOpcode ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> opcode value for this node.</p>


<p>For pre-isel nodes (those for which isMachineOpcode returns false), these are the opcode values in the <a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a> and &lt;target&gt;<a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a> namespaces. For post-isel opcodes, see getMachineOpcode.</p>


<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5425376fb8bb34c4f59a84a3ee70c790">AddCombineTo64bitMLAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a308239e88ecd5485cd72bf0f9ea300d7">AddCombineTo64bitUMAAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp/#a7205a09270a6b2b5f382416d022b39e4">allowARIDWithDisp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp/#aeb46ceff4613693a14720e867bf55f57">AllowARIIWithZeroDisp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a665697d954db3756f083f5db4cafe5dc">canEmitConjunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a07e9d7ff453553fd3e5e64c9d93d5d07">canEnableCoalescing</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#affe8145f52cae856369a22fa52019397">anonymous{RISCVISelLowering.cpp}::canFoldToVW_SU</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#a8b2154a7e9a794c5b363a5c2c1e489bd">anonymous{RISCVISelLowering.cpp}::canFoldToVW_W</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvisellowering-cpp-/#adec3c0687a05bd66a2a9937f4a374d34">anonymous{RISCVISelLowering.cpp}::canFoldToVWWithSameExtensionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a415e74316c092fb208d6725d7ee4ff95">canLowerSRLToRoundingShiftForVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#addc8ecda6f7aec38ce2769862c04eb0f">closestSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad1b9f6a1979dddff5b170976bfd53c52">CombineANDShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5dc2c71746128f53bed7b56d72316f1d">combineBitOpWithShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab160c4766dfd9c2f981e092e730fd1b0">combineShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5efc2b9d3d3b40b85f5f7366bc145837">combineSubShiftToOrcB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab039512652c2e46b69e54b91ba5d0dc3">combineToExtendCMOV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f4cf2e3dcecef6763caca7fd8949d76">combineX86SubCmpForFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a588e5dcf7ccf9ec2b6922f24c012a08a">emitConjunctionRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a44384f1a2c70a34d648ffb22d2c6bfb1">extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a44384f1a2c70a34d648ffb22d2c6bfb1">extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b307d4ad3f5e1ae0c9888b5d0cc6b54">foldBinOpIntoSelectIfProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af91c2a3b14c738c31113158a698e0324">foldMaskedMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aec15e9006d3d3507d186d2f98525aecc">llvm::SelectionDAG::FoldSymbolOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#a7a8b106c04d7ad2177a98cd55d554c1e">llvm::AtomicSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aa97617ded03926053f78ec06608f32bb">llvm::MemSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#ac878f3428a5bad7aab5ea896279ddb0c">llvm::VPBaseLoadStoreSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#aa39ec573c06f366f5dd8501db78cdc55">llvm::VPGatherScatterSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1cea2904e9cf054e408e6023cd8b852c">llvm::getBitwiseNotOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae40536e54a704fc900dd851134869a48">getConstantLaneNumOfExtractHalfOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#a9adf1f62190a4bb8e413e90a80b1d30b">llvm::AtomicSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a7f35a1195b2f7e4b5ddac3b560ecc026">llvm::VPGatherScatterSDNode::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#a15af2bb174c26b84e4e95189b6269061">llvm::MaskedLoadStoreSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a28b67759403dd76217036777c0e83ca6">llvm::VPBaseLoadStoreSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#af5b443bb58f583818fa0a8ebeb702ac0">llvm::VPGatherScatterSDNode::getMask</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a0aaa2e30b965ca8584badc25c324958d">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getMaskAndVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a61378df65052d091f64f8ac2657758b7">getMemVTFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a9ae4cee3cd6aafb475565cb82d033b40">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::getNodePriority</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ac5504ff57aff2070132ce601e1a25924">getNormalLoadInput</a>, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#a627db7f6090192061ab9493cbb6d1881">llvm::LSBaseSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#ac469e176938b3fc117e515e5110bc4f5">llvm::MaskedLoadStoreSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a8b61ddb92d8209dadefb79dd6ba3ed55">llvm::VPBaseLoadStoreSDNode::getOffset</a>, <a href="#a59192c42d4cbf804fbcc1deff8edb614">getOperationName</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#afa89bad4ae6c9667571ba16df07adf70">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getOrCreateExtendedOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a59f302f024d9a267fb828052606a707d">llvm::VPGatherScatterSDNode::getScale</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a776c5a5c2c4c9c913f9b44e5b0437f69">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSupportedFoldings</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#aedff02bc7a3014d6a1a017a46dad11dd">llvm::AtomicSDNode::getVal</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#ab78e96ef913d507fc7f16bd2941e8b40">llvm::VPBaseLoadStoreSDNode::getVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a74e51fad18332454f2fbd005b9071090">llvm::VPGatherScatterSDNode::getVectorLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a16fdb3e37daf197199709a37540402d0">hasOnlyLiveInOpers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a22c99596004378b139e9ab48fae048dc">hasOnlyLiveOutUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abcc89aad99c6a03adb5443eb5fa9f93c">isAddSubOrSubAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a4b1f6c2a4e7b3aed4f56643d545f305b">isBitfieldExtractOpFromAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#ae1be01ee8290461b0f344a0c0c3058a4">llvm::AtomicSDNode::isCompareAndSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0e3aa05aca949e6905dcb30c81c679e3">llvm::ARMTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a52376a753c8ddea8a93cc03bdecc4fcd">llvm::RISCVTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6c49319d93381e455f0138e221896629">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af4674b301fdc98e0a729a8d4690e45f2">isFloatingPointZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84e306a52da2372d1d398fb5a3c75c81">llvm::isLegalAVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp/#abd648b9bbf53e1b89e8e7e2695034268">isMemOPCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#abeb92f766ab3212ede2e5c3ddff2a1a6">isNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a5c013753f05b14d6d638ffe65860c6f1">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a6d5b4f84c3dda985bea36681d13bc55b">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#adb5a1dc721c95f38cb7951e826d9e646">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isSupportedFPExtend</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a95c8b57eb11e8d25decddd3c86c9703c">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isSupportedRoot</a>, <a href="#ad85183a1e40f2a1dc0840c22484b8eec">isVPOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a6df0bebd8a9245a944f0682ac1231a1b">llvm::HexagonDAGToDAGISel::LoadInstrForLoadIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#af8947d9c8165e82094241d319758e0c5">lowerCallFromStatepointLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab254961e69630f8f3d82f83429dd4be4">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a09b35db55ed7bd3a4027630fff72d970">LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/classes/llvm/emptymatchcontext/#a57a490617c60e8a5afc9fab788a0bb19">llvm::EmptyMatchContext::match</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa5e728389b60e4210dc8e60dc114ee56">llvm::VPMatchContext::match</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af6fb44d5b8fabbbd624ebe34231c5ce6">llvm::SelectionDAG::matchBinOpReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5f03e5e8300e8aee8c276ed87ea5cc3b">matchSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#ae4ff30a063f91465787152121a63d6ce">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::NodeExtensionHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2ab3403403aae0dd2e28fd96af0e4c39">ParseBFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aed7db4aa3ec7143f38592865c2c0455d">PerformADDVecReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6c02410f9bb19b5b6eb61c9711ae4156">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad6bb7ee72f79badd15b563bf112de6e5">performBuildVectorCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ada7b7dfe4d829cdafff6278e361547df">llvm::ARMTargetLowering::PerformCMOVToBFICombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a05ea7c29a0fde5a9a808c50aefd2e0fa">performCONDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a172a1f5983db0d10ae90c0d3f5beccdb">PerformExtractEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aefd957dcc1874b25b5b758324370d20d">performExtractVectorEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4c4ced6d8064c639d791e53119774fcf">performINSERT_VECTOR_ELTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a313d642b3a7b838825ec80b84909b9ce">performMADD_MSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5991e29bae68e989e978dc600f93b48e">performMemPairCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afe3fc9a96e843f0a30a80d4af77c1b26">PerformMinMaxCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a2dec0cffd4ecd689da9a7901b8b90124">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7b5373efa0bde041422551595378b61">performSetCCPunpkCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a56ba18b7bb062d32ea351c6349a415c6">performSRACombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a111643e86a00d697a134123e45817e14">PerformSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adac55a5ab0773a88dd987c4610e2ed59">PerformUMLALCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4d29144f0f49ccc2a115d389beaef36e">PerformVCMPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a19d36e331487399aaac4f18bac0c7956">PerformVMOVhrCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a40eb7d32bd58dfbdde6c632446a56828">PerformVMOVrhCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a14fe6050fa67f0e7b01314d5c7586b8e">performXORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2c166ebb81953ce2aa531c18213e0011">reduceBuildVecToShuffleWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a420129a3b8db368bc6768ddb7293255d">resetVRegCycle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ade0519245a3e86cb20548e200f65863e">scalarizeExtEltFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#af829baf84aa61aab9b55f9196427759a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddLikeOr</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ae29a60720e41fdf677935d16ad9d3b5b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a97ed12d88f268d0adc4202788727a7e7">llvm::HexagonDAGToDAGISel::SelectBrevLdIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#af1389c2a1baf930223956103b615a838">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a420a3a405f7aa80d6963eb2d9a2d641b">llvm::HexagonDAGToDAGISel::SelectNewCircIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#af619c526b5e90968d76fbd4fe4c861cb">llvm::RISCVDAGToDAGISel::selectShiftMask</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#a1f47a74aa91b1356aa1d2b7416cd06ea">llvm::AtomicSDNode::setExtensionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac6c9b791cef5925e123539fb2934316b">shouldCombineToPostInc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#abbdb66ef7655ebae91e2bbfab4320f23">simplifyMul24</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6f0cac8b7a7acd364d34649335444ceb">stripModuloOnShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acedf14c0b42fdeea7ed01a8a6e051299">transformAddImmMulImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab64eb471c9d5a9db3c882d6bed499ddd">transformAddShlImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreiseldagtodag-cpp-/xcoredagtodagisel/#af3ca2da669fcab80222c31e39e32287d">anonymous{XCoreISelDAGToDAG.cpp}::XCoreDAGToDAGISel::tryBRIND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af27372c25a294d5d3b8ba864de3419b7">tryLowerPartialReductionToDot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae7edfd8337d702eebfdbf7010c3b2c74">tryMemPairCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#afe51519b53f2da04c9a224a1da7bd2bc">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectStackSlotTagP</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a1671cc3411876afb45d27eac3a048d4a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectXAR</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a92aeb185d8fa73b0d6b44f62e13af912">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryShiftAmountMod</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7072e7476bdcc2ff6396305b680fa83">tryToConvertShuffleOfTbl2ToTbl4</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae362c61a21181f35e570b2d94cdd2056">tryToFoldExtendSelectLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07229844dfee2ef29637eec9717bede7">tryToWidenSetCCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab2278ad575ade428648fc629fb5ecb45">widenAbs</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a45c76061665647247b00ba9b1967c407">widenCtPop</a>.</p>

</div>
</div>

### getOperand() {#a8388f666d6e735f35837ad03ed1f7a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::SDNode::getOperand (unsigned Num)</td>
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



<p>Definition at line 992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5425376fb8bb34c4f59a84a3ee70c790">AddCombineTo64bitMLAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af20aaa3827f50046072a07327167aee5">AddCombineTo64BitSMLAL16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a308239e88ecd5485cd72bf0f9ea300d7">AddCombineTo64bitUMAAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a37754d31c33565bdfd4903ab5e905a6a">AddCombineToVPADD</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab1ec5f3b915078525275298dc021f58c">llvm::ARMBaseInstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09ed4b8df3900d37518583f29bbb0144">llvm::SIInstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a2d2ea6e61626afee21fc7752c9affa05">llvm::X86InstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a4ba2ac7568356ddd4b07a7f1718c8d6a">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::canClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a04cb51bd51ce0d3d114071ed4c38183b">CanCombineFCOPYSIGN_EXTEND_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a665697d954db3756f083f5db4cafe5dc">canEmitConjunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a415e74316c092fb208d6725d7ee4ff95">canLowerSRLToRoundingShiftForVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7877081a6d6934a224f09a048611ecf1">checkBoolTestAndOrSetCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#aff339c6bc38a08e357a06878c1ab11db">checkWMMAElementsModifiersF16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad1b9f6a1979dddff5b170976bfd53c52">CombineANDShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4149392e82922475c1b566db35e3c8b8">combineAndShuffleNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c3d86d724323d88d2fdf99d29d3de72">combineBasicSADPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a62454aa5151d369549b3c0414bdf5646">combineCCMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a672f8f5fb89a9c2758df02f8e2d1e263">combineCompareEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae222abd7ba47c29a86fc6be7f3dd02fb">combineFaddCFmul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2a2b06cd0043981c801d852ace83fded">combineMaskedLoadConstantMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad7c52d56e60df127f4f9a429a5455590">combineSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab160c4766dfd9c2f981e092e730fd1b0">combineShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a69d159ccc8c9f4f70ed369d35c5c420b">combineShuffleOfBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade03879f56390aad1613d54401f911a5">combineShuffleOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a7847dc95e3ec6e1cdaa66ac48a0f7985">combineShuffleOfSplatVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6da34b4a62e36f7b3b51720f19d3e753">combineShuffleToAnyExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5efc2b9d3d3b40b85f5f7366bc145837">combineSubShiftToOrcB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab039512652c2e46b69e54b91ba5d0dc3">combineToExtendCMOV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af01458f5f68de9153c5392eebedfa0f1">combineTruncationShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a143e143f8ee315e712138f13f3343cd5">combineTruncToVnclip</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54b7a43507d8f339f806b8d1c9f12f29">combineVectorCompareAndMaskUnaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac5281f53eae7762532968413f7201798">CombineVMOVDRRCandidateWithVecOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8389740010ccf99686a066f0bdc4dbdc">combineVPDPBUSDPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a491cbf5a685bf7c4455335bc9606ac49">combineVWADDSUBWSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a108b26123f976ad2ab078287e4be83ef">combineZext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a71a49469d7d437afe471a050139f094f">createMMXBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af95bcf95fcfc5d82d24423018024641e">detectZextAbsDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a588e5dcf7ccf9ec2b6922f24c012a08a">emitConjunctionRec</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a66608723a39fea9af315107db02b6ef5">anonymous{DAGCombiner.cpp}::DAGCombiner::ExtendSetCCUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a44384f1a2c70a34d648ffb22d2c6bfb1">extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a44384f1a2c70a34d648ffb22d2c6bfb1">extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2d63c559640ebacf58b26c51ffa5b358">foldAddSubMasked1</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b307d4ad3f5e1ae0c9888b5d0cc6b54">foldBinOpIntoSelectIfProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a54a58a0466a38d38cc1fc0c57513195f">foldCSELOfCSEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af91c2a3b14c738c31113158a698e0324">foldMaskedMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70a3356be1e0bc8db5a2e2e5d8e6d7b1">foldMaskedMergeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8648786e9af485e27d907ecd2f2a2a08">foldOverflowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6aa5a20ccba4eafeded8c21562b71918">foldSelectOfCTTZOrCTLZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a781a75dfc661452760864c019bafd96e">foldShuffleOfConcatUndefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a614caf1728d9aec23d5fe873c92208c1">formSplatFromShuffles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab36c9d24e2e9bf7f23e297e087acb8ce">llvm::getAnnotatedNodeAVL</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#a7a8b106c04d7ad2177a98cd55d554c1e">llvm::AtomicSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a20fd5ba47db6a4cc8ad9d197fc1bbbee">llvm::LoadSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#a85c8136546badca2829e588d792b9aa3">llvm::MaskedGatherScatterSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedhistogramsdnode/#ade36860aa8301007204da6e3790973a5">llvm::MaskedHistogramSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadsdnode/#a1f864fce9d9468832543842342f27f28">llvm::MaskedLoadSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedstoresdnode/#a1cc9aee25dfe7ca5a4712bb35bc2e58a">llvm::MaskedStoreSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aa97617ded03926053f78ec06608f32bb">llvm::MemSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#a46c9e231f45e8c83b88089c0b013b87b">llvm::StoreSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#ac878f3428a5bad7aab5ea896279ddb0c">llvm::VPBaseLoadStoreSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#aa39ec573c06f366f5dd8501db78cdc55">llvm::VPGatherScatterSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/vploadsdnode/#ab0a49b77f174bb9700e10ff641555a7a">llvm::VPLoadSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#ae5686f70f3eb230c66231eba74e4c81a">llvm::VPStoreSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#accc1c4157f081c29a731f1b3218f2422">llvm::VPStridedLoadSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#a35124a6a1a9c430f877c0e16f747f042">llvm::VPStridedStoreSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86maskedgatherscattersdnode/#a0c5fac1e666cab274da583b96f480c21">llvm::X86MaskedGatherScatterSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab858661e16a61c4fc6b27b6b26aac17b">llvm::MemSDNode::getChain</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a85e6f92ca194a48ccbd299086709411b">llvm::SelectionDAG::getCommutedVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae40536e54a704fc900dd851134869a48">getConstantLaneNumOfExtractHalfOperand</a>, <a href="#a9dfad184e37d97a10814cdce3d46c072">getConstantOperandAPInt</a>, <a href="#a90cd0589eba5e5112a68717f122f1fbe">getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a1713768600a9f5a62eb74a616aa73428">llvm::BuildVectorSDNode::getConstantRawBits</a>, <a href="/web-llvm/docs/api/classes/llvm/lifetimesdnode/#a36ad577ee2189ada7f55321216833893">llvm::LifetimeSDNode::getFrameIndex</a>, <a href="#ae1fa8ded9bce6f8321a69e99e41a473c">getGluedNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4836b23626e1d7b24f8bb84be3a55667">getHopForBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedhistogramsdnode/#a0556e4325b1db8bf054411166fca7af8">llvm::MaskedHistogramSDNode::getInc</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#a21aa53cf563f733b571568804f2fe132">llvm::MaskedGatherScatterSDNode::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedhistogramsdnode/#ac674f6ea753e14902f93c57d7d4a18ab">llvm::MaskedHistogramSDNode::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a7f35a1195b2f7e4b5ddac3b560ecc026">llvm::VPGatherScatterSDNode::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86maskedgatherscattersdnode/#af269dcd95d67ab2e06e3bdc02733551c">llvm::X86MaskedGatherScatterSDNode::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedhistogramsdnode/#ab557a882da35ece52a563b773f35d71f">llvm::MaskedHistogramSDNode::getIntID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a17fca146e0dc0228bae32fe5548ab48a">getKnownUndefForVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#aa643ef2936e8a316202b42ba0039748c">llvm::MaskedGatherScatterSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedhistogramsdnode/#aacd48f85bafeb2961ef3e83536e77457">llvm::MaskedHistogramSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadsdnode/#a73e4a53e09c506d5a0fc379f31a51a4d">llvm::MaskedLoadSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#a15af2bb174c26b84e4e95189b6269061">llvm::MaskedLoadStoreSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedstoresdnode/#a29dc583cf3d72bd9a72628a68e20f235">llvm::MaskedStoreSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a28b67759403dd76217036777c0e83ca6">llvm::VPBaseLoadStoreSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#af5b443bb58f583818fa0a8ebeb702ac0">llvm::VPGatherScatterSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vploadsdnode/#a61f1568cf6aacb3a2980b8f1e5f84aa1">llvm::VPLoadSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#a2b0343c0c0472cc151d7225769121eea">llvm::VPStoreSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#a122e7fcbeb8950bea3149fd8e85ff298">llvm::VPStridedLoadSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#a3c797c8bdf07aac08877287398229f32">llvm::VPStridedStoreSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/x86maskedgatherscattersdnode/#adb1f451b03c08ed49f5669f2a8c68fe4">llvm::X86MaskedGatherScatterSDNode::getMask</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a0aaa2e30b965ca8584badc25c324958d">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getMaskAndVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae2caf47c7fb0d8972d9c1f261beaf289">getMaskSetter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a61378df65052d091f64f8ac2657758b7">getMemVTFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ac5504ff57aff2070132ce601e1a25924">getNormalLoadInput</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a71689ed396153740b31ac1a182364651">llvm::LoadSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#a627db7f6090192061ab9493cbb6d1881">llvm::LSBaseSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadsdnode/#acd5da151f55f9cd260957b3d3837888d">llvm::MaskedLoadSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#ac469e176938b3fc117e515e5110bc4f5">llvm::MaskedLoadStoreSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedstoresdnode/#a07825475998a31b3620872baefe89fb1">llvm::MaskedStoreSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#a51de544d610ce7e2c69bc1b34fbeb18e">llvm::StoreSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a8b61ddb92d8209dadefb79dd6ba3ed55">llvm::VPBaseLoadStoreSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/vploadsdnode/#a2ea875639216a92072519c2f7e0810be">llvm::VPLoadSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#ad0bea6a1db04f3b016670ab7868999ad">llvm::VPStoreSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#a9c07f472f01b592e55539abe917ea128">llvm::VPStridedLoadSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#ac587acbf76235ccaa2eecfdd254fedb8">llvm::VPStridedStoreSDNode::getOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe1ee0c3600d3982d5dcb722f8079ebd">getOneTrueElt</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="#a59192c42d4cbf804fbcc1deff8edb614">getOperationName</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgathersdnode/#aa2ad47067cddba6b8a564d814651e1f3">llvm::MaskedGatherSDNode::getPassThru</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadsdnode/#a793dd618775011dfbd3192dff8decd87">llvm::MaskedLoadSDNode::getPassThru</a>, <a href="/web-llvm/docs/api/classes/llvm/x86maskedgathersdnode/#a20f34b83ba66a4fda8d0ed5dc1ed78e9">llvm::X86MaskedGatherSDNode::getPassThru</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a28caa20d9fc8a395fd4253ccbfe7eb48">llvm::BuildVectorSDNode::getRepeatedSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#a3663b1bf571b5f9d32f43f32a5befff1">llvm::MaskedGatherScatterSDNode::getScale</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedhistogramsdnode/#a1340ac9e3f450e63a7cc11c47a1bb910">llvm::MaskedHistogramSDNode::getScale</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a59f302f024d9a267fb828052606a707d">llvm::VPGatherScatterSDNode::getScale</a>, <a href="/web-llvm/docs/api/classes/llvm/x86maskedgatherscattersdnode/#a50a01979338ef47bfba4d9bbfffd6ee5">llvm::X86MaskedGatherScatterSDNode::getScale</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a66b06a3a00ea8358c447658d398dc3f8">llvm::BuildVectorSDNode::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#a8d30c4408e2010e8852bb16eac8f3b9b">llvm::VPStridedLoadSDNode::getStride</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#ad9aa523d72f8981dd688d59ba3d97b15">llvm::VPStridedStoreSDNode::getStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afaf1cbe4bd00ba18fb62321d5cbe4646">getUnderlyingExtractedFromVec</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#ab355b8de097910b27f8a8527f9d2e512">getUsefulBitsForUse</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#aedff02bc7a3014d6a1a017a46dad11dd">llvm::AtomicSDNode::getVal</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedscattersdnode/#a36568c90b5f9be054cdf935fb1d447bf">llvm::MaskedScatterSDNode::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedstoresdnode/#a528c38d7286fc12408f931fdc395345d">llvm::MaskedStoreSDNode::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#a53864ff3d05d5cd58b6f0df00b48ae6f">llvm::StoreSDNode::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscattersdnode/#af11ddb340ac1a39e45b7d2105fa3d347">llvm::VPScatterSDNode::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#af1ab80f0db7e9a6ee7ded9bce1d2f764">llvm::VPStoreSDNode::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#a4391df42f8991101a5dce3ad295db4b1">llvm::VPStridedStoreSDNode::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86maskedscattersdnode/#a0ec27b2fe75d2efb55f453add0f9cedd">llvm::X86MaskedScatterSDNode::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#ab78e96ef913d507fc7f16bd2941e8b40">llvm::VPBaseLoadStoreSDNode::getVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a74e51fad18332454f2fbd005b9071090">llvm::VPGatherScatterSDNode::getVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vploadsdnode/#a31f1a90ae948f74aaf475c31fe946a6c">llvm::VPLoadSDNode::getVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#a853b19ab9ec4e6e9f8638103ee2d1f38">llvm::VPStoreSDNode::getVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#aaad00bf2c8f291639664e73aa7fd48e1">llvm::VPStridedLoadSDNode::getVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#aca5e63b5826019a0e1719ed4e67bd7b7">llvm::VPStridedStoreSDNode::getVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a16fdb3e37daf197199709a37540402d0">hasOnlyLiveInOpers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a22c99596004378b139e9ab48fae048dc">hasOnlyLiveOutUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a62d1f680d02d55bbd8ac9bbd62dcfe01">haveEfficientBuildVectorPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10bc55b7d7f53073cf539ae7a34a74ef">incDecVectorConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10f0c9e6db4a0388d577d2da5a0487ca">isAddSubOrSubAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abcc89aad99c6a03adb5443eb5fa9f93c">isAddSubOrSubAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aab17595c13740973595e3e453704985a">isAllConstantBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a4b1f6c2a4e7b3aed4f56643d545f305b">isBitfieldExtractOpFromAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a3ef62399dd4b7e5dbc8398704aaa79bc">llvm::BuildVectorSDNode::isConstantSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad952c5828f21002a545e9de9f64cc4aa">llvm::X86TargetLowering::isDesirableToCombineLogicOpOfSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0e3aa05aca949e6905dcb30c81c679e3">llvm::ARMTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a52376a753c8ddea8a93cc03bdecc4fcd">llvm::RISCVTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6c49319d93381e455f0138e221896629">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afe52999c6dfc815ec8496f43626191eb">isF128MovedFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af4674b301fdc98e0a729a8d4690e45f2">isFloatingPointZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7deed7d39c19fcbc3252b3b0551d3c92">isHopBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9c9e38be1df7a70627fec8fa8a2eb42b">llvm::SelectionDAG::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp/#abd648b9bbf53e1b89e8e7e2695034268">isMemOPCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a5c013753f05b14d6d638ffe65860c6f1">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a6d5b4f84c3dda985bea36681d13bc55b">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a6df0bebd8a9245a944f0682ac1231a1b">llvm::HexagonDAGToDAGISel::LoadInstrForLoadIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab83ddc0d46d65b1f035e1c8599b22b8d">lowerBitreverseShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af7efcd13ccffb0fae2b3ef52bde4b6d7">LowerBuildVectorv4x32</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#af8947d9c8165e82094241d319758e0c5">lowerCallFromStatepointLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a47c057e00771d3428bba280de009c4c8">lowerDisjointIndicesShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab8bc9452845ce93765def17a42addaed">LowerMLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab254961e69630f8f3d82f83429dd4be4">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a699145421612880595f18dd1b31bf7cb">lowerShuffleAsBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a602b901d40f2b6bc5bf489a131309eef">lowerShuffleViaVRegSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a404ad9f75afc026c7a9bfed11188048a">LowerToHorizontalOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a09b35db55ed7bd3a4027630fff72d970">LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac7baf43d7c06b852b52777d659622145">lowerVECTOR_SHUFFLEAsRotate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af6fb44d5b8fabbbd624ebe34231c5ce6">llvm::SelectionDAG::matchBinOpReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f5195509d89464589e673074691103a">matchPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ab55a53b7284f13b291dc91b270a8224e">MergeInputChains</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a488da8d90b5af11b00e77838d99cbaa2">narrowExtractedVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a3ee9c785b2ee5b9c02f9caf6c76b271f">narrowInsertExtractVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2a97ef0e99d8dd358ff9296a748e894">narrowShuffle</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#ae4ff30a063f91465787152121a63d6ce">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::NodeExtensionHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a99ae43a8879de19170e80277b5c54b88">nodesHaveSameOperandValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnodeiterator/#adde9abdd50170cdd80fa6c1c9c41098b">llvm::SDNodeIterator::operator*</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2ab3403403aae0dd2e28fd96af0e4c39">ParseBFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a50e569990d11dcbe8205d75e9bcdc08b">peekThroughBitcasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#af12579ae662d4b706778ef90b989d4fc">PerformADDCombineWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aed7db4aa3ec7143f38592865c2c0455d">PerformADDVecReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6c02410f9bb19b5b6eb61c9711ae4156">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab051a4c12430b297d1465afcb7cf8485">llvm::ARMTargetLowering::PerformBRCONDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a90b1ef73daf047e3bc666006c9e35a77">performBuildShuffleExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad6bb7ee72f79badd15b563bf112de6e5">performBuildVectorCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ada7b7dfe4d829cdafff6278e361547df">llvm::ARMTargetLowering::PerformCMOVToBFICombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a05ea7c29a0fde5a9a808c50aefd2e0fa">performCONDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4765786a8a3de00320df895defc3250">performExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a172a1f5983db0d10ae90c0d3f5beccdb">PerformExtractEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aefd957dcc1874b25b5b758324370d20d">performExtractVectorEltCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6913e341612419ecb5b860b6759b929c">llvm::AMDGPUTargetLowering::performFNegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ade8c7b6c75d72baebf1ac6d244b9fca5">PerformHWLoopCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4c4ced6d8064c639d791e53119774fcf">performINSERT_VECTOR_ELTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed80d9ad70fe74f3136dd25a2eee1c47">performLDNT1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a313d642b3a7b838825ec80b84909b9ce">performMADD_MSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5991e29bae68e989e978dc600f93b48e">performMemPairCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afe3fc9a96e843f0a30a80d4af77c1b26">PerformMinMaxCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa26e9cc2dafb4d8b4af1d6e8f252ef09">performMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a589928ae94c1e14b50e374c6a1146c60">llvm::ARMTargetLowering::PerformMVEExtCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a641b9fd791f4bf8e254fdddec43feb4c">PerformORCombineToSMULWBT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7bd1aee507cb5d38c758c9d8620fb629">PerformREMCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2d87a7cc93a308acb6482288fea2bd7c">PerformSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a434e132c04f973b024b815eaad19165f">performSetccAddFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a2dec0cffd4ecd689da9a7901b8b90124">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7b5373efa0bde041422551595378b61">performSetCCPunpkCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a391272ef81598a4a25763b2f35809615">PerformShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a24edd3104fd2ecba03dd7ca79104295d">performSHLCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4a2c60919236f6bec42a5a1cd2e0fadb">llvm::AMDGPUTargetLowering::performShlCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a60f3ecc52d65b8827909808283319dfa">performSignExtendSetCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a56ba18b7bb062d32ea351c6349a415c6">performSRACombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a5885643f7123cbe2d37a298d2551c9e1">performSRLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a13534e47159f35c97e261aac72664214">performSTNT1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a111643e86a00d697a134123e45817e14">PerformSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afe728440df980a14ddaa125c441496cc">performSubsToAndsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a267cdbd87c30830568cb74844b0e489c">performSVEAndCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d8e109ce3c796c31524f5a06dd745ac">performSVEMulAddSubCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adac55a5ab0773a88dd987c4610e2ed59">PerformUMLALCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a436aed4536d617f9ac1a208273150ac0">performVecReduceAddCombineWithUADDLP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a19d36e331487399aaac4f18bac0c7956">PerformVMOVhrCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a40eb7d32bd58dfbdde6c632446a56828">PerformVMOVrhCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab245ac37eac3c3ba9c6e8cfa310f4a46">PerformVMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a14fe6050fa67f0e7b01314d5c7586b8e">performXORCombine</a>, <a href="#a998e1d9da008364ea6a05c3a0c891b69">print</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a7be640126e3f1024b18981f1de2de20f">llvm::ResourcePriorityQueue::rawRegPressureDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af2093ca4a132848caa9d8acc509df1b2">ReconstructShuffleWithRuntimeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2c166ebb81953ce2aa531c18213e0011">reduceBuildVecToShuffleWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5c7ea2dbf94f8dfc629e9a056d7d2b51">replaceShuffleOfInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ade0519245a3e86cb20548e200f65863e">scalarizeExtEltFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1e801ca0fc0ae63d482926b72ce3b45c">scalarizeExtractedBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a977ad76f842f5addf1b023121d96465e">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#af829baf84aa61aab9b55f9196427759a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddLikeOr</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#af1389c2a1baf930223956103b615a838">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a420a3a405f7aa80d6963eb2d9a2d641b">llvm::HexagonDAGToDAGISel::SelectNewCircIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a7003b5e44eb73177e8c26b4a91247e57">llvm::AMDGPUDAGToDAGISel::SelectVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#abbdb66ef7655ebae91e2bbfab4320f23">simplifyMul24</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a31f76b4a999282e4fa0317f9404ba919">simplifyShuffleOfShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ab58a68a9178bb332e0c3f5c19fd381ec">llvm::HexagonDAGToDAGISel::StoreInstrForLoadIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6f0cac8b7a7acd364d34649335444ceb">stripModuloOnShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acedf14c0b42fdeea7ed01a8a6e051299">transformAddImmMulImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab64eb471c9d5a9db3c882d6bed499ddd">transformAddShlImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acb09f4729b96af486916310eaf0e16f3">tryBitfieldInsertOpFromOr</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreiseldagtodag-cpp-/xcoredagtodagisel/#af3ca2da669fcab80222c31e39e32287d">anonymous{XCoreISelDAGToDAG.cpp}::XCoreDAGToDAGISel::tryBRIND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#aa541e074a612b8ca4a7291a3b0746b7e">tryBuildVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af27372c25a294d5d3b8ba864de3419b7">tryLowerPartialReductionToDot</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a1671cc3411876afb45d27eac3a048d4a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectXAR</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a92aeb185d8fa73b0d6b44f62e13af912">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryShiftAmountMod</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#aa3196a845dd9ce40f3b0766ee99dea7e">llvm::RISCVDAGToDAGISel::trySignedBitfieldExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7072e7476bdcc2ff6396305b680fa83">tryToConvertShuffleOfTbl2ToTbl4</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae362c61a21181f35e570b2d94cdd2056">tryToFoldExtendSelectLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a3ded6112ba385818b252376e0dafa70a">anonymous{DAGCombiner.cpp}::DAGCombiner::visitFADDForFMACombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab2278ad575ade428648fc629fb5ecb45">widenAbs</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a45c76061665647247b00ba9b1967c407">widenCtPop</a>.</p>

</div>
</div>

### getOperationName() {#a59192c42d4cbf804fbcc1deff8edb614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string SDNode::getOperationName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the opcode of this operation for printing.</p>

<p>Declaration at line 1090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af798622367e75c5536666dbfec5d5ea3">llvm::ISD::ABDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff129f5ab4fbc8279e7aaacb45f840b1">llvm::ISD::ABDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a35c1cf0dd553444732dba8e8b9be0f6b">llvm::ISD::ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a20084f62caecb0db80ad71bdabda73c2">llvm::ISD::ADDC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad116e32876f2275acf60ffb1651c9256">llvm::ISD::ADDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a591c03cc284124ff624856ce485ebc17">llvm::ISD::ADDROFRETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa275bf149ab5df1067cfb721936ecbc">llvm::ISD::ANY_EXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8005dc9efe12e770682b4b5200dad30b">llvm::ISD::AssertAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee4f13218bdbb5c5697f7e786618ecb2">llvm::ISD::AssertSext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863">llvm::ISD::AssertZext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a55a4b1d94ca6176bcb5449196d67e798">llvm::ISD::AVGCEILS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8489c40b1b3f92b0c4fc98d06099c441">llvm::ISD::AVGCEILU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110acc5444f2e2933b551e3afbdd93a9bfc8">llvm::ISD::AVGFLOORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5096628a43b16ff34ace64193ded1c93">llvm::ISD::AVGFLOORU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8472e46f9e4db168c5610ecdfb05dbaf">llvm::ISD::BasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeea401cc0b7fa5aa6f4d3a0612140e1d">llvm::ISD::BITREVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae98378a8672947382d343d75a5df3003">llvm::ISD::BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a41bd84b853e2c03fb1af1f4ca9ebdcaf">llvm::ISD::BUILD_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a477ef80c70c7359199eace0e5d3133b1">llvm::ISD::BUILTIN_OP_END</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110acc20c926003b2af97ba08689176e7130">llvm::ISD::CARRY_FALSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110addc63b0e91a7c2b397e7908052d8caf9">llvm::ISD::CLEAR_CACHE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa366e6b1653ab1cedbeeaef9afecedd7">llvm::ISD::CONDCODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1be4c8da7c68a4c683de1a98b5cc5b9d">llvm::ISD::ConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa8cad208c3cb96b33b5d8544590325b1">llvm::ISD::ConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a041c4b27006496ee8d8bcdf72e248632">llvm::ISD::CONVERGENCECTRL_ANCHOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5a787d44a3bcbc803d314896056d9569">llvm::ISD::CONVERGENCECTRL_ENTRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a509e81081ec1935d3f4f0df758c60e0f">llvm::ISD::CONVERGENCECTRL_GLUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adef60c4df07ee437cd2714f7b18f93f2">llvm::ISD::CONVERGENCECTRL_LOOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a84c47705bcf7271413738ae8bf3871e6">llvm::ISD::CopyFromReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93bc27ca4d9e211c54b0d9efb660f080">llvm::ISD::CopyToReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add33c0ae9a63902e573fc1f92fc33f1c">llvm::ISD::CTLZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0340c8d57d1dcebc43a00412989583d3">llvm::ISD::CTLZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a991d07d163bd4d9984cf1ef36e92c214">llvm::ISD::CTPOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6da41a113af0909470baea7486b3386b">llvm::ISD::CTTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a601e66a26efd05520f7cb26aef3af340">llvm::ISD::CTTZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a062083eb3ff8c441c73d3bf42ca09bba">llvm::ISD::DELETED_NODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abad932e63381a4671b5db19a3404c82e">llvm::ISD::EH_DWARF_CFA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4edf35e2383003ff20057e5a45012a55">llvm::ISD::EH_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a122a450e069003dc86859ef47ab6e278">llvm::ISD::EH_SJLJ_LONGJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae5a57fe9fd413df909ab121ca1a813c7">llvm::ISD::EH_SJLJ_SETJMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2e0f3a93e85a46b2ebac7330c2a0c581">llvm::ISD::EH_SJLJ_SETUP_DISPATCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a926013f6dca240eca95aca66c8d3e74b">llvm::ISD::EntryToken</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae243ce466d350b1aca774a6ae9aea81c">llvm::ISD::EXPERIMENTAL_VECTOR_HISTOGRAM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad88f843bce966361c7fd2cd022e6528a">llvm::ISD::ExternalSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7e6dca8262a3de788d1bab4ba184d675">llvm::ISD::EXTRACT_ELEMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a74a787311d3ab9a17ee0acde7b6a6b14">llvm::ISD::FCANONICALIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeffc3319657e213a530ce583603f7221">llvm::ISD::FCOPYSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a130b6a6d409367c8a61dd14dfa39785c">llvm::ISD::FGETSIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2415bea72c995bb9cf9f85bbbf90bcd7">llvm::ISD::FMAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae4a4e2126c6db34e2dfd71b6bd0408ee">llvm::ISD::FP_TO_SINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98661814400e72a77f5ed4e088c06937">llvm::ISD::FP_TO_UINT_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a40b296b7db128b2d63f81a95efc5a311">llvm::ISD::FPTRUNC_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a228deacdfba1bd2d5a3663b19609f945">llvm::ISD::FRAME_TO_ARGS_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdb38c8daa8c1ab881007062d113cef3">llvm::ISD::FRAMEADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4b437632fd9b97dd36010d85eb363efe">llvm::ISD::FrameIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3b50b6d74957b19afb85ac29f66afef">llvm::ISD::FREEZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a822b0d02b601898e2d6db5b39e12cc8a">llvm::ISD::FSHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a874350de5b4f6b8f4db13940e17ed81b">llvm::ISD::FSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89f3afc3fa907ff83759c6c76d97a973">llvm::ISD::GET_ROUNDING</a>, <a href="#a7c6e64fef2ad2ba4052cd8365e97e8d2">getAsZExtVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aac36688686cd311fab09e6b55efb7f96">llvm::Intrinsic::getBaseName</a>, <a href="#a7f96a3399d86d6f136aaa121de4217a3">getMachineOpcode</a>, <a href="#a23f2f5947fc429aff1270651c6d019ea">getOpcode</a>, <a href="#a8388f666d6e735f35837ad03ed1f7a7a">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa07a74d942f49b11a81baf6dba21726e">llvm::TargetLowering::getTargetNodeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaef4ead62e1835b863820f6c818c36ac">llvm::ISD::GLOBAL_OFFSET_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a30316f8f9985260c49d7c26bc70a6cad">llvm::ISD::GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a49f1172c7014cc4fa3570792e6834e2c">llvm::ISD::GlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a76b6d3008e806ea613323ff316ef72c3">llvm::ISD::IS_FPCLASS</a>, <a href="#a1223d6e9a7dfb6e51299b894beccc679">isMachineOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0c70100db6ddc0b37b56feb242145cf4">llvm::ISD::JumpTable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9d483820471b07a73225bf33986fd110">llvm::ISD::LOCAL_RECOVER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aabb68e91001557f73ff8af63eb8d5883">llvm::ISD::MCSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a01c94937492f3ac3fb1e0be8eb0b9ef1">llvm::ISD::MERGE_VALUES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa2a7c3eccf06b41e4275bbeadb46d22e">llvm::ISD::MULHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a80d3b085af08f0dce1724207ef99b5">llvm::ISD::MULHU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa47439d20ce0879ea68ca293e018b4f5">llvm::ISD::PARITY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8df1b84ea64ad5048f27873205c8ab89">llvm::ISD::PtrAuthGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92fceabd268d62ef2c95799a102b8abf">llvm::ISD::READ_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a419e8283a58d2b1b86591fa7f18ccfd9">llvm::ISD::Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7e54881d7b0838c37485e4c79d215d07">llvm::ISD::RegisterMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2dfacb29792dd59f2cfbe529206265bc">llvm::ISD::RETURNADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a863ec6ebb75bf89cfea14da646d77e92">llvm::ISD::SADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af9eda6a77c3228cd36537469a7425133">llvm::ISD::SADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af1b946afff631cee7aa6de570bef7785">llvm::ISD::SADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac9cda41d5b1ac3a0babb77b881b506eb">llvm::ISD::SCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1f61c2422057e10403b2f6003543c300">llvm::ISD::SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a470242ff0d0c1f979101aa369a3a410e">llvm::ISD::SDIVFIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadc85d973be8149bbaa5f372aa1faf3e">llvm::ISD::SDIVFIXSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a874f66e1efe5be79552bbe7ee3121a">llvm::ISD::SDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78d0f198115bfe3331ab7cfcf7a40a97">llvm::ISD::SELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bb33e400f29724907dc27ced04e9038">llvm::ISD::SETCCCARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae258b87332b47d96bdf47e4cd915f9ea">llvm::ISD::SETFALSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a66792a566255872c951cb6b8f9cb0541">llvm::ISD::SETFALSE2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4">llvm::ISD::SETGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">llvm::ISD::SETGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a71f916390487bb109d9968c72553eaf4">llvm::ISD::SETO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a08c31033acfb9d6f0bc4a8a82cc26862">llvm::ISD::SETOEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac7bb30d4918c1ee9dd208083154e109f">llvm::ISD::SETOGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a31d1e24e08b255d6aa290d67d16ce2c9">llvm::ISD::SETOGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a1febf3bac2f3d7d98ec19f1ff5c385ea">llvm::ISD::SETOLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a20257a4d3833cf88afd42caeaed70dde">llvm::ISD::SETOLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a57c68bf7ef20bd558854a24d5b0c1e72">llvm::ISD::SETONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a8e273eab0623ea5713aa5bcbdac2b16b">llvm::ISD::SETTRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a1a575d029fd38d929229ac39e573e8fc">llvm::ISD::SETTRUE2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a0deb50cd2f3f8e4a94eef4cdf769b848">llvm::ISD::SETUEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a9dff1dcbac65852b71473818c11869b1">llvm::ISD::SETUGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac538f0b432df970cbaaf6b81d777c6a7">llvm::ISD::SETULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">llvm::ISD::SETULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a0d1546187d4d526fcbdd43183689075e">llvm::ISD::SETUNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a48a334bbe606d5e82c9cd84eaa127b50">llvm::ISD::SETUO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aeb80f9832dad739ee9c6deaa3110d98f">llvm::ISD::SHL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3893859b5caa079593b9bf91b96e05fb">llvm::ISD::SIGN_EXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af3b59179b6fcbc89463181015ace8e9b">llvm::ISD::SMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaac895215ecbb3c411c957c8beb39b70">llvm::ISD::SMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1354c6f8508d6cd697dc89a5d9a52dfd">llvm::ISD::SMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1a7f3f523e22ac3df6332e625289a7e6">llvm::ISD::SMULFIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26a7dd56cd899cec0a1f6d2443f91db4">llvm::ISD::SMULFIXSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa35d0a58fdded3d225d512a60aea0951">llvm::ISD::SMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7f864031b6fb691b1525cbea92542ef1">llvm::ISD::SPLAT_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad358f0823a936bde7edd419ab1058bd4">llvm::ISD::SPLAT_VECTOR_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110add9a41fa65a9675200d73710a82b880e">llvm::ISD::SPONENTRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a78139be59781ad05e1698eb95c58e0b1">llvm::ISD::SRA_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a124ba0f5b2887879212c74a68bc230a3">llvm::ISD::SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ed8e1dc0db59ab2a071da53ee794759">llvm::ISD::SRL_PARTS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa30a145a99902daca036d039378abca2">llvm::ISD::SSHLSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6efe16ea597cfd8eeac26516fc992ee7">llvm::ISD::SSUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a139dc5419039d94496e69dbb264251b5">llvm::ISD::SSUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a77984d86d70df1f3229da7a5119652a9">llvm::ISD::SSUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a73ec2109e5056d5cb07dad24ddd848c3">llvm::ISD::STEP_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc1699b53cce73a1a89fa9190db8f2f8">llvm::ISD::STRICT_FACOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad11fa7fd2a91d210ecbdf09d56cd9f42">llvm::ISD::STRICT_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a548c5ee9bfffd516c18b0844d8916d98">llvm::ISD::STRICT_FASIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5fc35989024437e6878d228dce85b34d">llvm::ISD::STRICT_FATAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1c24a514835d74a2a0b441825a622cef">llvm::ISD::STRICT_FATAN2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1fb1e48394636004fd75f5916f0d730f">llvm::ISD::STRICT_FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae2047d551dd66943aa285b4c7eab0766">llvm::ISD::STRICT_FCOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac9090021eb9a063125475a3d2f380af2">llvm::ISD::STRICT_FCOSH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4151e13f7626f6d790d58c0fa444f32e">llvm::ISD::STRICT_FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aba2dfbb2100ec6aee6e5b52bc713c26a">llvm::ISD::STRICT_FEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad5d3bf9997ecfea792abc058e7d39e72">llvm::ISD::STRICT_FEXP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab74cbb3933c5f5d2cc90d299836c05cc">llvm::ISD::STRICT_FFLOOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110addd63c6d866c8a8020a0cc4de467b285">llvm::ISD::STRICT_FLDEXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad795680a8d2d37bdede6696d72f41c35">llvm::ISD::STRICT_FLOG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad227f160898f13eeb05150f03de8d40b">llvm::ISD::STRICT_FLOG10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a409f18d3c3acb29ab844e9942441cc4b">llvm::ISD::STRICT_FLOG2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a26ff7f7547f66e1a4f6d5e7efe4b2f59">llvm::ISD::STRICT_FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a917038ef7ae3264e336457da0f75e95b">llvm::ISD::STRICT_FMAXIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92f7a0e4dfe860ff938d463d84270ba3">llvm::ISD::STRICT_FMAXNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3093a04e2918e155f32d435e2f974e88">llvm::ISD::STRICT_FMINIMUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a98f18e85e4e6421f5c859680602a4c1f">llvm::ISD::STRICT_FMINNUM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4b912b6be299d30d75b876e939d16fd6">llvm::ISD::STRICT_FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae463c3e40819d6e9de30d7d858867ef4">llvm::ISD::STRICT_FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a65a342694a17f4a1db771dbc36d31cc9">llvm::ISD::STRICT_FPOW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7acf26c84b90a50efe9898bc9bcd8d18">llvm::ISD::STRICT_FPOWI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aacf4034f48b7e32a9e20bfedbb5502bd">llvm::ISD::STRICT_FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af57a22f2843a1c3a79d17350945ede58">llvm::ISD::STRICT_FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0953e80e4e94f6ded9680e64c5df5cc">llvm::ISD::STRICT_FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab7d5c27c800b79a02a1492f1965af72f">llvm::ISD::STRICT_FROUNDEVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a06c721642eadaa31c37384b39fe11387">llvm::ISD::STRICT_FSIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9b07fb8cd5a1230b0f736489ddd9eebc">llvm::ISD::STRICT_FSINH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a476844aad24870fab3d132b5fe6b1f37">llvm::ISD::STRICT_FSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad6192a54cb1dfeca8173749cc735269a">llvm::ISD::STRICT_FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8ae8131038d9b94abd2880812bf5b0e">llvm::ISD::STRICT_FTAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a244401fe9aee94da72b7f0fb6b095a45">llvm::ISD::STRICT_FTANH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a883c1084962f12018ca0fe3e1222fa7d">llvm::ISD::STRICT_FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad4892124e4817d9807dcf39808016bc4">llvm::ISD::STRICT_LLRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adef1eba7d8c2a0db4a94d7327d217c90">llvm::ISD::STRICT_LLROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa7fc883444df66de315a684ecf5f5e2d">llvm::ISD::STRICT_LRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6bd04c8da718875a071107ede0f362d6">llvm::ISD::STRICT_LROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a56735332b7dc26b4e164035831fb40ab">llvm::ISD::STRICT_UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2ab6db512a611d1ef4ff8069e2bbfd0d">llvm::ISD::SUBC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac9246c101c0cc9232e37b3941194bb13">llvm::ISD::SUBE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1b7eba375863a0e80549eb1a782c5683">llvm::ISD::TargetBlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac479e53ca98903b1028ec80e12fb0af8">llvm::ISD::TargetConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a95cd714ab601765342e2ec9f6ba2cb34">llvm::ISD::TargetConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a038a7f124b4118456a27a739c03650bf">llvm::ISD::TargetConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a59b314018a929255951f01f8daaae72f">llvm::ISD::TargetExternalSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aa84894f4966964ef9fc79f9515a6c875">llvm::ISD::TargetFrameIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b8176af163ee944af127081d24f4a2">llvm::ISD::TargetGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc9ad7857b7faf49dcde3dcf434e22a6">llvm::ISD::TargetGlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a606393d2a8329de83a61d6f6447d1035">llvm::ISD::TargetIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a603c0651ff8c3a929c5e1d8b9a8f14cb">llvm::ISD::TargetJumpTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af78365e835dbc10df18c1cd5d8853fd0">llvm::ISD::TRUNCATE_SSAT_S</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a694c9a71596643f6ddd4ee767666cf43">llvm::ISD::TRUNCATE_SSAT_U</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af81ec85e716e986c5555135612f62b29">llvm::ISD::TRUNCATE_USAT_U</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ddf36330110b4abea43fe390bea9ef9">llvm::ISD::UADDO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5e433873c201ad85c30e42da1ae05977">llvm::ISD::UADDSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a482ae65625bd4d6059f7259b88ac4dbc">llvm::ISD::UCMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a15637879021fa7d5226045c0668a99a8">llvm::ISD::UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa5af2aa3cc2e31b44b69d43e13235be">llvm::ISD::UDIVFIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5c5ebc516cae422508ee0c062ef6b593">llvm::ISD::UDIVFIXSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3a257ffa49107e2db978e8a6e2688ada">llvm::ISD::UDIVREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a169032eecd015d4eeb869c457202a6c8">llvm::ISD::UINT_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af675e759c0ffff8d48ea14a60fe3517b">llvm::ISD::UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a17126302da6199930e55e841ca1b082d">llvm::ISD::UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a79c959df09509d7ff66d9b04bc40d18d">llvm::ISD::UMUL_LOHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293cdca810c396f99a2bd63b017dd943">llvm::ISD::UMULFIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaab3219acc86e3b3a199effbb69aa07a">llvm::ISD::UMULFIXSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7800622851751b8ae318b41f4096830e">llvm::ISD::UMULO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c6d8f265e9e16e5debdb9a536b55d3d">llvm::ISD::UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad1657dbc1957901a6d9cd224efbc0f28">llvm::ISD::UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5ae4b108d3f627b66f3b1e5da51f4587">llvm::ISD::USHLSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4ffc75d65231b55461c0ba4f36a3e500">llvm::ISD::USUBO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac81ebcd59d629d8680e50ffba9855255">llvm::ISD::USUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a89166b38f12c0bd3e8a61d8f1a5a8bc8">llvm::ISD::USUBSAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41972fe6f3fab862543b7b835a714f9b">llvm::utostr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a40d4f41a75df8e16bc5dbe62d62465b8">llvm::ISD::VALUETYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adb06c311948bd9fb944ab3c433138181">llvm::ISD::VECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af5b978686fa3409a40ce3abe447db653">llvm::ISD::VECTOR_DEINTERLEAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a29b106f7933f1b79281c4964bcbee807">llvm::ISD::VECTOR_FIND_LAST_ACTIVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7314e9c42c2c93e3786adfd12aee39d7">llvm::ISD::VECTOR_INTERLEAVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aad7728df1343db6f976857aaa2e945ee">llvm::ISD::VECTOR_REVERSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad55a17543ef86f6d46aebb45028a9067">llvm::ISD::VECTOR_SPLICE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a61a1595d03afe86764ad7625d358608e">llvm::ISD::WRITE_REGISTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adf7f4fc30c272a1987e075d7470df84c">llvm::ISD::ZERO_EXTEND_VECTOR_INREG</a>.</p>


<p>Referenced by <a href="#a6d72e52ee2c6a11256e6d04c8820e648">printr</a>.</p>

</div>
</div>

### getSimpleValueType() {#a7a6096cff14db41b299758115c6e261c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::SDNode::getSimpleValueType (unsigned ResNo)</td>
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

<p>Return the type of a specified result as a simple type.</p>

<p>Definition at line 1068 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a> and <a href="#ac0a534d63ac5c5b87f36acdade953fbe">getValueType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4836b23626e1d7b24f8bb84be3a55667">getHopForBuildVector</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a0aaa2e30b965ca8584badc25c324958d">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getMaskAndVL</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#ab2ca64c9af2f0f7716b503640706d362">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getNarrowType</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#afa89bad4ae6c9667571ba16df07adf70">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getOrCreateExtendedOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10bc55b7d7f53073cf539ae7a34a74ef">incDecVectorConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10f0c9e6db4a0388d577d2da5a0487ca">isAddSubOrSubAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7deed7d39c19fcbc3252b3b0551d3c92">isHopBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab83ddc0d46d65b1f035e1c8599b22b8d">lowerBitreverseShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a47c057e00771d3428bba280de009c4c8">lowerDisjointIndicesShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a602b901d40f2b6bc5bf489a131309eef">lowerShuffleViaVRegSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a968c16471029370282f7c406b333ea37">lowerToAddSubOrFMAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a404ad9f75afc026c7a9bfed11188048a">LowerToHorizontalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a7be640126e3f1024b18981f1de2de20f">llvm::ResourcePriorityQueue::rawRegPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a8414362458bfc0acef16b0440665faa1">llvm::RISCVDAGToDAGISel::selectScalarFPAsInt</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>.</p>

</div>
</div>

### getValueSizeInBits() {#a75de6a9cc37e7d0a70e488ad3c4159c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::SDNode::getValueSizeInBits (unsigned ResNo)</td>
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

<p>Returns MVT::getSizeInBits(getValueType(ResNo)).</p>


<p>If the value type is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>Definition at line 1077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a> and <a href="#ac0a534d63ac5c5b87f36acdade953fbe">getValueType</a>.</p>

</div>
</div>

### getValueType() {#ac0a534d63ac5c5b87f36acdade953fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::SDNode::getValueType (unsigned ResNo)</td>
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

<p>Return the type of a specified result.</p>

<p>Definition at line 1062 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5425376fb8bb34c4f59a84a3ee70c790">AddCombineTo64bitMLAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a04cb51bd51ce0d3d114071ed4c38183b">CanCombineFCOPYSIGN_EXTEND_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a2fc82b70727afff2c18b36c0a6c280cd">combineADDToMAT_PCREL_ADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c3d86d724323d88d2fdf99d29d3de72">combineBasicSADPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a3fe8c06097a055b8ab0114f2678ed2d6">combineCarryDiamond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af2bbdc92f4c64587511d192d903ca743">combineMinMaxReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af72da135a7e8a925ffa9fbbb4ecf0b1f">combinePredicateReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab160c4766dfd9c2f981e092e730fd1b0">combineShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a69d159ccc8c9f4f70ed369d35c5c420b">combineShuffleOfBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade03879f56390aad1613d54401f911a5">combineShuffleOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a7847dc95e3ec6e1cdaa66ac48a0f7985">combineShuffleOfSplatVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6da34b4a62e36f7b3b51720f19d3e753">combineShuffleToAnyExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab039512652c2e46b69e54b91ba5d0dc3">combineToExtendCMOV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af01458f5f68de9153c5392eebedfa0f1">combineTruncationShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a77515f2a50929db00636724e30ef3190">combineUADDO_CARRYDiamond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54b7a43507d8f339f806b8d1c9f12f29">combineVectorCompareAndMaskUnaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac5281f53eae7762532968413f7201798">CombineVMOVDRRCandidateWithVecOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8389740010ccf99686a066f0bdc4dbdc">combineVPDPBUSDPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f4cf2e3dcecef6763caca7fd8949d76">combineX86SubCmpForFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af06754acf6dbda0709a6cda0b11cdab5">Expand64BitShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a66608723a39fea9af315107db02b6ef5">anonymous{DAGCombiner.cpp}::DAGCombiner::ExtendSetCCUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b307d4ad3f5e1ae0c9888b5d0cc6b54">foldBinOpIntoSelectIfProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70a3356be1e0bc8db5a2e2e5d8e6d7b1">foldMaskedMergeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a781a75dfc661452760864c019bafd96e">foldShuffleOfConcatUndefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a614caf1728d9aec23d5fe873c92208c1">formSplatFromShuffles</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a85e6f92ca194a48ccbd299086709411b">llvm::SelectionDAG::getCommutedVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a1713768600a9f5a62eb74a616aa73428">llvm::BuildVectorSDNode::getConstantRawBits</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a33c0ea764b5da70fb2f5263babf1e5ae">llvm::HexagonTargetLowering::GetDynamicTLSAddr</a>, <a href="#ae1fa8ded9bce6f8321a69e99e41a473c">getGluedNode</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a9b491c57b85b9102e646df663d7f55e3">llvm::ShuffleVectorSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a449efebfbf16040c8d5c658f4c891f3f">llvm::ShuffleVectorSDNode::getMaskElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a61378df65052d091f64f8ac2657758b7">getMemVTFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe1ee0c3600d3982d5dcb722f8079ebd">getOneTrueElt</a>, <a href="#a7a6096cff14db41b299758115c6e261c">getSimpleValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a93d85169d871f169e06ab00673048741">llvm::PPC::getSplatIdxForPPCMnemonics</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a78735185fd19e227f3c2f0bcfcd46ae8">llvm::ShuffleVectorSDNode::getSplatIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>, <a href="#a75de6a9cc37e7d0a70e488ad3c4159c7">getValueSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10bc55b7d7f53073cf539ae7a34a74ef">incDecVectorConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchiseldagtodag-cpp/#ad42177120fd9d2f2693b604658449116">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a59074e4ad89f513d48ef59b365b89c0b">isAddCarryChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aab17595c13740973595e3e453704985a">isAllConstantBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a4b1f6c2a4e7b3aed4f56643d545f305b">isBitfieldExtractOpFromAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aaf4b732e582e80caaceee1ed402180b8">isBitfieldExtractOpFromShr</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a3ef62399dd4b7e5dbc8398704aaa79bc">llvm::BuildVectorSDNode::isConstantSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ceb04284d179d66b26dede64956d9c7">llvm::isConstOrConstSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad952c5828f21002a545e9de9f64cc4aa">llvm::X86TargetLowering::isDesirableToCombineLogicOpOfSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6c49319d93381e455f0138e221896629">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adfaf056ced72346fabb19629cb51ead0">isHalvingTruncateAndConcatOfLegalIntScalableType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3e9938aeee2aaef4ca5933920bb8c2af">isLegalBitRotate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a98c172c9b66de1264ee2123e4f1a3df2">llvm::SelectionDAGISel::IsLegalToFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#af4ddbb361d77fd42e32b5d6df0075a6e">llvm::ShuffleVectorSDNode::isSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a81538cbfd94655fdcddb7053535b618d">isSubBorrowChain</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a95c8b57eb11e8d25decddd3c86c9703c">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isSupportedRoot</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a9440e31a32ea6624c0b77e7e45223be9">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::LegalizeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abf668b25006ed7fd3e0b86681aa0e5e1">lookThroughSignExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af8cc1f957026a793e58fec505e47a7c5">llvm::X86TargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a18f228d6b8d87ccfbe0db322ed26a2c6">lowerDSPIntr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a1e66c7cdb5788173f5681ee37389dee1">lowerMSACopyIntr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7092b8371f80f3acf826e7bfc1e00d92">LowerToTLSExecModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa38de8a6bc68bdfd3aea0e8900c7745">LowerToTLSLocalDynamicModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac7baf43d7c06b852b52777d659622145">lowerVECTOR_SHUFFLEAsRotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a488da8d90b5af11b00e77838d99cbaa2">narrowExtractedVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a3ee9c785b2ee5b9c02f9caf6c76b271f">narrowInsertExtractVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2a97ef0e99d8dd358ff9296a748e894">narrowShuffle</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#ae4ff30a063f91465787152121a63d6ce">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::NodeExtensionHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a635ad8d6dba2689cc34e3bb3fb12c2a6">performAddUADDVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4764dd7a5c84db5880e9d37d5c1ce949">performANDORCSELCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a05ea7c29a0fde5a9a808c50aefd2e0fa">performCONDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a001a6e7473d9f11917ec04f38e3cb498">performINTRINSIC_WO_CHAINCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a313d642b3a7b838825ec80b84909b9ce">performMADD_MSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abf0bc161f51dbc01add0270eb00b2f77">PerformMinMaxFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a434e132c04f973b024b815eaad19165f">performSetccAddFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a2dec0cffd4ecd689da9a7901b8b90124">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7b5373efa0bde041422551595378b61">performSetCCPunpkCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a60f3ecc52d65b8827909808283319dfa">performSignExtendSetCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afe728440df980a14ddaa125c441496cc">performSubsToAndsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a267cdbd87c30830568cb74844b0e489c">performSVEAndCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a436aed4536d617f9ac1a208273150ac0">performVecReduceAddCombineWithUADDLP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90e158dcd9e3da205b3703145ed4cfcb">performVP_STORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>, <a href="#ad4e2295ddf513d5a4898fa7b3f1c2121">print_types</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2c166ebb81953ce2aa531c18213e0011">reduceBuildVecToShuffleWithZero</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad09a0f9913dd2fad9b84458bdb263aaa">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5f4f153e2f8d9dd1c45d089ea3c7499f">resolveBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ade0519245a3e86cb20548e200f65863e">scalarizeExtEltFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1e801ca0fc0ae63d482926b72ce3b45c">scalarizeExtractedBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a312de8232fec3e0e128f4a34b7ddc55d">llvm::PPCTargetLowering::SelectAddressRegImm</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#af1389c2a1baf930223956103b615a838">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a9208ba235fd513181d17277332f9bde2">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectLoadLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a87024e3cd8e787fed3e17063882847aa">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostLoadLane</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a72ba34ed2a0e75181bfecf7d463156f8">llvm::X86InstrInfo::shouldScheduleLoadsNear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#aa541e074a612b8ca4a7291a3b0746b7e">tryBuildVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#afa371a03066103bb85f89636e86686d7">llvm::RISCVDAGToDAGISel::tryIndexedLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a92aeb185d8fa73b0d6b44f62e13af912">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryShiftAmountMod</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aedd894c113704ea926d5339d9f1aa2e7">trySimplifySrlAddToRshrnb</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7072e7476bdcc2ff6396305b680fa83">tryToConvertShuffleOfTbl2ToTbl4</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa267be29b6ab02eda3ff34dd9c608b0c">tryToFoldExtOfMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07229844dfee2ef29637eec9717bede7">tryToWidenSetCCOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab2278ad575ade428648fc629fb5ecb45">widenAbs</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a45c76061665647247b00ba9b1967c407">widenCtPop</a>.</p>

</div>
</div>

### getVTList() {#a8353d97eb11578ab1ecb797200ca85c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDVTList llvm::SDNode::getVTList ()</td>
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



<p>Definition at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a064060d88e13e0fe28415d9bb1683b4f">combineAddOrSubToADCOrSBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a3fe8c06097a055b8ab0114f2678ed2d6">combineCarryDiamond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a16e4d757dd734397239791b2cbb221c7">combineCarryThroughADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0a830cdb7a7691a1d390be839ff5859f">combineSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a77515f2a50929db00636724e30ef3190">combineUADDO_CARRYDiamond</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a56ba18b7bb062d32ea351c6349a415c6">performSRACombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afe728440df980a14ddaa125c441496cc">performSubsToAndsCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#abbdb66ef7655ebae91e2bbfab4320f23">simplifyMul24</a>.</p>

</div>
</div>

### hasAnyUseOfValue() {#ab6ea142f5ae930a660fbb4105ef42a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDNode::hasAnyUseOfValue (unsigned Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there are any use of the indicated value.</p>


<p>hasAnyUseOfValue - Return true if there are any use of the indicated value.</p>


<p>This method ignores uses of other values defined by this operation.</p>


<p>Declaration at line 884 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12501 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7f06dbaee5fa2b239de548d0a775b25b">getNumValues</a> and <a href="#a42e9a628b333dddfcc9d5fb17824dc17">uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5425376fb8bb34c4f59a84a3ee70c790">AddCombineTo64bitMLAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0a830cdb7a7691a1d390be839ff5859f">combineSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a05ea7c29a0fde5a9a808c50aefd2e0fa">performCONDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad09a0f9913dd2fad9b84458bdb263aaa">llvm::SelectionDAG::ReplaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>.</p>

</div>
</div>

### hasNUsesOfValue() {#ad82ad170343d0b4fe88a5551ec43659d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDNode::hasNUsesOfValue (unsigned NUses, unsigned Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there are exactly NUSES uses of the indicated value.</p>


<p>hasNUsesOfValue - Return true if there are exactly NUSES uses of the indicated value.</p>


<p>This method ignores uses of other values defined by this operation.</p>


<p>Declaration at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7f06dbaee5fa2b239de548d0a775b25b">getNumValues</a> and <a href="#a42e9a628b333dddfcc9d5fb17824dc17">uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac8e70a2e70e45733c882bb7b103a9c88">getCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ababdb755e930b1b856496616c735a117">isFMAddSubOrFMSubAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### hasOneUse() {#a295d0b84f4e63438c0edb0021c41d47a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::hasOneUse ()</td>
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

<p>Return true if there is exactly one use of this node.</p>

<p>Definition at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a88027543aef5a9bc0d82bc5e5e3506c3">llvm::hasSingleElement</a> and <a href="#a42e9a628b333dddfcc9d5fb17824dc17">uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a064060d88e13e0fe28415d9bb1683b4f">combineAddOrSubToADCOrSBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad1b9f6a1979dddff5b170976bfd53c52">CombineANDShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a16e4d757dd734397239791b2cbb221c7">combineCarryThroughADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a42665647b96c498ee34474d061608fb7">combineSelectAndUseCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiisellowering-cpp/#a7b7fd03bd2909ea37140e7a7c0467b7b">combineSelectAndUseCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adeaf659e662150ed5f19eb4c9d7cbbb0">combineSetCCMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade03879f56390aad1613d54401f911a5">combineShuffleOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0a830cdb7a7691a1d390be839ff5859f">combineSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a588e5dcf7ccf9ec2b6922f24c012a08a">emitConjunctionRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af91c2a3b14c738c31113158a698e0324">foldMaskedMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70a3356be1e0bc8db5a2e2e5d8e6d7b1">foldMaskedMergeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8b9766fd6e7fa9f1d99f19fb8bcfe993">getBT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abcc89aad99c6a03adb5443eb5fa9f93c">isAddSubOrSubAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7b88feeb3710cc54997cad1540860f08">isAddSubSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a02ba38ae733ae47a36eb03d9661fff6d">isAddSubSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a792e04e2a436db3281f42173654da414">isAddSubZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad17c5939bd075abb87efb7268115f49b">isAddSubZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4236a4880dff9f75230ffb9d581defaa">IsCMPZCSINC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aecbd41e7754d9ca4d664dfa0d9df8510">llvm::AArch64TargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4332a6c6b7e415a85911602414542140">llvm::AMDGPUTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0e3aa05aca949e6905dcb30c81c679e3">llvm::ARMTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a52376a753c8ddea8a93cc03bdecc4fcd">llvm::RISCVTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#acadf633df07f9e11330ae99edf3e1bb7">llvm::TargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afe52999c6dfc815ec8496f43626191eb">isF128MovedFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a76077783204d9df857265567d4a10c29">isI128MovedFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7a61cf78eb38e383357df8c175aebc3b">isLoadOrMultipleLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c4d94b8b92e288f152e1f1d9e2598d">lower1BitShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae2e5854cbbb56cb58c6b641d105998db">matchBSwapHWordOrAndAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a488da8d90b5af11b00e77838d99cbaa2">narrowExtractedVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#af12579ae662d4b706778ef90b989d4fc">PerformADDCombineWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5fd0659783f0d5916ce7af83b808d90a">PerformADDCombineWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4764dd7a5c84db5880e9d37d5c1ce949">performANDORCSELCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a05ea7c29a0fde5a9a808c50aefd2e0fa">performCONDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6bf8361890dacf0c32272b056acff135">performNegCSelCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiisellowering-cpp/#acaa7667e3eb47c2528ee28df06d25ee1">PerformSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a111643e86a00d697a134123e45817e14">PerformSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#aeaa88de6884da5fde45eafb9b11fcb3e">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::selectFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acedf14c0b42fdeea7ed01a8a6e051299">transformAddImmMulImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab64eb471c9d5a9db3c882d6bed499ddd">transformAddShlImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abe50b03585622dd5b4b3c76d44ea7a8e">TryDistrubutionADDVecReduce</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a3ded6112ba385818b252376e0dafa70a">anonymous{DAGCombiner.cpp}::DAGCombiner::visitFADDForFMACombine</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a10977176a9063297e4ed5e4c23422b29">anonymous{DAGCombiner.cpp}::DAGCombiner::visitFSUBForFMACombine</a>.</p>

</div>
</div>

### hasPoisonGeneratingFlags() {#ad961d1de3aa88629112015651709de3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::hasPoisonGeneratingFlags ()</td>
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



<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a19128eb1e6729dd3cf2afce783620adaa7d54b653cca4a4672202c8055e75e8e4">llvm::SDNodeFlags::PoisonGeneratingFlags</a>.</p>

</div>
</div>

### hasPredecessor() {#ab250276b651715d29b3ed20467d5f0a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDNode::hasPredecessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if N is a predecessor of this node.</p>


<p>N is either an operand of this node, or can be reached by recursively traversing up the operands. NOTE: This is an expensive method. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> it carefully.</p>


<p>Declaration at line 903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12595 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="#a7c6beebf86835d6582b0550cd7731ee9">hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a>.</p>

</div>
</div>

### intersectFlagsWith() {#a6740680254c86d6fb43a3f8d88af9572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SDNode::intersectFlagsWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear any flags in this node that aren't also set in Flags.</p>


<p>If Flags is not in a defined state then this has no effect.</p>


<p>Declaration at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12602 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>

</div>
</div>

### isDivergent() {#a28417243f8d25f74e598d78d7802c366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::isDivergent ()</td>
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



<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#afb910e6a374ba558af8571d2a0a095ed">SDNodeBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9330a86a613cf892ee5c7f515713f200">llvm::SITargetLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a45cd7009ba8bafa53767589f88b53994">llvm::SITargetLowering::isReassocProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a00eceab7a08d0acc74a729ebd9660475">llvm::SITargetLowering::PostISelFolding</a>, <a href="#a998e1d9da008364ea6a05c3a0c891b69">print</a>, <a href="#ac351340ed4428a1b6d69d303bcba86d9">print_details</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac630ccda26fea2f45afa3fb89bc1a8f4">llvm::SelectionDAG::ReplaceAllUsesOfValueWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5da44486df08f753ea147fe04e86026f">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad09a0f9913dd2fad9b84458bdb263aaa">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8518c120f782df9e974c8b1b589feb40">llvm::SelectionDAG::ReplaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8272c4da36b8d295addf73f56c548155">llvm::SITargetLowering::shouldExpandVectorDynExt</a>.</p>

</div>
</div>

### isMachineOpcode() {#a1223d6e9a7dfb6e51299b894beccc679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::isMachineOpcode ()</td>
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

<p>Test if this node has a post-isel opcode, directly corresponding to a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> opcode.</p>

<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a883ff468e6ea584087e66416d02a5e48">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::AddPseudoTwoAddrDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab1ec5f3b915078525275298dc021f58c">llvm::ARMBaseInstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09ed4b8df3900d37518583f29bbb0144">llvm::SIInstrInfo::areLoadsFromSameBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a2d2ea6e61626afee21fc7752c9affa05">llvm::X86InstrInfo::areLoadsFromSameBasePtr</a>, <a href="#a7f96a3399d86d6f136aaa121de4217a3">getMachineOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae2caf47c7fb0d8972d9c1f261beaf289">getMaskSetter</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a21153a0c2c9279d36a253cfb602bef43">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa65c4a19ddc8ce7ddec084e5a1a4a62a">llvm::TargetInstrInfo::getOperandLatency</a>, <a href="#a59192c42d4cbf804fbcc1deff8edb614">getOperationName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#ab355b8de097910b27f8a8527f9d2e512">getUsefulBitsForUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a5c013753f05b14d6d638ffe65860c6f1">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#afba9f58251019a23a1d7f60d6c958071">llvm::ResourcePriorityQueue::isResourceAvailable</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a7be640126e3f1024b18981f1de2de20f">llvm::ResourcePriorityQueue::rawRegPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a810f1b98c4887804780355393149e783">llvm::ResourcePriorityQueue::regPressureDelta</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a1b480aa4515358bac44d9281c7f74471">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::RegPressureDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae30e9e0cfb98797266d9fc1226cf467d">llvm::ResourcePriorityQueue::reserveResources</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a8cbc84894a200075ee84886cd3fa6549">usesAllOnesMask</a>.</p>

</div>
</div>

### isMemIntrinsic() {#a84ea0c52aaedee23f6e0ef24a0373201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::isMemIntrinsic ()</td>
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

<p>Test if this node is a memory intrinsic (with valid pointer information).</p>

<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#afb910e6a374ba558af8571d2a0a095ed">SDNodeBits</a>.</p>

</div>
</div>

### isOnlyUserOf() {#a2998329e16665f7101fac0ae9faee5c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDNode::isOnlyUserOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this node is the only use of N.</p>


<p>isOnlyUserOf - Return true if this node is the only use of N.</p>


<p>Declaration at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac1639f9e80414a665a5826e6e4ca6095">canonicalizeShuffleMaskWithHorizOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a7e5a9b5c5f87a0f7d2227881e84be8a2">findNonImmUse</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#acb7284db7f63030c26cd605c4afd7fa6">llvm::ARMTargetLowering::isVectorLoadExtDesirable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>.</p>

</div>
</div>

### isOperandOf() {#a94aa946198a3279b30a6d3a943dede42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDNode::isOperandOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this node is an operand of N.</p>

<p>Declaration at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12542 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a3fe8c06097a055b8ab0114f2678ed2d6">combineCarryDiamond</a>.</p>

</div>
</div>

### isPredecessorOf() {#aaf99b3ee1d9577ac86d3bf072c7bc789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::isPredecessorOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Return true if this node is a predecessor of N.</p>


<p>NOTE: Implemented on top of hasPredecessor and every bit as expensive. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> carefully.</p>


<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5425376fb8bb34c4f59a84a3ee70c790">AddCombineTo64bitMLAL</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#afdcf01d7d3527e56cd6cc217975aac68">llvm::AMDGPUDAGToDAGISel::matchLoadD16FromBuildVector</a>.</p>

</div>
</div>

### isStrictFPOpcode() {#a07f22269e73f15d1d993421c5e4a2f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::isStrictFPOpcode ()</td>
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

<p>Test if this node is a strict floating point pseudo-op.</p>

<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4106aa1194d1a3ddfe03bbbc600913cf">combineFP_ROUND</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aefd957dcc1874b25b5b758324370d20d">performExtractVectorEltCombine</a>.</p>

</div>
</div>

### isTargetOpcode() {#ae2432058d52e384abd351a75adf27aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::isTargetOpcode ()</td>
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

<p>Test if this node has a target-specific opcode (in the &lt;target&gt;<a href="/web-llvm/docs/api/namespaces/llvm/isd">ISD</a> namespace).</p>

<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a477ef80c70c7359199eace0e5d3133b1">llvm::ISD::BUILTIN_OP_END</a>.</p>

</div>
</div>

### isUndef() {#ad29680b0f3d0427cab5a32e727f9f11a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::isUndef ()</td>
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

<p>Return true if the type of the node type undefined.</p>

<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7c6d8f265e9e16e5debdb9a536b55d3d">llvm::ISD::UNDEF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abaf220e37dfcbfd9339df9b9ac2dff42">combineBinOpToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3e8b7d7b4d4abd86ab48a0f51f8a6c80">ExpandHorizontalBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a28caa20d9fc8a395fd4253ccbfe7eb48">llvm::BuildVectorSDNode::getRepeatedSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a66b06a3a00ea8358c447658d398dc3f8">llvm::BuildVectorSDNode::getSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a404ad9f75afc026c7a9bfed11188048a">LowerToHorizontalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a087a79677b0a36af63d2122ea6e1ee29">llvm::VETargetLowering::lowerVVP_GATHER_SCATTER</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a2f8e0ad32ef05ffb3966db924f5ae9ee">llvm::VETargetLowering::lowerVVP_LOAD_STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>.</p>

</div>
</div>

### isVPOpcode() {#ad85183a1e40f2a1dc0840c22484b8eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::isVPOpcode ()</td>
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

<p>Test if this node is a vector predication operation.</p>

<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="#a23f2f5947fc429aff1270651c6d019ea">getOpcode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aed1c239da7e4526d3140443b3bf6f8d7">llvm::ISD::isVPOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aa5e728389b60e4210dc8e60dc114ee56">llvm::VPMatchContext::match</a>.</p>

</div>
</div>

### op\_begin() {#aee6bd1fd282469b3476efce4b707f09a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::SDNode::op_begin ()</td>
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



<p>Definition at line 999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="#aeffcf6f6a22d7591beed2f7a9d9fee20">DropOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8c5470848197ac902e80545f0d08aa1c">ExtendToType</a>, <a href="/web-llvm/docs/api/classes/llvm/sduse/#acd878cccb723ba2a3287560acaebc4eb">llvm::SDUse::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a68ec2b2ff4e5854ccb107f08d0de92b0">moveBelowOrigChain</a>, <a href="#a2bb043b87aa8cdef6d1e9e14329aec6a">op_values</a>, <a href="#a0cdd5176dc41b96586448ecc59770250">ops</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4c4ced6d8064c639d791e53119774fcf">performINSERT_VECTOR_ELTCombine</a> and <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#aa0b3de3815c7ba67bd6b19ef08ac9f1c">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::selectInlineAsm</a>.</p>

</div>
</div>

### op\_end() {#ae499cc99d4fe44d343ca9ac6a2ae8845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::SDNode::op_end ()</td>
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



<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="#aeffcf6f6a22d7591beed2f7a9d9fee20">DropOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8c5470848197ac902e80545f0d08aa1c">ExtendToType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a68ec2b2ff4e5854ccb107f08d0de92b0">moveBelowOrigChain</a>, <a href="#a2bb043b87aa8cdef6d1e9e14329aec6a">op_values</a>, <a href="#a0cdd5176dc41b96586448ecc59770250">ops</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4c4ced6d8064c639d791e53119774fcf">performINSERT_VECTOR_ELTCombine</a> and <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#aa0b3de3815c7ba67bd6b19ef08ac9f1c">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::selectInlineAsm</a>.</p>

</div>
</div>

### op\_values() {#a2bb043b87aa8cdef6d1e9e14329aec6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; value_op_iterator &gt; llvm::SDNode::op_values ()</td>
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



<p>Definition at line 1015 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#aee6bd1fd282469b3476efce4b707f09a">op_begin</a> and <a href="#ae499cc99d4fe44d343ca9ac6a2ae8845">op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f4cf2e3dcecef6763caca7fd8949d76">combineX86SubCmpForFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a7e5a9b5c5f87a0f7d2227881e84be8a2">findNonImmUse</a>, <a href="#a7c6beebf86835d6582b0550cd7731ee9">hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#ab7448e12bb2449435bddec7d9e00564a">llvm::BuildVectorSDNode::isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae7ed3fbc13ac6319f5437a7ebe61cd0b">llvm::SelectionDAG::isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a404ad9f75afc026c7a9bfed11188048a">LowerToHorizontalOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>.</p>

</div>
</div>

### ops() {#a0cdd5176dc41b96586448ecc59770250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SDUse &gt; llvm::SDNode::ops ()</td>
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



<p>Definition at line 1001 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#aee6bd1fd282469b3476efce4b707f09a">op_begin</a> and <a href="#ae499cc99d4fe44d343ca9ac6a2ae8845">op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aa10cee1a6cc1fbb381e3dab0c92c4cb2">canFoldStoreIntoLibCallOutputPointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aecabf0b51b7f3a579c05fc08e06c265a">extractSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3d2572a2d7cf0d8584f28c2c1c2e14c8">extractSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1c34ea579237aedce7149724afc490ab">insert1BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9c9e38be1df7a70627fec8fa8a2eb42b">llvm::SelectionDAG::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2e18d86a676154c8ddeb0a9dbdce719d">mergeEltWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a90b1ef73daf047e3bc666006c9e35a77">performBuildShuffleExtendCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6913e341612419ecb5b860b6759b929c">llvm::AMDGPUTargetLowering::performFNegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ade0519245a3e86cb20548e200f65863e">scalarizeExtEltFP</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6edfdb2ee22d183ae51d57796e56f8e3">widenSubVector</a>.</p>

</div>
</div>

### print() {#a998e1d9da008364ea6a05c3a0c891b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SDNode::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a999ec9d4610ecb7c24d399bbc447ed70">getDebugLoc</a>, <a href="#a7f311fcc2415eee3cb3694013b985304">getNumOperands</a>, <a href="#a8388f666d6e735f35837ad03ed1f7a7a">getOperand</a>, <a href="#a28417243f8d25f74e598d78d7802c366">isDivergent</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#a62a3cfb3d3c455d1999831d2fcfce9a8">printOperand</a>, <a href="#a6d72e52ee2c6a11256e6d04c8820e648">printr</a>, <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#a24f7c51780d2512ebed1c6e980dbeaa2">VerboseDAGDumping</a>.</p>


<p>Referenced by <a href="#addc45c27e50b974d99ba074ebfc4930c">dump</a>.</p>

</div>
</div>

### print\_details() {#ac351340ed4428a1b6d69d303bcba86d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SDNode::print_details (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1093 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a5023bb0687db0b35d3b2d19327217ce5">getFlags</a>, <a href="#a478a16ce230e9f3901fdc6847bc063b5">getHasDebugValue</a>, <a href="#a2ba18a788637b22646b09602bd5a50c8">getIndexedModeName</a>, <a href="#a2c7563253850e555f36f44d91157e5bb">getIROrder</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#a1bdddc5f08b7b8b77e2518296dd4d84f">getNodeId</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a67a9597d213ec55980bfeae907088d12">hasNoInfs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a3bd26297d4422f25aaeacd40ffbbc478">hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ac7f3587a2e9b666879ee5067a9593253">hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a28417243f8d25f74e598d78d7802c366">isDivergent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#ace21909c26dd090286cc93b20b5a3cc4">printMemOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a5d6e37f3d036496321824378223ad718a8009351707fa969013ab5d9126bab03e">Scaled</a>, <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#a24f7c51780d2512ebed1c6e980dbeaa2">VerboseDAGDumping</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>


<p>Referenced by <a href="#a6d72e52ee2c6a11256e6d04c8820e648">printr</a>.</p>

</div>
</div>

### print\_types() {#ad4e2295ddf513d5a4898fa7b3f1c2121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SDNode::print_types (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a923e1e1096d253c80d8a241754cb878f">llvm::EVT::getEVTString</a>, <a href="#a7f06dbaee5fa2b239de548d0a775b25b">getNumValues</a>, <a href="#ac0a534d63ac5c5b87f36acdade953fbe">getValueType</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>


<p>Referenced by <a href="#a6d72e52ee2c6a11256e6d04c8820e648">printr</a>.</p>

</div>
</div>

### printr() {#a6d72e52ee2c6a11256e6d04c8820e648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SDNode::printr (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 1064 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a59192c42d4cbf804fbcc1deff8edb614">getOperationName</a>, <a href="#ac351340ed4428a1b6d69d303bcba86d9">print_details</a>, <a href="#ad4e2295ddf513d5a4898fa7b3f1c2121">print_types</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#a001f788db44eec30b041b21b571523d7">PrintNodeId</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>


<p>Referenced by <a href="#a998e1d9da008364ea6a05c3a0c891b69">print</a>.</p>

</div>
</div>

### printrFull() {#a5db0a95c12b4b5ee310ea283172e3e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SDNode::printrFull (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print a <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> node and all children down to the leaves.</p>


<p>The given <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> allows target-specific nodes to be printed in human-readable form. Unlike printr, this will print the whole DAG, including children that appear multiple times.</p>


<p>Declaration at line 1103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a9d07a0db71661297bf458ca459bfe448">printrWithDepth</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>

</div>
</div>

### printrWithDepth() {#a9d07a0db71661297bf458ca459bfe448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SDNode::printrWithDepth (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G=nullptr, unsigned depth=100)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print a <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> node and children up to depth "depth." The given <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> allows target-specific nodes to be printed in human-readable form.</p>


<p>Unlike printr, this will print children that appear multiple times wherever they are used.</p>


<p>Declaration at line 1111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#adfc37ceb937f230dbfdbda000e383090">printrWithDepthHelper</a> and <a href="#a6398ba1604e154e21413ce15dd4a180e">SelectionDAG</a>.</p>


<p>Referenced by <a href="#a9f4da658044d115b980e5c832fa25cdb">dumprWithDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#a23c69653370af251e721680e01303967">llvm::MipsSETargetLowering::PerformDAGCombine</a> and <a href="#a5db0a95c12b4b5ee310ea283172e3e49">printrFull</a>.</p>

</div>
</div>

### Profile() {#a4476e9669bf25c55cf7c5181dad8cd63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SDNode::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gather unique data for the node.</p>


<p>Profile - Gather unique data for the node.</p>


<p>Declaration at line 1145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12453 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a240a52f42f36383bda1850cbaee8755e">AddNodeIDNode</a>.</p>

</div>
</div>

### setCFIType() {#ac91f61940049e03836c7ba45f488c51f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDNode::setCFIType (uint32_t Type)</td>
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



<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### setCombinerWorklistIndex() {#a8f3e50d50ee6c3dc75635b6219ca6c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDNode::setCombinerWorklistIndex (int Index)</td>
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

<p>Set worklist index for DAGCombiner.</p>

<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### setDebugLoc() {#a01dfe4f342c26108b177ff260ed81116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDNode::setDebugLoc (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> dl)</td>
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

<p>Set source location info.</p>


<p>Try to avoid this, putting it in the constructor is preferable.</p>


<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### setFlags() {#add49be7f78dace3e4363786d14d30899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDNode::setFlags (<a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> NewFlags)</td>
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



<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2f6ed7bfd084f49c2369eec4c74495a3">performFADDCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a3baa54d2ae1c98e5d8ae5af8acdf82c8">PerformFADDVCMLACombine</a>.</p>

</div>
</div>

### setHasDebugValue() {#a40063dd06404e7d8df5bc40a956ae433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDNode::setHasDebugValue (bool b)</td>
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



<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#afb910e6a374ba558af8571d2a0a095ed">SDNodeBits</a>.</p>

</div>
</div>

### setIROrder() {#a079553cc2e662f6004719e3b52595a7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDNode::setIROrder (unsigned Order)</td>
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

<p>Set the node ordering.</p>

<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### setNodeId() {#a5689e9ae35c6ceb3b9377299c98e0e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SDNode::setNodeId (int Id)</td>
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

<p>Set unique node id.</p>

<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c14b3df966377178b3881085703182c">llvm::SelectionDAG::mutateStrictFPToFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledaglinearize/#ac5dfad52f2ec0adbc920cf686c615e00">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::Schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### use\_begin() {#a9450817c42562fe06198b67be72a24ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_iterator llvm::SDNode::use_begin ()</td>
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

<p>Provide iteration support to walk over all uses of an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>.</p>

<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac630ccda26fea2f45afa3fb89bc1a8f4">llvm::SelectionDAG::ReplaceAllUsesOfValueWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5da44486df08f753ea147fe04e86026f">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad09a0f9913dd2fad9b84458bdb263aaa">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8518c120f782df9e974c8b1b589feb40">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="#a6163a1abbdce6098d64026e3393ecca7">use_size</a>, <a href="#a42e9a628b333dddfcc9d5fb17824dc17">uses</a> and <a href="#a22d9b41775e14d6cf4cd11b33e2f05c8">uses</a>.</p>

</div>
</div>

### use\_empty() {#a7d150e94e3cd7f6681fa07ea2b72da14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::use_empty ()</td>
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

<p>Return true if there are no uses of this node.</p>

<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a2a73ac8be22cfe2a7d10fd13e70d57e1">foldADDIForFasterLocalAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a2f1e2f811ae9139b9543751585239443">llvm::TargetLowering::getCheaperOrNeutralNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#acb7284db7f63030c26cd605c4afd7fa6">llvm::ARMTargetLowering::isVectorLoadExtDesirable</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa91c37999052160d434c5bf803257c9">llvm::SelectionDAG::RemoveDeadNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a>.</p>

</div>
</div>

### use\_size() {#a6163a1abbdce6098d64026e3393ecca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SDNode::use_size ()</td>
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

<p>Return the number of uses of this node.</p>


<p>This method takes time proportional to the number of uses.</p>


<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="#a9450817c42562fe06198b67be72a24ac">use_begin</a> and <a href="#aef02f2c1bd12936a80611b134b24a47d">use_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a14e0400deb65254122edb9e66d7bfcf7">performANDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a4a6ec610f1626d7d5198a8d06e9eba18">llvm::AArch64TargetLowering::shouldRemoveRedundantExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a3ded6112ba385818b252376e0dafa70a">anonymous{DAGCombiner.cpp}::DAGCombiner::visitFADDForFMACombine</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a10977176a9063297e4ed5e4c23422b29">anonymous{DAGCombiner.cpp}::DAGCombiner::visitFSUBForFMACombine</a>.</p>

</div>
</div>

### user\_begin() {#ae04dc684fcd3d20b890bbf44e4a28395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">user_iterator llvm::SDNode::user_begin ()</td>
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

<p>Provide iteration support to walk over all users of an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>.</p>

<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp/#abd648b9bbf53e1b89e8e7e2695034268">isMemOPCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a5c013753f05b14d6d638ffe65860c6f1">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a45cd7009ba8bafa53767589f88b53994">llvm::SITargetLowering::isReassocProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#acb7284db7f63030c26cd605c4afd7fa6">llvm::ARMTargetLowering::isVectorLoadExtDesirable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>, <a href="#ad5596cf1822f4cc9e37fb75b6dff630f">users</a> and <a href="#ad6b0a2bca17658c77d292e8848ee7e3e">users</a>.</p>

</div>
</div>

### users() {#ad5596cf1822f4cc9e37fb75b6dff630f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; user_iterator &gt; llvm::SDNode::users ()</td>
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



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ae04dc684fcd3d20b890bbf44e4a28395">user_begin</a> and <a href="#aac9d6f3ddac69a00594e8cc1510081e4">user_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a5275881bd107ea2567bbcc6170773d4a">llvm::AMDGPUTargetLowering::addTokenForArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a0ea933cf7c687d2caba4d0fd66d7ed47">adjustForLTGFR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab5a426cb5c2105ca954c4ab9f12ef76f">combineShiftToMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#af87756aa5602d0bdb89ae449ca01b179">hasVolatileUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0469afc3caef8616d4b1c7501cba1b8">isHorizontalBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a176c5cbd80b59d908680911c34fdde6f">isOnlyUsedByStores</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a5c013753f05b14d6d638ffe65860c6f1">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aa2cd314fbe333e0f217764966e7db967">isWorthFoldingSHL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aeefb78459638421a22efc227acbf0a2a">lowerShufflePairAsUNPCKAndPermute</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a5d3cc5ce2199f840a6a9273c2285746e">PerformFADDCombineWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6913e341612419ecb5b860b6759b929c">llvm::AMDGPUTargetLowering::performFNegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a40c243011cdda005e97448378d575096">performGlobalAddressCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7bd1aee507cb5d38c758c9d8620fb629">PerformREMCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ada4201742fab8916f9da75acd2b58fc1">performSRACombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledaglinearize/#ac5dfad52f2ec0adbc920cf686c615e00">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::Schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizedag-cpp/#a5cc28391bb90b8555e7da10104afdbd6">useSinCos</a>.</p>

</div>
</div>

### users() {#ad6b0a2bca17658c77d292e8848ee7e3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; user_iterator &gt; llvm::SDNode::users ()</td>
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



<p>Definition at line 874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ae04dc684fcd3d20b890bbf44e4a28395">user_begin</a> and <a href="#aac9d6f3ddac69a00594e8cc1510081e4">user_end</a>.</p>

</div>
</div>

### uses() {#a42e9a628b333dddfcc9d5fb17824dc17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_iterator &gt; llvm::SDNode::uses ()</td>
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



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a9450817c42562fe06198b67be72a24ac">use_begin</a> and <a href="#aef02f2c1bd12936a80611b134b24a47d">use_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a021f42abfec39ba02f6b719a449b21db">ExtendUsesToFormExtLoad</a>, <a href="#a2594280bfba5f9b0dff74cfb5b4f29d2">getGluedUser</a>, <a href="#ab6ea142f5ae930a660fbb4105ef42a98">hasAnyUseOfValue</a>, <a href="#ad82ad170343d0b4fe88a5551ec43659d">hasNUsesOfValue</a>, <a href="#a295d0b84f4e63438c0edb0021c41d47a">hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2869d5459dca008c1c7a1e824e7faf5e">llvm::SelectionDAG::ReplaceAllUsesOfValuesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>.</p>

</div>
</div>

### uses() {#a22d9b41775e14d6cf4cd11b33e2f05c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_iterator &gt; llvm::SDNode::uses ()</td>
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



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a9450817c42562fe06198b67be72a24ac">use_begin</a> and <a href="#aef02f2c1bd12936a80611b134b24a47d">use_end</a>.</p>

</div>
</div>

### value\_begin() {#aecf9393b9b8bfef4019780f5cb4db651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_iterator llvm::SDNode::value_begin ()</td>
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



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="#a210b2e97bcab8e5cbab59a92fc3e1b70">values</a>.</p>

</div>
</div>

### value\_end() {#a3ee68ee9398984fcd74e7cfcc3fb4ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_iterator llvm::SDNode::value_end ()</td>
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



<p>Definition at line 1084 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="#a210b2e97bcab8e5cbab59a92fc3e1b70">values</a>.</p>

</div>
</div>

### values() {#a210b2e97bcab8e5cbab59a92fc3e1b70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; value_iterator &gt; llvm::SDNode::values ()</td>
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



<p>Definition at line 1085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#aecf9393b9b8bfef4019780f5cb4db651">value_begin</a> and <a href="#a3ee68ee9398984fcd74e7cfcc3fb4ce0">value_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### DropOperands() {#aeffcf6f6a22d7591beed2f7a9d9fee20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SDNode::DropOperands ()</td>
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

<p>Release the operands and set this node to have zero operands.</p>


<p>DropOperands - Release the operands and set this node to have zero operands.</p>


<p>Declaration at line 1170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 10911 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aee6bd1fd282469b3476efce4b707f09a">op_begin</a>, <a href="#ae499cc99d4fe44d343ca9ac6a2ae8845">op_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a> and <a href="/web-llvm/docs/api/classes/llvm/use/#a40360b4fa7b8e6920a68e5a8a0814f1f">llvm::Use::set</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/handlesdnode/#a97ff75dd1d21754fe69c5bd2d28c51dd">llvm::HandleSDNode::~HandleSDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ConstantSDNodeBits {#ae72447d1a1b836c2f0e8b6ff423e3b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantSDNodeBitfields llvm::SDNode::ConstantSDNodeBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a7fb32f2b4aee1957c1c0ef3bc6589a5a">llvm::ConstantSDNode::isOpaque</a> and <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::ConstantSDNode::SelectionDAG</a>.</p>

</div>
</div>

### LoadSDNodeBits {#a305e5de87d3873ae5ae1b8de12b631f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadSDNodeBitfields llvm::SDNode::LoadSDNodeBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#a9adf1f62190a4bb8e413e90a80b1d30b">llvm::AtomicSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#ad85ec82447c2f1824538de9b449ffed0">llvm::LoadSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgathersdnode/#ad50a0839037ef004596c36fb0747f132">llvm::MaskedGatherSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadsdnode/#a5e8a56760cd84a8ae65da031cb23325d">llvm::MaskedLoadSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/vploadsdnode/#a4dc464489bfda12a2a630bef1b3acab2">llvm::VPLoadSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#a48191b584d98939e01c294312f3cc70c">llvm::VPStridedLoadSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadsdnode/#a20404c2e1366e0c7fa14af7e4e78f159">llvm::MaskedLoadSDNode::isExpandingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/vploadsdnode/#af8b83144d65631879820c591190ea783">llvm::VPLoadSDNode::isExpandingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#a5cbb0fcfa3ab48ce9dfef51fb13885d3">llvm::VPStridedLoadSDNode::isExpandingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgathersdnode/#a61aaa10c02d10b52ecae12b34805d901">llvm::MaskedGatherSDNode::MaskedGatherSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadsdnode/#a1a0e8f3ceb0bee93f6278d985e007f82">llvm::MaskedLoadSDNode::MaskedLoadSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::LoadSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#a1f47a74aa91b1356aa1d2b7416cd06ea">llvm::AtomicSDNode::setExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/vploadsdnode/#a9ad1af6c4a3cad363a085a3d68a8d666">llvm::VPLoadSDNode::VPLoadSDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#ad5cfda85e5251efee3809e81cd8659be">llvm::VPStridedLoadSDNode::VPStridedLoadSDNode</a>.</p>

</div>
</div>

### LSBaseSDNodeBits {#a4237d5ad92a3df47c762bdacb7b109e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LSBaseSDNodeBitfields llvm::SDNode::LSBaseSDNodeBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#a4030b40c584191b8fd4ad3febacfc082">llvm::LSBaseSDNode::getAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#afc34d1f7b397f399ec5107922a20c671">llvm::MaskedLoadStoreSDNode::getAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a9bd385364c986ea0ed953b8ef8243466">llvm::VPBaseLoadStoreSDNode::getAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#aac579f9e6e05352893f101a310023b21">llvm::MaskedGatherScatterSDNode::getIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedhistogramsdnode/#aeedd8ca0ecfe6c1c7cf3c721b685846a">llvm::MaskedHistogramSDNode::getIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a729dfc632abe01939c7eb2050b20d49c">llvm::VPGatherScatterSDNode::getIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#a083785be56ad0ab8dbf81e50a6a761ac">llvm::LSBaseSDNode::LSBaseSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#a70ef3f18e52d25106579f0673aaa6b1c">llvm::MaskedGatherScatterSDNode::MaskedGatherScatterSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#a2e7048e7f25ba106f889cbb5c8ab3d09">llvm::MaskedLoadStoreSDNode::MaskedLoadStoreSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a7cdac375772f7b4e63f30cb6fd02a4c6">llvm::VPBaseLoadStoreSDNode::VPBaseLoadStoreSDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a98f56e585d111952edfdc53e8d30e7a5">llvm::VPGatherScatterSDNode::VPGatherScatterSDNode</a>.</p>

</div>
</div>

### MemSDNodeBits {#a434bf5710046ffbca878d6379c5a6be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemSDNodeBitfields llvm::SDNode::MemSDNodeBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ac689f393979f367a01d766c2d0db529b">llvm::MemSDNode::isDereferenceable</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#abfc21c6926e533d26ad132d76eb1b0e7">llvm::MemSDNode::isInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aba37cfe8576deaf53760781cffe425fe">llvm::MemSDNode::isNonTemporal</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a64cdf55a9cfb33bd17e61beae253e3aa">llvm::MemSDNode::isVolatile</a> and <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a00a2cd9501aed5f7e8746c0458990503">llvm::MemSDNode::MemSDNode</a>.</p>

</div>
</div>

### PersistentId {#a9e75d949a65ef6909562f6439494ac06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::SDNode::PersistentId = 0xffff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unique and persistent id per <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> in the DAG.</p>


<p>Used for debug printing. We do not place that under <span class="doxyComputerOutput">#if LLVM_ENABLE_ABI_BREAKING_CHECKS</span> intentionally because it adds unneeded complexity without noticeable benefits (see discussion with @thakis in D120714). Currently, there are two padding bytes after this field.</p>


<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/handlesdnode/#a2321efb50c82783a57ab32a79830f213">llvm::HandleSDNode::HandleSDNode</a>.</p>

</div>
</div>

### RawSDNodeBits {#a0e80b38dfd0d7e5a37e81b971d633a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::SDNode::RawSDNodeBits[sizeof(uint16_t)]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ae80c6b39fd20683261c5f48f849693c7">llvm::MemSDNode::getRawSubclassData</a> and <a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a>.</p>

</div>
</div>

### SDNodeBits {#afb910e6a374ba558af8571d2a0a095ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNodeBitfields llvm::SDNode::SDNodeBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="#a478a16ce230e9f3901fdc6847bc063b5">getHasDebugValue</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ae80c6b39fd20683261c5f48f849693c7">llvm::MemSDNode::getRawSubclassData</a>, <a href="#a28417243f8d25f74e598d78d7802c366">isDivergent</a>, <a href="#a84ea0c52aaedee23f6e0ef24a0373201">isMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicsdnode/#a7840ddfe91a4ac8a274c60ed76f496cb">llvm::MemIntrinsicSDNode::MemIntrinsicSDNode</a> and <a href="#a40063dd06404e7d8df5bc40a956ae433">setHasDebugValue</a>.</p>

</div>
</div>

### StoreSDNodeBits {#a70ebb56a2ad697ea3d91bdddf419af1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StoreSDNodeBitfields llvm::SDNode::StoreSDNodeBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/maskedstoresdnode/#a013173de4641589e604dac46c2922b0b">llvm::MaskedStoreSDNode::isCompressingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#acd06a139da381c58c60f3d846b933830">llvm::VPStoreSDNode::isCompressingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#adabdec5aa2dd92fc3bab62458dcb1b6d">llvm::VPStridedStoreSDNode::isCompressingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedscattersdnode/#ae2522b8300a328b97f5e8254a7abe9a7">llvm::MaskedScatterSDNode::isTruncatingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedstoresdnode/#a634ded3768d9e3284cab2663fbc64df6">llvm::MaskedStoreSDNode::isTruncatingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#aa749a22473eb96b69739110332910e4e">llvm::StoreSDNode::isTruncatingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#ad7dacf27d443ae10e59eb005a8887be3">llvm::VPStoreSDNode::isTruncatingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#a460088a793f44c318224e6353f104e66">llvm::VPStridedStoreSDNode::isTruncatingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedscattersdnode/#a271d77d66ae014c74df87920f4ea05b8">llvm::MaskedScatterSDNode::MaskedScatterSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedstoresdnode/#a07562952b3d598a6158355ac26a326cf">llvm::MaskedStoreSDNode::MaskedStoreSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::StoreSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#aa820fc766465e05355b8ac7695d08f7e">llvm::StoreSDNode::setTruncatingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#a3c08669f110fb4a1f82c92cd8bb85e7d">llvm::VPStoreSDNode::VPStoreSDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#a61e2e3de34d6d12b3f1c2d916d21d281">llvm::VPStridedStoreSDNode::VPStridedStoreSDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

###  {#a03bbc707a0208f54539d04e1409394ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::SDNode llvm::SDNode</td>
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



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CFIType {#aad60e923c79b6c8955a62191bc8f1081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SDNode::CFIType = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### CombinerWorklistIndex {#a6a2e332a415a60ff9a00abb3d402f1ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SDNode::CombinerWorklistIndex = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index in worklist of DAGCombiner, or negative if the node is not in the worklist.</p>


<p>-1 = not in worklist; -2 = not in worklist, but has already been combined at least once.</p>


<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### debugLoc {#adff203d6ee679a31b8a42dd5034151a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::SDNode::debugLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source line information.</p>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### Flags {#a3ef304988dcedfe2ebc817313643be37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNodeFlags llvm::SDNode::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### IROrder {#a36d759f51453759d2975f734dec314c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDNode::IROrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### NodeId {#a40398a7840619a7b5da46c6f5db238f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SDNode::NodeId = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unique id per <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> in the DAG.</p>

<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### NodeType {#a1cb08146a9ce597bbe0fe041688b3bc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::SDNode::NodeType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The operation that this node performs.</p>

<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### NumOperands {#aa90c58a600afe6f83489372f2af02492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::SDNode::NumOperands = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of entries in the Operand/Value list.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### NumValues {#aac307623c65c259fa04b58d17a6455fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::SDNode::NumValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### OperandList {#aa7176483afc8e1542f045bfaf8b5e9a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDUse* llvm::SDNode::OperandList = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The values that are used by this operation.</p>

<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### UseList {#aff2eb8ff3c1bbcfbd468555842d4c3e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDUse* llvm::SDNode::UseList = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of uses for this <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>.</p>

<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### ValueList {#a55fc5cc51d97d619d16fcd99ae1f340a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EVT* llvm::SDNode::ValueList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The types of the values this node defines.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>'s may define multiple values simultaneously.</p>


<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### areOnlyUsersOf() {#a921a083162ebeec8f46240c1a48fef7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SDNode::areOnlyUsersOf (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; Nodes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all the users of N are contained in Nodes.</p>


<p>Return true if the only users of N are contained in Nodes.</p>


<p>NOTE: Requires at least one match, but doesn't require them all.</p>


<p>Declaration at line 970 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>.</p>

</div>
</div>

### getIndexedModeName() {#a2ba18a788637b22646b09602bd5a50c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * SDNode::getIndexedModeName (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31">ISD::MemIndexedMode</a> AM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31a10a4094c81c0b9cd5e82e53b48932203">llvm::ISD::POST_DEC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31a866c29237765ff291c9503abbdca60e1">llvm::ISD::POST_INC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31a57c3822f99653c422d5a21206adc6e42">llvm::ISD::PRE_DEC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>.</p>


<p>Referenced by <a href="#ac351340ed4428a1b6d69d303bcba86d9">print_details</a>.</p>

</div>
</div>

### getMaxNumOperands() {#a37b45952f6124e0e70fed54f06c59a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr size_t llvm::SDNode::getMaxNumOperands ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the maximum number of operands that a <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> can hold.</p>

<p>Definition at line 976 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">llvm::max</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a70d3e07bad78e3a1d2ba86aa871b9501">llvm::SelectionDAG::getTokenFactor</a>.</p>

</div>
</div>

### hasPredecessorHelper() {#a7c6beebf86835d6582b0550cd7731ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SDNode::hasPredecessorHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt; &amp; Worklist, unsigned int MaxSteps=0, bool TopologicalPrune=false)</td>
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

<p>Returns true if N is a predecessor of any node in Worklist.</p>


<p>This helper keeps Visited and Worklist sets externally to allow unions searches to be performed in parallel, caching of results across queries and incremental addition to Worklist. Stops early if N is found but will resume. Remember to clear Visited and Worklists if DAG changes. MaxSteps gives a maximum number of nodes to visit before giving up. The TopologicalPrune flag signals that positive NodeIds are topologically ordered (Operands have strictly smaller node id) and search can be pruned leveraging this.</p>


<p>Definition at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aefd9be80f1cb9ff1e978d98489a77ecd">MaxSteps</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a2bb043b87aa8cdef6d1e9e14329aec6a">op_values</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#af64f53af99d4ee7bbf57ea0aab719254">SDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aa10cee1a6cc1fbb381e3dab0c92c4cb2">canFoldStoreIntoLibCallOutputPointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a7e5a9b5c5f87a0f7d2227881e84be8a2">findNonImmUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a9d391021d805c83de0c322c3cb0fb355">getPostIndexedLoadStoreOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#aeb0bc3fb3008d1f61c5a1adb0b901c82">HandleMergeInputChains</a>, <a href="#ab250276b651715d29b3ed20467d5f0a0">hasPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abeb31ccfc9e083463bbeee472a765160">isValidBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac6c9b791cef5925e123539fb2934316b">shouldCombineToPostInc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae7edfd8337d702eebfdbf7010c3b2c74">tryMemPairCombine</a>.</p>

</div>
</div>

### use\_end() {#aef02f2c1bd12936a80611b134b24a47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_iterator llvm::SDNode::use_end ()</td>
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



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac630ccda26fea2f45afa3fb89bc1a8f4">llvm::SelectionDAG::ReplaceAllUsesOfValueWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5da44486df08f753ea147fe04e86026f">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad09a0f9913dd2fad9b84458bdb263aaa">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8518c120f782df9e974c8b1b589feb40">llvm::SelectionDAG::ReplaceAllUsesWith</a>, <a href="#a6163a1abbdce6098d64026e3393ecca7">use_size</a>, <a href="#a42e9a628b333dddfcc9d5fb17824dc17">uses</a> and <a href="#a22d9b41775e14d6cf4cd11b33e2f05c8">uses</a>.</p>

</div>
</div>

### user\_end() {#aac9d6f3ddac69a00594e8cc1510081e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">user_iterator llvm::SDNode::user_end ()</td>
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



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="#ad5596cf1822f4cc9e37fb75b6dff630f">users</a> and <a href="#ad6b0a2bca17658c77d292e8848ee7e3e">users</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### getSDVTList() {#a7154dd9788b4b7afed19471c3a7393f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDVTList llvm::SDNode::getSDVTList (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/handlesdnode/#a2321efb50c82783a57ab32a79830f213">llvm::HandleSDNode::HandleSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblocksdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::BasicBlockSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/condcodesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::CondCodeSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/labelsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::LabelSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnodesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::MDNodeSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/registermasksdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::RegisterMaskSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/srcvaluesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::SrcValueSDNode::SelectionDAG</a> and <a href="/web-llvm/docs/api/classes/llvm/vtsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::VTSDNode::SelectionDAG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getValueTypeList() {#a009a116b8e60eed5f2174a2370db6357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EVT * SDNode::getValueTypeList (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pointer to the specified value type.</p>


<p>getValueTypeList - Return a pointer to the specified value type.</p>


<p>Declaration at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12473 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp">SelectionDAGDumper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
