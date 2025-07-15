---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/tailduplicator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TailDuplicator` Class Reference

<p>Utility class to perform tail duplication. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TailDuplicator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">llvm/CodeGen/TailDuplicator.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a533d2f6b8e63f0dc5d94c348038db804">AvailableValsTy</a> = std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d68f8587f29b4e8c0f2c57c70bd3eed">RegSubRegPair</a> = <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1974019840857f5ae10aa6b4edc5317d">initMF</a> (MachineFunction &amp;MF, bool PreRegAlloc, const MachineBranchProbabilityInfo *MBPI, MBFIWrapper *MBFI, ProfileSummaryInfo *PSI, bool LayoutMode, unsigned TailDupSize=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare to run on a specific machine function. <a href="#a1974019840857f5ae10aa6b4edc5317d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b957210a6d62c3fe19410e746fc6ab4">tailDuplicateBlocks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for small blocks that are unconditionally branched to and do not fall through. <a href="#a1b957210a6d62c3fe19410e746fc6ab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7dba30d4d9162f00367404e06085391">shouldTailDuplicate</a> (bool IsSimple, MachineBasicBlock &amp;TailBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if it is profitable to duplicate this block. <a href="#aa7dba30d4d9162f00367404e06085391">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fffb36a3e1523ff3d26521f27c02df8">canTailDuplicate</a> (MachineBasicBlock *TailBB, MachineBasicBlock *PredBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if TailBB can successfully be duplicated into PredBB. <a href="#a8fffb36a3e1523ff3d26521f27c02df8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0f17f40e0399c6d151a50e99797e58">tailDuplicateAndUpdate</a> (bool IsSimple, MachineBasicBlock *MBB, MachineBasicBlock *ForcedLayoutPred, SmallVectorImpl&lt; MachineBasicBlock * &gt; *DuplicatedPreds=nullptr, function_ref&lt; void(MachineBasicBlock *)&gt; *RemovalCallback=nullptr, SmallVectorImpl&lt; MachineBasicBlock * &gt; *CandidatePtr=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tail duplicate a single basic block into its predecessors, and then clean up. <a href="#a1c0f17f40e0399c6d151a50e99797e58">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6dfbbe064199ada8872db93fafbb25">addSSAUpdateEntry</a> (Register OrigReg, Register NewReg, MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a definition and source virtual registers pair for SSA update. <a href="#aaf6dfbbe064199ada8872db93fafbb25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a91bb965d2e38538eda198752daabc1">processPHI</a> (MachineInstr *MI, MachineBasicBlock *TailBB, MachineBasicBlock *PredBB, DenseMap&lt; Register, RegSubRegPair &gt; &amp;LocalVRMap, SmallVectorImpl&lt; std::pair&lt; Register, RegSubRegPair &gt; &gt; &amp;Copies, const DenseSet&lt; Register &gt; &amp;UsedByPhi, bool Remove)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> PHI node in TailBB by turning it into a copy in PredBB. <a href="#a6a91bb965d2e38538eda198752daabc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac6f4630f1dddc1ccaff27bec9832b05">duplicateInstruction</a> (MachineInstr *MI, MachineBasicBlock *TailBB, MachineBasicBlock *PredBB, DenseMap&lt; Register, RegSubRegPair &gt; &amp;LocalVRMap, const DenseSet&lt; Register &gt; &amp;UsedByPhi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Duplicate a TailBB instruction to PredBB and update the source operands due to earlier PHI translation. <a href="#aac6f4630f1dddc1ccaff27bec9832b05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d30319cb163f5dc38f7fe70eccfcaf5">updateSuccessorsPHIs</a> (MachineBasicBlock *FromBB, bool isDead, SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;TDBBs, SmallSetVector&lt; MachineBasicBlock *, 8 &gt; &amp;Succs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After FromBB is tail duplicated into its predecessor blocks, the successors have gained new predecessors. <a href="#a5d30319cb163f5dc38f7fe70eccfcaf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad648e4cb2b934e2ed534acf4bd9cd9a9">canCompletelyDuplicateBB</a> (MachineBasicBlock &amp;BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a38ade9c743d4adbd125d61dbfbb0c7">duplicateSimpleBB</a> (MachineBasicBlock *TailBB, SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;TDBBs, const DenseSet&lt; Register &gt; &amp;RegsUsedByPhi)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278a085c332aad0e60b81642569c0e8e">tailDuplicate</a> (bool IsSimple, MachineBasicBlock *TailBB, MachineBasicBlock *ForcedLayoutPred, SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;TDBBs, SmallVectorImpl&lt; MachineInstr * &gt; &amp;Copies, SmallVectorImpl&lt; MachineBasicBlock * &gt; *CandidatePtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If it is profitable, duplicate TailBB's contents in each of its predecessors. <a href="#a278a085c332aad0e60b81642569c0e8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bfd8f34c99bf181bac920ff0c30199a">appendCopies</a> (MachineBasicBlock *MBB, SmallVectorImpl&lt; std::pair&lt; Register, RegSubRegPair &gt; &gt; &amp;CopyInfos, SmallVectorImpl&lt; MachineInstr * &gt; &amp;Copies)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>At the end of the block <span class="doxyComputerOutput">MBB</span> generate COPY instructions between registers described by <span class="doxyComputerOutput">CopyInfos</span>. <a href="#a3bfd8f34c99bf181bac920ff0c30199a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324991efafa19205d6c8283b1ab9c4bc">removeDeadBlock</a> (MachineBasicBlock *MBB, function_ref&lt; void(MachineBasicBlock *)&gt; *RemovalCallback=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified dead machine basic block from the function, updating the CFG. <a href="#a324991efafa19205d6c8283b1ab9c4bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa192941648d3c556a2f28d1f01584b19">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4ea8918349745eed50700e9c1b41664">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd356af0446d3fa19540b5ad26243caa">MBPI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35111feec198f000577347f0e6f75615">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1fe58b450f75c4a6aabb2291fbdad49">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mbfiwrapper">MBFIWrapper</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1020208f4f90094513954e36892ff85d">MBFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afebb03d86e2838d1b608c7d47f3341b9">PSI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a085622ba45fe7a89c5eaa07587b20dc8">PreRegAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c5b896064c23b061b98044e8e3e3ec5">LayoutMode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f69d5416f1ae6d7583dd5a003fe05f">TailDupSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b9ac8f8f0b3c9aad99a7d0443cde336">SSAUpdateVRs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, AvailableValsTy &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a555c49a3d8b085dd48862452554d5c39">SSAUpdateVals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b5f49c33bc7b11d150556b0ee1ca0a">isSimpleBB</a> (MachineBasicBlock *TailBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this BB has only one unconditional jump. <a href="#a22b5f49c33bc7b11d150556b0ee1ca0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Utility class to perform tail duplication.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AvailableValsTy {#a533d2f6b8e63f0dc5d94c348038db804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TailDuplicator::AvailableValsTy =  std::vector&lt;std::pair&lt;MachineBasicBlock *, Register&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### RegSubRegPair {#a0d68f8587f29b4e8c0f2c57c70bd3eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TailDuplicator::RegSubRegPair =  TargetInstrInfo::RegSubRegPair</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canTailDuplicate() {#a8fffb36a3e1523ff3d26521f27c02df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TailDuplicator::canTailDuplicate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TailBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PredBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if TailBB can successfully be duplicated into PredBB.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a00e55a6b6b44b739e9da1d62f1d8a5b3">llvm::MachineBasicBlock::isInlineAsmBrIndirectTarget</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>.</p>

</div>
</div>

### initMF() {#a1974019840857f5ae10aa6b4edc5317d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TailDuplicator::initMF (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, bool PreRegAlloc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> * MBPI, <a href="/web-llvm/docs/api/classes/llvm/mbfiwrapper">MBFIWrapper</a> * MBFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, bool LayoutMode, unsigned TailDupSize=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepare to run on a specific machine function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MF</td>
<td class="doxyParamItemDescription"><p>- <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> that will be processed</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PreRegAlloc</td>
<td class="doxyParamItemDescription"><p>- true if used before register allocation</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MBPI</td>
<td class="doxyParamItemDescription"><p>- Branch Probability Info. Used to propagate correct probabilities when modifying the CFG.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LayoutMode</td>
<td class="doxyParamItemDescription"><p>- When true, don't use the existing layout to make decisions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TailDupSize</td>
<td class="doxyParamItemDescription"><p>- Maxmimum size of blocks to tail-duplicate. Zero default implies using the command line value TailDupSize.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tailduplicatepassbase/#a0780ac5d6a2962adf46e1c611e6ca6fa">llvm::TailDuplicatePassBase&lt; DerivedT, PreRegAlloc &gt;::run</a>.</p>

</div>
</div>

### shouldTailDuplicate() {#aa7dba30d4d9162f00367404e06085391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TailDuplicator::shouldTailDuplicate (bool IsSimple, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TailBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if it is profitable to duplicate this block.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf35424231192c6b4a3e22d711f50b1e">llvm::MachineBasicBlock::back</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5ffb77c69d69a5beff906caaecfd7be4">llvm::MachineBasicBlock::canFallThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a095ce2d870dadf620a4c887ecc0efef8">llvm::MachineBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33fe94054a904130a7c774f78423c8b7">llvm::TargetMachine::getTargetTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp/#acc16edf21eddec420cd4b27adb3111c6">InstrCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a19ce3659ba05d62794e306f6d070a850">llvm::MachineInstr::isIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ab6fdf9b428bc3d57837022121c155cbf">llvm::Triple::isOSDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adc8f1be4a77ae671ac139d5f06b44deb">llvm::MachineBasicBlock::isSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#aecc8f70ed265db22955640a6e1aa396b">TailDupIndirectBranchSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#a18b176a0ede2d73fc8c45ab79e30e66f">TailDuplicateSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#a44220b47eb71fa141e85efc36579ae27">TailDupPredSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#a5cbdacc193404b637719f0e857254113">TailDupSuccSize</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a703ba58bd58d60cd76ad205dda1634eb">llvm::MachineBasicBlock::terminatorIsComputedGoto</a>.</p>


<p>Referenced by <a href="#a1b957210a6d62c3fe19410e746fc6ab4">tailDuplicateBlocks</a>.</p>

</div>
</div>

### tailDuplicateAndUpdate() {#a1c0f17f40e0399c6d151a50e99797e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TailDuplicator::tailDuplicateAndUpdate (bool IsSimple, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * ForcedLayoutPred, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; * DuplicatedPreds=nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *)&gt; * RemovalCallback=nullptr, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; * CandidatePtr=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tail duplicate a single basic block into its predecessors, and then clean up.</p>


<p>Tail duplicate the block and cleanup.</p>


<p>If <span class="doxyComputerOutput">DuplicatePreds</span> is not null, it will be updated to contain the list of predecessors that received a copy of <span class="doxyComputerOutput">MBB</span>. If <span class="doxyComputerOutput">RemovalCallback</span> is non-null. It will be called before MBB is deleted. If <span class="doxyComputerOutput">CandidatePtr</span> is not null, duplicate into these blocks only.</p>


<p><span class="doxyComputerOutput">IsSimple</span> - return value of isSimpleBB <span class="doxyComputerOutput">MBB</span> - block to be duplicated <span class="doxyComputerOutput">ForcedLayoutPred</span> - If non-null, treat this block as the layout predecessor, instead of using the ordering in MF <span class="doxyComputerOutput">DuplicatedPreds</span> - if non-null, <span class="doxyComputerOutput">DuplicatedPreds</span> will contain a list of all Preds that received a copy of <span class="doxyComputerOutput">MBB</span>. <span class="doxyComputerOutput">RemovalCallback</span> - if non-null, called just before MBB is deleted.</p>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#ab01bfdaa2826542f165fa1ff6a2aacf1">llvm::MachineSSAUpdater::AddAvailableValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp/#a5cd9e4c7fe1a7ebe8b545eb891a2a949">Copies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a00117e47ce48a2a6e82e852dbb342202">llvm::MachineSSAUpdater::Initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#af977af9be6319c90e0918cb38b4f045b">isDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a71a08885f7838dc5a544816a357e2ec7">llvm::MachineSSAUpdater::RewriteUse</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#a1b957210a6d62c3fe19410e746fc6ab4">tailDuplicateBlocks</a>.</p>

</div>
</div>

### tailDuplicateBlocks() {#a1b957210a6d62c3fe19410e746fc6ab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TailDuplicator::tailDuplicateBlocks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for small blocks that are unconditionally branched to and do not fall through.</p>


<p>Tail-duplicate their instructions into their predecessors to eliminate (dynamic) branches.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="#a22b5f49c33bc7b11d150556b0ee1ca0a">isSimpleBB</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aa7dba30d4d9162f00367404e06085391">shouldTailDuplicate</a>, <a href="#a1c0f17f40e0399c6d151a50e99797e58">tailDuplicateAndUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#a3b48dcbea48d075f9499d16b28039329">TailDupLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#a6cd47dc48def323bdf8b022f8ebe42d7">TailDupVerify</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#a833919b7851dc025ff507a7f8652bb8e">VerifyPHIs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tailduplicatepassbase/#a0780ac5d6a2962adf46e1c611e6ca6fa">llvm::TailDuplicatePassBase&lt; DerivedT, PreRegAlloc &gt;::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addSSAUpdateEntry() {#aaf6dfbbe064199ada8872db93fafbb25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TailDuplicator::addSSAUpdateEntry (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OrigReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a definition and source virtual registers pair for SSA update.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>

</div>
</div>

### appendCopies() {#a3bfd8f34c99bf181bac920ff0c30199a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TailDuplicator::appendCopies (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">RegSubRegPair</a> &gt; &gt; &amp; CopyInfos, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; Copies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>At the end of the block <span class="doxyComputerOutput">MBB</span> generate COPY instructions between registers described by <span class="doxyComputerOutput">CopyInfos</span>.</p>


<p>Append resulting instructions to <span class="doxyComputerOutput">Copies</span>.</p>


<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 1065 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>

</div>
</div>

### canCompletelyDuplicateBB() {#ad648e4cb2b934e2ed534acf4bd9cd9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TailDuplicator::canCompletelyDuplicateBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>

</div>
</div>

### duplicateInstruction() {#aac6f4630f1dddc1ccaff27bec9832b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TailDuplicator::duplicateInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TailBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PredBB, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">RegSubRegPair</a> &gt; &amp; LocalVRMap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UsedByPhi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Duplicate a TailBB instruction to PredBB and update the source operands due to earlier PHI translation.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>

</div>
</div>

### duplicateSimpleBB() {#a5a38ade9c743d4adbd125d61dbfbb0c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TailDuplicator::duplicateSimpleBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TailBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; TDBBs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; RegsUsedByPhi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>

</div>
</div>

### processPHI() {#a6a91bb965d2e38538eda198752daabc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TailDuplicator::processPHI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TailBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PredBB, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">RegSubRegPair</a> &gt; &amp; LocalVRMap, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">RegSubRegPair</a> &gt; &gt; &amp; Copies, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; RegsUsedByPhi, bool Remove)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> PHI node in TailBB by turning it into a copy in PredBB.</p>


<p>Remember the source register that's contributed by PredBB and update SSA update map.</p>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>

</div>
</div>

### removeDeadBlock() {#a324991efafa19205d6c8283b1ab9c4bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TailDuplicator::removeDeadBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *)&gt; * RemovalCallback=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified dead machine basic block from the function, updating the CFG.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>

</div>
</div>

### tailDuplicate() {#a278a085c332aad0e60b81642569c0e8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TailDuplicator::tailDuplicate (bool IsSimple, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TailBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * ForcedLayoutPred, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; TDBBs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; Copies, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; * CandidatePtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If it is profitable, duplicate TailBB's contents in each of its predecessors.</p>


<p><span class="doxyComputerOutput">IsSimple</span> result of isSimpleBB <span class="doxyComputerOutput">TailBB</span> Block to be duplicated. <span class="doxyComputerOutput">ForcedLayoutPred</span> When non-null, use this block as the layout predecessor instead of the previous block in MF's order. <span class="doxyComputerOutput">TDBBs</span> A vector to keep track of all blocks tail-duplicated into. <span class="doxyComputerOutput">Copies</span> A vector of copy instructions inserted. Used later to walk all the inserted copies and remove redundant ones.</p>


<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>

</div>
</div>

### updateSuccessorsPHIs() {#a5d30319cb163f5dc38f7fe70eccfcaf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TailDuplicator::updateSuccessorsPHIs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FromBB, bool isDead, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; TDBBs, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 8 &gt; &amp; Succs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After FromBB is tail duplicated into its predecessor blocks, the successors have gained new predecessors.</p>


<p>Update the PHI instructions in them accordingly.</p>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LayoutMode {#a2c5b896064c23b061b98044e8e3e3ec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TailDuplicator::LayoutMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### MBFI {#a1020208f4f90094513954e36892ff85d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBFIWrapper* llvm::TailDuplicator::MBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### MBPI {#acd356af0446d3fa19540b5ad26243caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBranchProbabilityInfo* llvm::TailDuplicator::MBPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### MF {#aa1fe58b450f75c4a6aabb2291fbdad49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::TailDuplicator::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### MRI {#a35111feec198f000577347f0e6f75615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::TailDuplicator::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### PreRegAlloc {#a085622ba45fe7a89c5eaa07587b20dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TailDuplicator::PreRegAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### PSI {#afebb03d86e2838d1b608c7d47f3341b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* llvm::TailDuplicator::PSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### SSAUpdateVals {#a555c49a3d8b085dd48862452554d5c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, AvailableValsTy&gt; llvm::TailDuplicator::SSAUpdateVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### SSAUpdateVRs {#a8b9ac8f8f0b3c9aad99a7d0443cde336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 16&gt; llvm::TailDuplicator::SSAUpdateVRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### TailDupSize {#aa8f69d5416f1ae6d7583dd5a003fe05f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TailDuplicator::TailDupSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### TII {#aa192941648d3c556a2f28d1f01584b19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::TailDuplicator::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

### TRI {#ad4ea8918349745eed50700e9c1b41664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::TailDuplicator::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isSimpleBB() {#a22b5f49c33bc7b11d150556b0ee1ca0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TailDuplicator::isSimpleBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TailBB)</td>
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

<p>True if this BB has only one unconditional jump.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a>, definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a62b5d2211c09378c471307293453d780">llvm::MachineBasicBlock::getFirstNonDebugInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a877507fda31c207ec36a018784369708">llvm::MachineBasicBlock::pred_empty</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>.</p>


<p>Referenced by <a href="#a1b957210a6d62c3fe19410e746fc6ab4">tailDuplicateBlocks</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/tailduplicator-h">TailDuplicator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp">TailDuplicator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
