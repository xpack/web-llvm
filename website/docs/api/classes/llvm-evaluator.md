---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/evaluator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Evaluator` Class

<p>This class evaluates LLVM IR, producing the <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> representing each SSA instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Evaluator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">llvm/Transforms/Utils/Evaluator.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd0baac1d20f5c48a97298fcfd50b45">Evaluator</a> (const DataLayout &amp;DL, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d431d84dba96db2c8359cf0deb5b09">~Evaluator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9fd94c18d93885c8d947121ab9721e">EvaluateFunction</a> (Function *F, Constant *&amp;RetVal, const SmallVectorImpl&lt; Constant * &gt; &amp;ActualArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Evaluate a call to function F, returning true if successful, false if we can't evaluate it. <a href="#aac9fd94c18d93885c8d947121ab9721e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7453e86423554598c4bc680679ad6287">getMutatedInitializers</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb90b074529faf1b1a1e29b7845aecd5">getInvariants</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff865cf80810ece1fc1ac6b6f441d0f">EvaluateBlock</a> (BasicBlock::iterator CurInst, BasicBlock *&amp;NextBB, bool &amp;StrippedPointerCastsForAliasAnalysis)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Evaluate all instructions in block BB, returning true if successful, false if we can't evaluate it. <a href="#a0ff865cf80810ece1fc1ac6b6f441d0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a270a530536c18d468985de32c0748efa">getVal</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36b45b1bb516b407f8935aa3a759976">setVal</a> (Value *V, Constant *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87731d4165211697a455c22bf578f41">getCalleeWithFormalArgs</a> (CallBase &amp;CB, SmallVectorImpl&lt; Constant * &gt; &amp;Formals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given call site return callee and list of its formal arguments. <a href="#ae87731d4165211697a455c22bf578f41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9732e8bd22ba7697913478e5c4e0a1e6">getFormalParams</a> (CallBase &amp;CB, Function *F, SmallVectorImpl&lt; Constant * &gt; &amp;Formals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given call site and callee returns list of callee formal argument values converting them when necessary. <a href="#a9732e8bd22ba7697913478e5c4e0a1e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630d36e0e7914f76fb50ffea270c0f17">ComputeLoadResult</a> (Constant *P, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value that would be computed by a load from P after the stores reflected by 'memory' have been performed. <a href="#a630d36e0e7914f76fb50ffea270c0f17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8523de4461819020570b63841f49e285">ComputeLoadResult</a> (GlobalVariable *GV, Type *Ty, const APInt &amp;Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad22579def00e85bded7c488b1bf2dca6">ValueStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>As we compute SSA register values, we store their contents here. <a href="#ad22579def00e85bded7c488b1bf2dca6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d047bd13669c2be48d2d0dd4d935db">CallStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used to detect recursion. <a href="#ae8d047bd13669c2be48d2d0dd4d935db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, MutableValue &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d5c99417bea0871158771d8edc53179">MutatedMemory</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each store we execute, we update this map. <a href="#a8d5c99417bea0871158771d8edc53179">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &gt;, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ecc9abb3893c078b52a38a02bbc89ec">AllocaTmps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To 'execute' an alloca, we create a temporary global variable to represent its body. <a href="#a4ecc9abb3893c078b52a38a02bbc89ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97405bcb3df302911109a020c03e1cf1">Invariants</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These global variables have been marked invariant by the static constructor. <a href="#a97405bcb3df302911109a020c03e1cf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8fd5ca21fee42283727b7d7a26b0cc">SimpleConstants</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These are constants we have checked and know to be simple enough to live in a static initializer of a global. <a href="#ade8fd5ca21fee42283727b7d7a26b0cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26e9e4813f12cda0021e9295bc9df89">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6a0c93afa787eab56f42a471d7ebe2">TLI</a></td>
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

<p>This class evaluates LLVM IR, producing the <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> representing each SSA instruction.</p>


<p>Changes to global variables are stored in a mapping that can be iterated over after the evaluation is complete. Once an evaluation call fails, the evaluation object should not be reused.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Evaluator() {#afbd0baac1d20f5c48a97298fcfd50b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Evaluator::Evaluator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Evaluator() {#af4d431d84dba96db2c8359cf0deb5b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Evaluator::~Evaluator ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EvaluateFunction() {#aac9fd94c18d93885c8d947121ab9721e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Evaluator::EvaluateFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&amp; RetVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; ActualArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Evaluate a call to function F, returning true if successful, false if we can't evaluate it.</p>


<p>ActualArgs contains the formal arguments for the function.</p>


<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp">Evaluator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/returninst/#a6c2dee0852138a5cb8a4fef5883db9ec">llvm::ReturnInst::getReturnValue</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#abf4eceb96c86c97477d4bcf8eec661e5">EvaluateStaticConstructor</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a37fe954e0b01502acccf9b29943e9164">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryEvaluateFunctionsWithArgs</a>.</p>

</div>
</div>

### getInvariants() {#adb90b074529faf1b1a1e29b7845aecd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallPtrSetImpl&lt; GlobalVariable * &gt; &amp; llvm::Evaluator::getInvariants ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#abf4eceb96c86c97477d4bcf8eec661e5">EvaluateStaticConstructor</a>.</p>

</div>
</div>

### getMutatedInitializers() {#a7453e86423554598c4bc680679ad6287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; GlobalVariable *, Constant * &gt; llvm::Evaluator::getMutatedInitializers ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#abf4eceb96c86c97477d4bcf8eec661e5">EvaluateStaticConstructor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ComputeLoadResult() {#a630d36e0e7914f76fb50ffea270c0f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * Evaluator::ComputeLoadResult (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * P, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the value that would be computed by a load from P after the stores reflected by 'memory' have been performed.</p>


<p>If we can't decide, return null.</p>


<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp">Evaluator.cpp</a>.</p>

</div>
</div>

### ComputeLoadResult() {#a8523de4461819020570b63841f49e285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * Evaluator::ComputeLoadResult (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp">Evaluator.cpp</a>.</p>

</div>
</div>

### EvaluateBlock() {#a0ff865cf80810ece1fc1ac6b6f441d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Evaluator::EvaluateBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> CurInst, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; NextBB, bool &amp; StrippedPointerCastsForAliasAnalysis)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Evaluate all instructions in block BB, returning true if successful, false if we can't evaluate it.</p>


<p>NewBB returns the next BB that control flows into, or null upon return. StrippedPointerCastsForAliasAnalysis is set to true if we looked through pointer casts to evaluate something.</p>


<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp">Evaluator.cpp</a>.</p>

</div>
</div>

### getCalleeWithFormalArgs() {#ae87731d4165211697a455c22bf578f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * Evaluator::getCalleeWithFormalArgs (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; Formals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given call site return callee and list of its formal arguments.</p>

<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp">Evaluator.cpp</a>.</p>

</div>
</div>

### getFormalParams() {#a9732e8bd22ba7697913478e5c4e0a1e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Evaluator::getFormalParams (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; Formals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given call site and callee returns list of callee formal argument values converting them when necessary.</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp">Evaluator.cpp</a>.</p>

</div>
</div>

### getVal() {#a270a530536c18d468985de32c0748efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::Evaluator::getVal (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

### setVal() {#af36b45b1bb516b407f8935aa3a759976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Evaluator::setVal (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllocaTmps {#a4ecc9abb3893c078b52a38a02bbc89ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;GlobalVariable&gt;, 32&gt; llvm::Evaluator::AllocaTmps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>To 'execute' an alloca, we create a temporary global variable to represent its body.</p>


<p>This vector is needed so we can delete the temporary globals when we are done.</p>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

### CallStack {#ae8d047bd13669c2be48d2d0dd4d935db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Function*, 4&gt; llvm::Evaluator::CallStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is used to detect recursion.</p>


<p>In pathological situations we could hit exponential behavior, but at least there is nothing unbounded.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

### DL {#ac26e9e4813f12cda0021e9295bc9df89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::Evaluator::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

### Invariants {#a97405bcb3df302911109a020c03e1cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;GlobalVariable*, 8&gt; llvm::Evaluator::Invariants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These global variables have been marked invariant by the static constructor.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

### MutatedMemory {#a8d5c99417bea0871158771d8edc53179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;GlobalVariable *, MutableValue&gt; llvm::Evaluator::MutatedMemory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For each store we execute, we update this map.</p>


<p>Loads check this to get the most up-to-date value. If evaluation is successful, this state is committed to the process.</p>


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

### SimpleConstants {#ade8fd5ca21fee42283727b7d7a26b0cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Constant*, 8&gt; llvm::Evaluator::SimpleConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These are constants we have checked and know to be simple enough to live in a static initializer of a global.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

### TLI {#a9c6a0c93afa787eab56f42a471d7ebe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::Evaluator::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

### ValueStack {#ad22579def00e85bded7c488b1bf2dca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;DenseMap&lt;Value*, Constant*&gt; &gt; llvm::Evaluator::ValueStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>As we compute SSA register values, we store their contents here.</p>


<p>The back of the deque contains the current function and the stack contains the values in the calling frames.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/evaluator-h">Evaluator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp">Evaluator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
