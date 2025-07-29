---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcarc/bundledretainclaimrvs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BundledRetainClaimRVs` Class



## Declaration

<div class="doxyDeclaration">
class llvm::objcarc::BundledRetainClaimRVs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">Transforms/ObjCARC/ObjCARC.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd129bf38f210aa4cd4fd8f88a2c6ff">BundledRetainClaimRVs</a> (bool ContractPass)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f65b06080f99f68ed35a34fd759cf2">~BundledRetainClaimRVs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fdb3ab3875b4306157d47d84e972405">insertAfterInvokes</a> (Function &amp;F, DominatorTree *DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a retainRV/claimRV call to the normal destination blocks of invokes with operand bundle "clang.arc.attachedcall". <a href="#a8fdb3ab3875b4306157d47d84e972405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38ccd8095fd94c6ed2cd2bd5b52082a">insertRVCall</a> (BasicBlock::iterator InsertPt, CallBase *AnnotatedCall)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a retainRV/claimRV call. <a href="#ac38ccd8095fd94c6ed2cd2bd5b52082a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05a8bebb48f20e6824a961af831314c">insertRVCallWithColors</a> (BasicBlock::iterator InsertPt, CallBase *AnnotatedCall, const DenseMap&lt; BasicBlock *, ColorVector &gt; &amp;BlockColors)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a retainRV/claimRV call with colors. <a href="#af05a8bebb48f20e6824a961af831314c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a3a24ed0274c01b34ef418b446bbfd8">contains</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if an instruction is a bundled retainRV/claimRV call. <a href="#a2a3a24ed0274c01b34ef418b446bbfd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32a933965ba0059ff2a3a322cc8b40b">eraseInst</a> (CallInst *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a retainRV/claimRV call entirely. <a href="#ad32a933965ba0059ff2a3a322cc8b40b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8714461b0d7449b6985ae95f59f42ef8">RVCalls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map of inserted retainRV/claimRV calls to annotated calls/invokes. <a href="#a8714461b0d7449b6985ae95f59f42ef8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1207e61f51c47284c4d63c07701a9d9">ContractPass</a></td>
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


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BundledRetainClaimRVs() {#adbd129bf38f210aa4cd4fd8f88a2c6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcarc::BundledRetainClaimRVs::BundledRetainClaimRVs (bool ContractPass)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BundledRetainClaimRVs() {#af0f65b06080f99f68ed35a34fd759cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BundledRetainClaimRVs::~BundledRetainClaimRVs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-cpp">ObjCARC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af4e05bf48a81b884e707efa650560fbf">llvm::objcarc::EraseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aefa876f2a1fd3dd74831f85634cb14b72fe">llvm::CallInst::TCK_NoTail</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### contains() {#a2a3a24ed0274c01b34ef418b446bbfd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::BundledRetainClaimRVs::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>See if an instruction is a bundled retainRV/claimRV call.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#acf48e56d2e2614373b53f03c5bd3c4b8">llvm::objcarc::TopDownPtrState::HandlePotentialAlterRefCount</a>.</p>

</div>
</div>

### eraseInst() {#ad32a933965ba0059ff2a3a322cc8b40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::BundledRetainClaimRVs::eraseInst (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
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

<p>Remove a retainRV/claimRV call entirely.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af4e05bf48a81b884e707efa650560fbf">llvm::objcarc::EraseInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac62778065b99372cc62cf994b967e7e8">llvm::CallBase::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca6c03d5e52bbdefc8c392e3ed77c7d6a1">llvm::LLVMContext::OB_clang_arc_attachedcall</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad82786d29c116d0bf5131f654d51e681">llvm::CallBase::removeOperandBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2a8f9bfe9d1345237cb3b2b205864da075">llvm::objcarc::User</a>.</p>

</div>
</div>

### insertAfterInvokes() {#a8fdb3ab3875b4306157d47d84e972405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, bool &gt; BundledRetainClaimRVs::insertAfterInvokes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a retainRV/claimRV call to the normal destination blocks of invokes with operand bundle "clang.arc.attachedcall".</p>


<p>If the edge to the normal destination block is a critical edge, split it.</p>


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-cpp">ObjCARC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aefba9af2f61452f20f4c947b4c2e5f4e">llvm::objcarc::hasAttachedCallOpBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac38ccd8095fd94c6ed2cd2bd5b52082a">insertRVCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab61955a622d233750894890e0704da5c">llvm::SplitCriticalEdge</a>.</p>

</div>
</div>

### insertRVCall() {#ac38ccd8095fd94c6ed2cd2bd5b52082a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * BundledRetainClaimRVs::insertRVCall (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPt, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * AnnotatedCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a retainRV/claimRV call.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-cpp">ObjCARC.cpp</a>.</p>


<p>Reference <a href="#af05a8bebb48f20e6824a961af831314c">insertRVCallWithColors</a>.</p>


<p>Referenced by <a href="#a8fdb3ab3875b4306157d47d84e972405">insertAfterInvokes</a>.</p>

</div>
</div>

### insertRVCallWithColors() {#af05a8bebb48f20e6824a961af831314c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * BundledRetainClaimRVs::insertRVCallWithColors (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPt, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * AnnotatedCall, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#ac16c24df0637600996c9c6081da170a2">ColorVector</a> &gt; &amp; BlockColors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a retainRV/claimRV call with colors.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-cpp">ObjCARC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2ac3755e61202abd74da5885d2e9c9160e">llvm::objcarc::Call</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a6be998a03774a37c14d7077897b53bc9">llvm::objcarc::createCallInstWithColors</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aaa634580f5cb9e54209fa554bf8fb388">llvm::objcarc::getAttachedARCFunction</a>.</p>


<p>Referenced by <a href="#ac38ccd8095fd94c6ed2cd2bd5b52082a">insertRVCall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ContractPass {#aa1207e61f51c47284c4d63c07701a9d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::BundledRetainClaimRVs::ContractPass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>.</p>

</div>
</div>

### RVCalls {#a8714461b0d7449b6985ae95f59f42ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;CallInst *, CallBase *&gt; llvm::objcarc::BundledRetainClaimRVs::RVCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map of inserted retainRV/claimRV calls to annotated calls/invokes.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-cpp">ObjCARC.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
