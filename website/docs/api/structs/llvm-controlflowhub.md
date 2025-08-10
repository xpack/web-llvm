---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/controlflowhub
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ControlFlowHub` Struct

<p>Given a set of branch descriptors [BB, Succ0, Succ1], create a "hub" such that the control flow from each BB to a successor is now split into two edges, one from BB to the hub and another from the hub to the successor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ControlFlowHub { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/controlflowutils-h">llvm/Transforms/Utils/ControlFlowUtils.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef132a79cbc9fc2395fe9696dd654f8e">addBranch</a> (BasicBlock *BB, BasicBlock *Succ0, BasicBlock *Succ1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e3b2ee272be893fb7d474a5530705c">finalize</a> (DomTreeUpdater *DTU, SmallVectorImpl&lt; BasicBlock * &gt; &amp;GuardBlocks, const StringRef Prefix, std::optional&lt; unsigned &gt; MaxControlFlowBooleans=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/branchdescriptor">BranchDescriptor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb601381bd0802bd08681776eeb7d297">Branches</a></td>
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

<p>Given a set of branch descriptors [BB, Succ0, Succ1], create a "hub" such that the control flow from each BB to a successor is now split into two edges, one from BB to the hub and another from the hub to the successor.</p>


<p>The hub consists of a series of guard blocks, one for each outgoing block. Each guard block conditionally branches to the corresponding outgoing block, or the next guard block in the chain. These guard blocks are returned in the argument vector.</p>


<p>This also updates any PHINodes in the successor. For each such <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, the operands corresponding to incoming blocks are moved to a new <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> in the hub, and the hub is made an operand of the original <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>.</p>


<p>Note that for some block BB with a conditional branch, it is not necessary that both successors are rerouted. The client specifies this by setting either Succ0 or Succ1 to nullptr, in which case, the corresponding successor is not rerouted.</p>



### Input CFG: {#autotoc_md59}



<pre><code>               Def
                |
                v
      In1      In2
       |        |
       |        |
       v        v
</code></pre>


<p>Foo ---&gt; Out1 Out2 | v <a href="/web-llvm/docs/api/classes/llvm/use">Use</a></p>



### Create hub: Incoming = {In1, In2}, Outgoing = {Out1, Out2} {#autotoc_md60}



<pre><code>        Def
         |
         v
</code></pre>


<p>In1 In2 Foo | Hub | | | + - - | - - + | | ' v ' V +------&gt; Guard1 -----&gt; Out1 ' | ' ' v ' ' Guard2 -----&gt; Out2 ' ' |</p>


<ul class="doxyList ">
<li>- - - - - + | v <a href="/web-llvm/docs/api/classes/llvm/use">Use</a></li>
</ul>


### Limitations: {#autotoc_md61}


<ol class="doxyList" type="1">
<li>This assumes that all terminators in the CFG are direct branches (the "br" instruction). The presence of any other control flow such as indirectbr, switch or callbr will cause an assert.</li>
<li>The updates to the PHINodes are not sufficient to restore SSA form. Consider a definition Def, its use <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>, incoming block In2 and outgoing block Out2, such that: a. In2 is reachable from D or contains D. b. U is reachable from Out2 or is contained in Out2. c. U is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> if U is contained in Out2.

Clearly, Def dominates Out2 since the program is valid SSA. But when the hub is introduced, there is a new path through the hub along which <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> is reachable from entry without passing through Def, and SSA is no longer valid. To fix this, we need to look at all the blocks post-dominated by the hub on the one hand, and dominated by Out2 on the other. This is left for the caller to accomplish, since each specific use of this function may have additional information which simplifies this fixup. For example, see <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#aaaff4f2206ebf29a0a8e629835ca1973">restoreSSA()</a> in the UnifyLoopExits pass.</li>
</ol>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/controlflowutils-h">ControlFlowUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addBranch() {#aef132a79cbc9fc2395fe9696dd654f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ControlFlowHub::addBranch (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Succ0, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Succ1)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/controlflowutils-h">ControlFlowUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#adb601381bd0802bd08681776eeb7d297">Branches</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#ad914c82e07de4044a3314a5d03c5b85a">fixIrreducible</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a91d961bc77edfba4fb721c6637c0c6ed">unifyLoopExits</a>.</p>

</div>
</div>

### finalize() {#a14e3b2ee272be893fb7d474a5530705c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * ControlFlowHub::finalize (<a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; GuardBlocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix, std::optional&lt; unsigned &gt; MaxControlFlowBooleans=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/controlflowutils-h">ControlFlowUtils.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp">ControlFlowUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a363d442ff7f9a13eafaee275aad9f54c">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a475a23ed9737641ade0a2f0dab1f19d0">llvm::SetVector&lt; T, Vector, Set, N &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="#adb601381bd0802bd08681776eeb7d297">Branches</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a99b699ca919e40ac78708ea425fbfa98">convertToGuardPredicates</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a71c91cbbfc1c0ecf9a69e10ccf739bd7">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Delete</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a2309608beb7af149f7bf6158319ecfdb">llvm::SetVector&lt; T, Vector, Set, N &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a0c7d0dae14eb8a5916fff9f72d8b46d2">llvm::SetVector&lt; T, Vector, Set, N &gt;::getArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a9aeeca2833810f01b20545a46fe22503">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a1f69c303174793beec42b1ebaf13cfb6">reconnectPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#ad914c82e07de4044a3314a5d03c5b85a">fixIrreducible</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a91d961bc77edfba4fb721c6637c0c6ed">unifyLoopExits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Branches {#adb601381bd0802bd08681776eeb7d297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BranchDescriptor&gt; llvm::ControlFlowHub::Branches</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/controlflowutils-h">ControlFlowUtils.h</a>.</p>


<p>Referenced by <a href="#aef132a79cbc9fc2395fe9696dd654f8e">addBranch</a> and <a href="#a14e3b2ee272be893fb7d474a5530705c">finalize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/controlflowutils-h">ControlFlowUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp">ControlFlowUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
