---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mergeicmps-cpp-/bcecmpblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BCECmpBlock` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MergeICmps.cpp}::BCECmpBlock { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 8 &gt; <a href="#a630e6993e9c458d245c7a44201a5ac36">InstructionSet</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4283e87062ea62462528f1dfaf8ca8e8">BCECmpBlock</a> (BCECmp Cmp, BasicBlock *BB, InstructionSet BlockInsts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-mergeicmps-cpp-/bceatom">BCEAtom</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a317731d5004b1c8eb7298a7c8e70359e">Lhs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-mergeicmps-cpp-/bceatom">BCEAtom</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d6c807133f0757a515e056b7e169d3">Rhs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59a70d3dcaafa30633424f1d08b6c576">SizeBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad53d4e48b8428fb4ca5dba1303bab869">doesOtherWork</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d5d1fe289a7c92a756ec3d5070cded3">canSplit</a> (AliasAnalysis &amp;AA) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a851916c7b9610597c4339a0d74f8e449">canSinkBCECmpInst</a> (const Instruction *, AliasAnalysis &amp;AA) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6e09a5b9048b42dd46cc648d2b86c4">split</a> (BasicBlock *NewParent, AliasAnalysis &amp;AA) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3441243b590e34dc725da94b4ca4165c">BB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a630e6993e9c458d245c7a44201a5ac36">InstructionSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9e252cf3742d4f44bdc6fd959c7c2d">BlockInsts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d81b75e5387b36bc6ab32f1a8aadf09">RequireSplit</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bbef757d11af498666563e16863f7b2">OrigOrder</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-mergeicmps-cpp-/bcecmp">BCECmp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5470e2b0df67e33659f97544164442b0">Cmp</a></td>
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


<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### InstructionSet {#a630e6993e9c458d245c7a44201a5ac36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallDenseSet&lt;const Instruction *, 8&gt; anonymous{MergeICmps.cpp}::BCECmpBlock::InstructionSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BCECmpBlock() {#a4283e87062ea62462528f1dfaf8ca8e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MergeICmps.cpp}::BCECmpBlock::BCECmpBlock (<a href="/web-llvm/docs/api/structs/anonymous-mergeicmps-cpp-/bcecmp">BCECmp</a> Cmp, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="#a630e6993e9c458d245c7a44201a5ac36">InstructionSet</a> BlockInsts)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<p>References <a href="#a3441243b590e34dc725da94b4ca4165c">BB</a>, <a href="#acd9e252cf3742d4f44bdc6fd959c7c2d">BlockInsts</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a1856fdec0c432794264014d2431101f9">anonymous{MergeICmps.cpp}::visitCmpBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canSinkBCECmpInst() {#a851916c7b9610597c4339a0d74f8e449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MergeICmps.cpp}::BCECmpBlock::canSinkBCECmpInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> &amp; AA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#a784097fca76abad9e815cf1692de79c4">llvm::Instruction::comesBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a728f79528ca8659e15d00c1e6818b316">llvm::isModSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a383175f96316074965ad115706bd49d7">llvm::Instruction::mayWriteToMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>.</p>


<p>Referenced by <a href="#a5d5d1fe289a7c92a756ec3d5070cded3">canSplit</a> and <a href="#afd6e09a5b9048b42dd46cc648d2b86c4">split</a>.</p>

</div>
</div>

### canSplit() {#a5d5d1fe289a7c92a756ec3d5070cded3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MergeICmps.cpp}::BCECmpBlock::canSplit (<a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> &amp; AA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<p>References <a href="#a3441243b590e34dc725da94b4ca4165c">BB</a>, <a href="#acd9e252cf3742d4f44bdc6fd959c7c2d">BlockInsts</a> and <a href="#a851916c7b9610597c4339a0d74f8e449">canSinkBCECmpInst</a>.</p>

</div>
</div>

### doesOtherWork() {#ad53d4e48b8428fb4ca5dba1303bab869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MergeICmps.cpp}::BCECmpBlock::doesOtherWork ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<p>References <a href="#a3441243b590e34dc725da94b4ca4165c">BB</a> and <a href="#acd9e252cf3742d4f44bdc6fd959c7c2d">BlockInsts</a>.</p>

</div>
</div>

### Lhs() {#a317731d5004b1c8eb7298a7c8e70359e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BCEAtom &amp; anonymous{MergeICmps.cpp}::BCECmpBlock::Lhs ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a0618470fa0f71f42d8d104317644e4de">anonymous{MergeICmps.cpp}::areContiguous</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#ab6e0643cf044a7eab7bf5f9ed1d0816e">anonymous{MergeICmps.cpp}::mergeBlocks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#aaa39273101436002f3e3bd16293327be">anonymous{MergeICmps.cpp}::visitICmp</a>.</p>

</div>
</div>

### Rhs() {#af3d6c807133f0757a515e056b7e169d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BCEAtom &amp; anonymous{MergeICmps.cpp}::BCECmpBlock::Rhs ()</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a0618470fa0f71f42d8d104317644e4de">anonymous{MergeICmps.cpp}::areContiguous</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#ab6e0643cf044a7eab7bf5f9ed1d0816e">anonymous{MergeICmps.cpp}::mergeBlocks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#aaa39273101436002f3e3bd16293327be">anonymous{MergeICmps.cpp}::visitICmp</a>.</p>

</div>
</div>

### SizeBits() {#a59a70d3dcaafa30633424f1d08b6c576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{MergeICmps.cpp}::BCECmpBlock::SizeBits ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>

</div>
</div>

### split() {#afd6e09a5b9048b42dd46cc648d2b86c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MergeICmps.cpp}::BCECmpBlock::split (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewParent, <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> &amp; AA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3441243b590e34dc725da94b4ca4165c">BB</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#acd9e252cf3742d4f44bdc6fd959c7c2d">BlockInsts</a>, <a href="#a851916c7b9610597c4339a0d74f8e449">canSinkBCECmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BB {#a3441243b590e34dc725da94b4ca4165c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{MergeICmps.cpp}::BCECmpBlock::BB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<p>Referenced by <a href="#a4283e87062ea62462528f1dfaf8ca8e8">BCECmpBlock</a>, <a href="#a5d5d1fe289a7c92a756ec3d5070cded3">canSplit</a>, <a href="#ad53d4e48b8428fb4ca5dba1303bab869">doesOtherWork</a> and <a href="#afd6e09a5b9048b42dd46cc648d2b86c4">split</a>.</p>

</div>
</div>

### BlockInsts {#acd9e252cf3742d4f44bdc6fd959c7c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSet anonymous{MergeICmps.cpp}::BCECmpBlock::BlockInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>


<p>Referenced by <a href="#a4283e87062ea62462528f1dfaf8ca8e8">BCECmpBlock</a>, <a href="#a5d5d1fe289a7c92a756ec3d5070cded3">canSplit</a>, <a href="#ad53d4e48b8428fb4ca5dba1303bab869">doesOtherWork</a> and <a href="#afd6e09a5b9048b42dd46cc648d2b86c4">split</a>.</p>

</div>
</div>

### OrigOrder {#a0bbef757d11af498666563e16863f7b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MergeICmps.cpp}::BCECmpBlock::OrigOrder = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>

</div>
</div>

### RequireSplit {#a6d81b75e5387b36bc6ab32f1a8aadf09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MergeICmps.cpp}::BCECmpBlock::RequireSplit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Cmp {#a5470e2b0df67e33659f97544164442b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BCECmp anonymous{MergeICmps.cpp}::BCECmpBlock::Cmp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp">MergeICmps.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
