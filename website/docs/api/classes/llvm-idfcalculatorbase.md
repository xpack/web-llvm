---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/idfcalculatorbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IDFCalculatorBase` Class Template Reference

<p>Determine the iterated dominance frontier, given a set of defining blocks, and optionally, a set of live-in blocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class NodeTy, bool IsPostDom&gt;
class llvm::IDFCalculatorBase&lt;NodeTy, IsPostDom&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">llvm/Support/GenericIteratedDominanceFrontier.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac2ed31d022ad67adcc89f805daeefba0">OrderedNodeTy</a> = std::conditional_t&lt; IsPostDom, <a href="/web-llvm/docs/api/structs/llvm/inverse">Inverse</a>&lt; NodeTy * &gt;, NodeTy * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad53b6924f735860e99160efbe46fc23f">ChildrenGetterTy</a> = <a href="/web-llvm/docs/api/structs/llvm/idfcalculatordetail/childrengetterty">IDFCalculatorDetail::ChildrenGetterTy</a>&lt; NodeTy, IsPostDom &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a17f7f46d9b71bafb1990791ab2a6d66f">IDFCalculatorBase</a> (DominatorTreeBase&lt; NodeTy, IsPostDom &gt; &amp;DT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a92c8ade53963309b97f3dcee88c91458">IDFCalculatorBase</a> (DominatorTreeBase&lt; NodeTy, IsPostDom &gt; &amp;DT, const ChildrenGetterTy &amp;C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9180c82ceffac7e5586cc2d6f368f996">setDefiningBlocks</a> (const SmallPtrSetImpl&lt; NodeTy * &gt; &amp;Blocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Give the IDF calculator the set of blocks in which the value is defined. <a href="#a9180c82ceffac7e5586cc2d6f368f996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8efdd1ea3537e57552087a2767969557">setLiveInBlocks</a> (const SmallPtrSetImpl&lt; NodeTy * &gt; &amp;Blocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Give the IDF calculator the set of blocks in which the value is live on entry to the block. <a href="#a8efdd1ea3537e57552087a2767969557">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a53036b9112c1460bcc6692c99e2de636">resetLiveInBlocks</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the live-in block set to be empty, and tell the IDF calculator to not use liveness anymore. <a href="#a53036b9112c1460bcc6692c99e2de636">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a714e5448566006046f747d9ec4df8241">calculate</a> (SmallVectorImpl&lt; NodeTy * &gt; &amp;IDFBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate iterated dominance frontiers. <a href="#a714e5448566006046f747d9ec4df8241">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; NodeTy, IsPostDom &gt; &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6bcfe55eeefc0c95af5ed0f8e1381c7b">DT</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad53b6924f735860e99160efbe46fc23f">ChildrenGetterTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbf05b35764b1470f0c46a36330c4009">ChildrenGetter</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a92a9bdca5057281105d82256cc2a8608">useLiveIn</a> = false</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; NodeTy * &gt; *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2de1e6d8104cba725ff1fa5caf5b3576">LiveInBlocks</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; NodeTy * &gt; *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0197e065ccd3ee35ba692332ad809e5e">DefBlocks</a></td>
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

<p>Determine the iterated dominance frontier, given a set of defining blocks, and optionally, a set of live-in blocks.</p>


<p>In turn, the results can be used to place phi nodes.</p>


<p>This algorithm is a linear time computation of Iterated Dominance Frontiers, pruned using the live-in set. By default, liveness is not used to prune the IDF computation. The template parameters should be of a CFG block type.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ChildrenGetterTy {#ad53b6924f735860e99160efbe46fc23f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::ChildrenGetterTy = 
      IDFCalculatorDetail::ChildrenGetterTy&lt;NodeTy, IsPostDom&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### OrderedNodeTy {#ac2ed31d022ad67adcc89f805daeefba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::OrderedNodeTy = 
      std::conditional_t&lt;IsPostDom, Inverse&lt;NodeTy *&gt;, NodeTy *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IDFCalculatorBase() {#a17f7f46d9b71bafb1990791ab2a6d66f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::IDFCalculatorBase (<a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; NodeTy, IsPostDom &gt; &amp; DT)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### IDFCalculatorBase() {#a92c8ade53963309b97f3dcee88c91458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::IDFCalculatorBase (<a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; NodeTy, IsPostDom &gt; &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad53b6924f735860e99160efbe46fc23f">ChildrenGetterTy</a> &amp; C)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### calculate() {#a714e5448566006046f747d9ec4df8241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::calculate (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; NodeTy * &gt; &amp; IDFBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate iterated dominance frontiers.</p>


<p>This uses the linear-time phi algorithm based on DJ-graphs mentioned in the file-level comment. It performs DF-&gt;IDF pruning using the live-in set, to avoid computing the IDF for blocks where an inserted PHI node would be dead.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a718717ee958956ec34ed177ef0b7f2ba">llvm::DomTreeNodeBase&lt; NodeT &gt;::getDFSNumIn</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#ab73bfd7dc4d5a446db965380e340810e">llvm::DomTreeNodeBase&lt; NodeT &gt;::getLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#ae6450915b4be60dae8a3c11dc8fc95dc">llvm::SmallPtrSetImplBase::reserve</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a21fc5eae685ef3e2dce4403a75d5ff2f">llvm::MemorySSAUpdater::insertDef</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a60fac14032181eef9fe2f3e790ce9c28">llvm::SSAUpdaterBulk::RewriteAllUses</a> and <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>.</p>

</div>
</div>

### resetLiveInBlocks() {#a53036b9112c1460bcc6692c99e2de636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::resetLiveInBlocks ()</td>
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

<p>Reset the live-in block set to be empty, and tell the IDF calculator to not use liveness anymore.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a60fac14032181eef9fe2f3e790ce9c28">llvm::SSAUpdaterBulk::RewriteAllUses</a>.</p>

</div>
</div>

### setDefiningBlocks() {#a9180c82ceffac7e5586cc2d6f368f996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::setDefiningBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; NodeTy * &gt; &amp; Blocks)</td>
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

<p>Give the IDF calculator the set of blocks in which the value is defined.</p>


<p>This is equivalent to the set of starting blocks it should be calculating the IDF for (though later gets pruned based on liveness).</p>


<p>Note: This set <em>must</em> live for the entire lifetime of the IDF calculator.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a21fc5eae685ef3e2dce4403a75d5ff2f">llvm::MemorySSAUpdater::insertDef</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a60fac14032181eef9fe2f3e790ce9c28">llvm::SSAUpdaterBulk::RewriteAllUses</a> and <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>.</p>

</div>
</div>

### setLiveInBlocks() {#a8efdd1ea3537e57552087a2767969557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::setLiveInBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; NodeTy * &gt; &amp; Blocks)</td>
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

<p>Give the IDF calculator the set of blocks in which the value is live on entry to the block.</p>


<p>This is used to prune the IDF calculation to not include blocks where any phi insertion would be dead.</p>


<p>Note: This set <em>must</em> live for the entire lifetime of the IDF calculator.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a60fac14032181eef9fe2f3e790ce9c28">llvm::SSAUpdaterBulk::RewriteAllUses</a> and <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ChildrenGetter {#afbf05b35764b1470f0c46a36330c4009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildrenGetterTy llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::ChildrenGetter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### DefBlocks {#a0197e065ccd3ee35ba692332ad809e5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallPtrSetImpl&lt;NodeTy *&gt;* llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::DefBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### DT {#a6bcfe55eeefc0c95af5ed0f8e1381c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTreeBase&lt;NodeTy, IsPostDom&gt;&amp; llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### LiveInBlocks {#a2de1e6d8104cba725ff1fa5caf5b3576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallPtrSetImpl&lt;NodeTy *&gt;* llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::LiveInBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### useLiveIn {#a92a9bdca5057281105d82256cc2a8608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::useLiveIn = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
