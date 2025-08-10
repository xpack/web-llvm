---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/dgnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DGNode` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> <a href="/web-llvm/docs/api/classes/node">Node</a> that points to an <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> and contains memory dependency edges. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::DGNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">llvm/Transforms/Vectorize/SandboxVectorizer/DependencyGraph.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> <a href="/web-llvm/docs/api/classes/node">Node</a> for instructions that may read/write memory, or have some ordering constraints, like with stacksave/stackrestore and alloca/inalloca. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a092a57c6895926cdc38b5b86d37c12">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/sandboxir/prediterator">PredIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070cf2a453521647e94d55981e96cf99">SchedBundle</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54077f081cf68ebe80c1aad5f9628151">MemDGNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed0ea23a6bea9a8d9432bd79b53c7219">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1513b646d997815c116f387fbc0c1f79">DGNode</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac658ffa5303478262f55dd88a11da991">DGNode</a> (const DGNode &amp;Other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d180e6958c0349fa578d0fbd3298faa">DGNode</a> (Instruction *I, DGNodeID ID)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd44e119740ec6771f922bba94a8ab2">~DGNode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a638d8c378ec2ed88b12edf9a64078240">getNumUnscheduledSuccs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the number of unscheduled successors. <a href="#a638d8c378ec2ed88b12edf9a64078240">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0711688e30314475ee4da4a3539d8032">decrUnscheduledSuccs</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c64df89d1520fbed8907df94ae53f2">ready</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if all dependent successors have been scheduled. <a href="#a88c64df89d1520fbed8907df94ae53f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7605f8f46182353463f3089f28e4ebab">scheduled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if this node has been scheduled. <a href="#a7605f8f46182353463f3089f28e4ebab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854bbb90fe11fd02b252d2a1d7affaa6">setScheduled</a> (bool NewVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle">SchedBundle</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac225caf79ca52b84701da01c7f168d24">getSchedBundle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the scheduling bundle that this node belongs to, or nullptr. <a href="#ac225caf79ca52b84701da01c7f168d24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb8920ca33a5b73c47e8323e6b588dec">comesBefore</a> (const DGNode *Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if this is before <span class="doxyComputerOutput">Other</span> in program order. <a href="#adb8920ca33a5b73c47e8323e6b588dec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5a092a57c6895926cdc38b5b86d37c12">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5190aa78dee07bdeba819e2edefc52d">preds_begin</a> (DependencyGraph &amp;DAG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5a092a57c6895926cdc38b5b86d37c12">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e61e6f681ccde97cc317f54d075716d">preds_end</a> (DependencyGraph &amp;DAG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5a092a57c6895926cdc38b5b86d37c12">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4219d98c5a132249dae3e65bd58e8f55">preds_begin</a> (DependencyGraph &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5a092a57c6895926cdc38b5b86d37c12">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa03ec800fcc2f19eb4552e93510d9113">preds_end</a> (DependencyGraph &amp;DAG) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a5a092a57c6895926cdc38b5b86d37c12">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a698f16d29354015faebe94a0c3457f">preds</a> (DependencyGraph &amp;DAG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns a range of DAG predecessors nodes. <a href="#a9a698f16d29354015faebe94a0c3457f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6adf15fe451a7d857cea3f8a1905f81">getInstruction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d55236dec78bc0420e7d86e78f5518a">print</a> (raw_ostream &amp;OS, bool PrintDeps=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad50c853d86f310072d65b617f23de4f6">dump</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746460f87865796b09f8ee64afee34a1">setSchedBundle</a> (SchedBundle &amp;SB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf18a7c5378cde4012d8d0a74124593e">clearSchedBundle</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#af59141b63a92961900cf61ba28262920">DGNodeID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fca33b920387d9421eec7178d1ad11">SubclassID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For isa/dyn_cast etc. <a href="#ac2fca33b920387d9421eec7178d1ad11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abcb1441a1b337d2be367a2b7cebe9b">UnscheduledSuccs</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of unscheduled successors. <a href="#a7abcb1441a1b337d2be367a2b7cebe9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab098cf6863005cd2383e1d347a349fbf">Scheduled</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is true if this node has been scheduled. <a href="#ab098cf6863005cd2383e1d347a349fbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle">SchedBundle</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf526dbbef9b86942cfa68d3ce6f5ab1">SB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The scheduler bundle that this node belongs to. <a href="#aaf526dbbef9b86942cfa68d3ce6f5ab1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ebd81638e4b1036804e15f659c22fa">isStackSaveOrRestoreIntrinsic</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aacb50005956176b4baba331072edc3">isMemIntrinsic</a> (IntrinsicInst *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if intrinsic <span class="doxyComputerOutput">I</span> touches memory. <a href="#a3aacb50005956176b4baba331072edc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e539bf766322a8813af1cbe288b8332">isMemDepCandidate</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We consider <span class="doxyComputerOutput">I</span> as a <a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Dependency Candidate instruction if it reads/write memory or if it has side-effects. <a href="#a2e539bf766322a8813af1cbe288b8332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1fd672c351e106798e5c147726c33a">isFenceLike</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if <span class="doxyComputerOutput">I</span> is fence like. It excludes non-mem intrinsics. <a href="#acc1fd672c351e106798e5c147726c33a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b89d7c178eb196de3d1f05cc205642">isMemDepNodeCandidate</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if <span class="doxyComputerOutput">I</span> is a memory dependency candidate instruction. <a href="#ac1b89d7c178eb196de3d1f05cc205642">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> <a href="/web-llvm/docs/api/classes/node">Node</a> that points to an <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> and contains memory dependency edges.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a5a092a57c6895926cdc38b5b86d37c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::DGNode::iterator =  PredIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DependencyGraph {#a0e281b1504ddc5ad8c3fdd3de5fc67e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a></td>
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


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>.</p>


<p>Referenced by <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>, <a href="#a9a698f16d29354015faebe94a0c3457f">preds</a>, <a href="#af5190aa78dee07bdeba819e2edefc52d">preds_begin</a>, <a href="#a4219d98c5a132249dae3e65bd58e8f55">preds_begin</a>, <a href="#a2e61e6f681ccde97cc317f54d075716d">preds_end</a> and <a href="#aa03ec800fcc2f19eb4552e93510d9113">preds_end</a>.</p>

</div>
</div>

### MemDGNode {#a54077f081cf68ebe80c1aad5f9628151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a></td>
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


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#a54077f081cf68ebe80c1aad5f9628151">MemDGNode</a>.</p>


<p>Referenced by <a href="#a54077f081cf68ebe80c1aad5f9628151">MemDGNode</a>.</p>

</div>
</div>

### operator&lt;&lt; {#aed0ea23a6bea9a8d9432bd79b53c7219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> &amp; N</td>
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


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a5d180e6958c0349fa578d0fbd3298faa">DGNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SchedBundle {#a070cf2a453521647e94d55981e96cf99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle">SchedBundle</a></td>
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


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#a070cf2a453521647e94d55981e96cf99">SchedBundle</a>.</p>


<p>Referenced by <a href="#ac225caf79ca52b84701da01c7f168d24">getSchedBundle</a>, <a href="#a070cf2a453521647e94d55981e96cf99">SchedBundle</a> and <a href="#a746460f87865796b09f8ee64afee34a1">setSchedBundle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DGNode() {#a1513b646d997815c116f387fbc0c1f79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::DGNode::DGNode (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5d180e6958c0349fa578d0fbd3298faa">DGNode</a>, <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a>, <a href="#ac1b89d7c178eb196de3d1f05cc205642">isMemDepNodeCandidate</a> and <a href="#ac2fca33b920387d9421eec7178d1ad11">SubclassID</a>.</p>

</div>
</div>

### DGNode() {#ac658ffa5303478262f55dd88a11da991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::DGNode::DGNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> &amp; Other)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a5d180e6958c0349fa578d0fbd3298faa">DGNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### DGNode() {#a5d180e6958c0349fa578d0fbd3298faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::DGNode::DGNode (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#af59141b63a92961900cf61ba28262920">DGNodeID</a> ID)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a> and <a href="#ac2fca33b920387d9421eec7178d1ad11">SubclassID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#a3ea0a929c3d4b4bb875a19ac00f7aa94">llvm::sandboxir::MemDGNode::classof</a>, <a href="#adb8920ca33a5b73c47e8323e6b588dec">comesBefore</a>, <a href="#ac658ffa5303478262f55dd88a11da991">DGNode</a>, <a href="#a1513b646d997815c116f387fbc0c1f79">DGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#a29735a2d6ea6cc680b8553d1013e040d">llvm::sandboxir::MemDGNode::hasMemPred</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#aaca93c4d946ee53558d24b87a1d131ad">llvm::sandboxir::MemDGNode::MemDGNode</a>, <a href="#aed0ea23a6bea9a8d9432bd79b53c7219">operator&lt;&lt;</a>, <a href="#a4219d98c5a132249dae3e65bd58e8f55">preds_begin</a> and <a href="#aa03ec800fcc2f19eb4552e93510d9113">preds_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DGNode() {#a5bd44e119740ec6771f922bba94a8ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::DGNode::~DGNode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>Reference <a href="#aaf526dbbef9b86942cfa68d3ce6f5ab1">SB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### comesBefore() {#adb8920ca33a5b73c47e8323e6b588dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DGNode::comesBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> * Other)</td>
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

<p>\Returns true if this is before <span class="doxyComputerOutput">Other</span> in program order.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a5d180e6958c0349fa578d0fbd3298faa">DGNode</a>, <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### decrUnscheduledSuccs() {#a0711688e30314475ee4da4a3539d8032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DGNode::decrUnscheduledSuccs ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7abcb1441a1b337d2be367a2b7cebe9b">UnscheduledSuccs</a>.</p>

</div>
</div>

### dump() {#ad50c853d86f310072d65b617f23de4f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DGNode::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a1d55236dec78bc0420e7d86e78f5518a">print</a>.</p>

</div>
</div>

### getInstruction() {#ad6adf15fe451a7d857cea3f8a1905f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::sandboxir::DGNode::getInstruction ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle/#a0dda45551d702439204dbc2ef32eade7">llvm::sandboxir::SchedBundle::getBot</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle/#a2de3d46c20d973de8710506ad587749c">llvm::sandboxir::SchedBundle::getTop</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/prioritycmp/#a0bb88b086ad7f839e857adcba9537fe6">llvm::sandboxir::PriorityCmp::operator()</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph/#aa8602ab3d40d78dfbf826e154ac3fb8d">llvm::sandboxir::DependencyGraph::print</a>.</p>

</div>
</div>

### getNumUnscheduledSuccs() {#a638d8c378ec2ed88b12edf9a64078240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::DGNode::getNumUnscheduledSuccs ()</td>
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

<p>\Returns the number of unscheduled successors.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#a7abcb1441a1b337d2be367a2b7cebe9b">UnscheduledSuccs</a>.</p>

</div>
</div>

### getSchedBundle() {#ac225caf79ca52b84701da01c7f168d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedBundle * llvm::sandboxir::DGNode::getSchedBundle ()</td>
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

<p>\Returns the scheduling bundle that this node belongs to, or nullptr.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#aaf526dbbef9b86942cfa68d3ce6f5ab1">SB</a> and <a href="#a070cf2a453521647e94d55981e96cf99">SchedBundle</a>.</p>

</div>
</div>

### preds() {#a9a698f16d29354015faebe94a0c3457f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::sandboxir::DGNode::preds (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
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

<p>\Returns a range of DAG predecessors nodes.</p>


<p>If this is a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> then this will also include the memory dependency predecessors. Please note that this can include the same node more than once, if for example it's both a use-def predecessor and a mem dep predecessor.</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#af5190aa78dee07bdeba819e2edefc52d">preds_begin</a> and <a href="#a2e61e6f681ccde97cc317f54d075716d">preds_end</a>.</p>

</div>
</div>

### preds\_begin() {#af5190aa78dee07bdeba819e2edefc52d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual iterator llvm::sandboxir::DGNode::preds_begin (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>, <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#aa24cfbd52340fdfc1d9d0a9b41e45226">llvm::sandboxir::skipNonInstr</a>.</p>


<p>Referenced by <a href="#a9a698f16d29354015faebe94a0c3457f">preds</a> and <a href="#a4219d98c5a132249dae3e65bd58e8f55">preds_begin</a>.</p>

</div>
</div>

### preds\_begin() {#a4219d98c5a132249dae3e65bd58e8f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sandboxir::DGNode::preds_begin (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>, <a href="#a5d180e6958c0349fa578d0fbd3298faa">DGNode</a> and <a href="#af5190aa78dee07bdeba819e2edefc52d">preds_begin</a>.</p>

</div>
</div>

### preds\_end() {#a2e61e6f681ccde97cc317f54d075716d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual iterator llvm::sandboxir::DGNode::preds_end (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a> and <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a>.</p>


<p>Referenced by <a href="#a9a698f16d29354015faebe94a0c3457f">preds</a> and <a href="#aa03ec800fcc2f19eb4552e93510d9113">preds_end</a>.</p>

</div>
</div>

### preds\_end() {#aa03ec800fcc2f19eb4552e93510d9113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sandboxir::DGNode::preds_end (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>, <a href="#a5d180e6958c0349fa578d0fbd3298faa">DGNode</a> and <a href="#a2e61e6f681ccde97cc317f54d075716d">preds_end</a>.</p>

</div>
</div>

### print() {#a1d55236dec78bc0420e7d86e78f5518a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DGNode::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool PrintDeps=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>References <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a>, <a href="#ab098cf6863005cd2383e1d347a349fbf">Scheduled</a> and <a href="#a7abcb1441a1b337d2be367a2b7cebe9b">UnscheduledSuccs</a>.</p>


<p>Referenced by <a href="#ad50c853d86f310072d65b617f23de4f6">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#a98726d4d9fcff82e7518d14b2e6b111a">llvm::sandboxir::MemDGNode::print</a>.</p>

</div>
</div>

### ready() {#a88c64df89d1520fbed8907df94ae53f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DGNode::ready ()</td>
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

<p>\Returns true if all dependent successors have been scheduled.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#a7abcb1441a1b337d2be367a2b7cebe9b">UnscheduledSuccs</a>.</p>

</div>
</div>

### scheduled() {#a7605f8f46182353463f3089f28e4ebab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DGNode::scheduled ()</td>
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

<p>\Returns true if this node has been scheduled.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#ab098cf6863005cd2383e1d347a349fbf">Scheduled</a>.</p>

</div>
</div>

### setScheduled() {#a854bbb90fe11fd02b252d2a1d7affaa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DGNode::setScheduled (bool NewVal)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#ab098cf6863005cd2383e1d347a349fbf">Scheduled</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### clearSchedBundle() {#acf18a7c5378cde4012d8d0a74124593e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DGNode::clearSchedBundle ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### setSchedBundle() {#a746460f87865796b09f8ee64afee34a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::DGNode::setSchedBundle (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle">SchedBundle</a> &amp; SB)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#aaf526dbbef9b86942cfa68d3ce6f5ab1">SB</a> and <a href="#a070cf2a453521647e94d55981e96cf99">SchedBundle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### I {#a476b7ce8aae2be423ff92d723e80c1ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::sandboxir::DGNode::I</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Referenced by <a href="#adb8920ca33a5b73c47e8323e6b588dec">comesBefore</a>, <a href="#a1513b646d997815c116f387fbc0c1f79">DGNode</a>, <a href="#a5d180e6958c0349fa578d0fbd3298faa">DGNode</a>, <a href="#ad6adf15fe451a7d857cea3f8a1905f81">getInstruction</a>, <a href="#acc1fd672c351e106798e5c147726c33a">isFenceLike</a>, <a href="#a2e539bf766322a8813af1cbe288b8332">isMemDepCandidate</a>, <a href="#ac1b89d7c178eb196de3d1f05cc205642">isMemDepNodeCandidate</a>, <a href="#a3aacb50005956176b4baba331072edc3">isMemIntrinsic</a>, <a href="#ad6ebd81638e4b1036804e15f659c22fa">isStackSaveOrRestoreIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#aaca93c4d946ee53558d24b87a1d131ad">llvm::sandboxir::MemDGNode::MemDGNode</a>, <a href="#af5190aa78dee07bdeba819e2edefc52d">preds_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#a1d3d14ffce5af497e11ba489b312938c">llvm::sandboxir::MemDGNode::preds_begin</a>, <a href="#a2e61e6f681ccde97cc317f54d075716d">preds_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#a089f843815efa5f6fbc88f1a55409383">llvm::sandboxir::MemDGNode::preds_end</a> and <a href="#a1d55236dec78bc0420e7d86e78f5518a">print</a>.</p>

</div>
</div>

### SB {#aaf526dbbef9b86942cfa68d3ce6f5ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedBundle* llvm::sandboxir::DGNode::SB = nullptr</td>
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

<p>The scheduler bundle that this node belongs to.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Referenced by <a href="#ac225caf79ca52b84701da01c7f168d24">getSchedBundle</a>, <a href="#a746460f87865796b09f8ee64afee34a1">setSchedBundle</a> and <a href="#a5bd44e119740ec6771f922bba94a8ab2">~DGNode</a>.</p>

</div>
</div>

### Scheduled {#ab098cf6863005cd2383e1d347a349fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DGNode::Scheduled = false</td>
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

<p>This is true if this node has been scheduled.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#adc30e7d524bb4a48b4f0054fdf4e4487">llvm::sandboxir::MemDGNode::addMemPred</a>, <a href="#a1d55236dec78bc0420e7d86e78f5518a">print</a>, <a href="#a7605f8f46182353463f3089f28e4ebab">scheduled</a> and <a href="#a854bbb90fe11fd02b252d2a1d7affaa6">setScheduled</a>.</p>

</div>
</div>

### SubclassID {#ac2fca33b920387d9421eec7178d1ad11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DGNodeID llvm::sandboxir::DGNode::SubclassID</td>
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

<p>For isa/dyn_cast etc.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Referenced by <a href="#a1513b646d997815c116f387fbc0c1f79">DGNode</a> and <a href="#a5d180e6958c0349fa578d0fbd3298faa">DGNode</a>.</p>

</div>
</div>

### UnscheduledSuccs {#a7abcb1441a1b337d2be367a2b7cebe9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::DGNode::UnscheduledSuccs = 0</td>
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

<p>The number of unscheduled successors.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#adc30e7d524bb4a48b4f0054fdf4e4487">llvm::sandboxir::MemDGNode::addMemPred</a>, <a href="#a0711688e30314475ee4da4a3539d8032">decrUnscheduledSuccs</a>, <a href="#a638d8c378ec2ed88b12edf9a64078240">getNumUnscheduledSuccs</a>, <a href="#a1d55236dec78bc0420e7d86e78f5518a">print</a> and <a href="#a88c64df89d1520fbed8907df94ae53f2">ready</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isFenceLike() {#acc1fd672c351e106798e5c147726c33a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DGNode::isFenceLike (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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

<p>\Returns true if <span class="doxyComputerOutput">I</span> is fence like. It excludes non-mem intrinsics.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="#a3aacb50005956176b4baba331072edc3">isMemIntrinsic</a>.</p>


<p>Referenced by <a href="#ac1b89d7c178eb196de3d1f05cc205642">isMemDepNodeCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a08f05f0c0f1ba57bd86262ea33748cec">llvm::sandboxir::isOrdered</a>.</p>

</div>
</div>

### isMemDepCandidate() {#a2e539bf766322a8813af1cbe288b8332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DGNode::isMemDepCandidate (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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

<p>We consider <span class="doxyComputerOutput">I</span> as a <a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Dependency Candidate instruction if it reads/write memory or if it has side-effects.</p>


<p>This is used by the dependency graph.</p>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="#a3aacb50005956176b4baba331072edc3">isMemIntrinsic</a>.</p>


<p>Referenced by <a href="#ac1b89d7c178eb196de3d1f05cc205642">isMemDepNodeCandidate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a08f05f0c0f1ba57bd86262ea33748cec">llvm::sandboxir::isOrdered</a>.</p>

</div>
</div>

### isMemDepNodeCandidate() {#ac1b89d7c178eb196de3d1f05cc205642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DGNode::isMemDepNodeCandidate (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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

<p>\Returns true if <span class="doxyComputerOutput">I</span> is a memory dependency candidate instruction.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a>, <a href="#acc1fd672c351e106798e5c147726c33a">isFenceLike</a>, <a href="#a2e539bf766322a8813af1cbe288b8332">isMemDepCandidate</a>, <a href="#ad6ebd81638e4b1036804e15f659c22fa">isStackSaveOrRestoreIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/allocainst/#a08a7e741e6857ca3418b3700f35868d8">llvm::sandboxir::AllocaInst::isUsedWithInAlloca</a>.</p>


<p>Referenced by <a href="#a1513b646d997815c116f387fbc0c1f79">DGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnodeintervalbuilder/#a5a0f15c37075c267f196cf8b7924e972">llvm::sandboxir::MemDGNodeIntervalBuilder::getBotMemDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph/#ab738214b8747fd2e0d9429149718b286">llvm::sandboxir::DependencyGraph::getOrCreateNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnodeintervalbuilder/#a99dd801df4d1697edd4ddd637666c084">llvm::sandboxir::MemDGNodeIntervalBuilder::getTopMemDGNode</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#aaca93c4d946ee53558d24b87a1d131ad">llvm::sandboxir::MemDGNode::MemDGNode</a>.</p>

</div>
</div>

### isMemIntrinsic() {#a3aacb50005956176b4baba331072edc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DGNode::isMemIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/intrinsicinst">IntrinsicInst</a> * I)</td>
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

<p>\Returns true if intrinsic <span class="doxyComputerOutput">I</span> touches memory.</p>


<p>This is used by the dependency graph.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a>.</p>


<p>Referenced by <a href="#acc1fd672c351e106798e5c147726c33a">isFenceLike</a> and <a href="#a2e539bf766322a8813af1cbe288b8332">isMemDepCandidate</a>.</p>

</div>
</div>

### isStackSaveOrRestoreIntrinsic() {#ad6ebd81638e4b1036804e15f659c22fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::DGNode::isStackSaveOrRestoreIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a476b7ce8aae2be423ff92d723e80c1ff">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="#ac1b89d7c178eb196de3d1f05cc205642">isMemDepNodeCandidate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
