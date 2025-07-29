---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/intrinsiclowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `IntrinsicLowering.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/intrinsiclowering-h">llvm/CodeGen/IntrinsicLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ArgIt&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a97741acf9b0e38ab508c939d99e53767">ReplaceCallWith</a> (const char *NewFn, CallInst *CI, ArgIt ArgBegin, ArgIt ArgEnd, Type *RetTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is used when we want to lower an intrinsic call to a call of an external function. <a href="#a97741acf9b0e38ab508c939d99e53767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17ec2410c8a9129558c2344614bf487">LowerBSWAP</a> (LLVMContext &amp;Context, Value *V, Instruction *IP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the code to lower bswap of V before the specified instruction IP. <a href="#af17ec2410c8a9129558c2344614bf487">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8fbcac63ba4f738ae2de92a195becc">LowerCTPOP</a> (LLVMContext &amp;Context, Value *V, Instruction *IP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the code to lower ctpop of V before the specified instruction IP. <a href="#ade8fbcac63ba4f738ae2de92a195becc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb735150a3d034d431651b14209c867">LowerCTLZ</a> (LLVMContext &amp;Context, Value *V, Instruction *IP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the code to lower ctlz of V before the specified instruction IP. <a href="#a3eb735150a3d034d431651b14209c867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a> (CallInst *CI, const char *Fname, const char *Dname, const char *LDname)</td>
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

## Functions

### LowerBSWAP() {#af17ec2410c8a9129558c2344614bf487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LowerBSWAP (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IP)</td>
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

<p>Emit the code to lower bswap of V before the specified instruction IP.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp">IntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>.</p>

</div>
</div>

### LowerCTLZ() {#a3eb735150a3d034d431651b14209c867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LowerCTLZ (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IP)</td>
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

<p>Emit the code to lower ctlz of V before the specified instruction IP.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp">IntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a> and <a href="#ade8fbcac63ba4f738ae2de92a195becc">LowerCTPOP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a3d437e0047c2e5a049151f46d9dd2d09">llvm::X86TargetLowering::LowerOperation</a>.</p>

</div>
</div>

### LowerCTPOP() {#ade8fbcac63ba4f738ae2de92a195becc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LowerCTPOP (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IP)</td>
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

<p>Emit the code to lower ctpop of V before the specified instruction IP.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp">IntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a3eb735150a3d034d431651b14209c867">LowerCTLZ</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a69482bf1572254076b1544aecb6fd46e">llvm::ARMTargetLowering::LowerOperation</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a3d437e0047c2e5a049151f46d9dd2d09">llvm::X86TargetLowering::LowerOperation</a>.</p>

</div>
</div>

### ReplaceCallWith() {#a97741acf9b0e38ab508c939d99e53767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ArgIt&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * ReplaceCallWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * NewFn, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, ArgIt ArgBegin, ArgIt ArgEnd, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
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

<p>This function is used when we want to lower an intrinsic call to a call of an external function.</p>


<p>This handles hard cases such as when there was already a prototype for the external function, but that prototype doesn't match the arguments we expect to pass in.</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp">IntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a> and <a href="#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a>.</p>

</div>
</div>

### ReplaceFPIntrinsicWithCall() {#a6341f4b0dd74acf5c862050cb99221d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReplaceFPIntrinsicWithCall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Fname, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Dname, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LDname)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp">IntrinsicLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4fb513d744ca72275932b2c7003f16f6">llvm::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc">llvm::Type::FP128TyID</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acb145f988329d1d621f73abcafea21d8">llvm::Type::getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48">llvm::Type::PPC_FP128TyID</a>, <a href="#a97741acf9b0e38ab508c939d99e53767">ReplaceCallWith</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">llvm::Type::X86_FP80TyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
