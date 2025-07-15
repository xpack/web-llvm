---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mergefunctions-cpp-/mergefunctions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MergeFunctions` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-mergefunctions-cpp-/mergefunctions">MergeFunctions</a> finds functions which will generate identical machine code, by considering all pointer types to be equivalent. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MergeFunctions.cpp}::MergeFunctions { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad74a3aee171cdcc05c28a201f8854887">FnTreeType</a> = std::set&lt; <a href="/web-llvm/docs/api/classes/anonymous-mergefunctions-cpp-/functionnode">FunctionNode</a>, FunctionNodeCmp &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c2c4b0501bdf0eb89a4381b1b59847">MergeFunctions</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncContainer&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad80b4f9594715a13974975d74f3e9ab">run</a> (FuncContainer &amp;Functions)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37dbaa9a80d1003647156618417fb5bd">runOnFunctions</a> (ArrayRef&lt; Function * &gt; F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 4 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15330f4089b1805c2a3ef44538328e09">getUsed</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FuncContainer&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26bdde77fef54fd9ec15d9f51e1828e8">run</a> (FuncContainer &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e0e74fc74170d92ad72682d74d99ee8">doFunctionalCheck</a> (std::vector&lt; WeakTrackingVH &gt; &amp;Worklist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks the rules of order relation introduced among functions set. <a href="#a1e0e74fc74170d92ad72682d74d99ee8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1a765254cc82909b7de031c32ba5ac">insert</a> (Function *NewFunction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a ComparableFunction into the FnTree, or merge it away if it's equal to one that's already present. <a href="#a5c1a765254cc82909b7de031c32ba5ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3c22b35020364b5ff8a5afd5a49b987">remove</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> from the FnTree and queue it up for a second sweep of analysis. <a href="#af3c22b35020364b5ff8a5afd5a49b987">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7ddffd2d4858161515c8599d29a96ac">removeUsers</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the functions that use this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> and remove them from FnTree and queue the functions. <a href="#ab7ddffd2d4858161515c8599d29a96ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648474279cd5091c388d53ebf4ffe244">replaceDirectCallers</a> (Function *Old, Function *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all direct calls of Old with calls of New. <a href="#a648474279cd5091c388d53ebf4ffe244">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d59a1d579c774ae134497d1287f6a1f">mergeTwoFunctions</a> (Function *F, Function *G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge two equivalent functions. <a href="#a5d59a1d579c774ae134497d1287f6a1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87377bc8213a08b0496cbaf488d8c1e3">filterInstsUnrelatedToPDI</a> (BasicBlock *GEntryBlock, std::vector&lt; Instruction * &gt; &amp;PDIUnrelatedWL, std::vector&lt; DbgVariableRecord * &gt; &amp;PDVRUnrelatedWL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fill PDIUnrelatedWL with instructions from the entry block that are unrelated to parameter related debug info. <a href="#a87377bc8213a08b0496cbaf488d8c1e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542c927f8b9efe2d2ccaf5e6290bd374">eraseTail</a> (Function *G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase the rest of the CFG (i.e. barring the entry block). <a href="#a542c927f8b9efe2d2ccaf5e6290bd374">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc17e17ae7b1f29dc368001cdc441b6">eraseInstsUnrelatedToPDI</a> (std::vector&lt; Instruction * &gt; &amp;PDIUnrelatedWL, std::vector&lt; DbgVariableRecord * &gt; &amp;PDVRUnrelatedWL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase the instructions in PDIUnrelatedWL as they are unrelated to the parameter debug info, from the entry block. <a href="#a7cc17e17ae7b1f29dc368001cdc441b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ad0ab198d56eb3a45448eea544e3f7">writeThunk</a> (Function *F, Function *G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace G with a simple tail call to bitcast(F). <a href="#a85ad0ab198d56eb3a45448eea544e3f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab608e133c2395968f9f8d7be5def3406">writeAlias</a> (Function *F, Function *G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0692a212e79396bcd5a141bdac31da71">writeThunkOrAlias</a> (Function *F, Function *G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa639c86f8cf838c72cda465999a3e869">replaceFunctionInTree</a> (const FunctionNode &amp;FN, Function *G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace function F with function G in the function tree. <a href="#aa639c86f8cf838c72cda465999a3e869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalnumberstate">GlobalNumberState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69c3c1dd7302a48584e65f93302a865d">GlobalNumbers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584f237d5f9cb2ae2abee4e35125d99d">Deferred</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A work queue of functions that may have been modified and should be analyzed again. <a href="#a584f237d5f9cb2ae2abee4e35125d99d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11c644e83999f465eed5c5b24e7814ff">Used</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of values marked as used in llvm.used and llvm.compiler.used. <a href="#a11c644e83999f465eed5c5b24e7814ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">FnTreeType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf17d252b84a23526653bd52a6c69b66">FnTree</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of all distinct functions. <a href="#adf17d252b84a23526653bd52a6c69b66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &gt;, FnTreeType::iterator &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae97cc77872d726ffaaa61f8f01daf6d4">FNodesInTree</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42d05ddb5cc9d19597ce97f24aaf3879">DelToNewMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deleted-New functions mapping. <a href="#a42d05ddb5cc9d19597ce97f24aaf3879">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-mergefunctions-cpp-/mergefunctions">MergeFunctions</a> finds functions which will generate identical machine code, by considering all pointer types to be equivalent.</p>


<p>Once identified, <a href="/web-llvm/docs/api/classes/anonymous-mergefunctions-cpp-/mergefunctions">MergeFunctions</a> will fold them by replacing a call to one to a call to a bitcast of the other.</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FnTreeType {#ad74a3aee171cdcc05c28a201f8854887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MergeFunctions.cpp}::MergeFunctions::FnTreeType =  std::set&lt;FunctionNode, FunctionNodeCmp&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MergeFunctions() {#a58c2c4b0501bdf0eb89a4381b1b59847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MergeFunctions.cpp}::MergeFunctions::MergeFunctions ()</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getUsed() {#a15330f4089b1805c2a3ef44538328e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt; GlobalValue *, 4 &gt; &amp; MergeFunctions::getUsed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>


<p>Referenced by <a href="#aad80b4f9594715a13974975d74f3e9ab">run</a>.</p>

</div>
</div>

### run() {#aad80b4f9594715a13974975d74f3e9ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncContainer&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MergeFunctions.cpp}::MergeFunctions::run (FuncContainer &amp; Functions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a15330f4089b1805c2a3ef44538328e09">getUsed</a> and <a href="#a37dbaa9a80d1003647156618417fb5bd">runOnFunctions</a>.</p>


<p>Referenced by <a href="#a37dbaa9a80d1003647156618417fb5bd">runOnFunctions</a>.</p>

</div>
</div>

### run() {#a26bdde77fef54fd9ec15d9f51e1828e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FuncContainer&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MergeFunctions.cpp}::MergeFunctions::run (FuncContainer &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp/#ab45a2f57efe11ed48ed4662ca20fed98">asPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp/#a36058dde352777cb9bacab2ec7bd8dd9">isEligibleForMerging</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af18a8188b0254597abea12364ac397a6">llvm::StructuralHash</a>.</p>

</div>
</div>

### runOnFunctions() {#a37dbaa9a80d1003647156618417fb5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; Function *, Function * &gt; MergeFunctions::runOnFunctions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#aad80b4f9594715a13974975d74f3e9ab">run</a>.</p>


<p>Referenced by <a href="#aad80b4f9594715a13974975d74f3e9ab">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### doFunctionalCheck() {#a1e0e74fc74170d92ad72682d74d99ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MergeFunctions::doFunctionalCheck (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; Worklist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks the rules of order relation introduced among functions set.</p>


<p>Returns true, if check has been passed, and false if failed.</p>


<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### eraseInstsUnrelatedToPDI() {#a7cc17e17ae7b1f29dc368001cdc441b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::eraseInstsUnrelatedToPDI (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; PDIUnrelatedWL, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * &gt; &amp; PDVRUnrelatedWL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase the instructions in PDIUnrelatedWL as they are unrelated to the parameter debug info, from the entry block.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PDVRUnrelatedWL</td>
<td class="doxyParamItemDescription"><p>contains the equivalent set of non-instruction debug-info records.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### eraseTail() {#a542c927f8b9efe2d2ccaf5e6290bd374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::eraseTail (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase the rest of the CFG (i.e. barring the entry block).</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### filterInstsUnrelatedToPDI() {#a87377bc8213a08b0496cbaf488d8c1e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::filterInstsUnrelatedToPDI (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * GEntryBlock, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; PDIUnrelatedWL, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * &gt; &amp; PDVRUnrelatedWL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fill PDIUnrelatedWL with instructions from the entry block that are unrelated to parameter related debug info.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PDVRUnrelatedWL</td>
<td class="doxyParamItemDescription"><p>The equivalent non-intrinsic debug records.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### insert() {#a5c1a765254cc82909b7de031c32ba5ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MergeFunctions::insert (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * NewFunction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a ComparableFunction into the FnTree, or merge it away if it's equal to one that's already present.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### mergeTwoFunctions() {#a5d59a1d579c774ae134497d1287f6a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::mergeTwoFunctions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge two equivalent functions.</p>


<p>Upon completion, G may be deleted, or may be converted into a thunk. In either case, it should never be visited again.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### remove() {#af3c22b35020364b5ff8a5afd5a49b987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::remove (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> from the FnTree and queue it up for a second sweep of analysis.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### removeUsers() {#ab7ddffd2d4858161515c8599d29a96ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::removeUsers (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the functions that use this <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> and remove them from FnTree and queue the functions.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### replaceDirectCallers() {#a648474279cd5091c388d53ebf4ffe244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::replaceDirectCallers (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace all direct calls of Old with calls of New.</p>


<p>Will bitcast New if necessary to make types match.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### replaceFunctionInTree() {#aa639c86f8cf838c72cda465999a3e869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::replaceFunctionInTree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-mergefunctions-cpp-/functionnode">FunctionNode</a> &amp; FN, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace function F with function G in the function tree.</p>


<p>Replace function F by function G.</p>


<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### writeAlias() {#ab608e133c2395968f9f8d7be5def3406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::writeAlias (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### writeThunk() {#a85ad0ab198d56eb3a45448eea544e3f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergeFunctions::writeThunk (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace G with a simple tail call to bitcast(F).</p>


<p>Also (unless MergeFunctionsPDI holds) replace direct uses of G with bitcast(F), delete G.</p>


<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### writeThunkOrAlias() {#a0692a212e79396bcd5a141bdac31da71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MergeFunctions::writeThunkOrAlias (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Deferred {#a584f237d5f9cb2ae2abee4e35125d99d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;WeakTrackingVH&gt; anonymous{MergeFunctions.cpp}::MergeFunctions::Deferred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A work queue of functions that may have been modified and should be analyzed again.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### DelToNewMap {#a42d05ddb5cc9d19597ce97f24aaf3879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Function *, Function *&gt; anonymous{MergeFunctions.cpp}::MergeFunctions::DelToNewMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deleted-New functions mapping.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### FNodesInTree {#ae97cc77872d726ffaaa61f8f01daf6d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AssertingVH&lt;Function&gt;, FnTreeType::iterator&gt; anonymous{MergeFunctions.cpp}::MergeFunctions::FNodesInTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### FnTree {#adf17d252b84a23526653bd52a6c69b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FnTreeType anonymous{MergeFunctions.cpp}::MergeFunctions::FnTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of all distinct functions.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the insert() and remove() methods to modify it. The map allows efficient lookup and deferring of Functions.</p>


<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### GlobalNumbers {#a69c3c1dd7302a48584e65f93302a865d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalNumberState anonymous{MergeFunctions.cpp}::MergeFunctions::GlobalNumbers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

### Used {#a11c644e83999f465eed5c5b24e7814ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;GlobalValue *, 4&gt; anonymous{MergeFunctions.cpp}::MergeFunctions::Used</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of values marked as used in llvm.used and llvm.compiler.used.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">MergeFunctions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
