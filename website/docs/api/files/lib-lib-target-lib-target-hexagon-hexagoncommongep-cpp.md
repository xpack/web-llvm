---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `HexagonCommonGEP.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">llvm/ADT/FoldingSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">llvm/ADT/GraphTraits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/postdominators-h">llvm/Analysis/PostDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">llvm/Support/Allocator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;map&gt;
#include &lt;set&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-hexagoncommongep-cpp-">anonymous{HexagonCommonGEP.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/false">false</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagoncommongep-cpp-/nodeordering">NodeOrdering</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagoncommongep-cpp-/hexagoncommongep">HexagonCommonGEP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/false/gepnode">GepNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/false/in-set">in_set</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagoncommongep-cpp-/locationasblock">LocationAsBlock</a></td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ec00a614664e0ab1ea83513a9d6bc4">operator new</a> (size_t, SpecificBumpPtrAllocator&lt; GepNode &gt; &amp;A)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57fa9ac6cd9430d8538c67be931255d">INITIALIZE_PASS_BEGIN</a> (HexagonCommonGEP, "hcommgep", "Hexagon Common GEP", false, false) INITIALIZE_PASS_END(HexagonCommonGEP</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670b2ca76a46e31c94528f34ebf849c8">invert_find_roots</a> (const NodeVect &amp;Nodes, NodeChildrenMap &amp;NCM, NodeVect &amp;Roots)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad675cfabbe3548ea7f9b06c3518c0656">nodes_for_root</a> (GepNode *Root, NodeChildrenMap &amp;NCM, NodeSet &amp;Nodes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/nodeset">NodeSet</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21cbbab6a6991f925afed97ead5bbf49">node_class</a> (GepNode *N, NodeSymRel &amp;Rel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static NodePair</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f2c9c1625f4e3c68c38e480df1b44a">node_pair</a> (GepNode *N1, GepNode *N2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024b67de8e1a0251f785d326118fc7fb">node_hash</a> (GepNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d49d1a5a29512386e2fa1226e982e00">node_eq</a> (GepNode *N1, GepNode *N2, NodePairSet &amp;Eq, NodePairSet &amp;Ne)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa715758b669411461023dd64ef038e2a">nearest_common_dominator</a> (DominatorTree *DT, T &amp;Blocks)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ddbec9e8a91a1d6a95110e5a197cde2">nearest_common_dominatee</a> (DominatorTree *DT, T &amp;Blocks)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd30b52c6e2ff0b9944201abcab34c45">first_use_of_in_block</a> (T &amp;Values, BasicBlock *B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee4d1dab7d36d8f7a2b1d979daef153">is_empty</a> (const BasicBlock *B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecea88f231914d2a6dc7ecf19a57f583">preheader</a> (DominatorTree *DT, Loop *L)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59df2ce3f3ae760637f23bfad489ff25">OptSpeculate</a>("commgep-speculate", cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0584340a79c4953a406c2cd7e5f93098">OptEnableInv</a>("commgep-inv", cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7641bfec93490ebd4f8667160ce2fc">OptEnableConst</a>("commgep-const", cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9b445b570e8440b849bd3c02c577633">hcommgep</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Hexagon Common</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad532e8710e50302e0a376b61c91fa91d">GEP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Hexagon Common</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed40187e4847faa6700b946d3f12b2c">false</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"commgep"</td>
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


<div class="doxySectionDef">

## Operators

### operator new() {#a00ec00a614664e0ab1ea83513a9d6bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * operator new (size_t, <a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; GepNode &gt; &amp; A)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### first\_use\_of\_in\_block() {#afd30b52c6e2ff0b9944201abcab34c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator first_use_of_in_block (T &amp; Values, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B)</td>
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



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#ab57fa9ac6cd9430d8538c67be931255d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (HexagonCommonGEP, "hcommgep", "Hexagon Common GEP", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### invert\_find\_roots() {#a670b2ca76a46e31c94528f34ebf849c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void invert_find_roots (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeVect &amp; Nodes, NodeChildrenMap &amp; NCM, NodeVect &amp; Roots)</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### is\_empty() {#abee4d1dab7d36d8f7a2b1d979daef153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool is_empty (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B)</td>
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



<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### nearest\_common\_dominatee() {#a3ddbec9e8a91a1d6a95110e5a197cde2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * nearest_common_dominatee (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, T &amp; Blocks)</td>
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



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a81f7fe4844c408d799428082f599c40b">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### nearest\_common\_dominator() {#aa715758b669411461023dd64ef038e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * nearest_common_dominator (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, T &amp; Blocks)</td>
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



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a2ec50ab2c78eff965caf3da71cd08be4">llvm::DominatorTree::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### node\_class() {#a21cbbab6a6991f925afed97ead5bbf49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeSet * node_class (GepNode * N, NodeSymRel &amp; Rel)</td>
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



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### node\_eq() {#a1d49d1a5a29512386e2fa1226e982e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool node_eq (GepNode * N1, GepNode * N2, NodePairSet &amp; Eq, NodePairSet &amp; Ne)</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>References <a href="#a1d49d1a5a29512386e2fa1226e982e00">node_eq</a>, <a href="#a024b67de8e1a0251f785d326118fc7fb">node_hash</a>, <a href="#a18f2c9c1625f4e3c68c38e480df1b44a">node_pair</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a1d49d1a5a29512386e2fa1226e982e00">node_eq</a>.</p>

</div>
</div>

### node\_hash() {#a024b67de8e1a0251f785d326118fc7fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned node_hash (GepNode * N)</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a1d49d1a5a29512386e2fa1226e982e00">node_eq</a>.</p>

</div>
</div>

### node\_pair() {#a18f2c9c1625f4e3c68c38e480df1b44a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodePair node_pair (GepNode * N1, GepNode * N2)</td>
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



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>Referenced by <a href="#a1d49d1a5a29512386e2fa1226e982e00">node_eq</a>.</p>

</div>
</div>

### nodes\_for\_root() {#ad675cfabbe3548ea7f9b06c3518c0656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void nodes_for_root (GepNode * Root, NodeChildrenMap &amp; NCM, <a href="/web-llvm/docs/api/classes/llvm/nodeset">NodeSet</a> &amp; Nodes)</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/nodeset/#aba49350c71f099c58053900c4250b417">llvm::NodeSet::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### preheader() {#aecea88f231914d2a6dc7ecf19a57f583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * preheader (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNode</a> and <a href="#a59df2ce3f3ae760637f23bfad489ff25">OptSpeculate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#abed40187e4847faa6700b946d3f12b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hexagon Common false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>

</div>
</div>

### GEP {#ad532e8710e50302e0a376b61c91fa91d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hexagon Common GEP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#aec8a5b489575aed066c15608ea3b9b81">anonymous{InlineCost.cpp}::CallAnalyzer::accumulateGEPOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a6396da6d0b65cef8693b0aedd06f31e3">llvm::SystemZTTIImpl::adjustInliningThreshold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#aa863110e9781bd6febba48dd5b5af5ab">allZeroIndices</a>, <a href="/web-llvm/docs/api/structs/llvm/poisonflags/#a98fdca1dc2f737080807f8e72b52b3d9">llvm::PoisonFlags::apply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a90036e9bed7ce7e86007bd8d83dd2d21">aspaceWrapValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a41f4145f819d062ed7c74067ad334808">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::buildLookup</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#ae277c85704c17a21f772da0aee54fbaa">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildNonKernelLDSBaseTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a4d5937fb63dff47c2112c8032650019b">calculateGEPOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aa5aa60eda03a6732ad5c06a8fc6bf97b">calculateVectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7d784ad1fd74a55994d44d0d3ac39b5e">llvm::FastISel::canFoldAddIntoGEP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#ae3d9d3b5408e22143d8aee0d684454c4">anonymous{AssumeBundleBuilder.cpp}::canonicalizedKnowledge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a856d46e90d7159a88c175ceff667f40c">canonicalizeGEPOfConstGEPI8</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9e6b15b1005dd460a35359f104cb06fe">canRewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aaa14b4fc802d9aa388b369deb1a1ef60">chainToBasePointerCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#aa89462fcd72ee43d1b3f2df0a61a698e">checkOverflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ac3cf098d54027ac28278b060376bdcbd">CleanupConstantGlobalUsers</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#ab0236d3f5f443260abf1ccfb1e5cc5a6">anonymous{FunctionAttrs.cpp}::collectArgumentUsesPerBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a1e5d35d93b0a1cd5f85018b1a98a883f">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::collectConstantsForGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a74bfb3b0492b90d4a296f4e0f131877c">collectOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4062c17e282cb2667cf0d52150c67fea">collectSRATypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a02541afb885f658a4f9ed304ba4bb5e9">combineAndLoadToBZHI</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a38a01001593bf75700ee024b15bdf413">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialFromPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f6c692bb79cca65ae3097ddd4c47e69">llvm::ConstantFoldExtractElementInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ae6e1699b7b98eaaf080f652b08792b9f">anonymous{ConstantFolding.cpp}::ConstantFoldInstOperandsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a944b77cb28ad77cdf28380c4453f8d02">convertToParamAS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a1542efe32b9a597a7d72d3b205dab176">convertToRelLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8fa9ad46c9ec8c4de6dca3245edeedfe">llvm::MachineInstr::copyFlagsFromInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#a3d3c00f50ccf7d2e10a5fc6ad4a07955">countNumMemAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#abbe450337ee726cf63054b5207c4d4c5">llvm::GetElementPtrInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#abe3945bfefe671a9a34f864d493d5fe7">decompose</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a3a288d8153f8bd74315b59636438d6e2">decomposeGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67aa349e8bb1aefc2a8a6ca18be9b87c">llvm::emitGEPOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a1b84446d2e199358a8406e7c92f51f03">llvm::VPWidenGEPRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/anonymous-separateconstoffsetfromgep-cpp-/constantoffsetextractor/#a867434c3e87f84340731c31c5e1b863d">anonymous{SeparateConstOffsetFromGEP.cpp}::ConstantOffsetExtractor::Extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a35c9927607481d33c2093c2b7d643e80">fillCommonArgs</a>, <a href="/web-llvm/docs/api/classes/anonymous-separateconstoffsetfromgep-cpp-/constantoffsetextractor/#aaffc55116f7466c3676d8852dc95175d">anonymous{SeparateConstOffsetFromGEP.cpp}::ConstantOffsetExtractor::Find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21fe87bf00db76089c043fed6a23fb76">llvm::findAllocaForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#af276809421b9e562341d3c420ff29712">findBaseDefiningValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa421c7018618b7f06cab7230bf12f872">findBaseDefiningValueOfVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf87a16be872504ce4d0ab9714dc6217">llvm::findHistogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typemetadatautils-cpp/#a5b42cb0df93187fef9fa135a5d14a06a">findLoadCallsAtConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa2d8fa2ef0e7ead8200cad6bd101af3e">findRematerializableChainToBasePointer</a>, <a href="/web-llvm/docs/api/groups/arcutilities/#gaf231df4dd6fb738c1f548aedb34ca81e">FindSingleUseIdentifiedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a3ef88a20b7b51243e963ed25e0e0c30e">foldDependentIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a37f98e168f7cc70d180aa6bed1625c87">foldGEPChainAsStructAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a222f3ff6cc88e36df2f31491a77c102a">foldGEPChainAsU8Access</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78688f28e25e6d68d3f06ddf6e7aac0f">llvm::InstCombinerImpl::foldICmpCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d58c11c9787c2764e5f11bb127ced00">llvm::InstCombinerImpl::foldICmpInstWithConstantNotInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a16a66955e366f83c6e35d99511a33167">foldSelectGEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a281dd141a9046b838c57d5f78a7580ec">llvm::gep_type_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac828b9b52935f87659a4adf237f820a3">llvm::gep_type_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a06b015ef2bac11ff6eea0dbe3b26befb">llvm::gep_type_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43c6ebb4fd35ebd815d66a2df4eed0b9">llvm::gep_type_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ac3e586008202db1f802e906a489d7574">GEPSequentialConstIndexed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#a8f3e4fda4ce5ab01260df66b88ebabd3">GEPToVectorIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a8d9ad0ef3d9122df6d6b4007c519c61e">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getAddressesOfVariablesInKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0af04c89840d424b7b33ae71d7c8cd28">llvm::ConstantExpr::getAlignOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#aa831f0a1520a405a32196cb32ec24084">getBaseType</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a91b2338794e62fc6ce61482b9bc1cde9">llvm::ARMTTIImpl::getGatherScatterOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a0f3039f831c483956c153ed9dee23dba">llvm::ScalarEvolution::getGEPExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0e431b29d5cd842ab00f85ec2cdab8b2">getGEPSmallConstantIntOffsetV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8287f8eaeb936bb75dc1bb6ef39fbdd1">llvm::getIndexExpressionsFromGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a5d4d9464721afd6bb6956c909c852bde">anonymous{AttributorAttributes.cpp}::getKnownAlignForUse</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9b1fee580716dee9404fc4e20c486392">llvm::X86TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a513e443b4a433b36c8d325032a2fbc1c">getOptimizationFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#aa967d704c27dcdee676c18b508e8a5f2">llvm::RISCVTTIImpl::getPointersChainCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a824c5127d35e6fc5004e7595959a5a55">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getPointersChainCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7144f12bd93229efcf87a052ab80d5e6">getSalvageOpsForGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a778163e6ec80716a12ab3282cb97f0d9">llvm::ConstantExpr::getSizeOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#ac1fce2baaba15c35a2bb18563ef08678">getStrideAndModOffsetOfGEP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a9e2a2220c5be86abe862aacbcf5030f8">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getTranslatedGlobalMemoryGEPOfLDSPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3e8b055fdb7e07479b83d69c15211d54">getUniformBase</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a0ea8063abb874faff99f39c4e849f8de">HasAddressTaken</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/straightlinestrengthreduce-cpp/#a194fc28e3e9aa788b53248cf4b19a515">hasOnlyOneNonZeroIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/operator/#a7fe2763bf9a8bee996a114f061736dc7">llvm::Operator::hasPoisonGeneratingFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a062c93def88f99e93047ba86970c4eab">hoistGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#ad7518d710d81c7c4c04cc6a61e7d65bc">llvm::IRSimilarity::isClose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3103683ccd8b97050f821110b98ad2">llvm::IsConstantOffsetFromGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#a3e49ed1824b63334071840d20aab03ba">isDereferenceableAndAlignedPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1a0282efdd962c35bc840b90bafeb35b">isFoldableInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ade8f600187cb9c664701443e796111e7">llvm::isGEPBasedOnPointerToString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/naryreassociate-cpp/#a66a15c1f8726876e5a4de283c6d3564d">isGEPFoldable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/straightlinestrengthreduce-cpp/#a66a15c1f8726876e5a4de283c6d3564d">isGEPFoldable</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a6cd79b520cf0ecc13ef7f9fe36db74fc">anonymous{InlineCost.cpp}::CallAnalyzer::isGEPFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab9ee1d3249435d1130a87d064d13857d">isGEPKnownNonNull</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a55232923939cd416fa4b1d1aad06cd2a">anonymous{DeadStoreElimination.cpp}::DSEState::isGuaranteedLoopInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a24010a1eb5e99f1a4ace051c293a401f">isKnownTypeIdMember</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a9d9847ba3ad2bc2837b041581277a8fb">isNoWrapAddRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#ae1c9444bcb6b157e8f8c4ec8bf265010">isOnlyCopiedFromConstantMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#afc00f27e00d04515eed04435def6d8fd">isPointerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp/#ad83e09e9f97995f00b7200b604edd436">IsPtrInBounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a6b46ea77082dda0b24b9fea490ae8fc8">isSafeAndProfitableToSinkLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a02c022baa01fdb4920060a670898b55a">IsSafeComputationToRemove</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantexpressions/#gaa025b4042992fcb4ee0a8495cebb32ba">LLVM_ATTRIBUTE_C_DEPRECATED</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructiongetelementpointer/#gaaabb47a8c98e8ec1c796b581928b4a98">LLVMGEPGetNoWrapFlags</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructiongetelementpointer/#ga8d86920b4e3ea2b38b297146f0bff606">LLVMGEPSetNoWrapFlags</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructiongetelementpointer/#ga1e623a49010f40ef27a4a7a955648898">LLVMGetGEPSourceElementType</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructioninsertvalue/#gabdcae5a93cfc74e4dbb5099855bb6435">LLVMGetNumIndices</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructiongetelementpointer/#ga46b2ca9ca0163ea0754ff5a38153d76b">LLVMIsInBounds</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructiongetelementpointer/#ga79a9cd9ca8d78e911071f4300ce9e460">LLVMSetIsInBounds</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a5d31f8dc135425bc0f938f13bcca4a0a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::loadMatrix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a8f69a29bf679c53a8703f5497bba92b2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerDynamicLDSVariables</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a0106bab2d4d5ef7149415e2af1dfb180">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::lowerFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a4cb889cf1f4cfbef0ae51eb6ee0e300f">makeGEPAndLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a49ff1486c1f55a643e7b59e7ea3a3ad5">makeGEPAndStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfaspacecastsimplifypass-cpp-/castgepcast/#ac868ac3d1fb9f763763f1f5f7bf35569">anonymous{BPFASpaceCastSimplifyPass.cpp}::CastGEPCast::match</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/ptradd-match/#adf6040f416775fc090cd26ca84fec1ce">llvm::PatternMatch::PtrAdd_match&lt; PointerOpTy, OffsetOpTy &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/vscaleval-match/#a9527ea0b64d646ba37e50d0a96ce87e9">llvm::PatternMatch::VScaleVal_match::match</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/offsetresult/#a8bf18b020aab0c85a442720c9d68e680">anonymous{ConstraintElimination.cpp}::OffsetResult::OffsetResult</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a4d9b426f332b379758b891f032f85d52">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::paintOrigin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a32c2973fa0babdd440d3ab7dd160664a">passingValueIsAlwaysUndefined</a>, <a href="/web-llvm/docs/api/structs/llvm/poisonflags/#a9bafefee99bbf3320fd4e5af1e487149">llvm::PoisonFlags::PoisonFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#abff89c097ca3eb3d820b684175b4008f">reconstructCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a993bbcce0f95684b4ec50194f4a498c5">reconstructGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfpreservestaticoffsetpass/#ad8b5905523204667cdaf17629a69a82e">llvm::BPFPreserveStaticOffsetPass::reconstructLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfpreservestaticoffsetpass/#a509bd79859ed851dc0a1aa4c437b97b8">llvm::BPFPreserveStaticOffsetPass::reconstructStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a66c07f0f69fee1125fecb13109da5c7b">anonymous{ValueMapper.cpp}::Mapper::remapInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a36fe1ed1682023b7fb3c4699f9009d31">removePAICalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a547d3856bc525978c9c94694b2f8cb20">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::replaceKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp/#a36be37a99f7cf2fdd84b942e5dafba1b">replaceWithGEP</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfaspacecastsimplifypass-cpp-/castgepcast/#ab558890ee34084040e962c122ddd83f4">anonymous{BPFASpaceCastSimplifyPass.cpp}::CastGEPCast::rewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a732f3ff01555ec522134bf060270c1ae">rewriteAccessChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0aa7c68d8c3095ffc271ecceab16c86e">rewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#aad2771f632ae6d8a0c58563162e29f99">rsrcPartRoot</a>, <a href="/web-llvm/docs/api/classes/anonymous-separateconstoffsetfromgep-cpp-/separateconstoffsetfromgep/#ad12e0825707a4d103c8475716b10ecf5">anonymous{SeparateConstOffsetFromGEP.cpp}::SeparateConstOffsetFromGEP::run</a>, <a href="/web-llvm/docs/api/structs/llvm/jumptabletoswitchpass/#a84778fc53894f05e88ce0cc794561742">llvm::JumpTableToSwitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/typefinder/#a76e63ec5dc3405d799590195281313e2">llvm::TypeFinder::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilprepare-cpp-/dxilpreparemodule/#a6bcc20d3d2e7ec05e259efe87ba8fd0c">anonymous{DXILPrepare.cpp}::DXILPrepareModule::runOnModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a021e32e2bf67f331d9384a162dc402c2">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeCheckedLoadUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a48d49b8df95d21ba931f3642c1f5a30d">shouldCanonicalizeGEPToPtrAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a004b3a18ad13375ad40e88cd41a0fe97">shouldConvertToRelLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a27dc41c474e5376ef7d1865735cfb3dd">shouldMergeGEPs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a386653f14c41f8ad1f564900b70a608a">shouldSinkVectorOfPtrs</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ac9fae87b41835eff9f16de8aa6b11239">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::storeMatrix</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a0fd3732392fdbdbc5a4436c0f1262999">anonymous{InlineCost.cpp}::CallAnalyzer::stripAndComputeInBoundsConstantOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#aa079180719a27f78e40cfa3f4412a7b2">stripGetElementPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a819ad633d5861ebb80db3c78c57bcfba">StripPointerGEPsAndCasts</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4fc5dce2b300d02414f7b8a99d93d300">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a760fb390c24b907500c0a181fada9590">llvm::VPRecipeBuilder::tryToCreateWidenRecipe</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#aa2e4df71e26ad90b9fd1c6e5ee0ce549">unrollGEPLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a88059267c10e00e4fcbc185400f3146e">unrollGEPStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/valueenumerator/#a462551b180e939bad5a404fc6cb38a9b">llvm::dxil::ValueEnumerator::ValueEnumerator</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a679f36556ace611ccc56580cb497973a">llvm::InstCombinerImpl::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#a8097ebbd1062135df7f1e914cd5f4c62">llvm::ObjectSizeOffsetEvaluator::visitGEPOperator</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#aa99e14a7059ad7f3028d950ac47c6877">anonymous{InlineCost.cpp}::CallAnalyzer::visitGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5417dab7a760eedf39c533b1b31b1b23">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#ae73e475ff9414b97c6ad36f601179133">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a900ef0957c31205735317d246eb68f7c">anonymous{MergeICmps.cpp}::visitICmpLoadOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8042dd4cb7e9772368f2808b8db577be">llvm::InstCombinerImpl::visitStoreInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad210afaefb4884ac5008dd5fbaf1cbf8">llvm::VPlanTransforms::VPInstructionsToVPRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#a76fb233396e6e9451f58b35eb03681da">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#ae1555a62444119fa96252a26dcf4894a">llvm::VPWidenGEPRecipe::VPWidenGEPRecipe</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a2ced856c3217b5902cfc6e22ade76eaa">WriteOptimizationInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a14d35a77d4b1f7036fd49cee4d138f21">llvm::InstCombinerImpl::~InstCombinerImpl</a>.</p>

</div>
</div>

### hcommgep {#ab9b445b570e8440b849bd3c02c577633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hcommgep</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>

</div>
</div>

### OptEnableConst {#a2e7641bfec93490ebd4f8667160ce2fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; OptEnableConst("commgep-const", cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>

</div>
</div>

### OptEnableInv {#a0584340a79c4953a406c2cd7e5f93098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; OptEnableInv("commgep-inv", cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>

</div>
</div>

### OptSpeculate {#a59df2ce3f3ae760637f23bfad489ff25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; OptSpeculate("commgep-speculate", cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>


<p>Referenced by <a href="#aecea88f231914d2a6dc7ecf19a57f583">preheader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"commgep"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp">HexagonCommonGEP.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
