---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/irbuilder-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `IRBuilder.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/nofolder-h">llvm/IR/NoFolder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">llvm/IR/Statepoint.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;optional&gt;
#include &lt;vector&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d0940bf47d81928d84178e2731a5c3">isConstantOne</a> (const Value *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isConstantOne - Return true only if val is constant int 1 <a href="#a22d0940bf47d81928d84178e2731a5c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36cf33ef120f4b9706471a89271dcfb5">getAlign</a> (Value *Ptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T0&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d755165fee4597d8598f64188cd8efe">getStatepointArgs</a> (IRBuilderBase &amp;B, uint64_t ID, uint32_t NumPatchBytes, Value *ActualCallee, uint32_t Flags, ArrayRef&lt; T0 &gt; CallArgs) -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, typename T3&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5ed1225be79d7074b85402de2dc1f686">getStatepointBundles</a> (std::optional&lt; ArrayRef&lt; T1 &gt; &gt; TransitionArgs, std::optional&lt; ArrayRef&lt; T2 &gt; &gt; DeoptArgs, ArrayRef&lt; T3 &gt; GCArgs) -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T0, typename T1, typename T2, typename T3&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35929b5ae2c67d8c86640518636092ae">CreateGCStatepointCallCommon</a> (IRBuilderBase *Builder, uint64_t ID, uint32_t NumPatchBytes, FunctionCallee ActualCallee, uint32_t Flags, ArrayRef&lt; T0 &gt; CallArgs, std::optional&lt; ArrayRef&lt; T1 &gt; &gt; TransitionArgs, std::optional&lt; ArrayRef&lt; T2 &gt; &gt; DeoptArgs, ArrayRef&lt; T3 &gt; GCArgs, const Twine &amp;Name)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T0, typename T1, typename T2, typename T3&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2f89404be2430701edb3e9827aaab276">CreateGCStatepointInvokeCommon</a> (IRBuilderBase *Builder, uint64_t ID, uint32_t NumPatchBytes, FunctionCallee ActualInvokee, BasicBlock *NormalDest, BasicBlock *UnwindDest, uint32_t Flags, ArrayRef&lt; T0 &gt; InvokeArgs, std::optional&lt; ArrayRef&lt; T1 &gt; &gt; TransitionArgs, std::optional&lt; ArrayRef&lt; T2 &gt; &gt; DeoptArgs, ArrayRef&lt; T3 &gt; GCArgs, const Twine &amp;Name)</td>
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

### CreateGCStatepointCallCommon() {#a35929b5ae2c67d8c86640518636092ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0, typename T1, typename T2, typename T3&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * CreateGCStatepointCallCommon (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> * Builder, uint64_t ID, uint32_t NumPatchBytes, <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> ActualCallee, uint32_t Flags, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T0 &gt; CallArgs, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &gt; &gt; TransitionArgs, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T2 &gt; &gt; DeoptArgs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T3 &gt; GCArgs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
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



<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp">IRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#a6272287f036b912f12c0270607cec675">llvm::FunctionCallee::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="#a9d755165fee4597d8598f64188cd8efe">getStatepointArgs</a>, <a href="#a5ed1225be79d7074b85402de2dc1f686">getStatepointBundles</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4c4140d787f9bc61bcbdf2609dc2d59e">llvm::IRBuilderBase::CreateGCStatepointCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2e1b793dbe7d7a63449ee06ffa01b644">llvm::IRBuilderBase::CreateGCStatepointCall</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a21540d7bc0618c279b134f034c498323">llvm::IRBuilderBase::CreateGCStatepointCall</a>.</p>

</div>
</div>

### CreateGCStatepointInvokeCommon() {#a2f89404be2430701edb3e9827aaab276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0, typename T1, typename T2, typename T3&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InvokeInst * CreateGCStatepointInvokeCommon (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> * Builder, uint64_t ID, uint32_t NumPatchBytes, <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> ActualInvokee, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NormalDest, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * UnwindDest, uint32_t Flags, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T0 &gt; InvokeArgs, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &gt; &gt; TransitionArgs, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T2 &gt; &gt; DeoptArgs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T3 &gt; GCArgs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
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



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp">IRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49c408a438b1844778bc59b1e4bb00c9">llvm::IRBuilderBase::CreateInvoke</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#a6272287f036b912f12c0270607cec675">llvm::FunctionCallee::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="#a9d755165fee4597d8598f64188cd8efe">getStatepointArgs</a>, <a href="#a5ed1225be79d7074b85402de2dc1f686">getStatepointBundles</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#adef9b5612fa5121cb6b1c53c7682c078">llvm::IRBuilderBase::CreateGCStatepointInvoke</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad6dd41fc123ba539f522a1a8ee760f9a">llvm::IRBuilderBase::CreateGCStatepointInvoke</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7dd089d2ef56e3e32220cb28eaf5a897">llvm::IRBuilderBase::CreateGCStatepointInvoke</a>.</p>

</div>
</div>

### getAlign() {#a36cf33ef120f4b9706471a89271dcfb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign getAlign (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr)</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp">IRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#ace794781892b542579c58d6eade3dba3">foldPatternedLoads</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp/#a36f341897beb949904185df801dcc02a">needsConstrainedOpcode</a>.</p>

</div>
</div>

### getStatepointArgs() {#a9d755165fee4597d8598f64188cd8efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Value * &gt; getStatepointArgs (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, uint64_t ID, uint32_t NumPatchBytes, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ActualCallee, uint32_t Flags, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T0 &gt; CallArgs)</td>
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



<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp">IRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a35929b5ae2c67d8c86640518636092ae">CreateGCStatepointCallCommon</a> and <a href="#a2f89404be2430701edb3e9827aaab276">CreateGCStatepointInvokeCommon</a>.</p>

</div>
</div>

### getStatepointBundles() {#a5ed1225be79d7074b85402de2dc1f686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, typename T3&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; OperandBundleDef &gt; getStatepointBundles (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &gt; &gt; TransitionArgs, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T2 &gt; &gt; DeoptArgs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T3 &gt; GCArgs)</td>
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



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp">IRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a35929b5ae2c67d8c86640518636092ae">CreateGCStatepointCallCommon</a> and <a href="#a2f89404be2430701edb3e9827aaab276">CreateGCStatepointInvokeCommon</a>.</p>

</div>
</div>

### isConstantOne() {#a22d0940bf47d81928d84178e2731a5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstantOne (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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

<p>isConstantOne - Return true only if val is constant int 1</p>

<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp">IRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/constantint/#a244bfbe5aae876e56cf5e62f0f27867a">llvm::ConstantInt::isOne</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a792b08a6322bb539ee5ce2f754588c8c">llvm::IRBuilderBase::CreateMalloc</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
