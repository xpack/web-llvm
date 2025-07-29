---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ssaupdaterbulk
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SSAUpdaterBulk` Class

<p>Helper class for SSA formation on a set of values defined in multiple blocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SSAUpdaterBulk { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">llvm/Transforms/Utils/SSAUpdaterBulk.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0037fd27eddece14c36773afcc9e5721">SSAUpdaterBulk</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e216fe4be54f5cd26865e1b25fc982e">SSAUpdaterBulk</a> (const SSAUpdaterBulk &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243fa3bde7c652d41bb2834e71b6d7dd">~SSAUpdaterBulk</a> ()=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk">SSAUpdaterBulk</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1341b52a3332fa3c3b18e575f771fff7">operator=</a> (const SSAUpdaterBulk &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb0a3b834b52c941090bb14e7f33fdf">AddVariable</a> (StringRef Name, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new variable to the SSA rewriter. <a href="#a3cb0a3b834b52c941090bb14e7f33fdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ded14ad5409c193178f8c72201a6cb">AddAvailableValue</a> (unsigned Var, BasicBlock *BB, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that a rewritten value is available in the specified block with the specified value. <a href="#a60ded14ad5409c193178f8c72201a6cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c1eb0b213b4b0f797053144466f06d">AddUse</a> (unsigned Var, Use *U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a use of the symbolic value. <a href="#a95c1eb0b213b4b0f797053144466f06d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60fac14032181eef9fe2f3e790ce9c28">RewriteAllUses</a> (DominatorTree *DT, SmallVectorImpl&lt; PHINode * &gt; *InsertedPHIs=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform all the necessary updates, including new PHI-nodes insertion and the requested uses update. <a href="#a60fac14032181eef9fe2f3e790ce9c28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a6c302a52db861531a36bd5d11a043">computeValueAt</a> (BasicBlock *BB, RewriteInfo &amp;R, DominatorTree *DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; RewriteInfo, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9371f209077da14675a83cb7f3613ffe">Rewrites</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/prediteratorcache">PredIteratorCache</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb1609f560770596dc52bdca3e8b364">PredCache</a></td>
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

<p>Helper class for SSA formation on a set of values defined in multiple blocks.</p>


<p>This is used when code duplication or another unstructured transformation wants to rewrite a set of uses of one value with uses of a set of values. The update is done only when RewriteAllUses is called, all other methods are used for book-keeping. That helps to share some common computations between updates of different uses (which is not the case when traditional <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> is used).</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SSAUpdaterBulk() {#a0037fd27eddece14c36773afcc9e5721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SSAUpdaterBulk::SSAUpdaterBulk ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>.</p>


<p>Referenced by <a href="#a1341b52a3332fa3c3b18e575f771fff7">operator=</a> and <a href="#a8e216fe4be54f5cd26865e1b25fc982e">SSAUpdaterBulk</a>.</p>

</div>
</div>

### SSAUpdaterBulk() {#a8e216fe4be54f5cd26865e1b25fc982e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SSAUpdaterBulk::SSAUpdaterBulk (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk">SSAUpdaterBulk</a> &amp;)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>.</p>


<p>Reference <a href="#a0037fd27eddece14c36773afcc9e5721">SSAUpdaterBulk</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SSAUpdaterBulk() {#a243fa3bde7c652d41bb2834e71b6d7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SSAUpdaterBulk::~SSAUpdaterBulk ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a1341b52a3332fa3c3b18e575f771fff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SSAUpdaterBulk &amp; llvm::SSAUpdaterBulk::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk">SSAUpdaterBulk</a> &amp;)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>.</p>


<p>Reference <a href="#a0037fd27eddece14c36773afcc9e5721">SSAUpdaterBulk</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddAvailableValue() {#a60ded14ad5409c193178f8c72201a6cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdaterBulk::AddAvailableValue (unsigned Var, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that a rewritten value is available in the specified block with the specified value.</p>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp">SSAUpdaterBulk.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### AddUse() {#a95c1eb0b213b4b0f797053144466f06d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdaterBulk::AddUse (unsigned Var, <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a use of the symbolic value.</p>


<p>This use will be updated with a rewritten value when RewriteAllUses is called.</p>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp">SSAUpdaterBulk.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp/#a1cef36d5650485966df368590e5abe4f">getUserBB</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### AddVariable() {#a3cb0a3b834b52c941090bb14e7f33fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SSAUpdaterBulk::AddVariable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a new variable to the SSA rewriter.</p>


<p>This needs to be called before AddAvailableValue or AddUse calls. The return value is the variable <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, which needs to be passed to AddAvailableValue and AddUse.</p>


<p>This needs to be called before AddAvailableValue or AddUse calls.</p>


<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp">SSAUpdaterBulk.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### RewriteAllUses() {#a60fac14032181eef9fe2f3e790ce9c28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAUpdaterBulk::RewriteAllUses (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; * InsertedPHIs=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform all the necessary updates, including new PHI-nodes insertion and the requested uses update.</p>


<p>The function requires dominator tree DT, which is used for computing locations for new phi-nodes insertions. If a nonnull pointer to a vector InsertedPHIs is passed, all the new phi-nodes will be added to this vector.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp">SSAUpdaterBulk.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a714e5448566006046f747d9ec4df8241">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::calculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp/#ab90f4a46f63bfddff132d20866be2da2">ComputeLiveInBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp/#a1cef36d5650485966df368590e5abe4f">getUserBB</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab978072498608d7bd344804926c2a91a">llvm::Value::hasValueHandle</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a53036b9112c1460bcc6692c99e2de636">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::resetLiveInBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a9180c82ceffac7e5586cc2d6f368f996">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::setDefiningBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a8efdd1ea3537e57552087a2767969557">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::setLiveInBlocks</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#abb87e6d5ed7ded2ccd8acac49caf22ab">llvm::ValueHandleBase::ValueIsRAUWd</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeValueAt() {#a52a6c302a52db861531a36bd5d11a043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SSAUpdaterBulk::computeValueAt (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, RewriteInfo &amp; R, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp">SSAUpdaterBulk.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PredCache {#accb1609f560770596dc52bdca3e8b364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredIteratorCache llvm::SSAUpdaterBulk::PredCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>.</p>

</div>
</div>

### Rewrites {#a9371f209077da14675a83cb7f3613ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RewriteInfo, 4&gt; llvm::SSAUpdaterBulk::Rewrites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterbulk-h">SSAUpdaterBulk.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp">SSAUpdaterBulk.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
