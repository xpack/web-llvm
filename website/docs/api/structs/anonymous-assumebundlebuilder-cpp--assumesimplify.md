---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AssumeSimplify` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c22a60a41f0ab3bfcc6cc605dcfb79">MergeIterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5908a7cf0985b76f3f54efddeea7803d">AssumeSimplify</a> (Function &amp;F, AssumptionCache &amp;AC, DominatorTree *DT, LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac60f8d37c7b1ad8cd553195f0c9414">buildMapping</a> (bool FilterBooleanArgument)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2f2e4897006cc2a16468e9e99f7b6d">RunCleanup</a> (bool ForceCleanup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all asumes in CleanupToDo if there boolean argument is true and ForceCleanup is set or the assume doesn't hold valuable knowledge. <a href="#a0e2f2e4897006cc2a16468e9e99f7b6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0879506ce04a79b173daca40d1967e35">dropRedundantKnowledge</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove knowledge stored in assume when it is already know by an attribute or an other assume. <a href="#a0879506ce04a79b173daca40d1967e35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d8e70094baa4fcc5eb68b59de54dc92">mergeRange</a> (BasicBlock *BB, MergeIterator Begin, MergeIterator End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge all Assumes from Begin to End in and insert the resulting assume as high as possible in the basicblock. <a href="#a0d8e70094baa4fcc5eb68b59de54dc92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">mergeAssumes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge assume when they are in the same <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> and for all instruction between them isGuaranteedToTransferExecutionToSuccessor returns true. <a href="#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91773ebb94d343768746f87dc96e7f70">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79674777a52423b6b582af0f28eba3ec">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d5c818d02979e0da640cc82255485b">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f6c99fef28caba3aa100427e18eeda">C</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c6f8308b4740649275da4a49b43672">CleanupToDo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; uint32_t &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad860d72978ebd7e8e51ec579ddb637d0">IgnoreTag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> *, 4 &gt;, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed99314102d69984c782e8888945bf7d">BBToAssume</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239c7971faca8f43b6528d7bc217b7dd">MadeChange</a> = false</td>
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


<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MergeIterator {#a37c22a60a41f0ab3bfcc6cc605dcfb79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::MergeIterator =  SmallVectorImpl&lt;IntrinsicInst *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AssumeSimplify() {#a5908a7cf0985b76f3f54efddeea7803d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::AssumeSimplify (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="#a79674777a52423b6b582af0f28eba3ec">AC</a>, <a href="#af9f6c99fef28caba3aa100427e18eeda">C</a>, <a href="#a11d5c818d02979e0da640cc82255485b">DT</a>, <a href="#a91773ebb94d343768746f87dc96e7f70">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372ec0fd61fee8a8845f46ccf27c82cf">llvm::IgnoreBundleTag</a> and <a href="#ad860d72978ebd7e8e51ec579ddb637d0">IgnoreTag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildMapping() {#aeac60f8d37c7b1ad8cd553195f0c9414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::buildMapping (bool FilterBooleanArgument)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="#a79674777a52423b6b582af0f28eba3ec">AC</a>, <a href="#aed99314102d69984c782e8888945bf7d">BBToAssume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a0879506ce04a79b173daca40d1967e35">dropRedundantKnowledge</a> and <a href="#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">mergeAssumes</a>.</p>

</div>
</div>

### dropRedundantKnowledge() {#a0879506ce04a79b173daca40d1967e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::dropRedundantKnowledge ()</td>
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

<p>Remove knowledge stored in assume when it is already know by an attribute or an other assume.</p>


<p>This can when valid update an existing knowledge in an attribute or an other assume.</p>


<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af36ce2c8e7a209b35ea79a00f0621852a1db3cb6d53ab5e73d0d8b9e1afaa26ce">llvm::ABA_Argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af36ce2c8e7a209b35ea79a00f0621852a62cb1e392c91b9c6bf2929bf1f6437a4">llvm::ABA_WasOn</a>, <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a3b64a97b9157b9bd9a1d924cae66254b">llvm::RetainedKnowledge::ArgValue</a>, <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a054a26c551d4de8f1af4d75a7a67a42a">llvm::RetainedKnowledge::AttrKind</a>, <a href="#aed99314102d69984c782e8888945bf7d">BBToAssume</a>, <a href="#aeac60f8d37c7b1ad8cd553195f0c9414">buildMapping</a>, <a href="#af9f6c99fef28caba3aa100427e18eeda">C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a34c6f8308b4740649275da4a49b43672">CleanupToDo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="#a11d5c818d02979e0da640cc82255485b">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a91773ebb94d343768746f87dc96e7f70">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5b33634e0aa97435f13845ce7e10411e">llvm::getKnowledgeFromBundle</a>, <a href="#ad860d72978ebd7e8e51ec579ddb637d0">IgnoreTag</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#ac2d5f8ba4215304f89a401248abed393">llvm::Attribute::isIntAttrKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f7c11444c9e7d7c1036ae1f049f4cee">llvm::isValidAssumeForContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#ac28513e2e067144d291d2d8f0301b61a">Lookup</a>, <a href="#a239c7971faca8f43b6528d7bc217b7dd">MadeChange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d7375d2149eafc730d09e8e48089021">llvm::MapValue</a> and <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a99ac6afa72b262e95ceb85328c6cb5c6">llvm::RetainedKnowledge::WasOn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#aa816756908e8f79bdcf1b5871e78a9ca">anonymous{AssumeBundleBuilder.cpp}::simplifyAssumes</a>.</p>

</div>
</div>

### mergeAssumes() {#a1dc2ed29bdcb3fedb0639cc8e88a7ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeAssumes ()</td>
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

<p>Merge assume when they are in the same <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> and for all instruction between them isGuaranteedToTransferExecutionToSuccessor returns true.</p>

<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="#aed99314102d69984c782e8888945bf7d">BBToAssume</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#aeac60f8d37c7b1ad8cd553195f0c9414">buildMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abff5a423c1f45e23958dde8ee695c9a9">llvm::isGuaranteedToTransferExecutionToSuccessor</a>, <a href="#a0d8e70094baa4fcc5eb68b59de54dc92">mergeRange</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#aa816756908e8f79bdcf1b5871e78a9ca">anonymous{AssumeBundleBuilder.cpp}::simplifyAssumes</a>.</p>

</div>
</div>

### mergeRange() {#a0d8e70094baa4fcc5eb68b59de54dc92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeRange (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="#a37c22a60a41f0ab3bfcc6cc605dcfb79">MergeIterator</a> Begin, <a href="#a37c22a60a41f0ab3bfcc6cc605dcfb79">MergeIterator</a> End)</td>
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

<p>Merge all Assumes from Begin to End in and insert the resulting assume as high as possible in the basicblock.</p>

<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="#a79674777a52423b6b582af0f28eba3ec">AC</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a201cb1ede84e08442e7433b7b3eaed69">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addKnowledge</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aadca3692ce40afeb83b7765b2d7dfc9c">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::build</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a34c6f8308b4740649275da4a49b43672">CleanupToDo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a91773ebb94d343768746f87dc96e7f70">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5b33634e0aa97435f13845ce7e10411e">llvm::getKnowledgeFromBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abff5a423c1f45e23958dde8ee695c9a9">llvm::isGuaranteedToTransferExecutionToSuccessor</a>, <a href="#a239c7971faca8f43b6528d7bc217b7dd">MadeChange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a99ac6afa72b262e95ceb85328c6cb5c6">llvm::RetainedKnowledge::WasOn</a>.</p>


<p>Referenced by <a href="#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">mergeAssumes</a>.</p>

</div>
</div>

### RunCleanup() {#a0e2f2e4897006cc2a16468e9e99f7b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::RunCleanup (bool ForceCleanup)</td>
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

<p>Remove all asumes in CleanupToDo if there boolean argument is true and ForceCleanup is set or the assume doesn't hold valuable knowledge.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a34c6f8308b4740649275da4a49b43672">CleanupToDo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4418ab5bfa0defc56f75457a07161472">llvm::isAssumeWithEmptyBundle</a> and <a href="#a239c7971faca8f43b6528d7bc217b7dd">MadeChange</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#aa816756908e8f79bdcf1b5871e78a9ca">anonymous{AssumeBundleBuilder.cpp}::simplifyAssumes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AC {#a79674777a52423b6b582af0f28eba3ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a5908a7cf0985b76f3f54efddeea7803d">AssumeSimplify</a>, <a href="#aeac60f8d37c7b1ad8cd553195f0c9414">buildMapping</a> and <a href="#a0d8e70094baa4fcc5eb68b59de54dc92">mergeRange</a>.</p>

</div>
</div>

### BBToAssume {#aed99314102d69984c782e8888945bf7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;BasicBlock *, SmallVector&lt;IntrinsicInst *, 4&gt;, 8&gt; anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::BBToAssume</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#aeac60f8d37c7b1ad8cd553195f0c9414">buildMapping</a>, <a href="#a0879506ce04a79b173daca40d1967e35">dropRedundantKnowledge</a> and <a href="#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">mergeAssumes</a>.</p>

</div>
</div>

### C {#af9f6c99fef28caba3aa100427e18eeda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::C</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a5908a7cf0985b76f3f54efddeea7803d">AssumeSimplify</a> and <a href="#a0879506ce04a79b173daca40d1967e35">dropRedundantKnowledge</a>.</p>

</div>
</div>

### CleanupToDo {#a34c6f8308b4740649275da4a49b43672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseSet&lt;IntrinsicInst *&gt; anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::CleanupToDo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a0879506ce04a79b173daca40d1967e35">dropRedundantKnowledge</a>, <a href="#a0d8e70094baa4fcc5eb68b59de54dc92">mergeRange</a> and <a href="#a0e2f2e4897006cc2a16468e9e99f7b6d">RunCleanup</a>.</p>

</div>
</div>

### DT {#a11d5c818d02979e0da640cc82255485b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a5908a7cf0985b76f3f54efddeea7803d">AssumeSimplify</a> and <a href="#a0879506ce04a79b173daca40d1967e35">dropRedundantKnowledge</a>.</p>

</div>
</div>

### F {#a91773ebb94d343768746f87dc96e7f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a5908a7cf0985b76f3f54efddeea7803d">AssumeSimplify</a>, <a href="#a0879506ce04a79b173daca40d1967e35">dropRedundantKnowledge</a> and <a href="#a0d8e70094baa4fcc5eb68b59de54dc92">mergeRange</a>.</p>

</div>
</div>

### IgnoreTag {#ad860d72978ebd7e8e51ec579ddb637d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntry&lt;uint32_t&gt;* anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::IgnoreTag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a5908a7cf0985b76f3f54efddeea7803d">AssumeSimplify</a> and <a href="#a0879506ce04a79b173daca40d1967e35">dropRedundantKnowledge</a>.</p>

</div>
</div>

### MadeChange {#a239c7971faca8f43b6528d7bc217b7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::MadeChange = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a0879506ce04a79b173daca40d1967e35">dropRedundantKnowledge</a>, <a href="#a0d8e70094baa4fcc5eb68b59de54dc92">mergeRange</a>, <a href="#a0e2f2e4897006cc2a16468e9e99f7b6d">RunCleanup</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#aa816756908e8f79bdcf1b5871e78a9ca">anonymous{AssumeBundleBuilder.cpp}::simplifyAssumes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
